# Boss Cycle 20260328-100458

@ALL
@BOSS

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，满足继续工作的前提。
3. 已尝试读取 `SAF-TaskAssignAndProgress.md`；当前仓库根目录不存在该文件，已如实记录缺失状态。
4. 已复核前一轮 Boss 留痕 `Boss/BOSS-CYCLE-20260328-093033.md` 与 `.role-sessions/BOSS.md`，确认本轮要继续沿用“Newrank 优先、趋势限制如实写明、统一 archive package、不自动公开发布”的口径，同时把时间戳统一切到 `20260328-100458`。
5. 已尝试检查 `https://www.newrank.cn/search/trend/skill`；当前 `WebFetch` 返回模型不支持导致的 `API Error 400`，因此本轮不能把在线取数写成成功抓取。
6. 按任务要求，如 Newrank 详情受限应使用 `yhslgg-arch/url-reader` 作为 fallback；但当前会话可用 skill 只有 `simplify` 与 `claude-api`，缺少该 skill，因此不能伪造 fallback 结果，只能把它写成环境限制。
7. 已确认本轮 archive package 统一为：`2026-03-28 / 20260328-100458+AI技能别再只换模型，先把工作流接起来 / material files`。
8. 本轮继续只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能别再只换模型，先把工作流接起来`。
- 统一归档日期：`2026-03-28`。
- 统一归档包：`2026-03-28 / 20260328-100458+AI技能别再只换模型，先把工作流接起来 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只找到了邻近趋势信号。
- Topic 必须优先产出一个可直接支持“AI技能别再只换模型，先把工作流接起来”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失或受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-28`、`20260328-100458`、`AI技能别再只换模型，先把工作流接起来`。
- 在趋势表达上，要优先收口到“AI 的差距不只在模型能力，而在能不能把输入、协作、校验与归档串成稳定流程”，而不是泛泛讨论模型参数。

### 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求是优先使用该入口，但本轮直接检查返回 `WebFetch API Error 400`，且错误原因为工具侧模型不支持，不是已经拿到可验证页面详情。
   - 因此下游只能把它写成优先入口与检查对象，不能扩写成已核实正文事实。
2. **`openclaw` / `openclaw skill` 邻近趋势线索**
   - 可沿用前序已留痕的 Newrank 邻近公开结果作为趋势方向级证据：`百度电商Skill登陆OpenClaw，五大能力全开放`、`Kimi推出OpenClaw云托管服务，跻身总榜前十；字节Seedance 2.0助力即梦排名上升 | AI产品月榜`、`百度智能云推出移动端OpenClaw部署方案`、`百度App接入OpenClaw 2周，超2成用户调用于投资理财分析`。
   - 这些线索足以支持“OpenClaw / Skill / 可复用能力”仍在传播语境中活跃，但都属于 Newrank 域名下的邻近公开文章，不是 `search/trend/skill` 深层详情页本身。
3. **`AI skill` / `workflow skill` 邻近趋势线索**
   - 可沿用已留痕的节点式工作流与 AI 榜单信号，例如 `Krea AI推出节点式工作流工具Nodes，总榜排名上升34位；通义千问总榜排名攀升68位 | AI产品周榜`，用于支撑“工作流 / 技能化调用 / 完整链路执行能力更容易形成传播点”的表达。
   - 可继续沿用稳定判断：工作流、节点式组织、技能化调用、完整链路执行能力，比单点功能更适合被内容化成“可带走路径”。
   - 本轮没有拿到 `workflow skill` 在 `search/trend/skill` 下的直连详情，因此 Topic 必须明确这是邻近趋势，不是精确详情页结论。
4. **`Copilot skill` 邻近趋势线索**
   - 当前仍只拿到泛站内页、导航页与 AI 榜单页级别留痕，没有明确 `Copilot skill` 直连结果。
   - 因此 `Copilot skill` 本轮只能写成“检索不足、暂无直连详情”，不能伪造成已抓到趋势正文。
5. **关键词命中状态说明**
   - `openclaw`：有稳定 Newrank 邻近线索。
   - `openclaw skill`：有 `OpenClaw + Skill` 邻近文章线索，但仍非 `search/trend/skill` 直连详情。
   - `AI skill`：没有 `search/trend/skill` 直连详情，但可沿用 AI 产品榜、调用链路组织能力等邻近信号。
   - `workflow skill`：没有 `search/trend/skill` 直连详情，但有节点式工作流与完整执行链路等邻近信号。
   - `Copilot skill`：未获得明确直连结果，仅有泛站内页留痕，证据最弱。
6. **来源限制说明**
   - 当前能确认的主要仍是 Newrank 主站与前序 Boss 留痕中的标题/摘要级线索，不是 `https://www.newrank.cn/search/trend/skill` 深层详情页本身。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增未经验证的在线细节，只能基于已留痕标题/摘要级线索与当前稳定判断继续收口。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果、公开检索仅得邻近信号、fallback 不可用状态，以及本轮未拿到深层详情的限制状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议框架：
  1. 先做认知反转：不是 AI 不够强，而是 workflow 没接上；
  2. 再做痛点代入：为什么同样接了 AI skill / copilot / workflow，结果还是忽高忽低；
  3. 中段拆 3 个流程断点：输入混乱、过程不可复用、结果没人校验；
  4. 给一套轻量解法：固定输入模板 + 角色拆分 + 输出复核；
  5. 结尾做收藏 / 评论型 CTA。
- 正文语气优先使用“踩坑后复盘”口吻，不写成工具测评，也不写成空泛方法论。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能别再只换模型`。
- 副标题建议突出：`先把工作流接起来`。
- 视觉重点放在“流程断点、协作链路、稳定交付”的升级感，以及选题、写稿、审稿、归档能被串起来的结果感。
- 避免元素：榜单截图、虚构热度、夸张收益承诺、自动发布暗示。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw` 与 `openclaw skill` 当前有稳定 Newrank 邻近线索，但 `search/trend/skill` 直连详情仍缺失；`AI skill`、`workflow skill` 当前主要靠邻近趋势证据支撑；`Copilot skill` 本轮检索证据不足。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260328-100458`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、OpenClaw 相关大众化关注、Copilot / Agent 协作技能、节点式工作流、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在换模型层，而更容易被收藏和复用的是能让用户直接照着走一遍的路径型内容”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、viral-copy breakdown、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-28`。
- `timestamp+中文标题` 层：`20260328-100458+AI技能别再只换模型，先把工作流接起来`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260328-100458.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 检索来源备注
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 当前可沿用的公开可见 Newrank 邻近结果，以前序稳定留痕为准，仅可作为标题 / 摘要片段 / 邻近趋势方向级证据使用，不能扩写成未验证正文事实。
- 前序留痕可复核位置：
  - `Boss/BOSS-CYCLE-20260328-093033.md`
  - `Boss/BOSS-CYCLE-20260328-085709.md`
  - `.role-sessions/BOSS.md`
  - `.role-sessions/current_task.md`
- 当前会话可用 skill 列表未提供 `yhslgg-arch/url-reader`，因此 fallback 要求只能记录为未满足的环境限制。
- 本轮尝试检查 `https://www.newrank.cn/search/trend/skill` 时，`WebFetch` 返回 `API Error 400`，错误原因为工具侧模型不支持，因此本轮仍未获得可验证详情页正文，只能记录为“已优先检查入口，但未成功取得可验证深层详情”。

## 当前判断
- 当前最大风险仍是来源留痕失真：`search/trend/skill` 精确详情没有稳定拿到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是 archive package 漂移：本轮所有下游都必须统一切到 `20260328-100458`。
- 当前内容机会点明确：用户对 AI 内容的价值判断，正从“会不会换更强模型”转向“能不能把一段流程稳定跑通并复用”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260328-100458.md`
- 发布动作：未执行
