# GitHub activity snapshot — 2026-09-15

Retrieved at 2026-09-14T16:02:43+00:00. This is a dated snapshot, not an automatically updated dashboard.

## Scope and method

- Public PRs authored by `tiammomo`, merged from 2026-01-01 through retrieval time, excluding repositories owned by `tiammomo`.
- Enumerated every page of the GitHub GraphQL user PR connection and checked its total count, then filtered repository visibility, owner, and `mergedAt`.
- Excludes private repositories, open PRs, closed-unmerged PRs, and PRs within the personal namespace. Organization ownership does not imply the author is unaffiliated.
- Repository inventory uses every page of GitHub's public user-repositories API. Non-fork does not imply sole authorship or production readiness. Stars measure repository popularity, not contribution count.
- Checked current READMEs for RepoSteward, ModelPort, QuantPilot, and RoutePilot; their existing short profile descriptions still match. Projects were not run or benchmarked for this refresh.

## Summary

- **88 merged public PRs across 6 repositories outside the personal namespace** in 2026.
- **32 public repositories: 18 non-forks and 14 forks**. Non-forks include the profile repository and personal website.
- **76 stars across the non-fork repositories** at retrieval time.
- Since the [September 9 snapshot](github-activity-2026-09-09.md): 7 additional merged PRs, including 6 in DeerFlow and 1 in xskill-wiki.

| Repository | Merged PRs |
| --- | ---: |
| [SkillNerds/xskill](https://github.com/SkillNerds/xskill) | 49 |
| [makecindy/cindy](https://github.com/makecindy/cindy) | 26 |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 10 |
| [SkillNerds/xskill-wiki](https://github.com/SkillNerds/xskill-wiki) | 1 |
| [deer-flow/llm-space](https://github.com/deer-flow/llm-space) | 1 |
| [LazyAGI/LazyLLM](https://github.com/LazyAGI/LazyLLM) | 1 |

## Public non-fork repository inventory

Descriptions below are repository metadata snapshots; missing descriptions are left blank.

| Repository | Primary language | Stars | Description |
| --- | --- | ---: | --- |
| [RepoSteward](https://github.com/tiammomo/RepoSteward) | Python | 27 | Local-first, policy-gated control plane for turning GitHub issues into verified, human-reviewed pull requests with coding agents. |
| [RoutePilot](https://github.com/tiammomo/RoutePilot) | Python | 16 | Artifact-first multi-agent travel assistant for evidence-backed Q&A, itinerary planning, validation, and versioned replanning. |
| [QuantPilot](https://github.com/tiammomo/QuantPilot) | TypeScript | 11 | AI-native quantitative research workspace powered by MoAgent, turning natural-language requests into evidence-backed stock analysis, screening, backtests, portfolio insights, and interactive financial dashboards. |
| [ModelPort](https://github.com/tiammomo/ModelPort) | Rust | 10 | ModelPort is a self-hosted Anthropic-compatible model gateway for Claude Code, VS Code Claude, and team-controlled provider routing. |
| [moyuan-code](https://github.com/tiammomo/moyuan-code) | Go | 3 | — |
| [moyuan-stock-trading-assistant](https://github.com/tiammomo/moyuan-stock-trading-assistant) | Python | 3 | moyuan-wencai |
| [Mamoji](https://github.com/tiammomo/Mamoji) | Java | 2 | An integrated operations and BI platform for SMEs and households, covering finance, budgeting, tax, approvals, payroll, analytics, and data protection. |
| [evolvable-user-memory](https://github.com/tiammomo/evolvable-user-memory) | Python | 1 | Evidence-grounded, evolvable user memory for AI applications — immutable revisions, contextual recall, attributable feedback, tenant isolation, and auditable learning. |
| [moyuan-sar-agent](https://github.com/tiammomo/moyuan-sar-agent) | TypeScript | 1 | moyuan-sar-agent |
| [MuseForge](https://github.com/tiammomo/MuseForge) | Python | 1 | MuseForge is a local-first AI image production workspace built for e-commerce teams. It connects product assets, structured prompts, batch generation, real-time progress tracking, candidate review, and a powerful editing canvas in one workflow—so teams can generate at scale, keep only the best results, and refine them for delivery. |
| [qwen38-27b-llamacpp](https://github.com/tiammomo/qwen38-27b-llamacpp) | Python | 1 | Qwen3.8-27B GGUF 本地推理服务：llama.cpp CUDA + Docker Compose，提供 OpenAI 兼容 API、128K 上下文与安全局域网接入。 |
| [agent-knowledge-platform](https://github.com/tiammomo/agent-knowledge-platform) | TypeScript | 0 | — |
| [local-inference-stack](https://github.com/tiammomo/local-inference-stack) | Python | 0 | Agent-ready local LLM inference stack with hardware-aware model selection, verified GGUF downloads, llama.cpp CUDA deployment, quality gates, Tool Use, and real-time observability. |
| [moyuan-data-agent](https://github.com/tiammomo/moyuan-data-agent) | Python | 0 | — |
| [moyuan-shop](https://github.com/tiammomo/moyuan-shop) | TypeScript | 0 | — |
| [offer-skills](https://github.com/tiammomo/offer-skills) | — | 0 | — |
| [tiammomo](https://github.com/tiammomo/tiammomo) | — | 0 | — |
| [tiammomo.github.io](https://github.com/tiammomo/tiammomo.github.io) | HTML | 0 | — |

## Merged PR evidence

Dates are UTC. Each PR appears once.

### SkillNerds/xskill — 49

| PR | Merged (UTC) | Title |
| --- | --- | --- |
| [#404](https://github.com/SkillNerds/xskill/pull/404) | 2026-09-08 | test(server): 恢复 kernel-host 调度器契约 |
| [#377](https://github.com/SkillNerds/xskill/pull/377) | 2026-08-31 | test(algorithms): 建立 raw-only Formation 数据与评分隔离契约 |
| [#385](https://github.com/SkillNerds/xskill/pull/385) | 2026-08-31 | test(formation): add paired Task-Grounded method-effect replay |
| [#379](https://github.com/SkillNerds/xskill/pull/379) | 2026-08-31 | test(tasks): benchmark Task linker structure against Session and Atom baselines |
| [#375](https://github.com/SkillNerds/xskill/pull/375) | 2026-08-31 | test(algorithms): 建立真实模型 Atom 拆分与路由离线回放 |
| [#394](https://github.com/SkillNerds/xskill/pull/394) | 2026-08-31 | feat(tasks): 默认开启 Task Graph 并保留显式回退 |
| [#393](https://github.com/SkillNerds/xskill/pull/393) | 2026-08-31 | fix(codex): 完整采集 rollout 工具证据并覆盖归档会话 |
| [#369](https://github.com/SkillNerds/xskill/pull/369) | 2026-08-31 | perf(generate): append wiki log without rewriting history |
| [#384](https://github.com/SkillNerds/xskill/pull/384) | 2026-08-31 | fix(bench): isolate Formation scenario aggregates |
| [#373](https://github.com/SkillNerds/xskill/pull/373) | 2026-08-29 | test(algorithms): 记录 Atom 候选边界分数并分析路由错误 |
| [#353](https://github.com/SkillNerds/xskill/pull/353) | 2026-08-27 | fix(team): 同机隔离在配置异常时 fail closed 并修复遗留母本软链 |
| [#358](https://github.com/SkillNerds/xskill/pull/358) | 2026-08-26 | fix(agents): 新任务清理遗留的 Skill 写入授权 |
| [#349](https://github.com/SkillNerds/xskill/pull/349) | 2026-08-26 | fix(reverse-sync): 安全修复存量 copy 安装基线 |
| [#348](https://github.com/SkillNerds/xskill/pull/348) | 2026-08-26 | fix(reverse-sync): 透传失败原因并展示当前故障 |
| [#346](https://github.com/SkillNerds/xskill/pull/346) | 2026-08-26 | test(algorithms): 建立 Logical Task 与 Attempt 离线回放基线 |
| [#347](https://github.com/SkillNerds/xskill/pull/347) | 2026-08-26 | feat(agents): 支持分阶段 LLM backend 配置 |
| [#326](https://github.com/SkillNerds/xskill/pull/326) | 2026-08-25 | feat(tasks): 实现 Logical Task 与 Task Attempt 运行时 |
| [#340](https://github.com/SkillNerds/xskill/pull/340) | 2026-08-25 | fix(reverse-sync): 容忍历史基线的换行符差异 |
| [#344](https://github.com/SkillNerds/xskill/pull/344) | 2026-08-25 | fix(e2e): 为不可用的软件包镜像增加官方源回退 |
| [#337](https://github.com/SkillNerds/xskill/pull/337) | 2026-08-25 | fix(agents): 应用 Agno 生成请求配置 |
| [#342](https://github.com/SkillNerds/xskill/pull/342) | 2026-08-25 | fix(ci): 兼容 Agno 3.0 metrics 导入路径 |
| [#332](https://github.com/SkillNerds/xskill/pull/332) | 2026-08-24 | fix(stress): 对齐 Nightly 控制面压力测试与当前运行时契约 |
| [#330](https://github.com/SkillNerds/xskill/pull/330) | 2026-08-24 | fix(deps): 修复 Milvus extra 缺少本地运行时依赖 |
| [#322](https://github.com/SkillNerds/xskill/pull/322) | 2026-08-24 | test(ci): 将 Team C/S 完整闭环纳入常规 PR E2E |
| [#323](https://github.com/SkillNerds/xskill/pull/323) | 2026-08-24 | fix(atoms): 合并相邻近重复 Atom 并保持源轨迹语言 |
| [#320](https://github.com/SkillNerds/xskill/pull/320) | 2026-08-23 | ci(maintenance): 升级官方 Actions 至 v7 |
| [#316](https://github.com/SkillNerds/xskill/pull/316) | 2026-08-23 | test(algorithms): 建立 Atom 拆分与路由离线回放基线 |
| [#319](https://github.com/SkillNerds/xskill/pull/319) | 2026-08-23 | test(perf): 去除容量测试中的批量 Git 初始化 |
| [#314](https://github.com/SkillNerds/xskill/pull/314) | 2026-08-22 | test(perf): 建立确定性热路径复杂度契约 |
| [#312](https://github.com/SkillNerds/xskill/pull/312) | 2026-08-22 | ci(perf): 按风险轴收敛测试矩阵 |
| [#307](https://github.com/SkillNerds/xskill/pull/307) | 2026-08-22 | perf(recommend): 以脏用户增量刷新画像 |
| [#308](https://github.com/SkillNerds/xskill/pull/308) | 2026-08-22 | perf(recommend): sync catalog vectors from a dirty queue |
| [#303](https://github.com/SkillNerds/xskill/pull/303) | 2026-08-22 | perf(skill-edit): schedule edits from persistent dirty queue |
| [#310](https://github.com/SkillNerds/xskill/pull/310) | 2026-08-22 | perf(atom-index): 增量维护 Atom 向量索引 |
| [#306](https://github.com/SkillNerds/xskill/pull/306) | 2026-08-22 | perf(atom-store): 建立可重建的 Atom 定位投影 |
| [#305](https://github.com/SkillNerds/xskill/pull/305) | 2026-08-22 | perf(canary): poll only active staging skills |
| [#302](https://github.com/SkillNerds/xskill/pull/302) | 2026-08-22 | perf(cluster): reuse generation-keyed catalog snapshots |
| [#304](https://github.com/SkillNerds/xskill/pull/304) | 2026-08-22 | fix(recommend): fuse results from all profile centers |
| [#254](https://github.com/SkillNerds/xskill/pull/254) | 2026-08-21 | fix(dashboard): separate current push from exposure history |
| [#290](https://github.com/SkillNerds/xskill/pull/290) | 2026-08-21 | perf(watcher): skip unchanged trajectory discovery scans |
| [#289](https://github.com/SkillNerds/xskill/pull/289) | 2026-08-21 | perf(watcher): reuse atom snapshots within a poll |
| [#280](https://github.com/SkillNerds/xskill/pull/280) | 2026-08-21 | test(platform): isolate checks from generated files and WSL hosts |
| [#277](https://github.com/SkillNerds/xskill/pull/277) | 2026-08-21 | test(dashboard): include pipeline pool route in builtin contract |
| [#276](https://github.com/SkillNerds/xskill/pull/276) | 2026-08-21 | fix(registry): create watcher index after legacy migration |
| [#253](https://github.com/SkillNerds/xskill/pull/253) | 2026-08-19 | fix(registry): preserve multi-skill pending projections |
| [#248](https://github.com/SkillNerds/xskill/pull/248) | 2026-08-19 | fix(cluster-agent): enforce candidate write invariants |
| [#258](https://github.com/SkillNerds/xskill/pull/258) | 2026-08-19 | perf(agents): avoid quadratic context trimming |
| [#256](https://github.com/SkillNerds/xskill/pull/256) | 2026-08-19 | fix(agents): preserve compacted execution state |
| [#246](https://github.com/SkillNerds/xskill/pull/246) | 2026-08-18 | fix(task-agent): reject missing or invalid ux_score |

### makecindy/cindy — 26

| PR | Merged (UTC) | Title |
| --- | --- | --- |
| [#2617](https://github.com/makecindy/cindy/pull/2617) | 2026-08-29 | fix(codex): preserve assistant message boundaries |
| [#2600](https://github.com/makecindy/cindy/pull/2600) | 2026-08-25 | fix(desktop): restore macOS fullscreen after showing window |
| [#2260](https://github.com/makecindy/cindy/pull/2260) | 2026-08-23 | fix(mobile): roll back enqueues without remote evidence |
| [#3004](https://github.com/makecindy/cindy/pull/3004) | 2026-08-23 | fix(model-providers): accept equivalent effort metadata |
| [#2570](https://github.com/makecindy/cindy/pull/2570) | 2026-08-23 | fix(codex): refresh resumed product prompt |
| [#2988](https://github.com/makecindy/cindy/pull/2988) | 2026-08-19 | fix(desktop): gate Claude tool search by provider |
| [#2493](https://github.com/makecindy/cindy/pull/2493) | 2026-08-19 | fix(desktop): explain XD tool-result image loss |
| [#2201](https://github.com/makecindy/cindy/pull/2201) | 2026-08-19 | feat(desktop): mark pending token usage |
| [#2603](https://github.com/makecindy/cindy/pull/2603) | 2026-08-14 | fix(desktop): guard pending provider switch routes |
| [#2636](https://github.com/makecindy/cindy/pull/2636) | 2026-08-14 | fix(desktop): honor Pi Anthropic utility routes |
| [#2555](https://github.com/makecindy/cindy/pull/2555) | 2026-08-13 | test(lizi-mcps): cover helper call_tool transport |
| [#2225](https://github.com/makecindy/cindy/pull/2225) | 2026-08-12 | fix(desktop): reconcile chat embedding availability |
| [#2157](https://github.com/makecindy/cindy/pull/2157) | 2026-08-12 | feat(browser): detect Chrome Beta on macOS |
| [#2548](https://github.com/makecindy/cindy/pull/2548) | 2026-08-12 | fix(desktop): honor system proxy for cua installer |
| [#2178](https://github.com/makecindy/cindy/pull/2178) | 2026-08-09 | feat(ghost): expose model in message hooks |
| [#2064](https://github.com/makecindy/cindy/pull/2064) | 2026-08-09 | feat(desktop): add plan mode composer command |
| [#1694](https://github.com/makecindy/cindy/pull/1694) | 2026-08-09 | fix(desktop): copy legacy asar files physically |
| [#2038](https://github.com/makecindy/cindy/pull/2038) | 2026-08-08 | test(device-link): wait for reconnect conditions |
| [#1885](https://github.com/makecindy/cindy/pull/1885) | 2026-08-06 | test(desktop): avoid orphan reaper PID collisions |
| [#1848](https://github.com/makecindy/cindy/pull/1848) | 2026-08-05 | fix(desktop): show Windows tray menu reliably |
| [#1671](https://github.com/makecindy/cindy/pull/1671) | 2026-08-05 | fix(responses-chat-bridge): support agent message history |
| [#1712](https://github.com/makecindy/cindy/pull/1712) | 2026-08-05 | fix(tools): extract Pi tarballs with GNU tar |
| [#1669](https://github.com/makecindy/cindy/pull/1669) | 2026-08-05 | test(maker-core): use session event contract in notice collector |
| [#1556](https://github.com/makecindy/cindy/pull/1556) | 2026-08-04 | fix(mobile): bound Home startup cache reads |
| [#1653](https://github.com/makecindy/cindy/pull/1653) | 2026-08-04 | test(desktop): validate Python probe execution |
| [#1492](https://github.com/makecindy/cindy/pull/1492) | 2026-08-04 | fix(desktop): sync pinned sessions to mobile |

### bytedance/deer-flow — 10

| PR | Merged (UTC) | Title |
| --- | --- | --- |
| [#5384](https://github.com/bytedance/deer-flow/pull/5384) | 2026-09-14 | feat(scheduled-tasks): filter run history by occurrence status |
| [#5381](https://github.com/bytedance/deer-flow/pull/5381) | 2026-09-12 | feat(scheduled-tasks): preview upcoming cron occurrences |
| [#5323](https://github.com/bytedance/deer-flow/pull/5323) | 2026-09-12 | fix(uploads): bound document outline and preview text |
| [#5363](https://github.com/bytedance/deer-flow/pull/5363) | 2026-09-12 | feat(scheduled-tasks): browse paginated run history |
| [#5316](https://github.com/bytedance/deer-flow/pull/5316) | 2026-09-12 | fix(uploads): recognize valid ATX headings in document outlines |
| [#5310](https://github.com/bytedance/deer-flow/pull/5310) | 2026-09-11 | fix(web-fetch): resolve relative URLs in extracted Markdown |
| [#5315](https://github.com/bytedance/deer-flow/pull/5315) | 2026-09-09 | fix(infoquest): bound HTTP connect and read waits |
| [#5280](https://github.com/bytedance/deer-flow/pull/5280) | 2026-09-08 | fix(tavily): handle Extract responses without a title |
| [#5281](https://github.com/bytedance/deer-flow/pull/5281) | 2026-09-08 | fix(uploads): exclude fenced code from document outlines |
| [#4658](https://github.com/bytedance/deer-flow/pull/4658) | 2026-08-04 | fix(docker): set DEER_FLOW_ROOT for log commands |

### SkillNerds/xskill-wiki — 1

| PR | Merged (UTC) | Title |
| --- | --- | --- |
| [#7](https://github.com/SkillNerds/xskill-wiki/pull/7) | 2026-09-14 | docs(wiki): explain Session, Atom, Task and Attempt |

### deer-flow/llm-space — 1

| PR | Merged (UTC) | Title |
| --- | --- | --- |
| [#126](https://github.com/deer-flow/llm-space/pull/126) | 2026-08-03 | feat: import DeerFlow run-event JSONL files |

### LazyAGI/LazyLLM — 1

| PR | Merged (UTC) | Title |
| --- | --- | --- |
| [#1270](https://github.com/LazyAGI/LazyLLM/pull/1270) | 2026-08-02 | feat(rag): support custom Excel column joiners |
