# @REVIEW

## Archive Package
- date: `2026-03-15`
- timestamp: `20260315-015824`
- archive_title: `AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程`
- archive_package: `2026-03-15 / 20260315-015824+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Verdict
CONDITIONAL

## Summary
- 分支检查通过：`git branch --show-current` 返回 `RedbookClaw`。
- Boss 与 Draft 已统一到本轮 archive package `20260315-015824+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程`。
- Topic 满足 Newrank-first 与 fallback 限制披露要求，并包含 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- Draft 包含 `Viral Rewrite Notes`，正文整体属于结构改写，不见明显直接照抄句子。
- 当前未见任何自动公开发布动作。

## Check Results
### 1. Topic 是否优先使用 Newrank，或明确说明受限原因
- 通过。`.role-sessions/Topic/@TOPIC:21-31` 明确先检查 `https://www.newrank.cn/search/trend/skill`，并说明 detail 不完整、`yhslgg-arch/url-reader` 不可用。
- 但当前主用 Topic 文件仍停留在旧归档包：`.role-sessions/Topic/@TOPIC:1` 仍是 `2026-03-15/20260314-225104+AI技能流正在从单点提问转向工作流编排/`，未切到本轮统一 archive package。

### 1a. Newrank detail 不可用时，是否使用 url-reader fallback 并记录抓取情况
- 条件通过。当前环境确实没有 `yhslgg-arch/url-reader` skill，Topic 已如实记录无法执行 fallback，未伪造抓取结果：`.role-sessions/Topic/@TOPIC:27-31`。
- 按当前会话约束，这一项可接受为“环境受限但已诚实披露”，但不能记成“fallback 已执行”。

### 2. Draft 是否包含 Viral Rewrite Notes
- 通过。见 `Draft/@DRAFT.md:100-104`。

### 3. Draft 是否属于改写结构而非复制句子
- 通过。Draft 延续了“提示词 vs 流程”的传播结构，但正文表述为原创展开，未见直接复制 Topic 爆款拆解中的现成句子。可参考 `Draft/@DRAFT.md:17-90` 对照 `.role-sessions/Topic/@TOPIC:75-135`。

### 4. 是否产出中文 archive-ready material（title/body/tags/settings）
- Draft：通过。`Draft/@DRAFT.md:9-98` 已包含中文标题、正文、tags/settings，并写明 archive package。
- Cover：部分通过。`Cover/@COVER:4-9` 提供了中文 archive 信息与封面候选，但封面文件的标题与 archive package 仍未和本轮统一：`Cover/@COVER:2` 仍写 `20260315-013230...`，`Cover/@COVER:7-8` 的 archive_title / archive_package 仍是 `AI技能别再堆提示词先把稳定交付的流程接起来`，与 Boss / Draft / Review 不一致。
- Topic：不通过。`.role-sessions/Topic/@TOPIC` 仍是上一轮包名与主题，未更新到 `20260315-015824`。

### 5. 是否仅用于预览 / 复审 / 手动发布
- 通过。Boss、Draft、Cover 均明确写了不自动公开发布，未见自动发布指令：`Boss/BOSS-CYCLE-20260315-015824.md:16-17`, `Draft/@DRAFT.md:96-98`, `Cover/@COVER:8-9`。

## Explicit Rework Items
1. **统一 Topic 归档包**：把 `.role-sessions/Topic/@TOPIC` 更新到本轮 `2026-03-15 / 20260315-015824+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`，不要继续沿用 `20260314-225104` 旧包。
2. **统一 Cover 归档包与标题**：修正 `Cover/@COVER:2` 的旧路径 `20260315-013230...`，并把 `Cover/@COVER:7-8` 的 `archive_title` / `archive_package` 改成与 Boss / Draft 完全一致的本轮中文标题。
3. **统一跨角色主题口径**：当前 Draft 主标题是“AI技能内容开始真正分层…”，Cover 仍是“AI技能别再堆提示词先把稳定交付的流程接起来”，需要统一为同一 archive 标题，避免归档漂移。
4. **完成后再复审**：修正 Topic 与 Cover 的时间戳、标题、archive package 后，才能算 archive-ready。

## Final Judgment
- 当前结果为 `CONDITIONAL`，不是 `PASS`。
- 主要原因不是来源或改写质量，而是 **Topic / Cover / Draft / Boss 的 archive package 未完全统一**，不满足 `date / timestamp+Chinese title / material files` 的同包归档要求。
