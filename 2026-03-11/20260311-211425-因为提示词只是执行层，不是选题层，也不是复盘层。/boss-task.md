# Boss Cycle 20260311-211425

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md`。
2. 已读取 `.role-sessions/current_task.md`。
3. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合要求，因此继续。
4. 已检查当前仓库结构，确认已有归档日期目录 `2026-03-12/`，本轮任务必须继续兼容该归档方式。
5. 已复核当前任务提示，确认 Topic 仍需优先从 `https://www.newrank.cn/search/trend/skill` 获取趋势线索，并且必须输出 viral-copy breakdown。
6. 已确认当前会话可用技能列表中未看到 `yhslgg-arch/url-reader`，因此本轮只能要求下游先检查该 skill 是否在实际执行环境可用；若不可用，必须明确记录 skill 缺失或不可调用，不得伪造 fallback 抓取结果。
7. 已确认 Draft 必须改写爆款结构与节奏，不得复制原句。
8. 已确认本轮只准备预览与手动发布内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能内容不是不够努力，而是你一直少了“趋势验证—工作流改写—归档复盘”这条爆款闭环`。
- 统一归档日期：`2026-03-12`。
- 统一归档包：`2026-03-12 / 20260311-211425+AI技能内容不是不够努力，而是你一直少了“趋势验证—工作流改写—归档复盘”这条爆款闭环 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织 Topic 检索方向。
- 必须优先产出一个可直接支持“AI技能内容为什么难跑出来，本质卡在趋势验证、工作流改写和归档复盘断裂”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失/受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，必须先尝试 `yhslgg-arch/url-reader` fallback；若实际环境不存在该 skill 或仍不可用，必须如实写出不可用状态，不能伪造抓取结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须新增明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须新增明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-12`、`20260311-211425` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果与 `yhslgg-arch/url-reader` fallback 的实际状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么 AI 技能内容常常停留在“会写提示词”但跑不出结果、为什么真正能跑出来的是“趋势验证 + 工作流改写 + 归档复盘”闭环、怎样把 Topic / Draft / Cover / Review / archive package 串成一条内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能内容为什么总是跑不出来`。
- 副标题建议突出：`因为你少了爆款闭环`。
- 视觉重点放在“Newrank 趋势验证 → Topic 拆爆款 → Draft 改写 → Cover 包装 → Review 复审 → Archive 归档”这条链路的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 如果 Newrank 详情不可用，必须核验 Topic 是否先尝试了 `yhslgg-arch/url-reader` fallback，并如实记录结果；若未尝试或写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover 的 archive timestamp 与 archive package 是否统一到 `20260311-211425`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、Copilot/Agent 协作技能、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 技能内容停在提示词层，真正能跑出来的是把趋势验证、工作流改写、归档复盘连成闭环”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-12`。
- `timestamp+中文标题` 层：`20260311-211425+AI技能内容不是不够努力，而是你一直少了“趋势验证—工作流改写—归档复盘”这条爆款闭环`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260311-211425.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 当前判断
- 当前最大风险仍是来源留痕失真：Newrank 详情拿不到，就必须诚实写限制；`yhslgg-arch/url-reader` 若不可用，也必须诚实写不可用。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 义务、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）
- 实际改动：新增 `Boss/BOSS-CYCLE-20260311-211425.md`
- 发布动作：未执行
