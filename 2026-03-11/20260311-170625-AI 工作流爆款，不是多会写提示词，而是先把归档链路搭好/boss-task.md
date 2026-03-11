# Boss Cycle 20260311-170625

## 当前重点
- 当前重点继续维持 Redbook 的 5 角色内容工厂结构：Boss / Topic / Draft / Cover / Review。
- 本轮交付必须支持归档目录布局：`date / timestamp+中文标题 / material files`。
- 本轮默认目标仍是可预览、可复审、可手动发布的内容包，不进行自动公开发布。
- 继续遵守硬约束：仅在 `RedbookClaw` 分支工作，不触碰 `main/master`，不修改 `node5`，且只写 `@ALL` 与 `@BOSS` 口径。
- Topic 仍需优先参考 Newrank 热点技能页 `https://www.newrank.cn/search/trend/skill`，围绕 AI skill、workflow skill、Copilot skill、openclaw 相关方向组织选题，并输出爆款文案拆解线索。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md`。
2. 已读取 `.role-sessions/current_task.md`。
3. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合要求，因此继续。
4. 已检索 `SAF-TaskAssignAndProgress.md`，当前仓库内未找到该文件，因此在本轮留痕中明确记为缺失。
5. 已检查 Boss 目录既有 `BOSS-CYCLE-*.md` 留痕，确认继续沿用单文件 Boss 周期任务模式。
6. 已再次尝试获取 Newrank 技能趋势页信息；当前环境下未拿到可用详情，且用户要求的 `yhslgg-arch/url-reader` skill 在当前环境不可用，因此本轮继续明确：Topic 必须先写清 Newrank 受限情况，不得伪造趋势证据；若后续环境恢复该 fallback，再补抓取结果。
7. 已确认本轮仍只形成预览与手动发布所需内容包，不做公开发布。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS` 的本轮要求：围绕单一中文主题组织 Redbook 内容包，所有产物必须能归入 `date / timestamp+中文标题 / material files` 的归档结构。
- Topic：
  - 优先从 Newrank 技能趋势页提取话题线索，并记录可见的趋势证据；若拿不到详情，必须明确写出“Newrank 当前不可见/受限”的事实，不能臆造来源。
  - 当前环境里 `yhslgg-arch/url-reader` 不可用，这一限制也必须写入来源说明；若后续运行环境恢复该能力，再把 fallback 抓取结果补入 topic evidence。
  - 产出中必须包含“Viral Copy Breakdown”部分，至少拆出 hook、结构、节奏、CTA、情绪触发点，不得直接照抄原句。
  - 统一服务同一中文标题，并给出归档建议：`date / timestamp+中文标题 / material files`。
- Draft：
  - 必须继承 Topic 中真实可验证的来源状态：要么是 Newrank 可见线索，要么是“Newrank 受限 + url-reader 当前不可用”的事实说明。
  - 正文目标应围绕同一主题生成可预览、可复审、可手动发布的中文文案草稿。
  - 必须输出中文标题、正文、标签/设置，以及一个简短的 `viral-copy breakdown` 或 `Viral Rewrite Notes` 段落。
  - 只能改写爆款结构与钩子逻辑，不得复制来源句子。
- Cover：
  - 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
  - 主副标题保持短促直接，强化“技能趋势 + 工作流结果”感。
- Review：
  - 必须核验 Topic 是否优先说明了 Newrank 证据或受限情况。
  - 在当前环境下，如 `yhslgg-arch/url-reader` 仍不可用，Review 应检查 Topic 是否如实记录该限制，而不是把不存在的 fallback 结果当成已完成。
  - 必须核验 Draft 是否包含 Viral Rewrite Notes，且为结构改写而非句子复制。
  - 必须核验最终产物是否满足中文归档可用、可预览、可复审、可手动发布且不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、Copilot/Agent 协作技能、内容工作流归档与复盘。
- 内容重点：不是泛泛讲 AI，而是讲“看到趋势后，怎样把技能/工作流整理成可复用、可复审、可手动发布的内容包”。
- 推荐本轮收敛选题：`AI 工作流爆款，不是多会写提示词，而是先把归档链路搭好`。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离归档结构与中文标题主线。

## 归档要求
- 最终内容包应能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层用于归档日期。
- `timestamp+中文标题` 层用于单次内容包唯一标识。
- `material files` 层用于沉淀素材、趋势截图、引用摘要、封面源文件、正文依据与复审凭据。
- Boss 侧本轮文件名：`Boss/BOSS-CYCLE-20260311-170625.md`。

## 当前判断
- 本轮 Boss 侧需要的真实编辑是新增一份 Boss 周期任务文件，并把 Newrank-first、archive layout、以及 fallback 不可用时的真实记录要求写清。
- 由于当前环境中 `yhslgg-arch/url-reader` skill 不可用，Boss 不能要求下游角色伪造 fallback 结果；应要求其如实记录限制并在能力恢复后补证据。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）
- 缺失文件：`SAF-TaskAssignAndProgress.md` 当前未检索到
- Newrank 状态：已尝试读取但未取得可用详情
- Fallback 状态：用户要求的 `yhslgg-arch/url-reader` 当前环境不可用，已在 Boss 要求中明确记录限制
- 实际改动：新增 `Boss/BOSS-CYCLE-20260311-170625.md`
- 发布动作：未执行
