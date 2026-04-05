# @REVIEW

## Archive Package
- date: `2026-04-05`
- timestamp: `20260405-010306`
- archive_title: `AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow`
- archive_package: `2026-04-05 / 20260405-010306+AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Result
- status: `FAIL`
- summary: `本轮 Topic / Draft / Cover 基本遵守了 Newrank-first 边界，Draft 也包含 Viral Rewrite Notes，正文属于结构改写而非句子照搬。但按 Review 规则，本轮仍缺少 required fallback 的实际执行与抓取记录，且当前 archive material files 实查仅落地了 @DRAFT.md，未形成完整的同轮归档包。因此当前结果不能判定为 preview ready。`

## Checks
### 1. Newrank-first topic sourcing
- PASS: `.role-sessions/Topic/@TOPIC:13-25` 明确写出首要来源是 `https://www.newrank.cn/search/trend/skill`，并如实记录本轮未成功取得可复核 trend detail。
- PASS: `.role-sessions/Topic/@TOPIC:52-62` 与 `Draft/@DRAFT.md:26-29` 都保持了来源边界，没有把未核验榜单、热度、排名或爆文明细写成事实。
- PASS: `Cover/@COVER:10-16` 继续承接同一边界，未把 Newrank 邻近线索包装成趋势详情页结论。

### 1a. Required fallback evidence
- PASS: `.role-sessions/Topic/@TOPIC:18-25` 明确记录：Newrank detail 不完整时应使用 `yhslgg-arch/url-reader`，但当前环境未提供该 skill，因此本轮未执行 fallback。
- PASS: `.role-sessions/logs/Topic-20260405-010306.log:16-17` 与 Topic 口径一致，明确写明 required fallback 当前不可用。
- FAIL: 按 `Review/CLAUDE.md:10-15` 与 `.role-sessions/current_task.md:4-7` 的要求，如果 Newrank detail 不可复核，就需要 `yhslgg-arch/url-reader` fallback evidence 并记录抓取内容；当前并没有 `record what it fetched` 的实际结果，因此该项未完成。

### 2. Viral Rewrite Notes / breakdown
- PASS: `.role-sessions/Topic/@TOPIC:106-171` 提供了完整 `Viral Copy Breakdown`，覆盖 hook、structure、conflict、promise、proof、CTA、pacing、emotional triggers。
- PASS: `Draft/@DRAFT.md:83-87` 包含独立 `Viral Rewrite Notes`，满足 Draft 必检项。
- PASS: `Cover/@COVER:18-24` 也提供了封面层的 viral-copy breakdown，并明确不复制外部表达。

### 3. Rewrite quality / anti-copy check
- PASS: `Draft/@DRAFT.md:17-62` 采用“认知反转 -> 来源边界 -> 4 个 workflow 断点 -> 轻量方法 -> CTA”的原创组织方式，属于结构改写，不是句子复制。
- PASS: `Draft/@DRAFT.md:59-60,83-86` 已明确声明借的是传播结构与钩子，不是外部原句复刻。
- PASS: `Cover/@COVER:26-72` 的封面候选延续同一主题，但未见直接复制 viral wording，也未虚构榜单结论。

### 4. Chinese archive-ready material
- PASS: `.role-sessions/Topic/@TOPIC:5-10`、`Draft/@DRAFT.md:3-8`、`Cover/@COVER:3-8` 的 archive package 已统一到 `2026-04-05 / 20260405-010306+AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow / material files`。
- PASS: `Draft/@DRAFT.md:10-87` 已提供中文标题、备用标题、中文正文、tags/settings、source angle、publish boundary 与 Viral Rewrite Notes。
- PASS: `Cover/@COVER:26-72` 已提供 4 个中文封面候选，满足至少 3 个 cover candidates 的要求。
- FAIL: 当前 archive 目录实查仅有 `2026-04-05/20260405-010306+AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow/material files/@DRAFT.md`，缺少同轮 `@TOPIC`、`@COVER`、`@REVIEW` 落地文件，尚未形成完整 archive-ready material files。

### 5. Preview readiness
- FAIL: 由于 required fallback evidence 缺失，且 archive material files 落盘不完整，本轮不能判定为 preview ready。
- PASS: 当前所有文本都保持了“仅用于预览、复审与手动发布，不自动公开发布”的边界。

## Rework Items
1. 一旦环境提供 `yhslgg-arch/url-reader`，必须对 `https://www.newrank.cn/search/trend/skill` 执行 required fallback，并在 Topic 中补写实际抓取内容、抓到的字段，以及哪些部分仍不可复核。
2. 在 fallback evidence 补齐前，继续保持当前保守口径：只能写“已优先检查 Newrank 入口、detail 不可复核、required fallback 当前未执行”，不得补写任何榜单、热度、排名、截图或详情页内容。
3. 把本轮 `@TOPIC`、`@COVER`、`@REVIEW` 正式落到 `2026-04-05 / 20260405-010306+AI技能内容别再停在谁接入了Skill真正更容易被收藏的是能稳定复用的workflow / material files`，不要只保留 `@DRAFT.md`。
4. 保持 Draft 当前的重写方向，不要把 `.role-sessions/Topic/@TOPIC:52-62` 的邻近线索扩写成 Newrank 已确认爆发的事实。

## Preview Readiness
- current_result: `NOT PREVIEW READY`
- condition_note: `当前主要问题不在 Draft 的改写质量，而在 required fallback 证据缺口与 archive 目录落盘不完整。只要 fallback 仍未实际执行、material files 仍缺 Topic / Cover / Review 正式文件，本轮就不能判定为 preview ready。`
