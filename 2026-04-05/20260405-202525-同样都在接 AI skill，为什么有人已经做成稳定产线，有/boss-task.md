# Boss Cycle 20260405-202525

## 当前重点
- 当前继续按 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进统一归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，确认本轮仍需优先使用 `https://www.newrank.cn/search/trend/skill` 作为一手趋势入口。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，满足继续工作的前提。
3. 已检查角色指令：
   - `Topic/CLAUDE.md` 要求 Topic 先走 Newrank，再在必要时使用 `yhslgg-arch/url-reader` fallback，并输出 `Viral Copy Breakdown` 与 `Rewrite Direction`。
   - `Draft/CLAUDE.md` 要求 Draft 继承 Newrank-first 证据状态，只改写爆款结构，不复制原句。
   - `Review/CLAUDE.md` 要求复审必须校验 Newrank-first、fallback 状态、以及非抄写质量。
4. 本轮尝试直接抓取 `https://www.newrank.cn/search/trend/skill` 时，当前会话未拿到可验证的深层详情；因此不能把该页详情写成已核实事实。
5. 按当前 live task，如果 Newrank detail 不可用，应使用 `yhslgg-arch/url-reader` 作为 required fallback；但当前会话可用 skill 列表只有 `simplify` 与 `claude-api`，没有 `yhslgg-arch/url-reader`，因此不能伪造 fallback 抓取结果。
6. 本轮还尝试使用在线抓取工具补充 Newrank 页面信息，但返回的是工具侧 `API Error 400`，不能视为取数成功，也不能当作来源证据。
7. 已复核历史稳定约束：必须如实记录来源限制、必须做 archive-ready 输出、必须把 viral pattern 拆成可改写结构、不得自动公开发布。

## 本轮统一归档包
- date: `2026-04-06`
- timestamp: `20260405-202525`
- archive_title: `为什么AI工作流内容比单条提示词更容易被收藏：用户真正想带走的是一套可直接复用的路径`
- archive_package: `2026-04-06 / 20260405-202525+为什么AI工作流内容比单条提示词更容易被收藏：用户真正想带走的是一套可直接复用的路径 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## 本轮主选题
- 推荐统一主题：`为什么AI工作流内容比单条提示词更容易被收藏：用户真正想带走的是一套可直接复用的路径`
- 主题收口方向：不要泛泛讲某个 AI 工具更强，而要讲用户为什么越来越偏向收藏“能直接照着跑”的完整流程内容。
- 内容语境关键词仍优先围绕：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill`。

## 来源状态与风险边界
### 1. Newrank-first 约束
- Topic 必须先写明：一手趋势入口是 `https://www.newrank.cn/search/trend/skill`。
- Topic 必须明确写出本轮真实状态：入口已优先检查，但当前未拿到可验证的深层详情。
- 禁止把不可见详情、未抓到的榜单字段、未核实热度值写成事实。

### 2. Required fallback 约束
- 按 live task，如果 Newrank detail 不可用，应使用 `yhslgg-arch/url-reader` 作为 required fallback。
- 但本轮当前环境没有该 skill，不能执行，也不能伪造“已抓取详情”或“已走 Firecrawl/Jina/Playwright 自动降级”。
- Topic / Draft / Review 都必须把这一点写成真实限制：`fallback 要求存在，但当前会话 skill 缺失，不可调用`。

### 3. 证据使用边界
- 本轮允许使用的证据层级，仍然只限于：
  - Newrank 优先入口已检查但详情受限这一事实；
  - 仓库内 Boss 历史留痕中的已记录标题/摘要级线索；
  - 当前会话里可确认的工具失败状态。
- 本轮不新增未经验证的在线细节，不把工具报错包装成趋势事实。

### 4. 内容风险
- 最大风险仍是来源失真：没有拿到 `search/trend/skill` 深层详情，就必须诚实写限制。
- 第二风险仍是爆款改写越界：只能拆结构、节奏、承诺、证据与 CTA，不能复制原句。
- 第三风险仍是归档包漂移：Topic / Draft / Cover / Review 的日期、时间戳、归档标题、archive package 必须完全统一。

## Topic 要求
- 必须优先把 `https://www.newrank.cn/search/trend/skill` 写进 `Source Status`。
- 必须按关键词写清覆盖状态：
  - `openclaw`
  - `openclaw skill`
  - `AI skill`
  - `workflow skill`
  - `copilot skill`
- 必须明确区分：哪些词有稳定直接线索，哪些词当前只有邻近趋势方向，哪些词没有直连详情。
- 必须明确写出：本轮未拿到 Newrank 深层详情，且 `yhslgg-arch/url-reader` 当前不可用。
- Topic 必须产出可直接给 Draft 使用的中文 topic package，至少包含：
  - 主选题
  - 3-5 个备选题
  - 目标人群
  - 趋势线索
  - viral references
  - rewrite angle
  - hook breakdown
- 必须新增 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA。
- 必须新增 `Rewrite Direction` 段落，明确哪些模式保留、哪些表达改写、哪些内容绝不能复制。
- Topic 的 archive 字段必须统一到本轮：
  - `date: 2026-04-06`
  - `timestamp: 20260405-202525`
  - `archive_title: 为什么AI工作流内容比单条提示词更容易被收藏：用户真正想带走的是一套可直接复用的路径`
  - `archive_package: 2026-04-06 / 20260405-202525+为什么AI工作流内容比单条提示词更容易被收藏：用户真正想带走的是一套可直接复用的路径 / material files`

## Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是：
  - Newrank-first 已检查但详情未验证；
  - required fallback 存在，但 `yhslgg-arch/url-reader` 当前不可用；
  - 所有例子都只能当作结构判断或标题/摘要级线索使用。
- 必须输出：
  - 1 个最终中文标题
  - 2 个备选标题
  - 1 篇中文正文
  - 1 个 tags/settings 区块
  - 1 个简短 `Viral Rewrite Notes`
  - 1 个简短 `viral-copy breakdown`
- 正文建议重点写三段：
  1. 为什么只教提示词越来越难形成收藏；
  2. 为什么“可直接照着跑的路径”更容易被用户带走；
  3. 怎样把趋势验证 / Topic 拆解 / Draft 改写 / Cover 包装 / Review 复审 串成一条内容生产线。
- Draft 必须是结构改写，不得复制爆款原句，不得补写未验证来源细节。
- Draft 的 archive 字段必须与本轮统一 package 完全一致。

## Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI工作流更容易被收藏`。
- 副标题建议突出：`用户想带走的是整套路径`。
- 视觉重点建议放在“从单条提示词 → 可直接复用流程”的价值跃迁。
- 页面逻辑要支持预览与手动发布，不导向自动发布。
- Cover 的 archive 字段必须与本轮统一 package 完全一致。

## Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否明确写出：Newrank detail 当前不可验证，`yhslgg-arch/url-reader` 按要求应使用但当前不可用。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否是结构改写而非句子复制。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260405-202525`。
- 必须核验最终产物是否只用于预览、复审与手动发布，不自动公开发布。
- 若上述任一项不成立，Review 应返回 `FAIL` 或 `CONDITIONAL`，并列出明确返工项。

## 推荐传播角度
- 当前更值得讲的不是“哪条 prompt 最神”，而是“为什么用户判断一条 AI 内容值不值得收藏，越来越看它能不能直接落成一套流程”。
- 推荐写法重点：
  - 提示词内容解决的是“会不会问”；
  - 工作流内容解决的是“能不能做完”；
  - 用户真正保存的，是一条今天就能复用的完整路径。
- 这个主题天然适合拆出 viral-copy breakdown，因为它同时具备：旧表达失效、新价值出现、案例拼图、可执行模板 四个传播支点。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- 本轮统一归档为：
  - `date` 层：`2026-04-06`
  - `timestamp+中文标题` 层：`20260405-202525+为什么AI工作流内容比单条提示词更容易被收藏：用户真正想带走的是一套可直接复用的路径`
  - `material files` 层：保留 Boss / Topic / Draft / Cover / Review 对应产物与来源状态说明。

## 当前判断
- 本轮核心不是扩更多题，而是把来源优先级、fallback 缺失、改写边界、统一归档包、以及非公开发布边界写清楚。
- 只要下游如实承认来源限制，并把内容重点收口到“可直接复用的路径”，本轮仍能形成一个可预览、可复审、可手动发布的 archive-ready 内容包。
- 本轮未执行任何公开发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`、角色 CLAUDE）
- 实际改动：新增 `Boss/BOSS-CYCLE-20260405-202525.md`
- 发布动作：未执行
