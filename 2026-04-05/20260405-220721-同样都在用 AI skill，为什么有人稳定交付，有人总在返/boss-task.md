# Boss Cycle 20260405-220721

## 当前重点
- 当前继续按 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进统一归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮已核验事项
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，确认本轮仍需优先使用 `https://www.newrank.cn/search/trend/skill` 作为一手趋势入口。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已尝试查找 `SAF-TaskAssignAndProgress.md`；当前仓库未检出该文件，因此本轮如实记录缺失状态，不虚构其内容。
4. 已复核历史 Boss 留痕，沿用其中已确认的来源边界、archive package 约束、viral-copy breakdown 要求与非公开发布边界。
5. 已再次确认当前会话可用 skill 只有 `simplify` 与 `claude-api`；任务要求中的 `yhslgg-arch/url-reader` 当前不可用，因此 fallback 要求存在，但本会话无法执行，不能伪造抓取结果或 extraction path。
6. 已尝试检查 `https://www.newrank.cn/search/trend/skill`；当前抓取返回 `API Error 400`，错误指向所请求模型不受支持，因此本轮不能把在线抓取写成成功取数，只能沿用已留痕的 Newrank 邻近趋势线索，并明确记录当前 detail 不可复核。
7. 已确认本轮主线收口为：`AI技能开始拼整条交付链，不再拼零散提示词`。
8. 已确认本轮归档布局必须支持：`2026-04-06 / 20260405-220721+AI技能开始拼整条交付链，不再拼零散提示词 / material files`。
9. 已确认本轮只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮统一归档包
- date: `2026-04-06`
- timestamp: `20260405-220721`
- archive_title: `AI技能开始拼整条交付链，不再拼零散提示词`
- archive_package: `2026-04-06 / 20260405-220721+AI技能开始拼整条交付链，不再拼零散提示词 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## 人群与目标
- 目标人群：想把 AI 真正接进内容产出的创作者、运营、独立开发者、小团队负责人。
- 核心问题：为什么同样都在加 AI skill、工作流、Agent 协作，有人越做越稳，有人每轮都像从头来过。
- 本轮目标：输出一套可预览、可复审、可手动发布的小红书内容包，不公开自动发布。
- 归档要求：所有下游产物按 `2026-04-06 / 20260405-220721+AI技能开始拼整条交付链，不再拼零散提示词 / material files` 对齐命名与整理。

## Topic 要求
- 首要来源固定为：`https://www.newrank.cn/search/trend/skill`。
- 本轮检索关键词边界：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill`。
- 当前来源核验结论：
  - 已按要求优先检查 Newrank trend 入口。
  - 本轮未取得可复核的 `search/trend/skill` detail。
  - 当前环境下对该入口的进一步抓取未成功：抓取工具返回 `API Error 400`，因此不能把本轮写成已成功拿到详情页内容。
  - 规则要求 detail 不可用时使用 `yhslgg-arch/url-reader` 作为 required fallback，但当前会话可用 skill 只有 `simplify` 与 `claude-api`，未提供该 skill，因此不能写成已执行 fallback。
- 因此本轮可安全使用的证据边界只有两类：
  - Newrank 优先入口已检查，但 detail 未取得这一事实。
  - 历史 Boss 留痕中已整理的 Newrank 邻近公开标题、摘要级线索与稳定趋势判断。
- 本轮不可写成事实的内容：任何未直接核验的排名、热度、互动量、详情页正文、截图结论、爆文原句。
- 当前可延续的趋势判断：围绕 OpenClaw、AI skill、workflow、多人协作的公开讨论，越来越指向“会不会用工具”之外的下一层能力——能不能把多个能力接成稳定交付链路。
- 主选题：`AI技能开始拼整条交付链，不再拼零散提示词`
- 备选题方向：
  - `同样在用 AI skill，为什么有人稳定交付，有人总在返工`
  - `不是工具不够多，而是你还没把流程接起来`
  - `OpenClaw 和 workflow 越来越热，真正稀缺的是闭环交付能力`
  - `AI 内容差距，不再只是提示词差距，而是流程完成度差距`
- Topic 必须产出可直接交给 Draft 的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含单独的 `Viral Copy Breakdown` 与 `Rewrite Direction` 段落。
- archive 字段必须统一到本轮：
  - `date: 2026-04-06`
  - `timestamp: 20260405-220721`
  - `archive_title: AI技能开始拼整条交付链，不再拼零散提示词`
  - `archive_package: 2026-04-06 / 20260405-220721+AI技能开始拼整条交付链，不再拼零散提示词 / material files`

## 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求是优先使用该入口，但本轮未拿到可验证的深层详情；现阶段只能把它写成优先入口与检查对象，不能扩写成已核实正文事实。
   - 本轮抓取返回 `API Error 400`，且错误信息指向模型不受支持，因此不能把在线抓取写成成功取数。
2. **`openclaw` / `openclaw skill` 邻近趋势线索**
   - 当前仍可沿用以下稳定邻近信号，但必须写清：这些线索属于 Newrank 域名下可见公开文章或摘要级留痕，不是 `search/trend/skill` 深层详情页本身。
   - 可继续引用的标题级线索包括：
     - `百度电商Skill登陆OpenClaw，五大能力全开放`
     - `Kimi推出OpenClaw云托管服务，跻身总榜前十；字节Seedance 2.0助力即梦排名上升 | AI产品月榜`
     - `百度智能云推出移动端OpenClaw部署方案`
     - `百度App接入OpenClaw 2周，超2成用户调用于投资理财分析`
   - 这些线索可支撑的方向是：OpenClaw 仍在“技能化调用”“可落地方案”“可复用能力”语境中出现，适合支撑“AI 正在从单次回答升级为可组织的技能工作流”这一判断。
3. **`AI skill` / `workflow skill` 邻近趋势线索**
   - 当前可继续采用：
     - `Krea AI推出节点式工作流工具Nodes，总榜排名上升34位；通义千问总榜排名攀升68位 | AI产品周榜`
     - `国产匿名模型Pony Alpha突袭海外OpenRouter，展示惊人编程能力` 中的“智能体工作流”邻近表述
     - `OpenAI推出面向科学家的免费AI原生工作台 Prism`
     - `2025抖音科技内容生态报告：2025年AI兴趣用户增长翻倍`
   - 本轮没有拿到 `workflow skill` 与 `AI skill` 在 `search/trend/skill` 下的直连详情，因此 Topic 必须明确这是邻近趋势，不是精确详情页结论。
4. **`copilot skill` 邻近趋势线索**
   - 当前仍只拿到站内导航 / 历史留痕级别的弱信号，没有明确 `copilot skill` 直连结果。
   - 可继续沿用历史邻近线索中的 `微软宣布加强Copilot Think Deeper深度思考功能`，支撑“用户关注点正在从快答转向更完整推理路径”的判断。
   - 因此 `copilot skill` 本轮只能写成“检索不足、暂无直连详情”，不能伪造成已抓到趋势正文。
5. **关键词命中状态说明**
   - `openclaw`：本轮有稳定 Newrank 邻近线索。
   - `openclaw skill`：本轮有 `OpenClaw + Skill` 邻近文章线索，但仍非 `search/trend/skill` 直连详情。
   - `AI skill`：本轮没有 `search/trend/skill` 直连详情，但可沿用 AI 产品榜、AI 原生工作台、AI 兴趣增长等邻近信号。
   - `workflow skill`：没有 `search/trend/skill` 直连详情，但有节点式工作流、智能体工作流、完整执行链路等邻近信号。
   - `copilot skill`：本轮未获得明确直连结果，仅有导航入口与历史邻近线索，证据最弱。
6. **来源限制说明**
   - 当前能确认的主要是 Newrank 主站及其相关文章的标题 / 摘要级线索，不是 `https://www.newrank.cn/search/trend/skill` 深层详情页本身。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增未经验证的在线细节，只能基于已留痕标题 / 摘要级线索与当前稳定判断继续收口。

## 给 Draft 的明确交付口径
- Draft 必写：1 个最终中文标题、2-3 个备选标题、1 篇中文正文、1 组 tags/settings、单独的 `Viral Copy Breakdown` 小节。
- Draft 必须继承真实来源状态：Newrank-first 已检查但 detail 未取得；required fallback 存在但当前 skill 不可用；所有趋势例子都只能作为标题/摘要级线索使用。
- Draft 必须重写爆款结构，不得照搬新闻标题、摘要、导语或 Topic 原句。
- 标题优先方向：
  - `AI技能开始拼整条交付链，不再拼零散提示词`
  - `同样在用 AI skill，为什么有人稳定交付，有人总在返工`
  - `不是工具不够多，而是你还没把流程接起来`
- 正文建议框架：
  1. 先做认知反转：问题不只是提示词，而是整条链路没接住；
  2. 再做痛点代入：为什么同样接了 AI skill，结果还是忽高忽低；
  3. 中段拆 4 个断点：输入不统一、角色没拆分、结果没人复核、材料没有归档；
  4. 给一套轻量解法：固定输入模板 + Skill 分工 + 节点复核 + archive 命名规则；
  5. 结尾做收藏/评论型 CTA。
- 正文语气：优先使用“踩坑后复盘”口吻，不写成工具测评，也不写成空泛方法论。
- Draft 必须附带简短 `Viral Rewrite Notes` 或等价段落，明确说明这是对爆款结构的改写，不是句子复制。
- archive 字段必须与本轮统一 package 完全一致。

## 给 Cover 的明确方向
- 封面标题方向：强认知反差，不做工具测评风。
- 可用封面文案方向：
  - `AI拼到最后，拼的是交付链`
  - `别再只拼提示词了`
  - `工具越多，越要把流程接起来`
- 视觉重点：流程断点、角色协作链路、稳定交付、可复用。
- 避免元素：榜单截图、虚构热度、夸张收益承诺、公开发布导向。
- 必须至少提供 3 个封面候选。
- archive 字段必须与本轮统一 package 完全一致。

## 给 Review 的复审口径
- 检查是否明确写出来源边界：Newrank 优先；`search/trend/skill` 本轮未取得可复核 detail；required fallback `yhslgg-arch/url-reader` 当前环境不可调用；因此没有新增详情页证据。
- 检查是否明确区分：`openclaw` 与 `openclaw skill` 有稳定邻近线索；`AI skill`、`workflow skill` 主要靠邻近趋势证据支撑；`copilot skill` 本轮证据最弱。
- 检查是否出现未验证的数据、排名、热度、爆文链接、截图式结论。
- 检查标题与正文是否只是借鉴传播结构，而非复制句子。
- 检查正文是否真正覆盖“谁负责、怎么接、如何复用、如何校验、如何归档”。
- 检查 `Viral Copy Breakdown` 是否写清 hook、结构、冲突点、承诺、证据类型、CTA。
- 检查 Topic / Draft / Cover / Review 的 archive 字段是否统一到 `20260405-220721`。
- 检查输出是否只用于预览、复审与手动发布，不自动公开发布。
- 若上述任一项不成立，Review 应返回 `FAIL` 或 `CONDITIONAL`，并列出明确返工项。

## Viral Copy Breakdown
### 1. Hook
- 开头必须先打破默认认知：不是 AI skill 不够多，而是流程没有接成可复用闭环。
- 第一屏重点不讲功能清单，而讲“为什么同样在用 AI，有人结果稳定，有人每次重来”。

### 2. Structure
- 推荐顺序：旧认知失效 -> 来源边界说明 -> 趋势线索拼图 -> 4 个真实断点 -> 轻量解法 -> 收藏/评论 CTA。
- 保留趋势感，但不能写成榜单播报或工具盘点。

### 3. Conflict
- 表层冲突：AI skill、OpenClaw、多人协作能力越来越多。
- 深层冲突：工具更多了，交付却未必更稳，问题在于输入、分工、复核、归档没有接起来。

### 4. Promise
- 承诺不是“稳爆”或“闭眼抄”，而是让读者更快定位自己卡在流程哪一段，并知道下一步先补什么。

### 5. Proof
- 证据只能落在已核验边界：Newrank 已优先检查；当前未取得可复核 detail；required fallback 当前不可执行；趋势判断仅建立在已留痕的 Newrank 邻近公开标题级线索上。
- 不得补写未核验的热度、排名、详情页正文、截图结论。

### 6. CTA
- CTA 以收藏、评论、复盘为主。
- 可用方向：`你现在最卡的是输入、分工、复核，还是归档？`

## Rewrite Direction
- 保留的模式：认知反转开头、问题先行、流程拆解、低承诺高可执行感、收藏型 CTA。
- 必须改写的部分：标题措辞、举例顺序、过渡句、观点表达、结尾召唤语。
- 绝不能复制的部分：任何 Newrank 文章标题原句、摘要原句、历史爆款开头原句、榜单式导语、截图口播句式。
- 改写原则：只借结构，不借句子；只借冲突框架，不借新闻表述；只保留可验证证据边界，不补虚构细节。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、OpenClaw 相关大众化关注、Copilot/Agent 协作技能、节点式工作流、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在提示词层，而真正开始拉开差距的是能不能把一整条流程稳定跑完并交付出来”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-04-06`。
- `timestamp+中文标题` 层：`20260405-220721+AI技能开始拼整条交付链，不再拼零散提示词`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260405-220721.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

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
- 实际改动：新增 `Boss/BOSS-CYCLE-20260405-220721.md`
- 发布动作：未执行
