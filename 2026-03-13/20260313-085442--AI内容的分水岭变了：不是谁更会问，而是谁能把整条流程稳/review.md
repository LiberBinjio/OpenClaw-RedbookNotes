# @REVIEW

## Archive Package Check
- target layout: `2026-03-13 / 20260313-070317+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`
- Topic archive package: `2026-03-13 / 20260313-070317+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`
- Draft archive package: `2026-03-13 / 20260313-070317+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`
- Cover archive package: `2026-03-13 / 20260313-070317+AI技能内容开始拼交付闭环，不拼提示词，能把流程跑完的人更容易留下结果 / material files`
- Result: `Cover` 未与 Topic / Draft / Boss 的统一中文标题保持一致，archive package 不统一。

## Check Results
1. **Newrank-first sourcing**: PASS
   - `@TOPIC:11-15` 明确把 `https://www.newrank.cn/search/trend/skill` 作为第一来源，并写清当前未取得可验证详情。
2. **Fallback evidence**: CONDITIONAL
   - `@TOPIC:13-15`、`@TOPIC:38` 与 `Draft/@DRAFT.md:36-40,83-84` 都如实写明按要求应使用 `yhslgg-arch/url-reader`，但当前会话未提供该 skill，因此无法执行。
   - 这满足“诚实记录限制”，但不满足“已完成 fallback 抓取”。当前只能按环境限制保留条件通过。
3. **Viral Rewrite Notes present**: PASS
   - `Draft/@DRAFT.md:80-84` 包含 `Viral Rewrite Notes`。
4. **Rewrite instead of copying**: PASS
   - Topic 已提供 `Viral Copy Breakdown` 与 `Rewrite Direction`（`@TOPIC:84-149`），Draft 也围绕“提示词 vs 流程复用”做了结构性改写，未见直接照抄 viral wording。
5. **Chinese archive-ready material**: CONDITIONAL
   - Topic、Draft、Cover 都是中文材料，且包含 title/body/tags/settings or cover candidates。
   - 但 `Cover/@COVER:3-8,71-80` 的 archive_title 与 archive_package 漂移，导致整包还不能直接按单一 archive 目录归档。
6. **Preview/manual publish boundary**: PASS
   - `@TOPIC:8`、`Draft/@DRAFT.md:78`、`Cover/@COVER:8,18,80` 都明确仅用于预览、复审与手动发布，不自动公开发布。

## Final Verdict
**CONDITIONAL**

## Required Rework Items
1. 统一 `Cover/@COVER` 的 `archive_title` 与 `archive_package`，必须与 Boss / Topic / Draft 一致：
   - `AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程`
2. `Cover/@COVER` 中 `Source Guardrail` 第 11 行当前写的是另一套 cycle 主题，也需要同步改回统一主题，避免归档与预览时标题分裂。
3. 保留当前 Newrank / fallback 限制说明，不要把 `yhslgg-arch/url-reader` 写成已执行成功；若后续环境补齐该 skill，再补抓取证据与 extraction path。

## File References
- Topic: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/@TOPIC`
- Draft: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/Draft/@DRAFT.md`
- Cover: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/Cover/@COVER`
- Boss: `/home/vibe/.openclaw/workspace/projects/SAF-claude-ai-team/Boss/BOSS-CYCLE-20260313-070317.md`
