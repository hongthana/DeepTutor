# Pull-request metadata inventory — 2026-10-29

Metadata snapshot for all 1,307 pull requests in `HKUDS/DeepTutor`, collected by the fully paginated [GitHub pulls endpoint](https://api.github.com/repos/HKUDS/DeepTutor/pulls) using `state=all&per_page=100&page=N`; pages 1–13 returned 100 records each, page 14 returned 7, and page 15 returned empty. Default sorting/order parameters were omitted; this was not a stable cursor snapshot. Source checkout: `1ea7df155447f4caf0e3abc86b3ff5395479cd4a`. API metadata reported 849 merged records; states: {'closed': 1220, 'open': 87}; base branches: {'main': 262, 'dev': 1039, 'dev-rag': 1, 'eval': 1, 'multi-user': 1, 'preview': 3}; drafts: 36. A closed PR is not necessarily merged: the `merged` field is listed independently.

The [pull review-comments endpoint](https://api.github.com/repos/HKUDS/DeepTutor/pulls/comments) used `per_page=100&page=N`; pages 1–2 returned records (page 2 contained 29), and page 3 returned empty, for 129 inline review-comment records. Default sorting/order parameters were omitted; this was not a stable cursor snapshot.

This index is for tracing related work. It does not represent review of each patch, CI result, or every review submission. Use GitHub for current state and inspect the actual diff and tests before relying on a precedent.

| PR | Title | State | Merged | Draft | Base | Head |
|---:|---|---|---|---|---|---|
| 2 | [avoid false 'Virtual env not detected' warning under conda](https://github.com/HKUDS/DeepTutor/pull/2) | closed | yes | no | main | fix/install-script-conda-detection |
| 10 | [fix(ui): knowledge base modal backdrop and positioning](https://github.com/HKUDS/DeepTutor/pull/10) | closed | yes | no | main | fix/kb-modal-positioning |
| 11 | [Hardened the Application's Attack Surface through Least Privilege Principle](https://github.com/HKUDS/DeepTutor/pull/11) | closed | yes | no | main | main |
| 12 | [fix(core): ensure core attributes initialized without rich library](https://github.com/HKUDS/DeepTutor/pull/12) | closed | yes | no | main | fix/smart-solver |
| 13 | [Added docker support along with some minor changes in previous files related to types](https://github.com/HKUDS/DeepTutor/pull/13) | closed | no | no | main | feature/docker_support |
| 14 | [Add Docker infrastructure for DeepTutor, including multi-stage Docker…](https://github.com/HKUDS/DeepTutor/pull/14) | closed | yes | no | main | docker |
| 17 | [Create HARM](https://github.com/HKUDS/DeepTutor/pull/17) | closed | no | no | main | patch-1 |
| 18 | [Fix JSON parsing failure for triple-quoted Python strings in Smart Solver](https://github.com/HKUDS/DeepTutor/pull/18) | closed | yes | no | main | fix-json-triple-quoted-strings |
| 19 | [Refined prompt for balance between deducing and rag](https://github.com/HKUDS/DeepTutor/pull/19) | closed | no | no | main | main |
| 20 | [fix(security): patch critical RCE and LFI vulnerabilities](https://github.com/HKUDS/DeepTutor/pull/20) | closed | yes | no | main | security/fix-critical-path-traversal-and-injection |
| 21 | [chore(deps): update core libraries to mitigate known CVEs](https://github.com/HKUDS/DeepTutor/pull/21) | closed | yes | no | main | chore/update-security-dependencies |
| 22 | [feat(security): enforce WSS protocol for production websockets](https://github.com/HKUDS/DeepTutor/pull/22) | closed | yes | no | main | feat/secure-websockets |
| 23 | [fix: SolveAgent code generation by enforcing intent-only planning](https://github.com/HKUDS/DeepTutor/pull/23) | closed | yes | no | main | fix/solveagent-intent-only-code-execution |
| 26 | [fix(UI): unrendered markdown in ActivityDetail card](https://github.com/HKUDS/DeepTutor/pull/26) | closed | yes | no | main | fix/undrendered-markdown-dashboard |
| 27 | [chore: transtale readme to ru](https://github.com/HKUDS/DeepTutor/pull/27) | closed | yes | no | main | translate_readme_to_ru |
| 28 | [fix: improve reload_excludes configuration for uvicorn server and added support for newer models (openai)](https://github.com/HKUDS/DeepTutor/pull/28) | closed | yes | no | main | fix/uvicorn-and-openai |
| 29 | [feat(i18n): add Portuguese language support](https://github.com/HKUDS/DeepTutor/pull/29) | closed | no | no | main | main |
| 32 | [Support open-source embedding models with custom embedding dimensions](https://github.com/HKUDS/DeepTutor/pull/32) | closed | no | no | main | fix-json-triple-quoted-strings |
| 34 | [feat: Dynamic LLM Provider Support (Local & Cloud)](https://github.com/HKUDS/DeepTutor/pull/34) | closed | yes | no | main | feat/local-llm-support |
| 35 | [fix: unify prompt loading and handle optional lightrag dependency](https://github.com/HKUDS/DeepTutor/pull/35) | closed | no | no | main | feature/unify-prompt-loading |
| 38 | [chore(deps): bump actions/upload-pages-artifact from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/38) | closed | yes | no | main | dependabot/github_actions/actions/upload-pages-artifact-4 |
| 39 | [chore(deps): bump actions/checkout from 4 to 6](https://github.com/HKUDS/DeepTutor/pull/39) | closed | yes | no | main | dependabot/github_actions/actions/checkout-6 |
| 40 | [chore(deps): bump actions/configure-pages from 4 to 5](https://github.com/HKUDS/DeepTutor/pull/40) | closed | yes | no | main | dependabot/github_actions/actions/configure-pages-5 |
| 41 | [chore(deps): bump python from 3.11-slim to 3.14-slim](https://github.com/HKUDS/DeepTutor/pull/41) | closed | no | no | main | dependabot/docker/python-3.14-slim |
| 42 | [chore(deps): bump node from 20-slim to 25-slim](https://github.com/HKUDS/DeepTutor/pull/42) | closed | yes | no | main | dependabot/docker/node-25-slim |
| 43 | [chore(deps): bump lucide-react from 0.460.0 to 0.562.0 in /web in the npm-minor-patch group](https://github.com/HKUDS/DeepTutor/pull/43) | closed | yes | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-6a651e08cd |
| 44 | [chore(deps): bump framer-motion from 11.18.2 to 12.24.0 in /web](https://github.com/HKUDS/DeepTutor/pull/44) | closed | yes | no | main | dependabot/npm_and_yarn/web/framer-motion-12.24.0 |
| 45 | [chore(deps): bump tailwind-merge from 2.6.0 to 3.4.0 in /web](https://github.com/HKUDS/DeepTutor/pull/45) | closed | yes | no | main | dependabot/npm_and_yarn/web/tailwind-merge-3.4.0 |
| 46 | [chore(deps): bump tailwindcss from 3.4.19 to 4.1.18 in /web](https://github.com/HKUDS/DeepTutor/pull/46) | closed | no | no | main | dependabot/npm_and_yarn/web/tailwindcss-4.1.18 |
| 47 | [chore(deps): bump react-markdown from 9.1.0 to 10.1.0 in /web](https://github.com/HKUDS/DeepTutor/pull/47) | closed | yes | no | main | dependabot/npm_and_yarn/web/react-markdown-10.1.0 |
| 48 | [chore(deps): bump @types/node from 22.19.3 to 25.0.3 in /web](https://github.com/HKUDS/DeepTutor/pull/48) | closed | yes | no | main | dependabot/npm_and_yarn/web/types/node-25.0.3 |
| 49 | [chore(deps): bump jspdf from 2.5.2 to 4.0.0 in /web](https://github.com/HKUDS/DeepTutor/pull/49) | closed | no | no | main | dependabot/npm_and_yarn/web/jspdf-4.0.0 |
| 50 | [fix(ci): Resolve linting and formatting issues](https://github.com/HKUDS/DeepTutor/pull/50) | closed | yes | no | main | fix/linting-and-actions |
| 51 | [UI/theme](https://github.com/HKUDS/DeepTutor/pull/51) | closed | yes | no | main | ui/theme |
| 52 | [Add project report documenting fork use cases and setup](https://github.com/HKUDS/DeepTutor/pull/52) | closed | no | no | main | claude/explore-fork-use-cases-W1Xox |
| 55 | [feat: support baidu ai search](https://github.com/HKUDS/DeepTutor/pull/55) | closed | yes | no | main | feat/support-baidu-search |
| 57 | [Feature/rag plugin system](https://github.com/HKUDS/DeepTutor/pull/57) | closed | yes | no | dev | feature/rag-plugin-system |
| 62 | [Fix critical jspdf vuln and clean up pre-commit hooks](https://github.com/HKUDS/DeepTutor/pull/62) | closed | yes | no | main | fix/patch-security-vulnerabilities |
| 64 | [fix: resolve double decoration in embedding functions for OpenRouter …](https://github.com/HKUDS/DeepTutor/pull/64) | closed | yes | no | main | fix/openrouter-embedding-compatibility |
| 66 | [Cleanup: address reviewer feedback on PR #62](https://github.com/HKUDS/DeepTutor/pull/66) | closed | no | no | main | fix/reviewer-feedback-cleanup |
| 67 | [Cleanup: address reviewer feedback on PR #62 (Final)](https://github.com/HKUDS/DeepTutor/pull/67) | closed | yes | no | main | fix/cleanup-final |
| 68 | [Arch/compliance and ux audit](https://github.com/HKUDS/DeepTutor/pull/68) | closed | no | no | main | arch/compliance-and-ux-audit |
| 71 | [feat/gracefully disable RagAnything when absent and tighten Python dependency handling](https://github.com/HKUDS/DeepTutor/pull/71) | closed | yes | no | main | feat/dependency-management |
| 77 | [provides more llm providers supports, fixed some ambiguities, ui updates,fixed discrepency between some elements of ui and backend were in sync.](https://github.com/HKUDS/DeepTutor/pull/77) | closed | yes | no | main | feat/llm_models_support |
| 79 | [Dev embeddings providers](https://github.com/HKUDS/DeepTutor/pull/79) | closed | yes | no | dev | dev-embeddings-providers |
| 81 | [fix: Add comprehensive error handling and JSON parsing for question g…](https://github.com/HKUDS/DeepTutor/pull/81) | closed | yes | no | main | fix/question-generation-json-parsing |
| 82 | [merge](https://github.com/HKUDS/DeepTutor/pull/82) | closed | no | no | dev | main |
| 83 | [fix(web): Remove duplicated translation keys](https://github.com/HKUDS/DeepTutor/pull/83) | closed | no | no | main | fix/duplicated-translation-keys |
| 84 | [Fix test configuration for GitHub Actions](https://github.com/HKUDS/DeepTutor/pull/84) | closed | no | no | main | claude/fix-tests-github-actions-Ga5jA |
| 87 | [feat: azure openai support](https://github.com/HKUDS/DeepTutor/pull/87) | closed | yes | no | dev | feat/azure-openai-support |
| 90 | [docs: update](https://github.com/HKUDS/DeepTutor/pull/90) | closed | yes | no | dev | docs/windows-lp-troubleshooting |
| 93 | [Web search providers](https://github.com/HKUDS/DeepTutor/pull/93) | closed | no | no | dev | web-search-providers |
| 95 | [Web search providers](https://github.com/HKUDS/DeepTutor/pull/95) | closed | yes | no | dev | web-search-providers |
| 96 | [Pr focused error handling](https://github.com/HKUDS/DeepTutor/pull/96) | closed | no | yes | dev | pr-focused-error-handling |
| 98 | [feat: Implement LlamaIndex and LightRAG pipelines with complete loose coupling](https://github.com/HKUDS/DeepTutor/pull/98) | closed | yes | no | dev | feat/llamaindex-pipeline |
| 99 | [fix: add standalone output mode for Docker deployment](https://github.com/HKUDS/DeepTutor/pull/99) | closed | no | no | main | claude/hosting-deployment-strategy-yXMys |
| 102 | [chore(deps): bump docker/build-push-action from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/102) | closed | no | no | main | dependabot/github_actions/docker/build-push-action-6 |
| 103 | [chore(deps): bump node from 22-slim to 25-slim](https://github.com/HKUDS/DeepTutor/pull/103) | closed | no | no | main | dependabot/docker/node-25-slim |
| 104 | [chore(deps): bump actions/setup-python from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/104) | closed | no | no | main | dependabot/github_actions/actions/setup-python-6 |
| 105 | [chore(deps): bump actions/checkout from 4 to 6](https://github.com/HKUDS/DeepTutor/pull/105) | closed | no | no | main | dependabot/github_actions/actions/checkout-6 |
| 106 | [chore(deps): bump the npm-minor-patch group in /web with 3 updates](https://github.com/HKUDS/DeepTutor/pull/106) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-3ef5fb6187 |
| 107 | [chore(deps): bump the python-minor-patch group with 4 updates](https://github.com/HKUDS/DeepTutor/pull/107) | closed | no | no | main | dependabot/pip/python-minor-patch-c122fccbb5 |
| 114 | [Add feature toggling](https://github.com/HKUDS/DeepTutor/pull/114) | closed | no | no | main | feature/add-feature-toggling |
| 117 | [fix: modal not vertically centered](https://github.com/HKUDS/DeepTutor/pull/117) | closed | yes | no | main | knowledge |
| 118 | [work/llm-error-framework](https://github.com/HKUDS/DeepTutor/pull/118) | closed | yes | no | dev | integrate/hk-dev |
| 122 | [feat: Add Local Folder Integration (Closes #101)](https://github.com/HKUDS/DeepTutor/pull/122) | closed | no | no | main | feature/local-folder-integration |
| 126 | [Feature/pre commit ci (#37)](https://github.com/HKUDS/DeepTutor/pull/126) | closed | yes | no | dev | feat/precommit-ci |
| 127 | [feat: folder sync with improved architecture (supersedes #122)](https://github.com/HKUDS/DeepTutor/pull/127) | closed | yes | no | dev | feature/folder-sync-refactored |
| 128 | [fix/docker](https://github.com/HKUDS/DeepTutor/pull/128) | closed | yes | no | dev | fix/docker-portability |
| 129 | [feat(kb): allow selecting RAG provider during KB create/upload](https://github.com/HKUDS/DeepTutor/pull/129) | closed | yes | no | dev | feat/kb/select-rag-provider |
| 130 | [feat: centralise JSON parsing with automatic repair fallback](https://github.com/HKUDS/DeepTutor/pull/130) | closed | yes | no | dev | feat/json-repair-robustness |
| 131 | [Modular rag implementation](https://github.com/HKUDS/DeepTutor/pull/131) | closed | yes | no | dev-rag | dev-rag |
| 138 | [fix: Folder Sync Improvements - Source Path Tracking & LightRAG Fallback](https://github.com/HKUDS/DeepTutor/pull/138) | closed | no | no | dev | feature/folder-sync-refactored |
| 139 | [fix: vulnerabilities in code execution and container security](https://github.com/HKUDS/DeepTutor/pull/139) | closed | no | no | main | hotfix/credential-security |
| 140 | [Feat/searxng](https://github.com/HKUDS/DeepTutor/pull/140) | closed | no | no | dev | feat/searxng |
| 142 | [Feature/solver session persistence](https://github.com/HKUDS/DeepTutor/pull/142) | closed | no | no | dev | feature/solver-session-persistence |
| 143 | [fix(llm): force temperature to 1.0 for gpt-5/o1/o3 models #141](https://github.com/HKUDS/DeepTutor/pull/143) | closed | no | no | dev | fix/issue-141-forced-temperature |
| 147 | [feat: Increase LLM retry attempts and delays for enhanced robustness with complex agents.](https://github.com/HKUDS/DeepTutor/pull/147) | closed | yes | no | dev | main |
| 149 | [chore(deps): bump actions/cache from 4 to 5](https://github.com/HKUDS/DeepTutor/pull/149) | closed | no | no | main | dependabot/github_actions/actions/cache-5 |
| 150 | [chore(deps): bump actions/setup-node from 4 to 6](https://github.com/HKUDS/DeepTutor/pull/150) | closed | no | no | main | dependabot/github_actions/actions/setup-node-6 |
| 151 | [chore(deps): update safety requirement from <3.0.0 to <4.0.0](https://github.com/HKUDS/DeepTutor/pull/151) | closed | no | no | main | dependabot/pip/safety-lt-4.0.0 |
| 152 | [chore(deps): bump the npm-minor-patch group in /web with 5 updates](https://github.com/HKUDS/DeepTutor/pull/152) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-fc7340563d |
| 153 | [chore(deps): update numpy requirement from <2.0.0,>=1.24.0 to >=1.24.0,<3.0.0](https://github.com/HKUDS/DeepTutor/pull/153) | closed | no | no | main | dependabot/pip/numpy-gte-1.24.0-and-lt-3.0.0 |
| 157 | [feat(math_solver): add mathematical solver tool with tests](https://github.com/HKUDS/DeepTutor/pull/157) | closed | no | no | dev | feat/math-solver |
| 165 | [Feat/strengthen llm support](https://github.com/HKUDS/DeepTutor/pull/165) | closed | no | no | main | feat/strengthen-llm-support |
| 166 | [Feat/llm harden](https://github.com/HKUDS/DeepTutor/pull/166) | closed | no | no | dev | feat/llm-harden |
| 169 | [chore: update repo roster images [skip ci]](https://github.com/HKUDS/DeepTutor/pull/169) | closed | no | no | main | main |
| 175 | [fix:CoWriterEditor scroll sync](https://github.com/HKUDS/DeepTutor/pull/175) | closed | yes | no | dev | fix/editor-scroll-sync |
| 176 | [Fix/i18n improvement](https://github.com/HKUDS/DeepTutor/pull/176) | closed | yes | no | main | fix/i18n-improvement |
| 178 | [chore(deps): bump the npm-minor-patch group across 1 directory with 7 updates](https://github.com/HKUDS/DeepTutor/pull/178) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-5ded2f9fbd |
| 183 | [Feature/llm hardening core slim (#52)](https://github.com/HKUDS/DeepTutor/pull/183) | closed | yes | no | dev | feat/llm-hardening |
| 184 | [docs: update ru translate](https://github.com/HKUDS/DeepTutor/pull/184) | closed | yes | no | main | update_ru_translate |
| 186 | [Integrate local fixes and configurations](https://github.com/HKUDS/DeepTutor/pull/186) | closed | no | no | main | local-updates-20260201 |
| 187 | [chore(deps): bump the npm-minor-patch group across 1 directory with 11 updates](https://github.com/HKUDS/DeepTutor/pull/187) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-cc9f2e1c93 |
| 189 | [feat/vision_slover](https://github.com/HKUDS/DeepTutor/pull/189) | closed | no | no | dev | feat/vision_slover |
| 190 | [feat/vision_slover](https://github.com/HKUDS/DeepTutor/pull/190) | closed | no | no | main | feat/vision_slover |
| 191 | [feat/vision_slover](https://github.com/HKUDS/DeepTutor/pull/191) | closed | yes | no | dev | feat/vision_slover |
| 192 | [chore(deps): bump the npm-minor-patch group across 1 directory with 13 updates](https://github.com/HKUDS/DeepTutor/pull/192) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-0112c175e8 |
| 194 | [feat: Add OpenRouter search provider](https://github.com/HKUDS/DeepTutor/pull/194) | closed | yes | no | dev | feat/openrouter-search |
| 195 | [adapt nginx server name  deployment ( deployment adaption )](https://github.com/HKUDS/DeepTutor/pull/195) | closed | no | no | main | Cloud-Deployment-Adaption |
| 196 | [Restrict code execution scope and enforce import whitelist](https://github.com/HKUDS/DeepTutor/pull/196) | closed | yes | no | dev | feat/code-executor-hardening |
| 198 | [chore(deps): bump the npm-minor-patch group across 1 directory with 14 updates](https://github.com/HKUDS/DeepTutor/pull/198) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-991c81a85b |
| 200 | [Claude/deeptutor news integration okk up](https://github.com/HKUDS/DeepTutor/pull/200) | closed | no | no | main | claude/deeptutor-news-integration-OkkUP |
| 201 | [merge student-simulation](https://github.com/HKUDS/DeepTutor/pull/201) | closed | yes | no | eval | jiahao-bench |
| 202 | [chore(deps): bump the npm-minor-patch group across 1 directory with 15 updates](https://github.com/HKUDS/DeepTutor/pull/202) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-2f4a3d6618 |
| 203 | [fix(api): resolve HTTP 413 on file uploads larger than 1 MB](https://github.com/HKUDS/DeepTutor/pull/203) | closed | no | no | main | fix/multipart-upload-413-large-files |
| 204 | [fix(api): resolve HTTP 413 on file uploads larger than 1 MB](https://github.com/HKUDS/DeepTutor/pull/204) | closed | no | no | dev | fix/multipart-upload-413-large-files-v2 |
| 205 | [fix: replace 16 bare excepts with except Exception across 9 files](https://github.com/HKUDS/DeepTutor/pull/205) | closed | no | no | main | fix/bare-excepts |
| 206 | [feat(web): streamline notebook studio direct entry defaults](https://github.com/HKUDS/DeepTutor/pull/206) | closed | no | no | main | codex/test-integration-notebook-studio-direct-entry-defaults-20260226 |
| 207 | [Codex/notebook back navigationfix(web): add notebook-scoped back navigation for question and guide pages](https://github.com/HKUDS/DeepTutor/pull/207) | closed | no | no | main | codex/notebook-back-navigation |
| 209 | [chore(deps): bump docker/setup-qemu-action from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/209) | closed | no | no | main | dependabot/github_actions/docker/setup-qemu-action-4 |
| 210 | [chore(deps): bump the npm-minor-patch group across 1 directory with 16 updates](https://github.com/HKUDS/DeepTutor/pull/210) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-72b74e7eed |
| 211 | [Merge 2.0-beta](https://github.com/HKUDS/DeepTutor/pull/211) | closed | no | no | dev | eval |
| 212 | [feat: add zhipu_ocr and remove knowledgebase](https://github.com/HKUDS/DeepTutor/pull/212) | closed | no | no | main | main |
| 213 | [ok](https://github.com/HKUDS/DeepTutor/pull/213) | closed | no | no | main | main |
| 214 | [feat: add MiniMax as first-class LLM provider](https://github.com/HKUDS/DeepTutor/pull/214) | closed | no | no | main | feature/add-minimax-provider |
| 215 | [feat: add Novita AI as LLM and embedding provider](https://github.com/HKUDS/DeepTutor/pull/215) | closed | no | no | main | novita-integration |
| 216 | [Sync original](https://github.com/HKUDS/DeepTutor/pull/216) | closed | no | no | main | main |
| 217 | [feat: implement SubprocessGuard for enhanced execution safety #185](https://github.com/HKUDS/DeepTutor/pull/217) | closed | no | no | main | strike/subprocess-safety-checks |
| 218 | [feat: implement UserIsolationManager for multi-user support #73](https://github.com/HKUDS/DeepTutor/pull/218) | closed | no | no | main | strike/multi-user-isolation |
| 219 | [feat: implement Arabic language and RTL support #172](https://github.com/HKUDS/DeepTutor/pull/219) | closed | no | no | main | strike/arabic-language-support |
| 220 | [docs: implement reasoning and safety checklist #199](https://github.com/HKUDS/DeepTutor/pull/220) | closed | no | no | main | strike/reasoning-safety-checklist |
| 221 | [feat: implement Flash Card generation for active study #171](https://github.com/HKUDS/DeepTutor/pull/221) | closed | no | no | main | strike/flash-card-generator |
| 222 | [feat: implement Arabic language and RTL support v2 #172](https://github.com/HKUDS/DeepTutor/pull/222) | closed | no | no | main | strike/arabic-localization-v2 |
| 223 | [feat: implement MultimodalPipeline for personalized adaptive learning #180](https://github.com/HKUDS/DeepTutor/pull/223) | closed | no | no | main | strike/multimodal-pipeline-integration |
| 224 | [feat: implement KnowledgeTracer for deep subject-agnostic mastery #173](https://github.com/HKUDS/DeepTutor/pull/224) | closed | no | no | main | strike/knowledge-tracing-engine |
| 225 | [feat: implement enhanced Markdown table editing #65](https://github.com/HKUDS/DeepTutor/pull/225) | closed | no | no | main | strike/enhanced-markdown-tables |
| 228 | [feat: implement high-fidelity SimulationEngine for practice #173](https://github.com/HKUDS/DeepTutor/pull/228) | closed | no | no | main | strike/adversarial-sim-logic |
| 229 | [chore(deps): bump docker/setup-buildx-action from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/229) | closed | no | no | main | dependabot/github_actions/docker/setup-buildx-action-4 |
| 230 | [chore(deps): bump actions/configure-pages from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/230) | closed | no | no | main | dependabot/github_actions/actions/configure-pages-6 |
| 231 | [chore(deps): bump actions/deploy-pages from 4 to 5](https://github.com/HKUDS/DeepTutor/pull/231) | closed | no | no | main | dependabot/github_actions/actions/deploy-pages-5 |
| 232 | [chore(deps): bump the npm-minor-patch group in /web with 13 updates](https://github.com/HKUDS/DeepTutor/pull/232) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-36cf6bd703 |
| 233 | [chore(deps): bump lucide-react from 0.562.0 to 1.7.0 in /web](https://github.com/HKUDS/DeepTutor/pull/233) | closed | no | no | main | dependabot/npm_and_yarn/web/lucide-react-1.7.0 |
| 234 | [chore(deps): bump typescript from 5.9.3 to 6.0.2 in /web](https://github.com/HKUDS/DeepTutor/pull/234) | closed | no | no | main | dependabot/npm_and_yarn/web/typescript-6.0.2 |
| 235 | [chore(deps): bump eslint from 9.39.2 to 10.1.0 in /web](https://github.com/HKUDS/DeepTutor/pull/235) | closed | no | no | main | dependabot/npm_and_yarn/web/eslint-10.1.0 |
| 236 | [chore(deps): bump i18next from 25.8.0 to 26.0.1 in /web](https://github.com/HKUDS/DeepTutor/pull/236) | closed | no | no | main | dependabot/npm_and_yarn/web/i18next-26.0.1 |
| 238 | [Let's meet DeepTutor 1.0.0!](https://github.com/HKUDS/DeepTutor/pull/238) | closed | yes | no | main | dev |
| 239 | [update tag](https://github.com/HKUDS/DeepTutor/pull/239) | closed | yes | no | main | dev |
| 240 | [fix(api): resolve HTTP 413 on file uploads larger than 1 MB](https://github.com/HKUDS/DeepTutor/pull/240) | closed | no | no | main | fix/170-starlette-multipart-size |
| 241 | [chore(deps): bump docker/build-push-action from 6 to 7](https://github.com/HKUDS/DeepTutor/pull/241) | closed | no | no | main | dependabot/github_actions/docker/build-push-action-7 |
| 242 | [chore(deps): bump docker/login-action from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/242) | closed | no | no | main | dependabot/github_actions/docker/login-action-4 |
| 243 | [chore(deps): bump docker/metadata-action from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/243) | closed | no | no | main | dependabot/github_actions/docker/metadata-action-6 |
| 244 | [chore(deps): bump the npm-minor-patch group in /web with 13 updates](https://github.com/HKUDS/DeepTutor/pull/244) | closed | no | no | main | dependabot/npm_and_yarn/web/npm-minor-patch-7d93cd7bc2 |
| 245 | [chore(deps): bump i18next from 25.8.0 to 26.0.3 in /web](https://github.com/HKUDS/DeepTutor/pull/245) | closed | no | no | main | dependabot/npm_and_yarn/web/i18next-26.0.3 |
| 246 | [chore(deps): bump eslint from 9.39.2 to 10.2.0 in /web](https://github.com/HKUDS/DeepTutor/pull/246) | closed | no | no | main | dependabot/npm_and_yarn/web/eslint-10.2.0 |
| 247 | [chore(deps): bump react-i18next from 16.5.3 to 17.0.2 in /web](https://github.com/HKUDS/DeepTutor/pull/247) | closed | no | no | main | dependabot/npm_and_yarn/web/react-i18next-17.0.2 |
| 248 | [chore(deps): update chardet requirement from <6.0.0,>=3.0.2 to >=3.0.2,<8.0.0](https://github.com/HKUDS/DeepTutor/pull/248) | closed | no | no | main | dependabot/pip/chardet-gte-3.0.2-and-lt-8.0.0 |
| 249 | [chore(deps): bump tailwindcss from 3.4.19 to 4.2.2 in /web](https://github.com/HKUDS/DeepTutor/pull/249) | closed | no | no | main | dependabot/npm_and_yarn/web/tailwindcss-4.2.2 |
| 250 | [fix(question-generator): support nested MinerU output in mimic mode](https://github.com/HKUDS/DeepTutor/pull/250) | closed | yes | no | dev | fix/mimic-mineru-markdown |
| 251 | [fix(deps): gate oauth-cli-kit to Python 3.11+](https://github.com/HKUDS/DeepTutor/pull/251) | closed | yes | no | dev | fix/python310-oauth-marker |
| 252 | [feat: add optional authentication with login, registration, and admin dashboard](https://github.com/HKUDS/DeepTutor/pull/252) | closed | no | no | dev | feature/simple-login-page |
| 253 | [fix: add missing imports for mimic websocket router](https://github.com/HKUDS/DeepTutor/pull/253) | closed | yes | no | dev | fix/mimic-ws-missing-imports |
| 254 | [fix: invalidate runtime caches after settings changes](https://github.com/HKUDS/DeepTutor/pull/254) | closed | yes | no | dev | fix/settings-catalog-cache-invalidation |
| 256 | [Fix Windows compatibility for Math Animator renderer](https://github.com/HKUDS/DeepTutor/pull/256) | closed | yes | no | dev | fix/windows-manim-renderer |
| 257 | [Enhance locate_agent prompt and improve agent features and UI](https://github.com/HKUDS/DeepTutor/pull/257) | closed | no | no | main | main |
| 259 | [fix(start-tour): tolerate non-UTF-8 subprocess output](https://github.com/HKUDS/DeepTutor/pull/259) | closed | yes | no | dev | fix/start-tour-decode-errors |
| 262 | [docs: clarify github copilot provider login semantics](https://github.com/HKUDS/DeepTutor/pull/262) | closed | yes | no | dev | fix/issue-261-copilot-login-docs |
| 263 | [fix: use parse_json_response for LLM outputs to handle markdown fences](https://github.com/HKUDS/DeepTutor/pull/263) | closed | yes | no | main | fix/json-parse-markdown-fences |
| 266 | [fix: Windows compatibility + Guided Learning improvements](https://github.com/HKUDS/DeepTutor/pull/266) | closed | yes | no | dev | fix/windows-manim-clean |
| 267 | [fix: enable streaming for tool-calling to fix Bailian Coding Plan endpoint errors](https://github.com/HKUDS/DeepTutor/pull/267) | closed | no | no | dev | fix/265-tool-calling-stream |
| 268 | [fix: embedding progress tracking + 429 rate limit retry](https://github.com/HKUDS/DeepTutor/pull/268) | closed | no | no | main | fix/embedding-progress-and-rate-limit |
| 270 | [Update README.md](https://github.com/HKUDS/DeepTutor/pull/270) | closed | no | no | main | patch-1 |
| 272 | [fix: use lowercased filename in mimetypes.guess_type() for consistent MIME validation](https://github.com/HKUDS/DeepTutor/pull/272) | closed | yes | no | dev | fix/issue-271-mime-type-case-insensitive |
| 275 | [fix: extend o-series regex to cover o4-mini and future o-series models](https://github.com/HKUDS/DeepTutor/pull/275) | closed | yes | no | dev | fix/issue-274-o4-mini-max-completion-tokens |
| 281 | [Prevent duplicate quiz questions by removing duplicates and adding history](https://github.com/HKUDS/DeepTutor/pull/281) | closed | yes | no | main | main |
| 282 | [test_base_agent_binding.py](https://github.com/HKUDS/DeepTutor/pull/282) | closed | no | no | main | patch-1 |
| 283 | [test_openrouter_provider.py](https://github.com/HKUDS/DeepTutor/pull/283) | closed | no | no | main | patch-2 |
| 285 | [fix(core): Resolve o4 model token bug & deeply enhance core test suite coverage](https://github.com/HKUDS/DeepTutor/pull/285) | closed | no | no | main | fix/core-tests |
| 286 | [fix: add auto-fallback for search providers without templates](https://github.com/HKUDS/DeepTutor/pull/286) | closed | yes | no | dev | fix/searxng-template-fallback |
| 287 | [v1.0.2](https://github.com/HKUDS/DeepTutor/pull/287) | closed | yes | no | main | dev |
| 288 | [feat: Add OpenAI Codex Provider & improve LaTeX rendering](https://github.com/HKUDS/DeepTutor/pull/288) | closed | no | no | main | main |
| 290 | [fix: resolve FileNotFoundError on Python 3.14+ in start_tour.py](https://github.com/HKUDS/DeepTutor/pull/290) | closed | no | no | main | fix/python-314-compatibility |
| 291 | [feat: add Korean (ko) language support](https://github.com/HKUDS/DeepTutor/pull/291) | closed | no | no | main | feat/korean-translation |
| 292 | [feat: add wrong-answer note for cross-session quiz review](https://github.com/HKUDS/DeepTutor/pull/292) | closed | yes | no | dev | feat/wrong-answer-note |
| 294 | [fix: merge system messages to comply with Qwen vLLM chat template](https://github.com/HKUDS/DeepTutor/pull/294) | closed | no | no | dev | fix/qwen-vllm-system-message-from-dev |
| 295 | [fix: merge system messages and add history reference fallback](https://github.com/HKUDS/DeepTutor/pull/295) | closed | yes | no | dev | fix/history-reference-empty-context |
| 297 | [feat: integrate LightRAG pipeline, Mermaid diagrams, and Liquid Glass…](https://github.com/HKUDS/DeepTutor/pull/297) | closed | no | no | main | main |
| 298 | [feat:Added goal-oriented learning with constraints and high-frequency key point extraction.](https://github.com/HKUDS/DeepTutor/pull/298) | open | no | no | dev | feat/derivative-student-exam-customization |
| 299 | [feat: detect embedding model mismatch in knowledge bases](https://github.com/HKUDS/DeepTutor/pull/299) | closed | yes | no | dev | feat/embedding-model-mismatch-detection |
| 302 | [fix: resolve FileNotFoundError crash on setup script in Python 3.14](https://github.com/HKUDS/DeepTutor/pull/302) | closed | no | no | main | fix/python-314-compat |
| 303 | [chore: stabilize testing pipeline and clean up technical debt](https://github.com/HKUDS/DeepTutor/pull/303) | closed | no | no | main | chore/test-stabilization |
| 305 | [docs: add long-horizon reasoning and safety checklist](https://github.com/HKUDS/DeepTutor/pull/305) | closed | no | no | dev | docs/issue-199-reasoning-safety-checklist |
| 306 | [fix: pass extra_headers to llm_complete in config test runner](https://github.com/HKUDS/DeepTutor/pull/306) | closed | no | no | dev | fix/test-runner-extra-headers |
| 307 | [fix: pass extra_headers to llm_complete in config test runner](https://github.com/HKUDS/DeepTutor/pull/307) | closed | yes | no | dev | fix/test-runner-extra-headers |
| 309 | [fix: handle npm.cmd correctly on Windows](https://github.com/HKUDS/DeepTutor/pull/309) | closed | yes | no | dev | fix/windows-npm-cmd |
| 310 | [fix: prefer unresolved sys.executable to stay inside venv](https://github.com/HKUDS/DeepTutor/pull/310) | closed | yes | no | dev | fix/resolve-python-venv-symlink |
| 311 | [Feature/passive agent](https://github.com/HKUDS/DeepTutor/pull/311) | closed | no | no | main | feature/passive_agent |
| 315 | [fix: oauth-cli-kit>=0.2.0 does not exist, lower to >=0.1.1](https://github.com/HKUDS/DeepTutor/pull/315) | closed | yes | no | dev | fix/oauth-cli-kit-version |
| 319 | [perf(web): fix severe input lag in long conversations (#317)](https://github.com/HKUDS/DeepTutor/pull/319) | closed | yes | no | dev | perf/fix-input-lag-317 |
| 320 | [Fix typo: Chinses -> Chinese](https://github.com/HKUDS/DeepTutor/pull/320) | closed | yes | no | dev | fix-typo-chinese |
| 321 | [feat(diagnostics): make LLM probe max_tokens configurable via env](https://github.com/HKUDS/DeepTutor/pull/321) | closed | yes | no | dev | feat/llm-test-max-tokens |
| 322 | [fix(embedding): skip `dimensions` for models that don't support matryoshka](https://github.com/HKUDS/DeepTutor/pull/322) | closed | no | no | main | feat/embed-matryoshka-whitelist |
| 323 | [fix(web): improve robust parsing for LaTeX block math and headings](https://github.com/HKUDS/DeepTutor/pull/323) | closed | yes | no | dev | fix/latex-rendering |
| 325 | [fix(embedding): drop `dimensions` on HTTP 400 and latch on success](https://github.com/HKUDS/DeepTutor/pull/325) | closed | no | no | main | feat/embed-retry-on-dimensions |
| 329 | [feat: Add Structure Note with VectifyAI PageIndex](https://github.com/HKUDS/DeepTutor/pull/329) | open | no | no | dev | feat/add-structure-note |
| 330 | [fix(web): resolve 15 npm security vulnerabilities](https://github.com/HKUDS/DeepTutor/pull/330) | closed | yes | no | dev | fix/npm-security-vulnerabilities |
| 332 | [Fix: TutorBot channel config wiped on every server restart](https://github.com/HKUDS/DeepTutor/pull/332) | closed | yes | no | dev | fix/tutorbot-config-wipe |
| 335 | [fix(api): add missing http_version arg in selective_access_log middleware](https://github.com/HKUDS/DeepTutor/pull/335) | closed | yes | no | dev | fix/selective-access-log-unpack |
| 336 | [feat: add optional authentication with login, registration, and admin dashboard](https://github.com/HKUDS/DeepTutor/pull/336) | closed | yes | no | multi-user | feature/auth-multiuser |
| 337 | [docs: add Thai README documentation](https://github.com/HKUDS/DeepTutor/pull/337) | closed | yes | no | dev | docs/thai-readme |
| 338 | [feat(tutorbot): Channels tab, Telegram UI, API channel reload, token …](https://github.com/HKUDS/DeepTutor/pull/338) | closed | yes | no | dev | srinikul/feature-333 |
| 340 | [Fix #296: [Bug]:LLM 0, EMBEDDING 0, SEARCH 0](https://github.com/HKUDS/DeepTutor/pull/340) | closed | yes | no | dev | fix/296-bug-llm-0-embedding-0-search-0 |
| 341 | [release: v1.1.2 — CI fix & release notes cleanup](https://github.com/HKUDS/DeepTutor/pull/341) | closed | yes | no | main | dev |
| 343 | [feat(i18n): add Russian (ru) locale](https://github.com/HKUDS/DeepTutor/pull/343) | closed | no | no | dev | feat/i18n-russian-locale |
| 345 | [fix: disable json_object response_format for gemma models](https://github.com/HKUDS/DeepTutor/pull/345) | closed | yes | no | dev | fix/issue-344-gemma-response-format |
| 347 | [fix(rag): guard against None embeddings in LlamaIndex pipeline](https://github.com/HKUDS/DeepTutor/pull/347) | closed | yes | no | dev | fix/embedding-none-guard |
| 348 | [feat(chat): make per-stage token limits and temperature configurable via agents.yaml](https://github.com/HKUDS/DeepTutor/pull/348) | closed | yes | no | dev | feat/configurable-chat-token-limits |
| 349 | [feat(chat): regenerate last response (CLI, WebSocket, Web UI)](https://github.com/HKUDS/DeepTutor/pull/349) | closed | yes | no | dev | feat/chat-regenerate-response |
| 352 | [fix(web): ensure readable text in dark code blocks on light theme](https://github.com/HKUDS/DeepTutor/pull/352) | closed | yes | no | dev | fix/dark-code-block-text-contrast |
| 353 | [fix: add ConnectError to embedding retry exceptions](https://github.com/HKUDS/DeepTutor/pull/353) | closed | yes | no | dev | fix/embedding-connecterror-retry |
| 354 | [fix : Tutorbot websocket resilience and CLI config parsing edge case](https://github.com/HKUDS/DeepTutor/pull/354) | closed | yes | no | dev | srini/fix-websocket-reconnect |
| 355 | [feat: Hide the API key on settings page](https://github.com/HKUDS/DeepTutor/pull/355) | closed | yes | no | dev | srini/feature-hide-api-key |
| 360 | [perf(web): decouple chat input state to resolve lag in long conversat…](https://github.com/HKUDS/DeepTutor/pull/360) | closed | yes | no | dev | perf/optimize-chat-input |
| 361 | [Perf/optimize chat input](https://github.com/HKUDS/DeepTutor/pull/361) | closed | no | no | dev | perf/optimize-chat-input |
| 362 | [Perf/optimize chat input](https://github.com/HKUDS/DeepTutor/pull/362) | closed | yes | no | dev | perf/optimize-chat-input |
| 367 | [fix #366: addressing issue](https://github.com/HKUDS/DeepTutor/pull/367) | closed | no | no | main | fix-366 |
| 368 | [fix(embedding): gate dimensions for text-embedding-3 models](https://github.com/HKUDS/DeepTutor/pull/368) | closed | yes | no | dev | codex/openai-compatible-dimensions |
| 371 | [feat(cli): add add-md and replace-md commands to notebook group](https://github.com/HKUDS/DeepTutor/pull/371) | closed | yes | no | dev | feat/notebook-add-md |
| 373 | [feat: Revamp soul template creation and usage](https://github.com/HKUDS/DeepTutor/pull/373) | closed | yes | no | dev | srinikul/soul-template-editor |
| 374 | [Frictionless Onboarding](https://github.com/HKUDS/DeepTutor/pull/374) | closed | no | no | main | main |
| 376 | [fix(scripts): prefer uv pip over python -m pip in start_tour.py](https://github.com/HKUDS/DeepTutor/pull/376) | closed | yes | no | dev | fix/uv-pip-compat |
| 378 | [[ImgBot] Optimize images](https://github.com/HKUDS/DeepTutor/pull/378) | closed | no | no | main | main |
| 379 | [docs: add Polish translation of README](https://github.com/HKUDS/DeepTutor/pull/379) | closed | yes | no | dev | docs/polish-readme-translation |
| 381 | [fix: use npm.cmd for version detection on Windows](https://github.com/HKUDS/DeepTutor/pull/381) | closed | yes | no | dev | fix/npm-cmd-detection-windows |
| 382 | [fix: restore theme-aware backgrounds for form elements and visualization](https://github.com/HKUDS/DeepTutor/pull/382) | closed | no | no | dev | fix/issue-363-dark-theme-input-bg |
| 388 | [docs: add Polish language link to main README](https://github.com/HKUDS/DeepTutor/pull/388) | closed | no | no | dev | docs/add-polish-link |
| 390 | [[codex] Normalize Azure OpenAI max token aliases](https://github.com/HKUDS/DeepTutor/pull/390) | closed | no | yes | main | codex-azure-openai-max-token-normalization |
| 391 | [fix: server startup on Windows + missing runtime deps in server.txt](https://github.com/HKUDS/DeepTutor/pull/391) | closed | yes | no | dev | fix/server-deps-and-utf8-encoding |
| 393 | [Fix/test pollution and math animator](https://github.com/HKUDS/DeepTutor/pull/393) | closed | no | no | main | fix/test-pollution-and-math-animator-v2 |
| 396 | [Improve mobile responsiveness](https://github.com/HKUDS/DeepTutor/pull/396) | closed | no | no | dev | dev |
| 404 | [fix(research): use f-string in reporting_agent logger.warning call](https://github.com/HKUDS/DeepTutor/pull/404) | closed | no | no | dev | fix/reporting-agent-logger-warning |
| 407 | [doc: Link CLAUDE.md to AGENTS.md](https://github.com/HKUDS/DeepTutor/pull/407) | closed | no | no | main | patch-1 |
| 409 | [refactor(storage): Add PostgreSQL support](https://github.com/HKUDS/DeepTutor/pull/409) | open | no | yes | dev | feat/postgres-support |
| 416 | [Fix stale embedding client during knowledge base indexing](https://github.com/HKUDS/DeepTutor/pull/416) | closed | no | no | main | fix/stale-embedding-client |
| 420 | [feat: add NVIDIA NIM provider with streaming support](https://github.com/HKUDS/DeepTutor/pull/420) | closed | yes | no | dev | feat/nvidia-nim-provider |
| 421 | [fix: handle non-string message content in TutorBot chat](https://github.com/HKUDS/DeepTutor/pull/421) | closed | yes | no | dev | fix/tutorbot-non-string-content |
| 422 | [fix: Add C++ compiler prerequisite in readme](https://github.com/HKUDS/DeepTutor/pull/422) | closed | yes | no | dev | srinikul/readme-update |
| 423 | [fix(deps): relax numpy upper bound to resolve manim conflict](https://github.com/HKUDS/DeepTutor/pull/423) | closed | yes | no | dev | srinikul/fix-python-requirements |
| 424 | [feat(embedding): add Gemini embedding provider support across runtime](https://github.com/HKUDS/DeepTutor/pull/424) | closed | yes | no | dev | srinikul/gemini-embeddings |
| 425 | [Claude/update docs after sync 4p zdz](https://github.com/HKUDS/DeepTutor/pull/425) | closed | no | no | main | claude/update-docs-after-sync-4pZDZ |
| 428 | [fix: fallback content to reasoning_content when DeepSeek returns empty content field](https://github.com/HKUDS/DeepTutor/pull/428) | closed | yes | no | dev | fix/deepseek-reasoning-content-fallback |
| 432 | [feat: SAGE Memory Companion plugin + Playground tile](https://github.com/HKUDS/DeepTutor/pull/432) | open | no | no | dev | sage-memory-companion |
| 435 | [fix: paint settings select dark-mode dropdown popover background](https://github.com/HKUDS/DeepTutor/pull/435) | closed | yes | no | dev | fix/settings-select-dark-mode-popover |
| 436 | [fix(chat): forward extra_headers to all LLM calls in agentic pipeline](https://github.com/HKUDS/DeepTutor/pull/436) | closed | yes | no | dev | fix/chat-extra-headers |
| 438 | [fix(llm): map max_completion_tokens to max_output_tokens for Responses API](https://github.com/HKUDS/DeepTutor/pull/438) | closed | yes | no | dev | fix/responses-api-max-completion-tokens-mapping |
| 439 | [fix(ui): skill editor validation and modal background](https://github.com/HKUDS/DeepTutor/pull/439) | closed | yes | no | dev | fix/skill-ui-validation-and-modal |
| 441 | [fix(agents): normalize single newlines to markdown paragraphs in quiz content](https://github.com/HKUDS/DeepTutor/pull/441) | closed | yes | no | dev | fix/quiz-question-paragraph-spacing |
| 442 | [fix: raise context_window ceiling and add qwen vision support](https://github.com/HKUDS/DeepTutor/pull/442) | closed | yes | no | dev | fix/context-window-vision-upstream |
| 443 | [feat: add delete chat turn functionality with attachment cleanup](https://github.com/HKUDS/DeepTutor/pull/443) | closed | yes | no | dev | feat/delete-chat-turn |
| 445 | [feat: add deeptutor start command to launch backend and frontend together](https://github.com/HKUDS/DeepTutor/pull/445) | closed | yes | no | dev | feat/cli-start-command |
| 447 | [fix: add deepseek-v4-flash and deepseek-v4-pro to model pricing table](https://github.com/HKUDS/DeepTutor/pull/447) | closed | yes | no | dev | fix/add-deepseek-v4-pricing |
| 449 | [fix(web): preserve newlines in user chat messages](https://github.com/HKUDS/DeepTutor/pull/449) | closed | yes | no | dev | fix/user-message-newline-444 |
| 450 | [Feature/critic agent](https://github.com/HKUDS/DeepTutor/pull/450) | closed | no | no | main | feature/critic-agent |
| 452 | [feat(tutorbot): add Zulip channel support](https://github.com/HKUDS/DeepTutor/pull/452) | closed | yes | no | dev | feat/add-zulip-channel |
| 453 | [fix(llm): stop sending reasoning_effort=minimal as top-level param to providers that reject it](https://github.com/HKUDS/DeepTutor/pull/453) | closed | yes | no | dev | fix/deepseek-reasoning-effort-minimal |
| 454 | [feat(desktop): add Electron desktop shell with sidebar, webview & macOS traffic light supportDesktop dev](https://github.com/HKUDS/DeepTutor/pull/454) | open | no | no | dev | desktop-dev |
| 455 | [fix: add TutorBot NVIDIA NIM provider support](https://github.com/HKUDS/DeepTutor/pull/455) | closed | yes | no | dev | codex/tutorbot-nvidia-nim |
| 456 | [feat: tooltips appear on hover for sidebar items](https://github.com/HKUDS/DeepTutor/pull/456) | closed | no | yes | main | feature/sidebar-tooltips |
| 457 | [feat: tooltips for sidebar](https://github.com/HKUDS/DeepTutor/pull/457) | closed | yes | no | dev | feature/sidebar-tooltips |
| 458 | [Feature/heartbeat](https://github.com/HKUDS/DeepTutor/pull/458) | closed | no | no | main | feature/heartbeat |
| 459 | [feat(api): add mobile turn event facade](https://github.com/HKUDS/DeepTutor/pull/459) | open | no | no | dev | codex/mobile-turn-events |
| 460 | [Feature/heartbeat](https://github.com/HKUDS/DeepTutor/pull/460) | closed | no | no | dev | feature/heartbeat |
| 461 | [chore: add py313 and py314 to Black target-version](https://github.com/HKUDS/DeepTutor/pull/461) | closed | no | no | dev | chore/py313-py314-tool-targets |
| 465 | [fix(ssl): extend DISABLE_SSL_VERIFY coverage to codex provider and four embedding adapters](https://github.com/HKUDS/DeepTutor/pull/465) | closed | yes | no | dev | fix/disable-ssl-verify-sweep |
| 466 | [Feature/arch linux](https://github.com/HKUDS/DeepTutor/pull/466) | closed | no | no | dev | feature/arch-linux |
| 467 | [Feature/critic agent](https://github.com/HKUDS/DeepTutor/pull/467) | closed | no | no | dev | feature/critic-agent |
| 469 | [fix: prevent citation markers from being injected into fenced code bl…](https://github.com/HKUDS/DeepTutor/pull/469) | closed | no | no | main | fix/citation-in-code-blocks |
| 470 | [Repair pnpm checks and provider runtime integration](https://github.com/HKUDS/DeepTutor/pull/470) | closed | no | no | main | contrib/upstream-check-repairs |
| 474 | [fix: 系统性修复多用户数据隔离问题](https://github.com/HKUDS/DeepTutor/pull/474) | closed | yes | no | dev | fix/mu-data |
| 477 | [fix(zulip): 弃用，重新PR](https://github.com/HKUDS/DeepTutor/pull/477) | closed | no | no | main | fix/zulip-attachment-upload-error |
| 478 | [fix: allow quiz answer textarea vertical resize](https://github.com/HKUDS/DeepTutor/pull/478) | closed | yes | no | dev | fix/quiz-textarea-vertical-resize |
| 479 | [弃用](https://github.com/HKUDS/DeepTutor/pull/479) | closed | no | no | dev | fix/zulip-attachment-clean |
| 480 | [fix(zulip): 修复 Zulip 通道附件上传与消息发送的 BUG，支持 Bot 自动订阅频道](https://github.com/HKUDS/DeepTutor/pull/480) | closed | yes | no | dev | fix/zulip-upload-and-send |
| 482 | [docs: add developer quick start guide for DeepTutor](https://github.com/HKUDS/DeepTutor/pull/482) | closed | no | no | main | agents/chinese-dev-quickstart-guide |
| 484 | [fix(zulip): 增加内容检测fallback解决Generic bot收不到mention flag问题](https://github.com/HKUDS/DeepTutor/pull/484) | closed | yes | no | dev | fix/zulip-upload-and-send |
| 485 | [fix(auth): make require_auth async so the user ContextVar reaches the endpoint](https://github.com/HKUDS/DeepTutor/pull/485) | closed | yes | no | dev | fix/auth-contextvar-async-481 |
| 488 | [feat(visualize): replace free-form HTML generation with standardized JSON widget spec framework](https://github.com/HKUDS/DeepTutor/pull/488) | open | no | no | dev | feat/visualize-framework-dev |
| 490 | [fix(visualize): unblock Gemini 2.5+ and harden Visualize pipeline](https://github.com/HKUDS/DeepTutor/pull/490) | closed | yes | no | dev | fix/gemini-2.5-thinking-tokens |
| 491 | [[codex] Add complete Arabic language support](https://github.com/HKUDS/DeepTutor/pull/491) | closed | no | yes | main | codex/complete-arabic-support |
| 492 | [feat: add chat retrieval controls and summary](https://github.com/HKUDS/DeepTutor/pull/492) | open | no | no | dev | feat/chat-retrieval-modes |
| 493 | [Fix SQLite FD Exhaustion](https://github.com/HKUDS/DeepTutor/pull/493) | closed | yes | yes | dev | fix/fd-exhaustion |
| 499 | [fix(web): reset quiz answer state when new quiz is generated in same chat](https://github.com/HKUDS/DeepTutor/pull/499) | closed | no | no | dev | fix/quiz-state-inheritance |
| 500 | [Feature/guided learning](https://github.com/HKUDS/DeepTutor/pull/500) | closed | yes | no | dev | feature/guided-learning |
| 501 | [fix: prevent sed from corrupting API_BASE placeholder validation](https://github.com/HKUDS/DeepTutor/pull/501) | closed | no | no | dev | fix/sed-placeholder-validation-bug-dev |
| 507 | [fix(security): harden ExecTool defaults against command injection (#506)](https://github.com/HKUDS/DeepTutor/pull/507) | closed | yes | no | dev | fix/harden-exec-tool-security |
| 508 | [Fix GPT-5 token limit parameter in init wizard probe](https://github.com/HKUDS/DeepTutor/pull/508) | closed | yes | no | dev | fix-openai-gpt5-token-param |
| 509 | [fix: prevent Document nodes from bypassing chunking pipeline](https://github.com/HKUDS/DeepTutor/pull/509) | closed | yes | no | dev | fix/ingestion-chunking-bypass |
| 510 | [feat: add pluggable TTS tool with multi-provider support](https://github.com/HKUDS/DeepTutor/pull/510) | open | no | no | dev | feat/tts-tool |
| 513 | [fix(settings): add profile button when no profiles exist](https://github.com/HKUDS/DeepTutor/pull/513) | closed | yes | no | dev | fix/add-profile-button-empty-state |
| 519 | [fix: route Anthropic-backend providers through native SDK in agentic loop](https://github.com/HKUDS/DeepTutor/pull/519) | closed | no | no | main | Branch_v1.4.0 |
| 522 | [feat: support zip upload with error-state recovery and recursive file scanning](https://github.com/HKUDS/DeepTutor/pull/522) | closed | no | no | main | feat/zip-upload |
| 523 | [Improve settings model fetching and question notebook lookup UX](https://github.com/HKUDS/DeepTutor/pull/523) | closed | no | no | main | main |
| 524 | [feat: truncate oversized event payloads in session response](https://github.com/HKUDS/DeepTutor/pull/524) | closed | yes | no | dev | feat/session-truncation |
| 525 | [feat: embed local Markdown image references as data URIs during indexing](https://github.com/HKUDS/DeepTutor/pull/525) | open | no | no | dev | feat/markdown-image-embedding |
| 526 | [fix: correct isinstance check in documents_to_nodes to fix KB indexing](https://github.com/HKUDS/DeepTutor/pull/526) | closed | no | no | dev | fix/kb-indexing-isinstance-check |
| 528 | [fix(chat): enable native tool calling for reasoning models via OpenAI-compatible endpoints](https://github.com/HKUDS/DeepTutor/pull/528) | closed | yes | no | dev | fix/qwen-tool-call |
| 529 | [fix: Qwen model JSON preamble, force-recompile overview pages, health false positives](https://github.com/HKUDS/DeepTutor/pull/529) | closed | yes | no | dev | fix/local-patches-win-utf8 |
| 533 | [chore: ignore local development artifacts](https://github.com/HKUDS/DeepTutor/pull/533) | closed | no | no | dev | chore/ignore-local-dev-artifacts-mainbase |
| 538 | [fix(tutorbot): correct question_type → question_types in deep-question SKILL.md](https://github.com/HKUDS/DeepTutor/pull/538) | closed | no | no | dev | fix/deep-question-skill-param-name |
| 539 | [feat: add dynamic_router compat gateway](https://github.com/HKUDS/DeepTutor/pull/539) | closed | no | no | main | main |
| 540 | [fix(web): preserve math before citation linkification](https://github.com/HKUDS/DeepTutor/pull/540) | closed | yes | no | dev | fix/math-citation-rendering |
| 541 | [fix(chat): route OAuth backend through native provider](https://github.com/HKUDS/DeepTutor/pull/541) | closed | no | yes | dev | fix/chat-provider-routing |
| 542 | [fix(chat): route OAuth backend through native provider](https://github.com/HKUDS/DeepTutor/pull/542) | closed | yes | no | dev | fix/chat-oauth-native-provider |
| 543 | [feat: upgrade MiniMax default model to M3](https://github.com/HKUDS/DeepTutor/pull/543) | closed | yes | no | dev | feature/upgrade-minimax-m3 |
| 544 | [fix: 将 Heartbeat 通知广播到所有已绑定的 Channel](https://github.com/HKUDS/DeepTutor/pull/544) | closed | no | no | dev | fix/heartbeat-channel-broadcast |
| 545 | [[codex] Add German UI and LLM localization](https://github.com/HKUDS/DeepTutor/pull/545) | closed | no | yes | dev | codex/german-localization-upstream |
| 546 | [[codex] Add German UI and LLM localization](https://github.com/HKUDS/DeepTutor/pull/546) | closed | no | no | dev | dev |
| 547 | [[codex] Add German UI and LLM localization](https://github.com/HKUDS/DeepTutor/pull/547) | closed | no | yes | dev | dev |
| 548 | [feat(web): use dropdown for UI language selection](https://github.com/HKUDS/DeepTutor/pull/548) | closed | no | no | dev | feat/ui-language-dropdown |
| 549 | [fix: keep NEXT_PUBLIC_AUTH_ENABLED out of the minifier constant-fold](https://github.com/HKUDS/DeepTutor/pull/549) | closed | yes | no | dev | fix/auth-enabled-build-flag |
| 550 | [fix: sidebar footer items stay as text when the sidebar is collapsed](https://github.com/HKUDS/DeepTutor/pull/550) | closed | yes | no | dev | fix/sidebar-footer-collapse |
| 551 | [fix(tutorbot): auto-start bots for all users in multi-user mode](https://github.com/HKUDS/DeepTutor/pull/551) | closed | no | no | dev | fix/multi-user-auto-start |
| 556 | [refactor: outbound broadcast routing for multi-channel heartbeat delivery](https://github.com/HKUDS/DeepTutor/pull/556) | closed | no | no | dev | refact/heartbeat-broadcast-router |
| 557 | [fix(llm): fit token budgets to 8192 vLLM ctx + repair vision config](https://github.com/HKUDS/DeepTutor/pull/557) | closed | no | no | main | fix/vllm-8k-token-budgets-and-vision-config |
| 558 | [fix: surface bad-login error inline instead of silent page reload](https://github.com/HKUDS/DeepTutor/pull/558) | closed | yes | no | dev | fix/login-401-no-error-message |
| 559 | [fix: accept username, not just email, on login and register forms](https://github.com/HKUDS/DeepTutor/pull/559) | closed | yes | no | dev | fix/login-username-input |
| 560 | [feat: Heartbeat Settings WebUI — configurable interval & model](https://github.com/HKUDS/DeepTutor/pull/560) | closed | no | no | dev | feat/heartbeat-settings |
| 561 | [Enhance knowledge base management and Co-Scientist capabilities](https://github.com/HKUDS/DeepTutor/pull/561) | closed | no | yes | main | main |
| 563 | [Oxca/tutor inline quiz history](https://github.com/HKUDS/DeepTutor/pull/563) | open | no | no | dev | oxca/tutor-inline-quiz-history |
| 564 | [Fix TutorBot shell exec persistence](https://github.com/HKUDS/DeepTutor/pull/564) | closed | no | no | main | fix/allow-shell-exec-persistence |
| 566 | [feat(partners): Partner 多用户隔离 — 按用户 scope 存储 partner 数据](https://github.com/HKUDS/DeepTutor/pull/566) | closed | no | no | dev | partner-multi-user-isolation |
| 568 | [fix: gate LLM features for users without an assigned model](https://github.com/HKUDS/DeepTutor/pull/568) | closed | yes | no | dev | fix/capability-access-gating |
| 570 | [fix: show only provider-relevant fields in Search settings](https://github.com/HKUDS/DeepTutor/pull/570) | closed | yes | no | dev | fix/search-settings-conditional-fields |
| 571 | [feat: discoverable profile rename and auto-name by provider](https://github.com/HKUDS/DeepTutor/pull/571) | closed | yes | no | dev | feat/settings-profile-naming |
| 572 | [fix: translate missing English settings-tour steps](https://github.com/HKUDS/DeepTutor/pull/572) | closed | yes | no | dev | fix/settings-tour-en-placeholders |
| 573 | [feat: user profile page with avatar (account info, icon/image avatar, sign out)](https://github.com/HKUDS/DeepTutor/pull/573) | closed | yes | no | dev | feat/profile-page |
| 577 | [feat(deploy): harden image for rootless podman with read-only rootfs](https://github.com/HKUDS/DeepTutor/pull/577) | closed | yes | no | dev | feature/rootless-podman-hardening |
| 578 | [feat: 聊天历史加载动画支持](https://github.com/HKUDS/DeepTutor/pull/578) | closed | yes | no | dev | feat/session-loading-overlay |
| 579 | [[security] fix(multi-user): deny MCP tools until explicitly granted](https://github.com/HKUDS/DeepTutor/pull/579) | closed | yes | no | dev | fix/mcp-tool-grants-deny-default |
| 581 | [fix(deploy): /var/run tmpfs mode 0755 → 1777 so supervisord can write pidfile as UID 1000](https://github.com/HKUDS/DeepTutor/pull/581) | closed | no | no | dev | fix/var-run-mode |
| 582 | [fix: run supervisord as root so services start under rootful Docker](https://github.com/HKUDS/DeepTutor/pull/582) | closed | yes | no | dev | fix/docker-rootful-supervisord |
| 583 | [feat: redesign User Management page (avatars, search, skeleton, confirm dialog)](https://github.com/HKUDS/DeepTutor/pull/583) | closed | yes | no | dev | feat/admin-users-redesign |
| 584 | [fix(llm): enable native tool calls for SiliconFlow](https://github.com/HKUDS/DeepTutor/pull/584) | closed | yes | no | dev | fix/siliconflow-native-tools |
| 585 | [refactor: move Back link to its own row in the page header](https://github.com/HKUDS/DeepTutor/pull/585) | closed | yes | no | dev | refactor/profile-header |
| 586 | [feat(docker): make BACKEND_HOST and FRONTEND_HOST env-configurable](https://github.com/HKUDS/DeepTutor/pull/586) | closed | yes | no | dev | feature/bind-host-config |
| 588 | [fix: render LaTeX in quiz options](https://github.com/HKUDS/DeepTutor/pull/588) | closed | yes | no | dev | fix/587-quiz-option-latex |
| 593 | [fix(docker): make supervisord config portable across rootful + rootless keep-id](https://github.com/HKUDS/DeepTutor/pull/593) | closed | yes | no | dev | fix/gosu-nonroot-skip |
| 600 | [Adaptive diagnostic: prefer nearest difficulty on fallback](https://github.com/HKUDS/DeepTutor/pull/600) | closed | no | no | main | feat/adaptive-diagnostic-nearest-difficulty |
| 601 | [feat(cowriter): export markdown drafts as PDF](https://github.com/HKUDS/DeepTutor/pull/601) | closed | no | yes | main | feat/cowriter-pdf-export |
| 602 | [fix: preserve zero LlamaIndex chunk overlap](https://github.com/HKUDS/DeepTutor/pull/602) | closed | yes | no | dev | codex/fix-chunk-overlap-zero |
| 604 | [[codex] fix mastery choice persistence and grading](https://github.com/HKUDS/DeepTutor/pull/604) | closed | yes | no | dev | codex/fix-mastery-choice-persistence |
| 608 | [fix(web): avoid crashes on malformed Markdown hash links](https://github.com/HKUDS/DeepTutor/pull/608) | closed | yes | no | dev | codex/markdown-safe-hash-decode |
| 609 | [fix(config): preserve KB default fallbacks](https://github.com/HKUDS/DeepTutor/pull/609) | closed | no | no | dev | codex/kb-config-empty-defaults |
| 614 | [Feat/agentkit tracer 1](https://github.com/HKUDS/DeepTutor/pull/614) | closed | no | no | main | feat/agentkit-tracer-1 |
| 615 | [fix(webui): send edited user message on Enter, keep Shift+Enter as newline](https://github.com/HKUDS/DeepTutor/pull/615) | closed | yes | no | dev | fix/edit-message-enter-send |
| 617 | [fix: count streamed LLM usage once per completion](https://github.com/HKUDS/DeepTutor/pull/617) | closed | yes | no | dev | fix/stream-usage-double-count |
| 619 | [fix(knowledge): persist linked folder sync state updates](https://github.com/HKUDS/DeepTutor/pull/619) | closed | yes | no | dev | fix/persist-linked-folder-sync-state |
| 620 | [fix(knowledge): make KB configuration updates atomic and race-safe](https://github.com/HKUDS/DeepTutor/pull/620) | open | no | no | dev | fix/kb-config-atomic-store |
| 622 | [fix: restore recency weighting in compute_mastery (#618)](https://github.com/HKUDS/DeepTutor/pull/622) | closed | yes | no | dev | fix/mastery-recency-weighting |
| 625 | [fix: set Secure attribute when clearing dt_token on logout](https://github.com/HKUDS/DeepTutor/pull/625) | closed | yes | no | dev | fix/logout-cookie-secure-samesite |
| 626 | [fix(llm): enable OpenAI Codex native tool calls](https://github.com/HKUDS/DeepTutor/pull/626) | closed | yes | no | dev | fix/openai-codex-native-tools |
| 627 | [feat(pageindex): retrieval via MCP tools + full document-endpoint format support](https://github.com/HKUDS/DeepTutor/pull/627) | closed | yes | no | dev | feat/pageindex-mcp-retrieval |
| 628 | [fix: resolve relative img_path in parsed content lists to absolute paths](https://github.com/HKUDS/DeepTutor/pull/628) | closed | yes | no | dev | fix/624-mineru-image-paths |
| 629 | [docs: quote pip extras install examples](https://github.com/HKUDS/DeepTutor/pull/629) | closed | yes | no | dev | nyxst4ck/auto-quote-pip-extras-20260715-094558 |
| 631 | [fix(partners): align WeCom with SDK 1.0.8](https://github.com/HKUDS/DeepTutor/pull/631) | closed | yes | no | dev | agent/fix-wecom-sdk-startup |
| 632 | [Add GitHub Actions workflow for Python package publishing](https://github.com/HKUDS/DeepTutor/pull/632) | open | no | no | dev | main |
| 633 | [fix: chat page not full width, scrollbar only works in middle area](https://github.com/HKUDS/DeepTutor/pull/633) | closed | no | no | main | fix/chat-full-width-scroll |
| 634 | [fix: chat page not full width, scrollbar only works in middle area](https://github.com/HKUDS/DeepTutor/pull/634) | closed | yes | no | dev | fix/chat-full-width-scroll |
| 635 | [fix(knowledge): update KB status to processing on file upload and sync-folder](https://github.com/HKUDS/DeepTutor/pull/635) | closed | yes | no | dev | fix/kb-upload-status |
| 636 | [fix(book): reset page status on compilation failure (worker + inline)](https://github.com/HKUDS/DeepTutor/pull/636) | closed | yes | no | dev | fix/book-page-stuck-generating |
| 637 | [Fix recency-weighting variable swap in compute_mastery](https://github.com/HKUDS/DeepTutor/pull/637) | open | no | no | dev | fix/618-recency-weighting-unpack |
| 638 | [feat: add Voice Tutor capability and Desmos Graph integration](https://github.com/HKUDS/DeepTutor/pull/638) | open | no | no | dev | ilk-katki |
| 642 | [fix: support newer Anthropic models via the official SDK](https://github.com/HKUDS/DeepTutor/pull/642) | closed | yes | no | dev | fix/anthropic-newer-model-support |
| 643 | [feat: add sql_query tool — persistent in-chat SQLite with Chart.js visualization](https://github.com/HKUDS/DeepTutor/pull/643) | closed | no | no | main | feature/sql-query-tool |
| 644 | [fix(partners): avoid hang in split_message when max_len <= 0](https://github.com/HKUDS/DeepTutor/pull/644) | closed | yes | no | dev | fix/split-message-nonpositive-maxlen-dev |
| 645 | [fix(memory): parse line-edit JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/645) | closed | yes | no | dev | fix/line-doc-raw-decode-edits-dev |
| 646 | [fix(memory): parse update facts JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/646) | closed | yes | no | dev | fix/update-facts-raw-decode-dev |
| 648 | [Add a theme selector for code blocks](https://github.com/HKUDS/DeepTutor/pull/648) | closed | yes | no | dev | feat/code_block_theme |
| 652 | [fix(embedding): don't send encoding_format by default for OpenAI-compatible providers](https://github.com/HKUDS/DeepTutor/pull/652) | closed | yes | no | dev | fix/siliconflow-encoding-format |
| 654 | [Add Atlas Cloud LLM provider](https://github.com/HKUDS/DeepTutor/pull/654) | closed | yes | no | dev | codex/add-atlascloud-provider |
| 657 | [fix: require explicit OpenAI Codex selection](https://github.com/HKUDS/DeepTutor/pull/657) | closed | yes | no | dev | fix/codex-url-provider-detection |
| 658 | [fix(book): stream long-running operations over WebSocket](https://github.com/HKUDS/DeepTutor/pull/658) | closed | yes | no | dev | fix/book-websocket-long-operations-dev |
| 662 | [fix(cli): catch UnicodeDecodeError in REPL input loop](https://github.com/HKUDS/DeepTutor/pull/662) | closed | no | no | main | fix/cli-unicode-decode-error |
| 663 | [fix(cli): harden UTF-8 terminal input handling](https://github.com/HKUDS/DeepTutor/pull/663) | closed | yes | no | dev | fix/cli-utf8-terminal-input |
| 667 | [fix(question): parse quiz JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/667) | closed | yes | no | dev | fix/quiz-payload-raw-decode |
| 668 | [fix(utils): decode trailing-prose JSON before repair](https://github.com/HKUDS/DeepTutor/pull/668) | closed | yes | no | dev | fix/json-parser-raw-decode-trailing |
| 669 | [fix(visualize): allow code fences without a blank closing line](https://github.com/HKUDS/DeepTutor/pull/669) | closed | yes | no | dev | fix/extract-code-block-optional-newline |
| 670 | [fix(partners): strip control chars in safe_filename](https://github.com/HKUDS/DeepTutor/pull/670) | closed | yes | no | dev | fix/safe-filename-strip-controls |
| 671 | [feat: add Eden AI as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/671) | closed | yes | no | dev | feat/edenai-provider |
| 674 | [fix: prevent sending messages while AI is streaming response](https://github.com/HKUDS/DeepTutor/pull/674) | closed | yes | no | dev | feature/fix-prevent-send-on-streaming |
| 675 | [fix(json_parser): strip <think> reasoning tags before parsing](https://github.com/HKUDS/DeepTutor/pull/675) | closed | yes | no | dev | fix/json-parser-think-tags |
| 678 | [perf(session): flush buffered turn events in a single transaction](https://github.com/HKUDS/DeepTutor/pull/678) | closed | yes | no | dev | perf/batch-turn-event-flush |
| 679 | [fix(partners): keep empty cells when converting Slack markdown tables](https://github.com/HKUDS/DeepTutor/pull/679) | closed | yes | no | dev | fix/slack-keep-empty-table-cells |
| 680 | [fix(research): parse first JSON value when adjacent values follow](https://github.com/HKUDS/DeepTutor/pull/680) | closed | yes | no | dev | fix/research-json-adjacent-objects |
| 681 | [fix(math-animator): do not treat ms as minutes in duration parsing](https://github.com/HKUDS/DeepTutor/pull/681) | closed | yes | no | dev | fix/duration-ms-not-minute |
| 682 | [fix(partners): do not treat empty markdown rows as table separators](https://github.com/HKUDS/DeepTutor/pull/682) | closed | yes | no | dev | fix/telegram-empty-row-not-separator |
| 683 | [fix(partners): keep leading/trailing empty Feishu table cells](https://github.com/HKUDS/DeepTutor/pull/683) | closed | yes | no | dev | fix/feishu-keep-empty-edge-table-cells |
| 685 | [fix(visualize): return empty on extract_code_block language miss](https://github.com/HKUDS/DeepTutor/pull/685) | open | no | no | dev | fix/extract-code-block-lang-miss |
| 686 | [fix(visualize): accept trailing prose after Chart.js JSON](https://github.com/HKUDS/DeepTutor/pull/686) | open | no | no | dev | fix/validate-chartjs-raw-decode |
| 687 | [fix(vision): parse LLM JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/687) | open | no | no | dev | fix/vision-extract-json-raw-decode |
| 688 | [fix(utils): strip edge whitespace in upload filenames](https://github.com/HKUDS/DeepTutor/pull/688) | open | no | no | dev | fix/validate-upload-strip-whitespace |
| 689 | [fix(partners): require a full-line frontmatter close fence](https://github.com/HKUDS/DeepTutor/pull/689) | open | no | no | dev | fix/strip-frontmatter-close-fence |
| 690 | [feat: 为 DeepTutor 添加独立 Codex OAuth 与动态模型目录](https://github.com/HKUDS/DeepTutor/pull/690) | closed | no | no | main | feat/codex-oauth-provider |
| 693 | [fix: prevent unnecessary re-render by stabilizing provider reference …](https://github.com/HKUDS/DeepTutor/pull/693) | closed | no | no | dev | feature/fix-wipe-info-in-create-kb |
| 699 | [fix(rag): escape $ in GraphRAG file_pattern, fix cache type](https://github.com/HKUDS/DeepTutor/pull/699) | closed | yes | no | dev | fix/695-graphrag-config-invalid-settings |
| 703 | [fix(llm): add opus-5 to the Anthropic effort-based family list](https://github.com/HKUDS/DeepTutor/pull/703) | closed | yes | no | dev | fix/anthropic-opus-5-effort-family |
| 704 | [fix(web): respect manual scrolling in partner chat](https://github.com/HKUDS/DeepTutor/pull/704) | closed | yes | no | dev | fix/partner-autoscroll-696-dev |
| 706 | [fix: persist DONE event ids before a completed turn's execution is popped](https://github.com/HKUDS/DeepTutor/pull/706) | closed | yes | no | dev | fix/698-reconnect-loses-done-message-ids |
| 707 | [fix: book creation timeout and spine single-chapter fallback](https://github.com/HKUDS/DeepTutor/pull/707) | closed | yes | no | dev | fix/book-engine-minimal |
| 710 | [fix(launcher): auto-run npm ci when web/node_modules is missing on source install](https://github.com/HKUDS/DeepTutor/pull/710) | closed | yes | no | dev | fix/launcher-auto-npm-install-on-missing-node-modules |
| 713 | [fix(codex-auth): resolve credentials to admin root for partner scopes](https://github.com/HKUDS/DeepTutor/pull/713) | closed | yes | no | dev | fix/codex-auth-partner-workspace-fallback |
| 715 | [fix: parse_language() collapses non-English codes to Chinese](https://github.com/HKUDS/DeepTutor/pull/715) | closed | no | no | main | fix/parse-language-712 |
| 716 | [fix: guide remote Codex OAuth loopback callbacks](https://github.com/HKUDS/DeepTutor/pull/716) | closed | no | no | dev | fix/codex-remote-oauth-guidance |
| 717 | [fix: update lazy imports to use absolute paths for service modules](https://github.com/HKUDS/DeepTutor/pull/717) | closed | yes | no | dev | fix/static-service-imports |
| 718 | [fix: localize admin user management UI](https://github.com/HKUDS/DeepTutor/pull/718) | closed | yes | no | dev | feature/zh-i18n-improvements |
| 719 | [feat: add immersive reading workspace](https://github.com/HKUDS/DeepTutor/pull/719) | open | no | no | dev | codex/immersive-reading |
| 720 | [fix: preserve chat input focus after sending](https://github.com/HKUDS/DeepTutor/pull/720) | closed | yes | no | dev | fix/preserve-chat-input-focus |
| 721 | [fix(chat): restore scroll position when switching sessions](https://github.com/HKUDS/DeepTutor/pull/721) | closed | no | yes | dev | agent/fix-chat-session-scroll |
| 722 | [ci: attach provenance and SBOM attestations to the released image](https://github.com/HKUDS/DeepTutor/pull/722) | closed | yes | no | dev | ci/image-provenance-sbom |
| 723 | [Feat/merge 1.5.2](https://github.com/HKUDS/DeepTutor/pull/723) | closed | no | no | main | feat/merge-1.5.2 |
| 724 | [Refresh MiniMax endpoints and add MiniMax-M3 context-window metadata](https://github.com/HKUDS/DeepTutor/pull/724) | closed | yes | no | dev | octo/20260729-parameter-refresh-recvq921tXfanC |
| 726 | [feat(settings): expose language switcher](https://github.com/HKUDS/DeepTutor/pull/726) | closed | no | yes | main | codex/settings-language-switcher |
| 728 | [feat(i18n): add complete Spanish (Spain) localization](https://github.com/HKUDS/DeepTutor/pull/728) | open | no | no | dev | feat/spanish-localization |
| 730 | [fix: bootstrap persisted interface language on first load](https://github.com/HKUDS/DeepTutor/pull/730) | closed | yes | no | dev | agent/fix-interface-language-bootstrap |
| 732 | [Fix terminal capability error handling](https://github.com/HKUDS/DeepTutor/pull/732) | closed | yes | no | dev | agent/fix-terminal-capability-error |
| 733 | [fix(auth): use _COOKIE_NAME constant in /status cookie parameter](https://github.com/HKUDS/DeepTutor/pull/733) | closed | yes | no | dev | main |
| 736 | [feat: add per-model reasoning effort setting](https://github.com/HKUDS/DeepTutor/pull/736) | closed | yes | no | dev | agent/add-model-reasoning-effort |
| 738 | [fix: make prompt loading and capability failures terminal](https://github.com/HKUDS/DeepTutor/pull/738) | closed | yes | no | dev | codex/v1.5.7-prompt-and-terminal-fixes |
| 742 | [fix: return minimal reasoning_effort for Gemini 3 and 2.5 Pro](https://github.com/HKUDS/DeepTutor/pull/742) | closed | no | no | dev | fix/gemini-3-reasoning-effort |
| 743 | [fix: make local container Codex OAuth bridge temporary](https://github.com/HKUDS/DeepTutor/pull/743) | closed | yes | no | dev | codex/fix-local-docker-codex-oauth |
| 744 | [feat(embedding): support Gemini Embedding 2 native RAG](https://github.com/HKUDS/DeepTutor/pull/744) | closed | yes | no | dev | codex/fix-gemini-embedding-2-rag |
| 746 | [Add Novita AI as a provider option](https://github.com/HKUDS/DeepTutor/pull/746) | closed | yes | no | dev | feat/novita-provider |
| 747 | [fix(knowledge): harden GraphRAG model and embedding compatibility](https://github.com/HKUDS/DeepTutor/pull/747) | closed | yes | no | dev | fix/graphrag-preflight-error-ui |
| 748 | [fix(visualize): guard against invalid visual_genre crashing generation](https://github.com/HKUDS/DeepTutor/pull/748) | closed | yes | no | dev | fix/visual-genre-fallback |
| 750 | [Codex/mobile responsive](https://github.com/HKUDS/DeepTutor/pull/750) | closed | no | no | main | codex/mobile-responsive |
| 751 | [feat(update): add installation-aware updates for Web and CLI](https://github.com/HKUDS/DeepTutor/pull/751) | open | no | no | dev | feature/web-self-update |
| 753 | [fix(web): resolve optimistic edit refresh race](https://github.com/HKUDS/DeepTutor/pull/753) | closed | yes | no | dev | 260802-fix-edit-message-refresh-race |
| 754 | [fix: surface local LightRAG provenance](https://github.com/HKUDS/DeepTutor/pull/754) | closed | yes | no | dev | codex/lightrag-provenance |
| 756 | [fix(research): mount read-only Obsidian tools instead of rag for vault KBs](https://github.com/HKUDS/DeepTutor/pull/756) | closed | yes | no | dev | 260803-fix-research-obsidian-tools |
| 758 | [feat: separate UI and model response languages](https://github.com/HKUDS/DeepTutor/pull/758) | closed | yes | no | dev | codex/split-ui-response-language |
| 763 | [fix(api): expose GET /api/v1/settings/ui without auth for pre-session language bootstrap](https://github.com/HKUDS/DeepTutor/pull/763) | closed | yes | no | dev | fix/auth-pages-ui-settings-public |
| 764 | [fix: match Claude model ids in vision capability overrides](https://github.com/HKUDS/DeepTutor/pull/764) | closed | yes | no | dev | fix/claude-model-vision-overrides |
| 765 | [feat: mark Kimi K3 as vision capable](https://github.com/HKUDS/DeepTutor/pull/765) | closed | no | no | dev | feat/kimi-k3-vision |
| 770 | [fix: recognize Qwen3.8-Max as vision-capable](https://github.com/HKUDS/DeepTutor/pull/770) | closed | no | no | dev | codex/fix-qwen38-max-vision |
| 771 | [feat: integrate liteparse as a document parsing engine](https://github.com/HKUDS/DeepTutor/pull/771) | closed | yes | no | main | chenhj-dev |
| 772 | [fix: bound conversation compaction budgets](https://github.com/HKUDS/DeepTutor/pull/772) | closed | yes | no | dev | codex/fix-context-compaction-budgets |
| 774 | [fix(codex): preserve OAuth model context window metadata](https://github.com/HKUDS/DeepTutor/pull/774) | closed | yes | no | dev | fix/codex-context-window-metadata |
| 776 | [feat(chat): add AskQuestions mode for contextual clarification](https://github.com/HKUDS/DeepTutor/pull/776) | closed | yes | no | dev | feat/ask-questions-capability |
| 778 | [fix: avoid repeated knowledge-base scans in list endpoint](https://github.com/HKUDS/DeepTutor/pull/778) | closed | yes | no | dev | agent/fix-knowledge-list-performance |
| 780 | [feat(provider): add codebuddy as a LLM provider](https://github.com/HKUDS/DeepTutor/pull/780) | closed | yes | no | dev | feat/codebuddy-provider |
| 783 | [fix: stop Partner responses with Escape](https://github.com/HKUDS/DeepTutor/pull/783) | closed | yes | no | dev | fix/766-partner-escape-stop |
| 784 | [fix: use IPv4 loopback for frontend proxy](https://github.com/HKUDS/DeepTutor/pull/784) | closed | yes | no | dev | codex/fix-deeptutor-ipv4-loopback-20260806t084051z |
| 785 | [[Bug]:Frontend proxy returns 500 on Windows local deployment due to localhost IPv6 resolution](https://github.com/HKUDS/DeepTutor/pull/785) | closed | no | no | main | fix/782-bug-frontend-proxy-returns-500-on-window |
| 786 | [fix(web): repair malformed strong-emphasis spacing in assistant output](https://github.com/HKUDS/DeepTutor/pull/786) | closed | yes | no | dev | fix/web-malformed-strong-emphasis |
| 789 | [feat(codex): persist managed reasoning effort overrides](https://github.com/HKUDS/DeepTutor/pull/789) | closed | yes | no | dev | feat/codex-reasoning-effort-override |
| 791 | [Create ARQUITECTURA.md](https://github.com/HKUDS/DeepTutor/pull/791) | closed | no | no | dev | dev |
| 800 | [fix: resolve generated-output downloads per user](https://github.com/HKUDS/DeepTutor/pull/800) | closed | no | no | dev | fix/790-multi-user-output-download |
| 802 | [fix(web): settle scroll to bottom after loading chat history](https://github.com/HKUDS/DeepTutor/pull/802) | closed | yes | no | dev | fix/chat-history-autoscroll |
| 804 | [fix(visualize): update iframe height when content shrinks](https://github.com/HKUDS/DeepTutor/pull/804) | closed | no | no | dev | codex/fix-issue-801-iframe-height |
| 809 | [fix: return minimal reasoning_effort for Gemini 3 and 2.5 Pro](https://github.com/HKUDS/DeepTutor/pull/809) | closed | yes | no | dev | fix/gemini-3-reasoning-effort |
| 811 | [feat: make Deep Research lifecycle-aware and recoverable](https://github.com/HKUDS/DeepTutor/pull/811) | closed | no | no | main | feature/feynman-learning |
| 812 | [fix(research): handle list-shaped RAG sources](https://github.com/HKUDS/DeepTutor/pull/812) | closed | no | no | dev | agent/fix-rag-list-citations |
| 813 | [fix(mcp): reconnect on credential change; stop reporting transport failures as tool timeouts](https://github.com/HKUDS/DeepTutor/pull/813) | closed | yes | no | main | upstream-pr/mcp-reload-and-error-reporting |
| 818 | [feat: add OrcaRouter as a named OpenAI-compatible gateway provider](https://github.com/HKUDS/DeepTutor/pull/818) | closed | yes | no | dev | orcarouter-integration |
| 820 | [fix(rag): run embed sync hooks on a worker thread when an event loop is already running](https://github.com/HKUDS/DeepTutor/pull/820) | closed | no | no | dev | fix/embedding-nested-event-loop |
| 821 | [fix(llm): mark OpenAI Codex as vision capable](https://github.com/HKUDS/DeepTutor/pull/821) | closed | yes | no | dev | fix/openai-codex-vision |
| 822 | [docs: add Traditional Chinese README](https://github.com/HKUDS/DeepTutor/pull/822) | closed | yes | no | dev | docs/traditional-chinese-readme |
| 823 | [feat(kids): isolate family kids library, harden reading sessions, and supervision](https://github.com/HKUDS/DeepTutor/pull/823) | closed | no | no | main | codex/character-graph-epub |
| 826 | [fix: preserve Responses tool call arguments](https://github.com/HKUDS/DeepTutor/pull/826) | closed | no | no | dev | codex/fix-write-note-tool-arguments |
| 829 | [fix: propagate Responses stream failures](https://github.com/HKUDS/DeepTutor/pull/829) | closed | yes | no | dev | codex/fix-write-note-tool-arguments |
| 830 | [fix(mcp): preserve image content for multimodal tools](https://github.com/HKUDS/DeepTutor/pull/830) | closed | no | no | dev | fix/mcp-image-content |
| 832 | [Guruai/mvp sinhala tutor](https://github.com/HKUDS/DeepTutor/pull/832) | closed | no | no | main | guruai/mvp-sinhala-tutor |
| 834 | [feat(rag): index parser visual structure with language-aware companions](https://github.com/HKUDS/DeepTutor/pull/834) | closed | no | yes | main | feat/mineru-visual-rag-pr1 |
| 836 | [feat(marginnote4): Phase 1 — connected KB type, read-only tools, and sync bridge](https://github.com/HKUDS/DeepTutor/pull/836) | closed | no | no | dev | codex/feat-marginnote4-protocol |
| 837 | [feat(rag): preserve structured parser visuals](https://github.com/HKUDS/DeepTutor/pull/837) | closed | no | yes | dev | feat/structured-visual-ingestion-core |
| 838 | [fix: make Ruff pre-commit hook fail on lint errors](https://github.com/HKUDS/DeepTutor/pull/838) | closed | yes | no | dev | codex/fix-ruff-precommit-soft-fail |
| 842 | [feat: add EPUB support for knowledge base](https://github.com/HKUDS/DeepTutor/pull/842) | closed | no | no | dev | fix/issue-429-epub-kb-support |
| 843 | [feat: add EPUB support for knowledge base](https://github.com/HKUDS/DeepTutor/pull/843) | closed | yes | no | dev | fix/issue-429-epub-kb-support |
| 844 | [fix: Windows MinerU parsing — subprocess UTF-8 decoding & render-thread crash](https://github.com/HKUDS/DeepTutor/pull/844) | closed | yes | no | dev | fix/windows-robustness |
| 845 | [feat: Add remote Docling Serve parsing support](https://github.com/HKUDS/DeepTutor/pull/845) | closed | yes | no | dev | parser |
| 847 | [fix(rag): run document parsing off the event loop (KB indexing stalls all requests)](https://github.com/HKUDS/DeepTutor/pull/847) | closed | yes | no | dev | fix/document-parsing-off-event-loop |
| 848 | [fix(mcp): omit image payloads from tool text](https://github.com/HKUDS/DeepTutor/pull/848) | closed | yes | no | dev | fix/mcp-image-content-redaction |
| 850 | [fix: sync partner tool list with global chat tool toggles](https://github.com/HKUDS/DeepTutor/pull/850) | closed | yes | no | dev | fix/partner-tool-global-toggle-sync |
| 851 | [fix: Keep env-bootstrapped admin usable and unpromoted (#849)](https://github.com/HKUDS/DeepTutor/pull/851) | closed | yes | no | dev | fix/849-env-bootstrap-admin-lockout |
| 852 | [fix: Install mcp by default so pageindex MCP connects](https://github.com/HKUDS/DeepTutor/pull/852) | closed | yes | no | dev | fix/792-mcp-core-dependency |
| 853 | [fix(subagent): resolve .cmd shims on Windows before spawning CLIs](https://github.com/HKUDS/DeepTutor/pull/853) | closed | yes | no | dev | fix/issue-759-windows-cmd-shim |
| 854 | [chore: update codebuddy dependency to version 0.2 in pyproject.toml](https://github.com/HKUDS/DeepTutor/pull/854) | closed | no | no | main | chenhj-dev |
| 856 | [fix: preserve console exception tracebacks](https://github.com/HKUDS/DeepTutor/pull/856) | closed | yes | no | dev | codex/fix-console-traceback |
| 858 | [fix: filter thinking tags from non-SSE local provider streams](https://github.com/HKUDS/DeepTutor/pull/858) | closed | yes | no | dev | codex/filter-non-sse-thinking-tags-20260814 |
| 863 | [fix(runtime): reject invalid runtime homes and placeholder OpenAI keys](https://github.com/HKUDS/DeepTutor/pull/863) | closed | yes | no | dev | codex/upstream-runtime-hardening |
| 864 | [fix(rag): improve local LlamaIndex pipeline compatibility](https://github.com/HKUDS/DeepTutor/pull/864) | closed | yes | no | dev | codex/upstream-rag-compat |
| 865 | [chore(web): stop tracking Next build output and enforce repo hygiene](https://github.com/HKUDS/DeepTutor/pull/865) | closed | yes | no | dev | codex/upstream-repo-hygiene |
| 869 | [fix(sessions): ensure cleanup of mastery path on session deletion](https://github.com/HKUDS/DeepTutor/pull/869) | closed | yes | no | dev | main |
| 870 | [fix: cache and dedupe docstore probes in kb list / knowledge API (#859)](https://github.com/HKUDS/DeepTutor/pull/870) | closed | yes | no | dev | fix/kb-list-docstore-cache |
| 871 | [feat: rename product to Lumen and add settings modal](https://github.com/HKUDS/DeepTutor/pull/871) | closed | no | yes | main | main |
| 872 | [fix: harden post-merge cleanup and image loading](https://github.com/HKUDS/DeepTutor/pull/872) | closed | yes | no | dev | codex/post-pr-integration-hardening |
| 873 | [修复 IMA 只读连接与原文检索](https://github.com/HKUDS/DeepTutor/pull/873) | closed | yes | no | dev | fix/ima-connection-flow |
| 874 | [测试：兼容 Codex 推理设置的多行调用](https://github.com/HKUDS/DeepTutor/pull/874) | closed | no | yes | dev | fix/codex-reasoning-contract-test |
| 875 | [feat: Add remote Tika parsing support](https://github.com/HKUDS/DeepTutor/pull/875) | closed | yes | no | dev | tika |
| 876 | [fix(security): redact model catalog secrets](https://github.com/HKUDS/DeepTutor/pull/876) | closed | yes | no | dev | codex/fix-857-settings-secret-redaction |
| 877 | [feat: expose LightRAG concurrency and extraction knobs in settings](https://github.com/HKUDS/DeepTutor/pull/877) | closed | yes | no | dev | feature/lightrag-configurable-params |
| 878 | [test: restore lint and source contract baseline](https://github.com/HKUDS/DeepTutor/pull/878) | closed | yes | no | dev | codex/fix-ci-baseline-contracts |
| 879 | [fix: isolate Partner sessions and memory per user](https://github.com/HKUDS/DeepTutor/pull/879) | closed | yes | no | dev | codex/fix-621-partner-data-isolation |
| 880 | [Fix missing assistant responses in Course Chat](https://github.com/HKUDS/DeepTutor/pull/880) | closed | no | yes | main | agent/fix-chat-response-hydration |
| 881 | [fix: isolate invalid Partner channel configs](https://github.com/HKUDS/DeepTutor/pull/881) | closed | yes | no | dev | codex/fix-827-channel-startup-isolation |
| 882 | [fix: use Responses API for OpenAI GPT-5 agentic tools](https://github.com/HKUDS/DeepTutor/pull/882) | closed | yes | no | dev | codex/fix-708-openai-agentic-responses |
| 883 | [fix: schedule qualitative mastery reviews](https://github.com/HKUDS/DeepTutor/pull/883) | closed | yes | no | dev | codex/fix-840-qualitative-review-scheduling |
| 884 | [fix: keep mastery teaching content visible](https://github.com/HKUDS/DeepTutor/pull/884) | closed | yes | no | dev | codex/fix-855-mastery-markdown |
| 885 | [fix: stream large knowledge uploads through web](https://github.com/HKUDS/DeepTutor/pull/885) | closed | yes | no | dev | codex/fix-868-large-multipart |
| 886 | [fix(partners): restore focus and reconnect after tab inactivity](https://github.com/HKUDS/DeepTutor/pull/886) | closed | yes | no | dev | codex/fix-partner-resilience |
| 887 | [fix(sandbox): expose active virtualenv safely in bubblewrap](https://github.com/HKUDS/DeepTutor/pull/887) | closed | yes | no | dev | codex/fix-bwrap-venv |
| 888 | [fix: recover model catalog and provider transport](https://github.com/HKUDS/DeepTutor/pull/888) | closed | yes | no | dev | codex/fix-model-transport-resilience |
| 889 | [fix(book): keep chapter map titles visible](https://github.com/HKUDS/DeepTutor/pull/889) | closed | yes | no | dev | codex/fix-concept-title-visibility |
| 890 | [fix(chat): preserve provider stream failure boundaries](https://github.com/HKUDS/DeepTutor/pull/890) | closed | yes | no | dev | codex/harden-stream-failure-boundaries |
| 892 | [Codex/bilingual mn4 closure](https://github.com/HKUDS/DeepTutor/pull/892) | closed | no | no | main | codex/bilingual-mn4-closure |
| 894 | [chore: repository governance hooks, CI hygiene, and branch policies](https://github.com/HKUDS/DeepTutor/pull/894) | closed | no | yes | main | codex/pr-repo-governance |
| 895 | [feat(immersive-reading): source-faithful EPUB reading core and web workspace](https://github.com/HKUDS/DeepTutor/pull/895) | closed | no | yes | main | codex/pr-immersive-core |
| 896 | [feat(reading): web audio TTS pronunciation and mobile reading UX](https://github.com/HKUDS/DeepTutor/pull/896) | closed | no | yes | main | codex/pr-pronunciation-mobile |
| 897 | [feat: PWA manifest, MarginNote 4 writeback, and sync manager refinements](https://github.com/HKUDS/DeepTutor/pull/897) | closed | no | yes | main | codex/pr-pwa-mn4-sync |
| 898 | [feat(reading): bilingual pairing, vocabulary loop, translation board, and source sync](https://github.com/HKUDS/DeepTutor/pull/898) | closed | no | yes | main | codex/pr-bilingual-vocab |
| 899 | [fix(knowledge): preserve source-relative directory structure when syncing external linked folders into raw/](https://github.com/HKUDS/DeepTutor/pull/899) | closed | yes | no | dev | fix/866-linked-folder-flatten |
| 901 | [Codex/refactor immersive architecture](https://github.com/HKUDS/DeepTutor/pull/901) | closed | no | no | main | codex/refactor-immersive-architecture |
| 903 | [feat: split knowledge sync - add GitHub source sync](https://github.com/HKUDS/DeepTutor/pull/903) | closed | yes | no | dev | codex/split-github-source-sync |
| 904 | [feat: add bounded web source sync](https://github.com/HKUDS/DeepTutor/pull/904) | closed | yes | no | dev | codex/split-web-source-sync |
| 905 | [feat(immersive-reading): add source-faithful reading core](https://github.com/HKUDS/DeepTutor/pull/905) | closed | no | yes | dev | codex/split-immersive-reading-core |
| 907 | [feat(pageindex): add OSS knowledge bases and reasoning-based retrieval](https://github.com/HKUDS/DeepTutor/pull/907) | closed | yes | no | dev | feat/pageindex-sdk-oss |
| 908 | [feat: add neutral deeptutor.plugins entry-point loader](https://github.com/HKUDS/DeepTutor/pull/908) | closed | yes | no | dev | feat/plugin-loader-entry-points |
| 910 | [fix(chat): inject current date into runtime context](https://github.com/HKUDS/DeepTutor/pull/910) | closed | yes | no | dev | fix/inject-currentdate-into-runtime-context |
| 911 | [feat: discover loop capabilities via entry points](https://github.com/HKUDS/DeepTutor/pull/911) | closed | yes | no | dev | feat/loop-capabilities-entry-points |
| 913 | [Feature/self hosted runner deploy](https://github.com/HKUDS/DeepTutor/pull/913) | closed | no | no | main | feature/self-hosted-runner-deploy |
| 917 | [feat(reading): polish bilingual mobile reading experience](https://github.com/HKUDS/DeepTutor/pull/917) | closed | no | yes | dev | codex/bilingual-mobile-reading-ux |
| 919 | [fix(usage): record token usage emitted as plain dicts by native adapters](https://github.com/HKUDS/DeepTutor/pull/919) | closed | yes | no | dev | fix/usage-dict-token-accounting |
| 920 | [fix(llm): recover from stale CA bundle paths](https://github.com/HKUDS/DeepTutor/pull/920) | closed | yes | no | dev | fix/recover-stale-ca-bundle-paths |
| 921 | [feat: /whisper dual-seat page and capability-complete forwarding](https://github.com/HKUDS/DeepTutor/pull/921) | closed | yes | no | dev | feat/whisper-dual-seat-web |
| 922 | [fix(obsidian): tolerate undecodable bytes and date frontmatter (#914, #915)](https://github.com/HKUDS/DeepTutor/pull/922) | closed | yes | no | dev | fix/obsidian-robustness |
| 923 | [fix: re-parent descendants on turn delete and render orphaned message trees](https://github.com/HKUDS/DeepTutor/pull/923) | closed | yes | no | dev | fix/issue-912-delete-turn-blank-page |
| 924 | [feat: honor end_loop metadata after ask_user resume](https://github.com/HKUDS/DeepTutor/pull/924) | closed | yes | no | dev | feat/end-loop-after-ask-user-resume |
| 925 | [feat: psych academy workspace pages (web-only, excludes whisper)](https://github.com/HKUDS/DeepTutor/pull/925) | open | no | no | dev | feat/psych-academy-web |
| 926 | [feat(book): add learning capture inbox](https://github.com/HKUDS/DeepTutor/pull/926) | closed | yes | no | dev | codex/book-learning-capture |
| 927 | [fix(book): gate KB fingerprint refresh on stale recompilation](https://github.com/HKUDS/DeepTutor/pull/927) | closed | yes | no | dev | codex/kb-drift-refresh-gate |
| 928 | [fix(api): return JSON for unhandled exceptions](https://github.com/HKUDS/DeepTutor/pull/928) | closed | yes | no | dev | codex/api-json-error-hardening |
| 930 | [fix: log provider error body on tool-schema rejection fallback](https://github.com/HKUDS/DeepTutor/pull/930) | closed | yes | no | dev | fix/log-tool-schema-rejection-body |
| 931 | [feat(knowledge): add MarginNote 4 as a connected knowledge base](https://github.com/HKUDS/DeepTutor/pull/931) | closed | yes | no | dev | codex/upstream-marginnote4 |
| 933 | [fix(rag): parallelize image descriptions in the LlamaIndex RAG pipeline with timeout and progress](https://github.com/HKUDS/DeepTutor/pull/933) | closed | yes | no | dev | fix/rag-image-description-concurrency |
| 936 | [fix(chat): prune deleted knowledge base references from sessions](https://github.com/HKUDS/DeepTutor/pull/936) | closed | yes | no | dev | fix/prune-stale-kb-references |
| 940 | [fix: converge LightRAG transport failures and cancellation](https://github.com/HKUDS/DeepTutor/pull/940) | closed | yes | no | dev | codex/nox-20-bounded-lightrag-retry |
| 944 | [fix(book): repair the reader flex height chain so long chapters scroll](https://github.com/HKUDS/DeepTutor/pull/944) | closed | no | no | dev | fix/book-reader-scroll-height-chain |
| 947 | [Feat/encore user sidebar](https://github.com/HKUDS/DeepTutor/pull/947) | closed | no | no | main | feat/encore-user-sidebar |
| 948 | [fix(voice): strip MediaRecorder codec params from STT uploads](https://github.com/HKUDS/DeepTutor/pull/948) | closed | yes | no | dev | fix/stt-webm-codec-mime |
| 949 | [fix(rag): filter MinerU page-layout blocks before indexing](https://github.com/HKUDS/DeepTutor/pull/949) | closed | yes | no | dev | codex/mineru-layout-block-filter |
| 950 | [feat: add QR channel onboarding for Feishu/Lark and WeCom](https://github.com/HKUDS/DeepTutor/pull/950) | closed | no | no | main | codex/partner-qr-onboarding |
| 952 | [feat: add QR onboarding for Feishu and WeCom partners](https://github.com/HKUDS/DeepTutor/pull/952) | closed | yes | no | dev | codex/partner-qr-onboarding |
| 953 | [fix(llamaindex): fail bounded when indexing stalls](https://github.com/HKUDS/DeepTutor/pull/953) | closed | yes | no | dev | fix/llamaindex-index-stall |
| 954 | [fix(cli): declare missing standalone runtime dependencies](https://github.com/HKUDS/DeepTutor/pull/954) | closed | yes | no | dev | fix/cli-runtime-dependencies |
| 956 | [fix(mastery): reject duplicate quiz option bodies](https://github.com/HKUDS/DeepTutor/pull/956) | closed | yes | no | dev | fix/955-duplicate-quiz-options |
| 958 | [feat: add per-conversation reasoning-effort override (#641)](https://github.com/HKUDS/DeepTutor/pull/958) | closed | yes | no | dev | feature/conversation-reasoning-effort |
| 959 | [feat(cli): add setup doctor command](https://github.com/HKUDS/DeepTutor/pull/959) | closed | yes | no | dev | fix/833-doctor-command |
| 960 | [fix(web): pin chat to late-mounted quiz cards](https://github.com/HKUDS/DeepTutor/pull/960) | closed | yes | no | dev | fix/quiz-card-autoscroll |
| 962 | [fix(embedding): survive provider rate limits — key rotation, retry budget, global throttle](https://github.com/HKUDS/DeepTutor/pull/962) | closed | yes | no | dev | upstream-pr/embedding-429-resilience |
| 964 | [fix(sandbox): support Windows code execution](https://github.com/HKUDS/DeepTutor/pull/964) | closed | yes | no | dev | fix/windows-code-execution |
| 968 | [feat(reading): add source-faithful EPUB contract](https://github.com/HKUDS/DeepTutor/pull/968) | closed | yes | no | dev | codex/epub-reading-contract |
| 969 | [feat(reading): render EPUBs faithfully in ReaderPane](https://github.com/HKUDS/DeepTutor/pull/969) | closed | yes | no | dev | codex/epub-faithful-viewer |
| 970 | [feat(reading): add safe extension protocol and empty toolbar slot](https://github.com/HKUDS/DeepTutor/pull/970) | closed | yes | no | dev | codex/upstream-reading-extensions |
| 972 | [feat(reading): persist W3C text selectors](https://github.com/HKUDS/DeepTutor/pull/972) | closed | yes | no | dev | codex/upstream-reading-selectors |
| 974 | [feat(reading): render reflowing annotations with Recogito](https://github.com/HKUDS/DeepTutor/pull/974) | closed | yes | no | dev | codex/upstream-reading-recogito |
| 975 | [fix(chat): decode dense non-ASCII unicode escapes for display](https://github.com/HKUDS/DeepTutor/pull/975) | closed | yes | no | dev | codex/fix-mastery-unicode-display |
| 976 | [fix(whisper): show plugin-required empty state](https://github.com/HKUDS/DeepTutor/pull/976) | closed | no | no | dev | codex/fix-whisper-plugin-empty-state |
| 977 | [fix(llm): drop temperature for bare Kimi model ids (k3) on the coding endpoint](https://github.com/HKUDS/DeepTutor/pull/977) | closed | yes | no | dev | fix/kimi-k3-temperature |
| 978 | [feat(llm): route OpenAI-compatible agent calls through the Responses API](https://github.com/HKUDS/DeepTutor/pull/978) | closed | no | no | dev | feat/responses-api-bridge |
| 979 | [feat(reading): add explicit bilingual EPUB pairing](https://github.com/HKUDS/DeepTutor/pull/979) | closed | yes | no | dev | codex/epub-bilingual-pairing |
| 981 | [ci: ignore non-version release tags](https://github.com/HKUDS/DeepTutor/pull/981) | closed | yes | no | dev | codex/release-tag-guards |
| 983 | [test(partners): assert the admin gate without a FastAPI internal](https://github.com/HKUDS/DeepTutor/pull/983) | closed | yes | no | dev | fix/partners-admin-gate-test |
| 985 | [feat(reading): add adjustable text display preferences](https://github.com/HKUDS/DeepTutor/pull/985) | closed | yes | no | dev | codex/upstream-reader-display |
| 986 | [fix: improve Windows cross-platform compatibility across runner, tool…](https://github.com/HKUDS/DeepTutor/pull/986) | closed | yes | no | dev | fix/windows-compatibility |
| 988 | [fix(codex): fail closed on TLS verification errors](https://github.com/HKUDS/DeepTutor/pull/988) | closed | yes | no | dev | fix/codex-tls-fail-closed |
| 989 | [fix(rag): preserve asymmetric embedding context](https://github.com/HKUDS/DeepTutor/pull/989) | closed | yes | no | dev | fix/lightrag-asymmetric-context |
| 990 | [feat(subagent): add Antigravity CLI (agy) backend](https://github.com/HKUDS/DeepTutor/pull/990) | closed | no | no | dev | feat/antigravity-cli |
| 991 | [feat(reading): add persistent document outline and in-page heading navigation](https://github.com/HKUDS/DeepTutor/pull/991) | closed | yes | no | dev | codex/upstream-reader-outline |
| 996 | [feat: add selection tutor and course workspaces](https://github.com/HKUDS/DeepTutor/pull/996) | closed | yes | no | dev | codex/selection-tutor-learning-spaces |
| 998 | [fix(book): read long chapters sequentially before turning pages](https://github.com/HKUDS/DeepTutor/pull/998) | closed | yes | no | dev | codex/book-reader-sequential-navigation |
| 999 | [fix(tests): ensure non-admin role for alice fixture in channel links …](https://github.com/HKUDS/DeepTutor/pull/999) | closed | no | no | dev | fix/test-channel-links-alice-fixture |
| 1000 | [Chore/line endings and ci](https://github.com/HKUDS/DeepTutor/pull/1000) | closed | no | no | main | chore/line-endings-and-ci |
| 1001 | [Chore/line endings and ci](https://github.com/HKUDS/DeepTutor/pull/1001) | closed | no | no | main | chore/line-endings-and-ci |
| 1002 | [fix(assessment): redirect plain-text mastery quizzes to cards (#941)](https://github.com/HKUDS/DeepTutor/pull/1002) | closed | yes | no | dev | codex/fix-mastery-plain-text-quiz |
| 1003 | [feat(llm): map web_search to native Responses tools for server-side search](https://github.com/HKUDS/DeepTutor/pull/1003) | closed | yes | no | dev | feat/native-web-search-responses |
| 1005 | [Fix llama.cpp context detection for loaded models](https://github.com/HKUDS/DeepTutor/pull/1005) | closed | yes | no | dev | props |
| 1006 | [feat(search): add Serply provider with web, news and scholar modes](https://github.com/HKUDS/DeepTutor/pull/1006) | closed | yes | no | dev | feat/serply-search |
| 1007 | [fix(mastery): don't freeze choice gates on clarifying composer text](https://github.com/HKUDS/DeepTutor/pull/1007) | closed | yes | no | dev | fix/mastery-composer-clarifying |
| 1008 | [fix(llm): stop matching bare 'tool' in schema-fallback detector](https://github.com/HKUDS/DeepTutor/pull/1008) | closed | yes | no | dev | fix/tool-schema-fallback-matcher |
| 1009 | [feat(reading): expose EPUB headings in the persistent outline](https://github.com/HKUDS/DeepTutor/pull/1009) | closed | yes | no | dev | codex/upstream-epub-outline-headings |
| 1011 | [feat(reading): render web snapshots as safe rich Markdown](https://github.com/HKUDS/DeepTutor/pull/1011) | closed | no | no | dev | codex/upstream-rich-web-snapshot |
| 1015 | [feat: add Volcengine Ark embedding, Doubao Search Custom and PaddleOCR parsing providers](https://github.com/HKUDS/DeepTutor/pull/1015) | open | no | no | dev | feat/volcengine-doubao-paddle-providers |
| 1017 | [fix(partners): serve partner artifacts from output downloads](https://github.com/HKUDS/DeepTutor/pull/1017) | closed | yes | no | dev | fix/partner-output-fallback |
| 1020 | [fix(chat): decode unicode escapes in ask_user card text](https://github.com/HKUDS/DeepTutor/pull/1020) | closed | yes | no | dev | fix/ask-user-unicode-escape |
| 1021 | [fix: make deep research resilient to interrupted streams](https://github.com/HKUDS/DeepTutor/pull/1021) | closed | yes | no | dev | codex/deep-research-resilience |
| 1022 | [fix(mastery): normalize objective module variants](https://github.com/HKUDS/DeepTutor/pull/1022) | closed | no | no | dev | codex/fix/mastery-lenient-modules |
| 1023 | [fix(mastery): add explicit question recovery exit (#1018)](https://github.com/HKUDS/DeepTutor/pull/1023) | closed | yes | no | dev | codex/fix/mastery-skip-tool |
| 1024 | [feat(settings): expose custom reasoning effort (#1010)](https://github.com/HKUDS/DeepTutor/pull/1024) | closed | yes | no | dev | codex/feat/reasoning-effort-custom |
| 1025 | [fix(tools): route file generation through code execution (#965)](https://github.com/HKUDS/DeepTutor/pull/1025) | closed | yes | no | dev | codex/fix/code-execution-file-artifacts |
| 1026 | [fix(partners): coalesce streaming draft updates (#788)](https://github.com/HKUDS/DeepTutor/pull/1026) | closed | yes | no | dev | codex/fix-partner-chat-update-loop |
| 1027 | [fix(web): resolve optimistic ids before deleteTurn](https://github.com/HKUDS/DeepTutor/pull/1027) | closed | yes | no | dev | fix/delete-turn-optimistic-id |
| 1029 | [feat(reading): enforce Focus-Check checkpoint progression](https://github.com/HKUDS/DeepTutor/pull/1029) | open | no | no | dev | codex/reading-focus-check |
| 1030 | [feat(reading): add semantic passage search](https://github.com/HKUDS/DeepTutor/pull/1030) | open | no | no | dev | codex/reading-description-search |
| 1031 | [feat(reading): add citation capture](https://github.com/HKUDS/DeepTutor/pull/1031) | closed | yes | no | dev | codex/reading-citation-capture |
| 1032 | [feat(reading): reference reading sections in chat](https://github.com/HKUDS/DeepTutor/pull/1032) | closed | yes | no | dev | codex/reading-chat-references |
| 1033 | [fix: align Windows exec runtime and search readiness](https://github.com/HKUDS/DeepTutor/pull/1033) | closed | yes | no | dev | codex/windows-exec-search-readiness |
| 1036 | [fix(reading): bind citations to turn materials and verified locators (#1034)](https://github.com/HKUDS/DeepTutor/pull/1036) | closed | yes | no | dev | codex/fix/reading-citation-material-binding |
| 1037 | [feat(video-learning): add native YouTube immersive watching (#997)](https://github.com/HKUDS/DeepTutor/pull/1037) | closed | yes | no | dev | codex/feat/video-learning-youtube |
| 1038 | [feat(reading): add session-scoped cross-material navigation history (#1035)](https://github.com/HKUDS/DeepTutor/pull/1038) | closed | yes | no | dev | codex/feat/reading-location-history |
| 1041 | [fix(llm): route Anthropic `temperature` via `extra_body` for SDK 1.x compat](https://github.com/HKUDS/DeepTutor/pull/1041) | closed | yes | no | main | fix/anthropic-sdk-1x-temperature-extra-body |
| 1042 | [fix(partners): coalesce streaming draft updates (#788)](https://github.com/HKUDS/DeepTutor/pull/1042) | closed | no | no | main | codex/fix-partner-chat-update-loop |
| 1043 | [fix(skills): scope ClawHub installs by publisher (#639)](https://github.com/HKUDS/DeepTutor/pull/1043) | closed | yes | no | dev | codex/fix/clawhub-publisher-refs |
| 1044 | [feat(rag): add opt-in HNSW vector indexes (#304)](https://github.com/HKUDS/DeepTutor/pull/1044) | closed | yes | no | dev | codex/feat/rag-hnsw-index |
| 1045 | [feat(rag): add optional cross-encoder reranking (#304)](https://github.com/HKUDS/DeepTutor/pull/1045) | closed | yes | no | dev | codex/feat/rag-cross-encoder-rerank |
| 1046 | [feat(media): add DashScope providers (#1016)](https://github.com/HKUDS/DeepTutor/pull/1046) | closed | yes | no | dev | codex/feat/dashscope-media-providers |
| 1047 | [docs(web): update overview screenshot (#1039)](https://github.com/HKUDS/DeepTutor/pull/1047) | closed | no | no | dev | codex/docs/v1-6-overview-screenshot |
| 1048 | [fix(llm): replay DeepSeek reasoning across tool calls](https://github.com/HKUDS/DeepTutor/pull/1048) | closed | no | no | dev | fix/deepseek-reasoning-replay |
| 1049 | [fix(web): skip persisting optimistic branch selections](https://github.com/HKUDS/DeepTutor/pull/1049) | closed | yes | no | dev | fix/switch-branch-optimistic-id |
| 1050 | [fix(tools): decode unicode escapes in ask_user payloads](https://github.com/HKUDS/DeepTutor/pull/1050) | closed | yes | no | dev | fix/ask-user-unicode-decode-backend |
| 1051 | [feat(chat): add per-conversation reasoning effort (#641)](https://github.com/HKUDS/DeepTutor/pull/1051) | closed | no | no | dev | codex/feat/conversation-reasoning-effort-upstream |
| 1052 | [feat(book): infer requested language (#471)](https://github.com/HKUDS/DeepTutor/pull/1052) | closed | yes | no | dev | codex/fix/book-language-options |
| 1053 | [feat(settings): add version update checks (#725)](https://github.com/HKUDS/DeepTutor/pull/1053) | closed | no | no | dev | codex/feat/settings-version-check |
| 1054 | [docs(safety): add reasoning and retrieval checklist (#199)](https://github.com/HKUDS/DeepTutor/pull/1054) | closed | yes | no | dev | codex/docs/reasoning-safety-checklist |
| 1055 | [test(web-source): cover relative images in crawled docs (#980)](https://github.com/HKUDS/DeepTutor/pull/1055) | closed | no | no | dev | codex/fix-web-source-relative-images |
| 1057 | [fix(question): validate topic before generation](https://github.com/HKUDS/DeepTutor/pull/1057) | closed | yes | no | dev | codex/deep-question-validation |
| 1059 | [fix(llm): disable DeepSeek flash thinking on openai bindings](https://github.com/HKUDS/DeepTutor/pull/1059) | closed | yes | no | dev | fix/openai-binding-deepseek-thinking |
| 1060 | [feat(search): add reference safety filtering (#375)](https://github.com/HKUDS/DeepTutor/pull/1060) | closed | yes | no | dev | codex/fix/search-reference-safety |
| 1061 | [feat(reading): add chapter relationship graph (#932)](https://github.com/HKUDS/DeepTutor/pull/1061) | closed | no | no | dev | codex/reading-character-graph |
| 1062 | [feat(chat): add inline markdown notes (#661)](https://github.com/HKUDS/DeepTutor/pull/1062) | closed | yes | no | dev | codex/feat/chat-markdown-note |
| 1064 | [docs(installation): document uninstall and data cleanup (#486)](https://github.com/HKUDS/DeepTutor/pull/1064) | closed | yes | no | dev | codex/docs/uninstall-cleanup |
| 1065 | [docs(knowledge): add note migration guide (#841)](https://github.com/HKUDS/DeepTutor/pull/1065) | closed | yes | no | dev | codex/docs/knowledge-migration |
| 1066 | [fix(embedding): enable Jina retrieval roles (#1063)](https://github.com/HKUDS/DeepTutor/pull/1066) | closed | yes | no | dev | codex/fix/jina-retrieval-roles |
| 1067 | [fix(llm): persist DeepSeek reasoning across turns (#1058)](https://github.com/HKUDS/DeepTutor/pull/1067) | closed | yes | no | dev | codex/fix/deepseek-persisted-reasoning |
| 1068 | [feat(chat): route explicit quiz requests (#807)](https://github.com/HKUDS/DeepTutor/pull/1068) | closed | yes | no | dev | codex/chat-quiz-routing |
| 1069 | [Replace RAG-Anything with native LightRAG 1.5 pipeline](https://github.com/HKUDS/DeepTutor/pull/1069) | closed | yes | no | dev | codex/nox-3-lightrag-native |
| 1070 | [feat(lightrag): add dedicated model selection (#640)](https://github.com/HKUDS/DeepTutor/pull/1070) | closed | yes | no | dev | codex/lightrag-model-overrides |
| 1071 | [fix(chat): select newly sent branch (#739)](https://github.com/HKUDS/DeepTutor/pull/1071) | closed | yes | no | dev | codex/fix/chat-edit-branch-selection |
| 1072 | [fix(llm): support Anthropic SDK temperature fields (#1040)](https://github.com/HKUDS/DeepTutor/pull/1072) | closed | no | no | dev | codex/fix/anthropic-sdk-temperature |
| 1073 | [fix(knowledge): explain scanned PDF parse failures (#431)](https://github.com/HKUDS/DeepTutor/pull/1073) | closed | yes | no | dev | codex/knowledge-empty-pdf-guidance |
| 1074 | [feat(knowledge): add WeKnora retrieval connections (#918)](https://github.com/HKUDS/DeepTutor/pull/1074) | closed | yes | no | dev | codex/feat/weknora-server |
| 1075 | [fix(llm): enable DeepSeek Pro native web search (#846)](https://github.com/HKUDS/DeepTutor/pull/1075) | closed | yes | no | dev | codex/fix/deepseek-responses-web-search |
| 1077 | [fix(runtime): fall back when psutil cannot read /proc](https://github.com/HKUDS/DeepTutor/pull/1077) | closed | yes | no | dev | fix/memory-probe-permission-error |
| 1078 | [fix(runtime): skip psutil process-tree walk on HarmonyOS (/proc/1/stat)](https://github.com/HKUDS/DeepTutor/pull/1078) | closed | no | no | main | fix/memory-probe-proc-permission |
| 1079 | [fix(mastery): read the module tree models actually emit (#1019)](https://github.com/HKUDS/DeepTutor/pull/1079) | closed | yes | no | dev | fix/mastery-build-schema |
| 1080 | [fix(ci): restore the ruff gate on dev](https://github.com/HKUDS/DeepTutor/pull/1080) | closed | yes | no | dev | fix/lint-pending-imports |
| 1081 | [feat(assessment): unify persisted review records (#824)](https://github.com/HKUDS/DeepTutor/pull/1081) | closed | yes | no | dev | codex/feat/assessment-review |
| 1082 | [chore(lint): restore dev formatting](https://github.com/HKUDS/DeepTutor/pull/1082) | closed | no | no | dev | codex/fix/ruff-pending-import |
| 1083 | [fix(ima): add ima.qq.com to the media-URL allowlist](https://github.com/HKUDS/DeepTutor/pull/1083) | closed | no | no | main | main |
| 1084 | [feat(llm): support explicit OpenAI wire API selection](https://github.com/HKUDS/DeepTutor/pull/1084) | closed | yes | no | dev | codex/deploy-v1.6.0-wire-api |
| 1085 | [fix(code-execution): preserve PDF scope and retry discipline (#965)](https://github.com/HKUDS/DeepTutor/pull/1085) | closed | no | no | dev | codex/fix/code-execution-pdf-reliability-dev |
| 1086 | [fix(web): localize organized session placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1086) | closed | yes | no | dev | fix/organized-session-placeholder-title |
| 1090 | [fix(web): remap KaTeX selections to LaTeX for Little Tutor](https://github.com/HKUDS/DeepTutor/pull/1090) | closed | no | no | dev | fix/selection-tutor-katex-latex |
| 1093 | [fix: avoid blocking the embedding event loop](https://github.com/HKUDS/DeepTutor/pull/1093) | closed | yes | no | dev | fix/lightrag-embedding-event-loop-deadlock |
| 1094 | [fix: persist reindex terminal state](https://github.com/HKUDS/DeepTutor/pull/1094) | closed | yes | no | dev | fix/lightrag-reindex-terminal-state |
| 1095 | [fix(web): localize HistorySessionPicker placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1095) | closed | yes | no | dev | fix/history-picker-placeholder-title |
| 1097 | [fix(launcher): detect IPv6 loopback port listeners (#1096)](https://github.com/HKUDS/DeepTutor/pull/1097) | closed | yes | no | dev | codex/fix/dual-stack-port-probe |
| 1098 | [feat(parsing): route Office and image files through MinerU (#1087)](https://github.com/HKUDS/DeepTutor/pull/1098) | closed | yes | no | dev | fix/mineru-non-pdf-formats |
| 1100 | [fix(courses): preserve handoff course scope (#1099)](https://github.com/HKUDS/DeepTutor/pull/1100) | closed | yes | no | dev | codex/fix/course-handoff-course-scope |
| 1102 | [fix(agentic): distinguish empty vs missing tool args (#1101)](https://github.com/HKUDS/DeepTutor/pull/1102) | closed | yes | no | dev | fix/arg-guard-empty-string-feedback |
| 1104 | [feat(reading): add safe read-aloud extension (#1103)](https://github.com/HKUDS/DeepTutor/pull/1104) | closed | yes | no | dev | codex/feat-reading-read-aloud-extension |
| 1106 | [feat(reading): add source-grounded study guidance extension (#1105)](https://github.com/HKUDS/DeepTutor/pull/1106) | closed | yes | no | main | codex/feat-reading-study-guidance |
| 1108 | [feat(reading): add source-grounded vocabulary extension (#1107)](https://github.com/HKUDS/DeepTutor/pull/1108) | closed | yes | no | main | codex/feat-reading-vocabulary |
| 1110 | [feat(learner): add account-scoped reading learning records (#1109)](https://github.com/HKUDS/DeepTutor/pull/1110) | closed | no | no | dev | codex/feat/learner-reading-records |
| 1112 | [feat(learner): add server-enforced account presets (#1111)](https://github.com/HKUDS/DeepTutor/pull/1112) | closed | no | no | main | codex/feat-learner-account-presets |
| 1113 | [feat(learner): add guardian authorization (#994)](https://github.com/HKUDS/DeepTutor/pull/1113) | closed | yes | no | main | codex/feat-learner-guardian-auth |
| 1115 | [feat(reading): add source-grounded quiz extension (#1114)](https://github.com/HKUDS/DeepTutor/pull/1115) | closed | yes | no | main | codex/feat-reading-quiz-extension |
| 1118 | [fix(ima): add ima.qq.com to the media-URL allowlist](https://github.com/HKUDS/DeepTutor/pull/1118) | closed | yes | no | dev | fix/ima-media-url-allowlist |
| 1119 | [feat(reading): add source-grounded translation extension](https://github.com/HKUDS/DeepTutor/pull/1119) | closed | yes | no | main | codex/feat-reading-translation |
| 1120 | [Add Word (.docx) import and export to Co-Writer](https://github.com/HKUDS/DeepTutor/pull/1120) | closed | yes | no | dev | docx |
| 1121 | [fix(partners): localize partner session placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1121) | closed | yes | no | dev | fix/partner-session-placeholder-title |
| 1122 | [feat(learner): add revocable device login credentials (#1116)](https://github.com/HKUDS/DeepTutor/pull/1122) | closed | no | no | main | codex/feat-learner-device-credentials |
| 1123 | [feat(reading): add session-scoped cross-material navigation history (#1035)](https://github.com/HKUDS/DeepTutor/pull/1123) | closed | yes | no | main | codex/feat/reading-location-history |
| 1124 | [feat(learner): add account-scoped learner profiles (#891)](https://github.com/HKUDS/DeepTutor/pull/1124) | closed | no | no | dev | codex/feat-learner-profile |
| 1126 | [feat(learner): add self-service learner profiles](https://github.com/HKUDS/DeepTutor/pull/1126) | closed | yes | no | main | codex/feat-learner-self-profile-v2 |
| 1129 | [feat(learner): add guardian management UI](https://github.com/HKUDS/DeepTutor/pull/1129) | closed | yes | no | main | codex/feat-learner-guardian-ui |
| 1134 | [fix(video-learning): retry unavailable Invidious captions (#1133)](https://github.com/HKUDS/DeepTutor/pull/1134) | closed | yes | no | dev | codex/fix/invidious-caption-refresh |
| 1135 | [test(video-learning): support lazy included routers (#1131)](https://github.com/HKUDS/DeepTutor/pull/1135) | closed | no | no | main | codex/fix-video-learning-mount |
| 1136 | [chore(ci): format Python baseline for Ruff 0.16 (#1132)](https://github.com/HKUDS/DeepTutor/pull/1136) | closed | no | no | main | codex/chore-ruff-format-baseline |
| 1139 | [fix(web): localize MyAgentsPicker placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1139) | closed | yes | no | dev | fix/my-agents-picker-placeholder-title |
| 1141 | [fix: provide contexts for mastery study](https://github.com/HKUDS/DeepTutor/pull/1141) | closed | yes | no | dev | fix/mastery-study-context |
| 1142 | [feat(video-learning): add timestamped transcript notes (#1137)](https://github.com/HKUDS/DeepTutor/pull/1142) | closed | yes | no | main | codex/feat/video-learning-transcript-notes |
| 1144 | [feat: add MiniMax Token Plan as a first-class LLM provider](https://github.com/HKUDS/DeepTutor/pull/1144) | closed | no | no | dev | feat/minimax-token-plan |
| 1145 | [fix(i18n): translate settings copy](https://github.com/HKUDS/DeepTutor/pull/1145) | closed | yes | no | dev | fix/settings-i18n |
| 1146 | [fix(video-learning): avoid Unix-only fcntl import on Windows](https://github.com/HKUDS/DeepTutor/pull/1146) | closed | yes | no | dev | fix/video-learning-windows-fcntl |
| 1148 | [feat(launcher): add macOS startup command](https://github.com/HKUDS/DeepTutor/pull/1148) | closed | yes | no | dev | codex/start-deeptutor-command |
| 1149 | [feat(settings): add tool search](https://github.com/HKUDS/DeepTutor/pull/1149) | closed | yes | no | dev | feat/settings-tool-search |
| 1151 | [fix(sandbox): enforce local exec output and process limits (#1150)](https://github.com/HKUDS/DeepTutor/pull/1151) | closed | yes | no | dev | codex/fix/sandbox-exec-limits |
| 1152 | [fix(runtime): ignore Windows SIGINT for deeptutor start (#1147)](https://github.com/HKUDS/DeepTutor/pull/1152) | closed | no | no | dev | fix/windows-launcher-ctrl-c-browser |
| 1153 | [test(video-learning): assert nested authentication policy (#1131)](https://github.com/HKUDS/DeepTutor/pull/1153) | closed | no | no | dev | codex/fix/video-learning-policy-mount |
| 1154 | [feat(launcher): add Windows startup batch script](https://github.com/HKUDS/DeepTutor/pull/1154) | open | no | no | dev | codex/start-deeptutor-bat |
| 1155 | [docs: fix stale AGENTS.md paths for capability_result and app facade](https://github.com/HKUDS/DeepTutor/pull/1155) | open | no | no | dev | docs/fix-agents-md-paths |
| 1156 | [feat(video-learning): add public Invidious hub discovery (#997)](https://github.com/HKUDS/DeepTutor/pull/1156) | closed | no | no | dev | codex/feat/video-learning-invidious-hub |
| 1157 | [fix(codex): expose Luna none reasoning effort](https://github.com/HKUDS/DeepTutor/pull/1157) | closed | yes | no | dev | fix/codex-luna-none-reasoning |
| 1159 | [feat(video-learning): add recent video summaries (#1158)](https://github.com/HKUDS/DeepTutor/pull/1159) | closed | no | no | dev | codex/feat/video-learning-recent |
| 1160 | [fix: prevent blank space below settings page](https://github.com/HKUDS/DeepTutor/pull/1160) | closed | yes | no | dev | fix/settings-bottom-gap |
| 1162 | [fix(web): decode unicode escapes in quiz card text](https://github.com/HKUDS/DeepTutor/pull/1162) | closed | yes | no | dev | fix/quiz-decode-unicode-escapes |
| 1163 | [docs: add RepoCloud one-click deploy button](https://github.com/HKUDS/DeepTutor/pull/1163) | open | no | no | dev | add-repocloud-deploy-button |
| 1165 | [feat(video-learning): keep active transcript cues visible (#1164)](https://github.com/HKUDS/DeepTutor/pull/1165) | closed | yes | no | dev | codex/feat/video-transcript-follow |
| 1167 | [test(mastery): cover study context providers (#1161)](https://github.com/HKUDS/DeepTutor/pull/1167) | closed | no | no | dev | codex/test/mastery-study-contexts |
| 1169 | [fix(video-learning): defer restored material loading (#1168)](https://github.com/HKUDS/DeepTutor/pull/1169) | closed | yes | no | dev | codex/fix/video-learning-defer-material-restore |
| 1170 | [fix(web): give WatchingContext a safe inactive default](https://github.com/HKUDS/DeepTutor/pull/1170) | closed | no | no | dev | fix/watching-context-safe-default |
| 1171 | [feat: pin LightRAG indexing models per knowledge base](https://github.com/HKUDS/DeepTutor/pull/1171) | closed | yes | no | dev | codex/nox-20-lightrag-indexing-model |
| 1174 | [feat: add LightRAG indexing model controls and provenance](https://github.com/HKUDS/DeepTutor/pull/1174) | closed | yes | no | dev | codex/nox-21-lightrag-indexing-ui |
| 1175 | [fix(llm): replay Responses reasoning output items](https://github.com/HKUDS/DeepTutor/pull/1175) | open | no | no | dev | fix-responses-api-reasoning-text |
| 1178 | [fix: preserve raw content during Chinese Markdown streaming](https://github.com/HKUDS/DeepTutor/pull/1178) | closed | yes | no | dev | fix/cjk-markdown-emphasis-streaming |
| 1179 | [feat(settings): allow any model reply language independently of the UI](https://github.com/HKUDS/DeepTutor/pull/1179) | closed | no | no | dev | feat/response-language-any |
| 1184 | [fix(cron): guard fcntl for Windows (msvcrt fallback)](https://github.com/HKUDS/DeepTutor/pull/1184) | closed | no | no | dev | fix/cron-fcntl-windows |
| 1185 | [fix(agentic): harden Gemini thought_signature capture](https://github.com/HKUDS/DeepTutor/pull/1185) | closed | no | no | dev | fix/gemini-thought-signature-replay |
| 1186 | [fix(update): detect source checkouts before enabling auto-update](https://github.com/HKUDS/DeepTutor/pull/1186) | closed | yes | no | dev | fix/source-install-update-detection |
| 1188 | [feat(learning): add visual learning board](https://github.com/HKUDS/DeepTutor/pull/1188) | closed | no | no | dev | codex/feat/visual-learning-board |
| 1189 | [fix(mastery): restore Save to Notebook and turn navigator](https://github.com/HKUDS/DeepTutor/pull/1189) | closed | no | no | dev | fix/mastery-study-notebook-turn-nav |
| 1191 | [perf(session): lazily load turn event traces](https://github.com/HKUDS/DeepTutor/pull/1191) | closed | yes | no | dev | codex/session-trace-memory |
| 1193 | [feat(video-learning): connect Invidious accounts (#1192)](https://github.com/HKUDS/DeepTutor/pull/1193) | closed | yes | no | dev | codex/feat/video-learning-invidious-account |
| 1194 | [feat(learning): add visual learning board (#1187)](https://github.com/HKUDS/DeepTutor/pull/1194) | closed | yes | no | dev | codex/feat/visual-learning-board-v2 |
| 1195 | [fix(llm): fall back on DeepSeek reasoning-replay 400s from Responses turns](https://github.com/HKUDS/DeepTutor/pull/1195) | closed | yes | no | dev | fix/responses-reasoning-fallback-markers |
| 1196 | [fix(web): redirect legacy mastery /study URLs to /sessions](https://github.com/HKUDS/DeepTutor/pull/1196) | closed | yes | no | dev | fix/mastery-study-to-sessions-redirect |
| 1197 | [test(cron): cover cross-platform migration locks](https://github.com/HKUDS/DeepTutor/pull/1197) | closed | yes | no | dev | fix/cron-fcntl-windows-msvcrt |
| 1198 | [fix(cron): support migration locks on Windows](https://github.com/HKUDS/DeepTutor/pull/1198) | closed | no | no | dev | fix/cron-windows-lock-1183 |
| 1199 | [fix(agentic): fall back for Gemini thinking tools](https://github.com/HKUDS/DeepTutor/pull/1199) | open | no | no | dev | fix/gemini-tool-fallback-1181 |
| 1200 | [fix(cli): expose knowledge-base progress events](https://github.com/HKUDS/DeepTutor/pull/1200) | closed | no | no | dev | fix/cli-kb-progress |
| 1201 | [fix(ci): restore dev release checks](https://github.com/HKUDS/DeepTutor/pull/1201) | closed | yes | no | dev | codex/fix/dev-ci-regressions |
| 1204 | [feat(video-learning): export timestamped notes as markdown (#1203)](https://github.com/HKUDS/DeepTutor/pull/1204) | closed | yes | no | dev | codex/feat/video-learning-notes-export |
| 1205 | [feat(search): filter unsafe web-search titles and snippets](https://github.com/HKUDS/DeepTutor/pull/1205) | closed | yes | no | dev | feat/web-search-content-source-filter |
| 1208 | [feat: add remote Hermes connected agent backend](https://github.com/HKUDS/DeepTutor/pull/1208) | closed | yes | no | main | feat/hermes-remote-backend |
| 1210 | [fix(ci): stabilize current dependency and reading gates](https://github.com/HKUDS/DeepTutor/pull/1210) | closed | yes | no | dev | codex/fix-dev-ci-fastapi |
| 1211 | [refactor(video-learning): separate Invidious account adapters](https://github.com/HKUDS/DeepTutor/pull/1211) | closed | yes | no | dev | codex/dev-decoupling-20260903 |
| 1212 | [revert: restore main after #1208 targeted the wrong base](https://github.com/HKUDS/DeepTutor/pull/1212) | closed | yes | no | main | codex/revert-accidental-main-1208 |
| 1213 | [feat: add hardened remote Hermes connected agent backend](https://github.com/HKUDS/DeepTutor/pull/1213) | closed | yes | no | dev | codex/hermes-remote-dev |
| 1214 | [feat(video-learning): add playback speed controls (#1207)](https://github.com/HKUDS/DeepTutor/pull/1214) | closed | no | no | dev | codex/feat/video-learning-playback-speed-v4 |
| 1216 | [fix(ci): restore dev route budgets (#1215)](https://github.com/HKUDS/DeepTutor/pull/1216) | closed | no | no | dev | codex/fix/dev-route-budgets |
| 1217 | [feat(mastery): add learning plan workflow foundation](https://github.com/HKUDS/DeepTutor/pull/1217) | closed | no | no | dev | feat/mastery-path-planning |
| 1218 | [feat(storage): content-addressed dedup for chat attachments](https://github.com/HKUDS/DeepTutor/pull/1218) | open | no | no | dev | feat/attachment-content-addressed-dedup |
| 1219 | [fix(agents): retry empty structured JSON in math animator](https://github.com/HKUDS/DeepTutor/pull/1219) | open | no | no | dev | fix/math-animator-structured-json-retry |
| 1221 | [fix(cli): give reasoning models room in the init connectivity probe](https://github.com/HKUDS/DeepTutor/pull/1221) | open | no | no | dev | bug/fix-issue-1220 |
| 1224 | [feat(video-learning): add transcript search (#1166)](https://github.com/HKUDS/DeepTutor/pull/1224) | closed | no | no | dev | codex/feat/video-learning-transcript-search-v4 |
| 1225 | [fix(learner): honor web learning policy (#1222)](https://github.com/HKUDS/DeepTutor/pull/1225) | closed | no | no | dev | codex/fix/learner-policy-web-shell |
| 1226 | [feat(learning): soft journal for multi-session teaching](https://github.com/HKUDS/DeepTutor/pull/1226) | open | no | no | dev | feat/learning-journal-mission-records |
| 1231 | [fix(learner): restore course access (#1228)](https://github.com/HKUDS/DeepTutor/pull/1231) | closed | yes | no | dev | codex/fix/learner-courses-1228 |
| 1232 | [fix: omit temperature for k3-256k](https://github.com/HKUDS/DeepTutor/pull/1232) | open | no | no | dev | fix/moonshot-k3-256k-temperature |
| 1233 | [feat(reading): support independent extension installation and fixed toolbar (#1233)](https://github.com/HKUDS/DeepTutor/pull/1233) | closed | no | no | dev | codex/fix-reading-extension-toolbar |
| 1237 | [feat(reading): add book paging and fullscreen to EPUBs](https://github.com/HKUDS/DeepTutor/pull/1237) | closed | no | no | dev | codex/feat/epub-book-paging |
| 1239 | [feat(video-learning): add a dedicated Watching workspace](https://github.com/HKUDS/DeepTutor/pull/1239) | closed | no | no | main | codex/upstream-watching-workspace |
| 1241 | [feat(video-learning): browse connected Invidious accounts](https://github.com/HKUDS/DeepTutor/pull/1241) | closed | yes | no | dev | codex/watching-invidious-account |
| 1243 | [feat: bundle a MarginNote 4 native add-on for the MN4 bridge](https://github.com/HKUDS/DeepTutor/pull/1243) | open | no | no | dev | feat/mn4-addon-client |
| 1247 | [fix: persist question notebook answer images](https://github.com/HKUDS/DeepTutor/pull/1247) | open | no | no | dev | fix/question-notebook-answer-images |
| 1248 | [feat(watching): integrate fullscreen learning and two-line captions](https://github.com/HKUDS/DeepTutor/pull/1248) | closed | no | no | dev | codex/watching-fullscreen-captions |
| 1251 | [fix: normalize Codex named-function tool choice for Responses](https://github.com/HKUDS/DeepTutor/pull/1251) | closed | no | no | dev | codex/fix-codex-tool-choice |
| 1253 | [fix(codex): recover Docker OAuth callbacks in settings](https://github.com/HKUDS/DeepTutor/pull/1253) | closed | no | no | dev | codex/fix-codex-container-callback |
| 1255 | [fix(watching): align transcript follow with video captions](https://github.com/HKUDS/DeepTutor/pull/1255) | closed | no | yes | dev | codex/watching-center-transcript |
| 1257 | [fix(watching): preserve note capture time and drafts across async saves](https://github.com/HKUDS/DeepTutor/pull/1257) | closed | no | yes | dev | codex/watching-notes-reliability |
| 1258 | [fix: persist notebook answer images](https://github.com/HKUDS/DeepTutor/pull/1258) | closed | yes | no | dev | fix/1245-question-notebook-image-upsert |
| 1260 | [fix: support Moonshot k3-256k temperature override](https://github.com/HKUDS/DeepTutor/pull/1260) | closed | yes | no | dev | codex/1227-k3-256k-temperature |
| 1261 | [fix(partners): register connected KBs instead of copytree-ing a folder that never exists](https://github.com/HKUDS/DeepTutor/pull/1261) | closed | yes | no | dev | fix/1259-partner-connected-kb-provisioning |
| 1263 | [docs(web): update overview screenshot for v1.6.5](https://github.com/HKUDS/DeepTutor/pull/1263) | closed | yes | no | dev | codex/docs/v1-6-5-overview-screenshot |
| 1264 | [fix(codex): expose eligible GPT-6 Astra in refreshed catalogs](https://github.com/HKUDS/DeepTutor/pull/1264) | closed | yes | no | dev | codex/nox-29-codex-catalog |
| 1265 | [feat(lightrag): configure independent roles and confirmed rebuilds](https://github.com/HKUDS/DeepTutor/pull/1265) | closed | yes | no | dev | codex/nox-30-lightrag-four-role-models |
| 1266 | [fix(chat): prevent PDF attachment tool hallucinations (#1223)](https://github.com/HKUDS/DeepTutor/pull/1266) | closed | yes | no | dev | codex/fix/chat-pdf-tool-hallucination |
| 1268 | [feat(rag): show LlamaIndex source figures in chat](https://github.com/HKUDS/DeepTutor/pull/1268) | open | no | no | dev | feat/llamaindex-rag-figures |
| 1269 | [fix(partners): restore generated artifact downloads (#1267)](https://github.com/HKUDS/DeepTutor/pull/1269) | closed | no | no | main | codex/fix/partner-artifact-downloads |
| 1270 | [feat(llm): allow any model reply language independently of the UI locale](https://github.com/HKUDS/DeepTutor/pull/1270) | closed | no | no | dev | feat/response-language-any |
| 1271 | [fix(llm): retry Responses requests without unsupported status](https://github.com/HKUDS/DeepTutor/pull/1271) | closed | yes | no | dev | fix/responses-input-status-compatibility |
| 1272 | [feat(subagent): add ACP client backend (Part of #1028)](https://github.com/HKUDS/DeepTutor/pull/1272) | open | no | no | dev | feat/acp-backend |
| 1274 | [fix(web): drop generated brand-icon table from app-shell chunk (unblocks route budgets)](https://github.com/HKUDS/DeepTutor/pull/1274) | closed | yes | no | dev | fix/web-route-budgets |
| 1275 | [chore(lightrag): upgrade native SDK to 1.5.7](https://github.com/HKUDS/DeepTutor/pull/1275) | closed | yes | no | dev | codex/nox-31-lightrag-1.5.7 |
| 1276 | [fix(web): normalize malformed ATX headings safely](https://github.com/HKUDS/DeepTutor/pull/1276) | closed | yes | no | dev | bugfix/markdown-atx-heading-normalization-20260906t160231z |
| 1277 | [feat(cli): add GitHub Copilot device login to init](https://github.com/HKUDS/DeepTutor/pull/1277) | closed | yes | no | dev | github-copilot-login |
| 1278 | [fix(chat): preserve pending ask_user turns (#1273)](https://github.com/HKUDS/DeepTutor/pull/1278) | closed | yes | no | dev | codex/fix/ask-user-turn-state |
| 1279 | [fix: require recorded learner evidence before awarding mastery](https://github.com/HKUDS/DeepTutor/pull/1279) | open | no | no | dev | codex/mastery-learner-evidence |
| 1280 | [fix: avoid progress errors after empty knowledge base creation](https://github.com/HKUDS/DeepTutor/pull/1280) | closed | yes | no | dev | codex/nox-36-empty-create-progress |
| 1281 | [fix: enforce native LightRAG embedding compatibility](https://github.com/HKUDS/DeepTutor/pull/1281) | closed | yes | no | dev | codex/nox-35-standalone-embedding |
| 1282 | [fix: restore formatting and deterministic CI checks](https://github.com/HKUDS/DeepTutor/pull/1282) | closed | yes | no | dev | codex/nox-37-ci-repair |
| 1283 | [fix(session): include ai_judgment in notebook_entries INSERT (#1245)](https://github.com/HKUDS/DeepTutor/pull/1283) | closed | no | no | dev | fix/1245-notebook-ai-judgment-column |
| 1284 | [fix: include ai_judgment in notebook INSERT, unblock CI gates, fix settings readiness panel](https://github.com/HKUDS/DeepTutor/pull/1284) | closed | no | no | dev | fix/1245-notebook-ai-judgment-column |
| 1285 | [fix: support GPT-5.6-Terra max_completion_tokens parameter](https://github.com/HKUDS/DeepTutor/pull/1285) | closed | no | no | dev | fix/gpt-5.6-terra-max-completion-tokens |
| 1286 | [fix(workspace): resolve workspace items from partner presentations](https://github.com/HKUDS/DeepTutor/pull/1286) | closed | no | no | dev | fix/partner-workspace-items-resolution |
| 1287 | [fix: resolve service mypy errors](https://github.com/HKUDS/DeepTutor/pull/1287) | closed | no | no | dev | codex/nox-38-mypy-services |
| 1291 | [fix(mastery): enable free-text question submission (#1289)](https://github.com/HKUDS/DeepTutor/pull/1291) | closed | yes | no | dev | codex/fix/mastery-submit |
| 1293 | [feat(knowledge): add KB frontier discovery tool (#1292)](https://github.com/HKUDS/DeepTutor/pull/1293) | closed | yes | no | dev | codex/feat/knowledge-frontier |
| 1295 | [feat(visualize): add Mermaid mindmap visualizer (#1294)](https://github.com/HKUDS/DeepTutor/pull/1295) | closed | yes | no | dev | codex/feat/mindmap-visualizer |
| 1298 | [fix(llm): raise a streamed provider error instead of answering with it](https://github.com/HKUDS/DeepTutor/pull/1298) | closed | yes | no | dev | fix/llm-stream-error-scope |
| 1300 | [fix(llm): survive api_key key pools in the config resolver](https://github.com/HKUDS/DeepTutor/pull/1300) | closed | yes | no | dev | fix/resolver-api-key-list |
| 1302 | [feat(knowledge): add URL import for knowledge bases (#1301)](https://github.com/HKUDS/DeepTutor/pull/1302) | closed | no | no | main | codex/feat/kb-url-import |
| 1304 | [feat(knowledge): add Zotero search tool and BibTeX structured parsing (#1303)](https://github.com/HKUDS/DeepTutor/pull/1304) | closed | no | no | main | codex/feat/zotero-bibtex-import |
| 1305 | [fix(reading): package PDF.js decoder assets (#1299)](https://github.com/HKUDS/DeepTutor/pull/1305) | closed | yes | no | dev | codex/fix/pdf-jpeg2000-assets |
| 1306 | [docs(web): document v1.6.4/v1.6.5 screenshot status](https://github.com/HKUDS/DeepTutor/pull/1306) | closed | yes | no | dev | codex/docs/v1-6-4-5-ui-docs |
| 1308 | [fix(web): fall back when crypto.randomUUID is unavailable for command ids](https://github.com/HKUDS/DeepTutor/pull/1308) | closed | yes | no | dev | fix/command-id-fallback |
| 1309 | [feat(plugins): add managed third-party plugin platform (#1307)](https://github.com/HKUDS/DeepTutor/pull/1309) | closed | no | no | dev | codex/plugins-platform-dev-v1 |
| 1310 | [feat(web): fully resizable reading workspace panels + focus preset](https://github.com/HKUDS/DeepTutor/pull/1310) | closed | yes | no | dev | feat/reading-companion-focus |
| 1311 | [feat(codex-auth): discover stable client version (#1296)](https://github.com/HKUDS/DeepTutor/pull/1311) | closed | no | no | dev | codex/feat/codex-client-version-discovery |
| 1312 | [fix(chat): always clear sending state in useCardSubmission (#1289)](https://github.com/HKUDS/DeepTutor/pull/1312) | closed | no | no | dev | dev |
| 1313 | [fix(chat): always clear sending state in useCardSubmission (#1289)](https://github.com/HKUDS/DeepTutor/pull/1313) | closed | no | no | dev | fix/submit-button-1289 |
| 1314 | [fix(web): render settings readiness panel for read-only users](https://github.com/HKUDS/DeepTutor/pull/1314) | closed | yes | no | dev | fix/settings-readiness-panel |
| 1315 | [fix(workspace): resolve workspace items from partner presentations (#1267)](https://github.com/HKUDS/DeepTutor/pull/1315) | closed | no | no | dev | fix/workspace-partner-presentations |
| 1317 | [feat(codex): automatically discover client versions for model catalog refresh](https://github.com/HKUDS/DeepTutor/pull/1317) | closed | yes | no | dev | codex/codex-catalog-client-version |
| 1319 | [feat：Use Electron to build desktop applications for Linux, macOS, and Windows.](https://github.com/HKUDS/DeepTutor/pull/1319) | closed | no | no | main | chenhj-dev |
| 1320 | [fix(config): let a book capability's agents.yaml settings take effect](https://github.com/HKUDS/DeepTutor/pull/1320) | closed | no | no | dev | fix/1316-book-capability-config-plumbing |
| 1321 | [fix(book): configure agent token budget (#1316)](https://github.com/HKUDS/DeepTutor/pull/1321) | closed | no | no | dev | codex/fix/book-agent-token-budget |
| 1322 | [feat：Use Electron to build desktop applications for Linux, macOS, and Windows.](https://github.com/HKUDS/DeepTutor/pull/1322) | open | no | no | dev | chenhj-dev |
| 1323 | [fix(learner): complete surface map for first-party learner screens + flip preset on restrictions assignment (#1222)](https://github.com/HKUDS/DeepTutor/pull/1323) | closed | yes | no | dev | fix/learner-surface-map |
| 1325 | [fix(questions): reject incomplete quiz plans](https://github.com/HKUDS/DeepTutor/pull/1325) | closed | yes | no | dev | fix/quiz-plan-completeness |
| 1327 | [fix(web): support current Codex chat history imports](https://github.com/HKUDS/DeepTutor/pull/1327) | closed | yes | no | dev | fix/codex-chat-history-import |
| 1330 | [feat(users): add batch import and deletion (#1329)](https://github.com/HKUDS/DeepTutor/pull/1330) | closed | yes | no | dev | codex/feat/bulk-user-management |
| 1331 | [fix: handle DeepSeek reasoning budget exhaustion](https://github.com/HKUDS/DeepTutor/pull/1331) | closed | yes | no | dev | codex/fix-issue-1328-reasoning-budget |
| 1332 | [fix(turns): log when a coordinator-routed reply finds no local waiter](https://github.com/HKUDS/DeepTutor/pull/1332) | closed | yes | no | dev | fix/1297-submit-user-reply-silent-drop |
| 1333 | [fix(chat): recover hallucinated PDF tool calls for attached sources](https://github.com/HKUDS/DeepTutor/pull/1333) | closed | yes | no | dev | aohanbei/fix/issue-1223-pdf-tool |
| 1334 | [feat(knowledge): add linked folder manual sync](https://github.com/HKUDS/DeepTutor/pull/1334) | closed | yes | no | dev | feat/knowledge-center-local-folder-sync |
| 1335 | [feat: add french as supported language](https://github.com/HKUDS/DeepTutor/pull/1335) | closed | yes | no | dev | feat/add-french-translation |
| 1337 | [docs(web): add v1.6.5 settings screenshots](https://github.com/HKUDS/DeepTutor/pull/1337) | closed | yes | no | dev | codex/docs/v1-6-5-settings-screenshots |
| 1338 | [fix(graphrag): prevent pandas.period extension conflicts on Windows](https://github.com/HKUDS/DeepTutor/pull/1338) | closed | no | no | dev | fix/graphrag-pandas-period-conflict |
| 1339 | [feat(notebook): expose direct record editing](https://github.com/HKUDS/DeepTutor/pull/1339) | closed | yes | no | dev | codex/feat/notebook-edit-discoverability |
| 1340 | [feat(search): add Web Risk lookups and renumber filtered citations (#375)](https://github.com/HKUDS/DeepTutor/pull/1340) | closed | yes | no | dev | feat/web-risk-citation-renumber |
| 1341 | [feat(partners): record wrong questions into the question bank (#1244)](https://github.com/HKUDS/DeepTutor/pull/1341) | closed | yes | no | dev | feat/partner-question-bank-record |
| 1343 | [fix(anthropic): stop sending `temperature` to Claude Sonnet 5 / Opus 4.8](https://github.com/HKUDS/DeepTutor/pull/1343) | closed | yes | no | dev | fix/claude-temperature-deprecated |
| 1344 | [feat(i18n): add Ukrainian as a full interface and output language](https://github.com/HKUDS/DeepTutor/pull/1344) | closed | yes | no | dev | feat/ukrainian-locale |
| 1345 | [feat(settings): expand response language options](https://github.com/HKUDS/DeepTutor/pull/1345) | closed | yes | no | dev | codex/issue1176-response-language |
| 1346 | [fix(visualize): reject fatal GeoGebra Text patterns and surface evalCommand failures](https://github.com/HKUDS/DeepTutor/pull/1346) | closed | yes | no | dev | codex/fix/ggb-validator-fatal-patterns |
| 1349 | [fix(skills): distinguish missing file from missing skill in read_skill](https://github.com/HKUDS/DeepTutor/pull/1349) | closed | yes | no | dev | codex/fix/read-skill-distinguish-file-error |
| 1350 | [feat(watching): preserve note timestamps and add save retry UX](https://github.com/HKUDS/DeepTutor/pull/1350) | closed | yes | no | dev | codex/feat/watching-note-timestamps |
| 1351 | [fix(watching): clamp transcript alignment to middle 50% and respect reduced motion](https://github.com/HKUDS/DeepTutor/pull/1351) | closed | yes | no | dev | codex/fix/transcript-alignment |
| 1353 | [fix(imagegen): retry with image-only modalities when both are unsupported](https://github.com/HKUDS/DeepTutor/pull/1353) | closed | yes | no | dev | codex/fix/openrouter-imagegen-modalities |
| 1357 | [fix(research): enforce tool timeout and retry policy (#1355)](https://github.com/HKUDS/DeepTutor/pull/1357) | closed | yes | no | dev | codex/fix/research-tool-timeout |
| 1358 | [fix(rag): surface embedding connectivity failures (#1356)](https://github.com/HKUDS/DeepTutor/pull/1358) | closed | no | no | main | codex/fix/rag-embedding-diagnostics |
| 1360 | [feat: add Grok CLI subagent connector](https://github.com/HKUDS/DeepTutor/pull/1360) | closed | yes | no | dev | feat/grok-cli-connector |
| 1361 | [fix(turns): reap an unowned waiting_input turn when a reply arrives (#1297)](https://github.com/HKUDS/DeepTutor/pull/1361) | closed | yes | no | dev | fix/waiting-turn-recovery-on-lost-waiter |
| 1362 | [fix(geogebra): repair image analysis that crashed before any model call](https://github.com/HKUDS/DeepTutor/pull/1362) | closed | yes | no | dev | fix/geogebra-analysis-crash |
| 1363 | [fix(chat): unlock the window when ask_user replies never land](https://github.com/HKUDS/DeepTutor/pull/1363) | closed | no | no | dev | fix/ask-user-chat-lock-1359 |
| 1365 | [fix: render LaTeX in mastery question cards](https://github.com/HKUDS/DeepTutor/pull/1365) | closed | no | no | dev | fix/mastery-card-latex |
| 1366 | [fix(book): isolate LLM scratchpad from generated content](https://github.com/HKUDS/DeepTutor/pull/1366) | closed | yes | no | dev | fix/book-scratchpad-leak |
| 1367 | [feat(reading): add fullscreen learning workspace shell (#1367)](https://github.com/HKUDS/DeepTutor/pull/1367) | closed | yes | no | dev | codex/fix/reading-learning-shell |
| 1368 | [feat(learner): add account-scoped reading learning records (#1109)](https://github.com/HKUDS/DeepTutor/pull/1368) | closed | yes | no | dev | codex/feat/learner-reading-records-focused |
| 1369 | [feat(learner): add personal learning progress view (#1130)](https://github.com/HKUDS/DeepTutor/pull/1369) | closed | yes | no | dev | codex/feat/learner-progress-view-1130-focused-stack |
| 1370 | [fix(skills): improve read_skill file recovery (#1347)](https://github.com/HKUDS/DeepTutor/pull/1370) | closed | yes | no | dev | codex/fix/read-skill-missing-file-error |
| 1371 | [feat(knowledge): add Zotero BibTeX search (#1303)](https://github.com/HKUDS/DeepTutor/pull/1371) | closed | yes | no | dev | codex/feat/zotero-bibtex-focused |
| 1372 | [feat(knowledge): expose linked folder sync controls (#1326)](https://github.com/HKUDS/DeepTutor/pull/1372) | closed | yes | no | dev | codex/feat/kb-folder-sync-ui |
| 1373 | [fix(turns): recover replies after waiter queue loss](https://github.com/HKUDS/DeepTutor/pull/1373) | closed | yes | no | dev | codex/fix/ask-user-waiter-loss |
| 1374 | [feat(sidebar): collapse fixed multi-user sections (#1230)](https://github.com/HKUDS/DeepTutor/pull/1374) | open | no | yes | dev | codex/feat/sidebar-multiuser-collapse |
| 1375 | [fix(users): derive learner preset from active policy](https://github.com/HKUDS/DeepTutor/pull/1375) | closed | yes | yes | dev | codex/fix/learner-policy-preset |
| 1376 | [feat(reading): reanchor selectors across revisions](https://github.com/HKUDS/DeepTutor/pull/1376) | closed | yes | yes | dev | codex/feat/reading-selector-revision |
| 1377 | [feat(resource-providers): add provider foundations and web controls (#961)](https://github.com/HKUDS/DeepTutor/pull/1377) | closed | no | yes | dev | codex/feat/resource-providers |
| 1379 | [feat(reading): add provider-aware media ingestion](https://github.com/HKUDS/DeepTutor/pull/1379) | closed | yes | no | dev | codex/reading-media-providers |
| 1380 | [feat(reading): add transcript-aware media stage (#1378)](https://github.com/HKUDS/DeepTutor/pull/1380) | closed | yes | no | dev | codex/reading-media-stage |
| 1381 | [feat(settings): export value-free profiles](https://github.com/HKUDS/DeepTutor/pull/1381) | closed | yes | no | dev | codex/feat/settings-profile-export |
| 1382 | [fix(path-service): restore workspace chat output downloads](https://github.com/HKUDS/DeepTutor/pull/1382) | closed | yes | no | dev | codex/fix/output-path-allowance |
| 1383 | [feat(settings): add reviewable named presets](https://github.com/HKUDS/DeepTutor/pull/1383) | closed | yes | no | dev | codex/feat/settings-named-presets |
| 1384 | [feat(reading): converge immersive watching into reading (#1378)](https://github.com/HKUDS/DeepTutor/pull/1384) | open | no | yes | dev | codex/feat/reading-media-convergence |
| 1385 | [feat(web-source): add durable sync scheduling](https://github.com/HKUDS/DeepTutor/pull/1385) | closed | yes | no | dev | codex/feat/settings-capability-readiness |
| 1386 | [fix(knowledge): add local OCR fallback for scanned PDFs (#431)](https://github.com/HKUDS/DeepTutor/pull/1386) | closed | yes | no | dev | codex/fix/scanned-pdf-ocr-fallback |
| 1387 | [feat(audio-overview): add KB audio overview pipeline](https://github.com/HKUDS/DeepTutor/pull/1387) | closed | yes | no | dev | codex/feat/audio-overview |
| 1388 | [fix(agents): ignore leading think blocks when extracting JSON](https://github.com/HKUDS/DeepTutor/pull/1388) | closed | yes | no | dev | fix/structured-json-leading-think |
| 1391 | [feat(payment): RIC-546/549/550 commercial payment layer (fork → upstream)](https://github.com/HKUDS/DeepTutor/pull/1391) | closed | no | no | main | feat/ric549-payment-frontend |
| 1394 | [feat(chat): add resend for failed turns](https://github.com/HKUDS/DeepTutor/pull/1394) | closed | yes | no | dev | codex/feat/chat-resend |
| 1395 | [fix(web): explicit retryable false takes precedence over HTTP status](https://github.com/HKUDS/DeepTutor/pull/1395) | closed | no | no | dev | codex/fix/retryable-precedence |
| 1396 | [fix(web): honor explicit retryable flags](https://github.com/HKUDS/DeepTutor/pull/1396) | closed | yes | no | dev | fix/1393-retryable-precedence |
| 1397 | [feat(knowledge): add knowledge_frontier discovery tool](https://github.com/HKUDS/DeepTutor/pull/1397) | closed | no | no | dev | codex/feat/kb-frontier-discovery |
| 1398 | [feat(sessions): add recycle bin for deleted chats](https://github.com/HKUDS/DeepTutor/pull/1398) | closed | yes | no | dev | codex/feat/recycle-bin |
| 1399 | [feat(textbook): rebuild chapters from running headers embedded mid-text](https://github.com/HKUDS/DeepTutor/pull/1399) | closed | yes | no | dev | upstream-pr/running-header-chapter-rebuild |
| 1401 | [fix(config): bump probe budget for reasoning models](https://github.com/HKUDS/DeepTutor/pull/1401) | closed | yes | no | dev | codex/fix/reasoning-probe-budget |
| 1402 | [fix(agent-loop): recover bounded reasoning-only finishes (#1400)](https://github.com/HKUDS/DeepTutor/pull/1402) | closed | yes | no | dev | codex/fix/reasoning-only-recovery |
| 1403 | [fix(mastery): bind draft before sending opening turn](https://github.com/HKUDS/DeepTutor/pull/1403) | open | no | no | dev | codex/fix-1392-mastery-draft-binding |
| 1404 | [fix(explore-context): keep reasoning on replayed rounds for thinking providers (#1400)](https://github.com/HKUDS/DeepTutor/pull/1404) | closed | yes | no | dev | fix/deepseek-reasoning-recovery |
| 1408 | [feat(imports): add ChatGPT conversation export support](https://github.com/HKUDS/DeepTutor/pull/1408) | closed | yes | no | dev | feat/1405-chatgpt-import |
| 1413 | [fix(runtime): cancel the capability when a turn's consumer stops](https://github.com/HKUDS/DeepTutor/pull/1413) | closed | yes | no | dev | fix/orchestrator-cancel-capability |
| 1414 | [fix(graphrag): recover stale pandas Arrow extension registrations](https://github.com/HKUDS/DeepTutor/pull/1414) | closed | yes | no | dev | fix/graphrag-pandas-period-v2 |
| 1415 | [feat(chat): search full conversation history](https://github.com/HKUDS/DeepTutor/pull/1415) | closed | yes | no | dev | feat/1406-conversation-search |
| 1416 | [fix(mastery): refuse a new-session handoff for the topic a turn is tutoring (#1412)](https://github.com/HKUDS/DeepTutor/pull/1416) | open | no | no | dev | fix/mastery-new-session-same-topic-loop |
| 1417 | [fix(mastery): drop duplicate ask_user options (#1409)](https://github.com/HKUDS/DeepTutor/pull/1417) | closed | yes | no | dev | codex/fix/mastery-unique-options-1409 |
| 1418 | [fix(ask-user): drop an option whose visible text duplicates another (#1409)](https://github.com/HKUDS/DeepTutor/pull/1418) | closed | yes | no | dev | fix/ask-user-duplicate-options |
| 1420 | [feat(reading): add age-aware action buttons](https://github.com/HKUDS/DeepTutor/pull/1420) | closed | no | yes | dev | codex/feat/reading-age-buttons |
| 1423 | [test(api): isolate partners router auth state (#1422)](https://github.com/HKUDS/DeepTutor/pull/1423) | closed | yes | no | dev | codex/test/partners-auth-isolation |
| 1425 | [fix(web): package standalone runtime assets (#1424)](https://github.com/HKUDS/DeepTutor/pull/1425) | closed | no | no | dev | codex/fix/standalone-assets |
| 1427 | [fix(api): preserve actual proxy peer identity (#1426)](https://github.com/HKUDS/DeepTutor/pull/1427) | closed | yes | no | dev | codex/fix/uvicorn-proxy-peer |
| 1430 | [fix(knowledge): respect robots crawl policy (#1429)](https://github.com/HKUDS/DeepTutor/pull/1430) | closed | no | no | dev | codex/fix/crawler-robots |
| 1431 | [fix(web): skip forced --webpack on Vercel to fix ENOENT deploy failure](https://github.com/HKUDS/DeepTutor/pull/1431) | closed | yes | no | dev | fix/vercel-webpack-build |
| 1433 | [test(app): stabilize multiworker reply subscription (#1432)](https://github.com/HKUDS/DeepTutor/pull/1433) | closed | yes | no | dev | codex/test/multiworker-reply-subscription |
| 1436 | [fix(settings): skip the client reset when an apply changes nothing (#1421)](https://github.com/HKUDS/DeepTutor/pull/1436) | closed | yes | no | dev | fix/catalog-apply-skips-identical-reset |
| 1441 | [fix(web): keep deep book routes in loading state](https://github.com/HKUDS/DeepTutor/pull/1441) | closed | yes | no | dev | fix/1440-deep-book-url-loading-state |
| 1442 | [fix(reading): keep material loading during hydration](https://github.com/HKUDS/DeepTutor/pull/1442) | closed | yes | no | dev | fix/1439-reading-material-loading |
| 1443 | [fix(turns): keep prior conversation images readable on later turns (#1438)](https://github.com/HKUDS/DeepTutor/pull/1443) | closed | yes | no | dev | fix/prior-image-attachments-cross-turn |
| 1444 | [feat(sessions): soft-delete recycle bin with restore and permanent delete](https://github.com/HKUDS/DeepTutor/pull/1444) | closed | no | no | dev | feat/recycle-bin |
| 1445 | [feat(search): full conversation search with LIKE escaping](https://github.com/HKUDS/DeepTutor/pull/1445) | closed | no | no | dev | feat/conversation-search |
| 1446 | [feat: Persistent File Library with API router (issue #1437)](https://github.com/HKUDS/DeepTutor/pull/1446) | closed | yes | no | dev | feat/file-library |
| 1449 | [fix(logging): schedule log coroutines from worker threads; make backend readiness budget configurable (#1435)](https://github.com/HKUDS/DeepTutor/pull/1449) | closed | no | no | dev | fix/log-scheduling-off-loop |
| 1450 | [fix(reading): run async extension handlers on the loop, not in an executor (#1448)](https://github.com/HKUDS/DeepTutor/pull/1450) | open | no | no | dev | fix/reading-async-extension-uvloop |
| 1452 | [fix(embedding): parse HTTP-date Retry-After values](https://github.com/HKUDS/DeepTutor/pull/1452) | closed | yes | no | dev | fix/1451-embedding-retry-after-http-date |
| 1453 | [Faithful-book pipeline: anchored question generation, KP bridging, overview-anchor chapter rebuild](https://github.com/HKUDS/DeepTutor/pull/1453) | closed | no | no | main | pipeline-faithful-chain |
| 1455 | [perf(web): disable sidebar viewport prefetch (#1447)](https://github.com/HKUDS/DeepTutor/pull/1455) | closed | yes | no | dev | codex/fix/sidebar-prefetch |
| 1456 | [fix(marginnote4): close the store's SQLite connections](https://github.com/HKUDS/DeepTutor/pull/1456) | closed | yes | no | dev | fix/marginnote4-close-store-connections |
| 1457 | [Faithful-book material pipeline: anchored question generation, KP bridging, multi-tier chapter rebuild](https://github.com/HKUDS/DeepTutor/pull/1457) | closed | no | no | main | pipeline-v168 |
| 1459 | [fix(docker): remap PUID/PGID for Unraid bind mounts (#1458)](https://github.com/HKUDS/DeepTutor/pull/1459) | closed | yes | no | dev | fix/unraid-volume-permissions |
| 1460 | [fix(visualize): repair GeoGebra Text coordinates](https://github.com/HKUDS/DeepTutor/pull/1460) | closed | yes | no | dev | codex/fix/ggb-text-validation |
| 1462 | [fix(partners): route outbound Telegram messages to the inbound topic thread](https://github.com/HKUDS/DeepTutor/pull/1462) | closed | yes | no | dev | fix/telegram-outbound-thread-routing |
| 1463 | [50/50 RevShare Integration: DeepTutor & AIML API](https://github.com/HKUDS/DeepTutor/pull/1463) | open | no | no | dev | feat/aimlapi-upstream |
| 1464 | [fix(reading): keep mobile toolbar actions reachable](https://github.com/HKUDS/DeepTutor/pull/1464) | closed | yes | no | dev | codex/fix/reading-mobile-toolbar |
| 1465 | [fix(mastery): time turns from submission](https://github.com/HKUDS/DeepTutor/pull/1465) | closed | no | no | dev | codex/fix/mastery-turn-submission-timer |
| 1466 | [fix(codex): fail fast on a credential that no longer refreshes instead of re-prompting every turn (#1454)](https://github.com/HKUDS/DeepTutor/pull/1466) | closed | yes | no | dev | fix/codex-oauth-fail-fast |
| 1469 | [fix(web): 加载带 polyfill 的 PDF.js 构建，让旧版引擎也能渲染](https://github.com/HKUDS/DeepTutor/pull/1469) | closed | yes | no | dev | fix/pdfjs-legacy-bundle |
| 1470 | [chore(deps): 让 qrcode 随核心依赖安装](https://github.com/HKUDS/DeepTutor/pull/1470) | closed | yes | no | dev | chore/qrcode-core-dependency |
| 1472 | [fix(reading): normalize packaged EPUB archives (#1447)](https://github.com/HKUDS/DeepTutor/pull/1472) | closed | yes | no | dev | codex/fix/epub-archive-normalization |
| 1474 | [fix: enforce mastery quiz delivery before successful completion](https://github.com/HKUDS/DeepTutor/pull/1474) | open | no | yes | dev | fix/mastery-card-promises |
| 1475 | [feat: complete adaptive SRS persistence and review UI](https://github.com/HKUDS/DeepTutor/pull/1475) | closed | yes | no | dev | feat/issue-1471-adaptive-srs-mvp |
| 1477 | [feat(learning): persist mastery prerequisites and topic-source links (#1476)](https://github.com/HKUDS/DeepTutor/pull/1477) | closed | yes | no | dev | codex/learning-mastery-prerequisites |
| 1479 | [fix(video-learning): decode caption HTML entities](https://github.com/HKUDS/DeepTutor/pull/1479) | closed | yes | no | dev | codex/fix-subtitle-html-entities-upstream |
| 1480 | [fix(rag): stop a stalled LlamaIndex worker leaking progress into the next job (#1478)](https://github.com/HKUDS/DeepTutor/pull/1480) | closed | yes | no | dev | fix/llamaindex-reindex-progress-finish |
| 1482 | [feat(auth): add secure public session handoff (#1467)](https://github.com/HKUDS/DeepTutor/pull/1482) | closed | yes | no | dev | codex/feat/session-handoff |
| 1483 | [docs: sync AGENTS.md with the current turn runtime](https://github.com/HKUDS/DeepTutor/pull/1483) | closed | yes | no | dev | docs/sync-agents-runtime |
| 1485 | [fix(notebook): prevent path traversal via read/write path asymmetry](https://github.com/HKUDS/DeepTutor/pull/1485) | closed | yes | no | dev | fix/notebook-path-traversal |
| 1486 | [feat: add native Volcengine (Doubao Seed-TTS) TTS provider](https://github.com/HKUDS/DeepTutor/pull/1486) | closed | no | no | dev | feature/volcengine-tts |
| 1487 | [fix(turns): regenerate a turn with attachments without breaking TurnRequest validation (#1484)](https://github.com/HKUDS/DeepTutor/pull/1487) | closed | no | no | dev | fix/turn-attachment-retry-start |
| 1488 | [fix(knowledge): bootstrap empty KBs on first upload](https://github.com/HKUDS/DeepTutor/pull/1488) | closed | yes | no | dev | fix/1481-empty-kb-upload-index-init |
| 1490 | [fix(github-source): refresh unchanged sync state](https://github.com/HKUDS/DeepTutor/pull/1490) | closed | yes | no | dev | fix/1489-refresh-unchanged-github-source-state |
| 1492 | [fix(usage): prefer exact model pricing matches](https://github.com/HKUDS/DeepTutor/pull/1492) | closed | yes | no | dev | fix/llm-pricing-exact-match |
| 1494 | [feat(rag): expose LightRAG llm_timeout so extraction LLM timeouts are tunable](https://github.com/HKUDS/DeepTutor/pull/1494) | closed | yes | no | dev | feat/lightrag-llm-timeout |
| 1495 | [fix(llm): treat grok as a large-context family](https://github.com/HKUDS/DeepTutor/pull/1495) | closed | yes | no | dev | fix/grok-large-context-window |
| 1496 | [fix(runtime): bypass system proxy for loopback health checks](https://github.com/HKUDS/DeepTutor/pull/1496) | closed | yes | no | dev | fix/loopback-health-check-proxy |
| 1499 | [fix(llm): try every API key after rate limits](https://github.com/HKUDS/DeepTutor/pull/1499) | closed | yes | no | dev | fix/llm-key-rotation-exhaust-pool |
| 1503 | [feat(reading): figures from PDFs, captions at ingest, and drawn-page renders](https://github.com/HKUDS/DeepTutor/pull/1503) | closed | yes | no | dev | feat/reading-figures |
| 1504 | [feat(learning): persist cross-surface Focus-Check in Question Bank](https://github.com/HKUDS/DeepTutor/pull/1504) | closed | yes | no | dev | feat/issue-1471-cross-surface-evidence |
| 1505 | [fix(parsing): fall back to a text-capable engine when the global default can't take a file (#1502)](https://github.com/HKUDS/DeepTutor/pull/1505) | closed | no | no | dev | fix/parsing-engine-fallback |
| 1506 | [fix: add missing task model branch to config test runner](https://github.com/HKUDS/DeepTutor/pull/1506) | closed | yes | no | dev | fix/task-model-config-test |
| 1510 | [fix(github-source): refresh sync state on unchanged SHA](https://github.com/HKUDS/DeepTutor/pull/1510) | open | no | no | dev | fix/1489-github-source-stale-state |
| 1513 | [fix(rag): report empty retrieval results (#1500)](https://github.com/HKUDS/DeepTutor/pull/1513) | closed | yes | no | dev | codex/fix/rag-empty-result |
| 1518 | [feat(learning): rank reviews from repeated misconceptions and explicit prerequisites](https://github.com/HKUDS/DeepTutor/pull/1518) | closed | no | no | dev | feat/1471-misconception-prerequisite-state |
| 1521 | [fix(chat): route PDF attachments through configured parser](https://github.com/HKUDS/DeepTutor/pull/1521) | closed | no | no | dev | codex/fix-chat-attachment-parser |
| 1524 | [fix(books): preserve deep-route loading context](https://github.com/HKUDS/DeepTutor/pull/1524) | closed | no | no | dev | fix/1440-book-deep-route-loading |
| 1529 | [Add Unifically LLM provider](https://github.com/HKUDS/DeepTutor/pull/1529) | closed | yes | no | dev | feat/unifically-provider |
| 1530 | [fix(mastery): keep learning evidence bound to objective identity](https://github.com/HKUDS/DeepTutor/pull/1530) | open | no | no | dev | fix/issue-1527-mastery-state-integrity |
| 1531 | [feat(i18n): add German as a full interface language](https://github.com/HKUDS/DeepTutor/pull/1531) | closed | yes | no | dev | feat/german-localization |
| 1532 | [feat(voice): verbalize LaTeX in TTS with a Math speak setting](https://github.com/HKUDS/DeepTutor/pull/1532) | closed | yes | no | dev | feat/tts-math-speak |
| 1533 | [merge  v1.6.9](https://github.com/HKUDS/DeepTutor/pull/1533) | closed | no | no | main | chenhj-dev |
| 1535 | [fix(mastery): restore Skills picker and workspace persona presets](https://github.com/HKUDS/DeepTutor/pull/1535) | closed | yes | no | dev | fix/1534-mastery-skills-workspace-personas |
| 1537 | [fix(question): retry a starved quiz repair, and count it honestly (#1508)](https://github.com/HKUDS/DeepTutor/pull/1537) | closed | yes | no | dev | fix/question-generation-reasoning-starvation |
| 1538 | [fix(web): offer the skills picker to mastery conversations (#1534)](https://github.com/HKUDS/DeepTutor/pull/1538) | closed | no | no | dev | fix/mastery-skills-picker |
| 1539 | [fix(session): name the reply language in the compaction instruction (#1511)](https://github.com/HKUDS/DeepTutor/pull/1539) | closed | yes | no | dev | fix/session-summary-language |
| 1551 | [fix(learning): keep Personalized Learning inside strict LazyMotion](https://github.com/HKUDS/DeepTutor/pull/1551) | open | no | no | dev | fix/1549-learning-lazy-motion |
| 1552 | [fix(visualize): point the no-payload diagnosis at the real remedy (#1546)](https://github.com/HKUDS/DeepTutor/pull/1552) | closed | yes | no | dev | fix/visualize-configured-max-tokens |
| 1553 | [fix(math-animator): raise the output budget when reasoning is truncated](https://github.com/HKUDS/DeepTutor/pull/1553) | open | no | no | dev | fix/math-animator-reasoning-truncation |
| 1556 | [refactor(auth): converge all role whitelists on a single normalize_role, add first set_role tests](https://github.com/HKUDS/DeepTutor/pull/1556) | closed | yes | no | dev | pr/roles-normalize-tests |
| 1557 | [fix(voice): stop speaking asterisks and drop the play-aloud auto-play prompt](https://github.com/HKUDS/DeepTutor/pull/1557) | closed | yes | no | dev | feat/tts-playback-followup |
| 1558 | [feat(partners): export group conversations as Markdown](https://github.com/HKUDS/DeepTutor/pull/1558) | closed | yes | no | dev | feat/1512-group-chat-export |
| 1563 | [fix(voice): use realtime DashScope STT model ids](https://github.com/HKUDS/DeepTutor/pull/1563) | closed | yes | no | dev | fix/dashscope-stt-realtime-model |
| 1564 | [fix(media): use the real DashScope image/video submit endpoints](https://github.com/HKUDS/DeepTutor/pull/1564) | closed | yes | no | dev | fix/dashscope-media-endpoints |
| 1565 | [feat(partners): roam web sessions across browsers](https://github.com/HKUDS/DeepTutor/pull/1565) | open | no | no | dev | feat/1512-partner-session-roaming |
| 1567 | [feat(auth): admit "teacher" and "student" role values in the single role whitelist](https://github.com/HKUDS/DeepTutor/pull/1567) | closed | yes | no | dev | feat/roles-teacher-student |
| 1569 | [feat(parsing): auto-slice oversized PDFs for MinerU cloud parsing](https://github.com/HKUDS/DeepTutor/pull/1569) | closed | yes | no | dev | pr/mineru-large-pdf-slicing |
| 1571 | [feat: add Cheaper Inference as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/1571) | closed | yes | no | dev | feature/cheaper-inference-provider |
| 1572 | [feat(auth): admit "teacher" and "student" role values in the single role whitelist](https://github.com/HKUDS/DeepTutor/pull/1572) | open | no | no | dev | auth-role-whitelist |
| 1573 | [fix: refresh managed Codex catalog for GPT-6 Sol and Luna](https://github.com/HKUDS/DeepTutor/pull/1573) | closed | no | no | dev | codex/nox-50-codex-catalog |
| 1574 | [fix: use headings for uploaded Markdown outlines](https://github.com/HKUDS/DeepTutor/pull/1574) | closed | yes | no | dev | fix/nox-45-markdown-outline |
| 1576 | [feat(reading): let the reader look at any stored figure on demand](https://github.com/HKUDS/DeepTutor/pull/1576) | closed | yes | no | dev | feat/reading-view-figure |
| 1580 | [feat: add a workspace-scoped task board](https://github.com/HKUDS/DeepTutor/pull/1580) | closed | yes | no | dev | codex/task-board |
| 1581 | [fix(i18n): add missing translations for fr language](https://github.com/HKUDS/DeepTutor/pull/1581) | closed | yes | no | dev | fix/french-translation-gaps |
| 1582 | [fix(mineru): scale cloud retry budget with key pool size](https://github.com/HKUDS/DeepTutor/pull/1582) | closed | yes | no | dev | pr/mineru-retry-budget-keypool |
| 1583 | [test(api): adapt knowledge_router/file_preview tests to lazy route inclusion](https://github.com/HKUDS/DeepTutor/pull/1583) | closed | yes | no | dev | fix/fastapi-lazy-include-tests |
| 1588 | [fix(llm): match Gemini ids carrying the models/ resource prefix](https://github.com/HKUDS/DeepTutor/pull/1588) | closed | yes | no | dev | codex/deeptutor-1579-gemini-models-prefix |
| 1589 | [fix: recognize referenced task model in readiness](https://github.com/HKUDS/DeepTutor/pull/1589) | closed | yes | no | dev | fix/task-reference-readiness |
| 1590 | [fix: detect MinerU models in ModelScope cache layout](https://github.com/HKUDS/DeepTutor/pull/1590) | closed | yes | no | dev | fix/mineru-modelscope-cache-readiness |
| 1591 | [fix: support Windows data volume permission checks](https://github.com/HKUDS/DeepTutor/pull/1591) | closed | yes | no | dev | fix/windows-data-volume-permissions |
| 1592 | [fix: preserve generated Partner attachments](https://github.com/HKUDS/DeepTutor/pull/1592) | closed | yes | no | dev | preserve-generated-partner-attachments |
| 1593 | [fix(partners): only start Partner authoring on an actual creation request](https://github.com/HKUDS/DeepTutor/pull/1593) | closed | yes | no | dev | fix/partner-authoring-intent-gate |
| 1597 | [fix(partners): never spend an answer on a keyword guess (#1587)](https://github.com/HKUDS/DeepTutor/pull/1597) | closed | yes | no | dev | fix/partner-authoring-honest-trigger |
| 1598 | [fix: Windows UID compatibility](https://github.com/HKUDS/DeepTutor/pull/1598) | open | no | no | dev | codex/fix-windows-uid-compatibility |
| 1599 | [fix: knowledge base listing through proxy](https://github.com/HKUDS/DeepTutor/pull/1599) | closed | yes | no | dev | codex/fix-knowledge-list-proxy |
| 1601 | [fix: request UTF-8 mode for model-authored exec code](https://github.com/HKUDS/DeepTutor/pull/1601) | closed | yes | no | dev | fix/exec-python-utf8 |
| 1602 | [fix(web): keep failed chat submissions recoverable and retryable (#1594)](https://github.com/HKUDS/DeepTutor/pull/1602) | closed | yes | no | dev | codex/fix/failed-turn-retry-1594 |
| 1605 | [fix(i18n): translate task board strings into German](https://github.com/HKUDS/DeepTutor/pull/1605) | closed | yes | no | dev | codex/fix-task-board-de-locale |
| 1606 | [fix(web): measure root redirect under chat route budget](https://github.com/HKUDS/DeepTutor/pull/1606) | closed | yes | no | dev | codex/fix-route-budget-baseline |
| 1607 | [fix(research): repoint resolve_pause user-reply helpers to the moved loop pipeline](https://github.com/HKUDS/DeepTutor/pull/1607) | closed | no | no | dev | fix/research-resolve-pause-stale-import |
| 1608 | [feat(book): complete bare LaTeX delimiters in math reading](https://github.com/HKUDS/DeepTutor/pull/1608) | open | no | no | dev | feat/latex-delimit-math-reading |
| 1609 | [fix(sessions): keep recycled chats out of history search](https://github.com/HKUDS/DeepTutor/pull/1609) | closed | yes | no | dev | fix/session-search-skip-recycled |
| 1615 | [fix: keep recycled sessions out of question bank counts](https://github.com/HKUDS/DeepTutor/pull/1615) | closed | yes | no | dev | fix/question-bank-counts-skip-recycled |
| 1616 | [fix: consolidate web search results up to the configured max_results](https://github.com/HKUDS/DeepTutor/pull/1616) | closed | yes | no | dev | fix/web-search-consolidation-max-results |
| 1618 | [feat: bulk select question bank entries in chat](https://github.com/HKUDS/DeepTutor/pull/1618) | closed | yes | no | dev | feature/chat-question-bank-bulk-select |
| 1619 | [fix(chat): preserve long-session branch path (#1614)](https://github.com/HKUDS/DeepTutor/pull/1619) | closed | yes | no | dev | codex/fix/chat-long-session-branching |
| 1620 | [feat: allow practice from the question bank](https://github.com/HKUDS/DeepTutor/pull/1620) | closed | yes | no | dev | feature/practice-from-question-bank |
| 1621 | [fix: post reading workspace "Save to notebook" to the backend route](https://github.com/HKUDS/DeepTutor/pull/1621) | closed | yes | no | dev | fix/reading-save-to-notebook-route |
| 1622 | [fix: keep BibTeX entries with accented author names](https://github.com/HKUDS/DeepTutor/pull/1622) | closed | yes | no | dev | fix/bibtex-quote-inside-braces |
| 1625 | [fix(workspace): preserve shared subagent access (#1613)](https://github.com/HKUDS/DeepTutor/pull/1625) | closed | yes | no | dev | codex/fix/workspace-subagents |
| 1626 | [fix(mastery): don't pre-search the KB with a quiz card answer](https://github.com/HKUDS/DeepTutor/pull/1626) | closed | yes | no | dev | fix/mastery-card-answer-kb-seed |
| 1627 | [fix(web): render display math whose $$ hug a multi-line formula](https://github.com/HKUDS/DeepTutor/pull/1627) | closed | yes | no | dev | fix/multiline-display-math-fences |
| 1628 | [docs(web): add v1.6.12 settings screenshots](https://github.com/HKUDS/DeepTutor/pull/1628) | closed | yes | no | dev | codex/docs/settings-screenshots-v1-6-12 |
| 1631 | [feat: add Requesty as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/1631) | closed | yes | no | dev | add-requesty-provider |
| 1632 | [fix(web-source): scope crawl seeds to their parent directory](https://github.com/HKUDS/DeepTutor/pull/1632) | closed | yes | no | dev | fix/crawler-seed-scope |
| 1633 | [fix(web-source): scope crawl seeds to their parent directory](https://github.com/HKUDS/DeepTutor/pull/1633) | closed | no | no | dev | codex/fix/crawler-sibling-scope-upstream |
| 1634 | [test(settings): persist restored subagent drafts (#1630)](https://github.com/HKUDS/DeepTutor/pull/1634) | closed | yes | no | dev | codex/test/subagent-settings-draft |
| 1635 | [feat(web-source): add bilingual source pairing (#902)](https://github.com/HKUDS/DeepTutor/pull/1635) | closed | yes | no | dev | codex/feat/bilingual-source-pairing |
| 1636 | [test(mastery): guard the review trail scroll cap (#1566)](https://github.com/HKUDS/DeepTutor/pull/1636) | closed | yes | no | dev | test/mastery-review-trail-scroll-cap |
| 1637 | [fix(reading): close a Markdown fence only on a matching bare run](https://github.com/HKUDS/DeepTutor/pull/1637) | closed | yes | no | dev | fix/markdown-outline-fence-length |
| 1638 | [fix(partners): render every fenced code block as code in Telegram HTML](https://github.com/HKUDS/DeepTutor/pull/1638) | closed | yes | no | dev | fix/telegram-fenced-code-blocks |
| 1639 | [docs(install): add one-command Docker quick start](https://github.com/HKUDS/DeepTutor/pull/1639) | closed | yes | no | dev | codex/docs-one-command-install |
| 1640 | [feat(co-writer): support model selection for edits (#661)](https://github.com/HKUDS/DeepTutor/pull/1640) | closed | yes | no | dev | codex/co-writer-model-selection |
| 1642 | [fix(agents): skip KB seeding for mastery card answers (#1624)](https://github.com/HKUDS/DeepTutor/pull/1642) | closed | no | no | dev | codex/fix/mastery-quiz-retrieval |
| 1645 | [feat(video-learning): add timestamped watching marks (#1644)](https://github.com/HKUDS/DeepTutor/pull/1645) | closed | yes | no | dev | codex/feat/video-learning-marks-upstream |
| 1649 | [feat: add kb eval command for RAG retrieval quality scoring](https://github.com/HKUDS/DeepTutor/pull/1649) | closed | yes | no | dev | feature/kb-retrieval-eval |
| 1651 | [feat(learner): expose assigned interactive books](https://github.com/HKUDS/DeepTutor/pull/1651) | closed | yes | no | dev | codex/feat/learner-assigned-books |
| 1652 | [fix(learner): expose assigned reading library (#1222)](https://github.com/HKUDS/DeepTutor/pull/1652) | closed | yes | no | dev | codex/fix/learner-reading-library |
| 1653 | [feat(web): offer reasoning effort levels for GLM models under openai binding](https://github.com/HKUDS/DeepTutor/pull/1653) | closed | yes | no | dev | feat/glm-reasoning-effort |
| 1655 | [feat(reading): add material-scoped natural read-aloud audio (#1654)](https://github.com/HKUDS/DeepTutor/pull/1655) | closed | yes | no | dev | codex/feat/reading-natural-tts |
| 1657 | [feat(reading): add server-owned quiz star rewards (#1656)](https://github.com/HKUDS/DeepTutor/pull/1657) | closed | yes | no | dev | codex/feat/reading-quiz-stars |
| 1659 | [fix(session): budget image blocks without tokenizing encoded payloads](https://github.com/HKUDS/DeepTutor/pull/1659) | closed | yes | no | dev | fix/image-context-budget |
| 1660 | [fix(rag): resolve numbered exercises from completed parse artifacts](https://github.com/HKUDS/DeepTutor/pull/1660) | closed | yes | no | dev | fix/numbered-exercise-lookup |
| 1661 | [feat: add Polish localization](https://github.com/HKUDS/DeepTutor/pull/1661) | closed | yes | no | dev | feat/polish-language |
| 1662 | [fix(learner): allow own-scope settings and workspace writes via route templates](https://github.com/HKUDS/DeepTutor/pull/1662) | closed | yes | no | dev | fix/learner-workspace-surface |
| 1663 | [fix(learning): mint quiz submission ids via randomUuid on plain HTTP](https://github.com/HKUDS/DeepTutor/pull/1663) | closed | yes | no | dev | fix/http-random-uuid |
| 1664 | [feat(parsing): select an independent image description model](https://github.com/HKUDS/DeepTutor/pull/1664) | closed | yes | no | dev | feat/image-description-model |
| 1665 | [perf(parsing): cache image descriptions per workspace](https://github.com/HKUDS/DeepTutor/pull/1665) | closed | yes | no | dev | perf/image-description-cache |
| 1666 | [fix(chat): label sent-message knowledge-base references with catalog names](https://github.com/HKUDS/DeepTutor/pull/1666) | closed | yes | no | dev | fix/chat-kb-ref-labels |
| 1668 | [fix(web): keep submits alive across the full reconnect ladder (#1648)](https://github.com/HKUDS/DeepTutor/pull/1668) | closed | yes | no | dev | fix/ask-user-submit-retry-budget |
| 1669 | [fix(parsing): add opt-in normalization for tiny scanned PDF pages](https://github.com/HKUDS/DeepTutor/pull/1669) | closed | yes | no | dev | fix/mineru-tiny-scan-normalization |
| 1670 | [Fix/mineru local failure reasons](https://github.com/HKUDS/DeepTutor/pull/1670) | closed | yes | no | dev | fix/mineru-local-failure-reasons |
| 1671 | [perf(rag): add opt-in bounded image-description batches](https://github.com/HKUDS/DeepTutor/pull/1671) | closed | yes | no | dev | perf/image-description-batching |
| 1672 | [fix(parsing): restore source pages and resume MinerU slices (follow-up to #1569)](https://github.com/HKUDS/DeepTutor/pull/1672) | closed | yes | no | dev | fix/mineru-segment-recovery |
| 1674 | [feat: add API Route as an LLM gateway provider](https://github.com/HKUDS/DeepTutor/pull/1674) | closed | yes | no | dev | feat/api-route-provider |
| 1675 | [fix(usage): exclude encoded image payloads from token estimates](https://github.com/HKUDS/DeepTutor/pull/1675) | closed | yes | no | dev | fix/multimodal-usage-estimate |
| 1677 | [fix(partners): keep IM replies in step with the turn](https://github.com/HKUDS/DeepTutor/pull/1677) | closed | yes | no | dev | main |
| 1679 | [fix: support Xiaomi MiMo v2.5 preset speech](https://github.com/HKUDS/DeepTutor/pull/1679) | closed | yes | no | dev | fix/mimo-v25-tts |
| 1680 | [feat: add synchronized speech narration to Math Animator](https://github.com/HKUDS/DeepTutor/pull/1680) | open | no | no | dev | codex/math-animator-narration |
| 1681 | [feat: add native MiniMax speech synthesis](https://github.com/HKUDS/DeepTutor/pull/1681) | closed | yes | no | dev | octo/20261001-tts-tool-recvwLi0fA8hap |
| 1682 | [fix(session): ground rendered LaTeX selections (#1676)](https://github.com/HKUDS/DeepTutor/pull/1682) | closed | yes | no | dev | codex/fix/tutor-latex-selection |
| 1683 | [fix(history): search full conversation transcripts (#1678)](https://github.com/HKUDS/DeepTutor/pull/1683) | closed | yes | no | dev | codex/fix/chat-history-search |
| 1684 | [feat: add FutureInfra as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/1684) | closed | yes | no | dev | add-futureinfra-provider |
| 1685 | [fix(session): stop waiting turns before deletion (#1646)](https://github.com/HKUDS/DeepTutor/pull/1685) | closed | yes | no | dev | codex/fix/mastery-session-lock |
| 1686 | [fix(reading): preserve EPUB outline anchors (#1673)](https://github.com/HKUDS/DeepTutor/pull/1686) | closed | yes | no | dev | codex/fix/epub-toc-anchors |
| 1687 | [feat(partners): add Telegram per-chat response policies (#1667)](https://github.com/HKUDS/DeepTutor/pull/1687) | closed | yes | no | dev | codex/feat/telegram-chat-policies |
| 1688 | [fix(reading): preserve PDF reading position across resizes](https://github.com/HKUDS/DeepTutor/pull/1688) | closed | yes | no | dev | fix/pdf-resize-reading-position |
| 1690 | [fix: handle process probe decoding failures and false-positive LLM retries](https://github.com/HKUDS/DeepTutor/pull/1690) | closed | yes | no | dev | codex/fix-runtime-log-errors |
| 1692 | [fix(mastery): shuffle choice options so the correct answer moves (#1691)](https://github.com/HKUDS/DeepTutor/pull/1692) | closed | yes | no | dev | fix/mastery-quiz-answer-shuffle |
| 1693 | [fix(partners): keep engine-injected paths out of IM tool hints](https://github.com/HKUDS/DeepTutor/pull/1693) | open | no | no | dev | fix/tool-hint-sanitize |
| 1694 | [fix(cli): respect configured token budget in doctor probe](https://github.com/HKUDS/DeepTutor/pull/1694) | closed | yes | no | dev | codex/fix-doctor-probe-budget |
| 1695 | [fix(rag): retain source figures beyond the 64-asset document cap (#1610)](https://github.com/HKUDS/DeepTutor/pull/1695) | open | no | no | dev | codex/fix-visual-retention |
| 1697 | [fix(web): normalize Windows path separators in contract node tests (#1696)](https://github.com/HKUDS/DeepTutor/pull/1697) | closed | no | no | dev | fix/1696-windows-test-paths |
| 1698 | [fix(web): normalize path separators in architecture and route contract tests (#1696)](https://github.com/HKUDS/DeepTutor/pull/1698) | open | no | no | dev | codex/fix-1696-windows-test-paths |
| 1699 | [test(codebuddy): make credential fixture expiry relative to now](https://github.com/HKUDS/DeepTutor/pull/1699) | open | no | no | dev | fix/codebuddy-credentials-fixture-expiry |
| 1700 | [fix(co-writer): keep a placeholder row and warn when DOCX table row parsing fails](https://github.com/HKUDS/DeepTutor/pull/1700) | closed | yes | no | dev | pr/docx-table-row-placeholder |
| 1701 | [fix(web): surface quiz follow-up session-id writeback failures](https://github.com/HKUDS/DeepTutor/pull/1701) | closed | yes | no | dev | pr/quiz-followup-writeback |
| 1702 | [fix(rag): classify invalid persisted index errors and include re-index steps](https://github.com/HKUDS/DeepTutor/pull/1702) | closed | yes | no | dev | pr/rag-invalid-index-classification |
| 1703 | [fix(rag): log swallowed embedding/image progress and LightRAG meta failures](https://github.com/HKUDS/DeepTutor/pull/1703) | closed | yes | no | dev | pr/rag-log-swallowed-progress-failures |
| 1704 | [fix(runtime): log swallowed launcher, init and update-worker failures](https://github.com/HKUDS/DeepTutor/pull/1704) | closed | yes | no | dev | pr/runtime-log-swallowed-failures |
| 1705 | [fix(chat): keep unsent drafts safe when restore fails](https://github.com/HKUDS/DeepTutor/pull/1705) | closed | yes | no | dev | pr/chat-draft-restore-guard-v3 |
| 1706 | [fix(knowledge): surface swallowed KB status, progress and folder-sync failures](https://github.com/HKUDS/DeepTutor/pull/1706) | closed | yes | no | dev | pr/knowledge-surface-swallowed-failures-v2 |
| 1707 | [fix: log silently swallowed failures in five services](https://github.com/HKUDS/DeepTutor/pull/1707) | closed | yes | no | dev | pr/services-log-swallowed-failures |
| 1708 | [fix(workspace): surface unreadable migration journals and skipped corrupt sources](https://github.com/HKUDS/DeepTutor/pull/1708) | closed | yes | no | dev | pr/workspace-migration-corrupt-sources |
| 1709 | [test(api): add contract tests for upload guards, quiz judge, reading progress, notebook and memory routers](https://github.com/HKUDS/DeepTutor/pull/1709) | closed | yes | no | dev | pr/test-api-router-contracts |
| 1710 | [test(web): cover the settings store and memory-graph helpers](https://github.com/HKUDS/DeepTutor/pull/1710) | closed | yes | no | dev | pr/test-web-settings-memory-graph |
| 1712 | [fix(llm): avoid tokenizing image payloads in request fingerprints](https://github.com/HKUDS/DeepTutor/pull/1712) | closed | yes | no | dev | fix/image-cache-fingerprints-20261004 |
| 1713 | [perf(mastery): seed fresh status before the first model call](https://github.com/HKUDS/DeepTutor/pull/1713) | closed | yes | no | dev | perf/mastery-status-snapshot-20261004 |
| 1714 | [perf(llm): deduplicate repeated inline user images per request](https://github.com/HKUDS/DeepTutor/pull/1714) | closed | yes | no | dev | perf/deduplicate-inline-images-20261004 |
| 1715 | [fix(runtime): surface launcher termination and port-kill signal failures](https://github.com/HKUDS/DeepTutor/pull/1715) | closed | yes | no | dev | codex/fix/launcher-terminate-visibility-v3 |
| 1716 | [docs(tools): add tools surface guide](https://github.com/HKUDS/DeepTutor/pull/1716) | closed | yes | no | dev | guide/tools-20261004-v2 |
| 1717 | [docs(events): add event and progress chain guide](https://github.com/HKUDS/DeepTutor/pull/1717) | closed | yes | no | dev | guide/events-20261004-v2 |
| 1718 | [test(book): cover engine stage transitions](https://github.com/HKUDS/DeepTutor/pull/1718) | closed | yes | no | dev | agent/book-engine-stage-tests-pr |
| 1719 | [test(storage): lock file library disk-deletion failure paths](https://github.com/HKUDS/DeepTutor/pull/1719) | closed | yes | no | dev | agent/dt22-file-library-deletion-tests-v2 |
| 1720 | [fix(migration): scope unreadable-journal rejection to migration paths](https://github.com/HKUDS/DeepTutor/pull/1720) | closed | no | no | main | agent/dt22-fix-corrupted-oplog-v2 |
| 1721 | [fix(migration): scope unreadable-journal rejection to migration paths](https://github.com/HKUDS/DeepTutor/pull/1721) | closed | no | no | main | agent/dt22-fix-corrupted-oplog-v2-pr |
| 1722 | [docs(chat): code-reading guide for the chat/agent runtime](https://github.com/HKUDS/DeepTutor/pull/1722) | closed | no | no | main | docs/guides/chat-runtime |
| 1723 | [feat(chat): keep branch navigator visible on forked messages (#1410)](https://github.com/HKUDS/DeepTutor/pull/1723) | closed | yes | no | dev | feat/chat-branch-navigator-visible-pr |
| 1724 | [feat(cron): allow disabling the scheduler and configuring its idle re-check interval (#451)](https://github.com/HKUDS/DeepTutor/pull/1724) | closed | no | no | main | feat/cron-scheduler-settings-up451 |
| 1725 | [test(chat): reset draft mocks between restore-failure specs](https://github.com/HKUDS/DeepTutor/pull/1725) | closed | no | no | main | fix/chat-draft-restore-guard-v2 |
| 1726 | [fix(partners): restore Feishu card text, media download type and mention names](https://github.com/HKUDS/DeepTutor/pull/1726) | closed | no | no | main | fix/feishu-parsing-defects |
| 1727 | [fix(knowledge): make update_kb_status write failures observable](https://github.com/HKUDS/DeepTutor/pull/1727) | closed | no | no | main | fix/knowledge-surface-swallowed-failures |
| 1728 | [fix(launcher): log handoff failure when mark_failed fails too](https://github.com/HKUDS/DeepTutor/pull/1728) | closed | no | no | main | fix/launcher-handoff-mark-failed-pr |
| 1729 | [fix: surface quiz followup session-id writeback failures](https://github.com/HKUDS/DeepTutor/pull/1729) | closed | no | no | main | fix/quiz-followup-writeback-pr |
| 1730 | [fix(sandbox): drop pass_fds from the rlimit report pipe and guard it with try/finally](https://github.com/HKUDS/DeepTutor/pull/1730) | closed | no | no | main | fix/sandbox-rlimit-degraded-v2 |
| 1731 | [fix(api): warn when a deferred tool's definition fails to load](https://github.com/HKUDS/DeepTutor/pull/1731) | closed | yes | no | dev | fix/tool-options-definition-warning-274-v2 |
| 1732 | [test: pin TZ in runtime_context date assertions for cross-timezone stability](https://github.com/HKUDS/DeepTutor/pull/1732) | closed | no | no | main | fix/tz-stable-runtime-context-tests |
| 1733 | [test: freeze naive FIXED_NOW for cross-platform TZ stability](https://github.com/HKUDS/DeepTutor/pull/1733) | closed | yes | no | dev | fix/tz-stable-runtime-context-tests-v2 |
| 1734 | [fix(reading): converge the mobile header and dock the selection panel](https://github.com/HKUDS/DeepTutor/pull/1734) | closed | yes | no | dev | fix/up-916-mobile-nav-dictionary |
| 1735 | [docs: add agents orchestration reading guide](https://github.com/HKUDS/DeepTutor/pull/1735) | closed | no | no | main | guide/agents-20261004 |
| 1736 | [fix(co-writer): use English placeholder and sort test imports for CI](https://github.com/HKUDS/DeepTutor/pull/1736) | closed | no | no | main | fix/docx-table-row-warning-162-v2-pr |
| 1737 | [fix(knowledge): log folder sync state recording failures](https://github.com/HKUDS/DeepTutor/pull/1737) | closed | no | no | main | pr/knowledge-surface-swallowed-failures |
| 1738 | [test(reading): cover the bilingual EPUB pairing pipeline edge cases](https://github.com/HKUDS/DeepTutor/pull/1738) | closed | yes | no | dev | test/epub-bilingual-unit-20261004 |
| 1739 | [test(api): cover learning-records account isolation and read boundaries](https://github.com/HKUDS/DeepTutor/pull/1739) | closed | yes | no | dev | test/learning-records-access-20261004 |
| 1740 | [test(plugins): pin entry-point loader contract across load, isolation, duplicate and gating paths](https://github.com/HKUDS/DeepTutor/pull/1740) | closed | yes | no | dev | test/plugins-entrypoint-loader-20261004 |
| 1741 | [test(question): pin mimic websocket error-path and stdout interceptor failure contracts](https://github.com/HKUDS/DeepTutor/pull/1741) | closed | yes | no | dev | test/question-mimic-ws-error-paths-20261004 |
| 1742 | [test(reading): pin progress API durability contract](https://github.com/HKUDS/DeepTutor/pull/1742) | closed | no | no | main | test/reading-progress-api-contract |
| 1743 | [chore: remove internal audit evidence from PR branch](https://github.com/HKUDS/DeepTutor/pull/1743) | open | no | no | dev | test/research-pipeline-stage-contract-pr |
| 1744 | [test(web): smoke coverage for StandaloneComposer send gating](https://github.com/HKUDS/DeepTutor/pull/1744) | closed | yes | no | dev | test/standalone-composer-smoke-20261004 |
| 1745 | [test(settings): cover CLI-app model persistence end to end (#1630)](https://github.com/HKUDS/DeepTutor/pull/1745) | closed | yes | no | dev | test/subagent-settings-apply-1630 |
| 1746 | [fix(partners): stop telegram typing loop for denied senders and dropped media-group stragglers](https://github.com/HKUDS/DeepTutor/pull/1746) | closed | yes | no | dev | test/telegram-message-parsing-20261003-v2 |
| 1747 | [test: add tex_downloader/tex_chunker toolchain tests](https://github.com/HKUDS/DeepTutor/pull/1747) | closed | no | no | main | test/tex-tools-20261004 |
| 1748 | [test: add tex_downloader/tex_chunker toolchain tests](https://github.com/HKUDS/DeepTutor/pull/1748) | closed | yes | no | dev | test/tex-tools-20261004-v2 |
| 1749 | [test(web): cover VisualizationViewer render branches (mermaid/svg/chartjs/html/plugin/manim)](https://github.com/HKUDS/DeepTutor/pull/1749) | closed | yes | no | dev | test/visualization-viewer-20261004 |
| 1750 | [style: apply ruff format to spine_synthesizer tests](https://github.com/HKUDS/DeepTutor/pull/1750) | closed | yes | no | dev | tests/spine-synthesizer-20261003-pr |
| 1751 | [fix(services): surface fsync failures in atomic writers as rate-limited warnings](https://github.com/HKUDS/DeepTutor/pull/1751) | closed | yes | no | dev | myfork/fix/atomic-write-fsync-warning |
| 1752 | [fix(llm): warn when CodeBuddy tool-call interrupt or drain fails](https://github.com/HKUDS/DeepTutor/pull/1752) | closed | no | no | main | myfork/fix/codebuddy-interrupt-warning-164 |
| 1753 | [fix(llm): warn when CodeBuddy tool-call interrupt or drain fails](https://github.com/HKUDS/DeepTutor/pull/1753) | closed | no | no | main | myfork/fix/codebuddy-interrupt-warning-164-pr |
| 1754 | [fix(courses): surface course deletion failure instead of silent redirect](https://github.com/HKUDS/DeepTutor/pull/1754) | closed | yes | no | dev | myfork/fix/course-delete-visible-error |
| 1755 | [fix(co-writer): warn and keep placeholder row when DOCX table row parsing fails](https://github.com/HKUDS/DeepTutor/pull/1755) | closed | no | no | main | myfork/fix/docx-table-row-warning-162 |
| 1756 | [fix(co-writer): use English placeholder and sort test imports for CI](https://github.com/HKUDS/DeepTutor/pull/1756) | closed | no | no | main | myfork/fix/docx-table-row-warning-162-v2 |
| 1757 | [fix(embedding): log progress callback failures instead of swallowing them](https://github.com/HKUDS/DeepTutor/pull/1757) | closed | no | no | main | myfork/fix/embed-progress-callback-logging-pr |
| 1758 | [fix: log image progress callback failures instead of swallowing them](https://github.com/HKUDS/DeepTutor/pull/1758) | closed | no | no | main | myfork/fix/image-progress-callback-pr |
| 1759 | [fix(lightrag): warn when workspace meta.json exists but is unusable](https://github.com/HKUDS/DeepTutor/pull/1759) | closed | no | no | main | myfork/fix/lightrag-meta-warning-20261003 |
| 1760 | [fix(lightrag): warn when workspace meta.json exists but is unusable](https://github.com/HKUDS/DeepTutor/pull/1760) | closed | no | no | main | myfork/fix/lightrag-meta-warning-20261003-pr |
| 1761 | [fix(workspace): surface skipped corrupt sources in migration dependency closure](https://github.com/HKUDS/DeepTutor/pull/1761) | closed | no | no | main | myfork/fix/migration-deps-skip-warnings-158 |
| 1762 | [fix(workspace): surface skipped corrupt sources in migration dependency closure](https://github.com/HKUDS/DeepTutor/pull/1762) | closed | no | no | main | myfork/fix/migration-deps-skip-warnings-158-pr |
| 1763 | [test(partners): lock outbound dispatch timeout semantics](https://github.com/HKUDS/DeepTutor/pull/1763) | closed | yes | no | dev | myfork/fix/partner-outbound-timeout-visibility |
| 1764 | [fix(memory): log corrupt snapshot files instead of skipping silently](https://github.com/HKUDS/DeepTutor/pull/1764) | closed | no | no | main | myfork/fix/snapshot-skip-warn-log-161 |
| 1765 | [fix(memory): log corrupt snapshot files instead of skipping silently](https://github.com/HKUDS/DeepTutor/pull/1765) | closed | no | no | main | myfork/fix/snapshot-skip-warn-log-161-pr |
| 1766 | [fix(api): warn when a deferred tool's definition fails to load](https://github.com/HKUDS/DeepTutor/pull/1766) | closed | no | no | main | myfork/fix/tool-options-definition-warning-274 |
| 1767 | [test(web): smoke ChatWorkspace empty home, streaming turn, failure banner](https://github.com/HKUDS/DeepTutor/pull/1767) | closed | yes | no | dev | myfork/test/chat-workspace-smoke-20261003-pr |
| 1768 | [test(co-writer): lock router contract for CRUD, 4xx payloads, export failures](https://github.com/HKUDS/DeepTutor/pull/1768) | closed | yes | no | dev | myfork/test/co-writer-contract-20261003 |
| 1769 | [test(launcher): cover lifecycle termination, port cleanup and marker corruption paths](https://github.com/HKUDS/DeepTutor/pull/1769) | closed | yes | no | dev | myfork/test/launcher-lifecycle-20261003 |
| 1770 | [test(web): cover memory-graph pure functions (parseDoc/splitRef/buildGraph)](https://github.com/HKUDS/DeepTutor/pull/1770) | closed | no | no | main | myfork/test/memory-graph-20261003-pr |
| 1771 | [test: memory workbench router contract coverage (GET shapes, edit/delete round-trips, 4xx)](https://github.com/HKUDS/DeepTutor/pull/1771) | closed | no | no | main | myfork/test/memory-router-contract-20261003 |
| 1772 | [style: ruff format memory router contract tests](https://github.com/HKUDS/DeepTutor/pull/1772) | closed | no | no | main | myfork/test/memory-router-contract-20261003-pr |
| 1773 | [test(session): cover pocketbase_store failure branches and pagination edges](https://github.com/HKUDS/DeepTutor/pull/1773) | closed | yes | no | dev | myfork/test/pocketbase-store-fallbacks-20261003-pr |
| 1774 | [test: unit-cover the quiz-judge WebSocket router](https://github.com/HKUDS/DeepTutor/pull/1774) | closed | no | no | main | myfork/test/quiz-judge-unit-20261003-pr |
| 1775 | [test(quiz): add QuizViewer smoke and grading interaction coverage](https://github.com/HKUDS/DeepTutor/pull/1775) | closed | yes | no | dev | myfork/test/quiz-viewer-smoke-20261003 |
| 1776 | [test(partners): telegram message parsing, chunking and typing contract suite](https://github.com/HKUDS/DeepTutor/pull/1776) | closed | no | no | main | myfork/test/telegram-message-parsing-20261003 |
| 1777 | [docs(evidence): i18n system reading guide (backend i18n, prompt/status YAML, web localization)](https://github.com/HKUDS/DeepTutor/pull/1777) | closed | no | no | main | guide/i18n-20261004 |
| 1778 | [fix(web): sanitize quoted html tag attributes and preserve bold whitespace](https://github.com/HKUDS/DeepTutor/pull/1778) | closed | no | no | main | test/markdown-display-security-v2-pr |
| 1780 | [fix: decode escaped emoji in ask_user cards as real characters](https://github.com/HKUDS/DeepTutor/pull/1780) | closed | yes | no | dev | fix/join-escaped-surrogate-pairs |
| 1783 | [fix: embedding concurrency, local Lemonade, reading fences, and learner nav](https://github.com/HKUDS/DeepTutor/pull/1783) | closed | yes | no | dev | fix/embedding-reading-learning |
| 1785 | [Expose built-in mastery tutor tools over HTTP](https://github.com/HKUDS/DeepTutor/pull/1785) | open | no | no | dev | codex/expose-mastery-tutor-tools |
| 1786 | [feat: add Opper as an LLM and embedding provider](https://github.com/HKUDS/DeepTutor/pull/1786) | closed | yes | no | dev | feat/opper-provider |
| 1787 | [fix(crawler): ignore absurd robots.txt crawl-delay values](https://github.com/HKUDS/DeepTutor/pull/1787) | closed | yes | no | dev | fix/robots-crawl-delay-cap |
| 1789 | [fix(chat): keep parked ask_user turns alive across deletion and reload](https://github.com/HKUDS/DeepTutor/pull/1789) | closed | yes | no | dev | fix/parked-turn-delete-and-restore |
| 1790 | [fix(mastery-path): allow editing legacy objective counts](https://github.com/HKUDS/DeepTutor/pull/1790) | closed | yes | no | dev | fix/mastery-path-legacy-objectives |
| 1791 | [feat(providers): add Y-API as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/1791) | closed | yes | no | dev | feat/y-api-provider |
| 1794 | [fix(learning): prevent compounding SRS lapses during multi-turn qualitative repairs (#1781)](https://github.com/HKUDS/DeepTutor/pull/1794) | closed | yes | no | dev | codex/fix-1781-qualitative-repair-lapses |
| 1797 | [fix: embedding local keyless, qwen3-Instruct thinking, embedding concurrency](https://github.com/HKUDS/DeepTutor/pull/1797) | closed | yes | no | dev | fix/three-bugs-embedding-qwen3-lock |
| 1798 | [fix(settings): prevent phantom unsaved changes when configuring MinerU cloud API](https://github.com/HKUDS/DeepTutor/pull/1798) | closed | yes | no | dev | fix/mineru-cloud-settings-dirty-state |
| 1800 | [fix(memory): aggregate account-level L1 across workspaces (#1799)](https://github.com/HKUDS/DeepTutor/pull/1800) | closed | yes | no | dev | fix/memory-l1-account-workspace-aggregation |
| 1801 | [fix(rag): surface the hybrid to vector-only retrieval degradation (#1792)](https://github.com/HKUDS/DeepTutor/pull/1801) | closed | yes | no | dev | fix/hybrid-profile-availability-signal |
| 1803 | [fix(knowledge): resolve workspace-scoped knowledge base files during deletion](https://github.com/HKUDS/DeepTutor/pull/1803) | closed | yes | no | dev | fix/workspace-kb-file-delete-not-found |
| 1804 | [fix(rag): shard the visual-asset manifest so KBs scale past 16 MB (#1802)](https://github.com/HKUDS/DeepTutor/pull/1804) | open | no | no | dev | fix/visual-manifest-scale |
| 1805 | [test(learning): cover persisted qualitative repair turns](https://github.com/HKUDS/DeepTutor/pull/1805) | closed | yes | no | dev | fix/qualitative-repair-persistence |
| 1806 | [Codex/tauri desktop phase 0](https://github.com/HKUDS/DeepTutor/pull/1806) | closed | no | no | main | codex/tauri-desktop-phase-0 |
| 1808 | [fix(sdk): serialize slotted capability availability](https://github.com/HKUDS/DeepTutor/pull/1808) | closed | yes | no | dev | fix/sdk-capability-contracts |
| 1810 | [fix(web): accept CRLF generated contracts without masking drift](https://github.com/HKUDS/DeepTutor/pull/1810) | closed | no | no | dev | fix/contract-check-newlines |
| 1812 | [fix(api): preserve Co-Writer model-selection HTTP errors](https://github.com/HKUDS/DeepTutor/pull/1812) | closed | yes | no | dev | fix/co-writer-http-errors |
| 1814 | [fix(api): materialize saved quiz answer attachments](https://github.com/HKUDS/DeepTutor/pull/1814) | closed | yes | no | dev | fix/quiz-judge-attachments |
| 1816 | [fix(learning): preserve submission order for timestamp ties](https://github.com/HKUDS/DeepTutor/pull/1816) | closed | no | no | dev | fix/assessment-time-ties |
| 1818 | [fix(settings): normalize Windows lock path aliases](https://github.com/HKUDS/DeepTutor/pull/1818) | closed | yes | no | dev | fix/settings-lock-path |
| 1820 | [fix(learning): keep aggregate reads in one SQLite snapshot](https://github.com/HKUDS/DeepTutor/pull/1820) | closed | yes | no | dev | fix/learning-read-snapshots |
| 1822 | [fix(storage): close short-lived SQLite connections deterministically](https://github.com/HKUDS/DeepTutor/pull/1822) | closed | yes | no | dev | fix/cron-connection-lifetime |
| 1824 | [fix(config): preserve catalogs after filesystem read failures](https://github.com/HKUDS/DeepTutor/pull/1824) | closed | yes | no | dev | fix/catalog-read-errors |
| 1826 | [fix(cache): isolate shared producers from waiter cancellation](https://github.com/HKUDS/DeepTutor/pull/1826) | closed | no | no | dev | fix/singleflight-cancellation |
| 1828 | [fix(llm): reload CodeBuddy credentials after SDK authentication errors](https://github.com/HKUDS/DeepTutor/pull/1828) | closed | yes | no | dev | fix/codebuddy-authentication-errors |
| 1830 | [fix(session): release admission leases after preference failures](https://github.com/HKUDS/DeepTutor/pull/1830) | closed | yes | no | dev | fix/turn-admission-lease |
| 1832 | [fix(session): keep shutdown closed after managed-update recovery](https://github.com/HKUDS/DeepTutor/pull/1832) | closed | no | no | dev | fix/turn-runtime-close |
| 1834 | [fix(session): preserve opaque PocketBase message cursors](https://github.com/HKUDS/DeepTutor/pull/1834) | closed | yes | no | dev | fix/pocketbase-message-cursors |
| 1836 | [fix(skills): restore installed skills after replacement failure](https://github.com/HKUDS/DeepTutor/pull/1836) | closed | yes | no | dev | fix/skill-install-rollback |
| 1838 | [fix(memory): finalize runs cancelled before execution](https://github.com/HKUDS/DeepTutor/pull/1838) | closed | no | no | dev | fix/memory-run-cancellation |
| 1840 | [fix(memory): anchor audit edits to the original document view](https://github.com/HKUDS/DeepTutor/pull/1840) | closed | yes | no | dev | fix/memory-audit-line-identity |
| 1842 | [fix(subagent): read oversized JSONL frames without truncation](https://github.com/HKUDS/DeepTutor/pull/1842) | closed | yes | no | dev | fix/subagent-stream-lines |
| 1844 | [fix(subagent): reap cancelled CLI probe processes](https://github.com/HKUDS/DeepTutor/pull/1844) | closed | no | no | dev | fix/subagent-probe-cleanup |
| 1846 | [fix(partners): cancel live web turns when stopping a partner](https://github.com/HKUDS/DeepTutor/pull/1846) | closed | yes | no | dev | fix/partner-turn-stop |
| 1848 | [fix(partners): preserve customized legacy persona text](https://github.com/HKUDS/DeepTutor/pull/1848) | closed | yes | no | dev | fix/custom-soul-preservation |
| 1850 | [fix(rag): report native retrieval errors in evaluation](https://github.com/HKUDS/DeepTutor/pull/1850) | closed | yes | no | dev | fix/evaluation-search-errors |
| 1852 | [fix(channels): propagate failed message deliveries to retry](https://github.com/HKUDS/DeepTutor/pull/1852) | closed | yes | no | dev | fix/dingtalk-delivery-retry |
| 1854 | [fix(obsidian): resolve backlinks using canonical note paths](https://github.com/HKUDS/DeepTutor/pull/1854) | closed | yes | no | dev | fix/obsidian-backlink-paths |
| 1856 | [fix(book): detect drift when a knowledge source becomes empty](https://github.com/HKUDS/DeepTutor/pull/1856) | closed | yes | no | dev | fix/book-empty-source-drift |
| 1858 | [fix(knowledge): confirm before deleting MarginNote state](https://github.com/HKUDS/DeepTutor/pull/1858) | closed | yes | no | dev | fix/marginnote-delete-confirmation |
| 1860 | [fix(video): preserve learning updates during playback discovery](https://github.com/HKUDS/DeepTutor/pull/1860) | closed | yes | no | dev | fix/video-playback-learning-state |
| 1862 | [fix(web): keep note editing usable when browser storage is denied](https://github.com/HKUDS/DeepTutor/pull/1862) | closed | yes | no | dev | fix/markdown-note-storage-access |
| 1864 | [fix(reading): reject unsafe citation range integers](https://github.com/HKUDS/DeepTutor/pull/1864) | closed | no | no | dev | fix/reading-citation-range-bounds |
| 1866 | [fix(reading): restore failed annotation deletions within their scope](https://github.com/HKUDS/DeepTutor/pull/1866) | closed | yes | no | dev | fix/reading-annotation-rollback |
| 1868 | [fix(web): preserve literal thinking tags inside Markdown fences](https://github.com/HKUDS/DeepTutor/pull/1868) | closed | yes | no | dev | fix/thinking-code-fences |
| 1870 | [fix(web): group sessions by local calendar days across DST](https://github.com/HKUDS/DeepTutor/pull/1870) | closed | yes | no | dev | fix/session-calendar-groups |
| 1872 | [fix(web): distinguish inherited and empty MCP selections](https://github.com/HKUDS/DeepTutor/pull/1872) | closed | yes | no | dev | fix/composer-empty-mcp-scope |
| 1874 | [fix(web): preserve settings refresh across streaming updates](https://github.com/HKUDS/DeepTutor/pull/1874) | closed | yes | no | dev | fix/setup-sync-stream-updates |
| 1876 | [fix(web): retry Mermaid rendering after an initial error](https://github.com/HKUDS/DeepTutor/pull/1876) | closed | yes | no | dev | fix/mermaid-error-recovery |
| 1878 | [fix(web): pause retained activity orbs after work settles](https://github.com/HKUDS/DeepTutor/pull/1878) | closed | no | no | dev | fix/settled-mark-animation |
| 1880 | [fix(web): start handoff exchange after strict-mode timer replay](https://github.com/HKUDS/DeepTutor/pull/1880) | closed | yes | no | dev | fix/handoff-effect-replay |
| 1882 | [fix(web): apply composer admission checks to Enter submissions](https://github.com/HKUDS/DeepTutor/pull/1882) | closed | yes | no | dev | fix/composer-keyboard-admission |
| 1884 | [fix(web): preserve legacy drafts when storage migration fails](https://github.com/HKUDS/DeepTutor/pull/1884) | closed | yes | no | dev | fix/co-writer-draft-migration |
| 1886 | [fix(web): isolate Co-Writer editing state by document identity](https://github.com/HKUDS/DeepTutor/pull/1886) | closed | no | no | dev | fix/co-writer-document-isolation |
| 1888 | [fix(web): stop reading workspace polling after effect cleanup](https://github.com/HKUDS/DeepTutor/pull/1888) | closed | no | no | dev | fix/reading-poll-lifetime |
| 1890 | [fix(web): clear notebook save state after cancellation](https://github.com/HKUDS/DeepTutor/pull/1890) | closed | yes | no | dev | fix/notebook-save-cancellation |
| 1892 | [fix(web): retain memory edits after failed HTTP saves](https://github.com/HKUDS/DeepTutor/pull/1892) | closed | yes | no | dev | fix/memory-save-http-errors |
| 1894 | [fix(web): preserve channel onboarding polling intervals](https://github.com/HKUDS/DeepTutor/pull/1894) | closed | no | no | dev | fix/channel-onboarding-poll-cadence |
| 1896 | [fix(web): block persona saves after a failed initial read](https://github.com/HKUDS/DeepTutor/pull/1896) | closed | yes | no | dev | fix/partner-soul-load-errors |
| 1897 | [feat(search): send X-Pplx-Integration header to Perplexity](https://github.com/HKUDS/DeepTutor/pull/1897) | closed | yes | no | dev | feat/perplexity-integration-header |
| 1898 | [fix(reading): unwrap backticked locator citations and split multi-locator links](https://github.com/HKUDS/DeepTutor/pull/1898) | closed | yes | no | dev | fix/reading-locator-citations-backtick-split |
| 1899 | [fix(chat): keep knowledge base resource option accessible when empty](https://github.com/HKUDS/DeepTutor/pull/1899) | closed | yes | no | dev | fix/chat-composer-empty-kb-option |
| 1900 | [feat(learning): add Guided practice to rebuild a worked solution](https://github.com/HKUDS/DeepTutor/pull/1900) | open | no | yes | dev | feat/solution-steps |
| 1904 | [course media syllabus](https://github.com/HKUDS/DeepTutor/pull/1904) | closed | no | no | main | codex/course-media-syllabus |
| 1906 | [fix(web): add visible return from activity panel](https://github.com/HKUDS/DeepTutor/pull/1906) | closed | yes | no | dev | fix/activity-panel-return |
| 1910 | [fix(session): budget projected image replay before compaction](https://github.com/HKUDS/DeepTutor/pull/1910) | closed | yes | no | dev | codex/fix-1909-image-compaction |
| 1911 | [feat(providers): add onomeo as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/1911) | closed | yes | no | dev | feat/add-onomeo-provider |
| 1917 | [feat(rag): add pluggable query rewrite layer for retrieval quality](https://github.com/HKUDS/DeepTutor/pull/1917) | closed | yes | no | dev | feature/rag-query-rewrite |
| 1919 | [fix: retry transient locks and decode UTF-8 when reading the indexing journal](https://github.com/HKUDS/DeepTutor/pull/1919) | closed | yes | no | dev | fix/indexing-journal-read-retry |
| 1921 | [fix(reading): accept video playback time in the reading viewport](https://github.com/HKUDS/DeepTutor/pull/1921) | closed | yes | no | dev | fix/reading-viewport-time-seconds |
| 1922 | [fix(reading): send the action the reading composer displays](https://github.com/HKUDS/DeepTutor/pull/1922) | closed | yes | no | dev | fix/reading-composer-hidden-capability |
| 1924 | [fix(agent-loop): keep content parts when appending a loop directive](https://github.com/HKUDS/DeepTutor/pull/1924) | closed | yes | no | dev | fix/agent-loop-preserve-multimodal-instruction |
| 1930 | [test(app): lock lost-ack resend session parity behind regression tests](https://github.com/HKUDS/DeepTutor/pull/1930) | closed | yes | no | dev | test/lost-ack-resend-session-parity-20261012 |
| 1931 | [fix(rag): align tool selector contract with execution (#1928)](https://github.com/HKUDS/DeepTutor/pull/1931) | closed | yes | no | dev | fix/rag-selector-contract-1928 |
| 1932 | [fix(mastery): revise multiple outline modules atomically (#1929)](https://github.com/HKUDS/DeepTutor/pull/1932) | closed | yes | no | dev | fix/mastery-outline-atomic-revision-1929 |
| 1934 | [fix(mastery): keep teaching visible across interleaved tool work](https://github.com/HKUDS/DeepTutor/pull/1934) | closed | yes | no | dev | contrib/mastery-visible-teaching |
| 1935 | [fix(chat): preserve follow state across delayed layout changes](https://github.com/HKUDS/DeepTutor/pull/1935) | closed | yes | no | dev | contrib/chat-layout-follow |
| 1936 | [feat(mastery): retain scoped teaching feedback and strategy outcomes](https://github.com/HKUDS/DeepTutor/pull/1936) | closed | yes | no | dev | contrib/mastery-teaching-guide |
| 1937 | [fix(mineru): own CLI worker lifecycle and avoid pipe-related hangs](https://github.com/HKUDS/DeepTutor/pull/1937) | closed | yes | no | dev | contrib/mineru-owned-process |
| 1938 | [feat(mastery): bound replay history while retaining exact tutoring recall](https://github.com/HKUDS/DeepTutor/pull/1938) | closed | yes | no | dev | contrib/mastery-sustainable-memory |
| 1939 | [feat(mastery): review outline batches before atomic commit (builds on #1932)](https://github.com/HKUDS/DeepTutor/pull/1939) | closed | yes | no | dev | contrib/mastery-reviewed-outline |
| 1942 | [fix(reading): accept browser-zipped EPUB folder uploads](https://github.com/HKUDS/DeepTutor/pull/1942) | closed | yes | no | dev | fix/epub-folder-drag-zip |
| 1943 | [feat(mastery): independently graded question groups with safe submission recovery](https://github.com/HKUDS/DeepTutor/pull/1943) | closed | yes | no | dev | contrib/mastery-grouped-assessment |
| 1945 | [fix(chat): recover edited and unsent submissions without duplicate admission](https://github.com/HKUDS/DeepTutor/pull/1945) | closed | yes | no | dev | contrib/chat-unsent-edit-recovery |
| 1948 | [fix(agentic): accept explicitly supplied schema-valid null arguments](https://github.com/HKUDS/DeepTutor/pull/1948) | closed | yes | no | dev | contrib/nullable-required-arguments |
| 1950 | [fix: close cron and web-source SQLite connections](https://github.com/HKUDS/DeepTutor/pull/1950) | closed | yes | no | dev | fix/close-background-sqlite-connections |
| 1952 | [fix(mastery): bind teaching records to visible delivered explanation](https://github.com/HKUDS/DeepTutor/pull/1952) | closed | yes | no | dev | contrib/mastery-delivered-teaching |
| 1953 | [feat(mastery): evaluate source-bound answers semantically with repairable uncertainty](https://github.com/HKUDS/DeepTutor/pull/1953) | closed | yes | no | dev | contrib/mastery-semantic-assessment |
| 1954 | [fix(mastery): make source preparation demand-driven and preserve partial teaching](https://github.com/HKUDS/DeepTutor/pull/1954) | closed | yes | no | dev | contrib/mastery-demand-source-preparation |
| 1956 | [fix(runtime): persist explicit incomplete capability results as failed turns](https://github.com/HKUDS/DeepTutor/pull/1956) | closed | yes | no | dev | contrib/capability-incomplete-outcome |
| 1957 | [fix(mastery): protect answer sources and finish repaired assessment delivery](https://github.com/HKUDS/DeepTutor/pull/1957) | closed | yes | no | dev | contrib/mastery-assessment-delivery-safety |
| 1958 | [fix: keep a chat turn's prompt-cache prefix stable across turns](https://github.com/HKUDS/DeepTutor/pull/1958) | closed | yes | no | dev | fix/prompt-cache-prefix |
| 1959 | [fix(voice): add native Gemini TTS adapter for generateContent speech](https://github.com/HKUDS/DeepTutor/pull/1959) | closed | yes | no | dev | fix/gemini-native-tts |
| 1962 | [fix(agents): count the full request in the context-window guard](https://github.com/HKUDS/DeepTutor/pull/1962) | closed | yes | no | dev | fix/context-window-guard |
| 1963 | [perf(documents): bound an inlined raster's long edge before admission](https://github.com/HKUDS/DeepTutor/pull/1963) | closed | yes | no | dev | perf/bound-inline-attachment-images |
| 1964 | [test: stabilize shared transport and browser audit contracts](https://github.com/HKUDS/DeepTutor/pull/1964) | closed | yes | no | dev | codex/pr-ci-settlement |
| 1965 | [perf(reading): load Markdown export only when requested](https://github.com/HKUDS/DeepTutor/pull/1965) | closed | yes | no | dev | codex/reading-export-lazy |
| 1967 | [fix(voice): surface the HTTP status when a preview error body is not JSON](https://github.com/HKUDS/DeepTutor/pull/1967) | closed | yes | no | dev | fix/voice-preview-non-json-error |
| 1969 | [fix(solve): keep the remaining plan in view after each step fold](https://github.com/HKUDS/DeepTutor/pull/1969) | closed | yes | no | dev | fix/solve-fold-keeps-plan |
| 1970 | [fix(chat): reconcile and dismiss browser-local unsent submissions](https://github.com/HKUDS/DeepTutor/pull/1970) | closed | yes | no | dev | codex/failed-submission-recovery |
| 1974 | [fix: install tzdata so named timezones resolve on Windows](https://github.com/HKUDS/DeepTutor/pull/1974) | closed | yes | no | dev | fix/windows-tzdata-usage-statistics |
| 1977 | [Feat/encore memory knowledge direct urls](https://github.com/HKUDS/DeepTutor/pull/1977) | closed | no | no | main | feat/encore-memory-knowledge-direct-urls |
| 1978 | [fix(llm): keep an explicit strict setting when converting tools for the Responses API](https://github.com/HKUDS/DeepTutor/pull/1978) | closed | yes | no | dev | fix/responses-tool-strict |
| 1980 | [feat(api): optional application-layer security with fastapi-guard (off by default)](https://github.com/HKUDS/DeepTutor/pull/1980) | closed | yes | no | dev | feat/fastapi-guard-security-middleware |
| 1985 | [fix(doctor): convert resolved LLM config before the online probe](https://github.com/HKUDS/DeepTutor/pull/1985) | closed | yes | no | dev | fix/doctor-online-resolved-config |
| 1986 | [fix: decode fetched pages with their declared <meta> charset](https://github.com/HKUDS/DeepTutor/pull/1986) | closed | yes | no | dev | fix/web-fetch-meta-charset |
| 1992 | [fix(llm): scope Codex prompt cache key to the conversation and send session-id](https://github.com/HKUDS/DeepTutor/pull/1992) | closed | yes | no | dev | claude/1991-fix |
| 1994 | [fix: render Markdown in partner conversation archives](https://github.com/HKUDS/DeepTutor/pull/1994) | closed | yes | no | dev | fix/partner-archives-markdown |
| 1995 | [feat: render Telegram replies with native rich messages](https://github.com/HKUDS/DeepTutor/pull/1995) | open | no | no | dev | feat/telegram-native-rich-messages |
| 1996 | [feat: choose reasoning effort per conversation](https://github.com/HKUDS/DeepTutor/pull/1996) | closed | no | yes | dev | feat/chat-reasoning-effort |
| 1997 | [fix(rag): wrap maybe_rewrite in try/except for fail-open safety](https://github.com/HKUDS/DeepTutor/pull/1997) | closed | no | no | main | fix/rag-query-rewrite-fail-open |
| 1998 | [fix(rag): wrap maybe_rewrite in try/except for fail-open safety](https://github.com/HKUDS/DeepTutor/pull/1998) | closed | yes | no | dev | fix/rag-query-rewrite-fail-open |
| 1999 | [feat(sync): 端云同步路由（分域分权 / 幂等 / 冲突留档 / 大文件通道）](https://github.com/HKUDS/DeepTutor/pull/1999) | open | no | no | dev | feat/sync-router |
| 2000 | [fix(mastery): show the picked option's text next to its letter in the grade seed](https://github.com/HKUDS/DeepTutor/pull/2000) | closed | yes | no | dev | claude/1993-fix |
| 2002 | [fix(docker): skip production frontend build in development](https://github.com/HKUDS/DeepTutor/pull/2002) | open | no | no | dev | fix/docker-development-build |
| 2004 | [feat: recommend MiniMax Flash and map current reasoning controls](https://github.com/HKUDS/DeepTutor/pull/2004) | closed | yes | no | dev | octo/minimax-m31-flash |
| 2006 | [fix(rag): decode BOM-marked UTF-8, Windows-1252 and UTF-16 text](https://github.com/HKUDS/DeepTutor/pull/2006) | open | no | no | dev | fix/text-decoding-order |
| 2007 | [fix(documents): read a DOCX text box and moved text once](https://github.com/HKUDS/DeepTutor/pull/2007) | open | no | no | dev | fix/docx-text-box-duplicates |
| 2008 | [fix(documents): keep empty PPTX table cells in their columns](https://github.com/HKUDS/DeepTutor/pull/2008) | open | no | no | dev | fix/pptx-table-empty-cells |
| 2009 | [fix: skip BM25 construction for vector-only indexing](https://github.com/HKUDS/DeepTutor/pull/2009) | open | no | no | dev | fix/vector-index-without-bm25 |
| 2010 | [feat(mcp): add Keenable web search to the curated catalog](https://github.com/HKUDS/DeepTutor/pull/2010) | open | no | no | dev | feat/keenable-mcp-catalog |
| 2011 | [fix(voice): cap manual read-aloud excerpts](https://github.com/HKUDS/DeepTutor/pull/2011) | open | no | no | dev | fix/read-aloud-preview |
| 2013 | [feat: animated video lessons rendered live with Remotion](https://github.com/HKUDS/DeepTutor/pull/2013) | closed | yes | no | preview | feat/video-lesson |
| 2014 | [feat(voice): add Microsoft Edge as a TTS provider](https://github.com/HKUDS/DeepTutor/pull/2014) | closed | yes | no | preview | feat/edge-tts-provider |
| 2016 | [fix(solve): refuse a second solve_plan so replans stay budgeted](https://github.com/HKUDS/DeepTutor/pull/2016) | closed | yes | no | dev | fix/solve-plan-respects-replan-budget |
| 2017 | [feat(learner): record reading time and guardian practice view (#1988)](https://github.com/HKUDS/DeepTutor/pull/2017) | open | no | no | dev | codex/feat/learner-reading-time-practice |
| 2018 | [fix: PDF uploads in chat dont get easily read in next message in same chat because of tool error](https://github.com/HKUDS/DeepTutor/pull/2018) | open | no | no | dev | oss-harness/issue-1223 |
| 2019 | [fix: keep mastery review within the mastery gate](https://github.com/HKUDS/DeepTutor/pull/2019) | closed | yes | no | dev | fix/issue-2012-mastered-review-queue |
| 2021 | [fix(chat): unlock iOS reply playback (#2020)](https://github.com/HKUDS/DeepTutor/pull/2021) | closed | yes | no | dev | codex/fix/ios-tts-playback |
| 2024 | [docs(storage): document local persistence layout (#612)](https://github.com/HKUDS/DeepTutor/pull/2024) | closed | yes | no | dev | codex/docs/local-data-storage |
| 2025 | [feat(search): add You.com provider (#1915)](https://github.com/HKUDS/DeepTutor/pull/2025) | closed | yes | no | dev | codex/fix/youcom-search-provider |
| 2026 | [fix(cli): budget reasoning model probes (#1220)](https://github.com/HKUDS/DeepTutor/pull/2026) | closed | yes | no | dev | codex/fix/init-reasoning-probe |
| 2027 | [fix(rag): resume embedding checkpoints (#1983)](https://github.com/HKUDS/DeepTutor/pull/2027) | closed | yes | no | dev | codex/feat/rag-embedding-resume |
| 2028 | [feat(learning): add mastery review strategies (#1908)](https://github.com/HKUDS/DeepTutor/pull/2028) | closed | yes | no | dev | codex/feat/mastery-review-strategies |
| 2029 | [fix(cron): keep server-local cron times on the wall clock across DST](https://github.com/HKUDS/DeepTutor/pull/2029) | closed | yes | no | dev | fix/cron-local-time-dst |
| 2033 | [fix(mastery): prevent recursive history archive growth](https://github.com/HKUDS/DeepTutor/pull/2033) | closed | yes | no | dev | fix/mastery-history-recursion |
| 2035 | [fix(runtime): recover orphaned turns after worker restart](https://github.com/HKUDS/DeepTutor/pull/2035) | closed | yes | no | dev | fix/worker-lost-recovery |
| 2038 | [fix(settings): expose effective vision support in llm-options](https://github.com/HKUDS/DeepTutor/pull/2038) | closed | no | no | dev | fix/llm-options-vision-flag |
| 2039 | [fix(settings): let a declared vision model drive image description](https://github.com/HKUDS/DeepTutor/pull/2039) | closed | yes | no | dev | fix/vision-capability-declared-provider |
| 2040 | [fix(rag): keep a failing caption group from aborting the ingest](https://github.com/HKUDS/DeepTutor/pull/2040) | closed | yes | no | dev | fix/image-caption-group-resilience |
| 2042 | [fix(session): bound PocketBase latest-message reads](https://github.com/HKUDS/DeepTutor/pull/2042) | closed | yes | no | dev | codex/deeptutor-bounded-last-message |
| 2043 | [test(parsing): stop racing init's reaping of a killed MinerU child](https://github.com/HKUDS/DeepTutor/pull/2043) | closed | no | no | dev | fix/mineru-lifecycle-zombie-race |
| 2044 | [Feature/practice qti support](https://github.com/HKUDS/DeepTutor/pull/2044) | open | no | no | dev | feature/practice_qti_support |
| 2045 | [fix(knowledge): keep same-named documents when creating a KB](https://github.com/HKUDS/DeepTutor/pull/2045) | closed | yes | no | dev | fix/kb-create-keep-same-named-docs |
| 2046 | [test: stabilize device credential timing across UTC midnight](https://github.com/HKUDS/DeepTutor/pull/2046) | closed | yes | no | dev | codex/fix/tests-playwright-runner |
| 2048 | [feat(providers): add Runcrate as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/2048) | closed | yes | no | dev | feat/runcrate-provider |
| 2050 | [feat: manage generated output files](https://github.com/HKUDS/DeepTutor/pull/2050) | closed | yes | no | dev | feat/math-animation-file-actions |
| 2051 | [fix(mastery): read idle placeholder arguments as omission (#2047)](https://github.com/HKUDS/DeepTutor/pull/2051) | closed | yes | no | dev | fix/mastery-revise-inactive-arguments |
| 2052 | [feat(tools): read a notebook record in full, and append to it](https://github.com/HKUDS/DeepTutor/pull/2052) | closed | no | no | dev | feat/notebook-read-append-2049 |
| 2056 | [fix(web): package and configure PDF.js CMaps for reader](https://github.com/HKUDS/DeepTutor/pull/2056) | closed | yes | no | dev | fix/pdfjs-cmap-url |
| 2058 | [fix(textbook_struct): keep two-char 单元 chapter token intact](https://github.com/HKUDS/DeepTutor/pull/2058) | closed | yes | no | dev | fix/textbook-struct-unit-header |
| 2059 | [fix(config): stop chat-settings read from corrupting shipped defaults](https://github.com/HKUDS/DeepTutor/pull/2059) | closed | yes | no | dev | fix/config-chat-defaults-mutation |
| 2060 | [fix(plugins): dedupe manifest dependencies by PEP 503 canonical name](https://github.com/HKUDS/DeepTutor/pull/2060) | closed | yes | no | dev | fix/plugins-dep-canonical-dedupe |
| 2061 | [fix(co_writer): don't crash DOCX export on a literal NUL in Markdown](https://github.com/HKUDS/DeepTutor/pull/2061) | closed | yes | no | dev | fix/co-writer-docx-nul-sentinel |
| 2062 | [fix(search): don't let flagged long references bypass Moderation](https://github.com/HKUDS/DeepTutor/pull/2062) | closed | yes | no | dev | fix/search-moderation-key-mismatch |
| 2063 | [fix(learning): resolve 'lesson N' by rank, not 0-based order value](https://github.com/HKUDS/DeepTutor/pull/2063) | closed | yes | no | dev | fix/learning-nav-module-order-base |
| 2064 | [fix(visualizers): normalize ids in lifecycle mutators like get()](https://github.com/HKUDS/DeepTutor/pull/2064) | closed | yes | no | dev | fix/visualizers-id-normalization |
| 2065 | [fix(api): strip control chars from Content-Disposition ASCII fallback](https://github.com/HKUDS/DeepTutor/pull/2065) | closed | yes | no | dev | fix/api-content-disposition-control-chars |
| 2066 | [fix(rag): strip only list markers from generated queries](https://github.com/HKUDS/DeepTutor/pull/2066) | closed | yes | no | dev | fix/rag-query-marker-stripping |
| 2067 | [fix(storage): escape LIKE wildcards in file library search](https://github.com/HKUDS/DeepTutor/pull/2067) | closed | yes | no | dev | fix/storage-file-search-like-escape |
| 2068 | [fix(textbook_struct): keep the higher-page chapter hit when deduping](https://github.com/HKUDS/DeepTutor/pull/2068) | closed | yes | no | dev | fix/textbook-dedupe-keep-higher-page |
| 2069 | [fix(vision): track escapes when splitting GeoGebra command args](https://github.com/HKUDS/DeepTutor/pull/2069) | closed | yes | no | dev | fix/ggb-validator-escaped-string-split |
| 2071 | [feat(pageindex): index with the Task model when one is configured](https://github.com/HKUDS/DeepTutor/pull/2071) | closed | yes | no | dev | feat/pageindex-task-model |
| 2076 | [feat(search): add google-browser-scraper as a self-hosted Google provider](https://github.com/HKUDS/DeepTutor/pull/2076) | closed | yes | no | dev | feat/google-browser-scraper-search |
| 2079 | [fix(video-lesson): run safely without Docker](https://github.com/HKUDS/DeepTutor/pull/2079) | closed | yes | no | preview | codex/video-runtime-isolation |
| 2080 | [fix(workspace): omit archived workspaces from navigation indexes](https://github.com/HKUDS/DeepTutor/pull/2080) | closed | no | no | dev | fix-workspace-nav-archived |
| 2081 | [fix: Agent loop bypasses OpenAICompatProvider cache_control, so Claude on OpenRouter never caches in chat/Mastery Path (](https://github.com/HKUDS/DeepTutor/pull/2081) | closed | yes | no | dev | oss-harness/issue-2078 |
| 2082 | [fix: omit completed Anthropic thinking at durable history replay](https://github.com/HKUDS/DeepTutor/pull/2082) | closed | yes | no | dev | fix/anthropic-stale-thinking-replay |
| 2083 | [feat: voice replies for the Feishu channel + pluggable transcription endpoint](https://github.com/HKUDS/DeepTutor/pull/2083) | closed | no | no | dev | local-voice-features |
| 2084 | [fix(subagent): discover Claude Code models through the official SDK](https://github.com/HKUDS/DeepTutor/pull/2084) | closed | no | no | dev | codex/claude-model-discovery |
| 2085 | [fix(mastery): keep shared history prefixes stable for prompt caching](https://github.com/HKUDS/DeepTutor/pull/2085) | closed | yes | no | dev | fix/mastery-history-prefix |
| 2086 | [feat(workspace): add a server-side folder picker for project workspaces](https://github.com/HKUDS/DeepTutor/pull/2086) | closed | yes | no | dev | codex/workspace-folder-picker |
| 2087 | [fix(subagent): discover Claude Code models through the official SDK](https://github.com/HKUDS/DeepTutor/pull/2087) | closed | yes | no | dev | codex/claude-model-discovery |
| 2089 | [fix(llm): match zhipu/GLM multimodal rejection so text-only retry fires](https://github.com/HKUDS/DeepTutor/pull/2089) | closed | yes | no | dev | fix/zhipu-image-rejection-retry |
| 2090 | [fix: Exact-substring quote check rejects faithful citations (line breaks/markup differ), so mastery_quiz fails repeatedl](https://github.com/HKUDS/DeepTutor/pull/2090) | closed | yes | no | dev | oss-harness/issue-2075 |
| 2093 | [fix(session): allow Little Tutor selections across Markdown markup and tables](https://github.com/HKUDS/DeepTutor/pull/2093) | closed | yes | no | dev | fix/issue-2091-selection-grounding-markdown |
| 2094 | [fix: stabilize worker recovery and repair dev contract checks](https://github.com/HKUDS/DeepTutor/pull/2094) | closed | yes | no | dev | codex/ci-contract-recovery-oct27 |
| 2095 | [fix(web): stop the mastery-goal source picker from trapping the mouse wheel](https://github.com/HKUDS/DeepTutor/pull/2095) | closed | yes | no | dev | fix/topic-wizard-scroll |
| 2096 | [feat: integrate modular installation with current dev](https://github.com/HKUDS/DeepTutor/pull/2096) | closed | yes | no | dev | codex/dev-modular-integration-oct28 |
| 2098 | [feat(calendar): export calendars as .ics files](https://github.com/HKUDS/DeepTutor/pull/2098) | closed | yes | no | dev | feat/calendar-ics-export |
| 2099 | [feat(notes): export flashcards for Anki](https://github.com/HKUDS/DeepTutor/pull/2099) | closed | yes | no | dev | feat/flashcards-anki-export |
| 2103 | [fix: Mastery Path concept objectives can never pass — every `mastery_assess` is refused as "teaching slice", so the tuto](https://github.com/HKUDS/DeepTutor/pull/2103) | closed | yes | no | dev | oss-harness/issue-2070 |
| 2108 | [fix(web): let a scrollbar drag release chat auto-follow while streaming](https://github.com/HKUDS/DeepTutor/pull/2108) | closed | yes | no | dev | fix/chat-scrollbar-drag-releases-follow |
| 2109 | [feat: add Claude Code provider backed by the Claude Agent SDK](https://github.com/HKUDS/DeepTutor/pull/2109) | closed | yes | no | dev | claude-code-provider |
| 2112 | [fix(memory): size chunk windows by the stride overlap leaves](https://github.com/HKUDS/DeepTutor/pull/2112) | closed | yes | no | dev | fix/chunker-budget-overlap-stride |
| 2113 | [[codex] Add isolated native memory snapshot evaluation](https://github.com/HKUDS/DeepTutor/pull/2113) | closed | yes | no | dev | codex/memory-evaluation-pilot |
| 2114 | [test: unblock dev's red contracts (stale expectations + chat budget headroom)](https://github.com/HKUDS/DeepTutor/pull/2114) | closed | yes | no | dev | fix/stale-contract-tests |
| 2115 | [fix: mask code and math spans in one pass before the CJK emphasis repair](https://github.com/HKUDS/DeepTutor/pull/2115) | closed | yes | no | dev | fix/cjk-emphasis-protected-spans |
| 2116 | [fix(session): mask code and math spans in one pass for CJK emphasis repair](https://github.com/HKUDS/DeepTutor/pull/2116) | closed | no | no | dev | fix/cjk-emphasis-protected-spans |
| 2117 | [fix(llm): keep streamed tool calls without an index apart](https://github.com/HKUDS/DeepTutor/pull/2117) | closed | yes | no | dev | fix/stream-tool-call-no-index |
| 2120 | [fix: preserve request identity when retrying unsent messages](https://github.com/HKUDS/DeepTutor/pull/2120) | closed | yes | no | dev | fix/preserve-submission-retry-request |
| 2121 | [fix(web): follow the OS theme by default and add a System option](https://github.com/HKUDS/DeepTutor/pull/2121) | closed | yes | no | dev | fix/2100-theme-follow-system |
| 2122 | [fix: use the current model and reply language when editing or resending](https://github.com/HKUDS/DeepTutor/pull/2122) | closed | yes | no | dev | feature/chat-edit-resend-current-settings |
| 2124 | [fix(web): edited questions pick up the live model and reply language](https://github.com/HKUDS/DeepTutor/pull/2124) | closed | yes | no | dev | fix/2106-edit-message-live-settings |
| 2125 | [fix(knowledge): reuse renamed staged documents on retry](https://github.com/HKUDS/DeepTutor/pull/2125) | closed | yes | no | dev | fix/reuse-colliding-staged-source |
| 2126 | [Integrate reviewed October PRs with correctness and compatibility fixes](https://github.com/HKUDS/DeepTutor/pull/2126) | closed | yes | no | dev | codex/pr-landing-oct29 |
| 2127 | [fix(web): keep the composer resources popover inside the viewport](https://github.com/HKUDS/DeepTutor/pull/2127) | open | no | no | dev | fix/2053-resource-popover-overflow |
| 2128 | [fix: show file actions for direct exec attachments](https://github.com/HKUDS/DeepTutor/pull/2128) | open | no | no | dev | feat/math-animation-file-actions |
| 2131 | [fix: recognize unspaced CJK memory sentence boundaries](https://github.com/HKUDS/DeepTutor/pull/2131) | open | no | no | dev | fix/memory-cjk-sentence-boundaries |
| 2135 | [feat(i18n): add Turkish as an interface and reply language](https://github.com/HKUDS/DeepTutor/pull/2135) | open | no | no | dev | feat/turkish-locale |
| 2136 | [fix(files): decode Windows-1254 text before falling back to Latin-1](https://github.com/HKUDS/DeepTutor/pull/2136) | open | no | no | dev | fix/cp1254-text-decoding |
| 2137 | [fix: Mastery Path re-poses a question the learner already answered correctly (fallback to the one source-verifiable item](https://github.com/HKUDS/DeepTutor/pull/2137) | open | no | no | main | oss-harness/issue-2073 |
| 2138 | [feat(providers): add CloudGPU as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/2138) | open | no | no | dev | cursor/cloudgpu-provider-a629 |
| 2139 | [Fix reindex freeze on large knowledge bases (O(n^2) run-state serialization)](https://github.com/HKUDS/DeepTutor/pull/2139) | open | no | no | main | fix/large-kb-reindex-on2-freeze |
