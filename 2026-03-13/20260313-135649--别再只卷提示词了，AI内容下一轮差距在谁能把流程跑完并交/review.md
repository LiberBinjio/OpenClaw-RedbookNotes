# @REVIEW

## Archive Package Check
- target layout: `2026-03-13 / 20260313-135649+AI技能内容开始从会提问转向会交付，真正拉开差距的是谁能把完整流程稳定跑完 / material files`
- Boss archive package: `2026-03-13 / 20260313-135649+AI技能内容开始从会提问转向会交付，真正拉开差距的是谁能把完整流程稳定跑完 / material files`
- Topic archive package: `2026-03-13 / 20260313-070317+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`
- Draft archive package: `2026-03-13 / 20260313-135649+AI技能内容开始从会提问转向会交付，真正拉开差距的是谁能把完整流程稳定跑完 / material files`
- Cover archive package: `2026-03-13 / 20260313-135649+AI技能内容开始从会提问转向会交付，真正拉开差距的是谁能把完整流程稳定跑完 / material files`
- Result: `Topic` 仍沿用旧时间戳 `20260313-070317` 与旧中文标题，未与 Boss / Draft / Cover 的本轮统一 archive package 对齐。

## Check Results
1. **Newrank-first sourcing**: PASS
   - `@TOPIC:11-15` 明确把 `https://www.newrank.cn/search/trend/skill` 作为第一来源，并写清当前未取得可验证详情。
   - `@TOPIC:33-39` 也如实说明当前只有邻近趋势线索，未把 `search/trend/skill` 写成已核实正文。
2. **Fallback evidence**: CONDITIONAL
   - `@TOPIC:13-15,38` 与 `Draft/@DRAFT.md:22-30,93-97` 都如实写明按要求应使用 `yhslgg-arch/url-reader`，但当前会话未提供该 skill，因此无法执行。
   - 这满足“诚实记录限制”，但不满足“已完成 fallback 抓取”，所以只能条件通过。
3. **Viral Rewrite Notes present**: PASS
   - `Draft/@DRAFT.md:93-97` 包含 `Viral Rewrite Notes`。
4. **Rewrite instead of copying**: PASS
   - Topic 已提供 `Viral Copy Breakdown` 与 `Rewrite Direction`（`@TOPIC:84-149`），Draft 也围绕“提示词 vs 流程交付”完成结构性改写，未见直接照抄 viral wording。
5. **Chinese archive-ready material**: CONDITIONAL
   - Topic、Draft、Cover 都提供了中文材料，Draft 也补齐了标题、正文、tags/settings，Cover 提供了 6 个候选。
   - 但 `@TOPIC:4-8,151-164` 仍停留在旧 archive timestamp / archive_title，导致整包暂时不能按单一目录直接归档。
6. **Preview/manual publish boundary**: PASS
   - `@TOPIC:8`、`Draft/@DRAFT.md:91`、`Cover/@COVER:8,18,86` 都明确仅用于预览、复审与手动发布，不自动公开发布。

## Final Verdict
**CONDITIONAL**

## Required Rework Items
1. 统一 `@TOPIC` 的 `date`、`timestamp`、`archive_title`、`archive_package`，必须改成 Boss 规定的本轮版本：
   - `2026-03-13`
   - `20260313-135649`
   - `AI技能内容开始从会提问转向会交付，真正拉开差距的是谁能把完整流程稳定跑完`
2. 同步修正 `@TOPIC` 中所有仍引用旧主题“AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程”的位置，避免 Topic 与 Draft / Cover / Boss 主题分裂。
3. 保留当前 Newrank / fallback 限制说明，不要把 `yhslgg-arch/url-reader` 写成已执行成功；若后续环境补齐该 skill，再补抓取证据与 extraction path。

## File References
- Topic: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/@TOPIC`
- Draft: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/Draft/@DRAFT.md`
- Cover: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/Cover/@COVER`
- Boss: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/Boss/BOSS-CYCLE-20260313-135649.md`
