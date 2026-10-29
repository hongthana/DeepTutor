# Contributor guide

This guide explains how the repository fits together, how to choose a safe first change, and where to verify it. It describes the source tree at **DeepTutor 1.7.0** (`deeptutor/__version__.py`; research snapshot `1ea7df155447f4caf0e3abc86b3ff5395479cd4a`). Branches and open discussions can move; check GitHub and the actual checkout before acting.

For installation and credentials, use [Agent Setup](AGENT_SETUP.md). For the canonical architecture and source owners, use [Architecture](ARCHITECTURE.md). For exact tests, use [Testing](TESTING.md). The [dated source index](research/2026-10-29/source-index.md), [issue index](research/2026-10-29/issues.md), and [PR metadata index](research/2026-10-29/pull-requests.md) make the broader research traceable.

## What the project does

DeepTutor is a learning application that can answer in chat, work from a learner's files and knowledge bases, run guided multi-step learning flows, and expose the same turn engine through a Web app, CLI, WebSocket API, and Python SDK. The runtime can be extended with modules and plugins. This means a change that appears local can affect more than one entry point: a tool may be mounted differently by a capability, API clients consume a shared event protocol, and optional modules can be absent at runtime.

The most useful mental model is a **durable turn**. An entry point normalizes a request and submits it to `TurnApplicationService`. The service coordinates persistence and replay. `TurnEngine` and `ChatOrchestrator` route a `UnifiedContext` to a capability; the capability uses registered tools and emits a shared result envelope. A per-turn `StreamBus` carries events to persistence and adapters. Separate progress streams exist for long-running indexing work; do not assume they have the same lifecycle as chat events.

### Research purpose and maintainer direction

The [project paper](https://arxiv.org/abs/2604.26962v3) describes citation-grounded tutoring, question generation, and adaptation through learner memory. Its benchmark claims belong to that paper and evaluated system version; they are not a validation of this checkout. [Issue #1916](https://github.com/HKUDS/DeepTutor/issues/1916) asks for the TutorBench data, simulator/judge tooling, redistribution terms and the matching code version; it was open with no comments in this snapshot. Treat reproducing the paper as a separate research contribution whose artifacts and licensing need confirmation.

Start larger proposals at the maintainer’s [roadmap #498](https://github.com/HKUDS/DeepTutor/issues/498), updated 2026-10-28. Its 1.7.x checklist names desktop applications, online MCP services, online Web apps, richer chat and community growth. Unchecked roadmap items are direction, not approved specifications or proof that no related implementation exists: the PR inventory already contains several desktop and integration proposals. For institutional deployment, integration, content/course or research collaboration, the [official collaboration page](https://deeptutor.info/collaborate/) offers a separate contact route; ordinary fixes follow GitHub contribution policy. No contact or submission was made by this research task.

### How the product evolved

Release notes show a widening learning workflow, with later versions adding layers rather than replacing the shared turn runtime:

- **0.x–1.3:** establish the Web app, provider/configuration surfaces, retrieval engines, document ingestion and recovery. The release notes are useful for locating when a legacy behavior or migration was introduced.
- **1.4:** consolidate chat, Deep Research, Deep Solve and Question flows on an agentic engine; add Auto Mode and layered memory; unify capability and localization infrastructure.
- **1.5:** broaden partner integrations and third-party extensions, harden multi-user isolation, and make the Knowledge Center support several retrieval and parsing engines.
- **1.6:** add source-faithful Reading, Courses, Little Tutor threads, learner/guardian policies, workspace-scoped content and daily practice; refactor Web/API contracts and durable turn behavior.
- **1.7:** split the source into version-matched optional Python distributions, add module lifecycle controls, and connect notebooks and new learning surfaces to the agent runtime. The current release notes and upgrade warnings are in [`assets/releases/ver1-7-0.md`](../assets/releases/ver1-7-0.md).

These are release-note eras, not a guarantee every feature remains enabled in every installation. Check module manifests and current route behavior.

### Two extension levels

- **Tools** perform a single operation the model chooses. Some are user-toggleable in Settings; others are gated by context, module, capability, or policy. The authoritative toggle list is `USER_TOGGLEABLE_TOOL_NAMES` in `deeptutor/tools/builtin/__init__.py`; mount rules live in `deeptutor/agents/_shared/tool_composition.py`.
- **Capabilities** own a turn or multi-stage workflow. Examples include `chat`, `deep_research`, `visualize`, and `mastery_path`. They should converge through `emit_capability_result()` so response data and usage accounting remain consistent.

Do not infer availability from a registry entry alone. Module enablement, runtime context, tool policy and the active capability can all affect what the learner can use. Read [Tools and capabilities](TOOLS_AND_CAPABILITIES.md), [Modules](MODULES.md), and [Plugins](PLUGINS.md) before changing these boundaries.

A **module** is an official version-matched Python distribution. Its manifest owns package paths, dependencies, capabilities, tool groups, routers, CLI groups, navigation and lifecycle callbacks; installed, enabled and ready are distinct states. A **plugin** is an independently reviewed extension package with its own manifest, declared permissions, approval state, private environment and typed entry-point contracts. Plugin approval is not an OS sandbox: host entry points execute in the host process, while managed worker isolation is primarily dependency/process lifecycle isolation. Read [Modules](MODULES.md) and [Plugins](PLUGINS.md) before changing package assembly or the trust boundary.

### A learner journey across those layers

A useful contribution map is the learner’s path through the product:

1. **Bring material or start a question.** The learner uploads a document, connects a knowledge source, selects a workspace, or enters chat. Ingestion moves through parsing, indexing and retrieval; source evidence and indexing progress have their own contracts.
2. **Understand material.** Chat can retrieve from a selected knowledge base; Immersive Reading presents a source document; capabilities such as `deep_solve` and `visualize` create different turn workflows. Source-page and figure presentation should stay tied to the answer that uses them.
3. **Ask a follow-up or practice.** Little Tutor starts a source-grounded child session from selected text. Ask Questions clarifies a request; Mastery Path organizes objectives and assessment; Practice works with the question bank. Session relationships, selection provenance and mastery records must survive navigation and replay.
4. **Keep learning artifacts.** Notebook entries, books, memory and generated files persist beyond a turn. Workspace choice, user ownership, deletion, migration and recovery determine where these artifacts live and who can see them.

A symptom may therefore cross a capability, durable session metadata, API and Web surface. When implementing a user-visible request, assess whether UX/UI is **required**, **not required**, or **explicitly out of scope**. For new learner-facing controls or discoverability features it is usually required; include entry point, labels, loading/empty/success/error states, accessibility and responsive behavior that the request affects. For a backend-only correction that restores an existing contract and adds no new user choice, explain why new UI is not required.

## Follow a learner request through the code

For a typical chat turn, trace the entry point into the durable application service, then the turn engine/orchestrator, selected capability, tool composition, and stream adapter. The main navigation paths are:

| Concern | Start here | Contract / adjacent owners |
|---|---|---|
| Turn routing and lifecycle | `deeptutor/runtime/orchestrator.py`, `deeptutor/app/` | `deeptutor/runtime/`, `deeptutor/core/context.py` |
| CLI and SDK | `deeptutor_cli/main.py`, `deeptutor/app/` | CLI serializers and shared turn service |
| WebSocket | `deeptutor/api/routers/unified_ws.py` | `deeptutor/core/stream.py`, `deeptutor/runtime/stream_bus.py`, `web/` client |
| Tool registration and visibility | `deeptutor/tools/`, `deeptutor/runtime/registry/` | `deeptutor/agents/_shared/tool_composition.py`, tool protocol |
| Capability stages and prompts | `deeptutor/capabilities/`, `deeptutor/capabilities/prompts/` | `deeptutor/core/capability_protocol.py`, result envelope |
| Settings and provider selection | `deeptutor/services/config/`, `deeptutor/services/model_selection/` | Settings APIs and `web/features/settings/` |
| Modules and package ownership | module manifests and `pyproject.toml` | `deeptutor/modules/`, generated requirements; see [Modules](MODULES.md) |
| Knowledge ingestion and retrieval | `deeptutor/knowledge/`, `deeptutor/services/rag/` | storage, parsers and retrieval evaluation |
| Web experience | `web/` | API contracts, shared components and `web` tests |
| Runtime data and workspaces | `deeptutor/services/`, `deeptutor/app/` | [Storage](DATA_STORAGE.md), [workspaces](workspaces.md) |

This table is a map, not permission to change every listed layer. For a user-visible behavior, inspect its rendered journey and state handling (loading, empty, failure, recovery, permissions, accessibility and responsive behavior) before editing. The contribution research records examples where a backend capability existed but the learner-facing path was missing or confusing.

The Web client is Next.js App Router with React and TypeScript. Routes live under `web/app/`; feature state, transport and domain logic live under `web/features/`; reusable building blocks live under `web/shared/` and `web/components/`; generated backend contracts live under `web/contracts/`. Keep route modules as composition boundaries and follow the dependency rules in `web/.dependency-cruiser.cjs`. Reuse the owning feature’s API client/store instead of creating component-local fetch, retry, WebSocket or persistence paths. Use the existing components, spacing, typography, icons and interaction patterns; add translation keys through the locale catalogs and check parity rather than adding another inline language conditional. Backend schema changes regenerate `web/contracts/` using the documented contract command.

## Set up a source checkout

Follow [Agent Setup](AGENT_SETUP.md) for the supported environment and provider configuration. The documented full-app source flow uses Python 3.11–3.14, Node.js 22 LTS, full Python requirements, editable source install, and the web lockfile:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements/full.txt
python -m pip install -e . --no-deps
python scripts/install_extras.py dev
(cd web && npm ci --legacy-peer-deps)
```

CLI-only contributors can skip Node/npm, but source checkouts expose the checked-in modules and still need the full Python dependencies. The application is modular; published wheels should be version-matched. Use `scripts/install_extras.py` rather than overlaying feature wheels on a source checkout. Never assume project-root `.env` files configure runtime settings: settings live under the DeepTutor runtime home, and `.env` loading is intentionally not automatic.

Keep test runtime homes, knowledge bases, credentials, and user data separate from the repository and each other. Follow [Storage](DATA_STORAGE.md) and [Security Guard](SECURITY_GUARD.md) before tests that create durable state. Avoid provider calls unless a test explicitly needs them and credentials/charges are understood.

## Choose the right contribution route

At the research snapshot, the source checkout was `main` at `1ea7df155447f4caf0e3abc86b3ff5395479cd4a`; the upstream branches were `dev` at `18aaa11697560d68e5a8a7215e3c6c70df24492d` and `multi-user` at `2c4769a96f926ff0642c4e34a461071412c7c903`. The checked-in [CONTRIBUTING.md](../CONTRIBUTING.md) describes the public project branch policy: ordinary features, fixes and refactors target `dev`; multi-user or tenant isolation work targets `multi-user`; docs-only changes may target `main` (and hotfixes are an exception). It currently names `dev` as the default development branch. Always confirm the current upstream branch and maintainer instructions before opening a PR. The project is forked as `hongthana/DeepTutor`; upstream is `HKUDS/DeepTutor`. Do not confuse fork-local work with upstream acceptance.

Repository policy for this worktree separately requires isolated feature worktrees for code changes, exact gates, and normal commits/pushes to `main` by default. When these repository-local instructions conflict with public contributor policy, do not silently choose a target: follow the task's explicit integration workflow or ask the repository owner. Docs-only work follows the main-branch exception in public guidance. This guide does not authorize committing or pushing.

A good contribution starts by:

1. Reproducing the behavior on the relevant current branch and release, then checking the issue and related PRs for newer evidence.
2. Identifying the owner and contract, including the UI/API/CLI paths affected. Keep one cohesive change and add a regression test at the contract boundary.
3. Writing down expected behavior and failure/recovery cases before editing. For UI changes, include the actual learner journey and verify the rendered flow.
4. Running the focused regression first, then the applicable repository gates in [Testing](TESTING.md). Record what each check establishes and any provider/platform limitation.
5. Updating the canonical topic documentation and examples when behavior or configuration changes. Avoid duplicating a contract across multiple docs.

The project contributor guide recommends `pre-commit run --all-files`; CI configuration and the current `docs-for-dev/TESTING.md` are the source of truth for gates. A command that is unavailable is not a pass. Test names and package scripts can change, so use the documented commands in the current checkout rather than an old issue comment.

### Choose a contribution path

| Strength or interest | Start with | Read / verify |
|---|---|---|
| Python tools or capabilities | A narrow tool or capability bug with an existing owner | Tool/capability contracts, mount rules, focused pytest, CLI/API behavior if shared |
| Frontend and accessibility | A named learner journey such as settings, chat or Reading | Feature transport/store owner, shared components, locale catalogs, Vitest plus browser/rendered acceptance for the affected states |
| Retrieval and documents | A deterministic parsing, indexing or retrieval reproduction | Knowledge and migration docs, synthetic files, source attribution, recovery/reindex tests; avoid provider-dependent evidence unless required |
| Runtime and persistence | A reproduced turn/replay/workspace lifecycle defect | Application service, event contract, storage/workspace ownership, restart/replay and isolation tests |
| Modules or plugins | A manifest/lifecycle boundary with disposable environments | Version alignment, generated requirements, approval/rollback/cancellation tests; avoid changing global interpreter state |
| Documentation | One verified stale command, path or omitted workflow | Canonical topic owner, local links, CLI help/contracts; keep duplicated translations in sync where required |

A realistic first week is to spend the first day tracing one learner journey and its owner, the second reproducing a small issue and identifying an existing test, the third implementing one bounded change with its regression, the fourth running the appropriate gates and rendering the affected UI if applicable, and the fifth preparing a concise PR with observed evidence and remaining limitations. This sequence is a suggestion; it does not replace the project’s branch policy or maintainer review.

## Issues and PRs: read as evidence, not as current truth

The dated research snapshot includes 773 issue records (651 closed, 122 open), 1,307 PR records (1,220 closed, 87 open), 2,192 issue comments, and 129 inline review comments. The issue endpoint also repeats PR records. The pull metadata reports merged state separately from closed/open state. The snapshot was captured through fully paginated GitHub endpoints on 2026-10-29; see the appendices for scope and fields.

The high-level clusters below come from qualitative review of recent issue titles, selected full issue bodies and linked discussion—not a mutually exclusive label taxonomy or quantified prevalence estimate. Issue categories overlap (for example, a UI report can also concern i18n, persistence or accessibility). Issue reports, maintainer replies, PR descriptions and review comments are useful for discovering reproductions, expected behavior and edge cases. They do not prove the bug still exists at this checkout, that a PR is accepted, or that its patch is safe. Several issue reports in the research set explicitly describe older v1.6.15 behavior; later PR metadata shows related work landing on `dev`. For example, issues #2041 (same-name KB documents), #2037 (vision model selector), and #2049 (notebook full read/append) have associated merged PR metadata. Treat them as historical context, not open work. #1940 was last updated on 2026-10-15, two weeks before this snapshot, and contains claims that age quickly; verify its linked records and current branch before repeating any status.

A reproduction check on the source snapshot confirmed #2111’s chunk-budget overrun for budgets 5, 10, and 20 (6, 11, and 21 output chunks); PR #2112 is recorded as merged to `dev`, so this is a branch-specific lead, not a universal open defect. Recent issue clusters point to localization, CJK text boundaries, chat recovery settings, mastery assessment and source presentation, knowledge-base ingestion, and learner navigation. A report with detailed reproduction is a lead to reproduce; it is not a validated diagnosis. Full traceability is in the [issue inventory](research/2026-10-29/issues.md) and [PR inventory](research/2026-10-29/pull-requests.md), not in a claim that every PR diff or review submission was inspected.

## Candidate work to investigate

This is a **snapshot of leads, not a queue of verified defects**. I searched the downloaded bodies and discussion comments for the issue references below across all 1,307 PR records and 2,192 collected comments, then checked issue status, PR state/merge metadata and the source paths named in candidate reports. A closed PR without `merged` metadata is not treated as an accepted fix. Full record traceability is in the appendices.

| Rank | Candidate and snapshot status | Current evidence and why it may fit | Scope, UX and useful acceptance checks |
|---:|---|---|---|
| 1 | [#2074 archived workspaces logged on each index poll](https://github.com/HKUDS/DeepTutor/issues/2074) — issue open; related [#2080](https://github.com/HKUDS/DeepTutor/pull/2080) closed, **not merged**, base `dev` | The source snapshot builds the cross-workspace session index in `deeptutor/services/workspace/navigation.py`; `tests/services/workspace/test_navigation.py` deliberately checks cross-workspace results and offline-workspace reporting. The maintainer closed #2080 because globally filtering archived workspaces would hide sessions from Settings → Archived Chats ([review comment](https://github.com/HKUDS/DeepTutor/pull/2080#issuecomment-6443279817)). | **UX: not required for a diagnostics-only change.** First characterize archived-but-reachable workspaces and missing archived folders. Preserve all reachable archived sessions in the archive-management view; unavailable archived folders must not cause other reachable archive rows or active-workspace results to disappear. Do not filter archived workspaces globally. Ask the maintainer to agree on a scoped, actionable logging or recovery behavior before implementation; retain the existing offline-workspace contract. This is a small investigation/test contribution, not an approved filter fix. |
| 2 | [#2118 return to a Little Tutor thread from its quoted source](https://github.com/HKUDS/DeepTutor/issues/2118) — issue open; no matching PR reference found in the collected PR bodies/comments | One commenter asks to be assigned. The report describes a missing route back from a source message and proposes a marker/popover. It points to existing parent-session metadata and message metadata as candidate sources for linking old threads. | **UX: required.** Define the visible marker, multiple-thread popover, thread focus/reopen, deletion permissions, loading/empty/error states, keyboard operation and mobile placement. Test source-message association, repeated threads and old sessions; verify in the rendered chat journey. This is product work with more UI surface than #2074. |
| 3 | [#2134 localized inline copy](https://github.com/HKUDS/DeepTutor/issues/2134) — issue open; related [#2135](https://github.com/HKUDS/DeepTutor/pull/2135) open to `dev` at snapshot | The issue author says their fix builds on the Turkish locale PR and will follow once it settles. This is therefore **coordinated work**, not unclaimed work. | **UX: required.** Coordinate with the author/maintainer before editing shared catalogs or locale seams. Acceptance spans named settings/navigation/dashboard components, translated catalog lookup with English fallback, locale tests and rendered verification. |
| 4 | [#2133 Windows-1254 text valid as GBK](https://github.com/HKUDS/DeepTutor/issues/2133) — issue open; related [#2136](https://github.com/HKUDS/DeepTutor/pull/2136) open to `dev` at snapshot | #2136 handles cp1254 text that fails earlier decoders but documents the ambiguous valid-GBK case as strict `xfail`, referring to #2133. The issue author notes that simple heuristics can misclassify real Chinese snippets and lists possible approaches. | **UX: decision-dependent.** A language/encoding hint could affect import controls and persisted source metadata; a heuristic-only backend patch has false-positive risk. Preserve GBK fixtures, add short and long Turkish examples and define a confidence/fallback story before changing decoder order. Not a safe first unreviewed patch. |
| 5 | [#2123 unreachable Math Animator visual QA](https://github.com/HKUDS/DeepTutor/issues/2123) — issue open; no matching PR reference found in collected PR bodies/comments | Source confirms `enable_visual_review` defaults to false in `deeptutor/agents/math_animator/pipeline.py`; the issue says none of the callers pass it. This moves optional visual review from a reachable configured feature toward an activation/product decision. | **UX: required if exposed as a setting.** Review latency, rendering availability and extra model cost; decide per capability and default before implementation. Add configuration/CLI/API tests, opt-in behavior tests and rendered output checks across Math Animator, Visualize and Book animation callers. Higher cost and broad call graph make this a later task. |
| — | [#2057 layered memory vs raw-history RAG evaluation](https://github.com/HKUDS/DeepTutor/issues/2057) — issue open; related [#2113](https://github.com/HKUDS/DeepTutor/pull/2113) merged to `dev` | The issue is explicitly an evaluation request, not a request to replace production memory. The merged PR adds an isolated synthetic evaluation runner, so read that artifact and current issue discussion before proposing a second benchmark. | UX: not required for an isolated developer evaluation. A useful follow-up would be evidence quality, limitation documentation or a reproducible synthetic case; no production behavior change follows without a separate decision. |

The prior apparent opportunities #2100 (system theme), #2091 (formatted text selection), and #2041 (same-name KB documents) already have merged PRs #2121, #2093, and #2045 respectively, each to `dev`; they are examples of how to verify a report, not current work recommendations. #2111 was reproduced against the `main` source snapshot at budgets 5/10/20 (6/11/21 chunks), while PR #2112 merged to `dev`; confirm the branch before interpreting that as a live defect.

**Best first contribution:** start with #2074 as a regression-characterization task. Confirm that reachable archived sessions remain visible in Settings → Archived Chats while an unavailable archived folder is isolated and reported without hiding other results. Then ask the maintainer for a scoped diagnostics/recovery design; do not apply the closed PR’s global filter. **Best first frontend contribution:** coordinate on #2134 only after #2135 settles, or choose a separate UI issue with no in-flight related work. Documentation contributions should correct one demonstrated stale command in its canonical page and verify links/examples.

## Patterns in recent pull requests

A selected sample of merged, closed-unmerged and open PRs illustrates useful review habits, but the records do not establish that each patch is a general design precedent. PR #1956 is closed with a merge timestamp; #1964 is closed without one; #2009, #2127, #2136 and #2139 are open at snapshot. Always consult `merged` separately from `state` in the inventory.

- PR [#2127](https://github.com/HKUDS/DeepTutor/pull/2127) addresses a viewport-bound composer popover and includes interaction tests. Its issue context (#2053) illustrates why a visual state needs rendered viewport evidence in addition to code assertions.
- PR [#2080](https://github.com/HKUDS/DeepTutor/pull/2080) is a useful negative example: the maintainer closed its global archived-workspace filter because Settings → Archived Chats depends on cross-workspace session indexing. Preserve the archive-management journey when narrowing a backend fix.
- PR [#2009](https://github.com/HKUDS/DeepTutor/pull/2009) gates vector-profile behavior and adds create/insert coverage. When adding a setting or profile, exercise the lifecycle, not just parsing.
- PR [#1956](https://github.com/HKUDS/DeepTutor/pull/1956) follows incomplete-result status through the stream and persisted turn state. Cross-layer state changes need consistent terminal semantics.
- PR [#1964](https://github.com/HKUDS/DeepTutor/pull/1964) addresses shared fixture and synchronization behavior; shared state can make individually passing tests unreliable unless fixtures and ordering are explicit.
- PR [#2136](https://github.com/HKUDS/DeepTutor/pull/2136) adds Windows-1254 decoding before Latin-1 fallback. Its discussion documents a limitation for strings whose bytes are also valid GBK (#2133); do not assume codec ordering can reliably identify ambiguous legacy encodings. Verify the target branch and preserve real GBK behavior.
- PR [#2139](https://github.com/HKUDS/DeepTutor/pull/2139) proposes batching run-state serialization and raises a stall timeout. Its description reports a long-running local reproduction, while the patch snapshot did not add a regression test. Treat the performance claim and tradeoff as a hypothesis to independently measure, not as an accepted implementation pattern.

These examples were inspected at patch level by the research owner for context. #1956 is merged, #1964 is closed unmerged, and #2009, #2136, #2139 and #2127 remain open at snapshot; the open PRs illustrate proposals and tests as submitted, not accepted conventions. The patch sample does not turn the inventory into a full review of repository PRs.

## Common risk areas

- **Durable state and migration:** session, workspace, notebook, memory and knowledge data can outlive a process. Cover restart, recovery and older data shapes. Read [Storage](DATA_STORAGE.md), [Knowledge Migration](KNOWLEDGE_MIGRATION.md), and [Indexing Recovery](INDEXING_RECOVERY.md).
- **Multiple users and permissions:** user identity, ownership, grants and filesystem paths must remain scoped. A tenant bug is a protected change; follow `multi-user` policy and require independent review.
- **Streaming and cancellation:** consumers may reconnect or replay; cancellation and terminal events must remain consistent across WebSocket, CLI and SDK. Read [Events and Progress](EVENTS_AND_PROGRESS.md) and [Runtime Design](RUNTIME_DESIGN.md).
- **Optional modules:** source tree availability differs from installed/enabled state. Keep dependency manifests, generated requirements, API routes and UI navigation in sync.
- **Model/provider variability:** a successful mocked unit test does not prove a live provider or model integration. Label and run live checks only where appropriate.
- **Learner-facing UX:** correct backend output can still be unusable if it is hidden, clipped, not recoverable, inaccessible, or disconnected from its source. Verify the rendered journey for the requested outcome.

## Research coverage and limits

The research sweep inventoried 172 Markdown files tracked at the source commit and read the project and developer guidance, topic pages, release-note headings and selected release bodies, translations, and subsystem readmes; the [source index](research/2026-10-29/source-index.md) distinguishes guidance from prompt, persona, skill and fixture content. The source index predates the four new research/contributor Markdown files in this change set. Historical releases show the transition from retrieval/configuration foundations through the 1.4 agentic engine and memory, 1.5 extension and multi-user expansion, and 1.6 learner workspaces/reading/practice to the 1.7 modular distribution. This synthesis is a navigation summary, not a line-by-line re-review of every translated copy or prompt.

For GitHub, the collector fully paginated the Issues endpoint, pulls endpoint and discussion data; resulting records are 2,080 issue-endpoint entries (773 issues and 1,307 PR mirrors), 1,307 pulls metadata records, 2,192 accessible comments, and 129 inline review-comment records. There are 78 fewer accessible comment records than the sum of comment counts reported in issue/PR metadata (2,270); a per-issue reconciliation fetched comments for 11 discrepant records and returned the same accessible counts. The reason for the metadata gap is unknown. The issue and PR appendices record the endpoint parameters and terminal page counts. Default sort/order parameters were omitted; collection across endpoints was not an atomic snapshot.

The guide uses qualitative issue themes and selected detailed body/comment reads; it does not claim a quantified issue taxonomy or body-level analysis of all 2,080 records. Selected PR diffs were inspected for the examples in [Patterns in recent pull requests](#patterns-in-recent-pull-requests), not for all 1,307 PRs. The metadata appendix is not a review of every diff, check run, or review submission, and it does not establish current remote state after collection. Treat recommendations as leads and verify target-branch behavior and live discussion before choosing work.

## Use and refresh this guide

Read [Contributing](../CONTRIBUTING.md), [Development](DEVELOPMENT.md), [Architecture](ARCHITECTURE.md), then [Testing](TESTING.md); continue with the single owning topic for your chosen journey. Use the dated inventories to find related records, then read their latest bodies, maintainer comments and diffs on GitHub before selecting a task.

Before each new contribution, verify the source version, target branch and related issue/PR states. Keep technical contracts in their canonical topic pages. Preserve these dated appendices as historical research; collect a new dated snapshot when refreshing the issue inventory rather than silently relabeling old counts as current. Record endpoint parameters, terminal pages and coverage gaps, distinguish merged from closed PRs, and reassess recommendations against maintainer comments and the actual target-branch code.
