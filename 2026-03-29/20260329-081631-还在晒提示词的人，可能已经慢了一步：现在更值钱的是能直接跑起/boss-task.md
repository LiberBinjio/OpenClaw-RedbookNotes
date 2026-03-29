# Boss Cycle 20260329-081631

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，并确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已尝试查找 `SAF-TaskAssignAndProgress.md`；当前仓库内未找到该文件，已如实记录缺失状态。
4. 已复核上一轮稳定留痕 `Boss/BOSS-CYCLE-20260312-205815.md`，沿用其已确认的来源边界、archive package 约束与非公开发布边界。
5. 已再次确认当前会话可用 skill 只有 `simplify` 与 `claude-api`；任务要求中的 `yhslgg-arch/url-reader` 当前不可用，因此 fallback 要求存在，但本会话无法执行，不能伪造抓取结果。
6. 已优先尝试围绕 `https://www.newrank.cn/search/trend/skill` 获取趋势入口信息；当前环境未成功拿到该入口的可验证详情内容，因此本轮只能把它写成优先入口与检查对象，不能扩写成已核实详情。
7. 已补充 Newrank / Voice Newrank 邻近公开趋势线索，确认近期更强的可见传播点集中在 `OpenClaw + Skill`、技能社区、工作流玩法、可安装能力包，而不是单独的提示词讨论。
8. 已确认本轮 archive package 必须统一为：`2026-03-29 / 20260329-081631+AI技能开始卷交付了：真正能反复带走的，不是提示词截图，而是一套装上就能跑的工作流 / material files`。
9. 已确认本轮只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能开始卷交付了：真正能反复带走的，不是提示词截图，而是一套装上就能跑的工作流`。
- 统一归档日期：`2026-03-29`。
- 统一归档包：`2026-03-29 / 20260329-081631+AI技能开始卷交付了：真正能反复带走的，不是提示词截图，而是一套装上就能跑的工作流 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只找到了邻近趋势信号。
- Topic 必须优先产出一个可直接支持“AI技能开始卷交付了：真正能反复带走的，不是提示词截图，而是一套装上就能跑的工作流”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失/受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-29`、`20260329-081631` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 在趋势表达上，要优先收口到“AI 内容的竞争点正在从会不会写 prompt，转向能不能把技能装上、流程跑通、结果反复交付”，而不是泛泛讨论模型参数。

### 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求是优先使用该入口，但本轮仍未拿到可验证的深层详情；因此下游只能把它写成优先入口与检查对象，不能扩写成已核实正文事实。
2. **`openclaw` / `openclaw skill` 邻近趋势线索**
   - `百度电商Skill登陆OpenClaw，五大能力全开放`（newrank.cn，2026-02-13）是当前最直接的 `OpenClaw + Skill` 邻近公开结果，可支撑“技能开始被平台化、能力包化”的表达。
   - `腾讯再推“养虾”新措施，上线“中国专供”SkillHub`（newrank.cn，2026-03-11）可支撑“技能发现、下载、排行、中文搜索开始被打包成社区化入口”的表达。
   - `装上了，然后呢？我们盘点了“养龙虾”的11种经典玩法`（newrank.cn，2026-03-13）可支撑“大家开始关心装好以后能不能直接跑起来”的玩法型传播语境。
   - `腾讯版“小龙虾”WorkBuddy正式上线`（newrank.cn，2026-03-09）可支撑“兼容 OpenClaw skills 的工作助手正在被包装成更可直接使用的职场能力”。
3. **`AI skill` / `workflow skill` 邻近趋势线索**
   - `千问请喝奶茶9小时破1000万单，总榜暂居第九有望继续飞升；MiniMax上升33位 | AI产品月榜`（voice.newrank.cn，2026-02-06）提到 2026 年 1 月 AI 编码平台中 Skills 模块扩张，可作为“技能化能力正在大规模进入 AI 产品”的邻近证据。
   - `百度智能云发布DuClaw`（voice.newrank.cn，2026-03-11）可支撑“零部署、内置搜索与知识类 Skills、多模型接入”正在成为可传播卖点。
   - 可继续沿用稳定判断：比起单个功能点，工作流、技能市场、可安装能力包、整条执行链路，更容易形成“看完就能照着做”的内容价值感。
4. **`Copilot skill` 邻近趋势线索**
   - 当前仍未拿到明确的 `Copilot skill` 直连 Newrank 详情结果。
   - 因此 `Copilot skill` 本轮只能写成“检索不足、暂无直连详情”，不能伪造成已抓到趋势正文。
5. **关键词命中状态说明**
   - `openclaw`：本轮有稳定 Newrank 邻近线索。
   - `openclaw skill`：本轮有 `OpenClaw + Skill` 邻近文章线索，但仍非 `search/trend/skill` 直连详情。
   - `AI skill`：本轮没有 `search/trend/skill` 直连详情，但有 AI 产品榜、Skills 模块扩张、能力包化等邻近信号。
   - `workflow skill`：没有 `search/trend/skill` 直连详情，但有工作助手、SkillHub、装上就能用的玩法内容等邻近信号。
   - `Copilot skill`：本轮未获得明确直连结果，证据最弱。
6. **来源限制说明**
   - 当前能确认的主要是 Newrank 主站与 `voice.newrank.cn` 的标题/摘要级线索，不是 `https://www.newrank.cn/search/trend/skill` 深层详情页本身。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增未经验证的在线细节，只能基于已留痕标题/摘要级线索与当前稳定判断继续收口。

### Viral Copy Breakdown
- **hook**：先打掉“AI 内容还在卷提示词”的旧认知，再抛出“现在卷的是能不能直接交付一条跑得通的工作流”。
- **结构**：先指出旧内容为什么不耐用，再给出行业变化线索，最后落到“什么样的内容更值得收藏与转发”。
- **冲突点**：用户以为自己缺的是更长提示词，真实缺的是可安装、可执行、可复用的技能链路。
- **承诺**：看完不只是被种草，而是知道什么内容结构更容易被保存、复用、手动发布。
- **证据**：用 OpenClaw + Skill、SkillHub、WorkBuddy、DuClaw、AI 产品月榜中的 Skills 模块等邻近趋势做支撑，但明确不是深层详情直引。
- **CTA**：引导读者从“收藏一句提示词”切换到“收藏一套可复用流程”，为后续手动发布/预览留出动作口。

### Rewrite Direction
- 保留的模式：趋势反转式开头、旧认知与新认知对撞、案例串联、最后收口到可执行方法。
- 必须改写的表达：所有爆款句式、情绪化断言、平台标题原句、摘要原句都只能改结构与意思，不能照抄。
- 绝不能复制的内容：任何 Newrank / Voice Newrank 标题原句、列表句式、结论句式都不能原样进入 Draft 正文。
- 推荐改写方向：从“技能生态在升温”切到“普通创作者真正能带走的，是被打包好的执行路径”，把平台新闻翻成用户视角价值。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果、公开检索仅得邻近信号、fallback 不可用状态，以及本轮未拿到深层详情的限制状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么只把 AI 当聊天框会越来越难形成复用价值、为什么“装上就能用的技能/工作流”更容易沉淀成内容资产、怎样把选题 / 写稿 / 审稿 / 归档串成一条可重复执行的内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能开始卷交付了`。
- 副标题建议突出：`不是提示词截图，而是一套装上就能跑的工作流`。
- 视觉重点放在“从聊天回答到可安装能力包/整条执行链路”的升级感，以及选题、写稿、审稿、归档能被串起来的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw` 与 `openclaw skill` 当前有稳定 Newrank 邻近线索，但 `search/trend/skill` 直连详情仍缺失；`AI skill`、`workflow skill` 当前主要靠邻近趋势证据支撑；`Copilot skill` 本轮检索证据不足。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260329-081631`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、OpenClaw 相关大众化关注、SkillHub / 工作助手 / 零部署技能方案、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在提示词层，而更容易被收藏和复用的是能让用户直接照着走一遍的路径型内容”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-29`。
- `timestamp+中文标题` 层：`20260329-081631+AI技能开始卷交付了：真正能反复带走的，不是提示词截图，而是一套装上就能跑的工作流`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260329-081631.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 检索来源备注
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 本轮可沿用的公开可见 Newrank / Voice Newrank 邻近结果包括：
  - `https://www.newrank.cn/article/detail/33856?utm_source=openai`
  - `https://www.newrank.cn/article/detail/34022?utm_source=openai`
  - `https://www.newrank.cn/article/detail/34041?utm_source=openai`
  - `https://voice.newrank.cn/study/detail/4DBD86A66136B9D8?utm_source=openai`
  - `https://voice.newrank.cn/study/detail/03CF58DF7130A995?utm_source=openai`
  - `https://www.newrank.cn/article/detail/34014?utm_source=openai`
  - `https://www.newrank.cn/article/detail/33993?utm_source=openai`
  - `https://voice.newrank.cn/study/detail/A0EFD08F9AC1D6EA?utm_source=openai`
- 上述链接与留痕当前仅可作为标题 / 摘要片段 / 邻近趋势方向级证据使用，不能扩写成未验证正文事实。
- 当前会话可用 skill 列表未提供 `yhslgg-arch/url-reader`，因此 fallback 要求只能记录为未满足的环境限制。
- 本轮仍未获得 `https://www.newrank.cn/search/trend/skill` 的可验证详情页正文，因此只能记录为“已优先检查入口与邻近公开结果，但未成功取得可验证深层详情”。

## 当前判断
- 当前最大风险仍是来源留痕失真：`search/trend/skill` 精确详情没有稳定拿到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是 archive package 漂移：本轮所有下游都必须统一切到 `20260329-081631`，避免 Topic / Draft / Cover / Review 沿用旧时间戳导致归档包不一致。
- 当前内容机会点明确：用户对 AI 内容的价值判断，正在从“会不会写 prompt”转向“能不能把一个技能装上、把一段流程跑通、把结果稳定交付出来”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260329-081631.md`
- 发布动作：未执行
