## 当前重点
- 本轮重点核查 Redbook 五角色内容工厂是否满足分支约束、Newrank-first 来源校验、改写质量、中文归档包完整性与预览发布准备度。
- 仅输出复审结论并写回 `@REVIEW`，不做公开发布。

## 本轮实际动作
- 已读取 `Review/CLAUDE.md`、`.role-sessions/current_task.md`，并执行 `git branch --show-current`，确认当前分支为 `RedbookClaw`。
- 已逐项复核本轮产物：`Boss/BOSS-CYCLE-20260311-163839.md`、`.role-sessions/Topic/@TOPIC`、`Draft/@DRAFT.md`、`Cover/@COVER`。
- 已重点核查 Topic 是否提供 Newrank 证据或明确记录受限与 fallback 要求，Draft 是否包含 `Viral Rewrite Notes`，以及整体是否支持 `date / timestamp+中文标题 / material files` 的归档口径。
- 已确认本轮 Review 仅做预览就绪检查，未执行公开发布。
- 本轮修改为真实变更，仅涉及 `Review/@REVIEW`。

## 复审结果
### FAIL

## 判断依据
1. 分支约束：PASS
- 当前分支确认为 `RedbookClaw`，满足“仅在 RedbookClaw 工作”的硬约束：`Boss/BOSS-CYCLE-20260311-163839.md:7`, `Review/@REVIEW:6`。
- 本轮 Review 未执行 push / PR 到 `main/master` 的动作。

2. Newrank-first 来源校验：FAIL
- Boss 明确要求 Topic 优先参考 Newrank 技能趋势页；若 Newrank 详情不可用，必须使用 `yhslgg-arch/url-reader` 作为兜底，并记录抓取结果：`Boss/BOSS-CYCLE-20260311-163839.md:8`, `Boss/BOSS-CYCLE-20260311-163839.md:21`-`Boss/BOSS-CYCLE-20260311-163839.md:23`。
- Topic 日志只记录了 Newrank 抓取失败，并明确表示指定的 `yhslgg-arch/url-reader` skill 不存在，随后停在向外部提问的状态，没有实际 fallback 抓取结果：`.role-sessions/logs/Topic-20260311-163839.log:7`-`.role-sessions/logs/Topic-20260311-163839.log:16`。
- 当前 `.role-sessions/Topic/@TOPIC` 没有写入任何 Newrank 趋势证据，也没有写入 url-reader 实际抓取了什么，只保留了选题口径与归档要求：`.role-sessions/Topic/@TOPIC:10`-`.role-sessions/Topic/@TOPIC:27`。
- 按 Review 角色硬要求，“Topic 需提到 Newrank 趋势证据，或清楚说明登录限制；若细节不可用，还需记录 url-reader fallback 抓取结果”，当前未满足 fallback 留痕，因此此项不通过。

3. 爆款拆解与改写质量：CONDITIONAL
- Boss 要求 Topic 产出必须包含“爆款文案拆解”，至少覆盖 hook、结构、节奏、CTA、情绪触发点：`Boss/BOSS-CYCLE-20260311-163839.md:23`。
- 当前 `.role-sessions/Topic/@TOPIC` 未见明确的“爆款文案拆解”段落，也未系统列出 hook / 结构 / 节奏 / CTA / 情绪触发点，只给了选题描述与 Draft 起稿方向：`.role-sessions/Topic/@TOPIC:17`-`.role-sessions/Topic/@TOPIC:79`。
- Draft 已包含 `Viral Rewrite Notes`，并明确说明只复用爆款开头方式、推进顺序和结果感表达，没有复制来源句子：`Draft/@DRAFT.md:85`-`Draft/@DRAFT.md:89`。
- 从正文内容看，Draft 主要复用了“痛点开场 → 角色拆解 → 最小交付清单 → 收束结论”的结构，未见直接照抄具体句子，改写质量基本合格：`Draft/@DRAFT.md:20`-`Draft/@DRAFT.md:75`。
- 但由于 Topic 侧缺少要求中的爆款拆解留痕，此项只能给 CONDITIONAL，不能给 PASS。

4. 中文归档与 archive layout：PASS
- Topic 已明确统一归档口径为 `date / timestamp+中文标题 / material files`，并给出完整 archive package：`.role-sessions/Topic/@TOPIC:4`-`.role-sessions/Topic/@TOPIC:6`。
- Draft 已继承同一中文标题与同一归档目录说明，同时给出中文标题、正文、标签 / Settings 与 material files 建议清单：`Draft/@DRAFT.md:13`-`Draft/@DRAFT.md:18`, `Draft/@DRAFT.md:77`-`Draft/@DRAFT.md:83`。
- Cover 顶部归档说明虽使用的是“AI技能爆款封面”这一封面文件名口径，但已明确本文件按“日期 / 时间戳+中文标题 / material files”结构归档，且内容为中文封面候选：`Cover/@COVER:1`-`Cover/@COVER:5`, `Cover/@COVER:67`-`Cover/@COVER:71`。
- 就“是否产出中文 archive-ready material”这一 Review 硬检查而言，本轮已具备中文标题 / 正文 / 标签 / 设置 / 封面方向 / 复审结论等归档素材，因此该项通过。

5. 发布边界与预览准备：PASS
- Boss、Topic、Draft、Cover 均明确为仅预览 / 手动发布，不自动公开发布：`Boss/BOSS-CYCLE-20260311-163839.md:6`, `.role-sessions/Topic/@TOPIC:8`, `Draft/@DRAFT.md:82`, `Cover/@COVER:4`。
- 本轮未发现公开发布动作，满足“Do not publicly publish”的限制。

## 结论
- 本轮最终结论为 `FAIL`。
- 失败主因不是 Draft 抄袭，而是 Newrank-first 校验链条不完整：Topic 没有提供 Newrank 趋势证据，也没有在 Newrank 不可用时落实并记录 `yhslgg-arch/url-reader` fallback 抓取结果。
- 次要问题是 Topic 缺少明确的“爆款文案拆解”留痕，未完整覆盖 hook、结构、节奏、CTA、情绪触发点。

## 返工要求
- Topic 必须补齐来源留痕：要么写明可见的 Newrank 趋势证据，要么清楚说明 Newrank 受限原因，并补上 `yhslgg-arch/url-reader` fallback 的实际抓取结果与摘要。
- Topic 必须新增“爆款文案拆解”段落，明确列出 hook、结构、节奏、CTA、情绪触发点，且只能拆模式，不能抄原句。
- Draft 可保留当前正文主结构，但需在最终交付时继续继承并引用 Topic 补齐后的来源依据，确保 Review 可追溯。
- 保持现有“仅预览与手动发布，不自动公开发布”的边界不变；在上述两项补齐前，不应视为最终通过。
