# Boss Cycle 20260315-034804

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，并确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已按规则检查 `SAF-TaskAssignAndProgress.md`；当前仓库内未找到该文件，已如实记录缺失状态。
4. 已复核上一轮稳定 Boss 任务文件与当前 `.role-sessions/BOSS.md` 口径，沿用其已确认的 archive package 约束、Newrank-first 来源边界、以及非公开发布边界。
5. 已检查当前会话可用 skill，仅有 `simplify` 与 `claude-api`；任务要求中的 `yhslgg-arch/url-reader` 当前不可用，因此 fallback 要求存在，但本会话不能执行，也不能伪造抓取结果。
6. 已复核现有 Topic 线索文件 `@TOPIC`：当前可确认的是 `https://www.newrank.cn/search/trend/skill` 为优先入口，且指定关键词在已留痕结果中未形成可直接引用的完整详情；因此下游只能如实写“入口优先检查过、细分详情不足/缺失、fallback skill 不可用”。
7. 已确认本轮 archive package 必须统一为：`2026-03-15 / 20260315-034804+AI技能流为什么开始从提示词转向可复用工作流资产 / material files`。
8. 已确认本轮只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能流为什么开始从提示词转向可复用工作流资产`。
- 统一归档日期：`2026-03-15`。
- 统一归档包：`2026-03-15 / 20260315-034804+AI技能流为什么开始从提示词转向可复用工作流资产 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只形成了邻近信号或详情不足状态。
- Topic 必须优先产出一个可直接支持“AI技能流为什么开始从提示词转向可复用工作流资产”的主选题。
- 如果 Newrank detail 不可用、受限或不稳定，必须明确写出：入口已优先检查、当前细分详情不足/缺失、不能把该页当成已验证细节来源。
- 如果 Newrank detail 不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-15`、`20260315-034804` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 在趋势表达上，要优先收口到“AI 的竞争点正在从会不会写提示词，转向能不能把一段流程拆清、跑顺、反复复用”，而不是泛泛讨论模型参数。

### 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前 Boss 可确认的稳定口径只有：该入口必须优先检查，但本轮并未拿到可放心扩写的细分详情，因此下游只能把它写成优先入口与检查对象，不能扩写成已核实的趋势正文事实。
2. **关键词方向与证据强弱**
   - `openclaw`：任务要求中必须优先关注，但本轮 Boss 侧没有新增到可独立引用的完整细节，只能写为重点检索词与方向词。
   - `openclaw skill`：同样属于重点方向词，但当前不能写成已拿到完整趋势详情。
   - `AI skill`：可作为主叙事关键词，但不能冒充已获得新榜细分热度细节。
   - `workflow skill`：适合承接“提示词 -> 工作流资产”的主题表达，但当前只能作为方向判断，不可伪造详情页事实。
   - `Copilot skill`：本轮仍只能写成重点检索方向之一，证据表达应最保守。
3. **内容层面的稳妥判断**
   - 当细分 trend detail 无法稳定验证时，更稳妥的内容方向不是编造榜单，而是围绕这些关键词共同指向的用户价值变化：用户越来越在意一套流程能否被拆解、复用、协作、归档，而不只是一次性回答是否漂亮。
   - 对小红书内容来说，这类“可以直接拿走照着做的路径”更容易形成收藏、复盘与手动发布前的预览价值。
4. **来源限制说明**
   - 当前能确认的是：Newrank 入口优先级明确；但细分详情没有在本会话形成可稳定复述的证据闭环。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增任何未经验证的在线细节、榜单数字、代表作品或爆文原句。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first、细分详情不足/缺失、fallback 不可用状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么只把 AI 当聊天框会越来越难形成复用价值、为什么 workflow skill 更容易沉淀成可反复调用的结果、怎样把选题 / 写稿 / 审稿 / 归档串成一条可重复执行的内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能流开始从提示词转向工作流资产`。
- 副标题建议突出：`真正拉开差距的，是可复用、可协作、可归档`。
- 视觉重点放在“从一次提问到整套执行链路”的升级感，以及选题、写稿、审稿、归档能被串起来的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 都已被列为优先检索方向，但本轮不可把它们写成已拿到完整细分详情。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260315-034804`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、OpenClaw 相关大众化关注、Copilot/Agent 协作技能、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在提示词层，而更容易被收藏和复用的是能让用户直接照着走一遍的路径型内容”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据边界、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-15`。
- `timestamp+中文标题` 层：`20260315-034804+AI技能流为什么开始从提示词转向可复用工作流资产`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260315-034804.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 当前判断
- 当前最大风险仍是来源留痕失真：`search/trend/skill` 细分详情没有稳定拿到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是 archive package 漂移：本轮所有下游都必须统一切到 `20260315-034804`，避免 Topic / Draft / Cover / Review 沿用旧时间戳导致归档包不一致。
- 当前内容机会点明确：用户对 AI 内容的价值判断，正从“会不会写 prompt”转向“能不能把一段流程稳定跑通并复用”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260315-034804.md`
- 发布动作：未执行
