# Boss Cycle 20260329-084942

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已查找 `SAF-TaskAssignAndProgress.md`；当前仓库内未找到该文件，已如实记录缺失状态。
4. 已复核既有留痕：`.role-sessions/BOSS.md`、`.role-sessions/Topic/TOPIC.md`，以及 `2026-03-29/20260329-074101+OpenClaw内容别再只写装上了没，更值得写的是Skill怎么接进交付流程/@DRAFT.md`，沿用其已确认的来源边界、archive package 约束、viral-copy breakdown 要求与非公开发布边界。
5. 已尝试按要求优先检查 `https://www.newrank.cn/search/trend/skill`；当前 `WebFetch` 返回 `API Error 400`，报错为请求模型不受支持，因此本轮未取得可核验的 Newrank 深层详情。
6. 已再次确认：任务要求中的 fallback `yhslgg-arch/url-reader` 在当前会话可用 skills 中不存在，因此无法实际执行该降级链路，不能把 fallback 写成已完成。
7. 已确认本轮统一 archive package 为：`2026-03-29 / 20260329-084942+OpenClaw内容别再只写装上了没，更值得写的是Skill怎么接进交付流程 / material files`。
8. 已确认本轮只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`OpenClaw内容别再只写装上了没，更值得写的是Skill怎么接进交付流程`。
- 统一归档日期：`2026-03-29`。
- 统一归档包：`2026-03-29 / 20260329-084942+OpenClaw内容别再只写装上了没，更值得写的是Skill怎么接进交付流程 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直连详情、哪些词只有邻近趋势线索。
- Topic 必须优先产出一个可直接支持“OpenClaw 内容不只写安装，而是写 Skill 如何接进交付流程”的主选题。
- 如果 Newrank 详情不可用，必须明确写出：入口已优先检查，但本轮未成功取得可验证深层详情。
- Topic 必须把本轮真实限制写清：`WebFetch` 检查 Newrank 时报 `API Error 400`；指定 fallback `yhslgg-arch/url-reader` 当前环境不可用，因此不能把 fallback 写成已执行成功。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-29`、`20260329-084942` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 在趋势表达上，要优先收口到：用户真正更愿意收藏的，不是“装上了没”，而是“Skill 放在哪个节点、怎么接进 workflow、结果怎样稳定交付”。
- 不得编造 Newrank 排名、热度值、爆文链接或任何未取到的详情字段。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first、详情未取到、fallback skill 不可用这三层限制。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 正文必须重写爆款结构，不得复制原句；重点不是新闻复述，而是把“Skill 怎么接进交付流程”讲清。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清四段：
  1. 为什么只写“装上了没”已经不够；
  2. 为什么很多 AI / OpenClaw 内容真正卡在 workflow 断点；
  3. Skill 接进交付链路后，哪些节点最容易稳定结果；
  4. 怎样把选题 / 起草 / 复核 / 归档串成一条可重复执行的内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`别再只写装上了没`。
- 副标题建议突出：`更值得写的是 Skill 怎么接进交付流程`。
- 视觉重点放在“从安装尝鲜到流程交付”的升级感，以及节点协作、复核闭环、结果沉淀。
- 避免元素：虚构热度、榜单截图、夸张收益承诺、自动发布暗示。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否如实写出：`WebFetch` 检查 Newrank 失败；`yhslgg-arch/url-reader` 当前不可用；因此没有新增可核验深层详情。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260329-084942`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。
- 若出现未验证的数据、排名、热度、爆文链接、或把 fallback 写成已成功执行，直接打回。

## 推荐选题边界
- 优先方向：OpenClaw、OpenClaw skill、AI skill、workflow skill、copilot skill、节点式工作流、内容交付、结果复用、归档整理。
- 内容重点：不是泛泛讲 AI，也不是只讲安装，而是讲“为什么 Skill 只有接进 workflow 和交付链路，才更容易形成稳定结果”。
- 本轮重点不是扩多个题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-29`。
- `timestamp+中文标题` 层：`20260329-084942+OpenClaw内容别再只写装上了没，更值得写的是Skill怎么接进交付流程`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260329-084942.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 检索来源备注
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 本轮检查结果：`WebFetch` 返回 `API Error 400`，当前未拿到该入口的可验证详情内容。
- 当前会话可用 skill 列表未提供 `yhslgg-arch/url-reader`，因此 fallback 要求只能记录为未满足的环境限制。
- 若下游需要补充趋势论证，只能沿用当前已留痕的公开可见邻近方向与任务指定关键词，不得扩写成未验证正文事实。
- 本轮未进行任何公开发布或外部可见发布动作。

## 当前判断
- 当前最大风险仍是来源留痕失真：Newrank 精确详情没有拿到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是 archive package 漂移：本轮所有下游都必须统一切到 `20260329-084942`，避免 Topic / Draft / Cover / Review 沿用旧时间戳导致归档包不一致。
- 当前内容机会点明确：用户对 OpenClaw / AI skill 内容的关注点，正在从“装上了没”转向“能不能接进真实任务并稳定交付”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前未找到
- 实际改动：新增 `Boss/BOSS-CYCLE-20260329-084942.md`
- 发布动作：未执行
