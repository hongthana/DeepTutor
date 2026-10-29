# GitHub issue and PR endpoint inventory — 2026-10-29

This is a traceability index for the downloaded GitHub Issues API collection for `HKUDS/DeepTutor` (source checkout `1ea7df155447f4caf0e3abc86b3ff5395479cd4a`). It contains all 2,080 endpoint entries: 773 issue records and 1,307 pull-request records exposed through the issues endpoint. PR entries link to their canonical pull request; see [pull-request metadata](pull-requests.md) for base/head and merge state.

Collection used the fully paginated [GitHub Issues endpoint](https://api.github.com/repos/HKUDS/DeepTutor/issues) with all states; the separately collected discussion comments came from the [issue comments endpoint](https://api.github.com/repos/HKUDS/DeepTutor/issues/comments). Requests used `state=all&per_page=100&page=N`; pages 1–21 returned records (page 21 contained 80), and page 22 returned empty. Issue comments used `per_page=100&page=N`; pages 1–22 returned records (page 22 contained 92), and page 23 returned empty. Default sorting/order parameters were omitted; this was not a stable cursor snapshot. The 773 issue records span 2025-12-29 through 2026-10-29 UTC (651 closed, 122 open at collection); 1,307 additional entries are pull requests. The downloaded comment collection contains 2,192 accessible records; endpoint metadata sums to 2,270 comments across issue and PR entries, so the 78-record discrepancy remains unexplained. Per-issue reconciliation for discrepant issues 782, 781, 777, 775, 773, 766, 761, 760, 759, 755 and 617 returned the same accessible counts. The separately downloaded inline-review collection contains 129 records. This is a point-in-time snapshot, not a claim about current remote state. It records titles, URLs, state, timestamps, and comment count, not full bodies or diffs. Read the linked GitHub discussion before taking an item; a later change may have closed or superseded it.

| Number | Kind | Title | Endpoint state | Created UTC | Updated UTC | Issue comments reported |
|---:|---|---|---|---|---|---:|
| 1 | Issue | [[Question]: I am looking to work on TODO tasks but.](https://github.com/HKUDS/DeepTutor/issues/1) | closed | 2025-12-29 | 2026-01-01 | 2 |
| 2 | PR | [avoid false 'Virtual env not detected' warning under conda](https://github.com/HKUDS/DeepTutor/pull/2) | closed | 2025-12-29 | 2025-12-31 | 1 |
| 3 | Issue | [[Feature Request]: Official Docker deployment support (Compose + prebuilt images)](https://github.com/HKUDS/DeepTutor/issues/3) | closed | 2025-12-29 | 2026-01-02 | 12 |
| 4 | Issue | [[Feature Request]:用gemini设计的一个考试模拟软件希望可以融合进DeepTutor项目中](https://github.com/HKUDS/DeepTutor/issues/4) | closed | 2025-12-30 | 2026-01-02 | 4 |
| 6 | Issue | [[Bug]:macmini M4芯片，依赖安装报错](https://github.com/HKUDS/DeepTutor/issues/6) | closed | 2025-12-31 | 2025-12-31 | 3 |
| 7 | Issue | [[Feature Request]: 可以集合一下minerU的PDF识别功能](https://github.com/HKUDS/DeepTutor/issues/7) | closed | 2025-12-31 | 2025-12-31 | 1 |
| 10 | PR | [fix(ui): knowledge base modal backdrop and positioning](https://github.com/HKUDS/DeepTutor/pull/10) | closed | 2025-12-31 | 2025-12-31 | 1 |
| 11 | PR | [Hardened the Application's Attack Surface through Least Privilege Principle](https://github.com/HKUDS/DeepTutor/pull/11) | closed | 2025-12-31 | 2025-12-31 | 1 |
| 12 | PR | [fix(core): ensure core attributes initialized without rich library](https://github.com/HKUDS/DeepTutor/pull/12) | closed | 2025-12-31 | 2025-12-31 | 1 |
| 13 | PR | [Added docker support along with some minor changes in previous files related to types](https://github.com/HKUDS/DeepTutor/pull/13) | closed | 2025-12-31 | 2026-01-02 | 11 |
| 14 | PR | [Add Docker infrastructure for DeepTutor, including multi-stage Docker…](https://github.com/HKUDS/DeepTutor/pull/14) | closed | 2025-12-31 | 2026-07-29 | 2 |
| 15 | Issue | [[Bug]: Smart Solver fails with JSON validation error when LLM generates Python triple-quoted strings](https://github.com/HKUDS/DeepTutor/issues/15) | closed | 2025-12-31 | 2026-01-02 | 17 |
| 17 | PR | [Create HARM](https://github.com/HKUDS/DeepTutor/pull/17) | closed | 2025-12-31 | 2026-01-01 | 1 |
| 18 | PR | [Fix JSON parsing failure for triple-quoted Python strings in Smart Solver](https://github.com/HKUDS/DeepTutor/pull/18) | closed | 2026-01-01 | 2026-01-01 | 1 |
| 19 | PR | [Refined prompt for balance between deducing and rag](https://github.com/HKUDS/DeepTutor/pull/19) | closed | 2026-01-01 | 2026-01-01 | 0 |
| 20 | PR | [fix(security): patch critical RCE and LFI vulnerabilities](https://github.com/HKUDS/DeepTutor/pull/20) | closed | 2026-01-02 | 2026-01-02 | 2 |
| 21 | PR | [chore(deps): update core libraries to mitigate known CVEs](https://github.com/HKUDS/DeepTutor/pull/21) | closed | 2026-01-02 | 2026-01-02 | 1 |
| 22 | PR | [feat(security): enforce WSS protocol for production websockets](https://github.com/HKUDS/DeepTutor/pull/22) | closed | 2026-01-02 | 2026-01-02 | 1 |
| 23 | PR | [fix: SolveAgent code generation by enforcing intent-only planning](https://github.com/HKUDS/DeepTutor/pull/23) | closed | 2026-01-02 | 2026-01-02 | 0 |
| 24 | Issue | [[Bug]: Exposed markdown syntax on dashboard (UI)](https://github.com/HKUDS/DeepTutor/issues/24) | closed | 2026-01-03 | 2026-01-04 | 0 |
| 25 | Issue | [[Question]:co-write tts应该如何配置](https://github.com/HKUDS/DeepTutor/issues/25) | closed | 2026-01-04 | 2026-01-04 | 1 |
| 26 | PR | [fix(UI): unrendered markdown in ActivityDetail card](https://github.com/HKUDS/DeepTutor/pull/26) | closed | 2026-01-04 | 2026-01-04 | 1 |
| 27 | PR | [chore: transtale readme to ru](https://github.com/HKUDS/DeepTutor/pull/27) | closed | 2026-01-04 | 2026-01-04 | 1 |
| 28 | PR | [fix: improve reload_excludes configuration for uvicorn server and added support for newer models (openai)](https://github.com/HKUDS/DeepTutor/pull/28) | closed | 2026-01-04 | 2026-01-06 | 1 |
| 29 | PR | [feat(i18n): add Portuguese language support](https://github.com/HKUDS/DeepTutor/pull/29) | closed | 2026-01-05 | 2026-01-09 | 4 |
| 30 | Issue | [[Bug]: Support opensource embedding models with different embedding dimensions than 1536 or 3072](https://github.com/HKUDS/DeepTutor/issues/30) | closed | 2026-01-05 | 2026-01-05 | 2 |
| 31 | Issue | [[Bug]:加载大文件的pdf文件的时候会提取不出来数据（complete! Extracted 0 content blocks [KnowledgeInit] ✗ ✗ Error processing 1.pdf: Parsing failed: No content was extracted）](https://github.com/HKUDS/DeepTutor/issues/31) | closed | 2026-01-05 | 2026-01-14 | 7 |
| 32 | PR | [Support open-source embedding models with custom embedding dimensions](https://github.com/HKUDS/DeepTutor/pull/32) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 33 | Issue | [issue: [architectural debt] refactor fragmented prompt loading and hardcoded language logic](https://github.com/HKUDS/DeepTutor/issues/33) | closed | 2026-01-05 | 2026-01-05 | 2 |
| 34 | PR | [feat: Dynamic LLM Provider Support (Local & Cloud)](https://github.com/HKUDS/DeepTutor/pull/34) | closed | 2026-01-05 | 2026-01-05 | 3 |
| 35 | PR | [fix: unify prompt loading and handle optional lightrag dependency](https://github.com/HKUDS/DeepTutor/pull/35) | closed | 2026-01-05 | 2026-01-05 | 3 |
| 36 | Issue | [[Bug]: Not able to run it on the 0.0.0.0](https://github.com/HKUDS/DeepTutor/issues/36) | closed | 2026-01-05 | 2026-01-09 | 4 |
| 37 | Issue | [[Bug]: LLMProvider uses str instead of string causing build failure](https://github.com/HKUDS/DeepTutor/issues/37) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 38 | PR | [chore(deps): bump actions/upload-pages-artifact from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/38) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 39 | PR | [chore(deps): bump actions/checkout from 4 to 6](https://github.com/HKUDS/DeepTutor/pull/39) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 40 | PR | [chore(deps): bump actions/configure-pages from 4 to 5](https://github.com/HKUDS/DeepTutor/pull/40) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 41 | PR | [chore(deps): bump python from 3.11-slim to 3.14-slim](https://github.com/HKUDS/DeepTutor/pull/41) | closed | 2026-01-05 | 2026-01-05 | 2 |
| 42 | PR | [chore(deps): bump node from 20-slim to 25-slim](https://github.com/HKUDS/DeepTutor/pull/42) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 43 | PR | [chore(deps): bump lucide-react from 0.460.0 to 0.562.0 in /web in the npm-minor-patch group](https://github.com/HKUDS/DeepTutor/pull/43) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 44 | PR | [chore(deps): bump framer-motion from 11.18.2 to 12.24.0 in /web](https://github.com/HKUDS/DeepTutor/pull/44) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 45 | PR | [chore(deps): bump tailwind-merge from 2.6.0 to 3.4.0 in /web](https://github.com/HKUDS/DeepTutor/pull/45) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 46 | PR | [chore(deps): bump tailwindcss from 3.4.19 to 4.1.18 in /web](https://github.com/HKUDS/DeepTutor/pull/46) | closed | 2026-01-05 | 2026-01-05 | 2 |
| 47 | PR | [chore(deps): bump react-markdown from 9.1.0 to 10.1.0 in /web](https://github.com/HKUDS/DeepTutor/pull/47) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 48 | PR | [chore(deps): bump @types/node from 22.19.3 to 25.0.3 in /web](https://github.com/HKUDS/DeepTutor/pull/48) | closed | 2026-01-05 | 2026-01-05 | 1 |
| 49 | PR | [chore(deps): bump jspdf from 2.5.2 to 4.0.0 in /web](https://github.com/HKUDS/DeepTutor/pull/49) | closed | 2026-01-05 | 2026-01-06 | 2 |
| 50 | PR | [fix(ci): Resolve linting and formatting issues](https://github.com/HKUDS/DeepTutor/pull/50) | closed | 2026-01-05 | 2026-01-06 | 2 |
| 51 | PR | [UI/theme](https://github.com/HKUDS/DeepTutor/pull/51) | closed | 2026-01-05 | 2026-01-07 | 2 |
| 52 | PR | [Add project report documenting fork use cases and setup](https://github.com/HKUDS/DeepTutor/pull/52) | closed | 2026-01-06 | 2026-01-06 | 0 |
| 53 | Issue | [[Bug]: docker 命令无法启动](https://github.com/HKUDS/DeepTutor/issues/53) | closed | 2026-01-06 | 2026-01-08 | 7 |
| 54 | Issue | [[Bug]: Fix `max_tokens` parameter for newer OpenAI models (gpt-5.x, o1, o3)](https://github.com/HKUDS/DeepTutor/issues/54) | closed | 2026-01-06 | 2026-01-08 | 1 |
| 55 | PR | [feat: support baidu ai search](https://github.com/HKUDS/DeepTutor/pull/55) | closed | 2026-01-06 | 2026-01-07 | 1 |
| 57 | PR | [Feature/rag plugin system](https://github.com/HKUDS/DeepTutor/pull/57) | closed | 2026-01-06 | 2026-01-06 | 1 |
| 58 | Issue | [[Bug]: Refuses to connect to ollama instance](https://github.com/HKUDS/DeepTutor/issues/58) | closed | 2026-01-06 | 2026-01-09 | 4 |
| 59 | Issue | [[Bug]: `test_embeddings_connection` assumes OpenAI embeddings](https://github.com/HKUDS/DeepTutor/issues/59) | closed | 2026-01-06 | 2026-01-09 | 4 |
| 60 | Issue | [[Feature Request]: upload directory of files at once](https://github.com/HKUDS/DeepTutor/issues/60) | closed | 2026-01-06 | 2026-01-15 | 5 |
| 62 | PR | [Fix critical jspdf vuln and clean up pre-commit hooks](https://github.com/HKUDS/DeepTutor/pull/62) | closed | 2026-01-06 | 2026-01-07 | 5 |
| 63 | Issue | [[Bug]: Can't generate multiple questions](https://github.com/HKUDS/DeepTutor/issues/63) | closed | 2026-01-06 | 2026-01-09 | 5 |
| 64 | PR | [fix: resolve double decoration in embedding functions for OpenRouter …](https://github.com/HKUDS/DeepTutor/pull/64) | closed | 2026-01-07 | 2026-01-07 | 1 |
| 65 | Issue | [[Feature Request]:希望markdown的编辑功能可以支持更加完善的表格编辑，可以实现合并表格等操作](https://github.com/HKUDS/DeepTutor/issues/65) | closed | 2026-01-07 | 2026-04-07 | 5 |
| 66 | PR | [Cleanup: address reviewer feedback on PR #62](https://github.com/HKUDS/DeepTutor/pull/66) | closed | 2026-01-07 | 2026-01-09 | 0 |
| 67 | PR | [Cleanup: address reviewer feedback on PR #62 (Final)](https://github.com/HKUDS/DeepTutor/pull/67) | closed | 2026-01-07 | 2026-01-07 | 3 |
| 68 | PR | [Arch/compliance and ux audit](https://github.com/HKUDS/DeepTutor/pull/68) | closed | 2026-01-07 | 2026-01-07 | 1 |
| 69 | Issue | [[Question]: Connection error when trying to use the 3rd party OpenAI provider.](https://github.com/HKUDS/DeepTutor/issues/69) | closed | 2026-01-07 | 2026-01-08 | 4 |
| 70 | Issue | [[Feature Request]:Implement Asynchronous Task Queue for Large File Processing to Prevent UI Blocking](https://github.com/HKUDS/DeepTutor/issues/70) | closed | 2026-01-07 | 2026-01-11 | 2 |
| 71 | PR | [feat/gracefully disable RagAnything when absent and tighten Python dependency handling](https://github.com/HKUDS/DeepTutor/pull/71) | closed | 2026-01-07 | 2026-01-08 | 3 |
| 72 | Issue | [[Bug]: unable to run on docker vps server](https://github.com/HKUDS/DeepTutor/issues/72) | closed | 2026-01-07 | 2026-01-09 | 2 |
| 73 | Issue | [[Feature Request]: 有计划提供多用户版本吗？ 所有知识共享但每个人的学习和笔记分开](https://github.com/HKUDS/DeepTutor/issues/73) | closed | 2026-01-07 | 2026-08-04 | 3 |
| 74 | Issue | [[Bug]:Docker run fail](https://github.com/HKUDS/DeepTutor/issues/74) | closed | 2026-01-08 | 2026-01-09 | 3 |
| 75 | Issue | [[Feature Request]:提供中文版本config](https://github.com/HKUDS/DeepTutor/issues/75) | closed | 2026-01-08 | 2026-01-09 | 1 |
| 76 | Issue | [[Question]:在知识库中仅有一篇pdf的论文，提问问题无法根据论文内容回答](https://github.com/HKUDS/DeepTutor/issues/76) | closed | 2026-01-08 | 2026-01-15 | 5 |
| 77 | PR | [provides more llm providers supports, fixed some ambiguities, ui updates,fixed discrepency between some elements of ui and backend were in sync.](https://github.com/HKUDS/DeepTutor/pull/77) | closed | 2026-01-08 | 2026-01-14 | 0 |
| 78 | Issue | [DeepTutor微信交流群](https://github.com/HKUDS/DeepTutor/issues/78) | open | 2026-01-08 | 2026-10-11 | 22 |
| 79 | PR | [Dev embeddings providers](https://github.com/HKUDS/DeepTutor/pull/79) | closed | 2026-01-08 | 2026-01-08 | 1 |
| 81 | PR | [fix: Add comprehensive error handling and JSON parsing for question g…](https://github.com/HKUDS/DeepTutor/pull/81) | closed | 2026-01-08 | 2026-01-09 | 0 |
| 82 | PR | [merge](https://github.com/HKUDS/DeepTutor/pull/82) | closed | 2026-01-08 | 2026-01-08 | 0 |
| 83 | PR | [fix(web): Remove duplicated translation keys](https://github.com/HKUDS/DeepTutor/pull/83) | closed | 2026-01-08 | 2026-01-09 | 2 |
| 84 | PR | [Fix test configuration for GitHub Actions](https://github.com/HKUDS/DeepTutor/pull/84) | closed | 2026-01-08 | 2026-01-09 | 0 |
| 85 | Issue | [[Bug]:azure openai not supported?](https://github.com/HKUDS/DeepTutor/issues/85) | closed | 2026-01-09 | 2026-01-14 | 3 |
| 86 | Issue | [[Question]:为什么使用DeepSeek api似乎不能让RAG正常工作](https://github.com/HKUDS/DeepTutor/issues/86) | closed | 2026-01-09 | 2026-01-14 | 4 |
| 87 | PR | [feat: azure openai support](https://github.com/HKUDS/DeepTutor/pull/87) | closed | 2026-01-09 | 2026-01-12 | 1 |
| 88 | Issue | [[Bug]:deepseek 深度研究报错](https://github.com/HKUDS/DeepTutor/issues/88) | closed | 2026-01-09 | 2026-01-09 | 1 |
| 89 | Issue | [[Bug]: markdown rendering issue.](https://github.com/HKUDS/DeepTutor/issues/89) | closed | 2026-01-10 | 2026-01-15 | 3 |
| 90 | PR | [docs: update](https://github.com/HKUDS/DeepTutor/pull/90) | closed | 2026-01-10 | 2026-01-11 | 1 |
| 91 | Issue | [[Bug]: Environment variable `EMBEDDING_DIMENSION` not being read correctly, causing embedding API failures](https://github.com/HKUDS/DeepTutor/issues/91) | closed | 2026-01-10 | 2026-01-11 | 4 |
| 92 | Issue | [[Bug]: Embedding  的ollama 的部署总是测试失败](https://github.com/HKUDS/DeepTutor/issues/92) | closed | 2026-01-10 | 2026-01-14 | 3 |
| 93 | PR | [Web search providers](https://github.com/HKUDS/DeepTutor/pull/93) | closed | 2026-01-10 | 2026-01-10 | 0 |
| 94 | Issue | [[Bug]:Embedding的硅基流动总是失败](https://github.com/HKUDS/DeepTutor/issues/94) | closed | 2026-01-10 | 2026-01-14 | 2 |
| 95 | PR | [Web search providers](https://github.com/HKUDS/DeepTutor/pull/95) | closed | 2026-01-10 | 2026-01-10 | 1 |
| 96 | PR | [Pr focused error handling](https://github.com/HKUDS/DeepTutor/pull/96) | closed | 2026-01-11 | 2026-01-11 | 0 |
| 97 | Issue | [[Bug]:跨平台部署失败 - Dockerfile及Shell脚本因CRLF换行符导致容器启动错误](https://github.com/HKUDS/DeepTutor/issues/97) | closed | 2026-01-11 | 2026-01-26 | 3 |
| 98 | PR | [feat: Implement LlamaIndex and LightRAG pipelines with complete loose coupling](https://github.com/HKUDS/DeepTutor/pull/98) | closed | 2026-01-11 | 2026-01-11 | 0 |
| 99 | PR | [fix: add standalone output mode for Docker deployment](https://github.com/HKUDS/DeepTutor/pull/99) | closed | 2026-01-11 | 2026-01-11 | 0 |
| 100 | Issue | [[Bug]:## LM Studio Embedding Integration Broken - 4 Critical Bugs ("hotfix")](https://github.com/HKUDS/DeepTutor/issues/100) | closed | 2026-01-11 | 2026-01-14 | 4 |
| 101 | Issue | [[Feature Request]: Local Folder Integration](https://github.com/HKUDS/DeepTutor/issues/101) | closed | 2026-01-11 | 2026-01-15 | 2 |
| 102 | PR | [chore(deps): bump docker/build-push-action from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/102) | closed | 2026-01-12 | 2026-01-12 | 2 |
| 103 | PR | [chore(deps): bump node from 22-slim to 25-slim](https://github.com/HKUDS/DeepTutor/pull/103) | closed | 2026-01-12 | 2026-01-12 | 2 |
| 104 | PR | [chore(deps): bump actions/setup-python from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/104) | closed | 2026-01-12 | 2026-01-12 | 2 |
| 105 | PR | [chore(deps): bump actions/checkout from 4 to 6](https://github.com/HKUDS/DeepTutor/pull/105) | closed | 2026-01-12 | 2026-01-12 | 2 |
| 106 | PR | [chore(deps): bump the npm-minor-patch group in /web with 3 updates](https://github.com/HKUDS/DeepTutor/pull/106) | closed | 2026-01-12 | 2026-01-12 | 2 |
| 107 | PR | [chore(deps): bump the python-minor-patch group with 4 updates](https://github.com/HKUDS/DeepTutor/pull/107) | closed | 2026-01-12 | 2026-01-12 | 2 |
| 108 | Issue | [[Feature Request]:前端配置平台还无法配置百度搜索的apikey，另外是否可以支持本地部署/非openai的tts模型呢](https://github.com/HKUDS/DeepTutor/issues/108) | closed | 2026-01-12 | 2026-01-14 | 2 |
| 109 | Issue | [[Feature Request]:智能解题界面刷新后内容消失](https://github.com/HKUDS/DeepTutor/issues/109) | closed | 2026-01-12 | 2026-01-19 | 2 |
| 110 | Issue | [[Bug]:Comprehensive Azure OpenAI API and gpt-5.2-chat Support](https://github.com/HKUDS/DeepTutor/issues/110) | closed | 2026-01-12 | 2026-01-14 | 3 |
| 112 | Issue | [[Bug]:用https访问setting页面显示Error loading data，请求被307重定向成http](https://github.com/HKUDS/DeepTutor/issues/112) | closed | 2026-01-12 | 2026-01-15 | 3 |
| 113 | Issue | [[Bug]: MinerU hangs during PDF parsing before embedding starts](https://github.com/HKUDS/DeepTutor/issues/113) | closed | 2026-01-12 | 2026-01-29 | 3 |
| 114 | PR | [Add feature toggling](https://github.com/HKUDS/DeepTutor/pull/114) | closed | 2026-01-12 | 2026-01-12 | 0 |
| 115 | Issue | [[Feature Request]:nas部署deeptutor显示backend service is offline](https://github.com/HKUDS/DeepTutor/issues/115) | closed | 2026-01-12 | 2026-01-27 | 9 |
| 116 | Issue | [[Question]: I have this error trying to set ollama models](https://github.com/HKUDS/DeepTutor/issues/116) | closed | 2026-01-12 | 2026-01-14 | 3 |
| 117 | PR | [fix: modal not vertically centered](https://github.com/HKUDS/DeepTutor/pull/117) | closed | 2026-01-13 | 2026-01-13 | 1 |
| 118 | PR | [work/llm-error-framework](https://github.com/HKUDS/DeepTutor/pull/118) | closed | 2026-01-13 | 2026-01-13 | 0 |
| 119 | Issue | [[Bug]:似乎无法处理md文件，转换成pdf过程中出错](https://github.com/HKUDS/DeepTutor/issues/119) | closed | 2026-01-13 | 2026-01-15 | 2 |
| 120 | Issue | [[Bug]:创建知识库上传文件报错](https://github.com/HKUDS/DeepTutor/issues/120) | closed | 2026-01-13 | 2026-01-14 | 1 |
| 121 | Issue | [[Bug]:embedding-dim](https://github.com/HKUDS/DeepTutor/issues/121) | closed | 2026-01-13 | 2026-01-14 | 1 |
| 122 | PR | [feat: Add Local Folder Integration (Closes #101)](https://github.com/HKUDS/DeepTutor/pull/122) | closed | 2026-01-13 | 2026-01-14 | 1 |
| 123 | Issue | [[BUG]:Knowledge Base initialization failure with Ollama: AttributeError ('list' object has no attribute 'size') and Dimension Mismatch](https://github.com/HKUDS/DeepTutor/issues/123) | closed | 2026-01-13 | 2026-10-12 | 3 |
| 124 | Issue | [[Bug]:Title: Issues Report: Dimension Mismatch, NumPy Formatting, and Windows Stability Improvements](https://github.com/HKUDS/DeepTutor/issues/124) | closed | 2026-01-13 | 2026-10-12 | 4 |
| 125 | Issue | [[Bug]: UI Progress Stuck at 100% after Backend Timeout](https://github.com/HKUDS/DeepTutor/issues/125) | closed | 2026-01-14 | 2026-10-12 | 1 |
| 126 | PR | [Feature/pre commit ci (#37)](https://github.com/HKUDS/DeepTutor/pull/126) | closed | 2026-01-14 | 2026-01-14 | 2 |
| 127 | PR | [feat: folder sync with improved architecture (supersedes #122)](https://github.com/HKUDS/DeepTutor/pull/127) | closed | 2026-01-14 | 2026-01-15 | 2 |
| 128 | PR | [fix/docker](https://github.com/HKUDS/DeepTutor/pull/128) | closed | 2026-01-14 | 2026-01-14 | 0 |
| 129 | PR | [feat(kb): allow selecting RAG provider during KB create/upload](https://github.com/HKUDS/DeepTutor/pull/129) | closed | 2026-01-14 | 2026-01-14 | 0 |
| 130 | PR | [feat: centralise JSON parsing with automatic repair fallback](https://github.com/HKUDS/DeepTutor/pull/130) | closed | 2026-01-14 | 2026-01-15 | 1 |
| 131 | PR | [Modular rag implementation](https://github.com/HKUDS/DeepTutor/pull/131) | closed | 2026-01-14 | 2026-01-15 | 0 |
| 132 | Issue | [[Bug]: "Generate Learning Plan BUG](https://github.com/HKUDS/DeepTutor/issues/132) | closed | 2026-01-14 | 2026-10-12 | 1 |
| 133 | Issue | [[Bug]: GPU CPU torch cuda problem](https://github.com/HKUDS/DeepTutor/issues/133) | closed | 2026-01-14 | 2026-10-12 | 3 |
| 134 | Issue | [[Bug]: Missing SetupWizard component causes frontend build](https://github.com/HKUDS/DeepTutor/issues/134) | closed | 2026-01-15 | 2026-10-12 | 4 |
| 135 | Issue | [[Bug]: AI Edit Assistant will not use the models in system settings, but only uses OpenAI.](https://github.com/HKUDS/DeepTutor/issues/135) | closed | 2026-01-15 | 2026-01-15 | 1 |
| 136 | Issue | [[Bug]:智能解题根本无法进行，用简单的 1+1= 都是一样的](https://github.com/HKUDS/DeepTutor/issues/136) | closed | 2026-01-15 | 2026-01-15 | 1 |
| 137 | Issue | [[Bug]:GPU SLOWNESS](https://github.com/HKUDS/DeepTutor/issues/137) | closed | 2026-01-15 | 2026-10-12 | 9 |
| 138 | PR | [fix: Folder Sync Improvements - Source Path Tracking & LightRAG Fallback](https://github.com/HKUDS/DeepTutor/pull/138) | closed | 2026-01-15 | 2026-04-07 | 2 |
| 139 | PR | [fix: vulnerabilities in code execution and container security](https://github.com/HKUDS/DeepTutor/pull/139) | closed | 2026-01-15 | 2026-01-29 | 0 |
| 140 | PR | [Feat/searxng](https://github.com/HKUDS/DeepTutor/pull/140) | closed | 2026-01-16 | 2026-04-07 | 1 |
| 141 | Issue | [[Bug]: Fix gpt-5.2-chat Support for Temperature = 1.0](https://github.com/HKUDS/DeepTutor/issues/141) | closed | 2026-01-16 | 2026-01-19 | 1 |
| 142 | PR | [Feature/solver session persistence](https://github.com/HKUDS/DeepTutor/pull/142) | closed | 2026-01-16 | 2026-01-19 | 2 |
| 143 | PR | [fix(llm): force temperature to 1.0 for gpt-5/o1/o3 models #141](https://github.com/HKUDS/DeepTutor/pull/143) | closed | 2026-01-16 | 2026-01-19 | 2 |
| 144 | Issue | [[Question]: 如何设置输出也是中文呢？现在所有的输出都是英文版本，即使问题和要求都是中文输入，输出也是英文版本](https://github.com/HKUDS/DeepTutor/issues/144) | closed | 2026-01-16 | 2026-01-22 | 1 |
| 145 | Issue | [[Bug]: .env.example_CN 中关于web_search 的配置描述错误](https://github.com/HKUDS/DeepTutor/issues/145) | closed | 2026-01-17 | 2026-01-18 | 1 |
| 146 | Issue | [[Bug]:在npn build的时候报错](https://github.com/HKUDS/DeepTutor/issues/146) | closed | 2026-01-18 | 2026-01-19 | 2 |
| 147 | PR | [feat: Increase LLM retry attempts and delays for enhanced robustness with complex agents.](https://github.com/HKUDS/DeepTutor/pull/147) | closed | 2026-01-18 | 2026-01-19 | 1 |
| 148 | Issue | [[Bug]:npm build 依旧报错](https://github.com/HKUDS/DeepTutor/issues/148) | closed | 2026-01-19 | 2026-01-19 | 2 |
| 149 | PR | [chore(deps): bump actions/cache from 4 to 5](https://github.com/HKUDS/DeepTutor/pull/149) | closed | 2026-01-19 | 2026-03-24 | 2 |
| 150 | PR | [chore(deps): bump actions/setup-node from 4 to 6](https://github.com/HKUDS/DeepTutor/pull/150) | closed | 2026-01-19 | 2026-03-24 | 2 |
| 151 | PR | [chore(deps): update safety requirement from <3.0.0 to <4.0.0](https://github.com/HKUDS/DeepTutor/pull/151) | closed | 2026-01-19 | 2026-03-24 | 2 |
| 152 | PR | [chore(deps): bump the npm-minor-patch group in /web with 5 updates](https://github.com/HKUDS/DeepTutor/pull/152) | closed | 2026-01-19 | 2026-01-26 | 2 |
| 153 | PR | [chore(deps): update numpy requirement from <2.0.0,>=1.24.0 to >=1.24.0,<3.0.0](https://github.com/HKUDS/DeepTutor/pull/153) | closed | 2026-01-19 | 2026-03-24 | 2 |
| 154 | Issue | [[Bug]:Fix: ReferenceError: prevStageRef is not defined in ResearchDashboard.tsx](https://github.com/HKUDS/DeepTutor/issues/154) | closed | 2026-01-19 | 2026-01-19 | 1 |
| 155 | Issue | [[Feature Request]: 添加支持类似S3 的Object Storage](https://github.com/HKUDS/DeepTutor/issues/155) | closed | 2026-01-19 | 2026-01-22 | 1 |
| 156 | Issue | [[Bug]: Azure OpenAI still can't work](https://github.com/HKUDS/DeepTutor/issues/156) | closed | 2026-01-19 | 2026-01-20 | 1 |
| 157 | PR | [feat(math_solver): add mathematical solver tool with tests](https://github.com/HKUDS/DeepTutor/pull/157) | closed | 2026-01-19 | 2026-04-07 | 2 |
| 158 | Issue | [[Bug]: RAG Searching always use llama_index even RAG was set to raganything](https://github.com/HKUDS/DeepTutor/issues/158) | closed | 2026-01-20 | 2026-01-21 | 2 |
| 159 | Issue | [[Bug]: Reporting generation failed during write_introduction, when azure openai gpt-5-mini model was used](https://github.com/HKUDS/DeepTutor/issues/159) | closed | 2026-01-20 | 2026-04-07 | 4 |
| 160 | Issue | [[Feature Request]:Support for Copilot API](https://github.com/HKUDS/DeepTutor/issues/160) | closed | 2026-01-20 | 2026-01-22 | 1 |
| 161 | Issue | [[Bug]:](https://github.com/HKUDS/DeepTutor/issues/161) | closed | 2026-01-21 | 2026-01-22 | 2 |
| 162 | Issue | [[Bug]: Incorrect image architecture for latest tag: AMD64 users forced to use version-specific tag](https://github.com/HKUDS/DeepTutor/issues/162) | closed | 2026-01-21 | 2026-01-22 | 1 |
| 163 | Issue | [[Bug]:对已有知识库再上传文件会报错](https://github.com/HKUDS/DeepTutor/issues/163) | closed | 2026-01-21 | 2026-01-24 | 4 |
| 164 | Issue | [[Bug]:](https://github.com/HKUDS/DeepTutor/issues/164) | closed | 2026-01-21 | 2026-01-22 | 1 |
| 165 | PR | [Feat/strengthen llm support](https://github.com/HKUDS/DeepTutor/pull/165) | closed | 2026-01-22 | 2026-02-03 | 0 |
| 166 | PR | [Feat/llm harden](https://github.com/HKUDS/DeepTutor/pull/166) | closed | 2026-01-22 | 2026-02-03 | 0 |
| 167 | Issue | [DeepTutor共创团队招募啦！](https://github.com/HKUDS/DeepTutor/issues/167) | closed | 2026-01-22 | 2026-04-07 | 1 |
| 168 | Issue | [[Bug]: MinerU TypeError: 'int' object is not subscriptable](https://github.com/HKUDS/DeepTutor/issues/168) | closed | 2026-01-23 | 2026-04-07 | 1 |
| 169 | PR | [chore: update repo roster images [skip ci]](https://github.com/HKUDS/DeepTutor/pull/169) | closed | 2026-01-24 | 2026-01-24 | 0 |
| 170 | Issue | [[Bug]:在已有知识库再上传文件出错：Failed to load resource: the server responded with a status of 413 (Request Entity Too Large)](https://github.com/HKUDS/DeepTutor/issues/170) | closed | 2026-01-24 | 2026-04-07 | 2 |
| 171 | Issue | [[Feature Request]: Flash Cards](https://github.com/HKUDS/DeepTutor/issues/171) | closed | 2026-01-24 | 2026-08-04 | 4 |
| 172 | Issue | [[Feature Request]:Adding support for arabic language](https://github.com/HKUDS/DeepTutor/issues/172) | closed | 2026-01-24 | 2026-04-11 | 1 |
| 173 | Issue | [[Feature Request]: General ideas](https://github.com/HKUDS/DeepTutor/issues/173) | closed | 2026-01-25 | 2026-10-12 | 5 |
| 174 | Issue | [[Bug]:knowledge还是用不了](https://github.com/HKUDS/DeepTutor/issues/174) | closed | 2026-01-25 | 2026-04-07 | 1 |
| 175 | PR | [fix:CoWriterEditor scroll sync](https://github.com/HKUDS/DeepTutor/pull/175) | closed | 2026-01-25 | 2026-01-25 | 1 |
| 176 | PR | [Fix/i18n improvement](https://github.com/HKUDS/DeepTutor/pull/176) | closed | 2026-01-25 | 2026-01-27 | 1 |
| 177 | Issue | [[Question]:为什么我api接入后他这个依旧不能回答我的问题？](https://github.com/HKUDS/DeepTutor/issues/177) | closed | 2026-01-25 | 2026-04-07 | 1 |
| 178 | PR | [chore(deps): bump the npm-minor-patch group across 1 directory with 7 updates](https://github.com/HKUDS/DeepTutor/pull/178) | closed | 2026-01-26 | 2026-02-02 | 2 |
| 179 | Issue | [[Bug]:创意生成无法显示结果](https://github.com/HKUDS/DeepTutor/issues/179) | closed | 2026-01-26 | 2026-04-08 | 3 |
| 180 | Issue | [[Feature Request]: Multimodal Learning Representations & Personalization Pipeline](https://github.com/HKUDS/DeepTutor/issues/180) | open | 2026-01-26 | 2026-04-28 | 2 |
| 182 | Issue | [[Bug]:仿真试卷模式生成题目时报错（可能是文件目录错误）](https://github.com/HKUDS/DeepTutor/issues/182) | closed | 2026-01-28 | 2026-04-07 | 2 |
| 183 | PR | [Feature/llm hardening core slim (#52)](https://github.com/HKUDS/DeepTutor/pull/183) | closed | 2026-01-29 | 2026-01-30 | 1 |
| 184 | PR | [docs: update ru translate](https://github.com/HKUDS/DeepTutor/pull/184) | closed | 2026-01-29 | 2026-01-30 | 1 |
| 185 | Issue | [[Feature Request]:](https://github.com/HKUDS/DeepTutor/issues/185) | open | 2026-01-30 | 2026-04-10 | 1 |
| 186 | PR | [Integrate local fixes and configurations](https://github.com/HKUDS/DeepTutor/pull/186) | closed | 2026-02-01 | 2026-02-15 | 1 |
| 187 | PR | [chore(deps): bump the npm-minor-patch group across 1 directory with 11 updates](https://github.com/HKUDS/DeepTutor/pull/187) | closed | 2026-02-02 | 2026-02-09 | 2 |
| 188 | Issue | [[Bug]: LLM 报错 Failed to fetch](https://github.com/HKUDS/DeepTutor/issues/188) | closed | 2026-02-03 | 2026-02-03 | 0 |
| 189 | PR | [feat/vision_slover](https://github.com/HKUDS/DeepTutor/pull/189) | closed | 2026-02-03 | 2026-02-03 | 0 |
| 190 | PR | [feat/vision_slover](https://github.com/HKUDS/DeepTutor/pull/190) | closed | 2026-02-03 | 2026-02-03 | 0 |
| 191 | PR | [feat/vision_slover](https://github.com/HKUDS/DeepTutor/pull/191) | closed | 2026-02-03 | 2026-03-09 | 1 |
| 192 | PR | [chore(deps): bump the npm-minor-patch group across 1 directory with 13 updates](https://github.com/HKUDS/DeepTutor/pull/192) | closed | 2026-02-09 | 2026-02-16 | 2 |
| 193 | Issue | [[Bug]:因为错误导致知识库查询失败后，即使错误修复，使用相同的查询词也会继续失败](https://github.com/HKUDS/DeepTutor/issues/193) | closed | 2026-02-09 | 2026-04-07 | 1 |
| 194 | PR | [feat: Add OpenRouter search provider](https://github.com/HKUDS/DeepTutor/pull/194) | closed | 2026-02-10 | 2026-02-15 | 1 |
| 195 | PR | [adapt nginx server name  deployment ( deployment adaption )](https://github.com/HKUDS/DeepTutor/pull/195) | closed | 2026-02-11 | 2026-04-07 | 2 |
| 196 | PR | [Restrict code execution scope and enforce import whitelist](https://github.com/HKUDS/DeepTutor/pull/196) | closed | 2026-02-12 | 2026-02-15 | 1 |
| 197 | Issue | [[Bug]:docker环境部署下添加新的LLM配置时，测试连接成功，但保存后再次测试报错，编辑配置时API Key输入框为空，实际配置已写入`data/user/settings/llm_configs.json`。](https://github.com/HKUDS/DeepTutor/issues/197) | closed | 2026-02-15 | 2026-04-07 | 1 |
| 198 | PR | [chore(deps): bump the npm-minor-patch group across 1 directory with 14 updates](https://github.com/HKUDS/DeepTutor/pull/198) | closed | 2026-02-16 | 2026-02-23 | 2 |
| 199 | Issue | [[Feature Request] Add a short "long-horizon reasoning & safety checklist" doc (docs only)](https://github.com/HKUDS/DeepTutor/issues/199) | open | 2026-02-19 | 2026-03-05 | 1 |
| 200 | PR | [Claude/deeptutor news integration okk up](https://github.com/HKUDS/DeepTutor/pull/200) | closed | 2026-02-20 | 2026-02-20 | 0 |
| 201 | PR | [merge student-simulation](https://github.com/HKUDS/DeepTutor/pull/201) | closed | 2026-02-21 | 2026-03-24 | 0 |
| 202 | PR | [chore(deps): bump the npm-minor-patch group across 1 directory with 15 updates](https://github.com/HKUDS/DeepTutor/pull/202) | closed | 2026-02-23 | 2026-03-09 | 2 |
| 203 | PR | [fix(api): resolve HTTP 413 on file uploads larger than 1 MB](https://github.com/HKUDS/DeepTutor/pull/203) | closed | 2026-02-23 | 2026-02-23 | 1 |
| 204 | PR | [fix(api): resolve HTTP 413 on file uploads larger than 1 MB](https://github.com/HKUDS/DeepTutor/pull/204) | closed | 2026-02-23 | 2026-04-07 | 1 |
| 205 | PR | [fix: replace 16 bare excepts with except Exception across 9 files](https://github.com/HKUDS/DeepTutor/pull/205) | closed | 2026-02-25 | 2026-04-07 | 1 |
| 206 | PR | [feat(web): streamline notebook studio direct entry defaults](https://github.com/HKUDS/DeepTutor/pull/206) | closed | 2026-02-26 | 2026-02-26 | 0 |
| 207 | PR | [Codex/notebook back navigationfix(web): add notebook-scoped back navigation for question and guide pages](https://github.com/HKUDS/DeepTutor/pull/207) | closed | 2026-02-26 | 2026-02-26 | 0 |
| 208 | Issue | [[Question]:LLM配置测试连接失败](https://github.com/HKUDS/DeepTutor/issues/208) | closed | 2026-03-02 | 2026-03-02 | 1 |
| 209 | PR | [chore(deps): bump docker/setup-qemu-action from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/209) | closed | 2026-03-09 | 2026-03-24 | 2 |
| 210 | PR | [chore(deps): bump the npm-minor-patch group across 1 directory with 16 updates](https://github.com/HKUDS/DeepTutor/pull/210) | closed | 2026-03-09 | 2026-03-24 | 2 |
| 211 | PR | [Merge 2.0-beta](https://github.com/HKUDS/DeepTutor/pull/211) | closed | 2026-03-09 | 2026-04-07 | 0 |
| 212 | PR | [feat: add zhipu_ocr and remove knowledgebase](https://github.com/HKUDS/DeepTutor/pull/212) | closed | 2026-03-09 | 2026-04-07 | 1 |
| 213 | PR | [ok](https://github.com/HKUDS/DeepTutor/pull/213) | closed | 2026-03-09 | 2026-03-09 | 0 |
| 214 | PR | [feat: add MiniMax as first-class LLM provider](https://github.com/HKUDS/DeepTutor/pull/214) | closed | 2026-03-19 | 2026-04-07 | 1 |
| 215 | PR | [feat: add Novita AI as LLM and embedding provider](https://github.com/HKUDS/DeepTutor/pull/215) | closed | 2026-03-22 | 2026-03-26 | 0 |
| 216 | PR | [Sync original](https://github.com/HKUDS/DeepTutor/pull/216) | closed | 2026-03-23 | 2026-03-23 | 0 |
| 217 | PR | [feat: implement SubprocessGuard for enhanced execution safety #185](https://github.com/HKUDS/DeepTutor/pull/217) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 218 | PR | [feat: implement UserIsolationManager for multi-user support #73](https://github.com/HKUDS/DeepTutor/pull/218) | closed | 2026-03-24 | 2026-04-07 | 3 |
| 219 | PR | [feat: implement Arabic language and RTL support #172](https://github.com/HKUDS/DeepTutor/pull/219) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 220 | PR | [docs: implement reasoning and safety checklist #199](https://github.com/HKUDS/DeepTutor/pull/220) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 221 | PR | [feat: implement Flash Card generation for active study #171](https://github.com/HKUDS/DeepTutor/pull/221) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 222 | PR | [feat: implement Arabic language and RTL support v2 #172](https://github.com/HKUDS/DeepTutor/pull/222) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 223 | PR | [feat: implement MultimodalPipeline for personalized adaptive learning #180](https://github.com/HKUDS/DeepTutor/pull/223) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 224 | PR | [feat: implement KnowledgeTracer for deep subject-agnostic mastery #173](https://github.com/HKUDS/DeepTutor/pull/224) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 225 | PR | [feat: implement enhanced Markdown table editing #65](https://github.com/HKUDS/DeepTutor/pull/225) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 226 | Issue | [[Bug]:使用翻译插件后报错](https://github.com/HKUDS/DeepTutor/issues/226) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 227 | Issue | [[Feature Request]:Feature Request: Add Simple Login Page](https://github.com/HKUDS/DeepTutor/issues/227) | closed | 2026-03-24 | 2026-05-07 | 2 |
| 228 | PR | [feat: implement high-fidelity SimulationEngine for practice #173](https://github.com/HKUDS/DeepTutor/pull/228) | closed | 2026-03-24 | 2026-04-07 | 1 |
| 229 | PR | [chore(deps): bump docker/setup-buildx-action from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/229) | closed | 2026-03-30 | 2026-04-05 | 2 |
| 230 | PR | [chore(deps): bump actions/configure-pages from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/230) | closed | 2026-03-30 | 2026-04-04 | 2 |
| 231 | PR | [chore(deps): bump actions/deploy-pages from 4 to 5](https://github.com/HKUDS/DeepTutor/pull/231) | closed | 2026-03-30 | 2026-04-04 | 2 |
| 232 | PR | [chore(deps): bump the npm-minor-patch group in /web with 13 updates](https://github.com/HKUDS/DeepTutor/pull/232) | closed | 2026-03-30 | 2026-04-05 | 2 |
| 233 | PR | [chore(deps): bump lucide-react from 0.562.0 to 1.7.0 in /web](https://github.com/HKUDS/DeepTutor/pull/233) | closed | 2026-03-30 | 2026-04-05 | 2 |
| 234 | PR | [chore(deps): bump typescript from 5.9.3 to 6.0.2 in /web](https://github.com/HKUDS/DeepTutor/pull/234) | closed | 2026-03-30 | 2026-04-05 | 2 |
| 235 | PR | [chore(deps): bump eslint from 9.39.2 to 10.1.0 in /web](https://github.com/HKUDS/DeepTutor/pull/235) | closed | 2026-03-30 | 2026-04-05 | 2 |
| 236 | PR | [chore(deps): bump i18next from 25.8.0 to 26.0.1 in /web](https://github.com/HKUDS/DeepTutor/pull/236) | closed | 2026-03-30 | 2026-04-05 | 2 |
| 238 | PR | [Let's meet DeepTutor 1.0.0!](https://github.com/HKUDS/DeepTutor/pull/238) | closed | 2026-04-04 | 2026-04-04 | 0 |
| 239 | PR | [update tag](https://github.com/HKUDS/DeepTutor/pull/239) | closed | 2026-04-04 | 2026-04-04 | 0 |
| 240 | PR | [fix(api): resolve HTTP 413 on file uploads larger than 1 MB](https://github.com/HKUDS/DeepTutor/pull/240) | closed | 2026-04-05 | 2026-04-07 | 1 |
| 241 | PR | [chore(deps): bump docker/build-push-action from 6 to 7](https://github.com/HKUDS/DeepTutor/pull/241) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 242 | PR | [chore(deps): bump docker/login-action from 3 to 4](https://github.com/HKUDS/DeepTutor/pull/242) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 243 | PR | [chore(deps): bump docker/metadata-action from 5 to 6](https://github.com/HKUDS/DeepTutor/pull/243) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 244 | PR | [chore(deps): bump the npm-minor-patch group in /web with 13 updates](https://github.com/HKUDS/DeepTutor/pull/244) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 245 | PR | [chore(deps): bump i18next from 25.8.0 to 26.0.3 in /web](https://github.com/HKUDS/DeepTutor/pull/245) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 246 | PR | [chore(deps): bump eslint from 9.39.2 to 10.2.0 in /web](https://github.com/HKUDS/DeepTutor/pull/246) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 247 | PR | [chore(deps): bump react-i18next from 16.5.3 to 17.0.2 in /web](https://github.com/HKUDS/DeepTutor/pull/247) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 248 | PR | [chore(deps): update chardet requirement from <6.0.0,>=3.0.2 to >=3.0.2,<8.0.0](https://github.com/HKUDS/DeepTutor/pull/248) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 249 | PR | [chore(deps): bump tailwindcss from 3.4.19 to 4.2.2 in /web](https://github.com/HKUDS/DeepTutor/pull/249) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 250 | PR | [fix(question-generator): support nested MinerU output in mimic mode](https://github.com/HKUDS/DeepTutor/pull/250) | closed | 2026-04-06 | 2026-04-07 | 3 |
| 251 | PR | [fix(deps): gate oauth-cli-kit to Python 3.11+](https://github.com/HKUDS/DeepTutor/pull/251) | closed | 2026-04-06 | 2026-04-07 | 0 |
| 252 | PR | [feat: add optional authentication with login, registration, and admin dashboard](https://github.com/HKUDS/DeepTutor/pull/252) | closed | 2026-04-06 | 2026-04-25 | 6 |
| 253 | PR | [fix: add missing imports for mimic websocket router](https://github.com/HKUDS/DeepTutor/pull/253) | closed | 2026-04-06 | 2026-04-07 | 0 |
| 254 | PR | [fix: invalidate runtime caches after settings changes](https://github.com/HKUDS/DeepTutor/pull/254) | closed | 2026-04-06 | 2026-04-07 | 0 |
| 255 | Issue | [[Bug]: Missing sys and Path imports crash mimic WebSocket endpoint](https://github.com/HKUDS/DeepTutor/issues/255) | closed | 2026-04-06 | 2026-04-07 | 2 |
| 256 | PR | [Fix Windows compatibility for Math Animator renderer](https://github.com/HKUDS/DeepTutor/pull/256) | closed | 2026-04-07 | 2026-04-08 | 1 |
| 257 | PR | [Enhance locate_agent prompt and improve agent features and UI](https://github.com/HKUDS/DeepTutor/pull/257) | closed | 2026-04-07 | 2026-04-07 | 1 |
| 258 | Issue | [[Bug]:’utf-8' codec can't decode](https://github.com/HKUDS/DeepTutor/issues/258) | closed | 2026-04-07 | 2026-04-07 | 1 |
| 259 | PR | [fix(start-tour): tolerate non-UTF-8 subprocess output](https://github.com/HKUDS/DeepTutor/pull/259) | closed | 2026-04-07 | 2026-04-07 | 3 |
| 261 | Issue | [[Bug]: `deeptutor provider login github-copilot` is documented as OAuth login, but it only sends a test completion request](https://github.com/HKUDS/DeepTutor/issues/261) | closed | 2026-04-07 | 2026-04-08 | 1 |
| 262 | PR | [docs: clarify github copilot provider login semantics](https://github.com/HKUDS/DeepTutor/pull/262) | closed | 2026-04-07 | 2026-04-08 | 1 |
| 263 | PR | [fix: use parse_json_response for LLM outputs to handle markdown fences](https://github.com/HKUDS/DeepTutor/pull/263) | closed | 2026-04-08 | 2026-04-08 | 1 |
| 264 | Issue | [Repository analysis: features, architecture, workflow, security, and structural visualization](https://github.com/HKUDS/DeepTutor/issues/264) | closed | 2026-04-08 | 2026-04-08 | 1 |
| 265 | Issue | [TutorBot + Feishu: 阿里云百炼 Coding Plan 端点 tool calling 返回 InvalidParameter 错误](https://github.com/HKUDS/DeepTutor/issues/265) | closed | 2026-04-08 | 2026-04-08 | 0 |
| 266 | PR | [fix: Windows compatibility + Guided Learning improvements](https://github.com/HKUDS/DeepTutor/pull/266) | closed | 2026-04-08 | 2026-04-08 | 3 |
| 267 | PR | [fix: enable streaming for tool-calling to fix Bailian Coding Plan endpoint errors](https://github.com/HKUDS/DeepTutor/pull/267) | closed | 2026-04-08 | 2026-04-08 | 1 |
| 268 | PR | [fix: embedding progress tracking + 429 rate limit retry](https://github.com/HKUDS/DeepTutor/pull/268) | closed | 2026-04-08 | 2026-04-09 | 2 |
| 269 | Issue | [[Question]: ЕSG Playbook for CEO in Armenia](https://github.com/HKUDS/DeepTutor/issues/269) | closed | 2026-04-09 | 2026-04-09 | 1 |
| 270 | PR | [Update README.md](https://github.com/HKUDS/DeepTutor/pull/270) | closed | 2026-04-09 | 2026-04-09 | 1 |
| 271 | Issue | [bug: mimetypes.guess_type() uses original case filename causing inconsistent MIME validation in DocumentValidator](https://github.com/HKUDS/DeepTutor/issues/271) | closed | 2026-04-09 | 2026-04-09 | 2 |
| 272 | PR | [fix: use lowercased filename in mimetypes.guess_type() for consistent MIME validation](https://github.com/HKUDS/DeepTutor/pull/272) | closed | 2026-04-09 | 2026-04-09 | 1 |
| 273 | Issue | [[Feature Request]: select or switch LLM models depending on the use case](https://github.com/HKUDS/DeepTutor/issues/273) | closed | 2026-04-09 | 2026-05-03 | 2 |
| 274 | Issue | [Bug: uses_max_completion_tokens() misses o4-mini and o4 models, causing API errors](https://github.com/HKUDS/DeepTutor/issues/274) | closed | 2026-04-10 | 2026-04-10 | 1 |
| 275 | PR | [fix: extend o-series regex to cover o4-mini and future o-series models](https://github.com/HKUDS/DeepTutor/pull/275) | closed | 2026-04-10 | 2026-04-10 | 1 |
| 276 | Issue | [💡 Proposal: Open Source Growth Strategy for DeepTutor v1.0.0](https://github.com/HKUDS/DeepTutor/issues/276) | closed | 2026-04-10 | 2026-04-10 | 2 |
| 277 | Issue | [[Bug]: LaTeX math expressions are not rendered correctly in chat UI](https://github.com/HKUDS/DeepTutor/issues/277) | closed | 2026-04-10 | 2026-04-10 | 2 |
| 278 | Issue | [[Bug]:MiniMax-M2.7 Model Compatibility Issue with Guided Learning](https://github.com/HKUDS/DeepTutor/issues/278) | closed | 2026-04-10 | 2026-04-10 | 2 |
| 279 | Issue | [[Feature Request]: rethink knowlage base on a scaleable way](https://github.com/HKUDS/DeepTutor/issues/279) | open | 2026-04-10 | 2026-04-10 | 1 |
| 280 | Issue | [[Bug]: All question generated in quiz are the same](https://github.com/HKUDS/DeepTutor/issues/280) | closed | 2026-04-10 | 2026-04-10 | 0 |
| 281 | PR | [Prevent duplicate quiz questions by removing duplicates and adding history](https://github.com/HKUDS/DeepTutor/pull/281) | closed | 2026-04-10 | 2026-04-10 | 1 |
| 282 | PR | [test_base_agent_binding.py](https://github.com/HKUDS/DeepTutor/pull/282) | closed | 2026-04-10 | 2026-04-10 | 1 |
| 283 | PR | [test_openrouter_provider.py](https://github.com/HKUDS/DeepTutor/pull/283) | closed | 2026-04-10 | 2026-04-10 | 1 |
| 284 | Issue | [[Bug]: Cannot configure Azure OpenAI LLM](https://github.com/HKUDS/DeepTutor/issues/284) | closed | 2026-04-10 | 2026-04-11 | 4 |
| 285 | PR | [fix(core): Resolve o4 model token bug & deeply enhance core test suite coverage](https://github.com/HKUDS/DeepTutor/pull/285) | closed | 2026-04-10 | 2026-04-11 | 1 |
| 286 | PR | [fix: add auto-fallback for search providers without templates](https://github.com/HKUDS/DeepTutor/pull/286) | closed | 2026-04-11 | 2026-04-11 | 1 |
| 287 | PR | [v1.0.2](https://github.com/HKUDS/DeepTutor/pull/287) | closed | 2026-04-11 | 2026-04-11 | 0 |
| 288 | PR | [feat: Add OpenAI Codex Provider & improve LaTeX rendering](https://github.com/HKUDS/DeepTutor/pull/288) | closed | 2026-04-11 | 2026-04-14 | 6 |
| 289 | Issue | [[BUG] FileNotFoundError on Python 3.14+ when running start_tour.py](https://github.com/HKUDS/DeepTutor/issues/289) | closed | 2026-04-11 | 2026-04-12 | 2 |
| 290 | PR | [fix: resolve FileNotFoundError on Python 3.14+ in start_tour.py](https://github.com/HKUDS/DeepTutor/pull/290) | closed | 2026-04-11 | 2026-04-12 | 2 |
| 291 | PR | [feat: add Korean (ko) language support](https://github.com/HKUDS/DeepTutor/pull/291) | closed | 2026-04-11 | 2026-05-28 | 1 |
| 292 | PR | [feat: add wrong-answer note for cross-session quiz review](https://github.com/HKUDS/DeepTutor/pull/292) | closed | 2026-04-11 | 2026-04-12 | 1 |
| 293 | Issue | [[Feature Request]: Rigid Knowledge Architecture and Workflow Limitations in Notebook and Record Management](https://github.com/HKUDS/DeepTutor/issues/293) | closed | 2026-04-11 | 2026-04-22 | 4 |
| 294 | PR | [fix: merge system messages to comply with Qwen vLLM chat template](https://github.com/HKUDS/DeepTutor/pull/294) | closed | 2026-04-11 | 2026-04-11 | 1 |
| 295 | PR | [fix: merge system messages and add history reference fallback](https://github.com/HKUDS/DeepTutor/pull/295) | closed | 2026-04-11 | 2026-04-12 | 1 |
| 296 | Issue | [[Bug]:LLM 0, EMBEDDING 0, SEARCH 0](https://github.com/HKUDS/DeepTutor/issues/296) | closed | 2026-04-12 | 2026-04-22 | 6 |
| 297 | PR | [feat: integrate LightRAG pipeline, Mermaid diagrams, and Liquid Glass…](https://github.com/HKUDS/DeepTutor/pull/297) | closed | 2026-04-12 | 2026-04-12 | 2 |
| 298 | PR | [feat:Added goal-oriented learning with constraints and high-frequency key point extraction.](https://github.com/HKUDS/DeepTutor/pull/298) | open | 2026-04-12 | 2026-08-02 | 5 |
| 299 | PR | [feat: detect embedding model mismatch in knowledge bases](https://github.com/HKUDS/DeepTutor/pull/299) | closed | 2026-04-12 | 2026-04-12 | 0 |
| 300 | Issue | [[Question]: Docs appear out of sync with current config and KB behavior](https://github.com/HKUDS/DeepTutor/issues/300) | closed | 2026-04-12 | 2026-04-12 | 1 |
| 301 | Issue | [[Bug?!]: DeepTutor “Guided Learning” Not Working with LM Studio (Docker Deployment)](https://github.com/HKUDS/DeepTutor/issues/301) | closed | 2026-04-12 | 2026-05-28 | 24 |
| 302 | PR | [fix: resolve FileNotFoundError crash on setup script in Python 3.14](https://github.com/HKUDS/DeepTutor/pull/302) | closed | 2026-04-12 | 2026-04-12 | 1 |
| 303 | PR | [chore: stabilize testing pipeline and clean up technical debt](https://github.com/HKUDS/DeepTutor/pull/303) | closed | 2026-04-12 | 2026-04-18 | 2 |
| 304 | Issue | [[Feature Request]: Add HNSW index and Rerank support for scalable retrieval](https://github.com/HKUDS/DeepTutor/issues/304) | open | 2026-04-13 | 2026-04-14 | 1 |
| 305 | PR | [docs: add long-horizon reasoning and safety checklist](https://github.com/HKUDS/DeepTutor/pull/305) | closed | 2026-04-13 | 2026-04-14 | 2 |
| 306 | PR | [fix: pass extra_headers to llm_complete in config test runner](https://github.com/HKUDS/DeepTutor/pull/306) | closed | 2026-04-13 | 2026-04-13 | 1 |
| 307 | PR | [fix: pass extra_headers to llm_complete in config test runner](https://github.com/HKUDS/DeepTutor/pull/307) | closed | 2026-04-13 | 2026-04-14 | 1 |
| 308 | Issue | [Bug: Custom extra_headers ignored during model connection test](https://github.com/HKUDS/DeepTutor/issues/308) | closed | 2026-04-13 | 2026-04-14 | 1 |
| 309 | PR | [fix: handle npm.cmd correctly on Windows](https://github.com/HKUDS/DeepTutor/pull/309) | closed | 2026-04-13 | 2026-04-14 | 0 |
| 310 | PR | [fix: prefer unresolved sys.executable to stay inside venv](https://github.com/HKUDS/DeepTutor/pull/310) | closed | 2026-04-13 | 2026-04-14 | 1 |
| 311 | PR | [Feature/passive agent](https://github.com/HKUDS/DeepTutor/pull/311) | closed | 2026-04-13 | 2026-04-13 | 0 |
| 312 | Issue | [[Question]:  how to reindex a existing knowledge base after change embedded model](https://github.com/HKUDS/DeepTutor/issues/312) | closed | 2026-04-14 | 2026-04-15 | 3 |
| 313 | Issue | [[Feature Request]:python venv use [uv]](https://github.com/HKUDS/DeepTutor/issues/313) | closed | 2026-04-14 | 2026-04-14 | 0 |
| 314 | Issue | [[Bug]: Dependency resolution fails on Windows 11 with UV — oauth-cli-kit>=0.2.0 does not exist on PyPI](https://github.com/HKUDS/DeepTutor/issues/314) | closed | 2026-04-14 | 2026-04-14 | 2 |
| 315 | PR | [fix: oauth-cli-kit>=0.2.0 does not exist, lower to >=0.1.1](https://github.com/HKUDS/DeepTutor/pull/315) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 316 | Issue | [[Question]: Why was the Serper search provider deprecated in f377913?](https://github.com/HKUDS/DeepTutor/issues/316) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 317 | Issue | [[Bug]: Severe input lag in chatbox during long conversations](https://github.com/HKUDS/DeepTutor/issues/317) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 319 | PR | [perf(web): fix severe input lag in long conversations (#317)](https://github.com/HKUDS/DeepTutor/pull/319) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 320 | PR | [Fix typo: Chinses -> Chinese](https://github.com/HKUDS/DeepTutor/pull/320) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 321 | PR | [feat(diagnostics): make LLM probe max_tokens configurable via env](https://github.com/HKUDS/DeepTutor/pull/321) | closed | 2026-04-14 | 2026-04-14 | 0 |
| 322 | PR | [fix(embedding): skip `dimensions` for models that don't support matryoshka](https://github.com/HKUDS/DeepTutor/pull/322) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 323 | PR | [fix(web): improve robust parsing for LaTeX block math and headings](https://github.com/HKUDS/DeepTutor/pull/323) | closed | 2026-04-14 | 2026-04-14 | 2 |
| 324 | Issue | [[Bug]: Error: [local] deeptutor.services.llm.executors.sdk_complete() got multiple values for keyword argument 'extra_headers'](https://github.com/HKUDS/DeepTutor/issues/324) | closed | 2026-04-14 | 2026-04-14 | 1 |
| 325 | PR | [fix(embedding): drop `dimensions` on HTTP 400 and latch on success](https://github.com/HKUDS/DeepTutor/pull/325) | closed | 2026-04-14 | 2026-04-17 | 1 |
| 326 | Issue | [[Question]: How to fix the Rag error ?](https://github.com/HKUDS/DeepTutor/issues/326) | closed | 2026-04-15 | 2026-04-18 | 2 |
| 329 | PR | [feat: Add Structure Note with VectifyAI PageIndex](https://github.com/HKUDS/DeepTutor/pull/329) | open | 2026-04-15 | 2026-09-10 | 0 |
| 330 | PR | [fix(web): resolve 15 npm security vulnerabilities](https://github.com/HKUDS/DeepTutor/pull/330) | closed | 2026-04-15 | 2026-04-17 | 1 |
| 331 | Issue | [[Bug]: TutorBot channel config wiped on every server restart](https://github.com/HKUDS/DeepTutor/issues/331) | closed | 2026-04-15 | 2026-04-18 | 2 |
| 332 | PR | [Fix: TutorBot channel config wiped on every server restart](https://github.com/HKUDS/DeepTutor/pull/332) | closed | 2026-04-15 | 2026-04-17 | 1 |
| 333 | Issue | [[Feature Request]: Add UI for configuring TutorBot channels (Telegram, Slack, etc.)](https://github.com/HKUDS/DeepTutor/issues/333) | closed | 2026-04-15 | 2026-04-22 | 3 |
| 334 | Issue | [[Bug]:Unable to Save To Notebook](https://github.com/HKUDS/DeepTutor/issues/334) | closed | 2026-04-16 | 2026-04-17 | 3 |
| 335 | PR | [fix(api): add missing http_version arg in selective_access_log middleware](https://github.com/HKUDS/DeepTutor/pull/335) | closed | 2026-04-17 | 2026-04-17 | 1 |
| 336 | PR | [feat: add optional authentication with login, registration, and admin dashboard](https://github.com/HKUDS/DeepTutor/pull/336) | closed | 2026-04-17 | 2026-05-04 | 2 |
| 337 | PR | [docs: add Thai README documentation](https://github.com/HKUDS/DeepTutor/pull/337) | closed | 2026-04-17 | 2026-04-18 | 1 |
| 338 | PR | [feat(tutorbot): Channels tab, Telegram UI, API channel reload, token …](https://github.com/HKUDS/DeepTutor/pull/338) | closed | 2026-04-17 | 2026-04-18 | 4 |
| 339 | Issue | [[Feature Request]:](https://github.com/HKUDS/DeepTutor/issues/339) | closed | 2026-04-18 | 2026-04-18 | 0 |
| 340 | PR | [Fix #296: [Bug]:LLM 0, EMBEDDING 0, SEARCH 0](https://github.com/HKUDS/DeepTutor/pull/340) | closed | 2026-04-18 | 2026-04-22 | 1 |
| 341 | PR | [release: v1.1.2 — CI fix & release notes cleanup](https://github.com/HKUDS/DeepTutor/pull/341) | closed | 2026-04-18 | 2026-04-18 | 0 |
| 343 | PR | [feat(i18n): add Russian (ru) locale](https://github.com/HKUDS/DeepTutor/pull/343) | closed | 2026-04-19 | 2026-05-28 | 1 |
| 344 | Issue | [[Bug]: response_format.type](https://github.com/HKUDS/DeepTutor/issues/344) | closed | 2026-04-19 | 2026-04-22 | 5 |
| 345 | PR | [fix: disable json_object response_format for gemma models](https://github.com/HKUDS/DeepTutor/pull/345) | closed | 2026-04-20 | 2026-04-20 | 2 |
| 346 | Issue | [[Bug]: LlamaIndex RAG pipeline: query-time retrieval fails with `TypeError: unsupported operand type(s) for *: 'NoneType' and 'float'`](https://github.com/HKUDS/DeepTutor/issues/346) | closed | 2026-04-20 | 2026-04-27 | 2 |
| 347 | PR | [fix(rag): guard against None embeddings in LlamaIndex pipeline](https://github.com/HKUDS/DeepTutor/pull/347) | closed | 2026-04-20 | 2026-04-20 | 0 |
| 348 | PR | [feat(chat): make per-stage token limits and temperature configurable via agents.yaml](https://github.com/HKUDS/DeepTutor/pull/348) | closed | 2026-04-20 | 2026-04-20 | 1 |
| 349 | PR | [feat(chat): regenerate last response (CLI, WebSocket, Web UI)](https://github.com/HKUDS/DeepTutor/pull/349) | closed | 2026-04-20 | 2026-04-20 | 1 |
| 350 | Issue | [[Question]:诚邀您加入 GitWatt 开源首发社区](https://github.com/HKUDS/DeepTutor/issues/350) | closed | 2026-04-20 | 2026-04-20 | 1 |
| 351 | Issue | [[Bug]: Residual input lag in TutorBot Chatbox (Follow-up to #317)](https://github.com/HKUDS/DeepTutor/issues/351) | closed | 2026-04-20 | 2026-04-24 | 10 |
| 352 | PR | [fix(web): ensure readable text in dark code blocks on light theme](https://github.com/HKUDS/DeepTutor/pull/352) | closed | 2026-04-20 | 2026-04-20 | 1 |
| 353 | PR | [fix: add ConnectError to embedding retry exceptions](https://github.com/HKUDS/DeepTutor/pull/353) | closed | 2026-04-20 | 2026-04-22 | 0 |
| 354 | PR | [fix : Tutorbot websocket resilience and CLI config parsing edge case](https://github.com/HKUDS/DeepTutor/pull/354) | closed | 2026-04-20 | 2026-04-22 | 0 |
| 355 | PR | [feat: Hide the API key on settings page](https://github.com/HKUDS/DeepTutor/pull/355) | closed | 2026-04-20 | 2026-04-22 | 0 |
| 356 | Issue | [[Question]:Chat interface does not return any response after submitting a question](https://github.com/HKUDS/DeepTutor/issues/356) | closed | 2026-04-21 | 2026-04-25 | 5 |
| 357 | Issue | [[Feature Request]:希望增加对话导出功能（支持导出 PDF 或图片，便于打印和分享）](https://github.com/HKUDS/DeepTutor/issues/357) | closed | 2026-04-21 | 2026-04-25 | 5 |
| 358 | Issue | [[Question]:Chat mode freezes mid-generation with "sqlite3.OperationalError: unable to open database file" on macOS](https://github.com/HKUDS/DeepTutor/issues/358) | closed | 2026-04-21 | 2026-04-22 | 2 |
| 359 | Issue | [[Question]:很难用，bug很多，动不动就出错，如果用docker部署会有很多坑，明明很简单的配置在这里变的无比复杂，根本不是给普通人用的，大家不要入坑。](https://github.com/HKUDS/DeepTutor/issues/359) | closed | 2026-04-21 | 2026-04-22 | 1 |
| 360 | PR | [perf(web): decouple chat input state to resolve lag in long conversat…](https://github.com/HKUDS/DeepTutor/pull/360) | closed | 2026-04-22 | 2026-04-22 | 1 |
| 361 | PR | [Perf/optimize chat input](https://github.com/HKUDS/DeepTutor/pull/361) | closed | 2026-04-22 | 2026-04-22 | 0 |
| 362 | PR | [Perf/optimize chat input](https://github.com/HKUDS/DeepTutor/pull/362) | closed | 2026-04-22 | 2026-04-22 | 0 |
| 363 | Issue | [[Bug]: Input background and text color ignore active theme in chats](https://github.com/HKUDS/DeepTutor/issues/363) | closed | 2026-04-22 | 2026-04-25 | 2 |
| 364 | Issue | [[Bug]:不能识别word文档，pdf文档，不能上传图片](https://github.com/HKUDS/DeepTutor/issues/364) | closed | 2026-04-22 | 2026-04-27 | 3 |
| 366 | Issue | [[Feature Request]:responsive design for mobile devices](https://github.com/HKUDS/DeepTutor/issues/366) | open | 2026-04-22 | 2026-04-23 | 2 |
| 367 | PR | [fix #366: addressing issue](https://github.com/HKUDS/DeepTutor/pull/367) | closed | 2026-04-22 | 2026-04-23 | 0 |
| 368 | PR | [fix(embedding): gate dimensions for text-embedding-3 models](https://github.com/HKUDS/DeepTutor/pull/368) | closed | 2026-04-23 | 2026-04-23 | 0 |
| 369 | Issue | [[Bug]:关于book功能页面的一些问题（Docker部署）](https://github.com/HKUDS/DeepTutor/issues/369) | closed | 2026-04-23 | 2026-04-24 | 3 |
| 370 | Issue | [[Bug]:无法删除某个知识库（Docker部署）](https://github.com/HKUDS/DeepTutor/issues/370) | closed | 2026-04-23 | 2026-04-24 | 4 |
| 371 | PR | [feat(cli): add add-md and replace-md commands to notebook group](https://github.com/HKUDS/DeepTutor/pull/371) | closed | 2026-04-23 | 2026-04-24 | 1 |
| 372 | Issue | [[Bug]: code and flash_cards`blocks fail during Book generation](https://github.com/HKUDS/DeepTutor/issues/372) | closed | 2026-04-23 | 2026-04-24 | 2 |
| 373 | PR | [feat: Revamp soul template creation and usage](https://github.com/HKUDS/DeepTutor/pull/373) | closed | 2026-04-23 | 2026-04-24 | 1 |
| 374 | PR | [Frictionless Onboarding](https://github.com/HKUDS/DeepTutor/pull/374) | closed | 2026-04-23 | 2026-04-25 | 1 |
| 375 | Issue | [[Feature Request]:References带出的内容需要做合规过滤](https://github.com/HKUDS/DeepTutor/issues/375) | open | 2026-04-24 | 2026-10-22 | 5 |
| 376 | PR | [fix(scripts): prefer uv pip over python -m pip in start_tour.py](https://github.com/HKUDS/DeepTutor/pull/376) | closed | 2026-04-24 | 2026-04-25 | 1 |
| 377 | Issue | [[Feature Request]:Add NVIDIA NIM API support](https://github.com/HKUDS/DeepTutor/issues/377) | closed | 2026-04-24 | 2026-08-04 | 2 |
| 378 | PR | [[ImgBot] Optimize images](https://github.com/HKUDS/DeepTutor/pull/378) | closed | 2026-04-24 | 2026-04-24 | 0 |
| 379 | PR | [docs: add Polish translation of README](https://github.com/HKUDS/DeepTutor/pull/379) | closed | 2026-04-24 | 2026-04-25 | 1 |
| 380 | Issue | [[Feature Request]: Add a Learning Experience Plugin SDK + first-party “Knowledge Garden” / “Concept Companion” learning layer](https://github.com/HKUDS/DeepTutor/issues/380) | open | 2026-04-24 | 2026-10-12 | 3 |
| 381 | PR | [fix: use npm.cmd for version detection on Windows](https://github.com/HKUDS/DeepTutor/pull/381) | closed | 2026-04-25 | 2026-04-25 | 0 |
| 382 | PR | [fix: restore theme-aware backgrounds for form elements and visualization](https://github.com/HKUDS/DeepTutor/pull/382) | closed | 2026-04-25 | 2026-04-25 | 1 |
| 383 | Issue | [[Bug]:1.2.3知识库是创建知识库，上传txt文档没有任何反应](https://github.com/HKUDS/DeepTutor/issues/383) | closed | 2026-04-25 | 2026-04-25 | 4 |
| 384 | Issue | [[Question]:当重新打开与辅导机器人的对话时，对话窗口直接在最上面，没有定位到会话的底部](https://github.com/HKUDS/DeepTutor/issues/384) | closed | 2026-04-25 | 2026-04-25 | 1 |
| 385 | Issue | [[Bug]:Docker 容器重启后 TutorBot Agent 随机处于停止状态，导致钉钉消息无法自动回复](https://github.com/HKUDS/DeepTutor/issues/385) | closed | 2026-04-25 | 2026-04-28 | 2 |
| 386 | Issue | [[Bug]:v1.2.4，创建知识库，上传markdown文档没有任何反应](https://github.com/HKUDS/DeepTutor/issues/386) | closed | 2026-04-25 | 2026-04-25 | 1 |
| 387 | Issue | [[Question]:清除Docker缓存，重新拉取镜像后，tutorbot 和 memory的资料未保留，不过聊天、书、知识库等板块记忆依旧保留](https://github.com/HKUDS/DeepTutor/issues/387) | closed | 2026-04-25 | 2026-04-25 | 1 |
| 388 | PR | [docs: add Polish language link to main README](https://github.com/HKUDS/DeepTutor/pull/388) | closed | 2026-04-25 | 2026-04-27 | 1 |
| 389 | Issue | [[Bug]:一个小bug](https://github.com/HKUDS/DeepTutor/issues/389) | closed | 2026-04-25 | 2026-04-27 | 1 |
| 390 | PR | [[codex] Normalize Azure OpenAI max token aliases](https://github.com/HKUDS/DeepTutor/pull/390) | closed | 2026-04-25 | 2026-05-28 | 1 |
| 391 | PR | [fix: server startup on Windows + missing runtime deps in server.txt](https://github.com/HKUDS/DeepTutor/pull/391) | closed | 2026-04-26 | 2026-04-27 | 1 |
| 392 | Issue | [[Bug]:failed to create a knowledge base (rag provider tested ok, docker log now error shown)](https://github.com/HKUDS/DeepTutor/issues/392) | closed | 2026-04-26 | 2026-04-27 | 3 |
| 393 | PR | [Fix/test pollution and math animator](https://github.com/HKUDS/DeepTutor/pull/393) | closed | 2026-04-26 | 2026-05-02 | 0 |
| 394 | Issue | [[Question]:在聊天界面，在中文输入法输入字的时候，直接回车，会把待打的字直接就发送出去。](https://github.com/HKUDS/DeepTutor/issues/394) | closed | 2026-04-26 | 2026-04-28 | 1 |
| 395 | Issue | [this issue was created in this repository by mistake](https://github.com/HKUDS/DeepTutor/issues/395) | closed | 2026-04-26 | 2026-04-26 | 1 |
| 396 | PR | [Improve mobile responsiveness](https://github.com/HKUDS/DeepTutor/pull/396) | closed | 2026-04-26 | 2026-05-25 | 0 |
| 397 | Issue | [[RFC]: 关于DeepTutor下一代Memory架构思考 \| Thoughts on DeerTutor's Next-Generation Memory Architecture](https://github.com/HKUDS/DeepTutor/issues/397) | open | 2026-04-26 | 2026-05-11 | 3 |
| 398 | Issue | [[Bug]: "Windows 启动报 UnicodeEncodeError"](https://github.com/HKUDS/DeepTutor/issues/398) | closed | 2026-04-26 | 2026-04-28 | 2 |
| 399 | Issue | [[Question]:Memory功能是否是实时总结？有时需要手动刷新两三次才总结并更新资料，甚至依旧不变。](https://github.com/HKUDS/DeepTutor/issues/399) | closed | 2026-04-26 | 2026-04-28 | 1 |
| 400 | Issue | [[Bug]: Failed to get valid JSON from LLM](https://github.com/HKUDS/DeepTutor/issues/400) | closed | 2026-04-26 | 2026-04-28 | 3 |
| 401 | Issue | [[Question]:能否配置个人本地化的数据库](https://github.com/HKUDS/DeepTutor/issues/401) | open | 2026-04-26 | 2026-05-12 | 1 |
| 402 | Issue | [[Bug]: Some Python libraries are not installing.](https://github.com/HKUDS/DeepTutor/issues/402) | closed | 2026-04-26 | 2026-04-27 | 4 |
| 403 | Issue | [[Feature Request]: Projects — Grouped Workspaces with Persistent Custom Instructions](https://github.com/HKUDS/DeepTutor/issues/403) | open | 2026-04-27 | 2026-08-28 | 4 |
| 404 | PR | [fix(research): use f-string in reporting_agent logger.warning call](https://github.com/HKUDS/DeepTutor/pull/404) | closed | 2026-04-27 | 2026-04-27 | 2 |
| 405 | Issue | [[Bug]:1.2.5版本在knowledge上传pdf文件没反应](https://github.com/HKUDS/DeepTutor/issues/405) | closed | 2026-04-27 | 2026-04-27 | 1 |
| 407 | PR | [doc: Link CLAUDE.md to AGENTS.md](https://github.com/HKUDS/DeepTutor/pull/407) | closed | 2026-04-27 | 2026-05-28 | 1 |
| 409 | PR | [refactor(storage): Add PostgreSQL support](https://github.com/HKUDS/DeepTutor/pull/409) | open | 2026-04-27 | 2026-08-02 | 0 |
| 410 | Issue | [[Bug]:1.3.0版知识库无法预览文件，显示“Failed to list files (404)”（Docker部署）](https://github.com/HKUDS/DeepTutor/issues/410) | closed | 2026-04-27 | 2026-04-28 | 3 |
| 411 | Issue | [[Question]:检索知识库总是失败，提示错误信息……](https://github.com/HKUDS/DeepTutor/issues/411) | closed | 2026-04-28 | 2026-04-28 | 3 |
| 412 | Issue | [[Question]: [deepseek] Error calling LLM: Error code: 404](https://github.com/HKUDS/DeepTutor/issues/412) | closed | 2026-04-28 | 2026-04-28 | 0 |
| 413 | Issue | [[Bug]:1.3.1版本memory刷新bug和knowledge bases 的re-index功能bug（Docker部署）](https://github.com/HKUDS/DeepTutor/issues/413) | closed | 2026-04-28 | 2026-04-30 | 4 |
| 414 | Issue | [[Bug]:生成book后，某些模块无法生成(Docker部署）](https://github.com/HKUDS/DeepTutor/issues/414) | closed | 2026-04-28 | 2026-04-30 | 3 |
| 415 | Issue | [[Question]:升级到1.3.1版本后，进行知识库检索，仍然失败，返回错误信息……](https://github.com/HKUDS/DeepTutor/issues/415) | closed | 2026-04-28 | 2026-04-30 | 6 |
| 416 | PR | [Fix stale embedding client during knowledge base indexing](https://github.com/HKUDS/DeepTutor/pull/416) | closed | 2026-04-28 | 2026-05-28 | 1 |
| 417 | Issue | [[Bug]:v1.2.5版本使用deepseek的api在进行辅导机器人聊天时出现参数传递报错](https://github.com/HKUDS/DeepTutor/issues/417) | closed | 2026-04-28 | 2026-04-29 | 2 |
| 418 | Issue | [[Bug]: kb_config.json status stuck at "processing" after indexing completes successfully](https://github.com/HKUDS/DeepTutor/issues/418) | closed | 2026-04-29 | 2026-04-30 | 1 |
| 420 | PR | [feat: add NVIDIA NIM provider with streaming support](https://github.com/HKUDS/DeepTutor/pull/420) | closed | 2026-04-29 | 2026-04-30 | 1 |
| 421 | PR | [fix: handle non-string message content in TutorBot chat](https://github.com/HKUDS/DeepTutor/pull/421) | closed | 2026-04-29 | 2026-05-06 | 1 |
| 422 | PR | [fix: Add C++ compiler prerequisite in readme](https://github.com/HKUDS/DeepTutor/pull/422) | closed | 2026-04-29 | 2026-04-30 | 2 |
| 423 | PR | [fix(deps): relax numpy upper bound to resolve manim conflict](https://github.com/HKUDS/DeepTutor/pull/423) | closed | 2026-04-29 | 2026-04-30 | 1 |
| 424 | PR | [feat(embedding): add Gemini embedding provider support across runtime](https://github.com/HKUDS/DeepTutor/pull/424) | closed | 2026-04-29 | 2026-04-30 | 1 |
| 425 | PR | [Claude/update docs after sync 4p zdz](https://github.com/HKUDS/DeepTutor/pull/425) | closed | 2026-04-30 | 2026-04-30 | 0 |
| 426 | Issue | [[Bug]: Embedding Error After Upgrading Deep Tutor from 1.2.5 to 1.3.2](https://github.com/HKUDS/DeepTutor/issues/426) | closed | 2026-04-30 | 2026-04-30 | 3 |
| 427 | Issue | [[Feature Request]: Suggestion: Improve Guide Learning](https://github.com/HKUDS/DeepTutor/issues/427) | closed | 2026-04-30 | 2026-05-01 | 2 |
| 428 | PR | [fix: fallback content to reasoning_content when DeepSeek returns empty content field](https://github.com/HKUDS/DeepTutor/pull/428) | closed | 2026-04-30 | 2026-05-04 | 1 |
| 429 | Issue | [[Feature Request]: add epub support for knowledge base](https://github.com/HKUDS/DeepTutor/issues/429) | open | 2026-04-30 | 2026-08-28 | 1 |
| 430 | Issue | [DeepSeek thinking mode full support & book generation UX improvements](https://github.com/HKUDS/DeepTutor/issues/430) | closed | 2026-04-30 | 2026-05-08 | 1 |
| 431 | Issue | [[Question]:Cannot process scanned PDF in Knowledge Base - "Skipped empty document" error](https://github.com/HKUDS/DeepTutor/issues/431) | open | 2026-05-01 | 2026-09-11 | 8 |
| 432 | PR | [feat: SAGE Memory Companion plugin + Playground tile](https://github.com/HKUDS/DeepTutor/pull/432) | open | 2026-05-01 | 2026-09-10 | 0 |
| 433 | Issue | [[Bug]:UI render issue in Dark Mode: LLM provider dropdown menu background remains white](https://github.com/HKUDS/DeepTutor/issues/433) | closed | 2026-05-01 | 2026-05-02 | 1 |
| 434 | Issue | [[Bug]:建立知识库后，聊天和题目生成分别在对知识库进行检索调用rag工具时存在的问题！](https://github.com/HKUDS/DeepTutor/issues/434) | closed | 2026-05-01 | 2026-05-02 | 5 |
| 435 | PR | [fix: paint settings select dark-mode dropdown popover background](https://github.com/HKUDS/DeepTutor/pull/435) | closed | 2026-05-02 | 2026-05-02 | 0 |
| 436 | PR | [fix(chat): forward extra_headers to all LLM calls in agentic pipeline](https://github.com/HKUDS/DeepTutor/pull/436) | closed | 2026-05-02 | 2026-05-04 | 1 |
| 437 | Issue | [[Bug]: AsyncResponses.create() got an unexpected keyword argument 'max_completion_tokens' when using OpenAI gpt-5.x models](https://github.com/HKUDS/DeepTutor/issues/437) | closed | 2026-05-02 | 2026-05-03 | 4 |
| 438 | PR | [fix(llm): map max_completion_tokens to max_output_tokens for Responses API](https://github.com/HKUDS/DeepTutor/pull/438) | closed | 2026-05-03 | 2026-05-03 | 1 |
| 439 | PR | [fix(ui): skill editor validation and modal background](https://github.com/HKUDS/DeepTutor/pull/439) | closed | 2026-05-03 | 2026-05-03 | 1 |
| 440 | Issue | [[Question]:Search failed (invalid_embedding_index): RAG index contains invalid embedding vectors](https://github.com/HKUDS/DeepTutor/issues/440) | open | 2026-05-03 | 2026-05-03 | 1 |
| 441 | PR | [fix(agents): normalize single newlines to markdown paragraphs in quiz content](https://github.com/HKUDS/DeepTutor/pull/441) | closed | 2026-05-04 | 2026-06-11 | 0 |
| 442 | PR | [fix: raise context_window ceiling and add qwen vision support](https://github.com/HKUDS/DeepTutor/pull/442) | closed | 2026-05-04 | 2026-06-11 | 0 |
| 443 | PR | [feat: add delete chat turn functionality with attachment cleanup](https://github.com/HKUDS/DeepTutor/pull/443) | closed | 2026-05-04 | 2026-06-11 | 0 |
| 444 | Issue | [[Bug]:辅导机器人对话无法换行（Docker部署）](https://github.com/HKUDS/DeepTutor/issues/444) | closed | 2026-05-05 | 2026-05-08 | 2 |
| 445 | PR | [feat: add deeptutor start command to launch backend and frontend together](https://github.com/HKUDS/DeepTutor/pull/445) | closed | 2026-05-05 | 2026-05-08 | 0 |
| 446 | Issue | [feat: configurable model pricing UI in Settings](https://github.com/HKUDS/DeepTutor/issues/446) | closed | 2026-05-05 | 2026-05-08 | 1 |
| 447 | PR | [fix: add deepseek-v4-flash and deepseek-v4-pro to model pricing table](https://github.com/HKUDS/DeepTutor/pull/447) | closed | 2026-05-05 | 2026-05-08 | 0 |
| 448 | Issue | [[Feature Request]: Add tooltips to each item on the sidebar](https://github.com/HKUDS/DeepTutor/issues/448) | closed | 2026-05-05 | 2026-05-08 | 3 |
| 449 | PR | [fix(web): preserve newlines in user chat messages](https://github.com/HKUDS/DeepTutor/pull/449) | closed | 2026-05-06 | 2026-05-08 | 0 |
| 450 | PR | [Feature/critic agent](https://github.com/HKUDS/DeepTutor/pull/450) | closed | 2026-05-06 | 2026-05-11 | 0 |
| 451 | Issue | [[Feature Request]:如何禁用周期性的 LLM 健康检查以避免消耗 token？](https://github.com/HKUDS/DeepTutor/issues/451) | open | 2026-05-06 | 2026-08-28 | 6 |
| 452 | PR | [feat(tutorbot): add Zulip channel support](https://github.com/HKUDS/DeepTutor/pull/452) | closed | 2026-05-06 | 2026-05-08 | 0 |
| 453 | PR | [fix(llm): stop sending reasoning_effort=minimal as top-level param to providers that reject it](https://github.com/HKUDS/DeepTutor/pull/453) | closed | 2026-05-06 | 2026-05-08 | 0 |
| 454 | PR | [feat(desktop): add Electron desktop shell with sidebar, webview & macOS traffic light supportDesktop dev](https://github.com/HKUDS/DeepTutor/pull/454) | open | 2026-05-07 | 2026-08-02 | 0 |
| 455 | PR | [fix: add TutorBot NVIDIA NIM provider support](https://github.com/HKUDS/DeepTutor/pull/455) | closed | 2026-05-07 | 2026-05-08 | 0 |
| 456 | PR | [feat: tooltips appear on hover for sidebar items](https://github.com/HKUDS/DeepTutor/pull/456) | closed | 2026-05-07 | 2026-05-07 | 1 |
| 457 | PR | [feat: tooltips for sidebar](https://github.com/HKUDS/DeepTutor/pull/457) | closed | 2026-05-07 | 2026-05-08 | 0 |
| 458 | PR | [Feature/heartbeat](https://github.com/HKUDS/DeepTutor/pull/458) | closed | 2026-05-08 | 2026-05-08 | 0 |
| 459 | PR | [feat(api): add mobile turn event facade](https://github.com/HKUDS/DeepTutor/pull/459) | open | 2026-05-08 | 2026-09-10 | 0 |
| 460 | PR | [Feature/heartbeat](https://github.com/HKUDS/DeepTutor/pull/460) | closed | 2026-05-08 | 2026-05-11 | 1 |
| 461 | PR | [chore: add py313 and py314 to Black target-version](https://github.com/HKUDS/DeepTutor/pull/461) | closed | 2026-05-09 | 2026-05-09 | 1 |
| 462 | Issue | [python-olm 3.2.16 在 macOS Python 3.14 + Apple Clang 21 下编译失败 (matrix-nio[e2e])](https://github.com/HKUDS/DeepTutor/issues/462) | closed | 2026-05-09 | 2026-05-10 | 1 |
| 463 | Issue | [[Question]: CORS error](https://github.com/HKUDS/DeepTutor/issues/463) | closed | 2026-05-09 | 2026-05-12 | 9 |
| 464 | Issue | [[Bug]: DISABLE_SSL_VERIFY=true and I still self-signed certificate in certificate chain](https://github.com/HKUDS/DeepTutor/issues/464) | closed | 2026-05-09 | 2026-05-10 | 1 |
| 465 | PR | [fix(ssl): extend DISABLE_SSL_VERIFY coverage to codex provider and four embedding adapters](https://github.com/HKUDS/DeepTutor/pull/465) | closed | 2026-05-09 | 2026-05-12 | 1 |
| 466 | PR | [Feature/arch linux](https://github.com/HKUDS/DeepTutor/pull/466) | closed | 2026-05-09 | 2026-05-10 | 0 |
| 467 | PR | [Feature/critic agent](https://github.com/HKUDS/DeepTutor/pull/467) | closed | 2026-05-10 | 2026-05-11 | 0 |
| 468 | Issue | [[Bug]: incorrectly inject '#references "citation"' into code blocks with array index like '[0]'](https://github.com/HKUDS/DeepTutor/issues/468) | closed | 2026-05-10 | 2026-05-10 | 1 |
| 469 | PR | [fix: prevent citation markers from being injected into fenced code bl…](https://github.com/HKUDS/DeepTutor/pull/469) | closed | 2026-05-10 | 2026-05-11 | 0 |
| 470 | PR | [Repair pnpm checks and provider runtime integration](https://github.com/HKUDS/DeepTutor/pull/470) | closed | 2026-05-10 | 2026-05-10 | 0 |
| 471 | Issue | [[Feature Request]: Setting a language in book section](https://github.com/HKUDS/DeepTutor/issues/471) | closed | 2026-05-10 | 2026-08-29 | 2 |
| 472 | Issue | [[Bug]: CoWriter response extreme short](https://github.com/HKUDS/DeepTutor/issues/472) | closed | 2026-05-10 | 2026-05-22 | 2 |
| 473 | Issue | [[Feature Request]: Chapter map - headlines are cut off](https://github.com/HKUDS/DeepTutor/issues/473) | open | 2026-05-10 | 2026-08-28 | 2 |
| 474 | PR | [fix: 系统性修复多用户数据隔离问题](https://github.com/HKUDS/DeepTutor/pull/474) | closed | 2026-05-11 | 2026-06-11 | 0 |
| 475 | Issue | [[Feature Request]: Allow user-resizing of answer textarea in Quiz component, ie. add 'resize:vertical' CSS property](https://github.com/HKUDS/DeepTutor/issues/475) | closed | 2026-05-11 | 2026-08-04 | 1 |
| 476 | Issue | [[Question]: Does add doc to knowledge base have quadratic complexity?](https://github.com/HKUDS/DeepTutor/issues/476) | closed | 2026-05-12 | 2026-06-01 | 1 |
| 477 | PR | [fix(zulip): 弃用，重新PR](https://github.com/HKUDS/DeepTutor/pull/477) | closed | 2026-05-12 | 2026-05-12 | 1 |
| 478 | PR | [fix: allow quiz answer textarea vertical resize](https://github.com/HKUDS/DeepTutor/pull/478) | closed | 2026-05-12 | 2026-05-14 | 0 |
| 479 | PR | [弃用](https://github.com/HKUDS/DeepTutor/pull/479) | closed | 2026-05-12 | 2026-10-09 | 0 |
| 480 | PR | [fix(zulip): 修复 Zulip 通道附件上传与消息发送的 BUG，支持 Bot 自动订阅频道](https://github.com/HKUDS/DeepTutor/pull/480) | closed | 2026-05-12 | 2026-05-14 | 0 |
| 481 | Issue | [[Bug] Non-admin users get 404 on all session requests in Docker multi-user deployment](https://github.com/HKUDS/DeepTutor/issues/481) | closed | 2026-05-13 | 2026-05-28 | 3 |
| 482 | PR | [docs: add developer quick start guide for DeepTutor](https://github.com/HKUDS/DeepTutor/pull/482) | closed | 2026-05-13 | 2026-05-13 | 0 |
| 484 | PR | [fix(zulip): 增加内容检测fallback解决Generic bot收不到mention flag问题](https://github.com/HKUDS/DeepTutor/pull/484) | closed | 2026-05-14 | 2026-05-29 | 1 |
| 485 | PR | [fix(auth): make require_auth async so the user ContextVar reaches the endpoint](https://github.com/HKUDS/DeepTutor/pull/485) | closed | 2026-05-14 | 2026-05-28 | 2 |
| 486 | Issue | [[Question]:How do I uninstall and clean it up?](https://github.com/HKUDS/DeepTutor/issues/486) | open | 2026-05-15 | 2026-05-16 | 1 |
| 487 | Issue | [[Bug]: 同一chat生成新的Quiz会继承上一个quiz的答题状态而不是全新的。](https://github.com/HKUDS/DeepTutor/issues/487) | closed | 2026-05-16 | 2026-05-22 | 2 |
| 488 | PR | [feat(visualize): replace free-form HTML generation with standardized JSON widget spec framework](https://github.com/HKUDS/DeepTutor/pull/488) | open | 2026-05-17 | 2026-08-02 | 0 |
| 489 | Issue | [[Bug]: Visualize (and other capabilities) silently truncate on Gemini 2.5 / 3.x due to default thinking tokens](https://github.com/HKUDS/DeepTutor/issues/489) | closed | 2026-05-17 | 2026-05-28 | 0 |
| 490 | PR | [fix(visualize): unblock Gemini 2.5+ and harden Visualize pipeline](https://github.com/HKUDS/DeepTutor/pull/490) | closed | 2026-05-17 | 2026-05-28 | 1 |
| 491 | PR | [[codex] Add complete Arabic language support](https://github.com/HKUDS/DeepTutor/pull/491) | closed | 2026-05-17 | 2026-05-28 | 1 |
| 492 | PR | [feat: add chat retrieval controls and summary](https://github.com/HKUDS/DeepTutor/pull/492) | open | 2026-05-19 | 2026-08-02 | 0 |
| 493 | PR | [Fix SQLite FD Exhaustion](https://github.com/HKUDS/DeepTutor/pull/493) | closed | 2026-05-19 | 2026-05-29 | 1 |
| 494 | Issue | [[Bug]: knowledge_learning router not registered in main.py](https://github.com/HKUDS/DeepTutor/issues/494) | closed | 2026-05-20 | 2026-05-28 | 1 |
| 495 | Issue | [[Bug]: Knowledge extractor fails with DeepSeek — JSON parsing error](https://github.com/HKUDS/DeepTutor/issues/495) | closed | 2026-05-20 | 2026-05-28 | 1 |
| 496 | Issue | [[Bug]: LearningSession has no metadata field — agents get empty context](https://github.com/HKUDS/DeepTutor/issues/496) | closed | 2026-05-20 | 2026-05-28 | 1 |
| 497 | Issue | [[Bug]: KnowledgePoint validation rejects LLM-extracted data (prerequisites & document_id)](https://github.com/HKUDS/DeepTutor/issues/497) | closed | 2026-05-20 | 2026-05-28 | 1 |
| 498 | Issue | [DeepTutor Roadmap](https://github.com/HKUDS/DeepTutor/issues/498) | open | 2026-05-20 | 2026-10-28 | 7 |
| 499 | PR | [fix(web): reset quiz answer state when new quiz is generated in same chat](https://github.com/HKUDS/DeepTutor/pull/499) | closed | 2026-05-21 | 2026-05-22 | 1 |
| 500 | PR | [Feature/guided learning](https://github.com/HKUDS/DeepTutor/pull/500) | closed | 2026-05-21 | 2026-05-29 | 4 |
| 501 | PR | [fix: prevent sed from corrupting API_BASE placeholder validation](https://github.com/HKUDS/DeepTutor/pull/501) | closed | 2026-05-21 | 2026-05-22 | 1 |
| 502 | Issue | [Docker: sed placeholder substitution breaks API base URL validation with non-default BACKEND_PORT](https://github.com/HKUDS/DeepTutor/issues/502) | closed | 2026-05-22 | 2026-05-22 | 0 |
| 503 | Issue | [[Bug]:Unable to communicate with version 1.4.0 beta](https://github.com/HKUDS/DeepTutor/issues/503) | closed | 2026-05-22 | 2026-05-25 | 2 |
| 504 | Issue | [[Bug]:设置页提示"无法从后端加载设置"和容器重启产生僵尸 turn，running 状态永久卡死（DOCKER部署）](https://github.com/HKUDS/DeepTutor/issues/504) | closed | 2026-05-22 | 2026-05-22 | 1 |
| 505 | Issue | [[Question]: v1.4.0 How to register a provider](https://github.com/HKUDS/DeepTutor/issues/505) | closed | 2026-05-22 | 2026-05-27 | 2 |
| 506 | Issue | [[Bug]:TutorBot ExecTool executes LLM-generated shell commands through WebSocket chat](https://github.com/HKUDS/DeepTutor/issues/506) | closed | 2026-05-23 | 2026-05-27 | 1 |
| 507 | PR | [fix(security): harden ExecTool defaults against command injection (#506)](https://github.com/HKUDS/DeepTutor/pull/507) | closed | 2026-05-23 | 2026-05-27 | 2 |
| 508 | PR | [Fix GPT-5 token limit parameter in init wizard probe](https://github.com/HKUDS/DeepTutor/pull/508) | closed | 2026-05-23 | 2026-05-27 | 1 |
| 509 | PR | [fix: prevent Document nodes from bypassing chunking pipeline](https://github.com/HKUDS/DeepTutor/pull/509) | closed | 2026-05-23 | 2026-05-27 | 1 |
| 510 | PR | [feat: add pluggable TTS tool with multi-provider support](https://github.com/HKUDS/DeepTutor/pull/510) | open | 2026-05-23 | 2026-09-10 | 0 |
| 511 | Issue | [[Feature Request]:支持通过 HTTP API 与指定 TutorBot 进行多轮对话](https://github.com/HKUDS/DeepTutor/issues/511) | closed | 2026-05-23 | 2026-06-04 | 2 |
| 512 | Issue | [[Bug]:  New user cannot create initial profile via UI with docker deployment](https://github.com/HKUDS/DeepTutor/issues/512) | closed | 2026-05-23 | 2026-05-27 | 2 |
| 513 | PR | [fix(settings): add profile button when no profiles exist](https://github.com/HKUDS/DeepTutor/pull/513) | closed | 2026-05-24 | 2026-06-09 | 1 |
| 514 | Issue | [[Bug]:Authorization Bypass in Book Confirmation Flow - Unauthorized Book Modification via book_id](https://github.com/HKUDS/DeepTutor/issues/514) | closed | 2026-05-24 | 2026-05-27 | 1 |
| 515 | Issue | [[Bug]:Cross-Session Authorization Bypass in Turn Regeneration - Unauthorized Session Manipulation](https://github.com/HKUDS/DeepTutor/issues/515) | closed | 2026-05-24 | 2026-05-27 | 1 |
| 516 | Issue | [[Bug]:Cross-Bot Authorization Bypass in TutorBot File Management - Unauthorized Bot File Modification](https://github.com/HKUDS/DeepTutor/issues/516) | closed | 2026-05-25 | 2026-05-27 | 1 |
| 517 | Issue | [[Bug]: Path Traversal in TutorBot Filesystem Tool - Arbitrary File Write via LLM Tool Execution](https://github.com/HKUDS/DeepTutor/issues/517) | closed | 2026-05-25 | 2026-05-27 | 1 |
| 518 | Issue | [[Bug]:Remote Code Execution via TutorBot Shell Tool - Arbitrary Command Execution through LLM](https://github.com/HKUDS/DeepTutor/issues/518) | closed | 2026-05-25 | 2026-05-27 | 1 |
| 519 | PR | [fix: route Anthropic-backend providers through native SDK in agentic loop](https://github.com/HKUDS/DeepTutor/pull/519) | closed | 2026-05-25 | 2026-05-28 | 1 |
| 520 | Issue | [[Bug]:v1.4.0: chat input disabled after first turn (regression); v1.4.0b0: hardcoded URL guard breaks matching deployments](https://github.com/HKUDS/DeepTutor/issues/520) | closed | 2026-05-25 | 2026-05-27 | 1 |
| 521 | Issue | [[Bug]: Error while embedding some documents in a Knowledge Base](https://github.com/HKUDS/DeepTutor/issues/521) | closed | 2026-05-25 | 2026-05-27 | 3 |
| 522 | PR | [feat: support zip upload with error-state recovery and recursive file scanning](https://github.com/HKUDS/DeepTutor/pull/522) | closed | 2026-05-26 | 2026-05-27 | 1 |
| 523 | PR | [Improve settings model fetching and question notebook lookup UX](https://github.com/HKUDS/DeepTutor/pull/523) | closed | 2026-05-26 | 2026-05-27 | 1 |
| 524 | PR | [feat: truncate oversized event payloads in session response](https://github.com/HKUDS/DeepTutor/pull/524) | closed | 2026-05-26 | 2026-05-27 | 1 |
| 525 | PR | [feat: embed local Markdown image references as data URIs during indexing](https://github.com/HKUDS/DeepTutor/pull/525) | open | 2026-05-26 | 2026-09-10 | 3 |
| 526 | PR | [fix: correct isinstance check in documents_to_nodes to fix KB indexing](https://github.com/HKUDS/DeepTutor/pull/526) | closed | 2026-05-27 | 2026-06-09 | 1 |
| 527 | Issue | [[Bug]: Qwen 3.6 Plus fails to use native tool calling via OpenAI-compatible endpoints](https://github.com/HKUDS/DeepTutor/issues/527) | closed | 2026-05-27 | 2026-05-27 | 2 |
| 528 | PR | [fix(chat): enable native tool calling for reasoning models via OpenAI-compatible endpoints](https://github.com/HKUDS/DeepTutor/pull/528) | closed | 2026-05-27 | 2026-06-09 | 1 |
| 529 | PR | [fix: Qwen model JSON preamble, force-recompile overview pages, health false positives](https://github.com/HKUDS/DeepTutor/pull/529) | closed | 2026-05-27 | 2026-05-29 | 1 |
| 530 | Issue | [[Bug]: disable_ssl_verify: true, and I still self-signed certificate in certificate chain](https://github.com/HKUDS/DeepTutor/issues/530) | closed | 2026-05-28 | 2026-05-28 | 2 |
| 531 | Issue | [TutorBot allow_shell_exec is silently reset to false on every auto-start (exec tool never enabled for auto_start bots)](https://github.com/HKUDS/DeepTutor/issues/531) | closed | 2026-05-28 | 2026-06-12 | 2 |
| 532 | Issue | [[Question]: RAG chat cannot return information from the selected knowledge base](https://github.com/HKUDS/DeepTutor/issues/532) | closed | 2026-05-29 | 2026-06-12 | 7 |
| 533 | PR | [chore: ignore local development artifacts](https://github.com/HKUDS/DeepTutor/pull/533) | closed | 2026-05-30 | 2026-06-14 | 1 |
| 534 | Issue | [Bug: allow_shell_exec cannot be persisted — missing in auto_start_bots, UpdateBotRequest, and _apply_payload](https://github.com/HKUDS/DeepTutor/issues/534) | closed | 2026-05-31 | 2026-06-12 | 1 |
| 535 | Issue | [[Question] 经过更深入的分析代码 tutorbot 可以通过 skills  实现主系统的几乎所有功能，关闭 issue ！！！](https://github.com/HKUDS/DeepTutor/issues/535) | closed | 2026-05-31 | 2026-05-31 | 1 |
| 536 | Issue | [[Question]: Does the container crash after 5 to 10 minutes of idle time?](https://github.com/HKUDS/DeepTutor/issues/536) | closed | 2026-06-01 | 2026-06-03 | 5 |
| 537 | Issue | [[Bug]:The responses are incoherent.](https://github.com/HKUDS/DeepTutor/issues/537) | closed | 2026-06-01 | 2026-06-24 | 1 |
| 538 | PR | [fix(tutorbot): correct question_type → question_types in deep-question SKILL.md](https://github.com/HKUDS/DeepTutor/pull/538) | closed | 2026-06-02 | 2026-06-09 | 0 |
| 539 | PR | [feat: add dynamic_router compat gateway](https://github.com/HKUDS/DeepTutor/pull/539) | closed | 2026-06-02 | 2026-06-11 | 0 |
| 540 | PR | [fix(web): preserve math before citation linkification](https://github.com/HKUDS/DeepTutor/pull/540) | closed | 2026-06-02 | 2026-06-14 | 0 |
| 541 | PR | [fix(chat): route OAuth backend through native provider](https://github.com/HKUDS/DeepTutor/pull/541) | closed | 2026-06-02 | 2026-06-02 | 1 |
| 542 | PR | [fix(chat): route OAuth backend through native provider](https://github.com/HKUDS/DeepTutor/pull/542) | closed | 2026-06-02 | 2026-06-14 | 0 |
| 543 | PR | [feat: upgrade MiniMax default model to M3](https://github.com/HKUDS/DeepTutor/pull/543) | closed | 2026-06-03 | 2026-06-23 | 0 |
| 544 | PR | [fix: 将 Heartbeat 通知广播到所有已绑定的 Channel](https://github.com/HKUDS/DeepTutor/pull/544) | closed | 2026-06-03 | 2026-06-08 | 1 |
| 545 | PR | [[codex] Add German UI and LLM localization](https://github.com/HKUDS/DeepTutor/pull/545) | closed | 2026-06-03 | 2026-06-04 | 1 |
| 546 | PR | [[codex] Add German UI and LLM localization](https://github.com/HKUDS/DeepTutor/pull/546) | closed | 2026-06-04 | 2026-06-04 | 1 |
| 547 | PR | [[codex] Add German UI and LLM localization](https://github.com/HKUDS/DeepTutor/pull/547) | closed | 2026-06-04 | 2026-06-04 | 1 |
| 548 | PR | [feat(web): use dropdown for UI language selection](https://github.com/HKUDS/DeepTutor/pull/548) | closed | 2026-06-04 | 2026-06-23 | 1 |
| 549 | PR | [fix: keep NEXT_PUBLIC_AUTH_ENABLED out of the minifier constant-fold](https://github.com/HKUDS/DeepTutor/pull/549) | closed | 2026-06-04 | 2026-06-14 | 1 |
| 550 | PR | [fix: sidebar footer items stay as text when the sidebar is collapsed](https://github.com/HKUDS/DeepTutor/pull/550) | closed | 2026-06-04 | 2026-06-14 | 0 |
| 551 | PR | [fix(tutorbot): auto-start bots for all users in multi-user mode](https://github.com/HKUDS/DeepTutor/pull/551) | closed | 2026-06-04 | 2026-06-22 | 0 |
| 552 | Issue | [[Question]: RAG chat on a 250 MB knowledge base failed to return results in a few minutes](https://github.com/HKUDS/DeepTutor/issues/552) | closed | 2026-06-05 | 2026-06-24 | 2 |
| 553 | Issue | [[Feature Request]: User profile page (account + avatar) and a lighter Admin page](https://github.com/HKUDS/DeepTutor/issues/553) | closed | 2026-06-05 | 2026-06-24 | 2 |
| 554 | Issue | [[Feature Request]:Quiz should be supported for knowledge base reference rather than attaching files into chat.](https://github.com/HKUDS/DeepTutor/issues/554) | closed | 2026-06-06 | 2026-08-04 | 3 |
| 555 | Issue | [[Feature Request]: Moodle](https://github.com/HKUDS/DeepTutor/issues/555) | closed | 2026-06-07 | 2026-06-20 | 3 |
| 556 | PR | [refactor: outbound broadcast routing for multi-channel heartbeat delivery](https://github.com/HKUDS/DeepTutor/pull/556) | closed | 2026-06-07 | 2026-06-22 | 0 |
| 557 | PR | [fix(llm): fit token budgets to 8192 vLLM ctx + repair vision config](https://github.com/HKUDS/DeepTutor/pull/557) | closed | 2026-06-08 | 2026-06-08 | 0 |
| 558 | PR | [fix: surface bad-login error inline instead of silent page reload](https://github.com/HKUDS/DeepTutor/pull/558) | closed | 2026-06-08 | 2026-06-14 | 0 |
| 559 | PR | [fix: accept username, not just email, on login and register forms](https://github.com/HKUDS/DeepTutor/pull/559) | closed | 2026-06-08 | 2026-06-14 | 0 |
| 560 | PR | [feat: Heartbeat Settings WebUI — configurable interval & model](https://github.com/HKUDS/DeepTutor/pull/560) | closed | 2026-06-09 | 2026-06-14 | 0 |
| 561 | PR | [Enhance knowledge base management and Co-Scientist capabilities](https://github.com/HKUDS/DeepTutor/pull/561) | closed | 2026-06-10 | 2026-06-23 | 2 |
| 563 | PR | [Oxca/tutor inline quiz history](https://github.com/HKUDS/DeepTutor/pull/563) | open | 2026-06-11 | 2026-09-10 | 0 |
| 564 | PR | [Fix TutorBot shell exec persistence](https://github.com/HKUDS/DeepTutor/pull/564) | closed | 2026-06-11 | 2026-06-14 | 1 |
| 565 | Issue | [[Question]:](https://github.com/HKUDS/DeepTutor/issues/565) | closed | 2026-06-12 | 2026-06-20 | 4 |
| 566 | PR | [feat(partners): Partner 多用户隔离 — 按用户 scope 存储 partner 数据](https://github.com/HKUDS/DeepTutor/pull/566) | closed | 2026-06-13 | 2026-07-11 | 0 |
| 567 | Issue | [[Feature Request]: LTI Integration](https://github.com/HKUDS/DeepTutor/issues/567) | open | 2026-06-13 | 2026-06-20 | 4 |
| 568 | PR | [fix: gate LLM features for users without an assigned model](https://github.com/HKUDS/DeepTutor/pull/568) | closed | 2026-06-13 | 2026-06-14 | 1 |
| 569 | Issue | [[Feature Request]:](https://github.com/HKUDS/DeepTutor/issues/569) | closed | 2026-06-14 | 2026-06-17 | 2 |
| 570 | PR | [fix: show only provider-relevant fields in Search settings](https://github.com/HKUDS/DeepTutor/pull/570) | closed | 2026-06-14 | 2026-06-19 | 0 |
| 571 | PR | [feat: discoverable profile rename and auto-name by provider](https://github.com/HKUDS/DeepTutor/pull/571) | closed | 2026-06-14 | 2026-06-19 | 0 |
| 572 | PR | [fix: translate missing English settings-tour steps](https://github.com/HKUDS/DeepTutor/pull/572) | closed | 2026-06-14 | 2026-06-19 | 0 |
| 573 | PR | [feat: user profile page with avatar (account info, icon/image avatar, sign out)](https://github.com/HKUDS/DeepTutor/pull/573) | closed | 2026-06-14 | 2026-06-20 | 1 |
| 574 | Issue | [[Bug] Partner 会话未接入 Memory 系统，L1无会话内容](https://github.com/HKUDS/DeepTutor/issues/574) | closed | 2026-06-15 | 2026-06-17 | 1 |
| 575 | Issue | [[Bug]:一些聊天中显示的问题和出题无法被记录的bug](https://github.com/HKUDS/DeepTutor/issues/575) | open | 2026-06-16 | 2026-09-01 | 3 |
| 576 | Issue | [[Feature Request]: Support rootless podman with read-only rootfs for hardened deployments](https://github.com/HKUDS/DeepTutor/issues/576) | closed | 2026-06-17 | 2026-06-20 | 1 |
| 577 | PR | [feat(deploy): harden image for rootless podman with read-only rootfs](https://github.com/HKUDS/DeepTutor/pull/577) | closed | 2026-06-17 | 2026-06-20 | 3 |
| 578 | PR | [feat: 聊天历史加载动画支持](https://github.com/HKUDS/DeepTutor/pull/578) | closed | 2026-06-20 | 2026-06-23 | 1 |
| 579 | PR | [[security] fix(multi-user): deny MCP tools until explicitly granted](https://github.com/HKUDS/DeepTutor/pull/579) | closed | 2026-06-21 | 2026-06-21 | 1 |
| 580 | Issue | [[Bug]: supervisord CRIT "could not write pidfile /var/run/supervisord.pid" on rootless podman + keep-id + RO rootfs](https://github.com/HKUDS/DeepTutor/issues/580) | closed | 2026-06-22 | 2026-06-24 | 1 |
| 581 | PR | [fix(deploy): /var/run tmpfs mode 0755 → 1777 so supervisord can write pidfile as UID 1000](https://github.com/HKUDS/DeepTutor/pull/581) | closed | 2026-06-22 | 2026-06-24 | 1 |
| 582 | PR | [fix: run supervisord as root so services start under rootful Docker](https://github.com/HKUDS/DeepTutor/pull/582) | closed | 2026-06-22 | 2026-06-23 | 0 |
| 583 | PR | [feat: redesign User Management page (avatars, search, skeleton, confirm dialog)](https://github.com/HKUDS/DeepTutor/pull/583) | closed | 2026-06-22 | 2026-06-23 | 0 |
| 584 | PR | [fix(llm): enable native tool calls for SiliconFlow](https://github.com/HKUDS/DeepTutor/pull/584) | closed | 2026-06-22 | 2026-06-23 | 0 |
| 585 | PR | [refactor: move Back link to its own row in the page header](https://github.com/HKUDS/DeepTutor/pull/585) | closed | 2026-06-22 | 2026-06-23 | 0 |
| 586 | PR | [feat(docker): make BACKEND_HOST and FRONTEND_HOST env-configurable](https://github.com/HKUDS/DeepTutor/pull/586) | closed | 2026-06-23 | 2026-06-23 | 0 |
| 587 | Issue | [Options do not render LaTeX formulas in quiz cards](https://github.com/HKUDS/DeepTutor/issues/587) | closed | 2026-06-23 | 2026-06-24 | 2 |
| 588 | PR | [fix: render LaTeX in quiz options](https://github.com/HKUDS/DeepTutor/pull/588) | closed | 2026-06-23 | 2026-06-24 | 1 |
| 589 | Issue | [[Feature Request]: PyMuPDF4LLM for building KnowledgeBase (with lightrag)](https://github.com/HKUDS/DeepTutor/issues/589) | closed | 2026-06-23 | 2026-06-24 | 1 |
| 590 | Issue | [[Feature Request]: Add Native Mattermost Channel to the Partner Subsystem](https://github.com/HKUDS/DeepTutor/issues/590) | closed | 2026-06-23 | 2026-06-30 | 2 |
| 591 | Issue | [[Feature Request]: Support for Standalone External LightRAG Container Endpoint](https://github.com/HKUDS/DeepTutor/issues/591) | closed | 2026-06-23 | 2026-06-24 | 1 |
| 592 | Issue | [Discussion: Should DeepTutor become installable apps?](https://github.com/HKUDS/DeepTutor/issues/592) | closed | 2026-06-24 | 2026-09-03 | 2 |
| 593 | PR | [fix(docker): make supervisord config portable across rootful + rootless keep-id](https://github.com/HKUDS/DeepTutor/pull/593) | closed | 2026-06-24 | 2026-06-27 | 1 |
| 594 | Issue | [[Bug]: Selecting pymupdf4llm as the document parser and then making knowledge base using lightrag selects mineru as document parser](https://github.com/HKUDS/DeepTutor/issues/594) | closed | 2026-06-24 | 2026-06-30 | 5 |
| 595 | Issue | [[Bug]:Deep Research returns a success response even when a research block fails](https://github.com/HKUDS/DeepTutor/issues/595) | closed | 2026-06-25 | 2026-06-30 | 1 |
| 596 | Issue | [[Security] Sessions not isolated by user — any authenticated user can read all other users' sessions](https://github.com/HKUDS/DeepTutor/issues/596) | closed | 2026-06-26 | 2026-06-30 | 2 |
| 597 | Issue | [[Question]:partner 有独立的 memory 吗？](https://github.com/HKUDS/DeepTutor/issues/597) | closed | 2026-06-26 | 2026-06-27 | 1 |
| 598 | Issue | [[Question]:多用户模式下普通用户无法使用 partner，也无法创建 partner 吗？](https://github.com/HKUDS/DeepTutor/issues/598) | closed | 2026-06-27 | 2026-06-27 | 2 |
| 599 | Issue | [[Bug]:多用户模式下用户登录后左上角图标显示错误](https://github.com/HKUDS/DeepTutor/issues/599) | closed | 2026-06-27 | 2026-06-27 | 1 |
| 600 | PR | [Adaptive diagnostic: prefer nearest difficulty on fallback](https://github.com/HKUDS/DeepTutor/pull/600) | closed | 2026-06-27 | 2026-06-27 | 1 |
| 601 | PR | [feat(cowriter): export markdown drafts as PDF](https://github.com/HKUDS/DeepTutor/pull/601) | closed | 2026-06-29 | 2026-07-09 | 0 |
| 602 | PR | [fix: preserve zero LlamaIndex chunk overlap](https://github.com/HKUDS/DeepTutor/pull/602) | closed | 2026-06-30 | 2026-06-30 | 0 |
| 603 | Issue | [[Bug]: Guided Learning choice options are lost and correct answers may be graded incorrectly](https://github.com/HKUDS/DeepTutor/issues/603) | closed | 2026-06-30 | 2026-06-30 | 1 |
| 604 | PR | [[codex] fix mastery choice persistence and grading](https://github.com/HKUDS/DeepTutor/pull/604) | closed | 2026-06-30 | 2026-06-30 | 1 |
| 605 | Issue | [[Bug]: Release 1.4.15 can't be installed using uv](https://github.com/HKUDS/DeepTutor/issues/605) | closed | 2026-06-30 | 2026-07-01 | 3 |
| 606 | Issue | [[Feature Request]: Pymupdf4llm option for LlamaIndex](https://github.com/HKUDS/DeepTutor/issues/606) | closed | 2026-06-30 | 2026-08-04 | 1 |
| 607 | Issue | [[Bug]: confirm-proposal times out client-side (~35-47s) but backend finishes the spine build anyway](https://github.com/HKUDS/DeepTutor/issues/607) | closed | 2026-07-02 | 2026-07-29 | 2 |
| 608 | PR | [fix(web): avoid crashes on malformed Markdown hash links](https://github.com/HKUDS/DeepTutor/pull/608) | closed | 2026-07-02 | 2026-07-18 | 0 |
| 609 | PR | [fix(config): preserve KB default fallbacks](https://github.com/HKUDS/DeepTutor/pull/609) | closed | 2026-07-03 | 2026-07-10 | 0 |
| 612 | Issue | [[Question]:persistence问题，用户数据长期是否考虑数据库方案，如pg](https://github.com/HKUDS/DeepTutor/issues/612) | open | 2026-07-07 | 2026-07-07 | 0 |
| 613 | Issue | [[Feature Request]: Agentic Multi-Speaker "Audio Overview" (Podcast) Generation from Knowledge Base](https://github.com/HKUDS/DeepTutor/issues/613) | open | 2026-07-07 | 2026-09-11 | 1 |
| 614 | PR | [Feat/agentkit tracer 1](https://github.com/HKUDS/DeepTutor/pull/614) | closed | 2026-07-08 | 2026-07-08 | 0 |
| 615 | PR | [fix(webui): send edited user message on Enter, keep Shift+Enter as newline](https://github.com/HKUDS/DeepTutor/pull/615) | closed | 2026-07-09 | 2026-10-16 | 1 |
| 616 | Issue | [[Bug]: WeCom channel crashes on start: wecom.py is incompatible with the pinned wecom-aibot-sdk 1.0.8](https://github.com/HKUDS/DeepTutor/issues/616) | closed | 2026-07-10 | 2026-07-19 | 1 |
| 617 | PR | [fix: count streamed LLM usage once per completion](https://github.com/HKUDS/DeepTutor/pull/617) | closed | 2026-07-10 | 2026-07-21 | 2 |
| 618 | Issue | [compute_mastery recency weighting is disabled by a variable-swap in the zip unpack](https://github.com/HKUDS/DeepTutor/issues/618) | closed | 2026-07-11 | 2026-07-19 | 1 |
| 619 | PR | [fix(knowledge): persist linked folder sync state updates](https://github.com/HKUDS/DeepTutor/pull/619) | closed | 2026-07-11 | 2026-07-18 | 0 |
| 620 | PR | [fix(knowledge): make KB configuration updates atomic and race-safe](https://github.com/HKUDS/DeepTutor/pull/620) | open | 2026-07-11 | 2026-08-02 | 0 |
| 621 | Issue | [[Question]: 多用户 Partner 分配机制下的 Memory 隔离与 Media 存储设计疑问](https://github.com/HKUDS/DeepTutor/issues/621) | open | 2026-07-11 | 2026-08-16 | 2 |
| 622 | PR | [fix: restore recency weighting in compute_mastery (#618)](https://github.com/HKUDS/DeepTutor/pull/622) | closed | 2026-07-12 | 2026-07-18 | 0 |
| 623 | Issue | [[Bug]: Logout may not clear secure dt_token cookie with SameSite=None](https://github.com/HKUDS/DeepTutor/issues/623) | closed | 2026-07-12 | 2026-07-19 | 0 |
| 624 | Issue | [[Bug] local mineru+lightrag](https://github.com/HKUDS/DeepTutor/issues/624) | closed | 2026-07-12 | 2026-07-19 | 0 |
| 625 | PR | [fix: set Secure attribute when clearing dt_token on logout](https://github.com/HKUDS/DeepTutor/pull/625) | closed | 2026-07-14 | 2026-07-18 | 0 |
| 626 | PR | [fix(llm): enable OpenAI Codex native tool calls](https://github.com/HKUDS/DeepTutor/pull/626) | closed | 2026-07-15 | 2026-07-18 | 0 |
| 627 | PR | [feat(pageindex): retrieval via MCP tools + full document-endpoint format support](https://github.com/HKUDS/DeepTutor/pull/627) | closed | 2026-07-15 | 2026-07-18 | 2 |
| 628 | PR | [fix: resolve relative img_path in parsed content lists to absolute paths](https://github.com/HKUDS/DeepTutor/pull/628) | closed | 2026-07-15 | 2026-07-19 | 4 |
| 629 | PR | [docs: quote pip extras install examples](https://github.com/HKUDS/DeepTutor/pull/629) | closed | 2026-07-15 | 2026-07-18 | 0 |
| 631 | PR | [fix(partners): align WeCom with SDK 1.0.8](https://github.com/HKUDS/DeepTutor/pull/631) | closed | 2026-07-16 | 2026-07-18 | 0 |
| 632 | PR | [Add GitHub Actions workflow for Python package publishing](https://github.com/HKUDS/DeepTutor/pull/632) | open | 2026-07-16 | 2026-09-10 | 0 |
| 633 | PR | [fix: chat page not full width, scrollbar only works in middle area](https://github.com/HKUDS/DeepTutor/pull/633) | closed | 2026-07-16 | 2026-07-16 | 0 |
| 634 | PR | [fix: chat page not full width, scrollbar only works in middle area](https://github.com/HKUDS/DeepTutor/pull/634) | closed | 2026-07-16 | 2026-07-18 | 0 |
| 635 | PR | [fix(knowledge): update KB status to processing on file upload and sync-folder](https://github.com/HKUDS/DeepTutor/pull/635) | closed | 2026-07-16 | 2026-07-18 | 1 |
| 636 | PR | [fix(book): reset page status on compilation failure (worker + inline)](https://github.com/HKUDS/DeepTutor/pull/636) | closed | 2026-07-16 | 2026-07-18 | 2 |
| 637 | PR | [Fix recency-weighting variable swap in compute_mastery](https://github.com/HKUDS/DeepTutor/pull/637) | open | 2026-07-17 | 2026-09-10 | 1 |
| 638 | PR | [feat: add Voice Tutor capability and Desmos Graph integration](https://github.com/HKUDS/DeepTutor/pull/638) | open | 2026-07-17 | 2026-09-10 | 0 |
| 639 | Issue | [[Question]: How do I install a skill from clawhub from a specific publisher?](https://github.com/HKUDS/DeepTutor/issues/639) | closed | 2026-07-17 | 2026-08-29 | 2 |
| 640 | Issue | [[Feature Request]: Specify parameters of LightRAG system](https://github.com/HKUDS/DeepTutor/issues/640) | open | 2026-07-17 | 2026-07-18 | 1 |
| 641 | Issue | [[Feature Request]:Add a per-conversation reasoning-effort selector to the chat composer](https://github.com/HKUDS/DeepTutor/issues/641) | open | 2026-07-18 | 2026-10-28 | 2 |
| 642 | PR | [fix: support newer Anthropic models via the official SDK](https://github.com/HKUDS/DeepTutor/pull/642) | closed | 2026-07-18 | 2026-07-18 | 0 |
| 643 | PR | [feat: add sql_query tool — persistent in-chat SQLite with Chart.js visualization](https://github.com/HKUDS/DeepTutor/pull/643) | closed | 2026-07-18 | 2026-07-18 | 0 |
| 644 | PR | [fix(partners): avoid hang in split_message when max_len <= 0](https://github.com/HKUDS/DeepTutor/pull/644) | closed | 2026-07-19 | 2026-07-23 | 1 |
| 645 | PR | [fix(memory): parse line-edit JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/645) | closed | 2026-07-19 | 2026-07-23 | 1 |
| 646 | PR | [fix(memory): parse update facts JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/646) | closed | 2026-07-19 | 2026-07-23 | 1 |
| 647 | Issue | [[Bug]:精通之路学习模式记忆重复记录问题](https://github.com/HKUDS/DeepTutor/issues/647) | closed | 2026-07-19 | 2026-07-23 | 1 |
| 648 | PR | [Add a theme selector for code blocks](https://github.com/HKUDS/DeepTutor/pull/648) | closed | 2026-07-19 | 2026-07-23 | 1 |
| 649 | Issue | [[Bug]:The conflict between scrolling up and streaming output,they scramble for the focus pane](https://github.com/HKUDS/DeepTutor/issues/649) | closed | 2026-07-20 | 2026-07-24 | 2 |
| 650 | Issue | [[Bug]:选中 Obsidian 知识库时,其他 LlamaIndex 知识库被静默跳过(exclusive capability 连坐)](https://github.com/HKUDS/DeepTutor/issues/650) | closed | 2026-07-20 | 2026-07-23 | 2 |
| 651 | Issue | [SiliconFlow Embedding API 不兼容（HTTP 400）](https://github.com/HKUDS/DeepTutor/issues/651) | closed | 2026-07-20 | 2026-07-23 | 2 |
| 652 | PR | [fix(embedding): don't send encoding_format by default for OpenAI-compatible providers](https://github.com/HKUDS/DeepTutor/pull/652) | closed | 2026-07-20 | 2026-07-23 | 1 |
| 654 | PR | [Add Atlas Cloud LLM provider](https://github.com/HKUDS/DeepTutor/pull/654) | closed | 2026-07-20 | 2026-07-23 | 1 |
| 655 | Issue | [优化建议](https://github.com/HKUDS/DeepTutor/issues/655) | open | 2026-07-20 | 2026-08-28 | 1 |
| 656 | Issue | [[Bug]:Bug: OpenAI-compatible endpoint containing "codex" is forced to OpenAI Codex OAut](https://github.com/HKUDS/DeepTutor/issues/656) | closed | 2026-07-21 | 2026-07-23 | 1 |
| 657 | PR | [fix: require explicit OpenAI Codex selection](https://github.com/HKUDS/DeepTutor/pull/657) | closed | 2026-07-21 | 2026-07-23 | 1 |
| 658 | PR | [fix(book): stream long-running operations over WebSocket](https://github.com/HKUDS/DeepTutor/pull/658) | closed | 2026-07-21 | 2026-07-23 | 3 |
| 659 | Issue | [[Bug]: Fresh installs are missing the three Persona presets shown in the documentation](https://github.com/HKUDS/DeepTutor/issues/659) | closed | 2026-07-21 | 2026-07-23 | 1 |
| 660 | Issue | [[Bug]: 设置 模型 嵌入模型  DASH-Scope](https://github.com/HKUDS/DeepTutor/issues/660) | closed | 2026-07-21 | 2026-07-23 | 1 |
| 661 | Issue | [[Feature Request]: 优化智能写作体验](https://github.com/HKUDS/DeepTutor/issues/661) | open | 2026-07-22 | 2026-07-24 | 2 |
| 662 | PR | [fix(cli): catch UnicodeDecodeError in REPL input loop](https://github.com/HKUDS/DeepTutor/pull/662) | closed | 2026-07-22 | 2026-08-13 | 0 |
| 663 | PR | [fix(cli): harden UTF-8 terminal input handling](https://github.com/HKUDS/DeepTutor/pull/663) | closed | 2026-07-22 | 2026-07-23 | 1 |
| 664 | Issue | [[Bug]: Mac PyPI Install Fail](https://github.com/HKUDS/DeepTutor/issues/664) | closed | 2026-07-22 | 2026-07-23 | 1 |
| 665 | Issue | [[Bug]: Book creation fails with 500 error when using DashScope qwen3.7-max (thinking   model + JSON mode conflict)](https://github.com/HKUDS/DeepTutor/issues/665) | closed | 2026-07-23 | 2026-07-23 | 0 |
| 666 | Issue | [[Bug]: deepseek ppt 技能报错,windows 源码部署](https://github.com/HKUDS/DeepTutor/issues/666) | closed | 2026-07-23 | 2026-07-23 | 2 |
| 667 | PR | [fix(question): parse quiz JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/667) | closed | 2026-07-23 | 2026-07-23 | 1 |
| 668 | PR | [fix(utils): decode trailing-prose JSON before repair](https://github.com/HKUDS/DeepTutor/pull/668) | closed | 2026-07-23 | 2026-07-23 | 1 |
| 669 | PR | [fix(visualize): allow code fences without a blank closing line](https://github.com/HKUDS/DeepTutor/pull/669) | closed | 2026-07-23 | 2026-07-23 | 1 |
| 670 | PR | [fix(partners): strip control chars in safe_filename](https://github.com/HKUDS/DeepTutor/pull/670) | closed | 2026-07-23 | 2026-07-23 | 1 |
| 671 | PR | [feat: add Eden AI as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/671) | closed | 2026-07-23 | 2026-07-24 | 1 |
| 672 | Issue | [[Bug]:调用deepseek API 使用Mastery Path时出现错误；Windows本地部署](https://github.com/HKUDS/DeepTutor/issues/672) | closed | 2026-07-23 | 2026-07-24 | 1 |
| 673 | Issue | [[Bug]:parse_json_response does not strip <think> reasoning tags, causing empty BookEngine   proposal fields](https://github.com/HKUDS/DeepTutor/issues/673) | closed | 2026-07-24 | 2026-07-24 | 2 |
| 674 | PR | [fix: prevent sending messages while AI is streaming response](https://github.com/HKUDS/DeepTutor/pull/674) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 675 | PR | [fix(json_parser): strip <think> reasoning tags before parsing](https://github.com/HKUDS/DeepTutor/pull/675) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 677 | Issue | [[Bug]:#487 的答题状态继承问题在 v1.5.3 Quiz custom模式下复现](https://github.com/HKUDS/DeepTutor/issues/677) | closed | 2026-07-24 | 2026-07-24 | 1 |
| 678 | PR | [perf(session): flush buffered turn events in a single transaction](https://github.com/HKUDS/DeepTutor/pull/678) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 679 | PR | [fix(partners): keep empty cells when converting Slack markdown tables](https://github.com/HKUDS/DeepTutor/pull/679) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 680 | PR | [fix(research): parse first JSON value when adjacent values follow](https://github.com/HKUDS/DeepTutor/pull/680) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 681 | PR | [fix(math-animator): do not treat ms as minutes in duration parsing](https://github.com/HKUDS/DeepTutor/pull/681) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 682 | PR | [fix(partners): do not treat empty markdown rows as table separators](https://github.com/HKUDS/DeepTutor/pull/682) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 683 | PR | [fix(partners): keep leading/trailing empty Feishu table cells](https://github.com/HKUDS/DeepTutor/pull/683) | closed | 2026-07-24 | 2026-07-24 | 0 |
| 684 | Issue | [[Feature Request]: Multi-language integration](https://github.com/HKUDS/DeepTutor/issues/684) | open | 2026-07-24 | 2026-08-12 | 4 |
| 685 | PR | [fix(visualize): return empty on extract_code_block language miss](https://github.com/HKUDS/DeepTutor/pull/685) | open | 2026-07-24 | 2026-08-02 | 0 |
| 686 | PR | [fix(visualize): accept trailing prose after Chart.js JSON](https://github.com/HKUDS/DeepTutor/pull/686) | open | 2026-07-24 | 2026-08-02 | 0 |
| 687 | PR | [fix(vision): parse LLM JSON with raw_decode](https://github.com/HKUDS/DeepTutor/pull/687) | open | 2026-07-24 | 2026-08-02 | 0 |
| 688 | PR | [fix(utils): strip edge whitespace in upload filenames](https://github.com/HKUDS/DeepTutor/pull/688) | open | 2026-07-24 | 2026-08-02 | 0 |
| 689 | PR | [fix(partners): require a full-line frontmatter close fence](https://github.com/HKUDS/DeepTutor/pull/689) | open | 2026-07-24 | 2026-08-02 | 0 |
| 690 | PR | [feat: 为 DeepTutor 添加独立 Codex OAuth 与动态模型目录](https://github.com/HKUDS/DeepTutor/pull/690) | closed | 2026-07-24 | 2026-07-26 | 1 |
| 691 | Issue | [[Bug]:input and loaded file will be wiped out, when creating new knowledge base with background indexing going on](https://github.com/HKUDS/DeepTutor/issues/691) | closed | 2026-07-24 | 2026-07-24 | 3 |
| 692 | Issue | [[Bug]: v1.5.3 书籍大纲只生成一个 Overview，忽略预设的 6 个章节](https://github.com/HKUDS/DeepTutor/issues/692) | closed | 2026-07-24 | 2026-07-24 | 1 |
| 693 | PR | [fix: prevent unnecessary re-render by stabilizing provider reference …](https://github.com/HKUDS/DeepTutor/pull/693) | closed | 2026-07-24 | 2026-07-27 | 0 |
| 694 | Issue | [[Bug]: RAG tool/retrieval emits only a query-echo source, no entity/chunk/relation citations](https://github.com/HKUDS/DeepTutor/issues/694) | closed | 2026-07-24 | 2026-08-04 | 3 |
| 695 | Issue | [[Bug]: GraphRAG 3.1.1 indexing is blocked by uvloop and invalid generated settings](https://github.com/HKUDS/DeepTutor/issues/695) | closed | 2026-07-24 | 2026-07-26 | 1 |
| 696 | Issue | [[Bug]:The conflict between scrolling up and streaming output still occurs in "Partner" modules. #649](https://github.com/HKUDS/DeepTutor/issues/696) | closed | 2026-07-25 | 2026-07-26 | 2 |
| 697 | Issue | [[Feature Request]:Preserve focus state after submitting a chat message.](https://github.com/HKUDS/DeepTutor/issues/697) | closed | 2026-07-25 | 2026-07-29 | 1 |
| 698 | Issue | [[Bug]:Assistant replies intermittently disappear from chat; next turn loses context (orphaned branch via stale parent_message_id)](https://github.com/HKUDS/DeepTutor/issues/698) | closed | 2026-07-25 | 2026-08-04 | 4 |
| 699 | PR | [fix(rag): escape $ in GraphRAG file_pattern, fix cache type](https://github.com/HKUDS/DeepTutor/pull/699) | closed | 2026-07-25 | 2026-07-26 | 0 |
| 701 | Issue | [[Bug]: claude-opus-5 always fails with `temperature` is deprecated — `opus-5` missing from _EFFORT_BASED_FAMILIES](https://github.com/HKUDS/DeepTutor/issues/701) | closed | 2026-07-25 | 2026-07-26 | 1 |
| 702 | Issue | [[Bug]: deeptutor start loses all frontend logs on non-UTF-8 Windows code pages (UnicodeEncodeError kills _stream_output)](https://github.com/HKUDS/DeepTutor/issues/702) | closed | 2026-07-25 | 2026-07-26 | 1 |
| 703 | PR | [fix(llm): add opus-5 to the Anthropic effort-based family list](https://github.com/HKUDS/DeepTutor/pull/703) | closed | 2026-07-25 | 2026-07-26 | 0 |
| 704 | PR | [fix(web): respect manual scrolling in partner chat](https://github.com/HKUDS/DeepTutor/pull/704) | closed | 2026-07-26 | 2026-07-26 | 0 |
| 705 | Issue | [Reconnect after a turn completes drops the DONE event's message ids (root cause of #698)](https://github.com/HKUDS/DeepTutor/issues/705) | closed | 2026-07-26 | 2026-08-16 | 2 |
| 706 | PR | [fix: persist DONE event ids before a completed turn's execution is popped](https://github.com/HKUDS/DeepTutor/pull/706) | closed | 2026-07-26 | 2026-08-16 | 1 |
| 707 | PR | [fix: book creation timeout and spine single-chapter fallback](https://github.com/HKUDS/DeepTutor/pull/707) | closed | 2026-07-26 | 2026-07-27 | 0 |
| 708 | Issue | [[Bug]:GTP Luna, Terra, and Sol fail to call tools](https://github.com/HKUDS/DeepTutor/issues/708) | closed | 2026-07-26 | 2026-08-29 | 12 |
| 709 | Issue | [deeptutor start crashes MODULE_NOT_FOUND source install](https://github.com/HKUDS/DeepTutor/issues/709) | closed | 2026-07-26 | 2026-07-27 | 1 |
| 710 | PR | [fix(launcher): auto-run npm ci when web/node_modules is missing on source install](https://github.com/HKUDS/DeepTutor/pull/710) | closed | 2026-07-26 | 2026-07-27 | 0 |
| 711 | Issue | [[Bug]: Partners/subagents fail to authenticate with OpenAI Codex (Sign in to Codex)](https://github.com/HKUDS/DeepTutor/issues/711) | closed | 2026-07-26 | 2026-07-27 | 1 |
| 712 | Issue | [[Bug]: parse_language() collapses every non-English language code to Chinese (ja/ko/de/fr/... -> zh)](https://github.com/HKUDS/DeepTutor/issues/712) | closed | 2026-07-27 | 2026-07-27 | 1 |
| 713 | PR | [fix(codex-auth): resolve credentials to admin root for partner scopes](https://github.com/HKUDS/DeepTutor/pull/713) | closed | 2026-07-27 | 2026-07-27 | 0 |
| 714 | Issue | [[Spec] 獨立試卷庫與 Original Paper 原卷測驗](https://github.com/HKUDS/DeepTutor/issues/714) | closed | 2026-07-27 | 2026-07-27 | 1 |
| 715 | PR | [fix: parse_language() collapses non-English codes to Chinese](https://github.com/HKUDS/DeepTutor/pull/715) | closed | 2026-07-27 | 2026-07-27 | 1 |
| 716 | PR | [fix: guide remote Codex OAuth loopback callbacks](https://github.com/HKUDS/DeepTutor/pull/716) | closed | 2026-07-27 | 2026-07-28 | 1 |
| 717 | PR | [fix: update lazy imports to use absolute paths for service modules](https://github.com/HKUDS/DeepTutor/pull/717) | closed | 2026-07-27 | 2026-07-28 | 0 |
| 718 | PR | [fix: localize admin user management UI](https://github.com/HKUDS/DeepTutor/pull/718) | closed | 2026-07-28 | 2026-07-29 | 0 |
| 719 | PR | [feat: add immersive reading workspace](https://github.com/HKUDS/DeepTutor/pull/719) | open | 2026-07-28 | 2026-09-24 | 8 |
| 720 | PR | [fix: preserve chat input focus after sending](https://github.com/HKUDS/DeepTutor/pull/720) | closed | 2026-07-28 | 2026-07-29 | 0 |
| 721 | PR | [fix(chat): restore scroll position when switching sessions](https://github.com/HKUDS/DeepTutor/pull/721) | closed | 2026-07-28 | 2026-07-29 | 0 |
| 722 | PR | [ci: attach provenance and SBOM attestations to the released image](https://github.com/HKUDS/DeepTutor/pull/722) | closed | 2026-07-28 | 2026-07-29 | 1 |
| 723 | PR | [Feat/merge 1.5.2](https://github.com/HKUDS/DeepTutor/pull/723) | closed | 2026-07-29 | 2026-07-29 | 0 |
| 724 | PR | [Refresh MiniMax endpoints and add MiniMax-M3 context-window metadata](https://github.com/HKUDS/DeepTutor/pull/724) | closed | 2026-07-29 | 2026-08-03 | 0 |
| 725 | Issue | [[Feature Request]:Auto-update button](https://github.com/HKUDS/DeepTutor/issues/725) | open | 2026-07-30 | 2026-09-02 | 1 |
| 726 | PR | [feat(settings): expose language switcher](https://github.com/HKUDS/DeepTutor/pull/726) | closed | 2026-07-30 | 2026-08-06 | 1 |
| 727 | Issue | [[Docs]: Feature request: Support Responses API for custom OpenAI-compatible providers](https://github.com/HKUDS/DeepTutor/issues/727) | closed | 2026-07-30 | 2026-08-25 | 2 |
| 728 | PR | [feat(i18n): add complete Spanish (Spain) localization](https://github.com/HKUDS/DeepTutor/pull/728) | open | 2026-07-30 | 2026-09-27 | 13 |
| 729 | Issue | [Interface language preference is ignored on first app load](https://github.com/HKUDS/DeepTutor/issues/729) | closed | 2026-07-31 | 2026-08-04 | 1 |
| 730 | PR | [fix: bootstrap persisted interface language on first load](https://github.com/HKUDS/DeepTutor/pull/730) | closed | 2026-07-31 | 2026-08-03 | 0 |
| 731 | Issue | [Capability failures render as blank assistant messages and persist completed status](https://github.com/HKUDS/DeepTutor/issues/731) | closed | 2026-07-31 | 2026-08-04 | 1 |
| 732 | PR | [Fix terminal capability error handling](https://github.com/HKUDS/DeepTutor/pull/732) | closed | 2026-07-31 | 2026-08-03 | 0 |
| 733 | PR | [fix(auth): use _COOKIE_NAME constant in /status cookie parameter](https://github.com/HKUDS/DeepTutor/pull/733) | closed | 2026-07-31 | 2026-08-03 | 0 |
| 734 | Issue | [Gemini 3 models fail with 400 INVALID_ARGUMENT — reasoning_effort="none" is only valid for Gemini 2.5 non-Pro](https://github.com/HKUDS/DeepTutor/issues/734) | closed | 2026-07-31 | 2026-08-12 | 1 |
| 735 | Issue | [[Feature Request]: Add per-model reasoning effort defaults to LLM settings](https://github.com/HKUDS/DeepTutor/issues/735) | closed | 2026-07-31 | 2026-08-04 | 2 |
| 736 | PR | [feat: add per-model reasoning effort setting](https://github.com/HKUDS/DeepTutor/pull/736) | closed | 2026-07-31 | 2026-08-03 | 0 |
| 737 | Issue | [math_animator prompt assets and capability failures need terminal handling](https://github.com/HKUDS/DeepTutor/issues/737) | closed | 2026-07-31 | 2026-08-06 | 2 |
| 738 | PR | [fix: make prompt loading and capability failures terminal](https://github.com/HKUDS/DeepTutor/pull/738) | closed | 2026-07-31 | 2026-08-06 | 0 |
| 739 | Issue | [[Bug]:非首条请求在首次编辑改动时无法保存](https://github.com/HKUDS/DeepTutor/issues/739) | closed | 2026-07-31 | 2026-08-29 | 3 |
| 740 | Issue | [[Feature Request]:  Introduce stateful persistent learning(state referencing Matt Pocock's /teach skill design)](https://github.com/HKUDS/DeepTutor/issues/740) | open | 2026-07-31 | 2026-07-31 | 0 |
| 742 | PR | [fix: return minimal reasoning_effort for Gemini 3 and 2.5 Pro](https://github.com/HKUDS/DeepTutor/pull/742) | closed | 2026-08-01 | 2026-08-01 | 0 |
| 743 | PR | [fix: make local container Codex OAuth bridge temporary](https://github.com/HKUDS/DeepTutor/pull/743) | closed | 2026-08-01 | 2026-08-03 | 0 |
| 744 | PR | [feat(embedding): support Gemini Embedding 2 native RAG](https://github.com/HKUDS/DeepTutor/pull/744) | closed | 2026-08-01 | 2026-08-03 | 0 |
| 745 | Issue | [[Bug]: GraphRAG request configuration diverges from DeepTutor chat and embedding profiles](https://github.com/HKUDS/DeepTutor/issues/745) | open | 2026-08-01 | 2026-08-28 | 3 |
| 746 | PR | [Add Novita AI as a provider option](https://github.com/HKUDS/DeepTutor/pull/746) | closed | 2026-08-01 | 2026-08-03 | 0 |
| 747 | PR | [fix(knowledge): harden GraphRAG model and embedding compatibility](https://github.com/HKUDS/DeepTutor/pull/747) | closed | 2026-08-01 | 2026-08-16 | 0 |
| 748 | PR | [fix(visualize): guard against invalid visual_genre crashing generation](https://github.com/HKUDS/DeepTutor/pull/748) | closed | 2026-08-01 | 2026-08-03 | 0 |
| 749 | Issue | [[Question]:knowledge页面一直显示“Unexpected token 'I', "Internal S"... is not valid JSON”](https://github.com/HKUDS/DeepTutor/issues/749) | closed | 2026-08-02 | 2026-08-10 | 2 |
| 750 | PR | [Codex/mobile responsive](https://github.com/HKUDS/DeepTutor/pull/750) | closed | 2026-08-02 | 2026-08-02 | 0 |
| 751 | PR | [feat(update): add installation-aware updates for Web and CLI](https://github.com/HKUDS/DeepTutor/pull/751) | open | 2026-08-02 | 2026-08-08 | 3 |
| 752 | Issue | [ResearchPipeline mounts rag tool for Obsidian KBs, producing spurious warnings](https://github.com/HKUDS/DeepTutor/issues/752) | closed | 2026-08-02 | 2026-08-06 | 3 |
| 753 | PR | [fix(web): resolve optimistic edit refresh race](https://github.com/HKUDS/DeepTutor/pull/753) | closed | 2026-08-02 | 2026-08-06 | 0 |
| 754 | PR | [fix: surface local LightRAG provenance](https://github.com/HKUDS/DeepTutor/pull/754) | closed | 2026-08-02 | 2026-08-24 | 0 |
| 755 | Issue | [[Bug]: GET /{kb_name}/files returns 500 for lightrag_server (connected) knowledge bases — no local raw/ dir exists by design](https://github.com/HKUDS/DeepTutor/issues/755) | closed | 2026-08-02 | 2026-08-09 | 5 |
| 756 | PR | [fix(research): mount read-only Obsidian tools instead of rag for vault KBs](https://github.com/HKUDS/DeepTutor/pull/756) | closed | 2026-08-03 | 2026-08-06 | 0 |
| 757 | Issue | [Decouple Web UI language from model response language](https://github.com/HKUDS/DeepTutor/issues/757) | closed | 2026-08-03 | 2026-08-06 | 1 |
| 758 | PR | [feat: separate UI and model response languages](https://github.com/HKUDS/DeepTutor/pull/758) | closed | 2026-08-03 | 2026-08-06 | 0 |
| 759 | Issue | [[Bug]: Windows: npm-installed Claude Code / Codex reported 'not installed' (CreateProcess can't resolve .cmd shims)](https://github.com/HKUDS/DeepTutor/issues/759) | closed | 2026-08-03 | 2026-08-17 | 13 |
| 760 | Issue | [Auth pages (/register, /login) stay English on first load — statically prerendered, not covered by #730](https://github.com/HKUDS/DeepTutor/issues/760) | closed | 2026-08-03 | 2026-08-06 | 9 |
| 761 | Issue | [[Bug]:Event Loop blocked by CPU-bound JSON serialization during large VDB merges, causing widespread LLM Request timeouts in final doc indexing stage](https://github.com/HKUDS/DeepTutor/issues/761) | closed | 2026-08-04 | 2026-08-09 | 8 |
| 762 | Issue | [[Feature Request / Question]: System dependencies and pip extras do not persist across Docker container recreations](https://github.com/HKUDS/DeepTutor/issues/762) | closed | 2026-08-04 | 2026-08-25 | 3 |
| 763 | PR | [fix(api): expose GET /api/v1/settings/ui without auth for pre-session language bootstrap](https://github.com/HKUDS/DeepTutor/pull/763) | closed | 2026-08-04 | 2026-08-06 | 0 |
| 764 | PR | [fix: match Claude model ids in vision capability overrides](https://github.com/HKUDS/DeepTutor/pull/764) | closed | 2026-08-04 | 2026-08-06 | 0 |
| 765 | PR | [feat: mark Kimi K3 as vision capable](https://github.com/HKUDS/DeepTutor/pull/765) | closed | 2026-08-04 | 2026-08-06 | 1 |
| 766 | Issue | [[Bug]: Partner responses cannot be stopped with Esc](https://github.com/HKUDS/DeepTutor/issues/766) | closed | 2026-08-04 | 2026-08-06 | 29 |
| 767 | Issue | [[Bug]: Partner chat still loses composer focus after sending or switching tabs](https://github.com/HKUDS/DeepTutor/issues/767) | closed | 2026-08-04 | 2026-08-23 | 2 |
| 768 | Issue | [[Bug]: Partner chat stays on "Connecting..." after the tab has been inactive](https://github.com/HKUDS/DeepTutor/issues/768) | closed | 2026-08-04 | 2026-08-23 | 2 |
| 769 | Issue | [[Bug] Chat home shows "模型加载中" indefinitely; forced send → "无法连接服务器" (no retry on ReadError/ConnectTimeout)](https://github.com/HKUDS/DeepTutor/issues/769) | closed | 2026-08-04 | 2026-08-23 | 3 |
| 770 | PR | [fix: recognize Qwen3.8-Max as vision-capable](https://github.com/HKUDS/DeepTutor/pull/770) | closed | 2026-08-04 | 2026-08-06 | 1 |
| 771 | PR | [feat: integrate liteparse as a document parsing engine](https://github.com/HKUDS/DeepTutor/pull/771) | closed | 2026-08-05 | 2026-08-12 | 0 |
| 772 | PR | [fix: bound conversation compaction budgets](https://github.com/HKUDS/DeepTutor/pull/772) | closed | 2026-08-05 | 2026-08-25 | 0 |
| 773 | Issue | [[Feature Request]: Add CodeBuddy/WorkBuddy as a provider](https://github.com/HKUDS/DeepTutor/issues/773) | closed | 2026-08-05 | 2026-08-12 | 8 |
| 774 | PR | [fix(codex): preserve OAuth model context window metadata](https://github.com/HKUDS/DeepTutor/pull/774) | closed | 2026-08-05 | 2026-08-06 | 0 |
| 775 | Issue | [[Feature Request]: Add an Ask Questions mode for proactive clarification before answering](https://github.com/HKUDS/DeepTutor/issues/775) | closed | 2026-08-05 | 2026-08-25 | 4 |
| 776 | PR | [feat(chat): add AskQuestions mode for contextual clarification](https://github.com/HKUDS/DeepTutor/pull/776) | closed | 2026-08-05 | 2026-08-25 | 0 |
| 777 | Issue | [[Bug]:Batch‑uploading files blocks all requests, which should be a bug in FastAPI's  BackgroundTasks](https://github.com/HKUDS/DeepTutor/issues/777) | closed | 2026-08-05 | 2026-08-08 | 5 |
| 778 | PR | [fix: avoid repeated knowledge-base scans in list endpoint](https://github.com/HKUDS/DeepTutor/pull/778) | closed | 2026-08-05 | 2026-08-06 | 0 |
| 779 | Issue | [[Bug]:write_note/exec tool calls intermittently arrive with empty arguments (missing required mode/command), loop repeats and wastes tokens](https://github.com/HKUDS/DeepTutor/issues/779) | closed | 2026-08-05 | 2026-08-08 | 1 |
| 780 | PR | [feat(provider): add codebuddy as a LLM provider](https://github.com/HKUDS/DeepTutor/pull/780) | closed | 2026-08-05 | 2026-08-12 | 0 |
| 781 | Issue | [[Feature Request]: Support per-user OpenAI Codex OAuth in multi-user deployments](https://github.com/HKUDS/DeepTutor/issues/781) | closed | 2026-08-05 | 2026-08-07 | 2 |
| 782 | Issue | [[Bug]:Frontend proxy returns 500 on Windows local deployment due to localhost IPv6 resolution](https://github.com/HKUDS/DeepTutor/issues/782) | closed | 2026-08-05 | 2026-08-07 | 5 |
| 783 | PR | [fix: stop Partner responses with Escape](https://github.com/HKUDS/DeepTutor/pull/783) | closed | 2026-08-05 | 2026-08-08 | 1 |
| 784 | PR | [fix: use IPv4 loopback for frontend proxy](https://github.com/HKUDS/DeepTutor/pull/784) | closed | 2026-08-06 | 2026-08-06 | 0 |
| 785 | PR | [[Bug]:Frontend proxy returns 500 on Windows local deployment due to localhost IPv6 resolution](https://github.com/HKUDS/DeepTutor/pull/785) | closed | 2026-08-06 | 2026-08-07 | 1 |
| 786 | PR | [fix(web): repair malformed strong-emphasis spacing in assistant output](https://github.com/HKUDS/DeepTutor/pull/786) | closed | 2026-08-07 | 2026-08-12 | 0 |
| 788 | Issue | [[Bug]:DeepTutor 前端的 React bug](https://github.com/HKUDS/DeepTutor/issues/788) | closed | 2026-08-07 | 2026-08-29 | 1 |
| 789 | PR | [feat(codex): persist managed reasoning effort overrides](https://github.com/HKUDS/DeepTutor/pull/789) | closed | 2026-08-07 | 2026-08-12 | 1 |
| 790 | Issue | [[Bug]:Multi-user File Download Fails with 404 "Output not found" on /api/outputs](https://github.com/HKUDS/DeepTutor/issues/790) | closed | 2026-08-07 | 2026-08-09 | 1 |
| 791 | PR | [Create ARQUITECTURA.md](https://github.com/HKUDS/DeepTutor/pull/791) | closed | 2026-08-07 | 2026-08-23 | 1 |
| 792 | Issue | [MCP server 'pageindex': connect timed out after 15s — missing 'mcp' dependency on standard install (ModuleNotFoundError)](https://github.com/HKUDS/DeepTutor/issues/792) | closed | 2026-08-08 | 2026-08-17 | 0 |
| 793 | Issue | [[Question]:Persona settings not working properly](https://github.com/HKUDS/DeepTutor/issues/793) | closed | 2026-08-08 | 2026-08-31 | 2 |
| 794 | Issue | [[Bug]: CLI /tool on 后状态行 tools= 显示为空，方括号内容被 Rich 吞掉](https://github.com/HKUDS/DeepTutor/issues/794) | closed | 2026-08-08 | 2026-08-09 | 1 |
| 795 | Issue | [[Bug]: 跨 turn 的 mastery 选择题因选项标签错位被误判为错误](https://github.com/HKUDS/DeepTutor/issues/795) | closed | 2026-08-08 | 2026-08-09 | 2 |
| 796 | Issue | [[Question]:现在没有账号系统吗？](https://github.com/HKUDS/DeepTutor/issues/796) | closed | 2026-08-08 | 2026-08-23 | 2 |
| 797 | Issue | [[Bug]: mastery_quiz 未设 question_type=choice 时，选择题按短答判分导致正确答案必错](https://github.com/HKUDS/DeepTutor/issues/797) | closed | 2026-08-08 | 2026-08-09 | 1 |
| 798 | Issue | [[Bug]: 回合预算/Token 耗尽时 pending_question 状态不一致，导致后续轮次必出判分错误](https://github.com/HKUDS/DeepTutor/issues/798) | closed | 2026-08-08 | 2026-08-09 | 1 |
| 799 | Issue | [[Bug]:DeepSeek DSML tool-call markup leaks into content channel — answer text flashes then disappears](https://github.com/HKUDS/DeepTutor/issues/799) | closed | 2026-08-08 | 2026-08-09 | 1 |
| 800 | PR | [fix: resolve generated-output downloads per user](https://github.com/HKUDS/DeepTutor/pull/800) | closed | 2026-08-08 | 2026-08-24 | 2 |
| 801 | Issue | [[Bug]: 可视化教学板块高度未随内容变化而更新，始终保持历史最大高度](https://github.com/HKUDS/DeepTutor/issues/801) | closed | 2026-08-08 | 2026-08-09 | 3 |
| 802 | PR | [fix(web): settle scroll to bottom after loading chat history](https://github.com/HKUDS/DeepTutor/pull/802) | closed | 2026-08-08 | 2026-08-12 | 0 |
| 804 | PR | [fix(visualize): update iframe height when content shrinks](https://github.com/HKUDS/DeepTutor/pull/804) | closed | 2026-08-09 | 2026-08-12 | 2 |
| 805 | Issue | [[Bug]:前端对话框不定时显示模型加载中](https://github.com/HKUDS/DeepTutor/issues/805) | closed | 2026-08-09 | 2026-08-09 | 1 |
| 806 | Issue | [[Bug]:升级DeepTutor后，之前的Knowledge Center/ Notebooks / Chat / Partners 数据消失](https://github.com/HKUDS/DeepTutor/issues/806) | closed | 2026-08-10 | 2026-08-10 | 0 |
| 807 | Issue | [[Feature Request]: Automatically route explicit quiz requests from Chat to deep_question](https://github.com/HKUDS/DeepTutor/issues/807) | closed | 2026-08-10 | 2026-08-31 | 1 |
| 808 | Issue | [[Bug]:AttributeError: 'list' object has no attribute 'get' in citation_manager.py when extracting list-based RAG source info](https://github.com/HKUDS/DeepTutor/issues/808) | closed | 2026-08-10 | 2026-08-12 | 1 |
| 809 | PR | [fix: return minimal reasoning_effort for Gemini 3 and 2.5 Pro](https://github.com/HKUDS/DeepTutor/pull/809) | closed | 2026-08-10 | 2026-08-12 | 0 |
| 810 | Issue | [[Bug]: Mastery Path ID is coupled to the chat session, preventing fresh sessions for an existing path](https://github.com/HKUDS/DeepTutor/issues/810) | closed | 2026-08-10 | 2026-08-12 | 1 |
| 811 | PR | [feat: make Deep Research lifecycle-aware and recoverable](https://github.com/HKUDS/DeepTutor/pull/811) | closed | 2026-08-10 | 2026-08-10 | 1 |
| 812 | PR | [fix(research): handle list-shaped RAG sources](https://github.com/HKUDS/DeepTutor/pull/812) | closed | 2026-08-11 | 2026-08-12 | 1 |
| 813 | PR | [fix(mcp): reconnect on credential change; stop reporting transport failures as tool timeouts](https://github.com/HKUDS/DeepTutor/pull/813) | closed | 2026-08-11 | 2026-08-12 | 0 |
| 814 | Issue | [[Feature Request]: Enable multimodal inputs for Gemini Embedding 2](https://github.com/HKUDS/DeepTutor/issues/814) | closed | 2026-08-11 | 2026-08-25 | 1 |
| 815 | Issue | [[Bug]: Tencent IMA provider uses upload flow; connect form and preflight are missing](https://github.com/HKUDS/DeepTutor/issues/815) | closed | 2026-08-11 | 2026-08-11 | 0 |
| 816 | Issue | [[Bug]: Partner 创建 Mind 步骤未反映 Settings→Chat→Tools 的工具开关状态](https://github.com/HKUDS/DeepTutor/issues/816) | closed | 2026-08-11 | 2026-08-23 | 1 |
| 817 | Issue | [[Bug]:python dep typer extra problem](https://github.com/HKUDS/DeepTutor/issues/817) | closed | 2026-08-11 | 2026-08-12 | 1 |
| 818 | PR | [feat: add OrcaRouter as a named OpenAI-compatible gateway provider](https://github.com/HKUDS/DeepTutor/pull/818) | closed | 2026-08-11 | 2026-08-12 | 0 |
| 819 | Issue | [[Bug]: Knowledge bases built via the Web UI / add_documents API silently have zero embeddings — vector retrieval never works](https://github.com/HKUDS/DeepTutor/issues/819) | closed | 2026-08-11 | 2026-08-11 | 0 |
| 820 | PR | [fix(rag): run embed sync hooks on a worker thread when an event loop is already running](https://github.com/HKUDS/DeepTutor/pull/820) | closed | 2026-08-11 | 2026-08-11 | 1 |
| 821 | PR | [fix(llm): mark OpenAI Codex as vision capable](https://github.com/HKUDS/DeepTutor/pull/821) | closed | 2026-08-11 | 2026-08-13 | 0 |
| 822 | PR | [docs: add Traditional Chinese README](https://github.com/HKUDS/DeepTutor/pull/822) | closed | 2026-08-11 | 2026-08-16 | 0 |
| 823 | PR | [feat(kids): isolate family kids library, harden reading sessions, and supervision](https://github.com/HKUDS/DeepTutor/pull/823) | closed | 2026-08-12 | 2026-08-24 | 3 |
| 824 | Issue | [feat(assessment): unify persisted quiz and focus-check review](https://github.com/HKUDS/DeepTutor/issues/824) | closed | 2026-08-12 | 2026-08-31 | 2 |
| 825 | Issue | [[Bug]: Responses tool arguments are dropped for item_id events or Markdown-fenced content](https://github.com/HKUDS/DeepTutor/issues/825) | closed | 2026-08-12 | 2026-08-12 | 1 |
| 826 | PR | [fix: preserve Responses tool call arguments](https://github.com/HKUDS/DeepTutor/pull/826) | closed | 2026-08-12 | 2026-08-12 | 2 |
| 827 | Issue | [[Bug]: partner channel with empty allow_from crashes the whole backend at startup (SystemExit instead of isolating the misconfiguration)](https://github.com/HKUDS/DeepTutor/issues/827) | closed | 2026-08-12 | 2026-08-23 | 3 |
| 828 | Issue | [[Bug]:请把伙伴和智能体 Gemini CLI替换到Antigravity CLI](https://github.com/HKUDS/DeepTutor/issues/828) | closed | 2026-08-12 | 2026-08-25 | 2 |
| 829 | PR | [fix: propagate Responses stream failures](https://github.com/HKUDS/DeepTutor/pull/829) | closed | 2026-08-12 | 2026-08-16 | 0 |
| 830 | PR | [fix(mcp): preserve image content for multimodal tools](https://github.com/HKUDS/DeepTutor/pull/830) | closed | 2026-08-12 | 2026-08-13 | 1 |
| 831 | Issue | [[Feature Request]: Add remote document parser (Docling/Tika) support](https://github.com/HKUDS/DeepTutor/issues/831) | closed | 2026-08-12 | 2026-08-25 | 1 |
| 832 | PR | [Guruai/mvp sinhala tutor](https://github.com/HKUDS/DeepTutor/pull/832) | closed | 2026-08-12 | 2026-08-12 | 0 |
| 834 | PR | [feat(rag): index parser visual structure with language-aware companions](https://github.com/HKUDS/DeepTutor/pull/834) | closed | 2026-08-12 | 2026-08-13 | 2 |
| 835 | Issue | [[Feature Request]: Preserve structured parser visuals in LlamaIndex ingestion](https://github.com/HKUDS/DeepTutor/issues/835) | closed | 2026-08-12 | 2026-08-13 | 2 |
| 836 | PR | [feat(marginnote4): Phase 1 — connected KB type, read-only tools, and sync bridge](https://github.com/HKUDS/DeepTutor/pull/836) | closed | 2026-08-12 | 2026-08-22 | 2 |
| 837 | PR | [feat(rag): preserve structured parser visuals](https://github.com/HKUDS/DeepTutor/pull/837) | closed | 2026-08-12 | 2026-08-13 | 1 |
| 838 | PR | [fix: make Ruff pre-commit hook fail on lint errors](https://github.com/HKUDS/DeepTutor/pull/838) | closed | 2026-08-12 | 2026-08-16 | 0 |
| 839 | Issue | [怎么连接 ima 呢，感觉可以连上，但是知识库里面的文档为 0](https://github.com/HKUDS/DeepTutor/issues/839) | closed | 2026-08-13 | 2026-08-23 | 4 |
| 840 | Issue | [[Bug]:Concept and design knowledge points are never added to the spaced-review queue](https://github.com/HKUDS/DeepTutor/issues/840) | closed | 2026-08-13 | 2026-08-19 | 2 |
| 841 | Issue | [[Docs]: Should add migration guidance](https://github.com/HKUDS/DeepTutor/issues/841) | closed | 2026-08-13 | 2026-08-31 | 1 |
| 842 | PR | [feat: add EPUB support for knowledge base](https://github.com/HKUDS/DeepTutor/pull/842) | closed | 2026-08-13 | 2026-08-13 | 0 |
| 843 | PR | [feat: add EPUB support for knowledge base](https://github.com/HKUDS/DeepTutor/pull/843) | closed | 2026-08-13 | 2026-08-16 | 0 |
| 844 | PR | [fix: Windows MinerU parsing — subprocess UTF-8 decoding & render-thread crash](https://github.com/HKUDS/DeepTutor/pull/844) | closed | 2026-08-13 | 2026-08-24 | 0 |
| 845 | PR | [feat: Add remote Docling Serve parsing support](https://github.com/HKUDS/DeepTutor/pull/845) | closed | 2026-08-13 | 2026-08-16 | 0 |
| 846 | Issue | [[Feature Request]: Support DeepSeek Responses API and native server-side web search](https://github.com/HKUDS/DeepTutor/issues/846) | closed | 2026-08-13 | 2026-08-29 | 5 |
| 847 | PR | [fix(rag): run document parsing off the event loop (KB indexing stalls all requests)](https://github.com/HKUDS/DeepTutor/pull/847) | closed | 2026-08-13 | 2026-09-24 | 0 |
| 848 | PR | [fix(mcp): omit image payloads from tool text](https://github.com/HKUDS/DeepTutor/pull/848) | closed | 2026-08-13 | 2026-08-16 | 1 |
| 849 | Issue | [Env-bootstrapped admin: first account created via /admin/users is silently promoted to admin, then the bootstrap admin is locked out (multi_user/identity.py)](https://github.com/HKUDS/DeepTutor/issues/849) | closed | 2026-08-13 | 2026-08-17 | 0 |
| 850 | PR | [fix: sync partner tool list with global chat tool toggles](https://github.com/HKUDS/DeepTutor/pull/850) | closed | 2026-08-14 | 2026-08-16 | 0 |
| 851 | PR | [fix: Keep env-bootstrapped admin usable and unpromoted (#849)](https://github.com/HKUDS/DeepTutor/pull/851) | closed | 2026-08-14 | 2026-08-16 | 0 |
| 852 | PR | [fix: Install mcp by default so pageindex MCP connects](https://github.com/HKUDS/DeepTutor/pull/852) | closed | 2026-08-14 | 2026-08-16 | 0 |
| 853 | PR | [fix(subagent): resolve .cmd shims on Windows before spawning CLIs](https://github.com/HKUDS/DeepTutor/pull/853) | closed | 2026-08-14 | 2026-08-16 | 0 |
| 854 | PR | [chore: update codebuddy dependency to version 0.2 in pyproject.toml](https://github.com/HKUDS/DeepTutor/pull/854) | closed | 2026-08-14 | 2026-08-19 | 1 |
| 855 | Issue | [[Bug]: The markdown explanation gets suppressed in quizzes in mastery mode](https://github.com/HKUDS/DeepTutor/issues/855) | closed | 2026-08-14 | 2026-08-19 | 2 |
| 856 | PR | [fix: preserve console exception tracebacks](https://github.com/HKUDS/DeepTutor/pull/856) | closed | 2026-08-14 | 2026-08-17 | 0 |
| 857 | Issue | [[Security] Unauthenticated GET /api/v1/settings exposes LLM API keys (catalog) via local_admin fallback](https://github.com/HKUDS/DeepTutor/issues/857) | closed | 2026-08-14 | 2026-08-19 | 2 |
| 858 | PR | [fix: filter thinking tags from non-SSE local provider streams](https://github.com/HKUDS/DeepTutor/pull/858) | closed | 2026-08-14 | 2026-08-19 | 0 |
| 859 | Issue | [[Bug]: kb list / GET /api/v1/knowledge/list extremely slow (~40s CLI, ~10s HTTP) — repeated full parses of multi-MB docstore.json](https://github.com/HKUDS/DeepTutor/issues/859) | closed | 2026-08-14 | 2026-08-23 | 2 |
| 860 | Issue | [feat(reading): complete bilingual EPUB study experience](https://github.com/HKUDS/DeepTutor/issues/860) | open | 2026-08-15 | 2026-08-25 | 1 |
| 861 | Issue | [feat(kids): add parent-managed EPUB reading mode](https://github.com/HKUDS/DeepTutor/issues/861) | closed | 2026-08-15 | 2026-08-25 | 2 |
| 862 | Issue | [feat(knowledge): connect GitHub and web knowledge sources](https://github.com/HKUDS/DeepTutor/issues/862) | closed | 2026-08-15 | 2026-08-25 | 1 |
| 863 | PR | [fix(runtime): reject invalid runtime homes and placeholder OpenAI keys](https://github.com/HKUDS/DeepTutor/pull/863) | closed | 2026-08-15 | 2026-08-17 | 0 |
| 864 | PR | [fix(rag): improve local LlamaIndex pipeline compatibility](https://github.com/HKUDS/DeepTutor/pull/864) | closed | 2026-08-15 | 2026-08-24 | 0 |
| 865 | PR | [chore(web): stop tracking Next build output and enforce repo hygiene](https://github.com/HKUDS/DeepTutor/pull/865) | closed | 2026-08-15 | 2026-08-16 | 0 |
| 866 | Issue | [[Bug]:  Directory hierarchy lost when adding external subfolders to knowledge base](https://github.com/HKUDS/DeepTutor/issues/866) | closed | 2026-08-15 | 2026-08-20 | 1 |
| 867 | Issue | [[Bug]:BwrapBackend lacks virtualenv support (venv/uv) under PEP 668 compliance](https://github.com/HKUDS/DeepTutor/issues/867) | closed | 2026-08-15 | 2026-08-19 | 2 |
| 868 | Issue | [[Bug]: Web UI fails to create knowledge base when uploading multiple large PDFs (HTTP 500 via frontend proxy)](https://github.com/HKUDS/DeepTutor/issues/868) | closed | 2026-08-15 | 2026-08-23 | 2 |
| 869 | PR | [fix(sessions): ensure cleanup of mastery path on session deletion](https://github.com/HKUDS/DeepTutor/pull/869) | closed | 2026-08-15 | 2026-08-16 | 0 |
| 870 | PR | [fix: cache and dedupe docstore probes in kb list / knowledge API (#859)](https://github.com/HKUDS/DeepTutor/pull/870) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 871 | PR | [feat: rename product to Lumen and add settings modal](https://github.com/HKUDS/DeepTutor/pull/871) | closed | 2026-08-16 | 2026-08-16 | 1 |
| 872 | PR | [fix: harden post-merge cleanup and image loading](https://github.com/HKUDS/DeepTutor/pull/872) | closed | 2026-08-16 | 2026-08-19 | 0 |
| 873 | PR | [修复 IMA 只读连接与原文检索](https://github.com/HKUDS/DeepTutor/pull/873) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 874 | PR | [测试：兼容 Codex 推理设置的多行调用](https://github.com/HKUDS/DeepTutor/pull/874) | closed | 2026-08-16 | 2026-08-23 | 1 |
| 875 | PR | [feat: Add remote Tika parsing support](https://github.com/HKUDS/DeepTutor/pull/875) | closed | 2026-08-16 | 2026-08-19 | 2 |
| 876 | PR | [fix(security): redact model catalog secrets](https://github.com/HKUDS/DeepTutor/pull/876) | closed | 2026-08-16 | 2026-08-19 | 0 |
| 877 | PR | [feat: expose LightRAG concurrency and extraction knobs in settings](https://github.com/HKUDS/DeepTutor/pull/877) | closed | 2026-08-16 | 2026-08-19 | 0 |
| 878 | PR | [test: restore lint and source contract baseline](https://github.com/HKUDS/DeepTutor/pull/878) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 879 | PR | [fix: isolate Partner sessions and memory per user](https://github.com/HKUDS/DeepTutor/pull/879) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 880 | PR | [Fix missing assistant responses in Course Chat](https://github.com/HKUDS/DeepTutor/pull/880) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 881 | PR | [fix: isolate invalid Partner channel configs](https://github.com/HKUDS/DeepTutor/pull/881) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 882 | PR | [fix: use Responses API for OpenAI GPT-5 agentic tools](https://github.com/HKUDS/DeepTutor/pull/882) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 883 | PR | [fix: schedule qualitative mastery reviews](https://github.com/HKUDS/DeepTutor/pull/883) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 884 | PR | [fix: keep mastery teaching content visible](https://github.com/HKUDS/DeepTutor/pull/884) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 885 | PR | [fix: stream large knowledge uploads through web](https://github.com/HKUDS/DeepTutor/pull/885) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 886 | PR | [fix(partners): restore focus and reconnect after tab inactivity](https://github.com/HKUDS/DeepTutor/pull/886) | closed | 2026-08-16 | 2026-08-19 | 0 |
| 887 | PR | [fix(sandbox): expose active virtualenv safely in bubblewrap](https://github.com/HKUDS/DeepTutor/pull/887) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 888 | PR | [fix: recover model catalog and provider transport](https://github.com/HKUDS/DeepTutor/pull/888) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 889 | PR | [fix(book): keep chapter map titles visible](https://github.com/HKUDS/DeepTutor/pull/889) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 890 | PR | [fix(chat): preserve provider stream failure boundaries](https://github.com/HKUDS/DeepTutor/pull/890) | closed | 2026-08-16 | 2026-08-16 | 0 |
| 891 | Issue | [[Feature Request]: Structured learner profile for age- and grade-appropriate responses](https://github.com/HKUDS/DeepTutor/issues/891) | closed | 2026-08-17 | 2026-08-31 | 1 |
| 892 | PR | [Codex/bilingual mn4 closure](https://github.com/HKUDS/DeepTutor/pull/892) | closed | 2026-08-17 | 2026-08-17 | 0 |
| 893 | Issue | [[Feature Request]:希望支持在界面中直接编辑笔记本和笔记记录](https://github.com/HKUDS/DeepTutor/issues/893) | closed | 2026-08-17 | 2026-08-23 | 2 |
| 894 | PR | [chore: repository governance hooks, CI hygiene, and branch policies](https://github.com/HKUDS/DeepTutor/pull/894) | closed | 2026-08-17 | 2026-08-17 | 1 |
| 895 | PR | [feat(immersive-reading): source-faithful EPUB reading core and web workspace](https://github.com/HKUDS/DeepTutor/pull/895) | closed | 2026-08-17 | 2026-08-17 | 1 |
| 896 | PR | [feat(reading): web audio TTS pronunciation and mobile reading UX](https://github.com/HKUDS/DeepTutor/pull/896) | closed | 2026-08-17 | 2026-08-17 | 1 |
| 897 | PR | [feat: PWA manifest, MarginNote 4 writeback, and sync manager refinements](https://github.com/HKUDS/DeepTutor/pull/897) | closed | 2026-08-17 | 2026-08-17 | 1 |
| 898 | PR | [feat(reading): bilingual pairing, vocabulary loop, translation board, and source sync](https://github.com/HKUDS/DeepTutor/pull/898) | closed | 2026-08-17 | 2026-08-17 | 1 |
| 899 | PR | [fix(knowledge): preserve source-relative directory structure when syncing external linked folders into raw/](https://github.com/HKUDS/DeepTutor/pull/899) | closed | 2026-08-17 | 2026-08-19 | 0 |
| 900 | Issue | [refactor(knowledge): isolate GitHub source sync into standalone pipeline](https://github.com/HKUDS/DeepTutor/issues/900) | closed | 2026-08-17 | 2026-08-25 | 1 |
| 901 | PR | [Codex/refactor immersive architecture](https://github.com/HKUDS/DeepTutor/pull/901) | closed | 2026-08-17 | 2026-08-17 | 0 |
| 902 | Issue | [feat(knowledge): add durable web-source sync follow-ups](https://github.com/HKUDS/DeepTutor/issues/902) | open | 2026-08-17 | 2026-09-28 | 4 |
| 903 | PR | [feat: split knowledge sync - add GitHub source sync](https://github.com/HKUDS/DeepTutor/pull/903) | closed | 2026-08-17 | 2026-08-24 | 2 |
| 904 | PR | [feat: add bounded web source sync](https://github.com/HKUDS/DeepTutor/pull/904) | closed | 2026-08-17 | 2026-08-25 | 4 |
| 905 | PR | [feat(immersive-reading): add source-faithful reading core](https://github.com/HKUDS/DeepTutor/pull/905) | closed | 2026-08-18 | 2026-08-24 | 2 |
| 906 | Issue | [v1.5.13 release tag fails its own frontend build (25 TS errors in web/)](https://github.com/HKUDS/DeepTutor/issues/906) | closed | 2026-08-18 | 2026-08-28 | 4 |
| 907 | PR | [feat(pageindex): add OSS knowledge bases and reasoning-based retrieval](https://github.com/HKUDS/DeepTutor/pull/907) | closed | 2026-08-18 | 2026-08-19 | 1 |
| 908 | PR | [feat: add neutral deeptutor.plugins entry-point loader](https://github.com/HKUDS/DeepTutor/pull/908) | closed | 2026-08-18 | 2026-08-19 | 4 |
| 909 | Issue | [[Bug]:AI Assistant Cannot Find Existing Mastery Paths — Path ID Resolution Falls Back to Wrong Session ID](https://github.com/HKUDS/DeepTutor/issues/909) | closed | 2026-08-18 | 2026-08-20 | 1 |
| 910 | PR | [fix(chat): inject current date into runtime context](https://github.com/HKUDS/DeepTutor/pull/910) | closed | 2026-08-18 | 2026-08-20 | 0 |
| 911 | PR | [feat: discover loop capabilities via entry points](https://github.com/HKUDS/DeepTutor/pull/911) | closed | 2026-08-18 | 2026-08-19 | 5 |
| 912 | Issue | [[Bug]: 对话过程中聊天页面直接不显示任何消息](https://github.com/HKUDS/DeepTutor/issues/912) | closed | 2026-08-18 | 2026-08-20 | 3 |
| 913 | PR | [Feature/self hosted runner deploy](https://github.com/HKUDS/DeepTutor/pull/913) | closed | 2026-08-18 | 2026-08-18 | 0 |
| 914 | Issue | [[Bug]: obsidian_read fails on any note with a date in its frontmatter](https://github.com/HKUDS/DeepTutor/issues/914) | closed | 2026-08-18 | 2026-08-20 | 3 |
| 915 | Issue | [[Bug]: one undecodable byte anywhere in a vault kills obsidian_search entirely](https://github.com/HKUDS/DeepTutor/issues/915) | closed | 2026-08-18 | 2026-08-20 | 3 |
| 916 | Issue | [feat(reading): improve mobile bilingual immersive reading UX](https://github.com/HKUDS/DeepTutor/issues/916) | open | 2026-08-18 | 2026-08-25 | 0 |
| 917 | PR | [feat(reading): polish bilingual mobile reading experience](https://github.com/HKUDS/DeepTutor/pull/917) | closed | 2026-08-18 | 2026-08-24 | 2 |
| 918 | Issue | [[Feature Request]: 知识库引擎能不能加上 WekNora](https://github.com/HKUDS/DeepTutor/issues/918) | closed | 2026-08-19 | 2026-08-31 | 2 |
| 919 | PR | [fix(usage): record token usage emitted as plain dicts by native adapters](https://github.com/HKUDS/DeepTutor/pull/919) | closed | 2026-08-19 | 2026-08-19 | 0 |
| 920 | PR | [fix(llm): recover from stale CA bundle paths](https://github.com/HKUDS/DeepTutor/pull/920) | closed | 2026-08-19 | 2026-08-20 | 0 |
| 921 | PR | [feat: /whisper dual-seat page and capability-complete forwarding](https://github.com/HKUDS/DeepTutor/pull/921) | closed | 2026-08-19 | 2026-08-19 | 2 |
| 922 | PR | [fix(obsidian): tolerate undecodable bytes and date frontmatter (#914, #915)](https://github.com/HKUDS/DeepTutor/pull/922) | closed | 2026-08-19 | 2026-08-19 | 0 |
| 923 | PR | [fix: re-parent descendants on turn delete and render orphaned message trees](https://github.com/HKUDS/DeepTutor/pull/923) | closed | 2026-08-19 | 2026-08-19 | 0 |
| 924 | PR | [feat: honor end_loop metadata after ask_user resume](https://github.com/HKUDS/DeepTutor/pull/924) | closed | 2026-08-19 | 2026-08-19 | 3 |
| 925 | PR | [feat: psych academy workspace pages (web-only, excludes whisper)](https://github.com/HKUDS/DeepTutor/pull/925) | open | 2026-08-19 | 2026-09-03 | 4 |
| 926 | PR | [feat(book): add learning capture inbox](https://github.com/HKUDS/DeepTutor/pull/926) | closed | 2026-08-19 | 2026-08-20 | 0 |
| 927 | PR | [fix(book): gate KB fingerprint refresh on stale recompilation](https://github.com/HKUDS/DeepTutor/pull/927) | closed | 2026-08-19 | 2026-08-20 | 0 |
| 928 | PR | [fix(api): return JSON for unhandled exceptions](https://github.com/HKUDS/DeepTutor/pull/928) | closed | 2026-08-19 | 2026-08-20 | 0 |
| 930 | PR | [fix: log provider error body on tool-schema rejection fallback](https://github.com/HKUDS/DeepTutor/pull/930) | closed | 2026-08-20 | 2026-08-21 | 0 |
| 931 | PR | [feat(knowledge): add MarginNote 4 as a connected knowledge base](https://github.com/HKUDS/DeepTutor/pull/931) | closed | 2026-08-20 | 2026-10-28 | 2 |
| 932 | Issue | [feat(reading): add chapter-scoped character and entity relationship graph](https://github.com/HKUDS/DeepTutor/issues/932) | open | 2026-08-20 | 2026-08-25 | 1 |
| 933 | PR | [fix(rag): parallelize image descriptions in the LlamaIndex RAG pipeline with timeout and progress](https://github.com/HKUDS/DeepTutor/pull/933) | closed | 2026-08-20 | 2026-08-24 | 0 |
| 934 | Issue | [[Bug] ModelScope Qwen3-Embedding-8B embedding fails: HTTP 400 encoding_format must be 'float' or 'base64', got ''](https://github.com/HKUDS/DeepTutor/issues/934) | closed | 2026-08-20 | 2026-08-21 | 1 |
| 935 | Issue | [feat(kids): harden reading sessions, content authorization, and daily limits](https://github.com/HKUDS/DeepTutor/issues/935) | closed | 2026-08-20 | 2026-08-25 | 5 |
| 936 | PR | [fix(chat): prune deleted knowledge base references from sessions](https://github.com/HKUDS/DeepTutor/pull/936) | closed | 2026-08-20 | 2026-08-24 | 0 |
| 937 | Issue | [[Bug]: Tool call IDs grow unboundedly in streaming responses (acc["id"] += str(tcid)) causing 400 "string too long" and empty final responses](https://github.com/HKUDS/DeepTutor/issues/937) | closed | 2026-08-20 | 2026-08-21 | 1 |
| 938 | Issue | [[Bug]:使用kimi-k3报invalid temperatur](https://github.com/HKUDS/DeepTutor/issues/938) | closed | 2026-08-20 | 2026-08-25 | 4 |
| 939 | Issue | [feat(kids): isolate family library with parent review and device pairing](https://github.com/HKUDS/DeepTutor/issues/939) | closed | 2026-08-20 | 2026-08-25 | 2 |
| 940 | PR | [fix: converge LightRAG transport failures and cancellation](https://github.com/HKUDS/DeepTutor/pull/940) | closed | 2026-08-20 | 2026-08-26 | 0 |
| 941 | Issue | [[Bug]: 一直使用纯文本提问，多次提醒、要求写入记忆，仍然无效](https://github.com/HKUDS/DeepTutor/issues/941) | closed | 2026-08-20 | 2026-08-30 | 4 |
| 942 | Issue | [[Bug]:精通之路的地图会持续互相污染](https://github.com/HKUDS/DeepTutor/issues/942) | closed | 2026-08-21 | 2026-08-25 | 3 |
| 943 | Issue | [[Feature Request]: Migrate the local LightRAG provider to LightRAG's native multimodal pipeline](https://github.com/HKUDS/DeepTutor/issues/943) | closed | 2026-08-21 | 2026-08-30 | 1 |
| 944 | PR | [fix(book): repair the reader flex height chain so long chapters scroll](https://github.com/HKUDS/DeepTutor/pull/944) | closed | 2026-08-21 | 2026-08-23 | 1 |
| 945 | Issue | [[Bug]: Transcription response had no `text` field](https://github.com/HKUDS/DeepTutor/issues/945) | closed | 2026-08-21 | 2026-08-24 | 2 |
| 946 | Issue | [[Bug]: LlamaIndex reindex hangs indefinitely during embedding batch (create_index in run_in_executor)](https://github.com/HKUDS/DeepTutor/issues/946) | closed | 2026-08-21 | 2026-08-24 | 2 |
| 947 | PR | [Feat/encore user sidebar](https://github.com/HKUDS/DeepTutor/pull/947) | closed | 2026-08-21 | 2026-08-21 | 0 |
| 948 | PR | [fix(voice): strip MediaRecorder codec params from STT uploads](https://github.com/HKUDS/DeepTutor/pull/948) | closed | 2026-08-21 | 2026-08-24 | 0 |
| 949 | PR | [fix(rag): filter MinerU page-layout blocks before indexing](https://github.com/HKUDS/DeepTutor/pull/949) | closed | 2026-08-21 | 2026-08-26 | 0 |
| 950 | PR | [feat: add QR channel onboarding for Feishu/Lark and WeCom](https://github.com/HKUDS/DeepTutor/pull/950) | closed | 2026-08-22 | 2026-08-29 | 1 |
| 951 | Issue | [feat(partners): add QR onboarding for Feishu, Lark, and WeCom channels](https://github.com/HKUDS/DeepTutor/issues/951) | closed | 2026-08-22 | 2026-08-25 | 3 |
| 952 | PR | [feat: add QR onboarding for Feishu and WeCom partners](https://github.com/HKUDS/DeepTutor/pull/952) | closed | 2026-08-22 | 2026-08-29 | 0 |
| 953 | PR | [fix(llamaindex): fail bounded when indexing stalls](https://github.com/HKUDS/DeepTutor/pull/953) | closed | 2026-08-22 | 2026-08-24 | 0 |
| 954 | PR | [fix(cli): declare missing standalone runtime dependencies](https://github.com/HKUDS/DeepTutor/pull/954) | closed | 2026-08-22 | 2026-08-24 | 0 |
| 955 | Issue | [[Bug]:quiz选择题多次出现2-3个相同选项](https://github.com/HKUDS/DeepTutor/issues/955) | closed | 2026-08-22 | 2026-08-25 | 2 |
| 956 | PR | [fix(mastery): reject duplicate quiz option bodies](https://github.com/HKUDS/DeepTutor/pull/956) | closed | 2026-08-22 | 2026-08-25 | 0 |
| 957 | Issue | [feat(kids): add source-grounded concept learning for bilingual readers](https://github.com/HKUDS/DeepTutor/issues/957) | closed | 2026-08-22 | 2026-08-25 | 1 |
| 958 | PR | [feat: add per-conversation reasoning-effort override (#641)](https://github.com/HKUDS/DeepTutor/pull/958) | closed | 2026-08-22 | 2026-08-24 | 1 |
| 959 | PR | [feat(cli): add setup doctor command](https://github.com/HKUDS/DeepTutor/pull/959) | closed | 2026-08-22 | 2026-08-25 | 0 |
| 960 | PR | [fix(web): pin chat to late-mounted quiz cards](https://github.com/HKUDS/DeepTutor/pull/960) | closed | 2026-08-22 | 2026-08-24 | 0 |
| 961 | Issue | [feat(plugins): add pluggable learning resource providers with lifecycle controls](https://github.com/HKUDS/DeepTutor/issues/961) | open | 2026-08-23 | 2026-08-25 | 0 |
| 962 | PR | [fix(embedding): survive provider rate limits — key rotation, retry budget, global throttle](https://github.com/HKUDS/DeepTutor/pull/962) | closed | 2026-08-23 | 2026-09-24 | 0 |
| 963 | Issue | [[Bug]:› http://127.0.0.1:3782/whisper  对话：Unknown capability: whisper_visitor. Available: ['chat', 'deep_solve', 'deep_question', 'deep_research', 'math_animator', 'visualize',   'mastery_path', 'immersive_reading']](https://github.com/HKUDS/DeepTutor/issues/963) | closed | 2026-08-23 | 2026-08-25 | 1 |
| 964 | PR | [fix(sandbox): support Windows code execution](https://github.com/HKUDS/DeepTutor/pull/964) | closed | 2026-08-23 | 2026-08-24 | 0 |
| 965 | Issue | [[Bug]:PDF generation script runs without error but produces no output file](https://github.com/HKUDS/DeepTutor/issues/965) | closed | 2026-08-23 | 2026-08-31 | 2 |
| 966 | Issue | [[Bug]: Book reader: long chapters unreadable — page-turner skips sections, no vertical scroll](https://github.com/HKUDS/DeepTutor/issues/966) | closed | 2026-08-23 | 2026-08-25 | 1 |
| 967 | Issue | [feat(reading): support faithful EPUB rendering in the reading pane](https://github.com/HKUDS/DeepTutor/issues/967) | closed | 2026-08-23 | 2026-08-25 | 1 |
| 968 | PR | [feat(reading): add source-faithful EPUB contract](https://github.com/HKUDS/DeepTutor/pull/968) | closed | 2026-08-23 | 2026-08-25 | 1 |
| 969 | PR | [feat(reading): render EPUBs faithfully in ReaderPane](https://github.com/HKUDS/DeepTutor/pull/969) | closed | 2026-08-23 | 2026-08-25 | 1 |
| 970 | PR | [feat(reading): add safe extension protocol and empty toolbar slot](https://github.com/HKUDS/DeepTutor/pull/970) | closed | 2026-08-23 | 2026-08-25 | 1 |
| 971 | Issue | [feat(reading): finish selector re-anchoring for structured revisions](https://github.com/HKUDS/DeepTutor/issues/971) | open | 2026-08-23 | 2026-08-25 | 0 |
| 972 | PR | [feat(reading): persist W3C text selectors](https://github.com/HKUDS/DeepTutor/pull/972) | closed | 2026-08-23 | 2026-08-25 | 2 |
| 973 | Issue | [[Bug]: 精通之路题干把 Unicode 转义原样显示出来](https://github.com/HKUDS/DeepTutor/issues/973) | closed | 2026-08-24 | 2026-08-30 | 5 |
| 974 | PR | [feat(reading): render reflowing annotations with Recogito](https://github.com/HKUDS/DeepTutor/pull/974) | closed | 2026-08-24 | 2026-08-25 | 0 |
| 975 | PR | [fix(chat): decode dense non-ASCII unicode escapes for display](https://github.com/HKUDS/DeepTutor/pull/975) | closed | 2026-08-24 | 2026-08-25 | 1 |
| 976 | PR | [fix(whisper): show plugin-required empty state](https://github.com/HKUDS/DeepTutor/pull/976) | closed | 2026-08-24 | 2026-08-25 | 2 |
| 977 | PR | [fix(llm): drop temperature for bare Kimi model ids (k3) on the coding endpoint](https://github.com/HKUDS/DeepTutor/pull/977) | closed | 2026-08-24 | 2026-08-25 | 0 |
| 978 | PR | [feat(llm): route OpenAI-compatible agent calls through the Responses API](https://github.com/HKUDS/DeepTutor/pull/978) | closed | 2026-08-24 | 2026-08-29 | 1 |
| 979 | PR | [feat(reading): add explicit bilingual EPUB pairing](https://github.com/HKUDS/DeepTutor/pull/979) | closed | 2026-08-24 | 2026-08-25 | 2 |
| 980 | Issue | [feat(reading): render web snapshots as rich Markdown and strip provenance comments](https://github.com/HKUDS/DeepTutor/issues/980) | closed | 2026-08-24 | 2026-08-31 | 3 |
| 981 | PR | [ci: ignore non-version release tags](https://github.com/HKUDS/DeepTutor/pull/981) | closed | 2026-08-24 | 2026-08-25 | 1 |
| 983 | PR | [test(partners): assert the admin gate without a FastAPI internal](https://github.com/HKUDS/DeepTutor/pull/983) | closed | 2026-08-24 | 2026-08-24 | 0 |
| 984 | Issue | [feat(reading): add adjustable typography and line width controls to text view](https://github.com/HKUDS/DeepTutor/issues/984) | closed | 2026-08-24 | 2026-08-25 | 1 |
| 985 | PR | [feat(reading): add adjustable text display preferences](https://github.com/HKUDS/DeepTutor/pull/985) | closed | 2026-08-24 | 2026-08-25 | 0 |
| 986 | PR | [fix: improve Windows cross-platform compatibility across runner, tool…](https://github.com/HKUDS/DeepTutor/pull/986) | closed | 2026-08-24 | 2026-08-26 | 0 |
| 987 | Issue | [feat(reading): add persistent document outline and in-page heading navigation](https://github.com/HKUDS/DeepTutor/issues/987) | closed | 2026-08-24 | 2026-08-25 | 1 |
| 988 | PR | [fix(codex): fail closed on TLS verification errors](https://github.com/HKUDS/DeepTutor/pull/988) | closed | 2026-08-24 | 2026-08-26 | 0 |
| 989 | PR | [fix(rag): preserve asymmetric embedding context](https://github.com/HKUDS/DeepTutor/pull/989) | closed | 2026-08-24 | 2026-08-26 | 0 |
| 990 | PR | [feat(subagent): add Antigravity CLI (agy) backend](https://github.com/HKUDS/DeepTutor/pull/990) | closed | 2026-08-24 | 2026-08-29 | 2 |
| 991 | PR | [feat(reading): add persistent document outline and in-page heading navigation](https://github.com/HKUDS/DeepTutor/pull/991) | closed | 2026-08-24 | 2026-08-25 | 1 |
| 992 | Issue | [feat(learner): model learners as ordinary users with presets and guardian authorization](https://github.com/HKUDS/DeepTutor/issues/992) | open | 2026-08-24 | 2026-08-25 | 0 |
| 993 | Issue | [feat(learner): enforce learner safety policies on ordinary user accounts](https://github.com/HKUDS/DeepTutor/issues/993) | closed | 2026-08-24 | 2026-08-31 | 1 |
| 994 | Issue | [feat(learner): add guardian authorization for learner materials and reports](https://github.com/HKUDS/DeepTutor/issues/994) | closed | 2026-08-24 | 2026-08-31 | 1 |
| 995 | Issue | [feat(reading): add guided learning as safe reading extensions](https://github.com/HKUDS/DeepTutor/issues/995) | open | 2026-08-24 | 2026-09-11 | 3 |
| 996 | PR | [feat: add selection tutor and course workspaces](https://github.com/HKUDS/DeepTutor/pull/996) | closed | 2026-08-24 | 2026-08-25 | 0 |
| 997 | Issue | [feat(video-learning): add YouTube immersive watching](https://github.com/HKUDS/DeepTutor/issues/997) | open | 2026-08-24 | 2026-09-05 | 3 |
| 998 | PR | [fix(book): read long chapters sequentially before turning pages](https://github.com/HKUDS/DeepTutor/pull/998) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 999 | PR | [fix(tests): ensure non-admin role for alice fixture in channel links …](https://github.com/HKUDS/DeepTutor/pull/999) | closed | 2026-08-25 | 2026-08-26 | 1 |
| 1000 | PR | [Chore/line endings and ci](https://github.com/HKUDS/DeepTutor/pull/1000) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1001 | PR | [Chore/line endings and ci](https://github.com/HKUDS/DeepTutor/pull/1001) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1002 | PR | [fix(assessment): redirect plain-text mastery quizzes to cards (#941)](https://github.com/HKUDS/DeepTutor/pull/1002) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1003 | PR | [feat(llm): map web_search to native Responses tools for server-side search](https://github.com/HKUDS/DeepTutor/pull/1003) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1004 | Issue | [[Bug]:mastery_path: learner's clarifying question typed in the composer is persisted as answered, stalling the gate forever](https://github.com/HKUDS/DeepTutor/issues/1004) | closed | 2026-08-25 | 2026-08-30 | 4 |
| 1005 | PR | [Fix llama.cpp context detection for loaded models](https://github.com/HKUDS/DeepTutor/pull/1005) | closed | 2026-08-25 | 2026-08-30 | 0 |
| 1006 | PR | [feat(search): add Serply provider with web, news and scholar modes](https://github.com/HKUDS/DeepTutor/pull/1006) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1007 | PR | [fix(mastery): don't freeze choice gates on clarifying composer text](https://github.com/HKUDS/DeepTutor/pull/1007) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1008 | PR | [fix(llm): stop matching bare 'tool' in schema-fallback detector](https://github.com/HKUDS/DeepTutor/pull/1008) | closed | 2026-08-25 | 2026-08-25 | 0 |
| 1009 | PR | [feat(reading): expose EPUB headings in the persistent outline](https://github.com/HKUDS/DeepTutor/pull/1009) | closed | 2026-08-25 | 2026-08-31 | 0 |
| 1010 | Issue | [[Feature Request] Expose reasoning_effort selector in LLM settings UI for generic OpenAI-compatible providers](https://github.com/HKUDS/DeepTutor/issues/1010) | closed | 2026-08-25 | 2026-08-30 | 1 |
| 1011 | PR | [feat(reading): render web snapshots as safe rich Markdown](https://github.com/HKUDS/DeepTutor/pull/1011) | closed | 2026-08-26 | 2026-10-04 | 1 |
| 1012 | Issue | [[Bug]:伙伴（Partner）网页对话生成的图片无法加载（404）](https://github.com/HKUDS/DeepTutor/issues/1012) | closed | 2026-08-26 | 2026-08-29 | 2 |
| 1013 | Issue | [[Bug]:](https://github.com/HKUDS/DeepTutor/issues/1013) | closed | 2026-08-26 | 2026-08-26 | 0 |
| 1014 | Issue | [[Bug]:系统出了一个测验选择题，我在第五个选项其他中输入了我不明白题干中某个词语的意思，后续它会一直重复提这个问题，不管我怎么回答它依然只记住了我不知道题干的意思，一直不能推进学习进度](https://github.com/HKUDS/DeepTutor/issues/1014) | closed | 2026-08-26 | 2026-08-26 | 3 |
| 1015 | PR | [feat: add Volcengine Ark embedding, Doubao Search Custom and PaddleOCR parsing providers](https://github.com/HKUDS/DeepTutor/pull/1015) | open | 2026-08-26 | 2026-09-10 | 0 |
| 1016 | Issue | [[Feature Request]:  tts/stt/T2I/T2V need dashscope provider](https://github.com/HKUDS/DeepTutor/issues/1016) | closed | 2026-08-26 | 2026-08-31 | 1 |
| 1017 | PR | [fix(partners): serve partner artifacts from output downloads](https://github.com/HKUDS/DeepTutor/pull/1017) | closed | 2026-08-26 | 2026-08-29 | 0 |
| 1018 | Issue | [[Bug]:评分工具死锁（Grading Tool Deadlock）](https://github.com/HKUDS/DeepTutor/issues/1018) | closed | 2026-08-26 | 2026-09-08 | 3 |
| 1019 | Issue | [Mastery Paths save empty for most LLMs — _parse_modules only reads name, models emit title](https://github.com/HKUDS/DeepTutor/issues/1019) | closed | 2026-08-26 | 2026-08-29 | 1 |
| 1020 | PR | [fix(chat): decode unicode escapes in ask_user card text](https://github.com/HKUDS/DeepTutor/pull/1020) | closed | 2026-08-26 | 2026-08-29 | 0 |
| 1021 | PR | [fix: make deep research resilient to interrupted streams](https://github.com/HKUDS/DeepTutor/pull/1021) | closed | 2026-08-27 | 2026-08-31 | 0 |
| 1022 | PR | [fix(mastery): normalize objective module variants](https://github.com/HKUDS/DeepTutor/pull/1022) | closed | 2026-08-27 | 2026-08-29 | 1 |
| 1023 | PR | [fix(mastery): add explicit question recovery exit (#1018)](https://github.com/HKUDS/DeepTutor/pull/1023) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1024 | PR | [feat(settings): expose custom reasoning effort (#1010)](https://github.com/HKUDS/DeepTutor/pull/1024) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1025 | PR | [fix(tools): route file generation through code execution (#965)](https://github.com/HKUDS/DeepTutor/pull/1025) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1026 | PR | [fix(partners): coalesce streaming draft updates (#788)](https://github.com/HKUDS/DeepTutor/pull/1026) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1027 | PR | [fix(web): resolve optimistic ids before deleteTurn](https://github.com/HKUDS/DeepTutor/pull/1027) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1028 | Issue | [[Feature Request]: Add support for Agent Client Protocol (ACP)](https://github.com/HKUDS/DeepTutor/issues/1028) | open | 2026-08-27 | 2026-09-06 | 2 |
| 1029 | PR | [feat(reading): enforce Focus-Check checkpoint progression](https://github.com/HKUDS/DeepTutor/pull/1029) | open | 2026-08-27 | 2026-09-05 | 0 |
| 1030 | PR | [feat(reading): add semantic passage search](https://github.com/HKUDS/DeepTutor/pull/1030) | open | 2026-08-27 | 2026-09-05 | 0 |
| 1031 | PR | [feat(reading): add citation capture](https://github.com/HKUDS/DeepTutor/pull/1031) | closed | 2026-08-27 | 2026-09-05 | 1 |
| 1032 | PR | [feat(reading): reference reading sections in chat](https://github.com/HKUDS/DeepTutor/pull/1032) | closed | 2026-08-27 | 2026-08-31 | 1 |
| 1033 | PR | [fix: align Windows exec runtime and search readiness](https://github.com/HKUDS/DeepTutor/pull/1033) | closed | 2026-08-27 | 2026-08-31 | 0 |
| 1034 | Issue | [fix(reading): bind citations to turn materials and verified locators](https://github.com/HKUDS/DeepTutor/issues/1034) | closed | 2026-08-27 | 2026-08-31 | 1 |
| 1035 | Issue | [feat(reading): add session-scoped cross-material navigation history](https://github.com/HKUDS/DeepTutor/issues/1035) | closed | 2026-08-27 | 2026-08-31 | 1 |
| 1036 | PR | [fix(reading): bind citations to turn materials and verified locators (#1034)](https://github.com/HKUDS/DeepTutor/pull/1036) | closed | 2026-08-27 | 2026-08-31 | 1 |
| 1037 | PR | [feat(video-learning): add native YouTube immersive watching (#997)](https://github.com/HKUDS/DeepTutor/pull/1037) | closed | 2026-08-27 | 2026-08-30 | 0 |
| 1038 | PR | [feat(reading): add session-scoped cross-material navigation history (#1035)](https://github.com/HKUDS/DeepTutor/pull/1038) | closed | 2026-08-27 | 2026-09-01 | 1 |
| 1039 | Issue | [docs(web): update overview screenshots for v1.6.0](https://github.com/HKUDS/DeepTutor/issues/1039) | closed | 2026-08-27 | 2026-08-31 | 1 |
| 1040 | Issue | [Anthropic SDK 1.x incompatibility: `temperature` kwarg rejected by `messages.create` / `messages.stream`](https://github.com/HKUDS/DeepTutor/issues/1040) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1041 | PR | [fix(llm): route Anthropic `temperature` via `extra_body` for SDK 1.x compat](https://github.com/HKUDS/DeepTutor/pull/1041) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1042 | PR | [fix(partners): coalesce streaming draft updates (#788)](https://github.com/HKUDS/DeepTutor/pull/1042) | closed | 2026-08-27 | 2026-08-29 | 1 |
| 1043 | PR | [fix(skills): scope ClawHub installs by publisher (#639)](https://github.com/HKUDS/DeepTutor/pull/1043) | closed | 2026-08-27 | 2026-08-29 | 0 |
| 1044 | PR | [feat(rag): add opt-in HNSW vector indexes (#304)](https://github.com/HKUDS/DeepTutor/pull/1044) | closed | 2026-08-27 | 2026-08-31 | 0 |
| 1045 | PR | [feat(rag): add optional cross-encoder reranking (#304)](https://github.com/HKUDS/DeepTutor/pull/1045) | closed | 2026-08-27 | 2026-09-02 | 0 |
| 1046 | PR | [feat(media): add DashScope providers (#1016)](https://github.com/HKUDS/DeepTutor/pull/1046) | closed | 2026-08-27 | 2026-08-31 | 0 |
| 1047 | PR | [docs(web): update overview screenshot (#1039)](https://github.com/HKUDS/DeepTutor/pull/1047) | closed | 2026-08-27 | 2026-09-01 | 1 |
| 1048 | PR | [fix(llm): replay DeepSeek reasoning across tool calls](https://github.com/HKUDS/DeepTutor/pull/1048) | closed | 2026-08-27 | 2026-09-02 | 2 |
| 1049 | PR | [fix(web): skip persisting optimistic branch selections](https://github.com/HKUDS/DeepTutor/pull/1049) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1050 | PR | [fix(tools): decode unicode escapes in ask_user payloads](https://github.com/HKUDS/DeepTutor/pull/1050) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1051 | PR | [feat(chat): add per-conversation reasoning effort (#641)](https://github.com/HKUDS/DeepTutor/pull/1051) | closed | 2026-08-28 | 2026-10-04 | 1 |
| 1052 | PR | [feat(book): infer requested language (#471)](https://github.com/HKUDS/DeepTutor/pull/1052) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1053 | PR | [feat(settings): add version update checks (#725)](https://github.com/HKUDS/DeepTutor/pull/1053) | closed | 2026-08-28 | 2026-10-04 | 1 |
| 1054 | PR | [docs(safety): add reasoning and retrieval checklist (#199)](https://github.com/HKUDS/DeepTutor/pull/1054) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1055 | PR | [test(web-source): cover relative images in crawled docs (#980)](https://github.com/HKUDS/DeepTutor/pull/1055) | closed | 2026-08-28 | 2026-10-04 | 1 |
| 1056 | Issue | [Deep Question allows empty topic and surfaces low-level Operation not permitted error](https://github.com/HKUDS/DeepTutor/issues/1056) | closed | 2026-08-28 | 2026-08-29 | 2 |
| 1057 | PR | [fix(question): validate topic before generation](https://github.com/HKUDS/DeepTutor/pull/1057) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1058 | Issue | [[Bug]:DeepSeek API `reasoning_content` 透传失败导致 400 错误](https://github.com/HKUDS/DeepTutor/issues/1058) | closed | 2026-08-28 | 2026-08-31 | 2 |
| 1059 | PR | [fix(llm): disable DeepSeek flash thinking on openai bindings](https://github.com/HKUDS/DeepTutor/pull/1059) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1060 | PR | [feat(search): add reference safety filtering (#375)](https://github.com/HKUDS/DeepTutor/pull/1060) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1061 | PR | [feat(reading): add chapter relationship graph (#932)](https://github.com/HKUDS/DeepTutor/pull/1061) | closed | 2026-08-28 | 2026-10-04 | 1 |
| 1062 | PR | [feat(chat): add inline markdown notes (#661)](https://github.com/HKUDS/DeepTutor/pull/1062) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1063 | Issue | [[Bug]: Jina embedding adapter never receives retrieval roles — `SUPPORTS_INPUT_TYPE` not opted in, so the `task` mapping is dead code and queries embed without `retrieval.query` semantics](https://github.com/HKUDS/DeepTutor/issues/1063) | closed | 2026-08-28 | 2026-08-29 | 1 |
| 1064 | PR | [docs(installation): document uninstall and data cleanup (#486)](https://github.com/HKUDS/DeepTutor/pull/1064) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1065 | PR | [docs(knowledge): add note migration guide (#841)](https://github.com/HKUDS/DeepTutor/pull/1065) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1066 | PR | [fix(embedding): enable Jina retrieval roles (#1063)](https://github.com/HKUDS/DeepTutor/pull/1066) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1067 | PR | [fix(llm): persist DeepSeek reasoning across turns (#1058)](https://github.com/HKUDS/DeepTutor/pull/1067) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1068 | PR | [feat(chat): route explicit quiz requests (#807)](https://github.com/HKUDS/DeepTutor/pull/1068) | closed | 2026-08-28 | 2026-08-31 | 2 |
| 1069 | PR | [Replace RAG-Anything with native LightRAG 1.5 pipeline](https://github.com/HKUDS/DeepTutor/pull/1069) | closed | 2026-08-28 | 2026-09-08 | 0 |
| 1070 | PR | [feat(lightrag): add dedicated model selection (#640)](https://github.com/HKUDS/DeepTutor/pull/1070) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1071 | PR | [fix(chat): select newly sent branch (#739)](https://github.com/HKUDS/DeepTutor/pull/1071) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1072 | PR | [fix(llm): support Anthropic SDK temperature fields (#1040)](https://github.com/HKUDS/DeepTutor/pull/1072) | closed | 2026-08-28 | 2026-08-29 | 1 |
| 1073 | PR | [fix(knowledge): explain scanned PDF parse failures (#431)](https://github.com/HKUDS/DeepTutor/pull/1073) | closed | 2026-08-28 | 2026-08-29 | 0 |
| 1074 | PR | [feat(knowledge): add WeKnora retrieval connections (#918)](https://github.com/HKUDS/DeepTutor/pull/1074) | closed | 2026-08-28 | 2026-08-31 | 0 |
| 1075 | PR | [fix(llm): enable DeepSeek Pro native web search (#846)](https://github.com/HKUDS/DeepTutor/pull/1075) | closed | 2026-08-29 | 2026-08-29 | 0 |
| 1076 | Issue | [[Bug]: GET /api/v1/system/memory 500 (PermissionError: /proc/1/stat) on HarmonyOS/OpenHarmony](https://github.com/HKUDS/DeepTutor/issues/1076) | closed | 2026-08-29 | 2026-08-29 | 2 |
| 1077 | PR | [fix(runtime): fall back when psutil cannot read /proc](https://github.com/HKUDS/DeepTutor/pull/1077) | closed | 2026-08-29 | 2026-08-29 | 0 |
| 1078 | PR | [fix(runtime): skip psutil process-tree walk on HarmonyOS (/proc/1/stat)](https://github.com/HKUDS/DeepTutor/pull/1078) | closed | 2026-08-29 | 2026-08-29 | 1 |
| 1079 | PR | [fix(mastery): read the module tree models actually emit (#1019)](https://github.com/HKUDS/DeepTutor/pull/1079) | closed | 2026-08-29 | 2026-08-29 | 0 |
| 1080 | PR | [fix(ci): restore the ruff gate on dev](https://github.com/HKUDS/DeepTutor/pull/1080) | closed | 2026-08-29 | 2026-08-29 | 0 |
| 1081 | PR | [feat(assessment): unify persisted review records (#824)](https://github.com/HKUDS/DeepTutor/pull/1081) | closed | 2026-08-29 | 2026-08-31 | 0 |
| 1082 | PR | [chore(lint): restore dev formatting](https://github.com/HKUDS/DeepTutor/pull/1082) | closed | 2026-08-29 | 2026-08-29 | 1 |
| 1083 | PR | [fix(ima): add ima.qq.com to the media-URL allowlist](https://github.com/HKUDS/DeepTutor/pull/1083) | closed | 2026-08-29 | 2026-08-30 | 0 |
| 1084 | PR | [feat(llm): support explicit OpenAI wire API selection](https://github.com/HKUDS/DeepTutor/pull/1084) | closed | 2026-08-29 | 2026-08-31 | 0 |
| 1085 | PR | [fix(code-execution): preserve PDF scope and retry discipline (#965)](https://github.com/HKUDS/DeepTutor/pull/1085) | closed | 2026-08-29 | 2026-09-11 | 1 |
| 1086 | PR | [fix(web): localize organized session placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1086) | closed | 2026-08-29 | 2026-08-31 | 0 |
| 1087 | Issue | [[Docs]: Incorrect document type for MinerU](https://github.com/HKUDS/DeepTutor/issues/1087) | closed | 2026-08-29 | 2026-08-31 | 2 |
| 1089 | Issue | [[Bug]: 对话中 LaTeX 复制或选择不是渲染前格式导致小老师检查失败](https://github.com/HKUDS/DeepTutor/issues/1089) | closed | 2026-08-29 | 2026-08-31 | 2 |
| 1090 | PR | [fix(web): remap KaTeX selections to LaTeX for Little Tutor](https://github.com/HKUDS/DeepTutor/pull/1090) | closed | 2026-08-29 | 2026-09-01 | 2 |
| 1091 | Issue | [fix(video-learning): preserve multiline Invidious caption cues](https://github.com/HKUDS/DeepTutor/issues/1091) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1093 | PR | [fix: avoid blocking the embedding event loop](https://github.com/HKUDS/DeepTutor/pull/1093) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1094 | PR | [fix: persist reindex terminal state](https://github.com/HKUDS/DeepTutor/pull/1094) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1095 | PR | [fix(web): localize HistorySessionPicker placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1095) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1096 | Issue | [fix(launcher): detect IPv6 loopback port listeners](https://github.com/HKUDS/DeepTutor/issues/1096) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1097 | PR | [fix(launcher): detect IPv6 loopback port listeners (#1096)](https://github.com/HKUDS/DeepTutor/pull/1097) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1098 | PR | [feat(parsing): route Office and image files through MinerU (#1087)](https://github.com/HKUDS/DeepTutor/pull/1098) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1099 | Issue | [fix(courses): preserve handoff course scope](https://github.com/HKUDS/DeepTutor/issues/1099) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1100 | PR | [fix(courses): preserve handoff course scope (#1099)](https://github.com/HKUDS/DeepTutor/pull/1100) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1101 | Issue | [Arg guard reports deliberate empty-string args as "missing", driving verbatim retries (obsidian_create_note + thinking models)](https://github.com/HKUDS/DeepTutor/issues/1101) | closed | 2026-08-30 | 2026-08-31 | 2 |
| 1102 | PR | [fix(agentic): distinguish empty vs missing tool args (#1101)](https://github.com/HKUDS/DeepTutor/pull/1102) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1103 | Issue | [feat(reading): add safe read-aloud extension](https://github.com/HKUDS/DeepTutor/issues/1103) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1104 | PR | [feat(reading): add safe read-aloud extension (#1103)](https://github.com/HKUDS/DeepTutor/pull/1104) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1105 | Issue | [feat(reading): add source-grounded study guidance extension](https://github.com/HKUDS/DeepTutor/issues/1105) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1106 | PR | [feat(reading): add source-grounded study guidance extension (#1105)](https://github.com/HKUDS/DeepTutor/pull/1106) | closed | 2026-08-30 | 2026-09-01 | 0 |
| 1107 | Issue | [feat(reading): add source-grounded vocabulary extension](https://github.com/HKUDS/DeepTutor/issues/1107) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1108 | PR | [feat(reading): add source-grounded vocabulary extension (#1107)](https://github.com/HKUDS/DeepTutor/pull/1108) | closed | 2026-08-30 | 2026-09-01 | 0 |
| 1109 | Issue | [feat(learner): add account-scoped reading learning records](https://github.com/HKUDS/DeepTutor/issues/1109) | open | 2026-08-30 | 2026-08-30 | 0 |
| 1110 | PR | [feat(learner): add account-scoped reading learning records (#1109)](https://github.com/HKUDS/DeepTutor/pull/1110) | closed | 2026-08-30 | 2026-09-10 | 10 |
| 1111 | Issue | [feat(learner): add server-enforced account presets](https://github.com/HKUDS/DeepTutor/issues/1111) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1112 | PR | [feat(learner): add server-enforced account presets (#1111)](https://github.com/HKUDS/DeepTutor/pull/1112) | closed | 2026-08-30 | 2026-09-04 | 1 |
| 1113 | PR | [feat(learner): add guardian authorization (#994)](https://github.com/HKUDS/DeepTutor/pull/1113) | closed | 2026-08-30 | 2026-09-01 | 0 |
| 1114 | Issue | [feat(reading): add source-grounded quiz extension](https://github.com/HKUDS/DeepTutor/issues/1114) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1115 | PR | [feat(reading): add source-grounded quiz extension (#1114)](https://github.com/HKUDS/DeepTutor/pull/1115) | closed | 2026-08-30 | 2026-09-01 | 0 |
| 1116 | Issue | [feat(learner): add revocable device login credentials](https://github.com/HKUDS/DeepTutor/issues/1116) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1117 | Issue | [feat(reading): add source-grounded translation extension](https://github.com/HKUDS/DeepTutor/issues/1117) | closed | 2026-08-30 | 2026-08-31 | 1 |
| 1118 | PR | [fix(ima): add ima.qq.com to the media-URL allowlist](https://github.com/HKUDS/DeepTutor/pull/1118) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1119 | PR | [feat(reading): add source-grounded translation extension](https://github.com/HKUDS/DeepTutor/pull/1119) | closed | 2026-08-30 | 2026-09-01 | 0 |
| 1120 | PR | [Add Word (.docx) import and export to Co-Writer](https://github.com/HKUDS/DeepTutor/pull/1120) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1121 | PR | [fix(partners): localize partner session placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1121) | closed | 2026-08-30 | 2026-08-31 | 0 |
| 1122 | PR | [feat(learner): add revocable device login credentials (#1116)](https://github.com/HKUDS/DeepTutor/pull/1122) | closed | 2026-08-30 | 2026-09-01 | 2 |
| 1123 | PR | [feat(reading): add session-scoped cross-material navigation history (#1035)](https://github.com/HKUDS/DeepTutor/pull/1123) | closed | 2026-08-31 | 2026-09-01 | 0 |
| 1124 | PR | [feat(learner): add account-scoped learner profiles (#891)](https://github.com/HKUDS/DeepTutor/pull/1124) | closed | 2026-08-31 | 2026-10-04 | 2 |
| 1125 | Issue | [feat(learner): let learners manage their own learning profile](https://github.com/HKUDS/DeepTutor/issues/1125) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1126 | PR | [feat(learner): add self-service learner profiles](https://github.com/HKUDS/DeepTutor/pull/1126) | closed | 2026-08-31 | 2026-09-01 | 0 |
| 1127 | Issue | [feat(learner): add explicit guardian authorization records](https://github.com/HKUDS/DeepTutor/issues/1127) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1128 | Issue | [feat(learner): add guardian management UI](https://github.com/HKUDS/DeepTutor/issues/1128) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1129 | PR | [feat(learner): add guardian management UI](https://github.com/HKUDS/DeepTutor/pull/1129) | closed | 2026-08-31 | 2026-09-01 | 2 |
| 1130 | Issue | [feat(learner): add a personal learning progress view](https://github.com/HKUDS/DeepTutor/issues/1130) | open | 2026-08-31 | 2026-08-31 | 0 |
| 1131 | Issue | [fix(video-learning): support lazy routers in mount test](https://github.com/HKUDS/DeepTutor/issues/1131) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1132 | Issue | [chore(ci): format Python baseline for Ruff 0.16](https://github.com/HKUDS/DeepTutor/issues/1132) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1133 | Issue | [fix(video-learning): retry unavailable Invidious captions](https://github.com/HKUDS/DeepTutor/issues/1133) | closed | 2026-08-31 | 2026-08-31 | 0 |
| 1134 | PR | [fix(video-learning): retry unavailable Invidious captions (#1133)](https://github.com/HKUDS/DeepTutor/pull/1134) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1135 | PR | [test(video-learning): support lazy included routers (#1131)](https://github.com/HKUDS/DeepTutor/pull/1135) | closed | 2026-08-31 | 2026-08-31 | 3 |
| 1136 | PR | [chore(ci): format Python baseline for Ruff 0.16 (#1132)](https://github.com/HKUDS/DeepTutor/pull/1136) | closed | 2026-08-31 | 2026-09-04 | 2 |
| 1137 | Issue | [feat(video-learning): add timestamped transcript notes](https://github.com/HKUDS/DeepTutor/issues/1137) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1138 | Issue | [[Feature Request]:content-addressed dedup across reading / knowledge-base / chat attachments to reduce local storage footprint](https://github.com/HKUDS/DeepTutor/issues/1138) | open | 2026-08-31 | 2026-08-31 | 0 |
| 1139 | PR | [fix(web): localize MyAgentsPicker placeholder titles](https://github.com/HKUDS/DeepTutor/pull/1139) | closed | 2026-08-31 | 2026-08-31 | 0 |
| 1140 | Issue | [[Bug]: No module named 'fcntl' （win11 upgrade bug）](https://github.com/HKUDS/DeepTutor/issues/1140) | closed | 2026-08-31 | 2026-08-31 | 2 |
| 1141 | PR | [fix: provide contexts for mastery study](https://github.com/HKUDS/DeepTutor/pull/1141) | closed | 2026-08-31 | 2026-08-31 | 0 |
| 1142 | PR | [feat(video-learning): add timestamped transcript notes (#1137)](https://github.com/HKUDS/DeepTutor/pull/1142) | closed | 2026-08-31 | 2026-09-01 | 0 |
| 1143 | Issue | [Windows native Web startup fails because video_learning imports Unix-only fcntl](https://github.com/HKUDS/DeepTutor/issues/1143) | closed | 2026-08-31 | 2026-08-31 | 2 |
| 1144 | PR | [feat: add MiniMax Token Plan as a first-class LLM provider](https://github.com/HKUDS/DeepTutor/pull/1144) | closed | 2026-08-31 | 2026-08-31 | 1 |
| 1145 | PR | [fix(i18n): translate settings copy](https://github.com/HKUDS/DeepTutor/pull/1145) | closed | 2026-08-31 | 2026-09-16 | 0 |
| 1146 | PR | [fix(video-learning): avoid Unix-only fcntl import on Windows](https://github.com/HKUDS/DeepTutor/pull/1146) | closed | 2026-08-31 | 2026-08-31 | 0 |
| 1147 | Issue | [[Windows] Opening the browser sends CTRL_C_EVENT (SIGINT) that kills the launcher; conflicts with Ctrl+C](https://github.com/HKUDS/DeepTutor/issues/1147) | closed | 2026-08-31 | 2026-08-31 | 2 |
| 1148 | PR | [feat(launcher): add macOS startup command](https://github.com/HKUDS/DeepTutor/pull/1148) | closed | 2026-08-31 | 2026-09-16 | 0 |
| 1149 | PR | [feat(settings): add tool search](https://github.com/HKUDS/DeepTutor/pull/1149) | closed | 2026-08-31 | 2026-09-16 | 0 |
| 1150 | Issue | [fix(sandbox): enforce local exec output and process limits](https://github.com/HKUDS/DeepTutor/issues/1150) | closed | 2026-08-31 | 2026-08-31 | 0 |
| 1151 | PR | [fix(sandbox): enforce local exec output and process limits (#1150)](https://github.com/HKUDS/DeepTutor/pull/1151) | closed | 2026-08-31 | 2026-08-31 | 0 |
| 1152 | PR | [fix(runtime): ignore Windows SIGINT for deeptutor start (#1147)](https://github.com/HKUDS/DeepTutor/pull/1152) | closed | 2026-08-31 | 2026-08-31 | 2 |
| 1153 | PR | [test(video-learning): assert nested authentication policy (#1131)](https://github.com/HKUDS/DeepTutor/pull/1153) | closed | 2026-08-31 | 2026-10-04 | 4 |
| 1154 | PR | [feat(launcher): add Windows startup batch script](https://github.com/HKUDS/DeepTutor/pull/1154) | open | 2026-08-31 | 2026-08-31 | 0 |
| 1155 | PR | [docs: fix stale AGENTS.md paths for capability_result and app facade](https://github.com/HKUDS/DeepTutor/pull/1155) | open | 2026-08-31 | 2026-08-31 | 0 |
| 1156 | PR | [feat(video-learning): add public Invidious hub discovery (#997)](https://github.com/HKUDS/DeepTutor/pull/1156) | closed | 2026-08-31 | 2026-10-04 | 3 |
| 1157 | PR | [fix(codex): expose Luna none reasoning effort](https://github.com/HKUDS/DeepTutor/pull/1157) | closed | 2026-08-31 | 2026-09-21 | 0 |
| 1158 | Issue | [feat(video-learning): add recent video summaries](https://github.com/HKUDS/DeepTutor/issues/1158) | open | 2026-08-31 | 2026-08-31 | 0 |
| 1159 | PR | [feat(video-learning): add recent video summaries (#1158)](https://github.com/HKUDS/DeepTutor/pull/1159) | closed | 2026-08-31 | 2026-10-04 | 5 |
| 1160 | PR | [fix: prevent blank space below settings page](https://github.com/HKUDS/DeepTutor/pull/1160) | closed | 2026-09-01 | 2026-09-03 | 0 |
| 1161 | Issue | [[Bug]: Mastery Study page throws: useWatching must be used inside WatchingProvider](https://github.com/HKUDS/DeepTutor/issues/1161) | closed | 2026-09-01 | 2026-09-03 | 1 |
| 1162 | PR | [fix(web): decode unicode escapes in quiz card text](https://github.com/HKUDS/DeepTutor/pull/1162) | closed | 2026-09-01 | 2026-09-03 | 0 |
| 1163 | PR | [docs: add RepoCloud one-click deploy button](https://github.com/HKUDS/DeepTutor/pull/1163) | open | 2026-09-01 | 2026-09-10 | 0 |
| 1164 | Issue | [feat(video-learning): keep active transcript cues visible](https://github.com/HKUDS/DeepTutor/issues/1164) | closed | 2026-09-01 | 2026-09-03 | 1 |
| 1165 | PR | [feat(video-learning): keep active transcript cues visible (#1164)](https://github.com/HKUDS/DeepTutor/pull/1165) | closed | 2026-09-01 | 2026-09-03 | 1 |
| 1166 | Issue | [feat(video-learning): add transcript search](https://github.com/HKUDS/DeepTutor/issues/1166) | closed | 2026-09-01 | 2026-09-11 | 1 |
| 1167 | PR | [test(mastery): cover study context providers (#1161)](https://github.com/HKUDS/DeepTutor/pull/1167) | closed | 2026-09-01 | 2026-10-04 | 1 |
| 1168 | Issue | [fix(video-learning): defer restored material loading](https://github.com/HKUDS/DeepTutor/issues/1168) | closed | 2026-09-01 | 2026-09-03 | 1 |
| 1169 | PR | [fix(video-learning): defer restored material loading (#1168)](https://github.com/HKUDS/DeepTutor/pull/1169) | closed | 2026-09-01 | 2026-09-03 | 2 |
| 1170 | PR | [fix(web): give WatchingContext a safe inactive default](https://github.com/HKUDS/DeepTutor/pull/1170) | closed | 2026-09-01 | 2026-10-28 | 2 |
| 1171 | PR | [feat: pin LightRAG indexing models per knowledge base](https://github.com/HKUDS/DeepTutor/pull/1171) | closed | 2026-09-01 | 2026-09-04 | 0 |
| 1172 | Issue | [[Bug] Mastery study page crashes ("This page couldn't load") when sending a chat message](https://github.com/HKUDS/DeepTutor/issues/1172) | closed | 2026-09-01 | 2026-09-03 | 2 |
| 1173 | Issue | [[Bug] Mastery study page crashes ("This page couldn't load") when sending a chat message](https://github.com/HKUDS/DeepTutor/issues/1173) | closed | 2026-09-01 | 2026-09-03 | 2 |
| 1174 | PR | [feat: add LightRAG indexing model controls and provenance](https://github.com/HKUDS/DeepTutor/pull/1174) | closed | 2026-09-01 | 2026-09-04 | 0 |
| 1175 | PR | [fix(llm): replay Responses reasoning output items](https://github.com/HKUDS/DeepTutor/pull/1175) | open | 2026-09-01 | 2026-09-01 | 0 |
| 1176 | Issue | [[Feature Request]: Allow response language other than English and Chinese](https://github.com/HKUDS/DeepTutor/issues/1176) | closed | 2026-09-01 | 2026-10-05 | 1 |
| 1177 | Issue | [[Bug][Windows] ModuleNotFoundError: No module named 'fcntl' on launch and SIGINT signal handler crashes](https://github.com/HKUDS/DeepTutor/issues/1177) | closed | 2026-09-01 | 2026-09-03 | 6 |
| 1178 | PR | [fix: preserve raw content during Chinese Markdown streaming](https://github.com/HKUDS/DeepTutor/pull/1178) | closed | 2026-09-01 | 2026-09-03 | 0 |
| 1179 | PR | [feat(settings): allow any model reply language independently of the UI](https://github.com/HKUDS/DeepTutor/pull/1179) | closed | 2026-09-01 | 2026-09-06 | 2 |
| 1180 | Issue | [[Bug]:[v1.6.2] Mastery Waypoint crashes because Mastery layout lacks WatchingProvider](https://github.com/HKUDS/DeepTutor/issues/1180) | closed | 2026-09-01 | 2026-09-01 | 1 |
| 1181 | Issue | [[Bug]: Gemini tool-calling loop fails with 400 "missing thought_signature" on multi-round function calls](https://github.com/HKUDS/DeepTutor/issues/1181) | closed | 2026-09-02 | 2026-09-07 | 1 |
| 1182 | Issue | [[Feature Request]:[Mastery Path] Navigation bar and "Save to Notebook" missing from Mastery Path conversations (v1.6.3)](https://github.com/HKUDS/DeepTutor/issues/1182) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1183 | Issue | [[Bug]:No module named 'fcntl' （cron\repository.py）v1.6.3](https://github.com/HKUDS/DeepTutor/issues/1183) | closed | 2026-09-02 | 2026-09-03 | 4 |
| 1184 | PR | [fix(cron): guard fcntl for Windows (msvcrt fallback)](https://github.com/HKUDS/DeepTutor/pull/1184) | closed | 2026-09-02 | 2026-09-02 | 1 |
| 1185 | PR | [fix(agentic): harden Gemini thought_signature capture](https://github.com/HKUDS/DeepTutor/pull/1185) | closed | 2026-09-02 | 2026-09-06 | 2 |
| 1186 | PR | [fix(update): detect source checkouts before enabling auto-update](https://github.com/HKUDS/DeepTutor/pull/1186) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1187 | Issue | [feat(learning): add visual learning board for Guided Learning](https://github.com/HKUDS/DeepTutor/issues/1187) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1188 | PR | [feat(learning): add visual learning board](https://github.com/HKUDS/DeepTutor/pull/1188) | closed | 2026-09-02 | 2026-09-02 | 1 |
| 1189 | PR | [fix(mastery): restore Save to Notebook and turn navigator](https://github.com/HKUDS/DeepTutor/pull/1189) | closed | 2026-09-02 | 2026-09-04 | 2 |
| 1190 | Issue | [perf(session): avoid duplicating full turn event traces in messages](https://github.com/HKUDS/DeepTutor/issues/1190) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1191 | PR | [perf(session): lazily load turn event traces](https://github.com/HKUDS/DeepTutor/pull/1191) | closed | 2026-09-02 | 2026-09-03 | 0 |
| 1192 | Issue | [feat(video-learning): connect Invidious accounts](https://github.com/HKUDS/DeepTutor/issues/1192) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1193 | PR | [feat(video-learning): connect Invidious accounts (#1192)](https://github.com/HKUDS/DeepTutor/pull/1193) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1194 | PR | [feat(learning): add visual learning board (#1187)](https://github.com/HKUDS/DeepTutor/pull/1194) | closed | 2026-09-02 | 2026-09-03 | 1 |
| 1195 | PR | [fix(llm): fall back on DeepSeek reasoning-replay 400s from Responses turns](https://github.com/HKUDS/DeepTutor/pull/1195) | closed | 2026-09-02 | 2026-09-03 | 0 |
| 1196 | PR | [fix(web): redirect legacy mastery /study URLs to /sessions](https://github.com/HKUDS/DeepTutor/pull/1196) | closed | 2026-09-02 | 2026-09-03 | 0 |
| 1197 | PR | [test(cron): cover cross-platform migration locks](https://github.com/HKUDS/DeepTutor/pull/1197) | closed | 2026-09-02 | 2026-09-03 | 0 |
| 1198 | PR | [fix(cron): support migration locks on Windows](https://github.com/HKUDS/DeepTutor/pull/1198) | closed | 2026-09-02 | 2026-09-02 | 1 |
| 1199 | PR | [fix(agentic): fall back for Gemini thinking tools](https://github.com/HKUDS/DeepTutor/pull/1199) | open | 2026-09-02 | 2026-09-02 | 0 |
| 1200 | PR | [fix(cli): expose knowledge-base progress events](https://github.com/HKUDS/DeepTutor/pull/1200) | closed | 2026-09-03 | 2026-09-03 | 0 |
| 1201 | PR | [fix(ci): restore dev release checks](https://github.com/HKUDS/DeepTutor/pull/1201) | closed | 2026-09-03 | 2026-09-03 | 0 |
| 1202 | Issue | [math_animator pipeline returns empty response for structured JSON prompts (content: null)](https://github.com/HKUDS/DeepTutor/issues/1202) | closed | 2026-09-03 | 2026-09-10 | 2 |
| 1203 | Issue | [feat(video-learning): export timestamped notes as markdown](https://github.com/HKUDS/DeepTutor/issues/1203) | closed | 2026-09-03 | 2026-09-03 | 1 |
| 1204 | PR | [feat(video-learning): export timestamped notes as markdown (#1203)](https://github.com/HKUDS/DeepTutor/pull/1204) | closed | 2026-09-03 | 2026-09-03 | 2 |
| 1205 | PR | [feat(search): filter unsafe web-search titles and snippets](https://github.com/HKUDS/DeepTutor/pull/1205) | closed | 2026-09-03 | 2026-09-03 | 0 |
| 1206 | Issue | [feat(mastery): redesign planning with optional AI-assisted route design](https://github.com/HKUDS/DeepTutor/issues/1206) | closed | 2026-09-03 | 2026-09-06 | 2 |
| 1207 | Issue | [feat(video-learning): add playback speed controls](https://github.com/HKUDS/DeepTutor/issues/1207) | closed | 2026-09-03 | 2026-09-11 | 1 |
| 1208 | PR | [feat: add remote Hermes connected agent backend](https://github.com/HKUDS/DeepTutor/pull/1208) | closed | 2026-09-03 | 2026-09-03 | 1 |
| 1209 | Issue | [Settings: capability readiness overview, cross-setting contradiction checks, and value-free profile export](https://github.com/HKUDS/DeepTutor/issues/1209) | open | 2026-09-03 | 2026-09-03 | 0 |
| 1210 | PR | [fix(ci): stabilize current dependency and reading gates](https://github.com/HKUDS/DeepTutor/pull/1210) | closed | 2026-09-03 | 2026-10-16 | 0 |
| 1211 | PR | [refactor(video-learning): separate Invidious account adapters](https://github.com/HKUDS/DeepTutor/pull/1211) | closed | 2026-09-03 | 2026-10-16 | 0 |
| 1212 | PR | [revert: restore main after #1208 targeted the wrong base](https://github.com/HKUDS/DeepTutor/pull/1212) | closed | 2026-09-03 | 2026-10-16 | 0 |
| 1213 | PR | [feat: add hardened remote Hermes connected agent backend](https://github.com/HKUDS/DeepTutor/pull/1213) | closed | 2026-09-03 | 2026-10-16 | 0 |
| 1214 | PR | [feat(video-learning): add playback speed controls (#1207)](https://github.com/HKUDS/DeepTutor/pull/1214) | closed | 2026-09-03 | 2026-09-10 | 2 |
| 1215 | Issue | [fix(ci): restore dev route budgets](https://github.com/HKUDS/DeepTutor/issues/1215) | open | 2026-09-03 | 2026-09-05 | 1 |
| 1216 | PR | [fix(ci): restore dev route budgets (#1215)](https://github.com/HKUDS/DeepTutor/pull/1216) | closed | 2026-09-03 | 2026-10-04 | 1 |
| 1217 | PR | [feat(mastery): add learning plan workflow foundation](https://github.com/HKUDS/DeepTutor/pull/1217) | closed | 2026-09-03 | 2026-09-06 | 3 |
| 1218 | PR | [feat(storage): content-addressed dedup for chat attachments](https://github.com/HKUDS/DeepTutor/pull/1218) | open | 2026-09-03 | 2026-09-09 | 0 |
| 1219 | PR | [fix(agents): retry empty structured JSON in math animator](https://github.com/HKUDS/DeepTutor/pull/1219) | open | 2026-09-03 | 2026-09-09 | 0 |
| 1220 | Issue | [[Bug]: gpt-5.6-terra model not working](https://github.com/HKUDS/DeepTutor/issues/1220) | open | 2026-09-03 | 2026-09-03 | 0 |
| 1221 | PR | [fix(cli): give reasoning models room in the init connectivity probe](https://github.com/HKUDS/DeepTutor/pull/1221) | open | 2026-09-03 | 2026-09-08 | 1 |
| 1222 | Issue | [[Bug]: Learning accounts — the policy reaches the client but nothing reads it, and CI cannot see the fallout](https://github.com/HKUDS/DeepTutor/issues/1222) | closed | 2026-09-03 | 2026-10-08 | 2 |
| 1223 | Issue | [[Bug]: PDF uploads in chat dont get easily read in next message in same chat because of tool error](https://github.com/HKUDS/DeepTutor/issues/1223) | open | 2026-09-03 | 2026-09-03 | 0 |
| 1224 | PR | [feat(video-learning): add transcript search (#1166)](https://github.com/HKUDS/DeepTutor/pull/1224) | closed | 2026-09-04 | 2026-09-10 | 2 |
| 1225 | PR | [fix(learner): honor web learning policy (#1222)](https://github.com/HKUDS/DeepTutor/pull/1225) | closed | 2026-09-04 | 2026-10-04 | 7 |
| 1226 | PR | [feat(learning): soft journal for multi-session teaching](https://github.com/HKUDS/DeepTutor/pull/1226) | open | 2026-09-04 | 2026-09-09 | 1 |
| 1227 | Issue | [[Bug]: moonshot k3-256k model id misses the temperature override (invalid temperature: only 1 is allowed)](https://github.com/HKUDS/DeepTutor/issues/1227) | closed | 2026-09-04 | 2026-09-08 | 1 |
| 1228 | Issue | [Learner accounts get 403 on /api/courses — and the UI masks it as an empty state](https://github.com/HKUDS/DeepTutor/issues/1228) | open | 2026-09-04 | 2026-09-12 | 3 |
| 1229 | Issue | [Partner Feishu channel: group-chat sessions are indistinguishable from DMs in the conversation list](https://github.com/HKUDS/DeepTutor/issues/1229) | closed | 2026-09-04 | 2026-09-08 | 1 |
| 1230 | Issue | [[Feature Request]:Migrate original admin account to sub‑account & collapsible sidebar items for multi‑user mode](https://github.com/HKUDS/DeepTutor/issues/1230) | open | 2026-09-04 | 2026-09-10 | 1 |
| 1231 | PR | [fix(learner): restore course access (#1228)](https://github.com/HKUDS/DeepTutor/pull/1231) | closed | 2026-09-04 | 2026-09-08 | 1 |
| 1232 | PR | [fix: omit temperature for k3-256k](https://github.com/HKUDS/DeepTutor/pull/1232) | open | 2026-09-04 | 2026-09-04 | 0 |
| 1233 | PR | [feat(reading): support independent extension installation and fixed toolbar (#1233)](https://github.com/HKUDS/DeepTutor/pull/1233) | closed | 2026-09-05 | 2026-10-04 | 1 |
| 1234 | Issue | [[Question]:i can't communicate with my partner on the Web page or QQ Bot platform](https://github.com/HKUDS/DeepTutor/issues/1234) | closed | 2026-09-05 | 2026-09-08 | 3 |
| 1235 | Issue | [[Bug / Enhancement] `RichMarkdownRenderer` fails to sanitize common LLM streaming Markdown anomalies (heading spacing, merged table rows, code block titles)](https://github.com/HKUDS/DeepTutor/issues/1235) | closed | 2026-09-05 | 2026-09-08 | 1 |
| 1236 | Issue | [feat(reading): render EPUBs as responsive book spreads](https://github.com/HKUDS/DeepTutor/issues/1236) | open | 2026-09-05 | 2026-09-05 | 1 |
| 1237 | PR | [feat(reading): add book paging and fullscreen to EPUBs](https://github.com/HKUDS/DeepTutor/pull/1237) | closed | 2026-09-05 | 2026-10-04 | 1 |
| 1238 | Issue | [feat(video-learning): give Immersive Watching a dedicated workspace](https://github.com/HKUDS/DeepTutor/issues/1238) | open | 2026-09-05 | 2026-09-05 | 0 |
| 1239 | PR | [feat(video-learning): add a dedicated Watching workspace](https://github.com/HKUDS/DeepTutor/pull/1239) | closed | 2026-09-05 | 2026-09-10 | 2 |
| 1240 | Issue | [feat(video-learning): browse connected Invidious accounts in Watching](https://github.com/HKUDS/DeepTutor/issues/1240) | open | 2026-09-05 | 2026-09-05 | 4 |
| 1241 | PR | [feat(video-learning): browse connected Invidious accounts](https://github.com/HKUDS/DeepTutor/pull/1241) | closed | 2026-09-05 | 2026-09-10 | 5 |
| 1242 | Issue | [[Bug] 官方所指 MN4 add-on v0.1.0 为 MN3 契约且无法解析；附 MN4 原生实现参考](https://github.com/HKUDS/DeepTutor/issues/1242) | open | 2026-09-05 | 2026-09-10 | 2 |
| 1243 | PR | [feat: bundle a MarginNote 4 native add-on for the MN4 bridge](https://github.com/HKUDS/DeepTutor/pull/1243) | open | 2026-09-05 | 2026-09-10 | 2 |
| 1244 | Issue | [Feature: let Partner conversations record wrong questions into the Question Notebook](https://github.com/HKUDS/DeepTutor/issues/1244) | open | 2026-09-05 | 2026-09-05 | 0 |
| 1245 | Issue | [Bug: question-notebook upsert with base64 images fails with OperationalError: 22 values for 23 columns](https://github.com/HKUDS/DeepTutor/issues/1245) | closed | 2026-09-05 | 2026-09-08 | 2 |
| 1246 | Issue | [feat(watching): integrate fullscreen learning and source-timed two-line captions](https://github.com/HKUDS/DeepTutor/issues/1246) | open | 2026-09-05 | 2026-09-05 | 2 |
| 1247 | PR | [fix: persist question notebook answer images](https://github.com/HKUDS/DeepTutor/pull/1247) | open | 2026-09-05 | 2026-09-05 | 0 |
| 1248 | PR | [feat(watching): integrate fullscreen learning and two-line captions](https://github.com/HKUDS/DeepTutor/pull/1248) | closed | 2026-09-05 | 2026-09-10 | 4 |
| 1249 | Issue | [[Feature Request]:](https://github.com/HKUDS/DeepTutor/issues/1249) | open | 2026-09-05 | 2026-09-05 | 0 |
| 1250 | Issue | [[Bug]: Codex provider forwards nested named-function tool_choice without Responses conversion](https://github.com/HKUDS/DeepTutor/issues/1250) | closed | 2026-09-05 | 2026-09-08 | 1 |
| 1251 | PR | [fix: normalize Codex named-function tool choice for Responses](https://github.com/HKUDS/DeepTutor/pull/1251) | closed | 2026-09-05 | 2026-09-07 | 1 |
| 1252 | Issue | [Codex OAuth has no in-page recovery when localhost callback cannot reach Docker](https://github.com/HKUDS/DeepTutor/issues/1252) | closed | 2026-09-05 | 2026-09-08 | 1 |
| 1253 | PR | [fix(codex): recover Docker OAuth callbacks in settings](https://github.com/HKUDS/DeepTutor/pull/1253) | closed | 2026-09-05 | 2026-09-08 | 1 |
| 1254 | Issue | [Watching: align active transcript with video captions and center on mobile](https://github.com/HKUDS/DeepTutor/issues/1254) | open | 2026-09-05 | 2026-09-05 | 1 |
| 1255 | PR | [fix(watching): align transcript follow with video captions](https://github.com/HKUDS/DeepTutor/pull/1255) | closed | 2026-09-05 | 2026-09-10 | 2 |
| 1256 | Issue | [Watching notes: preserve capture timestamps and drafts across async saves](https://github.com/HKUDS/DeepTutor/issues/1256) | open | 2026-09-05 | 2026-09-05 | 1 |
| 1257 | PR | [fix(watching): preserve note capture time and drafts across async saves](https://github.com/HKUDS/DeepTutor/pull/1257) | closed | 2026-09-05 | 2026-09-10 | 3 |
| 1258 | PR | [fix: persist notebook answer images](https://github.com/HKUDS/DeepTutor/pull/1258) | closed | 2026-09-05 | 2026-09-07 | 0 |
| 1259 | Issue | [[Bug]:Partner KB provisioning fails for connected (Obsidian / linked) knowledge bases — `_copy_knowledge_base` uses `copytree` on a pointer KB that has no on-disk folder by design](https://github.com/HKUDS/DeepTutor/issues/1259) | closed | 2026-09-05 | 2026-09-08 | 1 |
| 1260 | PR | [fix: support Moonshot k3-256k temperature override](https://github.com/HKUDS/DeepTutor/pull/1260) | closed | 2026-09-06 | 2026-09-07 | 0 |
| 1261 | PR | [fix(partners): register connected KBs instead of copytree-ing a folder that never exists](https://github.com/HKUDS/DeepTutor/pull/1261) | closed | 2026-09-06 | 2026-09-07 | 0 |
| 1262 | Issue | [README: refresh UI screenshots and walkthroughs for v1.6.4/v1.6.5](https://github.com/HKUDS/DeepTutor/issues/1262) | open | 2026-09-06 | 2026-09-09 | 3 |
| 1263 | PR | [docs(web): update overview screenshot for v1.6.5](https://github.com/HKUDS/DeepTutor/pull/1263) | closed | 2026-09-06 | 2026-09-08 | 0 |
| 1264 | PR | [fix(codex): expose eligible GPT-6 Astra in refreshed catalogs](https://github.com/HKUDS/DeepTutor/pull/1264) | closed | 2026-09-06 | 2026-09-08 | 0 |
| 1265 | PR | [feat(lightrag): configure independent roles and confirmed rebuilds](https://github.com/HKUDS/DeepTutor/pull/1265) | closed | 2026-09-06 | 2026-09-21 | 0 |
| 1266 | PR | [fix(chat): prevent PDF attachment tool hallucinations (#1223)](https://github.com/HKUDS/DeepTutor/pull/1266) | closed | 2026-09-06 | 2026-09-07 | 0 |
| 1267 | Issue | [[Bug] Partner Chat generated artifacts fail to download (404 Not Found) due to missing workspace routing, scoped presentation item lookup, and relative output links](https://github.com/HKUDS/DeepTutor/issues/1267) | closed | 2026-09-06 | 2026-09-08 | 1 |
| 1268 | PR | [feat(rag): show LlamaIndex source figures in chat](https://github.com/HKUDS/DeepTutor/pull/1268) | open | 2026-09-06 | 2026-09-06 | 0 |
| 1269 | PR | [fix(partners): restore generated artifact downloads (#1267)](https://github.com/HKUDS/DeepTutor/pull/1269) | closed | 2026-09-06 | 2026-09-10 | 2 |
| 1270 | PR | [feat(llm): allow any model reply language independently of the UI locale](https://github.com/HKUDS/DeepTutor/pull/1270) | closed | 2026-09-06 | 2026-10-05 | 2 |
| 1271 | PR | [fix(llm): retry Responses requests without unsupported status](https://github.com/HKUDS/DeepTutor/pull/1271) | closed | 2026-09-06 | 2026-09-07 | 0 |
| 1272 | PR | [feat(subagent): add ACP client backend (Part of #1028)](https://github.com/HKUDS/DeepTutor/pull/1272) | open | 2026-09-06 | 2026-09-09 | 0 |
| 1273 | Issue | [[Bug]:v1.6.5: ask_user single-choice question auto-closes with "这道题已经不再等待作答" before user submits — turn-end-state desync](https://github.com/HKUDS/DeepTutor/issues/1273) | closed | 2026-09-06 | 2026-09-08 | 2 |
| 1274 | PR | [fix(web): drop generated brand-icon table from app-shell chunk (unblocks route budgets)](https://github.com/HKUDS/DeepTutor/pull/1274) | closed | 2026-09-06 | 2026-09-07 | 2 |
| 1275 | PR | [chore(lightrag): upgrade native SDK to 1.5.7](https://github.com/HKUDS/DeepTutor/pull/1275) | closed | 2026-09-06 | 2026-09-08 | 0 |
| 1276 | PR | [fix(web): normalize malformed ATX headings safely](https://github.com/HKUDS/DeepTutor/pull/1276) | closed | 2026-09-06 | 2026-09-07 | 0 |
| 1277 | PR | [feat(cli): add GitHub Copilot device login to init](https://github.com/HKUDS/DeepTutor/pull/1277) | closed | 2026-09-07 | 2026-10-07 | 0 |
| 1278 | PR | [fix(chat): preserve pending ask_user turns (#1273)](https://github.com/HKUDS/DeepTutor/pull/1278) | closed | 2026-09-07 | 2026-09-08 | 0 |
| 1279 | PR | [fix: require recorded learner evidence before awarding mastery](https://github.com/HKUDS/DeepTutor/pull/1279) | open | 2026-09-07 | 2026-09-10 | 1 |
| 1280 | PR | [fix: avoid progress errors after empty knowledge base creation](https://github.com/HKUDS/DeepTutor/pull/1280) | closed | 2026-09-07 | 2026-09-08 | 0 |
| 1281 | PR | [fix: enforce native LightRAG embedding compatibility](https://github.com/HKUDS/DeepTutor/pull/1281) | closed | 2026-09-07 | 2026-09-21 | 0 |
| 1282 | PR | [fix: restore formatting and deterministic CI checks](https://github.com/HKUDS/DeepTutor/pull/1282) | closed | 2026-09-07 | 2026-09-08 | 0 |
| 1283 | PR | [fix(session): include ai_judgment in notebook_entries INSERT (#1245)](https://github.com/HKUDS/DeepTutor/pull/1283) | closed | 2026-09-07 | 2026-09-07 | 1 |
| 1284 | PR | [fix: include ai_judgment in notebook INSERT, unblock CI gates, fix settings readiness panel](https://github.com/HKUDS/DeepTutor/pull/1284) | closed | 2026-09-07 | 2026-09-10 | 1 |
| 1285 | PR | [fix: support GPT-5.6-Terra max_completion_tokens parameter](https://github.com/HKUDS/DeepTutor/pull/1285) | closed | 2026-09-07 | 2026-09-10 | 1 |
| 1286 | PR | [fix(workspace): resolve workspace items from partner presentations](https://github.com/HKUDS/DeepTutor/pull/1286) | closed | 2026-09-07 | 2026-09-09 | 0 |
| 1287 | PR | [fix: resolve service mypy errors](https://github.com/HKUDS/DeepTutor/pull/1287) | closed | 2026-09-08 | 2026-09-08 | 1 |
| 1288 | Issue | [[Bug]: v1.6.5 Duplicate flickering blank "New Chat" on Home click](https://github.com/HKUDS/DeepTutor/issues/1288) | closed | 2026-09-08 | 2026-09-08 | 0 |
| 1289 | Issue | [[Bug]: v1.6.5 Disabled submit button in Mastery Path mode](https://github.com/HKUDS/DeepTutor/issues/1289) | closed | 2026-09-08 | 2026-09-10 | 1 |
| 1291 | PR | [fix(mastery): enable free-text question submission (#1289)](https://github.com/HKUDS/DeepTutor/pull/1291) | closed | 2026-09-08 | 2026-09-10 | 0 |
| 1292 | Issue | [feat(knowledge): add KB frontier discovery tool](https://github.com/HKUDS/DeepTutor/issues/1292) | closed | 2026-09-08 | 2026-10-07 | 1 |
| 1293 | PR | [feat(knowledge): add KB frontier discovery tool (#1292)](https://github.com/HKUDS/DeepTutor/pull/1293) | closed | 2026-09-08 | 2026-09-13 | 0 |
| 1294 | Issue | [feat(visualize): add Mermaid mindmap visualizer](https://github.com/HKUDS/DeepTutor/issues/1294) | closed | 2026-09-08 | 2026-10-07 | 1 |
| 1295 | PR | [feat(visualize): add Mermaid mindmap visualizer (#1294)](https://github.com/HKUDS/DeepTutor/pull/1295) | closed | 2026-09-08 | 2026-10-07 | 1 |
| 1296 | Issue | [[Feature Request]: Automatically discover the Codex client version for model catalog refresh](https://github.com/HKUDS/DeepTutor/issues/1296) | closed | 2026-09-08 | 2026-10-07 | 3 |
| 1297 | Issue | [[Bug]: v1.6.6 Mastery ask_user Submit Answer does nothing and turn remains waiting_input](https://github.com/HKUDS/DeepTutor/issues/1297) | closed | 2026-09-08 | 2026-09-10 | 0 |
| 1298 | PR | [fix(llm): raise a streamed provider error instead of answering with it](https://github.com/HKUDS/DeepTutor/pull/1298) | closed | 2026-09-08 | 2026-09-10 | 0 |
| 1299 | Issue | [[Bug]: v1.6.6 immersive reader omits JPEG2000 page images due to missing decoder assets/configuration](https://github.com/HKUDS/DeepTutor/issues/1299) | closed | 2026-09-08 | 2026-09-10 | 1 |
| 1300 | PR | [fix(llm): survive api_key key pools in the config resolver](https://github.com/HKUDS/DeepTutor/pull/1300) | closed | 2026-09-08 | 2026-09-24 | 0 |
| 1301 | Issue | [feat(knowledge): add URL import for knowledge bases](https://github.com/HKUDS/DeepTutor/issues/1301) | closed | 2026-09-08 | 2026-09-08 | 1 |
| 1302 | PR | [feat(knowledge): add URL import for knowledge bases (#1301)](https://github.com/HKUDS/DeepTutor/pull/1302) | closed | 2026-09-08 | 2026-09-08 | 1 |
| 1303 | Issue | [feat(knowledge): add Zotero integration with BibTeX parsing and library search](https://github.com/HKUDS/DeepTutor/issues/1303) | closed | 2026-09-08 | 2026-10-07 | 1 |
| 1304 | PR | [feat(knowledge): add Zotero search tool and BibTeX structured parsing (#1303)](https://github.com/HKUDS/DeepTutor/pull/1304) | closed | 2026-09-08 | 2026-09-10 | 2 |
| 1305 | PR | [fix(reading): package PDF.js decoder assets (#1299)](https://github.com/HKUDS/DeepTutor/pull/1305) | closed | 2026-09-08 | 2026-09-10 | 0 |
| 1306 | PR | [docs(web): document v1.6.4/v1.6.5 screenshot status](https://github.com/HKUDS/DeepTutor/pull/1306) | closed | 2026-09-08 | 2026-09-10 | 0 |
| 1307 | Issue | [feat(plugins): add managed third-party plugin platform](https://github.com/HKUDS/DeepTutor/issues/1307) | closed | 2026-09-08 | 2026-10-08 | 1 |
| 1308 | PR | [fix(web): fall back when crypto.randomUUID is unavailable for command ids](https://github.com/HKUDS/DeepTutor/pull/1308) | closed | 2026-09-08 | 2026-09-10 | 0 |
| 1309 | PR | [feat(plugins): add managed third-party plugin platform (#1307)](https://github.com/HKUDS/DeepTutor/pull/1309) | closed | 2026-09-08 | 2026-10-04 | 1 |
| 1310 | PR | [feat(web): fully resizable reading workspace panels + focus preset](https://github.com/HKUDS/DeepTutor/pull/1310) | closed | 2026-09-08 | 2026-10-07 | 0 |
| 1311 | PR | [feat(codex-auth): discover stable client version (#1296)](https://github.com/HKUDS/DeepTutor/pull/1311) | closed | 2026-09-08 | 2026-09-11 | 3 |
| 1312 | PR | [fix(chat): always clear sending state in useCardSubmission (#1289)](https://github.com/HKUDS/DeepTutor/pull/1312) | closed | 2026-09-09 | 2026-09-09 | 0 |
| 1313 | PR | [fix(chat): always clear sending state in useCardSubmission (#1289)](https://github.com/HKUDS/DeepTutor/pull/1313) | closed | 2026-09-09 | 2026-09-10 | 1 |
| 1314 | PR | [fix(web): render settings readiness panel for read-only users](https://github.com/HKUDS/DeepTutor/pull/1314) | closed | 2026-09-09 | 2026-09-10 | 0 |
| 1315 | PR | [fix(workspace): resolve workspace items from partner presentations (#1267)](https://github.com/HKUDS/DeepTutor/pull/1315) | closed | 2026-09-09 | 2026-09-10 | 1 |
| 1316 | Issue | [[Bug]:Book spine synthesis fails with "LLM returned empty response" when using a reasoning model via an Anthropic-format endpoint](https://github.com/HKUDS/DeepTutor/issues/1316) | closed | 2026-09-09 | 2026-09-10 | 1 |
| 1317 | PR | [feat(codex): automatically discover client versions for model catalog refresh](https://github.com/HKUDS/DeepTutor/pull/1317) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1318 | Issue | [[Bug]: Quiz generation silently drops to 0 or 1 questions when the Plan step's chain-of-thought exceeds its token budget](https://github.com/HKUDS/DeepTutor/issues/1318) | closed | 2026-09-09 | 2026-09-10 | 2 |
| 1319 | PR | [feat：Use Electron to build desktop applications for Linux, macOS, and Windows.](https://github.com/HKUDS/DeepTutor/pull/1319) | closed | 2026-09-09 | 2026-09-09 | 0 |
| 1320 | PR | [fix(config): let a book capability's agents.yaml settings take effect](https://github.com/HKUDS/DeepTutor/pull/1320) | closed | 2026-09-09 | 2026-09-10 | 1 |
| 1321 | PR | [fix(book): configure agent token budget (#1316)](https://github.com/HKUDS/DeepTutor/pull/1321) | closed | 2026-09-09 | 2026-09-10 | 1 |
| 1322 | PR | [feat：Use Electron to build desktop applications for Linux, macOS, and Windows.](https://github.com/HKUDS/DeepTutor/pull/1322) | open | 2026-09-09 | 2026-10-20 | 2 |
| 1323 | PR | [fix(learner): complete surface map for first-party learner screens + flip preset on restrictions assignment (#1222)](https://github.com/HKUDS/DeepTutor/pull/1323) | closed | 2026-09-09 | 2026-09-24 | 4 |
| 1324 | Issue | [[Bug] GeoGebra visualizer: known-fatal command patterns pass validation and runtime errors never reach the repair loop](https://github.com/HKUDS/DeepTutor/issues/1324) | closed | 2026-09-09 | 2026-09-14 | 4 |
| 1325 | PR | [fix(questions): reject incomplete quiz plans](https://github.com/HKUDS/DeepTutor/pull/1325) | closed | 2026-09-09 | 2026-09-14 | 0 |
| 1326 | Issue | [[Feature Request]: Expose local folder linking and sync controls in the Knowledge Center UI](https://github.com/HKUDS/DeepTutor/issues/1326) | closed | 2026-09-09 | 2026-10-07 | 1 |
| 1327 | PR | [fix(web): support current Codex chat history imports](https://github.com/HKUDS/DeepTutor/pull/1327) | closed | 2026-09-09 | 2026-09-10 | 0 |
| 1328 | Issue | [[Bug]: chat 回复仅显示 'I could not produce a useful response'：DeepSeek 推理模型把整轮输出预算烧在思考上 labels: ["bug", "triage"]](https://github.com/HKUDS/DeepTutor/issues/1328) | closed | 2026-09-09 | 2026-09-23 | 1 |
| 1329 | Issue | [feat(users): add batch import and deletion](https://github.com/HKUDS/DeepTutor/issues/1329) | closed | 2026-09-09 | 2026-10-07 | 2 |
| 1330 | PR | [feat(users): add batch import and deletion (#1329)](https://github.com/HKUDS/DeepTutor/pull/1330) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1331 | PR | [fix: handle DeepSeek reasoning budget exhaustion](https://github.com/HKUDS/DeepTutor/pull/1331) | closed | 2026-09-09 | 2026-09-16 | 0 |
| 1332 | PR | [fix(turns): log when a coordinator-routed reply finds no local waiter](https://github.com/HKUDS/DeepTutor/pull/1332) | closed | 2026-09-09 | 2026-09-10 | 0 |
| 1333 | PR | [fix(chat): recover hallucinated PDF tool calls for attached sources](https://github.com/HKUDS/DeepTutor/pull/1333) | closed | 2026-09-09 | 2026-09-10 | 0 |
| 1334 | PR | [feat(knowledge): add linked folder manual sync](https://github.com/HKUDS/DeepTutor/pull/1334) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1335 | PR | [feat: add french as supported language](https://github.com/HKUDS/DeepTutor/pull/1335) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1336 | Issue | [[Feature Request]:[Notebook/UX] Note "edit" is buried in the ⋮ menu while the pencil at top only renames the notebook](https://github.com/HKUDS/DeepTutor/issues/1336) | closed | 2026-09-09 | 2026-10-07 | 2 |
| 1337 | PR | [docs(web): add v1.6.5 settings screenshots](https://github.com/HKUDS/DeepTutor/pull/1337) | closed | 2026-09-09 | 2026-09-10 | 0 |
| 1338 | PR | [fix(graphrag): prevent pandas.period extension conflicts on Windows](https://github.com/HKUDS/DeepTutor/pull/1338) | closed | 2026-09-09 | 2026-09-10 | 1 |
| 1339 | PR | [feat(notebook): expose direct record editing](https://github.com/HKUDS/DeepTutor/pull/1339) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1340 | PR | [feat(search): add Web Risk lookups and renumber filtered citations (#375)](https://github.com/HKUDS/DeepTutor/pull/1340) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1341 | PR | [feat(partners): record wrong questions into the question bank (#1244)](https://github.com/HKUDS/DeepTutor/pull/1341) | closed | 2026-09-09 | 2026-09-19 | 0 |
| 1343 | PR | [fix(anthropic): stop sending `temperature` to Claude Sonnet 5 / Opus 4.8](https://github.com/HKUDS/DeepTutor/pull/1343) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1344 | PR | [feat(i18n): add Ukrainian as a full interface and output language](https://github.com/HKUDS/DeepTutor/pull/1344) | closed | 2026-09-09 | 2026-09-23 | 0 |
| 1345 | PR | [feat(settings): expand response language options](https://github.com/HKUDS/DeepTutor/pull/1345) | closed | 2026-09-09 | 2026-09-23 | 2 |
| 1346 | PR | [fix(visualize): reject fatal GeoGebra Text patterns and surface evalCommand failures](https://github.com/HKUDS/DeepTutor/pull/1346) | closed | 2026-09-09 | 2026-09-10 | 0 |
| 1347 | Issue | [[Bug]: read_skill conflates missing file with missing skill, seeding citation fabrication loop in chat](https://github.com/HKUDS/DeepTutor/issues/1347) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1348 | Issue | [[Bug]: openrouter imagegen](https://github.com/HKUDS/DeepTutor/issues/1348) | closed | 2026-09-10 | 2026-09-23 | 3 |
| 1349 | PR | [fix(skills): distinguish missing file from missing skill in read_skill](https://github.com/HKUDS/DeepTutor/pull/1349) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1350 | PR | [feat(watching): preserve note timestamps and add save retry UX](https://github.com/HKUDS/DeepTutor/pull/1350) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1351 | PR | [fix(watching): clamp transcript alignment to middle 50% and respect reduced motion](https://github.com/HKUDS/DeepTutor/pull/1351) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1352 | Issue | [[Bug] Book generation leaks LLM thinking/scratchpad into chapter content](https://github.com/HKUDS/DeepTutor/issues/1352) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1353 | PR | [fix(imagegen): retry with image-only modalities when both are unsupported](https://github.com/HKUDS/DeepTutor/pull/1353) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1354 | Issue | [[Bug] Codex chat history import returns HTTP 400](https://github.com/HKUDS/DeepTutor/issues/1354) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1355 | Issue | [[Bug]: Research tool timeout and retry settings are ignored](https://github.com/HKUDS/DeepTutor/issues/1355) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1356 | Issue | [[Bug]: Knowledge retrieval obscures embedding connectivity failures](https://github.com/HKUDS/DeepTutor/issues/1356) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1357 | PR | [fix(research): enforce tool timeout and retry policy (#1355)](https://github.com/HKUDS/DeepTutor/pull/1357) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1358 | PR | [fix(rag): surface embedding connectivity failures (#1356)](https://github.com/HKUDS/DeepTutor/pull/1358) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1359 | Issue | [[Bug]:主页聊天窗口调用 ask_user 后卡片报错且主对话被锁死](https://github.com/HKUDS/DeepTutor/issues/1359) | closed | 2026-09-10 | 2026-10-07 | 1 |
| 1360 | PR | [feat: add Grok CLI subagent connector](https://github.com/HKUDS/DeepTutor/pull/1360) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1361 | PR | [fix(turns): reap an unowned waiting_input turn when a reply arrives (#1297)](https://github.com/HKUDS/DeepTutor/pull/1361) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1362 | PR | [fix(geogebra): repair image analysis that crashed before any model call](https://github.com/HKUDS/DeepTutor/pull/1362) | closed | 2026-09-10 | 2026-09-10 | 0 |
| 1363 | PR | [fix(chat): unlock the window when ask_user replies never land](https://github.com/HKUDS/DeepTutor/pull/1363) | closed | 2026-09-10 | 2026-09-10 | 2 |
| 1364 | Issue | [[Bug]: Mastery Path question cards do not render LaTeX in prompts, options, or grading explanations](https://github.com/HKUDS/DeepTutor/issues/1364) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1365 | PR | [fix: render LaTeX in mastery question cards](https://github.com/HKUDS/DeepTutor/pull/1365) | closed | 2026-09-10 | 2026-09-10 | 1 |
| 1366 | PR | [fix(book): isolate LLM scratchpad from generated content](https://github.com/HKUDS/DeepTutor/pull/1366) | closed | 2026-09-10 | 2026-09-16 | 0 |
| 1367 | PR | [feat(reading): add fullscreen learning workspace shell (#1367)](https://github.com/HKUDS/DeepTutor/pull/1367) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1368 | PR | [feat(learner): add account-scoped reading learning records (#1109)](https://github.com/HKUDS/DeepTutor/pull/1368) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1369 | PR | [feat(learner): add personal learning progress view (#1130)](https://github.com/HKUDS/DeepTutor/pull/1369) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1370 | PR | [fix(skills): improve read_skill file recovery (#1347)](https://github.com/HKUDS/DeepTutor/pull/1370) | closed | 2026-09-10 | 2026-09-14 | 1 |
| 1371 | PR | [feat(knowledge): add Zotero BibTeX search (#1303)](https://github.com/HKUDS/DeepTutor/pull/1371) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1372 | PR | [feat(knowledge): expose linked folder sync controls (#1326)](https://github.com/HKUDS/DeepTutor/pull/1372) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1373 | PR | [fix(turns): recover replies after waiter queue loss](https://github.com/HKUDS/DeepTutor/pull/1373) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1374 | PR | [feat(sidebar): collapse fixed multi-user sections (#1230)](https://github.com/HKUDS/DeepTutor/pull/1374) | open | 2026-09-10 | 2026-09-10 | 0 |
| 1375 | PR | [fix(users): derive learner preset from active policy](https://github.com/HKUDS/DeepTutor/pull/1375) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1376 | PR | [feat(reading): reanchor selectors across revisions](https://github.com/HKUDS/DeepTutor/pull/1376) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1377 | PR | [feat(resource-providers): add provider foundations and web controls (#961)](https://github.com/HKUDS/DeepTutor/pull/1377) | closed | 2026-09-10 | 2026-10-04 | 1 |
| 1378 | Issue | [Fold immersive_watching into Immersive Reading as a media source_kind](https://github.com/HKUDS/DeepTutor/issues/1378) | closed | 2026-09-10 | 2026-10-07 | 3 |
| 1379 | PR | [feat(reading): add provider-aware media ingestion](https://github.com/HKUDS/DeepTutor/pull/1379) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1380 | PR | [feat(reading): add transcript-aware media stage (#1378)](https://github.com/HKUDS/DeepTutor/pull/1380) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1381 | PR | [feat(settings): export value-free profiles](https://github.com/HKUDS/DeepTutor/pull/1381) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1382 | PR | [fix(path-service): restore workspace chat output downloads](https://github.com/HKUDS/DeepTutor/pull/1382) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1383 | PR | [feat(settings): add reviewable named presets](https://github.com/HKUDS/DeepTutor/pull/1383) | closed | 2026-09-10 | 2026-09-23 | 0 |
| 1384 | PR | [feat(reading): converge immersive watching into reading (#1378)](https://github.com/HKUDS/DeepTutor/pull/1384) | open | 2026-09-10 | 2026-09-11 | 0 |
| 1385 | PR | [feat(web-source): add durable sync scheduling](https://github.com/HKUDS/DeepTutor/pull/1385) | closed | 2026-09-11 | 2026-09-23 | 0 |
| 1386 | PR | [fix(knowledge): add local OCR fallback for scanned PDFs (#431)](https://github.com/HKUDS/DeepTutor/pull/1386) | closed | 2026-09-11 | 2026-09-23 | 0 |
| 1387 | PR | [feat(audio-overview): add KB audio overview pipeline](https://github.com/HKUDS/DeepTutor/pull/1387) | closed | 2026-09-11 | 2026-09-23 | 0 |
| 1388 | PR | [fix(agents): ignore leading think blocks when extracting JSON](https://github.com/HKUDS/DeepTutor/pull/1388) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1389 | Issue | [[Feature Request]: Recycle Bin](https://github.com/HKUDS/DeepTutor/issues/1389) | closed | 2026-09-11 | 2026-10-07 | 1 |
| 1390 | Issue | [[Feature Request]: Resend for failed chat requests](https://github.com/HKUDS/DeepTutor/issues/1390) | closed | 2026-09-11 | 2026-10-07 | 1 |
| 1391 | PR | [feat(payment): RIC-546/549/550 commercial payment layer (fork → upstream)](https://github.com/HKUDS/DeepTutor/pull/1391) | closed | 2026-09-11 | 2026-09-22 | 0 |
| 1392 | Issue | [[Bug]:New Mastery Path stays empty — the outline is written to a second, panel-invisible path](https://github.com/HKUDS/DeepTutor/issues/1392) | closed | 2026-09-11 | 2026-09-20 | 1 |
| 1393 | Issue | [bug(web): explicit retryable false is overridden by HTTP status](https://github.com/HKUDS/DeepTutor/issues/1393) | closed | 2026-09-11 | 2026-09-23 | 1 |
| 1394 | PR | [feat(chat): add resend for failed turns](https://github.com/HKUDS/DeepTutor/pull/1394) | closed | 2026-09-11 | 2026-09-23 | 0 |
| 1395 | PR | [fix(web): explicit retryable false takes precedence over HTTP status](https://github.com/HKUDS/DeepTutor/pull/1395) | closed | 2026-09-11 | 2026-10-04 | 1 |
| 1396 | PR | [fix(web): honor explicit retryable flags](https://github.com/HKUDS/DeepTutor/pull/1396) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1397 | PR | [feat(knowledge): add knowledge_frontier discovery tool](https://github.com/HKUDS/DeepTutor/pull/1397) | closed | 2026-09-11 | 2026-10-04 | 1 |
| 1398 | PR | [feat(sessions): add recycle bin for deleted chats](https://github.com/HKUDS/DeepTutor/pull/1398) | closed | 2026-09-11 | 2026-09-14 | 1 |
| 1399 | PR | [feat(textbook): rebuild chapters from running headers embedded mid-text](https://github.com/HKUDS/DeepTutor/pull/1399) | closed | 2026-09-11 | 2026-09-24 | 0 |
| 1400 | Issue | [[Bug]: Reasoning-only rounds with zero output collapse into the empty-response fallback (reproduced in both chat and deep_solve): DeepSeek reasoning model exhausts its per-round budget, and explore_context is rejected with HTTP 400](https://github.com/HKUDS/DeepTutor/issues/1400) | closed | 2026-09-11 | 2026-09-23 | 3 |
| 1401 | PR | [fix(config): bump probe budget for reasoning models](https://github.com/HKUDS/DeepTutor/pull/1401) | closed | 2026-09-11 | 2026-09-14 | 1 |
| 1402 | PR | [fix(agent-loop): recover bounded reasoning-only finishes (#1400)](https://github.com/HKUDS/DeepTutor/pull/1402) | closed | 2026-09-11 | 2026-09-14 | 0 |
| 1403 | PR | [fix(mastery): bind draft before sending opening turn](https://github.com/HKUDS/DeepTutor/pull/1403) | open | 2026-09-11 | 2026-09-20 | 1 |
| 1404 | PR | [fix(explore-context): keep reasoning on replayed rounds for thinking providers (#1400)](https://github.com/HKUDS/DeepTutor/pull/1404) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1405 | Issue | [[Feature Request]: Import ChatGPT conversation exports](https://github.com/HKUDS/DeepTutor/issues/1405) | closed | 2026-09-11 | 2026-10-07 | 2 |
| 1406 | Issue | [[Feature Request]: Search across full conversation history](https://github.com/HKUDS/DeepTutor/issues/1406) | closed | 2026-09-11 | 2026-09-23 | 2 |
| 1407 | Issue | [feat(learning): a read-only journal overview panel for mission and handoff (Part of #740)](https://github.com/HKUDS/DeepTutor/issues/1407) | closed | 2026-09-11 | 2026-10-07 | 2 |
| 1408 | PR | [feat(imports): add ChatGPT conversation export support](https://github.com/HKUDS/DeepTutor/pull/1408) | closed | 2026-09-11 | 2026-09-23 | 0 |
| 1409 | Issue | [[Bug]: v1.6.7 Duplicate options appear in multiple-choice questions on Mastery Path](https://github.com/HKUDS/DeepTutor/issues/1409) | closed | 2026-09-11 | 2026-09-23 | 5 |
| 1410 | Issue | [[Bug]: v1.6.7 Chat history lost inside session](https://github.com/HKUDS/DeepTutor/issues/1410) | closed | 2026-09-11 | 2026-10-07 | 6 |
| 1411 | Issue | [[Bug]: v1.6.7 Mastery Path returns many responses without questions/cards](https://github.com/HKUDS/DeepTutor/issues/1411) | closed | 2026-09-11 | 2026-09-21 | 3 |
| 1412 | Issue | [[Bug]: v1.6.7 Mastery Path repeated new sessions and incorrect topic binding](https://github.com/HKUDS/DeepTutor/issues/1412) | closed | 2026-09-11 | 2026-09-23 | 3 |
| 1413 | PR | [fix(runtime): cancel the capability when a turn's consumer stops](https://github.com/HKUDS/DeepTutor/pull/1413) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1414 | PR | [fix(graphrag): recover stale pandas Arrow extension registrations](https://github.com/HKUDS/DeepTutor/pull/1414) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1415 | PR | [feat(chat): search full conversation history](https://github.com/HKUDS/DeepTutor/pull/1415) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1416 | PR | [fix(mastery): refuse a new-session handoff for the topic a turn is tutoring (#1412)](https://github.com/HKUDS/DeepTutor/pull/1416) | open | 2026-09-11 | 2026-09-11 | 0 |
| 1417 | PR | [fix(mastery): drop duplicate ask_user options (#1409)](https://github.com/HKUDS/DeepTutor/pull/1417) | closed | 2026-09-11 | 2026-09-23 | 0 |
| 1418 | PR | [fix(ask-user): drop an option whose visible text duplicates another (#1409)](https://github.com/HKUDS/DeepTutor/pull/1418) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1419 | Issue | [feat(reading): add age-aware action button presentation](https://github.com/HKUDS/DeepTutor/issues/1419) | closed | 2026-09-11 | 2026-10-07 | 3 |
| 1420 | PR | [feat(reading): add age-aware action buttons](https://github.com/HKUDS/DeepTutor/pull/1420) | closed | 2026-09-11 | 2026-10-04 | 1 |
| 1421 | Issue | [[Bug]:v1.6.6第一次使用进入时发的第一句话会卡循环很久，重启后恢复正常](https://github.com/HKUDS/DeepTutor/issues/1421) | closed | 2026-09-11 | 2026-10-07 | 7 |
| 1422 | Issue | [test(api): isolate partners router authentication state](https://github.com/HKUDS/DeepTutor/issues/1422) | closed | 2026-09-11 | 2026-09-23 | 2 |
| 1423 | PR | [test(api): isolate partners router auth state (#1422)](https://github.com/HKUDS/DeepTutor/pull/1423) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1424 | Issue | [fix(web): package standalone runtime assets](https://github.com/HKUDS/DeepTutor/issues/1424) | closed | 2026-09-11 | 2026-10-04 | 2 |
| 1425 | PR | [fix(web): package standalone runtime assets (#1424)](https://github.com/HKUDS/DeepTutor/pull/1425) | closed | 2026-09-11 | 2026-10-04 | 1 |
| 1426 | Issue | [fix(api): preserve actual proxy peer identity](https://github.com/HKUDS/DeepTutor/issues/1426) | closed | 2026-09-11 | 2026-09-23 | 1 |
| 1427 | PR | [fix(api): preserve actual proxy peer identity (#1426)](https://github.com/HKUDS/DeepTutor/pull/1427) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1428 | Issue | [Vercel deploy fails ENOENT routes-manifest-deterministic.json with forced --webpack build](https://github.com/HKUDS/DeepTutor/issues/1428) | closed | 2026-09-11 | 2026-09-23 | 1 |
| 1429 | Issue | [fix(knowledge): respect robots crawl policy](https://github.com/HKUDS/DeepTutor/issues/1429) | closed | 2026-09-11 | 2026-09-20 | 0 |
| 1430 | PR | [fix(knowledge): respect robots crawl policy (#1429)](https://github.com/HKUDS/DeepTutor/pull/1430) | closed | 2026-09-11 | 2026-09-29 | 1 |
| 1431 | PR | [fix(web): skip forced --webpack on Vercel to fix ENOENT deploy failure](https://github.com/HKUDS/DeepTutor/pull/1431) | closed | 2026-09-11 | 2026-09-14 | 0 |
| 1432 | Issue | [test(app): stabilize multiworker reply subscription](https://github.com/HKUDS/DeepTutor/issues/1432) | closed | 2026-09-11 | 2026-09-23 | 1 |
| 1433 | PR | [test(app): stabilize multiworker reply subscription (#1432)](https://github.com/HKUDS/DeepTutor/pull/1433) | closed | 2026-09-11 | 2026-09-13 | 0 |
| 1434 | Issue | [[Feature Request]: Read-only, replayable session lifecycle feed for companion integrations](https://github.com/HKUDS/DeepTutor/issues/1434) | closed | 2026-09-12 | 2026-09-12 | 2 |
| 1435 | Issue | [[Bug] v1.6.7 精通之路的首段等待无计时，且 RAG 工具事件协程未 await](https://github.com/HKUDS/DeepTutor/issues/1435) | closed | 2026-09-12 | 2026-09-19 | 6 |
| 1436 | PR | [fix(settings): skip the client reset when an apply changes nothing (#1421)](https://github.com/HKUDS/DeepTutor/pull/1436) | closed | 2026-09-12 | 2026-09-13 | 0 |
| 1437 | Issue | [[Feature Request] Add a persistent reusable file library across conversations](https://github.com/HKUDS/DeepTutor/issues/1437) | closed | 2026-09-12 | 2026-09-19 | 0 |
| 1438 | Issue | [[Bug] Single attachments cannot be reliably referenced from the second turn onward](https://github.com/HKUDS/DeepTutor/issues/1438) | closed | 2026-09-12 | 2026-09-19 | 3 |
| 1439 | Issue | [[Bug] Safari briefly shows “material unavailable” while Immersive Reading is loading](https://github.com/HKUDS/DeepTutor/issues/1439) | closed | 2026-09-12 | 2026-09-19 | 1 |
| 1440 | Issue | [[Bug] Deep book URLs briefly render the empty parent-level list while loading](https://github.com/HKUDS/DeepTutor/issues/1440) | closed | 2026-09-12 | 2026-09-19 | 2 |
| 1441 | PR | [fix(web): keep deep book routes in loading state](https://github.com/HKUDS/DeepTutor/pull/1441) | closed | 2026-09-12 | 2026-09-23 | 0 |
| 1442 | PR | [fix(reading): keep material loading during hydration](https://github.com/HKUDS/DeepTutor/pull/1442) | closed | 2026-09-12 | 2026-09-13 | 0 |
| 1443 | PR | [fix(turns): keep prior conversation images readable on later turns (#1438)](https://github.com/HKUDS/DeepTutor/pull/1443) | closed | 2026-09-12 | 2026-09-13 | 0 |
| 1444 | PR | [feat(sessions): soft-delete recycle bin with restore and permanent delete](https://github.com/HKUDS/DeepTutor/pull/1444) | closed | 2026-09-13 | 2026-09-14 | 2 |
| 1445 | PR | [feat(search): full conversation search with LIKE escaping](https://github.com/HKUDS/DeepTutor/pull/1445) | closed | 2026-09-13 | 2026-09-14 | 1 |
| 1446 | PR | [feat: Persistent File Library with API router (issue #1437)](https://github.com/HKUDS/DeepTutor/pull/1446) | closed | 2026-09-13 | 2026-09-13 | 1 |
| 1447 | Issue | [[Feature & Bugfix] Reading Workspace Enhancements: Real-time TOC Tracking, EPUB Formatting Toolbar & Themes, Configurable Single/Two-Page Spread Layout, EPUB Archive Normalization ("Could not load this section"), and Navigation Prefetch Optimization](https://github.com/HKUDS/DeepTutor/issues/1447) | closed | 2026-09-13 | 2026-10-07 | 4 |
| 1448 | Issue | [[Bug] Immersive Reading extensions fail with HTTP 503 under uvloop: `TypeError: coroutines cannot be used with run_in_executor()`](https://github.com/HKUDS/DeepTutor/issues/1448) | closed | 2026-09-13 | 2026-09-20 | 2 |
| 1449 | PR | [fix(logging): schedule log coroutines from worker threads; make backend readiness budget configurable (#1435)](https://github.com/HKUDS/DeepTutor/pull/1449) | closed | 2026-09-13 | 2026-09-13 | 1 |
| 1450 | PR | [fix(reading): run async extension handlers on the loop, not in an executor (#1448)](https://github.com/HKUDS/DeepTutor/pull/1450) | open | 2026-09-14 | 2026-09-14 | 0 |
| 1451 | Issue | [[Bug] HTTP-date Retry-After crashes OpenAI-compatible embedding retries](https://github.com/HKUDS/DeepTutor/issues/1451) | closed | 2026-09-14 | 2026-09-20 | 1 |
| 1452 | PR | [fix(embedding): parse HTTP-date Retry-After values](https://github.com/HKUDS/DeepTutor/pull/1452) | closed | 2026-09-14 | 2026-09-23 | 0 |
| 1453 | PR | [Faithful-book pipeline: anchored question generation, KP bridging, overview-anchor chapter rebuild](https://github.com/HKUDS/DeepTutor/pull/1453) | closed | 2026-09-14 | 2026-09-14 | 1 |
| 1454 | Issue | [[Bug]:DeepTutor 的 Codex OAuth 凭据当时无效或未完成授权；每次发起对话都会重新请求 chatgpt.com/backend-api](https://github.com/HKUDS/DeepTutor/issues/1454) | closed | 2026-09-14 | 2026-10-07 | 3 |
| 1455 | PR | [perf(web): disable sidebar viewport prefetch (#1447)](https://github.com/HKUDS/DeepTutor/pull/1455) | closed | 2026-09-14 | 2026-09-23 | 0 |
| 1456 | PR | [fix(marginnote4): close the store's SQLite connections](https://github.com/HKUDS/DeepTutor/pull/1456) | closed | 2026-09-14 | 2026-09-23 | 0 |
| 1457 | PR | [Faithful-book material pipeline: anchored question generation, KP bridging, multi-tier chapter rebuild](https://github.com/HKUDS/DeepTutor/pull/1457) | closed | 2026-09-14 | 2026-09-27 | 2 |
| 1458 | Issue | [[Bug]: [Bug] Knowledge base not initialized (llamaindex) due to permission/user conflicts on Unraid Docker](https://github.com/HKUDS/DeepTutor/issues/1458) | closed | 2026-09-14 | 2026-09-20 | 0 |
| 1459 | PR | [fix(docker): remap PUID/PGID for Unraid bind mounts (#1458)](https://github.com/HKUDS/DeepTutor/pull/1459) | closed | 2026-09-14 | 2026-09-23 | 0 |
| 1460 | PR | [fix(visualize): repair GeoGebra Text coordinates](https://github.com/HKUDS/DeepTutor/pull/1460) | closed | 2026-09-14 | 2026-09-23 | 0 |
| 1461 | Issue | [Telegram replies always land in General topic in forum groups (topic routing is inbound-only)](https://github.com/HKUDS/DeepTutor/issues/1461) | closed | 2026-09-14 | 2026-09-20 | 1 |
| 1462 | PR | [fix(partners): route outbound Telegram messages to the inbound topic thread](https://github.com/HKUDS/DeepTutor/pull/1462) | closed | 2026-09-14 | 2026-09-23 | 0 |
| 1463 | PR | [50/50 RevShare Integration: DeepTutor & AIML API](https://github.com/HKUDS/DeepTutor/pull/1463) | open | 2026-09-14 | 2026-09-28 | 0 |
| 1464 | PR | [fix(reading): keep mobile toolbar actions reachable](https://github.com/HKUDS/DeepTutor/pull/1464) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1465 | PR | [fix(mastery): time turns from submission](https://github.com/HKUDS/DeepTutor/pull/1465) | closed | 2026-09-15 | 2026-10-04 | 1 |
| 1466 | PR | [fix(codex): fail fast on a credential that no longer refreshes instead of re-prompting every turn (#1454)](https://github.com/HKUDS/DeepTutor/pull/1466) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1467 | Issue | [[Feature Request]: Secure private-network to public-tunnel session handoff](https://github.com/HKUDS/DeepTutor/issues/1467) | closed | 2026-09-15 | 2026-10-07 | 1 |
| 1469 | PR | [fix(web): 加载带 polyfill 的 PDF.js 构建，让旧版引擎也能渲染](https://github.com/HKUDS/DeepTutor/pull/1469) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1470 | PR | [chore(deps): 让 qrcode 随核心依赖安装](https://github.com/HKUDS/DeepTutor/pull/1470) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1471 | Issue | [[Feature Request]: Adaptive long-term learning engine for Mastery Path — retention-based spaced repetition, unified learning evidence, and study prioritization](https://github.com/HKUDS/DeepTutor/issues/1471) | closed | 2026-09-15 | 2026-10-12 | 5 |
| 1472 | PR | [fix(reading): normalize packaged EPUB archives (#1447)](https://github.com/HKUDS/DeepTutor/pull/1472) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1473 | Issue | [[Bug]: Mastery accepts card-delivery claims without posting a question card](https://github.com/HKUDS/DeepTutor/issues/1473) | closed | 2026-09-15 | 2026-09-17 | 0 |
| 1474 | PR | [fix: enforce mastery quiz delivery before successful completion](https://github.com/HKUDS/DeepTutor/pull/1474) | open | 2026-09-15 | 2026-09-17 | 0 |
| 1475 | PR | [feat: complete adaptive SRS persistence and review UI](https://github.com/HKUDS/DeepTutor/pull/1475) | closed | 2026-09-15 | 2026-09-19 | 1 |
| 1476 | Issue | [feat(learning): persist mastery prerequisites and topic-source links](https://github.com/HKUDS/DeepTutor/issues/1476) | closed | 2026-09-15 | 2026-10-07 | 2 |
| 1477 | PR | [feat(learning): persist mastery prerequisites and topic-source links (#1476)](https://github.com/HKUDS/DeepTutor/pull/1477) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1478 | Issue | [LlamaIndex re-index can leak stale embedding progress after a timeout](https://github.com/HKUDS/DeepTutor/issues/1478) | closed | 2026-09-15 | 2026-10-12 | 5 |
| 1479 | PR | [fix(video-learning): decode caption HTML entities](https://github.com/HKUDS/DeepTutor/pull/1479) | closed | 2026-09-15 | 2026-09-23 | 0 |
| 1480 | PR | [fix(rag): stop a stalled LlamaIndex worker leaking progress into the next job (#1478)](https://github.com/HKUDS/DeepTutor/pull/1480) | closed | 2026-09-15 | 2026-09-23 | 2 |
| 1481 | Issue | [[Bug]: Creating an empty knowledge base and then uploading documents always fails with "Knowledge base not initialized (llamaindex)"](https://github.com/HKUDS/DeepTutor/issues/1481) | closed | 2026-09-16 | 2026-10-07 | 2 |
| 1482 | PR | [feat(auth): add secure public session handoff (#1467)](https://github.com/HKUDS/DeepTutor/pull/1482) | closed | 2026-09-16 | 2026-09-23 | 0 |
| 1483 | PR | [docs: sync AGENTS.md with the current turn runtime](https://github.com/HKUDS/DeepTutor/pull/1483) | closed | 2026-09-16 | 2026-09-23 | 0 |
| 1484 | Issue | [[Bug]:Retrying/Regenerating a turn with attachments permanently hangs UI on "Thinking..." due to Pydantic ValidationError in TurnRequest](https://github.com/HKUDS/DeepTutor/issues/1484) | closed | 2026-09-16 | 2026-09-21 | 3 |
| 1485 | PR | [fix(notebook): prevent path traversal via read/write path asymmetry](https://github.com/HKUDS/DeepTutor/pull/1485) | closed | 2026-09-16 | 2026-09-23 | 0 |
| 1486 | PR | [feat: add native Volcengine (Doubao Seed-TTS) TTS provider](https://github.com/HKUDS/DeepTutor/pull/1486) | closed | 2026-09-16 | 2026-09-17 | 0 |
| 1487 | PR | [fix(turns): regenerate a turn with attachments without breaking TurnRequest validation (#1484)](https://github.com/HKUDS/DeepTutor/pull/1487) | closed | 2026-09-16 | 2026-10-05 | 1 |
| 1488 | PR | [fix(knowledge): bootstrap empty KBs on first upload](https://github.com/HKUDS/DeepTutor/pull/1488) | closed | 2026-09-16 | 2026-09-23 | 0 |
| 1489 | Issue | [fix(github-source): refresh state after unchanged syncs](https://github.com/HKUDS/DeepTutor/issues/1489) | closed | 2026-09-16 | 2026-09-23 | 1 |
| 1490 | PR | [fix(github-source): refresh unchanged sync state](https://github.com/HKUDS/DeepTutor/pull/1490) | closed | 2026-09-16 | 2026-10-07 | 0 |
| 1491 | Issue | [[Feature Request]需要一个可以一键安装的网址或者方式](https://github.com/HKUDS/DeepTutor/issues/1491) | closed | 2026-09-16 | 2026-10-07 | 1 |
| 1492 | PR | [fix(usage): prefer exact model pricing matches](https://github.com/HKUDS/DeepTutor/pull/1492) | closed | 2026-09-16 | 2026-09-23 | 0 |
| 1494 | PR | [feat(rag): expose LightRAG llm_timeout so extraction LLM timeouts are tunable](https://github.com/HKUDS/DeepTutor/pull/1494) | closed | 2026-09-17 | 2026-09-23 | 0 |
| 1495 | PR | [fix(llm): treat grok as a large-context family](https://github.com/HKUDS/DeepTutor/pull/1495) | closed | 2026-09-17 | 2026-09-23 | 2 |
| 1496 | PR | [fix(runtime): bypass system proxy for loopback health checks](https://github.com/HKUDS/DeepTutor/pull/1496) | closed | 2026-09-17 | 2026-09-23 | 0 |
| 1497 | Issue | [[Bug]: Mastery accepts card-delivery claims without posting a question card](https://github.com/HKUDS/DeepTutor/issues/1497) | closed | 2026-09-17 | 2026-09-26 | 2 |
| 1498 | Issue | [[Bug]:   Mastery accepts card-delivery claims without posting a question card](https://github.com/HKUDS/DeepTutor/issues/1498) | closed | 2026-09-17 | 2026-09-26 | 3 |
| 1499 | PR | [fix(llm): try every API key after rate limits](https://github.com/HKUDS/DeepTutor/pull/1499) | closed | 2026-09-17 | 2026-09-23 | 0 |
| 1500 | Issue | [[Bug]:[问题反馈] deeptutor 1.6.8：Tencent IMA 知识库添加到伙伴后，检索未获得可核对内容与来源](https://github.com/HKUDS/DeepTutor/issues/1500) | closed | 2026-09-17 | 2026-10-07 | 5 |
| 1501 | Issue | [[Bug]: [Windows] Detached launcher worker spawns console tools and children without CREATE_NO_WINDOW — empty console windows flash on screen, and closing one kills the whole app](https://github.com/HKUDS/DeepTutor/issues/1501) | closed | 2026-09-17 | 2026-10-07 | 4 |
| 1502 | Issue | [[Bug]: Global parsing-engine selection hard-fails per file type — .txt/.md cannot coexist with MinerU-engine PDFs in one KB](https://github.com/HKUDS/DeepTutor/issues/1502) | closed | 2026-09-17 | 2026-10-07 | 6 |
| 1503 | PR | [feat(reading): figures from PDFs, captions at ingest, and drawn-page renders](https://github.com/HKUDS/DeepTutor/pull/1503) | closed | 2026-09-17 | 2026-09-23 | 0 |
| 1504 | PR | [feat(learning): persist cross-surface Focus-Check in Question Bank](https://github.com/HKUDS/DeepTutor/pull/1504) | closed | 2026-09-17 | 2026-09-19 | 1 |
| 1505 | PR | [fix(parsing): fall back to a text-capable engine when the global default can't take a file (#1502)](https://github.com/HKUDS/DeepTutor/pull/1505) | closed | 2026-09-17 | 2026-10-05 | 1 |
| 1506 | PR | [fix: add missing task model branch to config test runner](https://github.com/HKUDS/DeepTutor/pull/1506) | closed | 2026-09-17 | 2026-09-26 | 0 |
| 1507 | Issue | [[Feature Request]: ZIM/Kiwix archives as a knowledge source (Book, Mastery Path, Immersive Reading, Knowledge Center)](https://github.com/HKUDS/DeepTutor/issues/1507) | closed | 2026-09-17 | 2026-09-27 | 1 |
| 1508 | Issue | [[Bug]:模型返回内容含题目时，题目有时被截断，未出现在这次对话中。](https://github.com/HKUDS/DeepTutor/issues/1508) | closed | 2026-09-17 | 2026-09-26 | 2 |
| 1510 | PR | [fix(github-source): refresh sync state on unchanged SHA](https://github.com/HKUDS/DeepTutor/pull/1510) | open | 2026-09-17 | 2026-09-17 | 0 |
| 1511 | Issue | [[Feature Request]: Custom reply language](https://github.com/HKUDS/DeepTutor/issues/1511) | closed | 2026-09-18 | 2026-09-27 | 4 |
| 1512 | Issue | [[Feature Request]:伙伴对话停止浏览器隔离；群组对话可下载](https://github.com/HKUDS/DeepTutor/issues/1512) | closed | 2026-09-18 | 2026-09-26 | 2 |
| 1513 | PR | [fix(rag): report empty retrieval results (#1500)](https://github.com/HKUDS/DeepTutor/pull/1513) | closed | 2026-09-18 | 2026-09-23 | 0 |
| 1514 | Issue | [[Bug]: deep_research report turn fails after 3 attempts — shared reasoning token budget + 64-char label probe discards recoverable label slips](https://github.com/HKUDS/DeepTutor/issues/1514) | closed | 2026-09-19 | 2026-09-27 | 3 |
| 1515 | Issue | [[Bug]: Tooltip stays pinned on screen after clicking a header/message button — pointer-granted focus keeps group-focus-within matching](https://github.com/HKUDS/DeepTutor/issues/1515) | closed | 2026-09-19 | 2026-09-26 | 2 |
| 1516 | Issue | [[Bug]:`BwrapBackend` fails on modern Linux (Ubuntu 24.04+) with `bwrap: loopback: Failed RTM_NEWADDR: Operation not permitted`, causing Agent/Partner file generation and IM delivery to fail silently](https://github.com/HKUDS/DeepTutor/issues/1516) | closed | 2026-09-19 | 2026-09-26 | 2 |
| 1517 | Issue | [[Feature Request]: Feishu partner channel — reply threading, working-reaction cleanup, and interactive /model picker card](https://github.com/HKUDS/DeepTutor/issues/1517) | closed | 2026-09-19 | 2026-09-26 | 3 |
| 1518 | PR | [feat(learning): rank reviews from repeated misconceptions and explicit prerequisites](https://github.com/HKUDS/DeepTutor/pull/1518) | closed | 2026-09-19 | 2026-10-23 | 1 |
| 1519 | Issue | [[Feature Request]: Decouple Question Notebook provenance from conversation sessions](https://github.com/HKUDS/DeepTutor/issues/1519) | closed | 2026-09-19 | 2026-09-26 | 2 |
| 1521 | PR | [fix(chat): route PDF attachments through configured parser](https://github.com/HKUDS/DeepTutor/pull/1521) | closed | 2026-09-19 | 2026-09-25 | 1 |
| 1522 | Issue | [Chat PDF attachments bypass the configured document parser for scanned PDFs](https://github.com/HKUDS/DeepTutor/issues/1522) | closed | 2026-09-19 | 2026-09-26 | 2 |
| 1523 | Issue | [Feature request: show chat attachment processing stages in the upload composer](https://github.com/HKUDS/DeepTutor/issues/1523) | closed | 2026-09-19 | 2026-09-27 | 3 |
| 1524 | PR | [fix(books): preserve deep-route loading context](https://github.com/HKUDS/DeepTutor/pull/1524) | closed | 2026-09-19 | 2026-09-19 | 0 |
| 1526 | Issue | [[Bug]: Tooltip layer fragmented across 5 implementations — screen-reader-invisible hints, clipped/overflowing labels, inverted disabled semantics, no touch path](https://github.com/HKUDS/DeepTutor/issues/1526) | closed | 2026-09-19 | 2026-09-27 | 3 |
| 1527 | Issue | [[Bug][High Severity]: Mastery Path corrupts learning state across outline replacement and invalid assessments](https://github.com/HKUDS/DeepTutor/issues/1527) | closed | 2026-09-19 | 2026-10-12 | 3 |
| 1529 | PR | [Add Unifically LLM provider](https://github.com/HKUDS/DeepTutor/pull/1529) | closed | 2026-09-20 | 2026-09-23 | 0 |
| 1530 | PR | [fix(mastery): keep learning evidence bound to objective identity](https://github.com/HKUDS/DeepTutor/pull/1530) | open | 2026-09-20 | 2026-09-20 | 1 |
| 1531 | PR | [feat(i18n): add German as a full interface language](https://github.com/HKUDS/DeepTutor/pull/1531) | closed | 2026-09-20 | 2026-09-26 | 0 |
| 1532 | PR | [feat(voice): verbalize LaTeX in TTS with a Math speak setting](https://github.com/HKUDS/DeepTutor/pull/1532) | closed | 2026-09-20 | 2026-09-23 | 2 |
| 1533 | PR | [merge  v1.6.9](https://github.com/HKUDS/DeepTutor/pull/1533) | closed | 2026-09-21 | 2026-09-21 | 0 |
| 1534 | Issue | [[Bug]: Mastery Path lacks the Skills picker and workspace-bound persona selector shows only Default (v1.6.9)](https://github.com/HKUDS/DeepTutor/issues/1534) | closed | 2026-09-21 | 2026-09-26 | 2 |
| 1535 | PR | [fix(mastery): restore Skills picker and workspace persona presets](https://github.com/HKUDS/DeepTutor/pull/1535) | closed | 2026-09-21 | 2026-09-23 | 0 |
| 1536 | Issue | [[Bug] v1.6.9 update-check toggle is masked by launcher-generated process override](https://github.com/HKUDS/DeepTutor/issues/1536) | closed | 2026-09-21 | 2026-09-26 | 2 |
| 1537 | PR | [fix(question): retry a starved quiz repair, and count it honestly (#1508)](https://github.com/HKUDS/DeepTutor/pull/1537) | closed | 2026-09-21 | 2026-09-23 | 0 |
| 1538 | PR | [fix(web): offer the skills picker to mastery conversations (#1534)](https://github.com/HKUDS/DeepTutor/pull/1538) | closed | 2026-09-21 | 2026-10-05 | 1 |
| 1539 | PR | [fix(session): name the reply language in the compaction instruction (#1511)](https://github.com/HKUDS/DeepTutor/pull/1539) | closed | 2026-09-21 | 2026-09-23 | 0 |
| 1541 | Issue | [[Bug]: Adaptive SRS updates are not timing-aware or replay-equivalent](https://github.com/HKUDS/DeepTutor/issues/1541) | closed | 2026-09-21 | 2026-10-12 | 2 |
| 1542 | Issue | [[Bug]: Cross-surface assessments do not produce durable linked learning evidence](https://github.com/HKUDS/DeepTutor/issues/1542) | closed | 2026-09-21 | 2026-10-12 | 2 |
| 1543 | Issue | [[Feature Request]: Source-grounded visual learning pipeline for textbook figures, diagrams, and interactive exercises](https://github.com/HKUDS/DeepTutor/issues/1543) | closed | 2026-09-21 | 2026-10-12 | 1 |
| 1545 | Issue | [Math animator: GeneratedCodeOutputError hides the real parse error and never logs the raw response, making failures undiagnosable](https://github.com/HKUDS/DeepTutor/issues/1545) | closed | 2026-09-22 | 2026-09-26 | 3 |
| 1546 | Issue | [Visualize: hardcoded max_tokens=16000 is consumed by reasoning models, so submit_visualization gets truncated (silent blank canvas)](https://github.com/HKUDS/DeepTutor/issues/1546) | closed | 2026-09-22 | 2026-09-26 | 3 |
| 1547 | Issue | [Math animator: reasoning model spends the whole max_tokens budget on <think>, code_generation fails deterministically (9/9 attempts)](https://github.com/HKUDS/DeepTutor/issues/1547) | closed | 2026-09-22 | 2026-09-26 | 2 |
| 1548 | Issue | [[Bug]: Personalized Learning crashes: motion component inside strict LazyMotion](https://github.com/HKUDS/DeepTutor/issues/1548) | closed | 2026-09-22 | 2026-09-26 | 1 |
| 1549 | Issue | [[Bug]: Personalized Learning crashes: motion component inside strict LazyMotion](https://github.com/HKUDS/DeepTutor/issues/1549) | closed | 2026-09-22 | 2026-09-26 | 4 |
| 1551 | PR | [fix(learning): keep Personalized Learning inside strict LazyMotion](https://github.com/HKUDS/DeepTutor/pull/1551) | open | 2026-09-22 | 2026-09-22 | 0 |
| 1552 | PR | [fix(visualize): point the no-payload diagnosis at the real remedy (#1546)](https://github.com/HKUDS/DeepTutor/pull/1552) | closed | 2026-09-22 | 2026-09-26 | 1 |
| 1553 | PR | [fix(math-animator): raise the output budget when reasoning is truncated](https://github.com/HKUDS/DeepTutor/pull/1553) | open | 2026-09-22 | 2026-09-22 | 0 |
| 1554 | Issue | [[Bug]: Browser microphone STT fails on Windows PyPI install because FFmpeg is an undocumented runtime dependency](https://github.com/HKUDS/DeepTutor/issues/1554) | closed | 2026-09-22 | 2026-09-26 | 2 |
| 1555 | Issue | [[Bug] In-app update stops systemd deployment without completing or restarting](https://github.com/HKUDS/DeepTutor/issues/1555) | closed | 2026-09-22 | 2026-09-27 | 3 |
| 1556 | PR | [refactor(auth): converge all role whitelists on a single normalize_role, add first set_role tests](https://github.com/HKUDS/DeepTutor/pull/1556) | closed | 2026-09-22 | 2026-09-24 | 1 |
| 1557 | PR | [fix(voice): stop speaking asterisks and drop the play-aloud auto-play prompt](https://github.com/HKUDS/DeepTutor/pull/1557) | closed | 2026-09-23 | 2026-10-04 | 0 |
| 1558 | PR | [feat(partners): export group conversations as Markdown](https://github.com/HKUDS/DeepTutor/pull/1558) | closed | 2026-09-23 | 2026-10-04 | 0 |
| 1563 | PR | [fix(voice): use realtime DashScope STT model ids](https://github.com/HKUDS/DeepTutor/pull/1563) | closed | 2026-09-23 | 2026-09-26 | 1 |
| 1564 | PR | [fix(media): use the real DashScope image/video submit endpoints](https://github.com/HKUDS/DeepTutor/pull/1564) | closed | 2026-09-23 | 2026-09-26 | 0 |
| 1565 | PR | [feat(partners): roam web sessions across browsers](https://github.com/HKUDS/DeepTutor/pull/1565) | open | 2026-09-23 | 2026-09-29 | 0 |
| 1566 | Issue | [[Bug]: 精通之路（Mastery Path）复习条目较多时“精通大纲”模块高度过矮，几乎不可用](https://github.com/HKUDS/DeepTutor/issues/1566) | closed | 2026-09-23 | 2026-09-26 | 1 |
| 1567 | PR | [feat(auth): admit "teacher" and "student" role values in the single role whitelist](https://github.com/HKUDS/DeepTutor/pull/1567) | closed | 2026-09-23 | 2026-09-27 | 0 |
| 1568 | Issue | [[Bug]: Knowledge base (LllamaIndex) initialization fails with "Embedding API key not set" and "Catalog" settings page is missing](https://github.com/HKUDS/DeepTutor/issues/1568) | closed | 2026-09-23 | 2026-09-27 | 3 |
| 1569 | PR | [feat(parsing): auto-slice oversized PDFs for MinerU cloud parsing](https://github.com/HKUDS/DeepTutor/pull/1569) | closed | 2026-09-23 | 2026-10-04 | 3 |
| 1570 | Issue | [[Bug]: Mastery turns remain stuck in “推理中” after worker_lost](https://github.com/HKUDS/DeepTutor/issues/1570) | closed | 2026-09-23 | 2026-09-27 | 2 |
| 1571 | PR | [feat: add Cheaper Inference as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/1571) | closed | 2026-09-23 | 2026-09-26 | 0 |
| 1572 | PR | [feat(auth): admit "teacher" and "student" role values in the single role whitelist](https://github.com/HKUDS/DeepTutor/pull/1572) | open | 2026-09-23 | 2026-10-03 | 0 |
| 1573 | PR | [fix: refresh managed Codex catalog for GPT-6 Sol and Luna](https://github.com/HKUDS/DeepTutor/pull/1573) | closed | 2026-09-23 | 2026-09-23 | 0 |
| 1574 | PR | [fix: use headings for uploaded Markdown outlines](https://github.com/HKUDS/DeepTutor/pull/1574) | closed | 2026-09-24 | 2026-09-27 | 0 |
| 1576 | PR | [feat(reading): let the reader look at any stored figure on demand](https://github.com/HKUDS/DeepTutor/pull/1576) | closed | 2026-09-24 | 2026-09-26 | 0 |
| 1577 | Issue | [[Bug]: Full re-index creates a fresh version workspace without inheriting kv_store_llm_response_cache](https://github.com/HKUDS/DeepTutor/issues/1577) | closed | 2026-09-24 | 2026-09-27 | 2 |
| 1578 | Issue | [[Bug]: LightRAG jobs run on a fresh event loop per task — shared asyncio locks fail with "bound to a different event loop", breaking searches and cache finalization](https://github.com/HKUDS/DeepTutor/issues/1578) | closed | 2026-09-24 | 2026-09-26 | 3 |
| 1579 | Issue | [[Bug]: Gemini models/ prefix breaks Auto vision detection and LightRAG VLM selection](https://github.com/HKUDS/DeepTutor/issues/1579) | closed | 2026-09-24 | 2026-09-26 | 1 |
| 1580 | PR | [feat: add a workspace-scoped task board](https://github.com/HKUDS/DeepTutor/pull/1580) | closed | 2026-09-24 | 2026-09-26 | 0 |
| 1581 | PR | [fix(i18n): add missing translations for fr language](https://github.com/HKUDS/DeepTutor/pull/1581) | closed | 2026-09-24 | 2026-09-26 | 0 |
| 1582 | PR | [fix(mineru): scale cloud retry budget with key pool size](https://github.com/HKUDS/DeepTutor/pull/1582) | closed | 2026-09-24 | 2026-09-27 | 1 |
| 1583 | PR | [test(api): adapt knowledge_router/file_preview tests to lazy route inclusion](https://github.com/HKUDS/DeepTutor/pull/1583) | closed | 2026-09-24 | 2026-09-27 | 1 |
| 1584 | Issue | [[Bug]:Windows crashes on os.geteuid/os.getegid during knowledge base operations](https://github.com/HKUDS/DeepTutor/issues/1584) | closed | 2026-09-24 | 2026-09-26 | 1 |
| 1585 | Issue | [[Bug]: MinerU readiness fails to detect ModelScope models stored under MODELSCOPE_CACHE/models](https://github.com/HKUDS/DeepTutor/issues/1585) | closed | 2026-09-24 | 2026-09-26 | 1 |
| 1586 | Issue | [[Bug]: Readiness reports referenced Task Model as unconfigured and disables Reason tool](https://github.com/HKUDS/DeepTutor/issues/1586) | closed | 2026-09-24 | 2026-09-27 | 2 |
| 1587 | Issue | [[Bug]: Bug: Spurious "Create Partner" triggers hijack normal responses and abort conversations](https://github.com/HKUDS/DeepTutor/issues/1587) | closed | 2026-09-25 | 2026-09-26 | 3 |
| 1588 | PR | [fix(llm): match Gemini ids carrying the models/ resource prefix](https://github.com/HKUDS/DeepTutor/pull/1588) | closed | 2026-09-25 | 2026-10-13 | 0 |
| 1589 | PR | [fix: recognize referenced task model in readiness](https://github.com/HKUDS/DeepTutor/pull/1589) | closed | 2026-09-25 | 2026-09-26 | 0 |
| 1590 | PR | [fix: detect MinerU models in ModelScope cache layout](https://github.com/HKUDS/DeepTutor/pull/1590) | closed | 2026-09-25 | 2026-09-26 | 0 |
| 1591 | PR | [fix: support Windows data volume permission checks](https://github.com/HKUDS/DeepTutor/pull/1591) | closed | 2026-09-25 | 2026-09-26 | 0 |
| 1592 | PR | [fix: preserve generated Partner attachments](https://github.com/HKUDS/DeepTutor/pull/1592) | closed | 2026-09-25 | 2026-09-26 | 0 |
| 1593 | PR | [fix(partners): only start Partner authoring on an actual creation request](https://github.com/HKUDS/DeepTutor/pull/1593) | closed | 2026-09-25 | 2026-09-26 | 0 |
| 1594 | Issue | [[Bug] Failed chat submissions appear sent but disappear after reload](https://github.com/HKUDS/DeepTutor/issues/1594) | closed | 2026-09-25 | 2026-09-26 | 1 |
| 1595 | Issue | [[Feature Request]: Choose a workspace when creating or moving a knowledge base](https://github.com/HKUDS/DeepTutor/issues/1595) | closed | 2026-09-25 | 2026-09-27 | 1 |
| 1596 | Issue | [[Bug]: Immersive Reading lacks the workspace Skills picker (v1.6.11)](https://github.com/HKUDS/DeepTutor/issues/1596) | closed | 2026-09-25 | 2026-09-26 | 1 |
| 1597 | PR | [fix(partners): never spend an answer on a keyword guess (#1587)](https://github.com/HKUDS/DeepTutor/pull/1597) | closed | 2026-09-25 | 2026-09-26 | 0 |
| 1598 | PR | [fix: Windows UID compatibility](https://github.com/HKUDS/DeepTutor/pull/1598) | open | 2026-09-26 | 2026-09-26 | 0 |
| 1599 | PR | [fix: knowledge base listing through proxy](https://github.com/HKUDS/DeepTutor/pull/1599) | closed | 2026-09-26 | 2026-10-04 | 1 |
| 1600 | Issue | [[Bug]:research模式下askuser和大纲同时出现](https://github.com/HKUDS/DeepTutor/issues/1600) | closed | 2026-09-26 | 2026-09-26 | 3 |
| 1601 | PR | [fix: request UTF-8 mode for model-authored exec code](https://github.com/HKUDS/DeepTutor/pull/1601) | closed | 2026-09-26 | 2026-09-26 | 0 |
| 1602 | PR | [fix(web): keep failed chat submissions recoverable and retryable (#1594)](https://github.com/HKUDS/DeepTutor/pull/1602) | closed | 2026-09-26 | 2026-09-26 | 0 |
| 1603 | Issue | [[Bug]: automark emits rough-notation spans but the frontend ships no renderer — annotations show as raw HTML code](https://github.com/HKUDS/DeepTutor/issues/1603) | closed | 2026-09-26 | 2026-09-26 | 1 |
| 1605 | PR | [fix(i18n): translate task board strings into German](https://github.com/HKUDS/DeepTutor/pull/1605) | closed | 2026-09-26 | 2026-10-16 | 0 |
| 1606 | PR | [fix(web): measure root redirect under chat route budget](https://github.com/HKUDS/DeepTutor/pull/1606) | closed | 2026-09-26 | 2026-10-16 | 0 |
| 1607 | PR | [fix(research): repoint resolve_pause user-reply helpers to the moved loop pipeline](https://github.com/HKUDS/DeepTutor/pull/1607) | closed | 2026-09-26 | 2026-09-26 | 0 |
| 1608 | PR | [feat(book): complete bare LaTeX delimiters in math reading](https://github.com/HKUDS/DeepTutor/pull/1608) | open | 2026-09-27 | 2026-09-27 | 0 |
| 1609 | PR | [fix(sessions): keep recycled chats out of history search](https://github.com/HKUDS/DeepTutor/pull/1609) | closed | 2026-09-27 | 2026-10-04 | 0 |
| 1610 | Issue | [[Bug/Enhancement]: Complete textbook grounding beyond the 64-figure cap: extraction fidelity and reliable retrieval](https://github.com/HKUDS/DeepTutor/issues/1610) | closed | 2026-09-27 | 2026-10-12 | 4 |
| 1611 | Issue | [[Feature Request]: Reliable source-grounded teaching and visual practice with trustworthy assessment and learning progress](https://github.com/HKUDS/DeepTutor/issues/1611) | closed | 2026-09-27 | 2026-10-12 | 3 |
| 1612 | Issue | [[Enhancement]: Reliable long-document indexing with resumable work, truthful progress, and safe recovery](https://github.com/HKUDS/DeepTutor/issues/1612) | closed | 2026-09-27 | 2026-10-12 | 4 |
| 1613 | Issue | [[Bug]:切换到自定义工作区后，子Agent都无法访问](https://github.com/HKUDS/DeepTutor/issues/1613) | closed | 2026-09-28 | 2026-10-04 | 2 |
| 1614 | Issue | [[Bug] 1.6.x renders only the first ~7 rounds of a long chat session, and the assistant loses all later context](https://github.com/HKUDS/DeepTutor/issues/1614) | closed | 2026-09-28 | 2026-10-04 | 5 |
| 1615 | PR | [fix: keep recycled sessions out of question bank counts](https://github.com/HKUDS/DeepTutor/pull/1615) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1616 | PR | [fix: consolidate web search results up to the configured max_results](https://github.com/HKUDS/DeepTutor/pull/1616) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1617 | Issue | [[Bug]:](https://github.com/HKUDS/DeepTutor/issues/1617) | closed | 2026-09-28 | 2026-09-28 | 0 |
| 1618 | PR | [feat: bulk select question bank entries in chat](https://github.com/HKUDS/DeepTutor/pull/1618) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1619 | PR | [fix(chat): preserve long-session branch path (#1614)](https://github.com/HKUDS/DeepTutor/pull/1619) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1620 | PR | [feat: allow practice from the question bank](https://github.com/HKUDS/DeepTutor/pull/1620) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1621 | PR | [fix: post reading workspace "Save to notebook" to the backend route](https://github.com/HKUDS/DeepTutor/pull/1621) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1622 | PR | [fix: keep BibTeX entries with accented author names](https://github.com/HKUDS/DeepTutor/pull/1622) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1623 | Issue | [[Bug]:内部含有回车的数学公式有时无法正常渲染](https://github.com/HKUDS/DeepTutor/issues/1623) | closed | 2026-09-28 | 2026-10-04 | 1 |
| 1624 | Issue | [[Bug]: Mastery Path quiz answers trigger context-free KB retrieval using option letters](https://github.com/HKUDS/DeepTutor/issues/1624) | closed | 2026-09-28 | 2026-10-04 | 1 |
| 1625 | PR | [fix(workspace): preserve shared subagent access (#1613)](https://github.com/HKUDS/DeepTutor/pull/1625) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1626 | PR | [fix(mastery): don't pre-search the KB with a quiz card answer](https://github.com/HKUDS/DeepTutor/pull/1626) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1627 | PR | [fix(web): render display math whose $$ hug a multi-line formula](https://github.com/HKUDS/DeepTutor/pull/1627) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1628 | PR | [docs(web): add v1.6.12 settings screenshots](https://github.com/HKUDS/DeepTutor/pull/1628) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1629 | Issue | [[Feature Request]: Native Integration of Scientific Research Primitives (Feynman / arXiv Workflows)](https://github.com/HKUDS/DeepTutor/issues/1629) | closed | 2026-09-28 | 2026-10-08 | 1 |
| 1630 | Issue | [[Bug]: 伙伴与智能体 CLI 应用的模型/推理强度配置无法保存（settings draft extensions.subagent:* 从未落地）](https://github.com/HKUDS/DeepTutor/issues/1630) | closed | 2026-09-28 | 2026-10-07 | 1 |
| 1631 | PR | [feat: add Requesty as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/1631) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1632 | PR | [fix(web-source): scope crawl seeds to their parent directory](https://github.com/HKUDS/DeepTutor/pull/1632) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1633 | PR | [fix(web-source): scope crawl seeds to their parent directory](https://github.com/HKUDS/DeepTutor/pull/1633) | closed | 2026-09-28 | 2026-09-28 | 1 |
| 1634 | PR | [test(settings): persist restored subagent drafts (#1630)](https://github.com/HKUDS/DeepTutor/pull/1634) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1635 | PR | [feat(web-source): add bilingual source pairing (#902)](https://github.com/HKUDS/DeepTutor/pull/1635) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1636 | PR | [test(mastery): guard the review trail scroll cap (#1566)](https://github.com/HKUDS/DeepTutor/pull/1636) | closed | 2026-09-28 | 2026-10-04 | 0 |
| 1637 | PR | [fix(reading): close a Markdown fence only on a matching bare run](https://github.com/HKUDS/DeepTutor/pull/1637) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1638 | PR | [fix(partners): render every fenced code block as code in Telegram HTML](https://github.com/HKUDS/DeepTutor/pull/1638) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1639 | PR | [docs(install): add one-command Docker quick start](https://github.com/HKUDS/DeepTutor/pull/1639) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1640 | PR | [feat(co-writer): support model selection for edits (#661)](https://github.com/HKUDS/DeepTutor/pull/1640) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1641 | Issue | [[Bug]:Fresh `.md` uploads open as a single page in Immersive Reading (v1.6.12)](https://github.com/HKUDS/DeepTutor/issues/1641) | closed | 2026-09-29 | 2026-10-08 | 3 |
| 1642 | PR | [fix(agents): skip KB seeding for mastery card answers (#1624)](https://github.com/HKUDS/DeepTutor/pull/1642) | closed | 2026-09-29 | 2026-10-04 | 1 |
| 1644 | Issue | [feat(video-learning): add timestamped watching marks](https://github.com/HKUDS/DeepTutor/issues/1644) | closed | 2026-09-29 | 2026-10-04 | 2 |
| 1645 | PR | [feat(video-learning): add timestamped watching marks (#1644)](https://github.com/HKUDS/DeepTutor/pull/1645) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1646 | Issue | [[Bug]: Deleting a Mastery session can leave an orphaned turn holding the workspace activity lock](https://github.com/HKUDS/DeepTutor/issues/1646) | closed | 2026-09-29 | 2026-10-04 | 1 |
| 1647 | Issue | [[Bug]: Chat message knowledge-base labels display internal resource IDs instead of names](https://github.com/HKUDS/DeepTutor/issues/1647) | closed | 2026-09-29 | 2026-10-04 | 2 |
| 1648 | Issue | [[Bug]: ask_user Submit during a WebSocket reconnect gives up after 2s (10x200ms) while the reconnect ladder waits up to 8s — and reports a false "question is no longer active"](https://github.com/HKUDS/DeepTutor/issues/1648) | closed | 2026-09-29 | 2026-10-04 | 3 |
| 1649 | PR | [feat: add kb eval command for RAG retrieval quality scoring](https://github.com/HKUDS/DeepTutor/pull/1649) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1650 | Issue | [feat(learner): support assigned interactive books](https://github.com/HKUDS/DeepTutor/issues/1650) | closed | 2026-09-29 | 2026-10-04 | 1 |
| 1651 | PR | [feat(learner): expose assigned interactive books](https://github.com/HKUDS/DeepTutor/pull/1651) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1652 | PR | [fix(learner): expose assigned reading library (#1222)](https://github.com/HKUDS/DeepTutor/pull/1652) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1653 | PR | [feat(web): offer reasoning effort levels for GLM models under openai binding](https://github.com/HKUDS/DeepTutor/pull/1653) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1654 | Issue | [feat(reading): add material-scoped natural read-aloud audio](https://github.com/HKUDS/DeepTutor/issues/1654) | closed | 2026-09-29 | 2026-10-04 | 1 |
| 1655 | PR | [feat(reading): add material-scoped natural read-aloud audio (#1654)](https://github.com/HKUDS/DeepTutor/pull/1655) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1656 | Issue | [feat(reading): add server-owned quiz star rewards](https://github.com/HKUDS/DeepTutor/issues/1656) | closed | 2026-09-29 | 2026-10-07 | 1 |
| 1657 | PR | [feat(reading): add server-owned quiz star rewards (#1656)](https://github.com/HKUDS/DeepTutor/pull/1657) | closed | 2026-09-29 | 2026-10-04 | 2 |
| 1659 | PR | [fix(session): budget image blocks without tokenizing encoded payloads](https://github.com/HKUDS/DeepTutor/pull/1659) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1660 | PR | [fix(rag): resolve numbered exercises from completed parse artifacts](https://github.com/HKUDS/DeepTutor/pull/1660) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1661 | PR | [feat: add Polish localization](https://github.com/HKUDS/DeepTutor/pull/1661) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1662 | PR | [fix(learner): allow own-scope settings and workspace writes via route templates](https://github.com/HKUDS/DeepTutor/pull/1662) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1663 | PR | [fix(learning): mint quiz submission ids via randomUuid on plain HTTP](https://github.com/HKUDS/DeepTutor/pull/1663) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1664 | PR | [feat(parsing): select an independent image description model](https://github.com/HKUDS/DeepTutor/pull/1664) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1665 | PR | [perf(parsing): cache image descriptions per workspace](https://github.com/HKUDS/DeepTutor/pull/1665) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1666 | PR | [fix(chat): label sent-message knowledge-base references with catalog names](https://github.com/HKUDS/DeepTutor/pull/1666) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1667 | Issue | [feat(partners/telegram): per-chat and per-topic response policy (open inside allowlisted topics, mention-only elsewhere)](https://github.com/HKUDS/DeepTutor/issues/1667) | closed | 2026-09-29 | 2026-10-04 | 2 |
| 1668 | PR | [fix(web): keep submits alive across the full reconnect ladder (#1648)](https://github.com/HKUDS/DeepTutor/pull/1668) | closed | 2026-09-29 | 2026-10-04 | 0 |
| 1669 | PR | [fix(parsing): add opt-in normalization for tiny scanned PDF pages](https://github.com/HKUDS/DeepTutor/pull/1669) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1670 | PR | [Fix/mineru local failure reasons](https://github.com/HKUDS/DeepTutor/pull/1670) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1671 | PR | [perf(rag): add opt-in bounded image-description batches](https://github.com/HKUDS/DeepTutor/pull/1671) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1672 | PR | [fix(parsing): restore source pages and resume MinerU slices (follow-up to #1569)](https://github.com/HKUDS/DeepTutor/pull/1672) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1673 | Issue | [[Bug]: EPUB reader loses TOC heading anchors and mislabels reading positions](https://github.com/HKUDS/DeepTutor/issues/1673) | closed | 2026-09-30 | 2026-10-04 | 1 |
| 1674 | PR | [feat: add API Route as an LLM gateway provider](https://github.com/HKUDS/DeepTutor/pull/1674) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1675 | PR | [fix(usage): exclude encoded image payloads from token estimates](https://github.com/HKUDS/DeepTutor/pull/1675) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1676 | Issue | [[Bug]: Tutor selection fails on complex rendered LaTeX](https://github.com/HKUDS/DeepTutor/issues/1676) | closed | 2026-09-30 | 2026-10-04 | 2 |
| 1677 | PR | [fix(partners): keep IM replies in step with the turn](https://github.com/HKUDS/DeepTutor/pull/1677) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1678 | Issue | [[Bug]: v1.6.12 Chat history search fails — existing text cannot be matched](https://github.com/HKUDS/DeepTutor/issues/1678) | closed | 2026-09-30 | 2026-10-04 | 1 |
| 1679 | PR | [fix: support Xiaomi MiMo v2.5 preset speech](https://github.com/HKUDS/DeepTutor/pull/1679) | closed | 2026-09-30 | 2026-10-04 | 0 |
| 1680 | PR | [feat: add synchronized speech narration to Math Animator](https://github.com/HKUDS/DeepTutor/pull/1680) | open | 2026-09-30 | 2026-09-30 | 0 |
| 1681 | PR | [feat: add native MiniMax speech synthesis](https://github.com/HKUDS/DeepTutor/pull/1681) | closed | 2026-10-01 | 2026-10-04 | 0 |
| 1682 | PR | [fix(session): ground rendered LaTeX selections (#1676)](https://github.com/HKUDS/DeepTutor/pull/1682) | closed | 2026-10-01 | 2026-10-04 | 0 |
| 1683 | PR | [fix(history): search full conversation transcripts (#1678)](https://github.com/HKUDS/DeepTutor/pull/1683) | closed | 2026-10-01 | 2026-10-04 | 0 |
| 1684 | PR | [feat: add FutureInfra as an LLM provider](https://github.com/HKUDS/DeepTutor/pull/1684) | closed | 2026-10-01 | 2026-10-04 | 0 |
| 1685 | PR | [fix(session): stop waiting turns before deletion (#1646)](https://github.com/HKUDS/DeepTutor/pull/1685) | closed | 2026-10-01 | 2026-10-04 | 0 |
| 1686 | PR | [fix(reading): preserve EPUB outline anchors (#1673)](https://github.com/HKUDS/DeepTutor/pull/1686) | closed | 2026-10-02 | 2026-10-04 | 0 |
| 1687 | PR | [feat(partners): add Telegram per-chat response policies (#1667)](https://github.com/HKUDS/DeepTutor/pull/1687) | closed | 2026-10-02 | 2026-10-04 | 0 |
| 1688 | PR | [fix(reading): preserve PDF reading position across resizes](https://github.com/HKUDS/DeepTutor/pull/1688) | closed | 2026-10-02 | 2026-10-04 | 0 |
| 1690 | PR | [fix: handle process probe decoding failures and false-positive LLM retries](https://github.com/HKUDS/DeepTutor/pull/1690) | closed | 2026-10-03 | 2026-10-04 | 1 |
| 1691 | Issue | [[Bug]:在”精通之道“的学习过程中，如果出选择题做测验，答案全部是A](https://github.com/HKUDS/DeepTutor/issues/1691) | closed | 2026-10-03 | 2026-10-04 | 1 |
| 1692 | PR | [fix(mastery): shuffle choice options so the correct answer moves (#1691)](https://github.com/HKUDS/DeepTutor/pull/1692) | closed | 2026-10-03 | 2026-10-07 | 1 |
| 1693 | PR | [fix(partners): keep engine-injected paths out of IM tool hints](https://github.com/HKUDS/DeepTutor/pull/1693) | open | 2026-10-03 | 2026-10-03 | 0 |
| 1694 | PR | [fix(cli): respect configured token budget in doctor probe](https://github.com/HKUDS/DeepTutor/pull/1694) | closed | 2026-10-03 | 2026-10-04 | 0 |
| 1695 | PR | [fix(rag): retain source figures beyond the 64-asset document cap (#1610)](https://github.com/HKUDS/DeepTutor/pull/1695) | open | 2026-10-03 | 2026-10-07 | 2 |
| 1696 | Issue | [[Bug]: Windows path separators cause architecture-contracts and internal-route-contract test failures in web/tests](https://github.com/HKUDS/DeepTutor/issues/1696) | closed | 2026-10-03 | 2026-10-04 | 1 |
| 1697 | PR | [fix(web): normalize Windows path separators in contract node tests (#1696)](https://github.com/HKUDS/DeepTutor/pull/1697) | closed | 2026-10-03 | 2026-10-03 | 1 |
| 1698 | PR | [fix(web): normalize path separators in architecture and route contract tests (#1696)](https://github.com/HKUDS/DeepTutor/pull/1698) | open | 2026-10-03 | 2026-10-03 | 0 |
| 1699 | PR | [test(codebuddy): make credential fixture expiry relative to now](https://github.com/HKUDS/DeepTutor/pull/1699) | open | 2026-10-03 | 2026-10-03 | 0 |
| 1700 | PR | [fix(co-writer): keep a placeholder row and warn when DOCX table row parsing fails](https://github.com/HKUDS/DeepTutor/pull/1700) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1701 | PR | [fix(web): surface quiz follow-up session-id writeback failures](https://github.com/HKUDS/DeepTutor/pull/1701) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1702 | PR | [fix(rag): classify invalid persisted index errors and include re-index steps](https://github.com/HKUDS/DeepTutor/pull/1702) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1703 | PR | [fix(rag): log swallowed embedding/image progress and LightRAG meta failures](https://github.com/HKUDS/DeepTutor/pull/1703) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1704 | PR | [fix(runtime): log swallowed launcher, init and update-worker failures](https://github.com/HKUDS/DeepTutor/pull/1704) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1705 | PR | [fix(chat): keep unsent drafts safe when restore fails](https://github.com/HKUDS/DeepTutor/pull/1705) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1706 | PR | [fix(knowledge): surface swallowed KB status, progress and folder-sync failures](https://github.com/HKUDS/DeepTutor/pull/1706) | closed | 2026-10-04 | 2026-10-07 | 1 |
| 1707 | PR | [fix: log silently swallowed failures in five services](https://github.com/HKUDS/DeepTutor/pull/1707) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1708 | PR | [fix(workspace): surface unreadable migration journals and skipped corrupt sources](https://github.com/HKUDS/DeepTutor/pull/1708) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1709 | PR | [test(api): add contract tests for upload guards, quiz judge, reading progress, notebook and memory routers](https://github.com/HKUDS/DeepTutor/pull/1709) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1710 | PR | [test(web): cover the settings store and memory-graph helpers](https://github.com/HKUDS/DeepTutor/pull/1710) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1711 | Issue | [[Bug]: /knowledge-bases rescans every index version per request and blocks the single worker for seconds](https://github.com/HKUDS/DeepTutor/issues/1711) | closed | 2026-10-04 | 2026-10-04 | 1 |
| 1712 | PR | [fix(llm): avoid tokenizing image payloads in request fingerprints](https://github.com/HKUDS/DeepTutor/pull/1712) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1713 | PR | [perf(mastery): seed fresh status before the first model call](https://github.com/HKUDS/DeepTutor/pull/1713) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1714 | PR | [perf(llm): deduplicate repeated inline user images per request](https://github.com/HKUDS/DeepTutor/pull/1714) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1715 | PR | [fix(runtime): surface launcher termination and port-kill signal failures](https://github.com/HKUDS/DeepTutor/pull/1715) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1716 | PR | [docs(tools): add tools surface guide](https://github.com/HKUDS/DeepTutor/pull/1716) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1717 | PR | [docs(events): add event and progress chain guide](https://github.com/HKUDS/DeepTutor/pull/1717) | closed | 2026-10-04 | 2026-10-07 | 0 |
| 1718 | PR | [test(book): cover engine stage transitions](https://github.com/HKUDS/DeepTutor/pull/1718) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1719 | PR | [test(storage): lock file library disk-deletion failure paths](https://github.com/HKUDS/DeepTutor/pull/1719) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1720 | PR | [fix(migration): scope unreadable-journal rejection to migration paths](https://github.com/HKUDS/DeepTutor/pull/1720) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1721 | PR | [fix(migration): scope unreadable-journal rejection to migration paths](https://github.com/HKUDS/DeepTutor/pull/1721) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1722 | PR | [docs(chat): code-reading guide for the chat/agent runtime](https://github.com/HKUDS/DeepTutor/pull/1722) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1723 | PR | [feat(chat): keep branch navigator visible on forked messages (#1410)](https://github.com/HKUDS/DeepTutor/pull/1723) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1724 | PR | [feat(cron): allow disabling the scheduler and configuring its idle re-check interval (#451)](https://github.com/HKUDS/DeepTutor/pull/1724) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1725 | PR | [test(chat): reset draft mocks between restore-failure specs](https://github.com/HKUDS/DeepTutor/pull/1725) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1726 | PR | [fix(partners): restore Feishu card text, media download type and mention names](https://github.com/HKUDS/DeepTutor/pull/1726) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1727 | PR | [fix(knowledge): make update_kb_status write failures observable](https://github.com/HKUDS/DeepTutor/pull/1727) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1728 | PR | [fix(launcher): log handoff failure when mark_failed fails too](https://github.com/HKUDS/DeepTutor/pull/1728) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1729 | PR | [fix: surface quiz followup session-id writeback failures](https://github.com/HKUDS/DeepTutor/pull/1729) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1730 | PR | [fix(sandbox): drop pass_fds from the rlimit report pipe and guard it with try/finally](https://github.com/HKUDS/DeepTutor/pull/1730) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1731 | PR | [fix(api): warn when a deferred tool's definition fails to load](https://github.com/HKUDS/DeepTutor/pull/1731) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1732 | PR | [test: pin TZ in runtime_context date assertions for cross-timezone stability](https://github.com/HKUDS/DeepTutor/pull/1732) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1733 | PR | [test: freeze naive FIXED_NOW for cross-platform TZ stability](https://github.com/HKUDS/DeepTutor/pull/1733) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1734 | PR | [fix(reading): converge the mobile header and dock the selection panel](https://github.com/HKUDS/DeepTutor/pull/1734) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1735 | PR | [docs: add agents orchestration reading guide](https://github.com/HKUDS/DeepTutor/pull/1735) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1736 | PR | [fix(co-writer): use English placeholder and sort test imports for CI](https://github.com/HKUDS/DeepTutor/pull/1736) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1737 | PR | [fix(knowledge): log folder sync state recording failures](https://github.com/HKUDS/DeepTutor/pull/1737) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1738 | PR | [test(reading): cover the bilingual EPUB pairing pipeline edge cases](https://github.com/HKUDS/DeepTutor/pull/1738) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1739 | PR | [test(api): cover learning-records account isolation and read boundaries](https://github.com/HKUDS/DeepTutor/pull/1739) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1740 | PR | [test(plugins): pin entry-point loader contract across load, isolation, duplicate and gating paths](https://github.com/HKUDS/DeepTutor/pull/1740) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1741 | PR | [test(question): pin mimic websocket error-path and stdout interceptor failure contracts](https://github.com/HKUDS/DeepTutor/pull/1741) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1742 | PR | [test(reading): pin progress API durability contract](https://github.com/HKUDS/DeepTutor/pull/1742) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1743 | PR | [chore: remove internal audit evidence from PR branch](https://github.com/HKUDS/DeepTutor/pull/1743) | open | 2026-10-05 | 2026-10-07 | 0 |
| 1744 | PR | [test(web): smoke coverage for StandaloneComposer send gating](https://github.com/HKUDS/DeepTutor/pull/1744) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1745 | PR | [test(settings): cover CLI-app model persistence end to end (#1630)](https://github.com/HKUDS/DeepTutor/pull/1745) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1746 | PR | [fix(partners): stop telegram typing loop for denied senders and dropped media-group stragglers](https://github.com/HKUDS/DeepTutor/pull/1746) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1747 | PR | [test: add tex_downloader/tex_chunker toolchain tests](https://github.com/HKUDS/DeepTutor/pull/1747) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1748 | PR | [test: add tex_downloader/tex_chunker toolchain tests](https://github.com/HKUDS/DeepTutor/pull/1748) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1749 | PR | [test(web): cover VisualizationViewer render branches (mermaid/svg/chartjs/html/plugin/manim)](https://github.com/HKUDS/DeepTutor/pull/1749) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1750 | PR | [style: apply ruff format to spine_synthesizer tests](https://github.com/HKUDS/DeepTutor/pull/1750) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1751 | PR | [fix(services): surface fsync failures in atomic writers as rate-limited warnings](https://github.com/HKUDS/DeepTutor/pull/1751) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1752 | PR | [fix(llm): warn when CodeBuddy tool-call interrupt or drain fails](https://github.com/HKUDS/DeepTutor/pull/1752) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1753 | PR | [fix(llm): warn when CodeBuddy tool-call interrupt or drain fails](https://github.com/HKUDS/DeepTutor/pull/1753) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1754 | PR | [fix(courses): surface course deletion failure instead of silent redirect](https://github.com/HKUDS/DeepTutor/pull/1754) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1755 | PR | [fix(co-writer): warn and keep placeholder row when DOCX table row parsing fails](https://github.com/HKUDS/DeepTutor/pull/1755) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1756 | PR | [fix(co-writer): use English placeholder and sort test imports for CI](https://github.com/HKUDS/DeepTutor/pull/1756) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1757 | PR | [fix(embedding): log progress callback failures instead of swallowing them](https://github.com/HKUDS/DeepTutor/pull/1757) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1758 | PR | [fix: log image progress callback failures instead of swallowing them](https://github.com/HKUDS/DeepTutor/pull/1758) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1759 | PR | [fix(lightrag): warn when workspace meta.json exists but is unusable](https://github.com/HKUDS/DeepTutor/pull/1759) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1760 | PR | [fix(lightrag): warn when workspace meta.json exists but is unusable](https://github.com/HKUDS/DeepTutor/pull/1760) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1761 | PR | [fix(workspace): surface skipped corrupt sources in migration dependency closure](https://github.com/HKUDS/DeepTutor/pull/1761) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1762 | PR | [fix(workspace): surface skipped corrupt sources in migration dependency closure](https://github.com/HKUDS/DeepTutor/pull/1762) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1763 | PR | [test(partners): lock outbound dispatch timeout semantics](https://github.com/HKUDS/DeepTutor/pull/1763) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1764 | PR | [fix(memory): log corrupt snapshot files instead of skipping silently](https://github.com/HKUDS/DeepTutor/pull/1764) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1765 | PR | [fix(memory): log corrupt snapshot files instead of skipping silently](https://github.com/HKUDS/DeepTutor/pull/1765) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1766 | PR | [fix(api): warn when a deferred tool's definition fails to load](https://github.com/HKUDS/DeepTutor/pull/1766) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1767 | PR | [test(web): smoke ChatWorkspace empty home, streaming turn, failure banner](https://github.com/HKUDS/DeepTutor/pull/1767) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1768 | PR | [test(co-writer): lock router contract for CRUD, 4xx payloads, export failures](https://github.com/HKUDS/DeepTutor/pull/1768) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1769 | PR | [test(launcher): cover lifecycle termination, port cleanup and marker corruption paths](https://github.com/HKUDS/DeepTutor/pull/1769) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1770 | PR | [test(web): cover memory-graph pure functions (parseDoc/splitRef/buildGraph)](https://github.com/HKUDS/DeepTutor/pull/1770) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1771 | PR | [test: memory workbench router contract coverage (GET shapes, edit/delete round-trips, 4xx)](https://github.com/HKUDS/DeepTutor/pull/1771) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1772 | PR | [style: ruff format memory router contract tests](https://github.com/HKUDS/DeepTutor/pull/1772) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1773 | PR | [test(session): cover pocketbase_store failure branches and pagination edges](https://github.com/HKUDS/DeepTutor/pull/1773) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1774 | PR | [test: unit-cover the quiz-judge WebSocket router](https://github.com/HKUDS/DeepTutor/pull/1774) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1775 | PR | [test(quiz): add QuizViewer smoke and grading interaction coverage](https://github.com/HKUDS/DeepTutor/pull/1775) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1776 | PR | [test(partners): telegram message parsing, chunking and typing contract suite](https://github.com/HKUDS/DeepTutor/pull/1776) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1777 | PR | [docs(evidence): i18n system reading guide (backend i18n, prompt/status YAML, web localization)](https://github.com/HKUDS/DeepTutor/pull/1777) | closed | 2026-10-05 | 2026-10-06 | 1 |
| 1778 | PR | [fix(web): sanitize quoted html tag attributes and preserve bold whitespace](https://github.com/HKUDS/DeepTutor/pull/1778) | closed | 2026-10-05 | 2026-10-11 | 1 |
| 1779 | Issue | [[Bug]:EmbeddingClient 的进程级全局锁把所有 embedding 请求串行化，batch_delay=0 时也生效，摧毁并发并导致 LightRAG 索引超时](https://github.com/HKUDS/DeepTutor/issues/1779) | closed | 2026-10-05 | 2026-10-07 | 2 |
| 1780 | PR | [fix: decode escaped emoji in ask_user cards as real characters](https://github.com/HKUDS/DeepTutor/pull/1780) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1781 | Issue | [[Bug]: Multi-turn qualitative repair compounds SRS lapses within minutes](https://github.com/HKUDS/DeepTutor/issues/1781) | closed | 2026-10-05 | 2026-10-07 | 1 |
| 1782 | Issue | [[Bug]: Knowledge base (LllamaIndex) initialization fails with "Embedding API key not set. Configure the active profile in Settings > Embedding models."](https://github.com/HKUDS/DeepTutor/issues/1782) | closed | 2026-10-05 | 2026-10-07 | 3 |
| 1783 | PR | [fix: embedding concurrency, local Lemonade, reading fences, and learner nav](https://github.com/HKUDS/DeepTutor/pull/1783) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1784 | Issue | [[Bug]: Existing Mastery Path maps with more than 7 objectives in a module cannot be edited](https://github.com/HKUDS/DeepTutor/issues/1784) | closed | 2026-10-05 | 2026-10-07 | 1 |
| 1785 | PR | [Expose built-in mastery tutor tools over HTTP](https://github.com/HKUDS/DeepTutor/pull/1785) | open | 2026-10-05 | 2026-10-19 | 0 |
| 1786 | PR | [feat: add Opper as an LLM and embedding provider](https://github.com/HKUDS/DeepTutor/pull/1786) | closed | 2026-10-05 | 2026-10-07 | 0 |
| 1787 | PR | [fix(crawler): ignore absurd robots.txt crawl-delay values](https://github.com/HKUDS/DeepTutor/pull/1787) | closed | 2026-10-06 | 2026-10-07 | 0 |
| 1788 | Issue | [[Bug]: Parked ask_user turns lose their card on reload and can be destroyed by deleting another message](https://github.com/HKUDS/DeepTutor/issues/1788) | closed | 2026-10-06 | 2026-10-07 | 2 |
| 1789 | PR | [fix(chat): keep parked ask_user turns alive across deletion and reload](https://github.com/HKUDS/DeepTutor/pull/1789) | closed | 2026-10-06 | 2026-10-07 | 0 |
| 1790 | PR | [fix(mastery-path): allow editing legacy objective counts](https://github.com/HKUDS/DeepTutor/pull/1790) | closed | 2026-10-06 | 2026-10-07 | 0 |
| 1791 | PR | [feat(providers): add Y-API as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/1791) | closed | 2026-10-06 | 2026-10-07 | 0 |
| 1792 | Issue | [[Bug]: Hybrid retrieval silently degrades to vector-only on Python 3.14 — no warning, despite `hybrid` being the default](https://github.com/HKUDS/DeepTutor/issues/1792) | closed | 2026-10-06 | 2026-10-07 | 3 |
| 1793 | Issue | [[Bug]: IndentationError and NameError in Document Parsing service](https://github.com/HKUDS/DeepTutor/issues/1793) | closed | 2026-10-06 | 2026-10-07 | 1 |
| 1794 | PR | [fix(learning): prevent compounding SRS lapses during multi-turn qualitative repairs (#1781)](https://github.com/HKUDS/DeepTutor/pull/1794) | closed | 2026-10-06 | 2026-10-07 | 0 |
| 1795 | Issue | [[Bug]: Interrupted shutdown orphans the backend; a non-interactive restart then exits instead of reclaiming it — under launchd this loops forever](https://github.com/HKUDS/DeepTutor/issues/1795) | closed | 2026-10-07 | 2026-10-07 | 1 |
| 1796 | Issue | [[Bug]: Qwen3-family models that reject `enable_thinking` cannot be used at all — the parameter is inferred from a name substring match](https://github.com/HKUDS/DeepTutor/issues/1796) | closed | 2026-10-07 | 2026-10-07 | 1 |
| 1797 | PR | [fix: embedding local keyless, qwen3-Instruct thinking, embedding concurrency](https://github.com/HKUDS/DeepTutor/pull/1797) | closed | 2026-10-07 | 2026-10-07 | 0 |
| 1798 | PR | [fix(settings): prevent phantom unsaved changes when configuring MinerU cloud API](https://github.com/HKUDS/DeepTutor/pull/1798) | closed | 2026-10-07 | 2026-10-07 | 0 |
| 1799 | Issue | [[Bug] Account-level Memory L1 misses custom-workspace conversations](https://github.com/HKUDS/DeepTutor/issues/1799) | closed | 2026-10-07 | 2026-10-07 | 4 |
| 1800 | PR | [fix(memory): aggregate account-level L1 across workspaces (#1799)](https://github.com/HKUDS/DeepTutor/pull/1800) | closed | 2026-10-07 | 2026-10-07 | 0 |
| 1801 | PR | [fix(rag): surface the hybrid to vector-only retrieval degradation (#1792)](https://github.com/HKUDS/DeepTutor/pull/1801) | closed | 2026-10-07 | 2026-10-07 | 0 |
| 1802 | Issue | [[Bug]: A knowledge base with enough figures cannot ingest further documents — the visual-asset manifest hits a hardcoded 16 MB cap and every subsequent file fails](https://github.com/HKUDS/DeepTutor/issues/1802) | closed | 2026-10-07 | 2026-10-07 | 3 |
| 1803 | PR | [fix(knowledge): resolve workspace-scoped knowledge base files during deletion](https://github.com/HKUDS/DeepTutor/pull/1803) | closed | 2026-10-07 | 2026-10-14 | 1 |
| 1804 | PR | [fix(rag): shard the visual-asset manifest so KBs scale past 16 MB (#1802)](https://github.com/HKUDS/DeepTutor/pull/1804) | open | 2026-10-07 | 2026-10-07 | 1 |
| 1805 | PR | [test(learning): cover persisted qualitative repair turns](https://github.com/HKUDS/DeepTutor/pull/1805) | closed | 2026-10-07 | 2026-10-14 | 0 |
| 1806 | PR | [Codex/tauri desktop phase 0](https://github.com/HKUDS/DeepTutor/pull/1806) | closed | 2026-10-08 | 2026-10-08 | 0 |
| 1807 | Issue | [[Bug]: SDK capability contract methods raise AttributeError](https://github.com/HKUDS/DeepTutor/issues/1807) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1808 | PR | [fix(sdk): serialize slotted capability availability](https://github.com/HKUDS/DeepTutor/pull/1808) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1809 | Issue | [[Bug]: Generated contract checking rejects unchanged CRLF checkouts](https://github.com/HKUDS/DeepTutor/issues/1809) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1810 | PR | [fix(web): accept CRLF generated contracts without masking drift](https://github.com/HKUDS/DeepTutor/pull/1810) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1811 | Issue | [[Bug]: Co-Writer edit and automark convert model-selection errors to HTTP 500](https://github.com/HKUDS/DeepTutor/issues/1811) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1812 | PR | [fix(api): preserve Co-Writer model-selection HTTP errors](https://github.com/HKUDS/DeepTutor/pull/1812) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1813 | Issue | [[Bug]: Quiz judging forwards local attachment URLs without image bytes](https://github.com/HKUDS/DeepTutor/issues/1813) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1814 | PR | [fix(api): materialize saved quiz answer attachments](https://github.com/HKUDS/DeepTutor/pull/1814) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1815 | Issue | [[Bug]: Equal-time assessment attempts can keep the earlier answer as latest](https://github.com/HKUDS/DeepTutor/issues/1815) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1816 | PR | [fix(learning): preserve submission order for timestamp ties](https://github.com/HKUDS/DeepTutor/pull/1816) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1817 | Issue | [Concurrent Windows settings writes can fail before acquiring the file lock](https://github.com/HKUDS/DeepTutor/issues/1817) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1818 | PR | [fix(settings): normalize Windows lock path aliases](https://github.com/HKUDS/DeepTutor/pull/1818) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1819 | Issue | [[Bug]: Learning evidence and atlas readers can mix committed revisions](https://github.com/HKUDS/DeepTutor/issues/1819) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1820 | PR | [fix(learning): keep aggregate reads in one SQLite snapshot](https://github.com/HKUDS/DeepTutor/pull/1820) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1821 | Issue | [[Bug]: Short-lived SQLite helpers leave connections open after their context exits](https://github.com/HKUDS/DeepTutor/issues/1821) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1822 | PR | [fix(storage): close short-lived SQLite connections deterministically](https://github.com/HKUDS/DeepTutor/pull/1822) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1823 | Issue | [[Bug]: Model catalog read errors can overwrite existing configuration with defaults](https://github.com/HKUDS/DeepTutor/issues/1823) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1824 | PR | [fix(config): preserve catalogs after filesystem read failures](https://github.com/HKUDS/DeepTutor/pull/1824) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1825 | Issue | [[Bug]: Cancelling one shared-hint waiter cancels other requests](https://github.com/HKUDS/DeepTutor/issues/1825) | closed | 2026-10-08 | 2026-10-15 | 0 |
| 1826 | PR | [fix(cache): isolate shared producers from waiter cancellation](https://github.com/HKUDS/DeepTutor/pull/1826) | closed | 2026-10-08 | 2026-10-15 | 0 |
| 1827 | Issue | [[Bug]: CodeBuddy cannot retry real SDK authentication errors](https://github.com/HKUDS/DeepTutor/issues/1827) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1828 | PR | [fix(llm): reload CodeBuddy credentials after SDK authentication errors](https://github.com/HKUDS/DeepTutor/pull/1828) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1829 | Issue | [[Bug]: Rejected turn admission can leave a coordinator lease active](https://github.com/HKUDS/DeepTutor/issues/1829) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1830 | PR | [fix(session): release admission leases after preference failures](https://github.com/HKUDS/DeepTutor/pull/1830) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1831 | Issue | [[Bug]: New turn admission can reopen a closed runtime](https://github.com/HKUDS/DeepTutor/issues/1831) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1832 | PR | [fix(session): keep shutdown closed after managed-update recovery](https://github.com/HKUDS/DeepTutor/pull/1832) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1833 | Issue | [[Bug]: PocketBase message IDs crash context and source lineage construction](https://github.com/HKUDS/DeepTutor/issues/1833) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1834 | PR | [fix(session): preserve opaque PocketBase message cursors](https://github.com/HKUDS/DeepTutor/pull/1834) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1835 | Issue | [[Bug]: Failed skill replacement removes the previous installed version](https://github.com/HKUDS/DeepTutor/issues/1835) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1836 | PR | [fix(skills): restore installed skills after replacement failure](https://github.com/HKUDS/DeepTutor/pull/1836) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1837 | Issue | [[Bug]: Queued memory cancellation leaves the run active](https://github.com/HKUDS/DeepTutor/issues/1837) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1838 | PR | [fix(memory): finalize runs cancelled before execution](https://github.com/HKUDS/DeepTutor/pull/1838) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1839 | Issue | [[Bug]: Later memory audit chunks can edit the wrong entries](https://github.com/HKUDS/DeepTutor/issues/1839) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1840 | PR | [fix(memory): anchor audit edits to the original document view](https://github.com/HKUDS/DeepTutor/pull/1840) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1841 | Issue | [[Bug]: CLI output pumping drops JSONL frames larger than 64 KiB](https://github.com/HKUDS/DeepTutor/issues/1841) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1842 | PR | [fix(subagent): read oversized JSONL frames without truncation](https://github.com/HKUDS/DeepTutor/pull/1842) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1843 | Issue | [[Bug]: Cancelled CLI model and version probes leave child processes running](https://github.com/HKUDS/DeepTutor/issues/1843) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1844 | PR | [fix(subagent): reap cancelled CLI probe processes](https://github.com/HKUDS/DeepTutor/pull/1844) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1845 | Issue | [[Bug]: Stopping a Partner leaves detached web-turn tasks running](https://github.com/HKUDS/DeepTutor/issues/1845) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1846 | PR | [fix(partners): cancel live web turns when stopping a partner](https://github.com/HKUDS/DeepTutor/pull/1846) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1847 | Issue | [[Bug]: Customized legacy persona text is overwritten as an old seed](https://github.com/HKUDS/DeepTutor/issues/1847) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1848 | PR | [fix(partners): preserve customized legacy persona text](https://github.com/HKUDS/DeepTutor/pull/1848) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1849 | Issue | [[Bug]: RAG evaluation reports native search failures as empty results](https://github.com/HKUDS/DeepTutor/issues/1849) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1850 | PR | [fix(rag): report native retrieval errors in evaluation](https://github.com/HKUDS/DeepTutor/pull/1850) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1851 | Issue | [[Bug]: DingTalk Matrix and Mochat delivery failures bypass retries](https://github.com/HKUDS/DeepTutor/issues/1851) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1852 | PR | [fix(channels): propagate failed message deliveries to retry](https://github.com/HKUDS/DeepTutor/pull/1852) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1853 | Issue | [[Bug]: Obsidian backlinks omit qualified wikilinks and confuse duplicate names](https://github.com/HKUDS/DeepTutor/issues/1853) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1854 | PR | [fix(obsidian): resolve backlinks using canonical note paths](https://github.com/HKUDS/DeepTutor/pull/1854) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1855 | Issue | [[Bug]: Book source health misses deletion of the last source document](https://github.com/HKUDS/DeepTutor/issues/1855) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1856 | PR | [fix(book): detect drift when a knowledge source becomes empty](https://github.com/HKUDS/DeepTutor/pull/1856) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1857 | Issue | [[Bug]: Refusing knowledge-base deletion still removes MarginNote data](https://github.com/HKUDS/DeepTutor/issues/1857) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1858 | PR | [fix(knowledge): confirm before deleting MarginNote state](https://github.com/HKUDS/DeepTutor/pull/1858) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1859 | Issue | [[Bug]: Playback discovery overwrites progress saved during its network request](https://github.com/HKUDS/DeepTutor/issues/1859) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1860 | PR | [fix(video): preserve learning updates during playback discovery](https://github.com/HKUDS/DeepTutor/pull/1860) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1861 | Issue | [[Bug]: Denied browser storage access crashes Markdown note editing](https://github.com/HKUDS/DeepTutor/issues/1861) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1862 | PR | [fix(web): keep note editing usable when browser storage is denied](https://github.com/HKUDS/DeepTutor/pull/1862) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1863 | Issue | [[Bug]: Unsafe citation ranges can freeze reading rendering](https://github.com/HKUDS/DeepTutor/issues/1863) | closed | 2026-10-08 | 2026-10-15 | 0 |
| 1864 | PR | [fix(reading): reject unsafe citation range integers](https://github.com/HKUDS/DeepTutor/pull/1864) | closed | 2026-10-08 | 2026-10-15 | 0 |
| 1865 | Issue | [[Bug]: Failed annotation deletion replaces newer or other-document annotations](https://github.com/HKUDS/DeepTutor/issues/1865) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1866 | PR | [fix(reading): restore failed annotation deletions within their scope](https://github.com/HKUDS/DeepTutor/pull/1866) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1867 | Issue | [[Bug]: Literal thinking tags inside streaming code fences become reasoning cards](https://github.com/HKUDS/DeepTutor/issues/1867) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1868 | PR | [fix(web): preserve literal thinking tags inside Markdown fences](https://github.com/HKUDS/DeepTutor/pull/1868) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1869 | Issue | [[Bug]: Session day groups are wrong after spring daylight saving](https://github.com/HKUDS/DeepTutor/issues/1869) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1870 | PR | [fix(web): group sessions by local calendar days across DST](https://github.com/HKUDS/DeepTutor/pull/1870) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1871 | Issue | [[Bug]: Explicit empty MCP selection is treated as inherited resources](https://github.com/HKUDS/DeepTutor/issues/1871) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1872 | PR | [fix(web): distinguish inherited and empty MCP selections](https://github.com/HKUDS/DeepTutor/pull/1872) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1873 | Issue | [[Bug]: Streaming message updates cancel an already handled settings refresh](https://github.com/HKUDS/DeepTutor/issues/1873) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1874 | PR | [fix(web): preserve settings refresh across streaming updates](https://github.com/HKUDS/DeepTutor/pull/1874) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1875 | Issue | [[Bug]: Mermaid cannot recover when its source is corrected after failure](https://github.com/HKUDS/DeepTutor/issues/1875) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1876 | PR | [fix(web): retry Mermaid rendering after an initial error](https://github.com/HKUDS/DeepTutor/pull/1876) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1877 | Issue | [[Bug]: Settled activity marks keep hidden canvas animations running](https://github.com/HKUDS/DeepTutor/issues/1877) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1878 | PR | [fix(web): pause retained activity orbs after work settles](https://github.com/HKUDS/DeepTutor/pull/1878) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1879 | Issue | [[Bug]: Strict-mode replay cancels automatic handoff sign-in permanently](https://github.com/HKUDS/DeepTutor/issues/1879) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1880 | PR | [fix(web): start handoff exchange after strict-mode timer replay](https://github.com/HKUDS/DeepTutor/pull/1880) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1881 | Issue | [[Bug]: Enter bypasses configuration confirmation and blocks paused-turn replies](https://github.com/HKUDS/DeepTutor/issues/1881) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1882 | PR | [fix(web): apply composer admission checks to Enter submissions](https://github.com/HKUDS/DeepTutor/pull/1882) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1883 | Issue | [[Bug]: Failed Co-Writer draft migration deletes the only saved copy](https://github.com/HKUDS/DeepTutor/issues/1883) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1884 | PR | [fix(web): preserve legacy drafts when storage migration fails](https://github.com/HKUDS/DeepTutor/pull/1884) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1885 | Issue | [[Bug]: Changing Co-Writer documents saves the previous text under the new ID](https://github.com/HKUDS/DeepTutor/issues/1885) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1886 | PR | [fix(web): isolate Co-Writer editing state by document identity](https://github.com/HKUDS/DeepTutor/pull/1886) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1887 | Issue | [[Bug]: Leaving a reading workspace restarts polling after pending requests finish](https://github.com/HKUDS/DeepTutor/issues/1887) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1888 | PR | [fix(web): stop reading workspace polling after effect cleanup](https://github.com/HKUDS/DeepTutor/pull/1888) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1889 | Issue | [[Bug]: Closing an in-flight notebook save leaves Save disabled on reopen](https://github.com/HKUDS/DeepTutor/issues/1889) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1890 | PR | [fix(web): clear notebook save state after cancellation](https://github.com/HKUDS/DeepTutor/pull/1890) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1891 | Issue | [[Bug]: Memory editor reports Saved after HTTP write failure](https://github.com/HKUDS/DeepTutor/issues/1891) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1892 | PR | [fix(web): retain memory edits after failed HTTP saves](https://github.com/HKUDS/DeepTutor/pull/1892) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1893 | Issue | [[Bug]: Pending onboarding responses restart polling immediately](https://github.com/HKUDS/DeepTutor/issues/1893) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1894 | PR | [fix(web): preserve channel onboarding polling intervals](https://github.com/HKUDS/DeepTutor/pull/1894) | closed | 2026-10-08 | 2026-10-08 | 1 |
| 1895 | Issue | [[Bug]: Failed persona loading enables an empty overwrite](https://github.com/HKUDS/DeepTutor/issues/1895) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1896 | PR | [fix(web): block persona saves after a failed initial read](https://github.com/HKUDS/DeepTutor/pull/1896) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1897 | PR | [feat(search): send X-Pplx-Integration header to Perplexity](https://github.com/HKUDS/DeepTutor/pull/1897) | closed | 2026-10-08 | 2026-10-18 | 0 |
| 1898 | PR | [fix(reading): unwrap backticked locator citations and split multi-locator links](https://github.com/HKUDS/DeepTutor/pull/1898) | closed | 2026-10-08 | 2026-10-18 | 1 |
| 1899 | PR | [fix(chat): keep knowledge base resource option accessible when empty](https://github.com/HKUDS/DeepTutor/pull/1899) | closed | 2026-10-08 | 2026-10-14 | 1 |
| 1900 | PR | [feat(learning): add Guided practice to rebuild a worked solution](https://github.com/HKUDS/DeepTutor/pull/1900) | open | 2026-10-08 | 2026-10-16 | 5 |
| 1901 | Issue | [[Enhancement]: Meaning-based visual and source-dependent assessment beyond answer aliases in Mastery Path](https://github.com/HKUDS/DeepTutor/issues/1901) | closed | 2026-10-08 | 2026-10-18 | 2 |
| 1902 | Issue | [[Enhancement]: Mastery Path lesson preparation that selects the right evidence without slowing every turn](https://github.com/HKUDS/DeepTutor/issues/1902) | closed | 2026-10-08 | 2026-10-18 | 2 |
| 1903 | Issue | [[Critical bug]: Local MinerU indexing can hang after CLI termination on Windows](https://github.com/HKUDS/DeepTutor/issues/1903) | closed | 2026-10-08 | 2026-10-18 | 2 |
| 1904 | PR | [course media syllabus](https://github.com/HKUDS/DeepTutor/pull/1904) | closed | 2026-10-09 | 2026-10-09 | 0 |
| 1906 | PR | [fix(web): add visible return from activity panel](https://github.com/HKUDS/DeepTutor/pull/1906) | closed | 2026-10-09 | 2026-10-14 | 0 |
| 1907 | Issue | [[Bug]: Usage statistics always shows "Unable to load usage statistics. Retry."](https://github.com/HKUDS/DeepTutor/issues/1907) | closed | 2026-10-09 | 2026-10-18 | 0 |
| 1908 | Issue | [[Feature Request]: Support fully customizable review frequency strategies](https://github.com/HKUDS/DeepTutor/issues/1908) | open | 2026-10-09 | 2026-10-09 | 0 |
| 1909 | Issue | [[Bug]: History compaction counts repeated images before the request-only deduplication from #1714](https://github.com/HKUDS/DeepTutor/issues/1909) | closed | 2026-10-09 | 2026-10-18 | 2 |
| 1910 | PR | [fix(session): budget projected image replay before compaction](https://github.com/HKUDS/DeepTutor/pull/1910) | closed | 2026-10-09 | 2026-10-14 | 3 |
| 1911 | PR | [feat(providers): add onomeo as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/1911) | closed | 2026-10-10 | 2026-10-14 | 0 |
| 1912 | Issue | [[Bug]: Transient Windows file locks can abort indexing journal safety checks](https://github.com/HKUDS/DeepTutor/issues/1912) | closed | 2026-10-10 | 2026-10-18 | 2 |
| 1914 | Issue | [[Enhancement]: Optimize the retry logic after Manim generation fails](https://github.com/HKUDS/DeepTutor/issues/1914) | closed | 2026-10-10 | 2026-10-18 | 2 |
| 1915 | Issue | [[Feature Request]: You.com as a keyless search provider (free tier, optional key)](https://github.com/HKUDS/DeepTutor/issues/1915) | open | 2026-10-10 | 2026-10-10 | 0 |
| 1916 | Issue | [Request: availability of TutorBench data and evaluation harness (arXiv 2604.26962)](https://github.com/HKUDS/DeepTutor/issues/1916) | open | 2026-10-11 | 2026-10-11 | 0 |
| 1917 | PR | [feat(rag): add pluggable query rewrite layer for retrieval quality](https://github.com/HKUDS/DeepTutor/pull/1917) | closed | 2026-10-11 | 2026-10-18 | 1 |
| 1918 | Issue | [Uploading an EPUB by dragging its unpacked folder (macOS, Safari & Chrome) is rejected with "unsupported extension '.zip'" — browsers auto-zip dragged folders](https://github.com/HKUDS/DeepTutor/issues/1918) | closed | 2026-10-11 | 2026-10-18 | 1 |
| 1919 | PR | [fix: retry transient locks and decode UTF-8 when reading the indexing journal](https://github.com/HKUDS/DeepTutor/pull/1919) | closed | 2026-10-11 | 2026-10-14 | 1 |
| 1920 | Issue | [[Performance][Mastery Path] Repeated historical state inflates multi-step turns; reduce context cost without losing tutoring continuity](https://github.com/HKUDS/DeepTutor/issues/1920) | closed | 2026-10-11 | 2026-10-18 | 2 |
| 1921 | PR | [fix(reading): accept video playback time in the reading viewport](https://github.com/HKUDS/DeepTutor/pull/1921) | closed | 2026-10-11 | 2026-10-14 | 0 |
| 1922 | PR | [fix(reading): send the action the reading composer displays](https://github.com/HKUDS/DeepTutor/pull/1922) | closed | 2026-10-11 | 2026-10-18 | 0 |
| 1923 | Issue | [[Bug]: Multimodal user message is stringified when a loop directive is appended — base64 image bytes ship as prompt text (4.0M tokens, provider 400, empty answer)](https://github.com/HKUDS/DeepTutor/issues/1923) | closed | 2026-10-11 | 2026-10-18 | 2 |
| 1924 | PR | [fix(agent-loop): keep content parts when appending a loop directive](https://github.com/HKUDS/DeepTutor/pull/1924) | closed | 2026-10-11 | 2026-10-14 | 1 |
| 1925 | Issue | [[High-impact bug][Mastery Path] Lesson explanations collapse into working notes before a quiz](https://github.com/HKUDS/DeepTutor/issues/1925) | closed | 2026-10-11 | 2026-10-18 | 2 |
| 1926 | Issue | [[High impact][Mastery Path] Long tutoring sessions accumulate excessive repeated context before compaction helps](https://github.com/HKUDS/DeepTutor/issues/1926) | closed | 2026-10-11 | 2026-10-18 | 2 |
| 1927 | Issue | [[Feature Request]: Per-user API-key model providers (bring your own key) in multi-user deployments](https://github.com/HKUDS/DeepTutor/issues/1927) | open | 2026-10-11 | 2026-10-11 | 0 |
| 1928 | Issue | [RAG visual argument contract causes avoidable correction rounds (optional selectors, page/crop bounds)](https://github.com/HKUDS/DeepTutor/issues/1928) | closed | 2026-10-11 | 2026-10-18 | 2 |
| 1929 | Issue | [[Mastery Path] Reviewed atomic multi-module outline revisions to reduce repeated model context](https://github.com/HKUDS/DeepTutor/issues/1929) | closed | 2026-10-11 | 2026-10-18 | 2 |
| 1930 | PR | [test(app): lock lost-ack resend session parity behind regression tests](https://github.com/HKUDS/DeepTutor/pull/1930) | closed | 2026-10-12 | 2026-10-14 | 0 |
| 1931 | PR | [fix(rag): align tool selector contract with execution (#1928)](https://github.com/HKUDS/DeepTutor/pull/1931) | closed | 2026-10-12 | 2026-10-14 | 1 |
| 1932 | PR | [fix(mastery): revise multiple outline modules atomically (#1929)](https://github.com/HKUDS/DeepTutor/pull/1932) | closed | 2026-10-12 | 2026-10-14 | 1 |
| 1933 | Issue | [[Enhancement][Mastery Path] Durable adaptation to learner feedback about explanations and teaching pace](https://github.com/HKUDS/DeepTutor/issues/1933) | closed | 2026-10-12 | 2026-10-18 | 4 |
| 1934 | PR | [fix(mastery): keep teaching visible across interleaved tool work](https://github.com/HKUDS/DeepTutor/pull/1934) | closed | 2026-10-12 | 2026-10-14 | 0 |
| 1935 | PR | [fix(chat): preserve follow state across delayed layout changes](https://github.com/HKUDS/DeepTutor/pull/1935) | closed | 2026-10-12 | 2026-10-14 | 0 |
| 1936 | PR | [feat(mastery): retain scoped teaching feedback and strategy outcomes](https://github.com/HKUDS/DeepTutor/pull/1936) | closed | 2026-10-12 | 2026-10-18 | 0 |
| 1937 | PR | [fix(mineru): own CLI worker lifecycle and avoid pipe-related hangs](https://github.com/HKUDS/DeepTutor/pull/1937) | closed | 2026-10-12 | 2026-10-18 | 0 |
| 1938 | PR | [feat(mastery): bound replay history while retaining exact tutoring recall](https://github.com/HKUDS/DeepTutor/pull/1938) | closed | 2026-10-12 | 2026-10-18 | 0 |
| 1939 | PR | [feat(mastery): review outline batches before atomic commit (builds on #1932)](https://github.com/HKUDS/DeepTutor/pull/1939) | closed | 2026-10-12 | 2026-10-18 | 0 |
| 1940 | Issue | [PLEASE START HERE [Tracking] Mastery Path reliability: contributions, evidence and remaining teaching-workflow gaps](https://github.com/HKUDS/DeepTutor/issues/1940) | open | 2026-10-12 | 2026-10-15 | 0 |
| 1941 | Issue | [[Bug][High impact][Mastery Path] Grouped practice falls back to unregistered prose while an older question remains active](https://github.com/HKUDS/DeepTutor/issues/1941) | closed | 2026-10-12 | 2026-10-18 | 1 |
| 1942 | PR | [fix(reading): accept browser-zipped EPUB folder uploads](https://github.com/HKUDS/DeepTutor/pull/1942) | closed | 2026-10-12 | 2026-10-14 | 0 |
| 1943 | PR | [feat(mastery): independently graded question groups with safe submission recovery](https://github.com/HKUDS/DeepTutor/pull/1943) | closed | 2026-10-12 | 2026-10-18 | 0 |
| 1944 | Issue | [[Bug][High impact] Cancelled/unsent messages silently fail edit-and-send and lack per-message recovery actions](https://github.com/HKUDS/DeepTutor/issues/1944) | closed | 2026-10-12 | 2026-10-18 | 1 |
| 1945 | PR | [fix(chat): recover edited and unsent submissions without duplicate admission](https://github.com/HKUDS/DeepTutor/pull/1945) | closed | 2026-10-12 | 2026-10-18 | 0 |
| 1946 | Issue | [[Bug] Schema-valid null arguments are rejected as missing before tool dispatch](https://github.com/HKUDS/DeepTutor/issues/1946) | closed | 2026-10-12 | 2026-10-18 | 1 |
| 1947 | Issue | [[Mastery Path] Reorder existing modules without rebuilding or losing learning state](https://github.com/HKUDS/DeepTutor/issues/1947) | closed | 2026-10-12 | 2026-10-18 | 1 |
| 1948 | PR | [fix(agentic): accept explicitly supplied schema-valid null arguments](https://github.com/HKUDS/DeepTutor/pull/1948) | closed | 2026-10-12 | 2026-10-14 | 0 |
| 1949 | Issue | [[Mastery Path] Teaching state gets ahead of delivery; feedback and partial answers do not reliably guide the next lesson](https://github.com/HKUDS/DeepTutor/issues/1949) | closed | 2026-10-12 | 2026-10-18 | 1 |
| 1950 | PR | [fix: close cron and web-source SQLite connections](https://github.com/HKUDS/DeepTutor/pull/1950) | closed | 2026-10-13 | 2026-10-14 | 0 |
| 1951 | Issue | [[Bug]: Gemini connection is offered for Text-to-Speech, but Gemini TTS models (e.g. gemini-3.8-flash-tts) cannot work — preview fails with 502](https://github.com/HKUDS/DeepTutor/issues/1951) | closed | 2026-10-13 | 2026-10-18 | 1 |
| 1952 | PR | [fix(mastery): bind teaching records to visible delivered explanation](https://github.com/HKUDS/DeepTutor/pull/1952) | closed | 2026-10-13 | 2026-10-18 | 0 |
| 1953 | PR | [feat(mastery): evaluate source-bound answers semantically with repairable uncertainty](https://github.com/HKUDS/DeepTutor/pull/1953) | closed | 2026-10-13 | 2026-10-18 | 0 |
| 1954 | PR | [fix(mastery): make source preparation demand-driven and preserve partial teaching](https://github.com/HKUDS/DeepTutor/pull/1954) | closed | 2026-10-13 | 2026-10-18 | 0 |
| 1955 | Issue | [[Bug][Mastery Path] Answer-key exposure and incomplete delivery undermine source-backed practice](https://github.com/HKUDS/DeepTutor/issues/1955) | closed | 2026-10-13 | 2026-10-18 | 1 |
| 1956 | PR | [fix(runtime): persist explicit incomplete capability results as failed turns](https://github.com/HKUDS/DeepTutor/pull/1956) | closed | 2026-10-13 | 2026-10-18 | 0 |
| 1957 | PR | [fix(mastery): protect answer sources and finish repaired assessment delivery](https://github.com/HKUDS/DeepTutor/pull/1957) | closed | 2026-10-13 | 2026-10-18 | 0 |
| 1958 | PR | [fix: keep a chat turn's prompt-cache prefix stable across turns](https://github.com/HKUDS/DeepTutor/pull/1958) | closed | 2026-10-13 | 2026-10-18 | 0 |
| 1959 | PR | [fix(voice): add native Gemini TTS adapter for generateContent speech](https://github.com/HKUDS/DeepTutor/pull/1959) | closed | 2026-10-14 | 2026-10-14 | 0 |
| 1961 | Issue | [[Bug]:In-turn context-window guard counts only message `content`, so it never trims a request that already exceeds the window](https://github.com/HKUDS/DeepTutor/issues/1961) | closed | 2026-10-14 | 2026-10-18 | 1 |
| 1962 | PR | [fix(agents): count the full request in the context-window guard](https://github.com/HKUDS/DeepTutor/pull/1962) | closed | 2026-10-14 | 2026-10-18 | 0 |
| 1963 | PR | [perf(documents): bound an inlined raster's long edge before admission](https://github.com/HKUDS/DeepTutor/pull/1963) | closed | 2026-10-14 | 2026-10-18 | 1 |
| 1964 | PR | [test: stabilize shared transport and browser audit contracts](https://github.com/HKUDS/DeepTutor/pull/1964) | closed | 2026-10-14 | 2026-10-16 | 0 |
| 1965 | PR | [perf(reading): load Markdown export only when requested](https://github.com/HKUDS/DeepTutor/pull/1965) | closed | 2026-10-14 | 2026-10-16 | 0 |
| 1966 | Issue | [Free hosted DeepTutor for your users: 100 cloud computers, README link request](https://github.com/HKUDS/DeepTutor/issues/1966) | open | 2026-10-15 | 2026-10-15 | 0 |
| 1967 | PR | [fix(voice): surface the HTTP status when a preview error body is not JSON](https://github.com/HKUDS/DeepTutor/pull/1967) | closed | 2026-10-15 | 2026-10-18 | 0 |
| 1968 | Issue | [[Bug]: deep_solve's context checkpoint deletes the remaining plan the model is following](https://github.com/HKUDS/DeepTutor/issues/1968) | closed | 2026-10-15 | 2026-10-18 | 1 |
| 1969 | PR | [fix(solve): keep the remaining plan in view after each step fold](https://github.com/HKUDS/DeepTutor/pull/1969) | closed | 2026-10-15 | 2026-10-18 | 1 |
| 1970 | PR | [fix(chat): reconcile and dismiss browser-local unsent submissions](https://github.com/HKUDS/DeepTutor/pull/1970) | closed | 2026-10-15 | 2026-10-18 | 0 |
| 1971 | Issue | [Mastery Path teaching feels clunky: fragmented lessons, rigid progression and costly orchestration](https://github.com/HKUDS/DeepTutor/issues/1971) | open | 2026-10-15 | 2026-10-15 | 0 |
| 1972 | Issue | [The interface feels clunky: unstable interactions, unclear progress and crowded navigation](https://github.com/HKUDS/DeepTutor/issues/1972) | open | 2026-10-15 | 2026-10-15 | 0 |
| 1973 | Issue | [[User experience] I came to study cell biology; repeated failures made DeepTutor impractical to use](https://github.com/HKUDS/DeepTutor/issues/1973) | open | 2026-10-15 | 2026-10-15 | 0 |
| 1974 | PR | [fix: install tzdata so named timezones resolve on Windows](https://github.com/HKUDS/DeepTutor/pull/1974) | closed | 2026-10-15 | 2026-10-18 | 0 |
| 1975 | Issue | [[Bug]: Responses tool conversion silently drops explicit strict=true/false](https://github.com/HKUDS/DeepTutor/issues/1975) | closed | 2026-10-16 | 2026-10-18 | 1 |
| 1976 | Issue | [[Dev] Audit and repair 1,000 source-traceable public mathematics questions](https://github.com/HKUDS/DeepTutor/issues/1976) | open | 2026-10-16 | 2026-10-16 | 0 |
| 1977 | PR | [Feat/encore memory knowledge direct urls](https://github.com/HKUDS/DeepTutor/pull/1977) | closed | 2026-10-16 | 2026-10-16 | 2 |
| 1978 | PR | [fix(llm): keep an explicit strict setting when converting tools for the Responses API](https://github.com/HKUDS/DeepTutor/pull/1978) | closed | 2026-10-16 | 2026-10-18 | 0 |
| 1979 | Issue | [[Feature Request]: Optional application-layer security for the backend (attack screening, automatic bans, per-route policies) with fastapi-guard](https://github.com/HKUDS/DeepTutor/issues/1979) | closed | 2026-10-16 | 2026-10-18 | 1 |
| 1980 | PR | [feat(api): optional application-layer security with fastapi-guard (off by default)](https://github.com/HKUDS/DeepTutor/pull/1980) | closed | 2026-10-16 | 2026-10-18 | 0 |
| 1982 | Issue | [One failed document aborts the entire KB rebuild — request for per-document failure tolerance and long-document timeout handling](https://github.com/HKUDS/DeepTutor/issues/1982) | closed | 2026-10-17 | 2026-10-18 | 2 |
| 1983 | Issue | [KB reindex loses all chunking/embedding progress on interruption — request for checkpoint/resume in the embedding stage](https://github.com/HKUDS/DeepTutor/issues/1983) | open | 2026-10-17 | 2026-10-17 | 0 |
| 1984 | Issue | [[Bug][Windows][v1.6.14] Settings Apply HTTP 500 at model_catalog.json os.replace (WinSW / LocalService deployment)](https://github.com/HKUDS/DeepTutor/issues/1984) | closed | 2026-10-17 | 2026-10-18 | 1 |
| 1985 | PR | [fix(doctor): convert resolved LLM config before the online probe](https://github.com/HKUDS/DeepTutor/pull/1985) | closed | 2026-10-18 | 2026-10-18 | 0 |
| 1986 | PR | [fix: decode fetched pages with their declared <meta> charset](https://github.com/HKUDS/DeepTutor/pull/1986) | closed | 2026-10-18 | 2026-10-18 | 0 |
| 1987 | Issue | [Learner accounts get 403 on /api/dashboard/learning-index — Personalized Learning page fails to load](https://github.com/HKUDS/DeepTutor/issues/1987) | closed | 2026-10-18 | 2026-10-18 | 1 |
| 1988 | Issue | [feat(learner): record effective reading time and let guardians view a learner's practice page](https://github.com/HKUDS/DeepTutor/issues/1988) | open | 2026-10-18 | 2026-10-18 | 0 |
| 1989 | Issue | [[Feature Request]:Clarify and support MinerU 4.x local parsing compatibility](https://github.com/HKUDS/DeepTutor/issues/1989) | open | 2026-10-18 | 2026-10-18 | 0 |
| 1990 | Issue | [[Bug]: Read-aloud on long assistant messages synthesizes the full answer text (up to max_input_chars), so playback takes extremely long to start](https://github.com/HKUDS/DeepTutor/issues/1990) | open | 2026-10-19 | 2026-10-19 | 0 |
| 1991 | Issue | [[Bug]: Codex OAuth inference omits session-id and changes cache affinity when summaries update](https://github.com/HKUDS/DeepTutor/issues/1991) | open | 2026-10-19 | 2026-10-19 | 0 |
| 1992 | PR | [fix(llm): scope Codex prompt cache key to the conversation and send session-id](https://github.com/HKUDS/DeepTutor/pull/1992) | closed | 2026-10-19 | 2026-10-27 | 0 |
| 1993 | Issue | [[Bug]:精通之路单选题选项在作答卡片上被打乱后，回传给导师的「字母答案」与学习者实际点击的选项内容不一致](https://github.com/HKUDS/DeepTutor/issues/1993) | open | 2026-10-19 | 2026-10-19 | 0 |
| 1994 | PR | [fix: render Markdown in partner conversation archives](https://github.com/HKUDS/DeepTutor/pull/1994) | closed | 2026-10-19 | 2026-10-27 | 0 |
| 1995 | PR | [feat: render Telegram replies with native rich messages](https://github.com/HKUDS/DeepTutor/pull/1995) | open | 2026-10-19 | 2026-10-27 | 0 |
| 1996 | PR | [feat: choose reasoning effort per conversation](https://github.com/HKUDS/DeepTutor/pull/1996) | closed | 2026-10-19 | 2026-10-19 | 0 |
| 1997 | PR | [fix(rag): wrap maybe_rewrite in try/except for fail-open safety](https://github.com/HKUDS/DeepTutor/pull/1997) | closed | 2026-10-19 | 2026-10-19 | 0 |
| 1998 | PR | [fix(rag): wrap maybe_rewrite in try/except for fail-open safety](https://github.com/HKUDS/DeepTutor/pull/1998) | closed | 2026-10-19 | 2026-10-27 | 0 |
| 1999 | PR | [feat(sync): 端云同步路由（分域分权 / 幂等 / 冲突留档 / 大文件通道）](https://github.com/HKUDS/DeepTutor/pull/1999) | open | 2026-10-19 | 2026-10-27 | 0 |
| 2000 | PR | [fix(mastery): show the picked option's text next to its letter in the grade seed](https://github.com/HKUDS/DeepTutor/pull/2000) | closed | 2026-10-20 | 2026-10-27 | 0 |
| 2001 | Issue | [[Bug]:Development Docker target can rebuild and discard the Next.js production output](https://github.com/HKUDS/DeepTutor/issues/2001) | open | 2026-10-20 | 2026-10-20 | 1 |
| 2002 | PR | [fix(docker): skip production frontend build in development](https://github.com/HKUDS/DeepTutor/pull/2002) | open | 2026-10-20 | 2026-10-27 | 0 |
| 2003 | Issue | [[Feature Request]:Add an in-app Access Control settings page](https://github.com/HKUDS/DeepTutor/issues/2003) | open | 2026-10-20 | 2026-10-20 | 0 |
| 2004 | PR | [feat: recommend MiniMax Flash and map current reasoning controls](https://github.com/HKUDS/DeepTutor/pull/2004) | closed | 2026-10-20 | 2026-10-27 | 0 |
| 2005 | Issue | [[Bug]: Hybrid retrieval BM25 build OOM-kills the backend on memory-constrained hosts (KB re-index fails with "persistence verification")](https://github.com/HKUDS/DeepTutor/issues/2005) | open | 2026-10-21 | 2026-10-21 | 1 |
| 2006 | PR | [fix(rag): decode BOM-marked UTF-8, Windows-1252 and UTF-16 text](https://github.com/HKUDS/DeepTutor/pull/2006) | open | 2026-10-21 | 2026-10-21 | 0 |
| 2007 | PR | [fix(documents): read a DOCX text box and moved text once](https://github.com/HKUDS/DeepTutor/pull/2007) | open | 2026-10-21 | 2026-10-21 | 0 |
| 2008 | PR | [fix(documents): keep empty PPTX table cells in their columns](https://github.com/HKUDS/DeepTutor/pull/2008) | open | 2026-10-21 | 2026-10-21 | 0 |
| 2009 | PR | [fix: skip BM25 construction for vector-only indexing](https://github.com/HKUDS/DeepTutor/pull/2009) | open | 2026-10-21 | 2026-10-21 | 0 |
| 2010 | PR | [feat(mcp): add Keenable web search to the curated catalog](https://github.com/HKUDS/DeepTutor/pull/2010) | open | 2026-10-21 | 2026-10-21 | 0 |
| 2011 | PR | [fix(voice): cap manual read-aloud excerpts](https://github.com/HKUDS/DeepTutor/pull/2011) | open | 2026-10-21 | 2026-10-25 | 0 |
| 2012 | Issue | [[Bug]: Mastery Path review mode fails to generate questions after updating to v1.6.15](https://github.com/HKUDS/DeepTutor/issues/2012) | open | 2026-10-21 | 2026-10-21 | 0 |
| 2013 | PR | [feat: animated video lessons rendered live with Remotion](https://github.com/HKUDS/DeepTutor/pull/2013) | closed | 2026-10-21 | 2026-10-26 | 0 |
| 2014 | PR | [feat(voice): add Microsoft Edge as a TTS provider](https://github.com/HKUDS/DeepTutor/pull/2014) | closed | 2026-10-21 | 2026-10-26 | 0 |
| 2015 | Issue | [[Bug]: deep_solve: a second solve_plan call wipes step progress and bypasses the replan budget](https://github.com/HKUDS/DeepTutor/issues/2015) | closed | 2026-10-21 | 2026-10-28 | 0 |
| 2016 | PR | [fix(solve): refuse a second solve_plan so replans stay budgeted](https://github.com/HKUDS/DeepTutor/pull/2016) | closed | 2026-10-21 | 2026-10-27 | 0 |
| 2017 | PR | [feat(learner): record reading time and guardian practice view (#1988)](https://github.com/HKUDS/DeepTutor/pull/2017) | open | 2026-10-21 | 2026-10-22 | 0 |
| 2018 | PR | [fix: PDF uploads in chat dont get easily read in next message in same chat because of tool error](https://github.com/HKUDS/DeepTutor/pull/2018) | open | 2026-10-21 | 2026-10-27 | 0 |
| 2019 | PR | [fix: keep mastery review within the mastery gate](https://github.com/HKUDS/DeepTutor/pull/2019) | closed | 2026-10-22 | 2026-10-27 | 0 |
| 2020 | Issue | [[Bug]: Chat "Play aloud" does not play on iOS browsers (audio.play() called after TTS fetch, outside the user gesture)](https://github.com/HKUDS/DeepTutor/issues/2020) | open | 2026-10-22 | 2026-10-22 | 0 |
| 2021 | PR | [fix(chat): unlock iOS reply playback (#2020)](https://github.com/HKUDS/DeepTutor/pull/2021) | closed | 2026-10-22 | 2026-10-27 | 0 |
| 2022 | Issue | [[Question]how I can make from broke, zero $ crypto, too at least few hundred dollars a month](https://github.com/HKUDS/DeepTutor/issues/2022) | open | 2026-10-22 | 2026-10-22 | 0 |
| 2023 | Issue | [[EduHub]:why AI if it's Soo good don't help me financially?](https://github.com/HKUDS/DeepTutor/issues/2023) | open | 2026-10-22 | 2026-10-22 | 0 |
| 2024 | PR | [docs(storage): document local persistence layout (#612)](https://github.com/HKUDS/DeepTutor/pull/2024) | closed | 2026-10-22 | 2026-10-27 | 0 |
| 2025 | PR | [feat(search): add You.com provider (#1915)](https://github.com/HKUDS/DeepTutor/pull/2025) | closed | 2026-10-22 | 2026-10-28 | 0 |
| 2026 | PR | [fix(cli): budget reasoning model probes (#1220)](https://github.com/HKUDS/DeepTutor/pull/2026) | closed | 2026-10-22 | 2026-10-28 | 1 |
| 2027 | PR | [fix(rag): resume embedding checkpoints (#1983)](https://github.com/HKUDS/DeepTutor/pull/2027) | closed | 2026-10-22 | 2026-10-27 | 0 |
| 2028 | PR | [feat(learning): add mastery review strategies (#1908)](https://github.com/HKUDS/DeepTutor/pull/2028) | closed | 2026-10-22 | 2026-10-28 | 0 |
| 2029 | PR | [fix(cron): keep server-local cron times on the wall clock across DST](https://github.com/HKUDS/DeepTutor/pull/2029) | closed | 2026-10-23 | 2026-10-28 | 0 |
| 2030 | Issue | [[Bug]:性能问题，精通之路进入会话加载时间比较长，需要优化一下加载时间](https://github.com/HKUDS/DeepTutor/issues/2030) | open | 2026-10-23 | 2026-10-26 | 1 |
| 2031 | Issue | [[Bug]:?dt_workspace=](https://github.com/HKUDS/DeepTutor/issues/2031) | open | 2026-10-23 | 2026-10-23 | 0 |
| 2032 | Issue | [[Bug]: Mastery history recursively re-archives read_source results and grows to millions of characters (v1.6.15)](https://github.com/HKUDS/DeepTutor/issues/2032) | closed | 2026-10-23 | 2026-10-28 | 1 |
| 2033 | PR | [fix(mastery): prevent recursive history archive growth](https://github.com/HKUDS/DeepTutor/pull/2033) | closed | 2026-10-23 | 2026-10-27 | 4 |
| 2034 | Issue | [[Bug]: Single-worker backend restart leaves turns running until a new submission; UI remains in Exploring](https://github.com/HKUDS/DeepTutor/issues/2034) | closed | 2026-10-23 | 2026-10-28 | 0 |
| 2035 | PR | [fix(runtime): recover orphaned turns after worker restart](https://github.com/HKUDS/DeepTutor/pull/2035) | closed | 2026-10-23 | 2026-10-27 | 0 |
| 2036 | Issue | [[Bug]: Figures from source-page presentation / generated images never appear where they are explained (stack at end of reply or invisible)](https://github.com/HKUDS/DeepTutor/issues/2036) | open | 2026-10-23 | 2026-10-23 | 0 |
| 2037 | Issue | [Image description model dropdown never lists any model: frontend filters on `supports_vision`, backend never sends it](https://github.com/HKUDS/DeepTutor/issues/2037) | open | 2026-10-23 | 2026-10-23 | 0 |
| 2038 | PR | [fix(settings): expose effective vision support in llm-options](https://github.com/HKUDS/DeepTutor/pull/2038) | closed | 2026-10-23 | 2026-10-23 | 1 |
| 2039 | PR | [fix(settings): let a declared vision model drive image description](https://github.com/HKUDS/DeepTutor/pull/2039) | closed | 2026-10-23 | 2026-10-27 | 0 |
| 2040 | PR | [fix(rag): keep a failing caption group from aborting the ingest](https://github.com/HKUDS/DeepTutor/pull/2040) | closed | 2026-10-23 | 2026-10-27 | 0 |
| 2041 | Issue | [[Bug]:kb create --docs-dir silently overwrites same-named documents and still reports success](https://github.com/HKUDS/DeepTutor/issues/2041) | open | 2026-10-24 | 2026-10-28 | 1 |
| 2042 | PR | [fix(session): bound PocketBase latest-message reads](https://github.com/HKUDS/DeepTutor/pull/2042) | closed | 2026-10-24 | 2026-10-28 | 0 |
| 2043 | PR | [test(parsing): stop racing init's reaping of a killed MinerU child](https://github.com/HKUDS/DeepTutor/pull/2043) | closed | 2026-10-24 | 2026-10-24 | 1 |
| 2044 | PR | [Feature/practice qti support](https://github.com/HKUDS/DeepTutor/pull/2044) | open | 2026-10-24 | 2026-10-29 | 0 |
| 2045 | PR | [fix(knowledge): keep same-named documents when creating a KB](https://github.com/HKUDS/DeepTutor/pull/2045) | closed | 2026-10-24 | 2026-10-27 | 0 |
| 2046 | PR | [test: stabilize device credential timing across UTC midnight](https://github.com/HKUDS/DeepTutor/pull/2046) | closed | 2026-10-24 | 2026-10-27 | 0 |
| 2047 | Issue | [[Bug] Mastery outline preview/commit rejects unused placeholder arguments with Codex OAuth](https://github.com/HKUDS/DeepTutor/issues/2047) | open | 2026-10-25 | 2026-10-25 | 0 |
| 2048 | PR | [feat(providers): add Runcrate as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/2048) | closed | 2026-10-25 | 2026-10-28 | 0 |
| 2049 | Issue | [[Feature Request]: Let the chat agent read a notebook record's full body and append to an existing record](https://github.com/HKUDS/DeepTutor/issues/2049) | open | 2026-10-25 | 2026-10-25 | 0 |
| 2050 | PR | [feat: manage generated output files](https://github.com/HKUDS/DeepTutor/pull/2050) | closed | 2026-10-25 | 2026-10-28 | 0 |
| 2051 | PR | [fix(mastery): read idle placeholder arguments as omission (#2047)](https://github.com/HKUDS/DeepTutor/pull/2051) | closed | 2026-10-25 | 2026-10-27 | 0 |
| 2052 | PR | [feat(tools): read a notebook record in full, and append to it](https://github.com/HKUDS/DeepTutor/pull/2052) | closed | 2026-10-25 | 2026-10-27 | 1 |
| 2053 | Issue | [[Bug]:「资源」浮层向下溢出，窗口最大化时不可见](https://github.com/HKUDS/DeepTutor/issues/2053) | open | 2026-10-26 | 2026-10-28 | 1 |
| 2054 | Issue | [[Bug]:性能问题，首次打开沉浸式阅读会话的eupb图书是同步阻塞的，耗时很长](https://github.com/HKUDS/DeepTutor/issues/2054) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2055 | Issue | [[Bug] Immersive PDF reader omits text requiring external CMaps (missing cMapUrl and packaged assets)](https://github.com/HKUDS/DeepTutor/issues/2055) | closed | 2026-10-26 | 2026-10-29 | 1 |
| 2056 | PR | [fix(web): package and configure PDF.js CMaps for reader](https://github.com/HKUDS/DeepTutor/pull/2056) | closed | 2026-10-26 | 2026-10-27 | 0 |
| 2057 | Issue | [rfc(memory): evaluate layered memory against raw-history RAG](https://github.com/HKUDS/DeepTutor/issues/2057) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2058 | PR | [fix(textbook_struct): keep two-char 单元 chapter token intact](https://github.com/HKUDS/DeepTutor/pull/2058) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2059 | PR | [fix(config): stop chat-settings read from corrupting shipped defaults](https://github.com/HKUDS/DeepTutor/pull/2059) | closed | 2026-10-26 | 2026-10-27 | 0 |
| 2060 | PR | [fix(plugins): dedupe manifest dependencies by PEP 503 canonical name](https://github.com/HKUDS/DeepTutor/pull/2060) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2061 | PR | [fix(co_writer): don't crash DOCX export on a literal NUL in Markdown](https://github.com/HKUDS/DeepTutor/pull/2061) | closed | 2026-10-26 | 2026-10-27 | 0 |
| 2062 | PR | [fix(search): don't let flagged long references bypass Moderation](https://github.com/HKUDS/DeepTutor/pull/2062) | closed | 2026-10-26 | 2026-10-27 | 0 |
| 2063 | PR | [fix(learning): resolve 'lesson N' by rank, not 0-based order value](https://github.com/HKUDS/DeepTutor/pull/2063) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2064 | PR | [fix(visualizers): normalize ids in lifecycle mutators like get()](https://github.com/HKUDS/DeepTutor/pull/2064) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2065 | PR | [fix(api): strip control chars from Content-Disposition ASCII fallback](https://github.com/HKUDS/DeepTutor/pull/2065) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2066 | PR | [fix(rag): strip only list markers from generated queries](https://github.com/HKUDS/DeepTutor/pull/2066) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2067 | PR | [fix(storage): escape LIKE wildcards in file library search](https://github.com/HKUDS/DeepTutor/pull/2067) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2068 | PR | [fix(textbook_struct): keep the higher-page chapter hit when deduping](https://github.com/HKUDS/DeepTutor/pull/2068) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2069 | PR | [fix(vision): track escapes when splitting GeoGebra command args](https://github.com/HKUDS/DeepTutor/pull/2069) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2070 | Issue | [[Bug]: Mastery Path concept objectives can never pass — every `mastery_assess` is refused as "teaching slice", so the tutor re-quizzes forever](https://github.com/HKUDS/DeepTutor/issues/2070) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2071 | PR | [feat(pageindex): index with the Task model when one is configured](https://github.com/HKUDS/DeepTutor/pull/2071) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2072 | Issue | [[Bug]: 模型正在写字的时候，界面会自动往下滚着跟随；但这套跟随会盖掉我自己的滚动——我往上滚去看前面讲过的内容，它会把我拽回底部，一直拽，读到一半的内容反复被顶走。](https://github.com/HKUDS/DeepTutor/issues/2072) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2073 | Issue | [[Bug]: Mastery Path re-poses a question the learner already answered correctly (fallback to the one source-verifiable item; focus packet can belong to another objective)](https://github.com/HKUDS/DeepTutor/issues/2073) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2074 | Issue | [[Bug]: Archived workspaces are still read by navigation indexes, logging a traceback on every poll when their folder is missing](https://github.com/HKUDS/DeepTutor/issues/2074) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2075 | Issue | [[Bug]: Exact-substring quote check rejects faithful citations (line breaks/markup differ), so mastery_quiz fails repeatedly and the tutor re-streams the same text](https://github.com/HKUDS/DeepTutor/issues/2075) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2076 | PR | [feat(search): add google-browser-scraper as a self-hosted Google provider](https://github.com/HKUDS/DeepTutor/pull/2076) | closed | 2026-10-26 | 2026-10-28 | 0 |
| 2077 | Issue | [[Bug]: share_mastery_history rewrites already-sent history (anchors the latest copy), breaking prompt-cache prefixes on every repeated state](https://github.com/HKUDS/DeepTutor/issues/2077) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2078 | Issue | [[Bug]: Agent loop bypasses OpenAICompatProvider cache_control, so Claude on OpenRouter never caches in chat/Mastery Path (0% cache reads)](https://github.com/HKUDS/DeepTutor/issues/2078) | open | 2026-10-26 | 2026-10-26 | 0 |
| 2079 | PR | [fix(video-lesson): run safely without Docker](https://github.com/HKUDS/DeepTutor/pull/2079) | closed | 2026-10-26 | 2026-10-26 | 0 |
| 2080 | PR | [fix(workspace): omit archived workspaces from navigation indexes](https://github.com/HKUDS/DeepTutor/pull/2080) | closed | 2026-10-26 | 2026-10-27 | 1 |
| 2081 | PR | [fix: Agent loop bypasses OpenAICompatProvider cache_control, so Claude on OpenRouter never caches in chat/Mastery Path (](https://github.com/HKUDS/DeepTutor/pull/2081) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2082 | PR | [fix: omit completed Anthropic thinking at durable history replay](https://github.com/HKUDS/DeepTutor/pull/2082) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2083 | PR | [feat: voice replies for the Feishu channel + pluggable transcription endpoint](https://github.com/HKUDS/DeepTutor/pull/2083) | closed | 2026-10-27 | 2026-10-27 | 1 |
| 2084 | PR | [fix(subagent): discover Claude Code models through the official SDK](https://github.com/HKUDS/DeepTutor/pull/2084) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2085 | PR | [fix(mastery): keep shared history prefixes stable for prompt caching](https://github.com/HKUDS/DeepTutor/pull/2085) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2086 | PR | [feat(workspace): add a server-side folder picker for project workspaces](https://github.com/HKUDS/DeepTutor/pull/2086) | closed | 2026-10-27 | 2026-10-28 | 0 |
| 2087 | PR | [fix(subagent): discover Claude Code models through the official SDK](https://github.com/HKUDS/DeepTutor/pull/2087) | closed | 2026-10-27 | 2026-10-28 | 0 |
| 2088 | Issue | [Chat with PDF attachment fails on zhipu/GLM: text-only fallback retry never fires (error 1210 not matched)](https://github.com/HKUDS/DeepTutor/issues/2088) | open | 2026-10-27 | 2026-10-27 | 0 |
| 2089 | PR | [fix(llm): match zhipu/GLM multimodal rejection so text-only retry fires](https://github.com/HKUDS/DeepTutor/pull/2089) | closed | 2026-10-27 | 2026-10-27 | 1 |
| 2090 | PR | [fix: Exact-substring quote check rejects faithful citations (line breaks/markup differ), so mastery_quiz fails repeatedl](https://github.com/HKUDS/DeepTutor/pull/2090) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2091 | Issue | [[Bug]: Little Tutor rejects selections that span Markdown formatting (tables, lists, bold)](https://github.com/HKUDS/DeepTutor/issues/2091) | open | 2026-10-27 | 2026-10-28 | 1 |
| 2092 | Issue | [[Feature Request]: Spanish (es) UI locale](https://github.com/HKUDS/DeepTutor/issues/2092) | open | 2026-10-27 | 2026-10-27 | 0 |
| 2093 | PR | [fix(session): allow Little Tutor selections across Markdown markup and tables](https://github.com/HKUDS/DeepTutor/pull/2093) | closed | 2026-10-27 | 2026-10-28 | 0 |
| 2094 | PR | [fix: stabilize worker recovery and repair dev contract checks](https://github.com/HKUDS/DeepTutor/pull/2094) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2095 | PR | [fix(web): stop the mastery-goal source picker from trapping the mouse wheel](https://github.com/HKUDS/DeepTutor/pull/2095) | closed | 2026-10-27 | 2026-10-28 | 3 |
| 2096 | PR | [feat: integrate modular installation with current dev](https://github.com/HKUDS/DeepTutor/pull/2096) | closed | 2026-10-27 | 2026-10-27 | 0 |
| 2097 | Issue | [[Bug]:Agent创建notebook和markdown文件之后给我链接，我一点开链接，发现page not found](https://github.com/HKUDS/DeepTutor/issues/2097) | open | 2026-10-27 | 2026-10-27 | 0 |
| 2098 | PR | [feat(calendar): export calendars as .ics files](https://github.com/HKUDS/DeepTutor/pull/2098) | closed | 2026-10-27 | 2026-10-28 | 0 |
| 2099 | PR | [feat(notes): export flashcards for Anki](https://github.com/HKUDS/DeepTutor/pull/2099) | closed | 2026-10-27 | 2026-10-28 | 0 |
| 2100 | Issue | [[Bug]: Theme never follows the OS after the first visit, and there is no System/Auto option](https://github.com/HKUDS/DeepTutor/issues/2100) | open | 2026-10-27 | 2026-10-28 | 2 |
| 2101 | Issue | [[Feature Request]: Render RTL content (Arabic, Hebrew, Persian) correctly in chat with dir=auto](https://github.com/HKUDS/DeepTutor/issues/2101) | open | 2026-10-27 | 2026-10-27 | 0 |
| 2102 | Issue | [[Feature Request]: Arabic (ar) UI locale](https://github.com/HKUDS/DeepTutor/issues/2102) | open | 2026-10-27 | 2026-10-27 | 0 |
| 2103 | PR | [fix: Mastery Path concept objectives can never pass — every `mastery_assess` is refused as "teaching slice", so the tuto](https://github.com/HKUDS/DeepTutor/pull/2103) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2104 | Issue | [[Bug]: CJK emphasis persistence repair corrupts inline code containing dollar signs](https://github.com/HKUDS/DeepTutor/issues/2104) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2105 | Issue | [[Bug]: Resend silently ignores the current model and explicit reply-language selection](https://github.com/HKUDS/DeepTutor/issues/2105) | open | 2026-10-28 | 2026-10-28 | 1 |
| 2106 | Issue | [[Bug]: Editing a persisted message silently reuses stale model and reply-language settings](https://github.com/HKUDS/DeepTutor/issues/2106) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2107 | Issue | [[Feature Request]: Configurable bounded recovery for reasoning-only output-budget exhaustion](https://github.com/HKUDS/DeepTutor/issues/2107) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2108 | PR | [fix(web): let a scrollbar drag release chat auto-follow while streaming](https://github.com/HKUDS/DeepTutor/pull/2108) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2109 | PR | [feat: add Claude Code provider backed by the Claude Agent SDK](https://github.com/HKUDS/DeepTutor/pull/2109) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2110 | Issue | [Docker image: rebuild on Node 22.23.4 (CVE-2026-111497)](https://github.com/HKUDS/DeepTutor/issues/2110) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2111 | Issue | [[Bug] chunk_with_boundary returns more than `budget` chunks whenever overlap_ratio > 0](https://github.com/HKUDS/DeepTutor/issues/2111) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2112 | PR | [fix(memory): size chunk windows by the stride overlap leaves](https://github.com/HKUDS/DeepTutor/pull/2112) | closed | 2026-10-28 | 2026-10-28 | 1 |
| 2113 | PR | [[codex] Add isolated native memory snapshot evaluation](https://github.com/HKUDS/DeepTutor/pull/2113) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2114 | PR | [test: unblock dev's red contracts (stale expectations + chat budget headroom)](https://github.com/HKUDS/DeepTutor/pull/2114) | closed | 2026-10-28 | 2026-10-28 | 4 |
| 2115 | PR | [fix: mask code and math spans in one pass before the CJK emphasis repair](https://github.com/HKUDS/DeepTutor/pull/2115) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2116 | PR | [fix(session): mask code and math spans in one pass for CJK emphasis repair](https://github.com/HKUDS/DeepTutor/pull/2116) | closed | 2026-10-28 | 2026-10-28 | 1 |
| 2117 | PR | [fix(llm): keep streamed tool calls without an index apart](https://github.com/HKUDS/DeepTutor/pull/2117) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2118 | Issue | [[Feature Request]: Show a Little Tutor entry point next to the quoted source message](https://github.com/HKUDS/DeepTutor/issues/2118) | open | 2026-10-28 | 2026-10-28 | 1 |
| 2119 | Issue | [[Bug]:Unable to select and copy PDF text in Immersive Reading mode](https://github.com/HKUDS/DeepTutor/issues/2119) | closed | 2026-10-28 | 2026-10-28 | 1 |
| 2120 | PR | [fix: preserve request identity when retrying unsent messages](https://github.com/HKUDS/DeepTutor/pull/2120) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2121 | PR | [fix(web): follow the OS theme by default and add a System option](https://github.com/HKUDS/DeepTutor/pull/2121) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2122 | PR | [fix: use the current model and reply language when editing or resending](https://github.com/HKUDS/DeepTutor/pull/2122) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2123 | Issue | [[Bug] Math Animator visual QA (VisualReviewAgent) is unreachable: enable_visual_review defaults to False and no caller passes it](https://github.com/HKUDS/DeepTutor/issues/2123) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2124 | PR | [fix(web): edited questions pick up the live model and reply language](https://github.com/HKUDS/DeepTutor/pull/2124) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2125 | PR | [fix(knowledge): reuse renamed staged documents on retry](https://github.com/HKUDS/DeepTutor/pull/2125) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2126 | PR | [Integrate reviewed October PRs with correctness and compatibility fixes](https://github.com/HKUDS/DeepTutor/pull/2126) | closed | 2026-10-28 | 2026-10-28 | 0 |
| 2127 | PR | [fix(web): keep the composer resources popover inside the viewport](https://github.com/HKUDS/DeepTutor/pull/2127) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2128 | PR | [fix: show file actions for direct exec attachments](https://github.com/HKUDS/DeepTutor/pull/2128) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2129 | Issue | [[Feature Request]: Turkish (tr) UI locale and reply language](https://github.com/HKUDS/DeepTutor/issues/2129) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2130 | Issue | [[Bug]: Memory sentence chunking misses unspaced CJK boundaries](https://github.com/HKUDS/DeepTutor/issues/2130) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2131 | PR | [fix: recognize unspaced CJK memory sentence boundaries](https://github.com/HKUDS/DeepTutor/pull/2131) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2132 | Issue | [[Bug]: Windows-1254 Turkish text files are decoded as Latin-1](https://github.com/HKUDS/DeepTutor/issues/2132) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2133 | Issue | [[Bug]: Windows-1254 Turkish text that is valid GBK is decoded as Chinese](https://github.com/HKUDS/DeepTutor/issues/2133) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2134 | Issue | [[Bug]: Inline { en, zh } UI copy shows English in every locale except Chinese](https://github.com/HKUDS/DeepTutor/issues/2134) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2135 | PR | [feat(i18n): add Turkish as an interface and reply language](https://github.com/HKUDS/DeepTutor/pull/2135) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2136 | PR | [fix(files): decode Windows-1254 text before falling back to Latin-1](https://github.com/HKUDS/DeepTutor/pull/2136) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2137 | PR | [fix: Mastery Path re-poses a question the learner already answered correctly (fallback to the one source-verifiable item](https://github.com/HKUDS/DeepTutor/pull/2137) | open | 2026-10-28 | 2026-10-28 | 0 |
| 2138 | PR | [feat(providers): add CloudGPU as an OpenAI-compatible gateway](https://github.com/HKUDS/DeepTutor/pull/2138) | open | 2026-10-29 | 2026-10-29 | 0 |
| 2139 | PR | [Fix reindex freeze on large knowledge bases (O(n^2) run-state serialization)](https://github.com/HKUDS/DeepTutor/pull/2139) | open | 2026-10-29 | 2026-10-29 | 0 |
