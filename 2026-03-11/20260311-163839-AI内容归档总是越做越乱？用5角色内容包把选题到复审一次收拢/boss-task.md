# Boss Cycle 20260311-163839

## 当前重点
- 当前重点继续维持 Redbook 的 5 角色内容工厂结构：Boss / Topic / Draft / Cover / Review。
- 本轮交付必须支持归档目录布局：`date / timestamp+中文标题 / material files`。
- 本轮默认目标仍是可预览、可复审、可手动发布的内容包，不进行自动公开发布。
- 继续遵守硬约束：仅在 `RedbookClaw` 分支工作，不触碰 `main/master`，不修改 `node5`，且只写 `@ALL` 与 `@BOSS` 口径。
- Topic 需优先参考 Newrank 热点技能页 `https://www.newrank.cn/search/trend/skill`，围绕 AI skill、workflow skill、Copilot skill、openclaw 相关方向组织选题，并输出爆款文案拆解线索。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md`。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合要求，因此继续。
3. 已读取 `.role-sessions/current_task.md`；`SAF-TaskAssignAndProgress.md` 当前未检索到。
4. 已检查 Boss 目录既有留痕文件，确认沿用 `Boss/BOSS-CYCLE-<timestamp>.md` 的单文件留痕模式。
5. 已尝试访问 Newrank 技能趋势页；当前环境下未取得可用详情，因此本轮 Boss 要求中明确记录 Topic 必须先保留 Newrank 访问受限说明，再按要求使用 url-reader 兜底读取目标链接详情后继续产出选题依据。
6. 已确认本轮仍只形成预览与手动发布所需内容包，不做公开发布。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS` 的本轮要求：围绕单一中文主题组织 Redbook 内容包，所有产物必须能归入 `date / timestamp+中文标题 / material files` 的归档结构。
- Topic：
  - 优先从 Newrank 技能趋势页提取话题线索，并记录可见的趋势证据或访问限制。
  - 若 Newrank 详情不可用，必须使用 `yhslgg-arch/url-reader` 作为兜底读取目标链接详情，并把抓取结果转成可归档的中文选题依据。
  - 产出中必须包含“爆款文案拆解”部分，至少拆出 hook、结构、节奏、CTA、情绪触发点，不得直接照抄原句。
  - 统一服务同一中文标题，并给出归档建议：`date / timestamp+中文标题 / material files`。
- Draft：
  - 必须继承 Topic 的 Newrank-first 证据或 fallback 抓取摘要。
  - 正文目标应围绕同一主题生成可预览、可复审、可手动发布的中文文案草稿。
  - 必须输出中文标题、正文、标签/设置，以及一个简短的 viral-copy breakdown / Viral Rewrite Notes 段落。
  - 只能改写爆款结构与钩子逻辑，不得复制来源句子。
- Cover：
  - 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
  - 主副标题保持短促直接，强化“技能趋势 + 工作流结果”感。
- Review：
  - 必须核验 Topic 是否优先说明 Newrank 证据；若不可用，是否记录了 url-reader 兜底与抓取结果。
  - 必须核验 Draft 是否包含 Viral Rewrite Notes，且为结构改写而非句子复制。
  - 必须核验最终产物是否满足中文归档可用、可预览、可复审、可手动发布且不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、Copilot/Agent 协作技能、内容工作流归档与复盘。
- 内容重点：不是泛泛讲 AI，而是讲“看到趋势后，怎样把技能/工作流整理成可复用、可复审、可手动发布的内容包”。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不生成自动公开发布动作。
  - 不偏离归档结构与中文标题主线。

## 归档要求
- 最终内容包应能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层用于归档日期。
- `timestamp+中文标题` 层用于单次内容包唯一标识。
- `material files` 层用于沉淀素材、趋势截图、引用摘要、封面源文件、正文依据与复审凭据。
- Boss 侧本轮文件名：`Boss/BOSS-CYCLE-20260311-163839.md`。

## 当前判断
- 本轮 Boss 侧需要的真实编辑是新增一份 Boss 周期任务文件，并把 Newrank-first 与 fallback 兜底要求写清。
- 当前目录中已有多轮 `BOSS-CYCLE-*.md` 留痕，因此继续保持同样命名方式最符合现有流程。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）
- 缺失文件：`SAF-TaskAssignAndProgress.md` 当前未检索到
- Newrank 状态：已尝试读取但未取得可用详情；已在任务中要求 Topic 记录限制并使用 url-reader 兜底
- 实际改动：新增 `Boss/BOSS-CYCLE-20260311-163839.md`
- 发布动作：未执行
