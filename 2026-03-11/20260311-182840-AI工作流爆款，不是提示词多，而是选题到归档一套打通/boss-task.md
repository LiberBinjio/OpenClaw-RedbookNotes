# Boss Cycle 20260311-182840

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md`。
2. 已读取 `.role-sessions/current_task.md`。
3. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合要求，因此继续。
4. 已检索 `SAF-TaskAssignAndProgress.md`，当前仓库内未找到该文件，因此在本轮留痕中明确记为缺失。
5. 已复核既有 Boss 周期文件，确认本轮仍应延续“单一主题 + 单一归档包”的收口方式，并保持 Boss 只写一个任务文件。
6. 已按要求优先尝试获取 Newrank 技能趋势页 `https://www.newrank.cn/search/trend/skill` 的可用详情；当前 `WebFetch` 工具返回模型级错误，未产出任何可靠页面内容，因此本轮不得伪造 Newrank 趋势证据。
7. 已按要求检查 fallback：尝试调用 `yhslgg-arch/url-reader` 技能时，系统直接返回 `Unknown skill: yhslgg-arch/url-reader`，说明该 fallback 要求存在，但在当前环境不可用。
8. 已确认本轮继续只准备预览与手动发布内容，不执行公开发布。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI 工作流爆款，不是提示词多，而是选题到归档一套打通`。
- 统一归档日期：`2026-03-12`。
- 统一归档包：`2026-03-12 / 20260311-182840+AI工作流爆款，不是提示词多，而是选题到归档一套打通 / material files`。

### Topic 要求
- 继续优先从 Newrank 技能趋势页找线索，围绕 AI skill、workflow skill、Copilot skill、openclaw 相关方向组织选题。
- 由于本轮 Newrank 页详情未成功获取，必须明确写出“已尝试获取，但当前抓取工具报错，暂无可靠详情”的事实，不能臆造趋势证据。
- 由于 `yhslgg-arch/url-reader` 当前环境返回 `Unknown skill`，必须如实写入来源说明，不能把 fallback 写成已完成。
- 必须新增明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、节奏、CTA、情绪触发点；只能拆模式，不能抄原句。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-12`、`20260311-182840` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 交付必须仍能直接给 Draft 使用。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态：当前只能写“Newrank 尝试抓取失败 + url-reader fallback 不可用”的事实说明。
- 必须围绕统一主题输出中文标题、正文、标签，并保留 `Viral Rewrite Notes` 或等价的 viral-copy breakdown 说明。
- 只能改写爆款结构与钩子逻辑，不得复制来源句子。
- 正文建议重点写清三段：为什么 AI 内容容易越做越乱、为什么真正的爆款来自流程收口、怎样把选题/草稿/封面/复审塞进同一个 archive package。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI工作流爆款`。
- 副标题建议突出：`不是提示词多，是归档链路顺`。
- 视觉重点放在“选题 → Draft → Cover → Review → Archive”这条链路的结果感。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先说明了 Newrank 证据缺失的真实原因：本轮是抓取工具报错，而不是已读到详情。
- 必须核验 Topic 是否如实记录 `yhslgg-arch/url-reader` 返回 `Unknown skill`，而不是伪造 fallback 结果。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown`。
- 必须核验 Topic / Draft / Cover 的 archive timestamp 与 archive package 是否统一到 `20260311-182840`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、Copilot/Agent 协作技能、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“爆款内容背后真正可复制的，不只是提示词，而是选题、改写、封面、复审、归档的整套链路”。
- 本轮重点不是新增第二主题，而是围绕单一主题收口，并把来源限制、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-12`。
- `timestamp+中文标题` 层：`20260311-182840+AI工作流爆款，不是提示词多，而是选题到归档一套打通`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260311-182840.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 当前判断
- 当前最大卡点有三处：
  1. Newrank 详情本轮未能成功抓到，不能提供可靠趋势细节。
  2. 要求中的 `yhslgg-arch/url-reader` fallback 在当前环境不存在，不能执行。
  3. 下游仍需把旧归档包统一切换到本轮时间戳，并补齐 `Viral Copy Breakdown` 留痕。
- 因此本轮 Boss 的核心任务不是换题，而是把来源限制、viral-copy breakdown 要求、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 当前环境下不得伪造 Newrank 详情，也不得伪造 `yhslgg-arch/url-reader` 结果。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）
- 缺失文件：`SAF-TaskAssignAndProgress.md` 当前未找到
- Newrank 状态：已尝试，但 `WebFetch` 返回模型级错误，当前无可靠详情可引用
- Fallback 状态：`yhslgg-arch/url-reader` 当前环境不可用，系统返回 `Unknown skill`
- 实际改动：新增 `Boss/BOSS-CYCLE-20260311-182840.md`
- 发布动作：未执行
