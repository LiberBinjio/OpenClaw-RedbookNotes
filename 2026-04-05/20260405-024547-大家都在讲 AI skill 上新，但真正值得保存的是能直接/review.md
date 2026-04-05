# @REVIEW

## Archive Package
- date: `2026-04-05`
- timestamp: `20260405-024547`
- archive_title: `AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow`
- archive_package: `2026-04-05 / 20260405-024547+AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Result
- status: `FAIL`
- summary: `当前分支正确，Topic / Draft / Cover 的时间戳已统一到 20260405-024547，Draft 也包含 Viral Rewrite Notes 且整体属于结构改写；但 Topic 在 Newrank detail 不可复核时，没有完成任务要求中的 yhslgg-arch/url-reader fallback 抓取并记录 fetched 内容，因此本轮仍不能判定为 preview ready。`

## Checks
### 1. Branch / boundary
- PASS: 当前分支为 `RedbookClaw`，符合 `Review/CLAUDE.md:4-7` 与当前任务要求。
- PASS: `Draft/@DRAFT:3-8`、`Cover/@COVER:3-8`、`Review/@REVIEW:3-8` 都写明仅用于预览、复审与手动发布，不自动公开发布。

### 2. Newrank-first topic sourcing
- PASS: `.role-sessions/Topic/@TOPIC:12-29` 明确写出首要来源是 `https://www.newrank.cn/search/trend/skill`，并说明本轮未成功取得可复核 trend detail、榜单明细、热度值、排名或爆文明细。
- PASS: `.role-sessions/Topic/@TOPIC:52-61` 与 `Draft/@DRAFT:23-31` 都把可用证据限制在已核验的来源边界与公开标题级邻近线索，没有把邻近线索扩写成已验证的趋势详情。
- PASS: `.role-sessions/Topic/@TOPIC:5-10`、`Draft/@DRAFT:3-8`、`Cover/@COVER:3-8` 的 archive package 已统一到 `20260405-024547`，支持 `date / timestamp+Chinese title / material files` 布局。

### 3. Required fallback evidence
- FAIL: `.role-sessions/Topic/@TOPIC:18-25` 只记录了按规则应使用 `yhslgg-arch/url-reader`，但当前环境未提供该 skill，因此 fallback 未执行。
- FAIL: `.role-sessions/Topic/@TOPIC:22-25` 的 `actual_fallback_execution` 明确写的是 `未执行；原因是当前环境未提供该 skill`，没有 `record what it fetched` 的实际结果。
- FAIL: `Review/CLAUDE.md:10-15` 和 `.role-sessions/current_task.md:4-7` 要求在 Newrank detail 不可用时提供 url-reader fallback evidence；本轮缺少这项证据，所以不能通过。

### 4. Viral rewrite quality
- PASS: `Draft/@DRAFT:17-65` 采用“认知反转 → 来源边界说明 → 4 个 workflow 断点 → 轻量方法 → CTA”的完整改写结构，属于 pattern rewrite，不是句子照搬。
- PASS: `Draft/@DRAFT:78-90` 含有 `Viral Copy Breakdown` 与 `Viral Rewrite Notes`，满足 `Review/CLAUDE.md:12-13`。
- PASS: `Cover/@COVER:18-24` 的封面拆解也只承接已核验边界，没有直接复制 viral wording。

### 5. Chinese archive-ready material
- PASS: `Draft/@DRAFT:10-90` 已提供中文标题、正文、tags/settings、viral breakdown、rewrite notes。
- PASS: `Cover/@COVER:26-72` 已提供 4 个中文封面候选和主推方案。
- PASS: `.role-sessions/Topic/@TOPIC:31-202` 已提供中文主选题、备选题、人群、问题定义、趋势线索、Viral Copy Breakdown、Rewrite Direction、Draft handoff notes。
- FAIL: 尽管文案层面已 archive-ready，但缺少任务硬性要求中的 url-reader fallback 抓取记录，因此不能认定为最终 preview ready。

## Rework Items
1. 在支持该技能的环境中执行 `yhslgg-arch/url-reader` 对 `https://www.newrank.cn/search/trend/skill` 的 required fallback，并把实际抓取结果写入 Topic，明确 `record what it fetched`。
2. 在 fallback 无法执行前，继续保持当前写法边界：只能写“已优先检查 Newrank 入口、detail 不可复核、当前环境未提供 required fallback skill”，不能补写任何未核验的详情、热度、排名、截图结论或榜单摘要。
3. 保持 `Draft/@DRAFT:17-90` 这种结构改写方式，不要退回成“谁接入了什么”的资讯复述，也不要复制外部 viral wording。

## Preview Readiness
- current_result: `NOT PREVIEW READY`
- blocking_reason: `唯一核心阻塞项是 required fallback evidence 缺失；在补齐 yhslgg-arch/url-reader 实际抓取记录前，本轮只能维持 FAIL。`
