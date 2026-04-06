# Boss Cycle 20260406-022828

## 当前重点
- 本轮继续按 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- Boss 本轮只写一个任务文件，所有下游产物都必须能收进统一归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守边界：仅在 `RedbookClaw` 工作，不触碰 `master/main`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮已核验事项
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，允许继续工作。
3. 已查找 `SAF-TaskAssignAndProgress.md`；当前仓库未检出该文件，因此本轮如实记录缺失状态，不虚构其内容。
4. 已按要求优先检查 `https://www.newrank.cn/search/trend/skill`；当前直接抓取未成功，`WebFetch` 返回 `API Error 400`，因此未取得可复核的详情页内容。
5. 任务要求中的 `yhslgg-arch/url-reader` 为 required fallback，但当前会话可用 skill 只有 `simplify` 与 `claude-api`，因此本轮无法执行该 fallback，只能如实记录环境限制。
6. 已复核上一轮稳定留痕 `Boss/BOSS-CYCLE-20260406-012226.md`，沿用已确认的来源边界、archive-ready 约束、viral-copy breakdown 要求与非公开发布边界。
7. 本轮结合 Newrank 可见公开结果，主线收口为：`AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付`。
8. 本轮所有下游产物必须统一归档到：`2026-04-06 / 20260406-022828+AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付 / material files`。

## 本轮统一归档包
- date: `2026-04-06`
- timestamp: `20260406-022828`
- archive_title: `AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付`
- archive_package: `2026-04-06 / 20260406-022828+AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## 人群与目标
- 目标人群：正在把 AI 接进真实产出的个人创作者、内容运营、独立开发者、小团队负责人。
- 核心问题：同样都在看 AI skill、OpenClaw、workflow，为什么有人越做越稳，有人还是每轮都像重新开始。
- 本轮目标：输出一套可预览、可复审、可手动发布的小红书内容包，不做公开自动发布。

## Topic 要求
- 首要来源固定为：`https://www.newrank.cn/search/trend/skill`。
- 本轮检索关键词边界：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill`。
- 当前来源核验结论：
  - 已按要求优先检查 Newrank trend 入口。
  - 本轮未取得可复核的 `search/trend/skill` detail。
  - 当前环境下直接抓取未成功：`WebFetch` 返回 `API Error 400`。
  - required fallback `yhslgg-arch/url-reader` 当前会话不可用，因此不能写成已执行 fallback。
- 因此本轮可安全使用的证据边界只有两类：
  - Newrank 优先入口已检查，但 detail 未取得这一事实。
  - Newrank 公开文章页、公开专题页、公开搜索结果中的标题级、摘要级、搜索结果级线索。
- 本轮不可写成事实的内容：任何未直接核验的排名细节、热度数值、互动量、详情页正文、截图结论、爆文原句。
- 主选题：`AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付`
- 备选题方向：
  - `同样都在接 AI skill，为什么有人稳定交付，有人每次重来`
  - `不是 AI 工具不够多，是你还没把 Skill 接进流程里`
  - `OpenClaw 技能越多以后，普通人更该补的是 workflow 能力`
  - `别急着继续加功能，真正该补的是一条能反复复用的流程`
  - `AI内容开始分层，不是谁会写更多提示词，而是谁能稳定交付`
- Topic 必须产出可直接交给 Draft 的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含单独的 `Viral Copy Breakdown` 与 `Rewrite Direction` 段落。
- archive 字段必须统一到本轮：
  - `date: 2026-04-06`
  - `timestamp: 20260406-022828`
  - `archive_title: AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付`
  - `archive_package: 2026-04-06 / 20260406-022828+AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付 / material files`

## 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求必须优先使用该入口，但本轮未拿到可验证 detail；现阶段只能写成优先入口与检查对象，不能扩写成已核实正文事实。
   - 当前直接抓取返回 `API Error 400`，因此不能把在线抓取写成成功取数。
2. **`openclaw` / `openclaw skill` 邻近线索较强**
   - `百度电商Skill登陆OpenClaw，五大能力全开放`（Newrank，2026-02-13）可支持 `OpenClaw + Skill` 已进入更大众的内容传播语境。
   - `你和最会玩“龙虾”的人，可能只差这8个硬核Skills`（Newrank，2026-03-23）可支持“skills 正在从开发者语境走向更广泛使用语境”的表达。
   - `百度秒哒应用生成Skill上线，面向全球用户开放`（Newrank，2026-03-17）可支持“Skill 正在进一步产品化、接入化”的表达。
3. **`AI skill` / `workflow skill` 邻近线索中等**
   - 本轮未拿到 `search/trend/skill` 详情页直连证据。
   - 但公开结果已能支持一个稳定判断：AI 内容讨论正在从“又多了几个技能名词”，转向“这些 skill 到底怎样被接进真实流程”。
   - 因此 Topic 可以把趋势收口到：用户更在意可复用路径、分工链路、复核节点、归档结果，而不是孤立功能点。
4. **`copilot skill` 证据最弱**
   - 当前没有拿到清晰的 Newrank 直连文章结果。
   - 因此 `copilot skill` 本轮只能写成“检索不足、暂无可复核直连详情”，不能伪造成已验证趋势。
5. **关键词命中状态说明**
   - `openclaw`：有稳定 Newrank 邻近公开线索。
   - `openclaw skill`：有较明确的 Newrank 文章级线索，但仍非 `search/trend/skill` 详情页本身。
   - `AI skill`：有公开搜索结果级和文章级邻近信号，但缺少详情页直连核验。
   - `workflow skill`：当前主要依赖趋势判断与邻近信号支撑，不能写成 detail 已验证。
   - `copilot skill`：本轮检索不足，证据最弱。
6. **来源限制说明**
   - 当前能确认的主要是 Newrank 站内公开标题 / 摘要 / 搜索结果级线索，不是 `https://www.newrank.cn/search/trend/skill` 深层详情页本身。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增未经验证的在线细节，只能基于已核验线索继续收口。

## 给 Draft 的明确交付口径
- Draft 必写：1 个最终中文标题、2-3 个备选标题、1 篇中文正文、1 组 tags/settings、单独的 `viral-copy breakdown` 小节。
- Draft 必须继承真实来源状态：Newrank-first 已检查但 detail 未取得；required fallback 存在但当前 skill 不可用；所有趋势例子都只能作为标题/摘要级线索使用。
- Draft 必须重写爆款结构，不得照搬新闻标题、摘要、导语或 Topic 原句。
- 标题优先方向：
  - `AI技能开始从功能堆叠转向流程复用，真正拉开差距的是稳定交付`
  - `同样都在接 AI skill，为什么有人稳定交付，有人每次重来`
  - `不是 AI 工具不够多，是你还没把 Skill 接进流程里`
- 正文建议框架：
  1. 先做认知反转：不是 AI skill 变多就自然更强，而是流程接通后才会更稳；
  2. 再做痛点代入：为什么同样都在接 Skill，有人能复用，有人每次从头再来；
  3. 中段拆 4 个断点：输入不统一、角色没拆分、结果没人复核、材料没有归档；
  4. 给一套轻量解法：固定输入模板 + Skill 分工 + 节点复核 + archive 命名规则；
  5. 结尾做收藏/评论型 CTA。
- 正文语气：优先使用“踩坑后复盘”口吻，不写成工具测评，也不写成空泛方法论。
- Draft 必须附带简短 `Viral Rewrite Notes` 或等价段落，明确说明这是对爆款结构的改写，不是句子复制。

## 给 Cover 的明确方向
- 封面标题方向：强认知反差，不做工具测评风。
- 可用封面文案方向：
  - `AI技能开始拼的，不是数量，是流程`
  - `同样是 AI skill，为什么别人越用越稳`
  - `别急着加功能，先把流程接起来`
- 视觉重点：流程断点、角色协作链路、稳定交付、可复用。
- 避免元素：榜单截图、虚构热度、夸张收益承诺、公开发布导向。
- 必须至少提供 3 个封面候选。
- archive 字段必须与本轮统一 package 完全一致。

## 给 Review 的复审口径
- 检查是否明确写出来源边界：Newrank 优先；`search/trend/skill` 本轮未取得可复核 detail；required fallback `yhslgg-arch/url-reader` 当前环境不可调用；因此没有新增详情页证据。
- 检查是否明确区分：`openclaw` 与 `openclaw skill` 证据较强；`AI skill`、`workflow skill` 主要靠邻近趋势证据支撑；`copilot skill` 本轮证据最弱。
- 检查是否出现未验证的数据、排名细节、热度、爆文链接、截图式结论。
- 检查标题与正文是否只是借鉴传播结构，而非复制句子。
- 检查正文是否真正覆盖“谁负责、怎么接、如何复用、如何校验、如何归档”。
- 检查 `Viral Copy Breakdown` 是否写清 hook、结构、冲突点、承诺、证据类型、CTA。
- 检查 Topic / Draft / Cover / Review 的 archive 字段是否统一到 `20260406-022828`。
- 检查输出是否只用于预览、复审与手动发布，不自动公开发布。
- 若上述任一项不成立，Review 应返回 `FAIL` 或 `CONDITIONAL`，并列出明确返工项。

## Viral Copy Breakdown
### 1. Hook
- 开头必须先打破默认认知：不是 AI skill 越多就自然越强，而是流程有没有被接成可复用闭环。
- 第一屏重点不讲功能清单，而讲“为什么同样都在接 AI，有人结果稳定，有人每次重来”。

### 2. Structure
- 推荐顺序：旧认知失效 -> 来源边界说明 -> 趋势线索拼图 -> 4 个真实断点 -> 轻量解法 -> 收藏/评论 CTA。
- 保留趋势感，但不能写成榜单播报或工具盘点。

### 3. Conflict
- 表层冲突：AI skill、OpenClaw、平台化接入越来越多。
- 深层冲突：功能更多了，交付却未必更稳，问题在于输入、分工、复核、归档没有接起来。

### 4. Promise
- 承诺不是“稳爆”或“闭眼抄”，而是让读者更快定位自己卡在流程哪一段，并知道下一步先补什么。

### 5. Proof
- 证据只能落在已核验边界：Newrank 已优先检查；当前未取得可复核 detail；required fallback 当前不可执行；趋势判断仅建立在已核验的 Newrank 标题级、摘要级、搜索结果级线索上。
- 不得补写未核验的热度、详情页正文、截图结论。

### 6. CTA
- CTA 以收藏、评论、复盘为主。
- 可用方向：`你现在最卡的是输入、分工、复核，还是归档？`

## Rewrite Direction
- 保留的模式：认知反转开头、问题先行、流程拆解、低承诺高可执行感、收藏型 CTA。
- 必须改写的部分：标题措辞、举例顺序、过渡句、观点表达、结尾召唤语。
- 绝不能复制的部分：任何 Newrank 文章标题原句、摘要原句、历史爆款开头原句、榜单式导语、截图口播句式。
- 改写原则：只借结构，不借句子；只借冲突框架，不借新闻表述；只保留可验证证据边界，不补虚构细节。

## 来源线索
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 本轮直接抓取该入口时，`WebFetch` 返回 `API Error 400`，因此不能把在线抓取写成成功取数。
- 邻近公开线索：
  - `https://www.newrank.cn/article/detail/33856?utm_source=openai`
  - `https://www.newrank.cn/article/detail/34114?utm_source=openai`
  - `https://www.newrank.cn/article/detail/34070?l=sq_main-dc_sq&utm_source=openai`
- 上述线索当前仅可作为标题 / 摘要 / 搜索结果级证据使用，不能扩写成未验证正文事实。

## 风险边界
- 不碰 `master/main`。
- 不动 `node5`。
- 不做公开发布。
- 不编造趋势证据。
- 不把 fallback 当成已经成功执行。
- 不把未实际获取的页面内容包装成已完成抓取。

## 交付说明
- 本轮 Boss 只写一个 boss task file。
- 下游角色以本文件为准继续产出。
- `SAF-TaskAssignAndProgress.md` 本轮仓库内未检出，不额外引用不存在文件。
- 本文件已满足 archive-ready 交付要求，可直接作为本轮 Boss 唯一任务包归档。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260406-022828.md`
- 发布动作：未执行
