@REVIEW

归档路径：
`2026-03-13 / 20260313-182703+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`

结论：CONDITIONAL

## Review Summary
- 分支检查通过：`RedbookClaw`。
- Topic 已明确 Newrank-first：`https://www.newrank.cn/search/trend/skill` 写入来源优先级，并如实说明当前未取得可核验深层详情，见 `.role-sessions/Topic/TOPIC:21-25`。
- Topic 也如实记录了 fallback 要求存在但 `yhslgg-arch/url-reader` 当前不可用，未伪造抓取结果，见 `.role-sessions/Topic/TOPIC:24-25`。
- Topic 已包含 `Viral Copy Breakdown` 与 `Rewrite Direction`，见 `.role-sessions/Topic/TOPIC:55-119`。
- Draft 已包含 `Viral Rewrite Notes`，且正文整体为结构性重写，没有直接复制 Topic 中的爆款句式原文，见 `Draft/@DRAFT.md:92-96`。
- Cover 提供了中文 archive-ready 包与手动发布边界，见 `Cover/@COVER:3-19`。

## Pass Items
1. **Newrank-first / fallback 边界**：通过。
2. **Viral rewrite 留痕**：通过。
3. **中文 archive-ready 输出**：基本通过，Topic / Draft / Cover 均提供中文标题、正文/说明、标签或设置，并声明仅预览/复审/手动发布。
4. **非复制式改写**：基本通过；当前 Draft 属于模式改写，不是句子照搬。

## Conditional Issues
1. **统一 archive package 未完全一致**：
   - Boss 统一要求的归档包是：`2026-03-13 / 20260313-182703+AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程 / material files`，见 `Boss/BOSS-CYCLE-20260313-182703.md:15,22`。
   - Draft 使用了同一时间戳，但中文标题与 Boss 不一致，见 `Draft/@DRAFT.md:4-7,89`。
   - Topic 的归档日期还写成了 `2026-03-14`，且标题也不是 Boss 统一标题，见 `.role-sessions/Topic/TOPIC:2-3`。
   - Cover 的 archive_title 也与 Boss 统一标题不一致，见 `Cover/@COVER:4-7`。
2. **Draft 写入了超出 Topic 可核验边界的“关键词证据强弱排序”**：
   - Draft 在 `Draft/@DRAFT.md:23-26` 直接写了 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 的分层判断。
   - 当前 Topic 只明确记录“未看到可核验榜单明细、fallback 不可用、未编造趋势数值”，见 `.role-sessions/Topic/TOPIC:21-25`，并未在同一文件中逐项给出上述五个关键词的证据强弱分层。
   - 为避免来源链条被 Draft 自行扩写，建议改成更保守表述：只承接 Topic 已明确确认的来源边界，不自行补写每个关键词的证据等级。

## Required Rework
1. 把 `Topic / Draft / Cover / Review` 的归档日期、中文标题、archive package 全部统一到 Boss 指定版本：
   - `date`: `2026-03-13`
   - `timestamp`: `20260313-182703`
   - `archive_title`: `AI技能内容开始真正分层：能被反复带走的，不是更长的提示词，而是能稳定复用的一整套流程`
2. 将 Topic 的归档建议路径从 `2026-03-14/...AI工作流技能正在替代碎片提问...` 改为 Boss 统一包名，见 `.role-sessions/Topic/TOPIC:2-6`。
3. 将 Cover 的 `archive_title` 与 package 名称改成 Boss 统一标题，保持与 Draft/Review 一致，见 `Cover/@COVER:4-7`。
4. 将 Draft `正文` 中 `Draft/@DRAFT.md:22-26` 的关键词分层判断改成更保守的来源边界描述，只复述 Topic 已明确确认的事实，不额外扩写各关键词证据强弱。

## Publish Boundary
- 当前产物仍保持“仅用于预览、复审与手动发布，不自动公开发布”，该边界通过。
