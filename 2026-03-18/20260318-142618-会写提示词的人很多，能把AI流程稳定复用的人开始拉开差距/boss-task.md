# Boss Cycle 20260318-142618

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，并确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已尝试读取 `SAF-TaskAssignAndProgress.md`；当前仓库内未找到该文件，已如实记录缺失状态。
4. 已复核最近稳定留痕：`Boss/BOSS-CYCLE-20260318-135822.md`，以及同轮 `.role-sessions/logs/Topic-20260318-135822.log`、`Draft-20260318-135822.log`、`Cover-20260318-135822.log`、`Review-20260318-135822.log`，用于继承已验证的来源边界与发现上轮未统一归档包的问题。
5. 已确认当前会话可用 skill 只有 `simplify` 与 `claude-api`；任务要求中的 `yhslgg-arch/url-reader` 当前不可用，因此 fallback 要求存在，但本会话无法执行，不能伪造抓取结果。
6. 已确认本轮 Topic 仍必须优先把 `https://www.newrank.cn/search/trend/skill` 作为趋势入口写进来源状态；但当前没有新增可验证的 Newrank 深层详情抓取结果，因此只能如实写明“入口已检查、详情不可得、fallback skill 不可用”。
7. 已确认上轮 Review 结论为 **CONDITIONAL**，主要问题不是内容方向错误，而是 Topic / Cover / Review 的 archive package 未统一；因此本轮核心任务是统一包名与时间戳，并要求下游显式产出可归档 review artifact。
8. 已确认本轮 archive package 必须统一为：`2026-03-18 / 20260318-142618+AI技能内容进入下一阶段：真正拉开差距的，不是会不会写提示词，而是能不能把整套流程稳定复用 / material files`。
9. 已确认本轮只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能内容进入下一阶段：真正拉开差距的，不是会不会写提示词，而是能不能把整套流程稳定复用`。
- 统一归档日期：`2026-03-18`。
- 统一归档包：`2026-03-18 / 20260318-142618+AI技能内容进入下一阶段：真正拉开差距的，不是会不会写提示词，而是能不能把整套流程稳定复用 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只找到了邻近趋势信号。
- Topic 必须优先产出一个可直接支持“AI技能内容进入下一阶段：真正拉开差距的，不是会不会写提示词，而是能不能把整套流程稳定复用”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失/受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- **本轮必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量统一为：`2026-03-18`、`20260318-142618`、`AI技能内容进入下一阶段：真正拉开差距的，不是会不会写提示词，而是能不能把整套流程稳定复用`。不得再沿用任意旧时间戳或自拟短标题。**
- 在趋势表达上，要优先收口到“AI 的竞争点正在从会不会写提示词，转向能不能把一段流程拆清、跑顺、反复复用”，而不是泛泛讨论模型参数。

### 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求是优先使用该入口，但本轮仍未拿到可验证的深层详情；因此下游只能把它写成优先入口与检查对象，不能扩写成已核实正文事实。
2. **上轮已留痕的稳定线索可继续借用，但必须标注为“邻近趋势/入口线索”而非“详情页结论”**
   - 可沿用上轮已记录的判断：工作流、技能化调用、完整链路执行能力，比单点功能更适合被内容化成“可带走路径”。
   - 可继续收口到：用户更容易收藏“能拿去复用的流程”，而不是单次工具测评。
   - 不能新增未经本轮验证的在线细节或具体热度数字。
3. **关键词命中状态说明模板**
   - `openclaw`：如无新增直连结果，只能写“本轮仍以邻近线索为主”。
   - `openclaw skill`：如无新增直连结果，只能写“有邻近线索，但非 `search/trend/skill` 直连详情”。
   - `AI skill`：如无新增详情，只能写“方向相关，但缺少本轮可验证详情”。
   - `workflow skill`：可写“与本轮主题高度相关，但本轮仍以工作流化方向判断为主”。
   - `Copilot skill`：若无新证据，必须明确“检索证据不足”。
4. **来源限制说明**
   - 当前能确认的主要是 Newrank 优先入口本身，以及上轮已留痕的方向性判断；不是 `https://www.newrank.cn/search/trend/skill` 深层详情页本身。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增未经验证的在线细节，只能基于已知稳定边界继续收口。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果、公开检索仅得入口/邻近信号、fallback 不可用状态，以及本轮未拿到深层详情的限制状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么只把 AI 当聊天框会越来越难形成复用价值、为什么 workflow skill 更容易沉淀成可反复调用的结果、怎样把选题 / 写稿 / 审稿 / 归档串成一条可重复执行的内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- **归档目录、时间戳、中文标题必须与本轮统一 package 完全一致，不得沿用 `20260318-135822` 或任意其他时间戳。**
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能内容进入下一阶段`。
- 副标题建议突出：`不是提示词更长，而是流程能稳定复用`。
- 视觉重点放在“从单次回答到整套执行链路”的升级感，以及选题、写稿、审稿、归档能被串起来的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- **归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。不得自拟新的短标题包名。**

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw` 与 `openclaw skill` 当前若无新证据只能保留为邻近线索；`AI skill`、`workflow skill` 当前主要靠方向性证据支撑；`Copilot skill` 本轮若无新增结果则证据不足。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- **必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260318-142618` 与统一中文标题。任何一个角色不一致都算未通过。**
- **必须输出一个可直接归档的 Review artifact，不接受仅有口头结论。**
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、OpenClaw 相关大众化关注、Copilot/Agent 协作技能、节点式工作流、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在提示词层，而更容易被收藏和复用的是能让用户直接照着走一遍的路径型内容”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-18`。
- `timestamp+中文标题` 层：`20260318-142618+AI技能内容进入下一阶段：真正拉开差距的，不是会不会写提示词，而是能不能把整套流程稳定复用`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260318-142618.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 当前判断
- 当前最大风险仍是来源留痕失真：`search/trend/skill` 精确详情没有稳定拿到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险仍是 archive package 漂移：本轮所有下游都必须统一切到 `20260318-142618`，避免 Topic / Draft / Cover / Review 再次出现不同时间戳或不同中文标题。
- 当前内容机会点明确：用户对 AI 内容的价值判断，正从“会不会写 prompt”转向“能不能把一段流程稳定跑通并复用”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260318-142618.md`
- 发布动作：未执行
