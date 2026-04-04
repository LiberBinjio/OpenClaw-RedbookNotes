# @REVIEW

## Archive Package
- date: `2026-04-04`
- timestamp: `20260404-200207`
- archive_title: `AI技能别再只堆工具，先把工作流跑通`
- archive_package: `2026-04-04 / 20260404-200207+AI技能别再只堆工具，先把工作流跑通 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Result
- status: `FAIL`
- summary: `Topic 已按要求写明 Newrank-first 检查、detail 未成功取得，以及 required fallback yhslgg-arch/url-reader 当前环境不可执行；Draft 已包含 Viral Rewrite Notes，整体属于结构改写而非句子复制；Cover 也完成了中文 archive-ready 文案。但本轮仍不满足 preview readiness：required fallback 没有实际 fetch 记录，且最终 archive folder layout 仅停留在字段声明，未形成实际 material files 目录包。`

## Checks
### 1. Newrank-first topic sourcing
- PASS: `@TOPIC:10-24` 明确写出优先入口为 `https://www.newrank.cn/search/trend/skill`，并如实记录本轮未拿到可复核 detail。
- PASS: `@TOPIC:25-33` 清楚限定了证据边界，没有把未核验的榜单名次、热度、详情页正文或截图结论写成事实。
- PASS: `@TOPIC:56-66` 与 `Draft/@DRAFT:21-24` 都继续承接同一来源边界，保持 Newrank-first 口径一致。

### 1a. Required fallback evidence
- PASS: `@TOPIC:16-24` 已明确记录：按规则应使用 `yhslgg-arch/url-reader` 作为 required fallback，但当前环境只提供 `simplify` 与 `claude-api`，因此不能伪造已执行。
- FAIL: `@TOPIC:20-24` 同时也明确写出 `actual_fallback_execution` 为未执行，因此没有 `record what it fetched` 的 fallback 抓取记录；按当前任务规则，这一项仍视为未完成。

### 2. Viral Rewrite Notes / breakdown
- PASS: `@TOPIC:112-167` 提供完整 `Viral Copy Breakdown`，包含 hook、structure、conflict、promise、proof、CTA，并明确禁抄边界。
- PASS: `Draft/@DRAFT:67-70` 包含独立 `Viral Rewrite Notes`。
- PASS: `Cover/@COVER:18-24` 也补齐了 `Viral Copy Breakdown`，且继续遵守证据边界。

### 3. Rewrite quality / anti-copy check
- PASS: `Draft/@DRAFT:17-54` 采用“认知反转 -> 来源边界 -> 4 个流程断点 -> 轻量解法 -> CTA”的原创改写结构，未见直接复制外部标题句或正文句。
- PASS: `Draft/@DRAFT:67-70` 明确声明保留的是高传播结构与钩子，不是外部原句。
- PASS: `Cover/@COVER:26-72` 封面文案延续同一主题，但没有照搬外部 viral wording，也没有虚构趋势证据。

### 4. Chinese archive-ready material
- PASS: `@TOPIC:3-8`、`Draft/@DRAFT:3-8`、`Cover/@COVER:3-8`、`Review/@REVIEW:3-8` 都已统一到 archive folder layout：`date / timestamp+Chinese title / material files`。
- PASS: `@TOPIC:35-197` 已形成完整中文 topic package，包含主选题、备选题、目标人群、问题定义、Trend Clue、Viral References、Rewrite Angle、Hook Breakdown、Viral Copy Breakdown、Rewrite Direction 与 Draft Handoff Notes。
- PASS: `Draft/@DRAFT:10-70` 已生成中文标题、备用标题、中文正文、tags/settings 与 Viral Rewrite Notes。
- PASS: `Cover/@COVER:26-72` 已提供 4 个中文封面候选，并明确主推版本。
- FAIL: 当前仓库中未看到实际落盘的 `2026-04-04 / 20260404-200207+AI技能别再只堆工具，先把工作流跑通 / material files` 目录包；目前仍是字段声明状态，不能算完整 archive-ready package。

### 5. Preview / publishing boundary
- PASS: `@TOPIC:3-8`、`Draft/@DRAFT:3-8`、`Cover/@COVER:3-8` 与 `Review/@REVIEW:3-8` 都保持了“仅用于预览、复审与手动发布，不自动公开发布”的边界。
- PASS: 当前未见任何公开发布动作。

## Rework Items
1. 若后续环境提供 `yhslgg-arch/url-reader`，必须对 `https://www.newrank.cn/search/trend/skill` 补做 required fallback，并在 Topic 中补记实际 fetch 到的内容与 extraction path；在此之前，fallback evidence 继续视为未完成。
2. 将本轮 Topic、Draft、Cover、Review 实际落盘到 `2026-04-04 / 20260404-200207+AI技能别再只堆工具，先把工作流跑通 / material files`，形成真实 archive-ready package，而不只是元数据声明。
3. 保持当前 Draft 的改写方向与证据边界，不要把 `@TOPIC:56-66` 的趋势判断扩写成未验证的榜单 detail、热度或排名。

## Preview Readiness
- current_result: `NOT PREVIEW READY`
- condition_note: `当前主要缺口是 required fallback 没有实际 fetch 记录，以及 archive folder layout 尚未形成真实 material files 目录包；这两项未补齐前，本轮应维持 FAIL。`
