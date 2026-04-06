@ALL
归档路径建议：2026-04-06 / 20260406-133158+AI技能越多越要先接流程，真正能拉开差距的是稳定交付 / material files

本轮 Boss 任务包

1. 人群与目标
- 目标人群：正在把 AI 接进真实产出的个人创作者、内容运营、独立开发者、小团队负责人。
- 核心问题：同样都在接 AI skill、OpenClaw、workflow，为什么有人越做越稳，有人每轮都像重新开始。
- 本轮目标：输出一套可预览、可复审、可手动发布的小红书内容包，不公开自动发布。
- 归档要求：所有下游产物按 `2026-04-06 / 20260406-133158+AI技能越多越要先接流程，真正能拉开差距的是稳定交付 / material files` 对齐命名与整理。

2. 主题要求
- 首要来源固定为：`https://www.newrank.cn/search/trend/skill`。
- 本轮检索关键词边界：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill`。
- 当前来源核验结论：
  - 已按要求优先检查 Newrank trend 入口。
  - 本轮未取得 `search/trend/skill` 的可复核 detail；当前直接抓取该入口返回失败，不能把本轮写成已拿到详情页、榜单字段、热度值或截图证据。
  - 规则要求 detail 不可用时使用 `yhslgg-arch/url-reader` 作为 required fallback，但当前会话可用 skill 只有 `simplify` 与 `claude-api`，未提供该 skill，因此不能写成已执行 fallback。
- 因此本轮可安全使用的证据边界只有三类：
  - `https://www.newrank.cn/search/trend/skill` 已优先检查，但 exact detail 未取得。
  - 当前环境未提供 `yhslgg-arch/url-reader`，required fallback 无法执行。
  - Newrank 邻近公开页面与搜索结果里可见的标题级、摘要级线索。
- 本轮不可写成事实的内容：任何未直接核验的排名、热度、互动量、详情页正文、截图结论、爆文原句。
- 当前可用趋势拼图线索：
  - `百度电商Skill登陆OpenClaw，五大能力全开放`：可安全提炼为 `OpenClaw + Skill` 已进入具体商业场景。
  - `关于“OpenClaw（龙虾）”的全部内容` 聚合页：可安全提炼为 OpenClaw 相关讨论仍在持续沉淀。
  - `实测首款直连微信的OpenClaw`：可安全提炼为 OpenClaw 已向更具体使用场景扩展。
  - `网易云音乐全面接入OpenClaw`：可安全提炼为 OpenClaw 能力继续向内容与服务场景延伸。
  - `百度网盘GenFlow全新升级，融合OpenClaw，支持多人AI协作`：可安全提炼为讨论重点已经从单点调用转向多人协作与流程协同。
  - `你和最会玩“龙虾”的人，可能只差这8个硬核Skills`：可安全提炼为讨论重点已从“有没有装上”转向“能力怎么真正用起来”。
- 当前可继承的趋势判断：围绕 OpenClaw、skills、场景接入、多人协作的讨论正在汇合，内容重点正在从“又多了什么功能/Skill”转向“这些 Skill 能不能被接成稳定交付链路”。
- 主选题：`AI技能越多越要先接流程，真正能拉开差距的是稳定交付`
- 备选题方向：
  - `同样都在接 AI skill，为什么有人稳定交付，有人每次重来`
  - `不是 AI 不够强，是你还没把 Skill 接进流程里`
  - `OpenClaw skill 越来越多以后，普通人更该补的是 workflow 能力`
  - `别再只卷提示词了，真正稀缺的是能把 Skill 接成一条交付链的人`
- 必须产出 `Viral Copy Breakdown`，拆清楚 hook、结构、冲突点、承诺、证据类型与 CTA；只做结构重写，不复制原句。

3. 给 Topic / Draft 的明确交付口径
- Topic 必须优先写明 `https://www.newrank.cn/search/trend/skill` 已作为一手入口检查，但本轮未取得可复核 detail。
- Topic 必须如实写出：按规则应使用 `yhslgg-arch/url-reader` 作为 required fallback，但当前环境 skill 不可用，因此未执行。
- Topic 可使用的稳定邻近线索：
  - `百度电商Skill登陆OpenClaw，五大能力全开放`
  - `关于“OpenClaw（龙虾）”的全部内容`
  - `实测首款直连微信的OpenClaw`
  - `网易云音乐全面接入OpenClaw`
  - `百度网盘GenFlow全新升级，融合OpenClaw，支持多人AI协作`
  - `你和最会玩“龙虾”的人，可能只差这8个硬核Skills`
- Topic 需要如实写出关键词命中状态：
  - `openclaw`：有稳定 Newrank 邻近线索。
  - `openclaw skill`：有 `OpenClaw + Skill` 邻近文章线索，但仍非 `search/trend/skill` 直连详情。
  - `AI skill`：可由 skills 上线、场景接入、生态扩展等邻近信号支撑。
  - `workflow skill`：可由多人协作、流程协同、实际场景接入等邻近信号支撑。
  - `copilot skill`：本轮未获得明确直连结果，证据最弱，只能写成检索不足。
- Topic 必须产出可直接交给 Draft 的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- Draft 必写：中文标题、中文正文、标签、单独的 `Viral Copy Breakdown` 小节。
- Draft 必须重写爆款结构，不得照搬新闻标题、摘要、导语或 Topic 原句。
- 标题优先方向：
  - `AI技能越多越要先接流程，真正能拉开差距的是稳定交付`
  - `同样都在接 AI skill，为什么有人稳定交付，有人每次重来`
  - `不是 AI 不够强，是你还没把 Skill 接进流程里`
- 正文建议框架：
  1) 先做认知反转：不是 AI 不行，而是流程没接好；
  2) 再做痛点代入：为什么同样接了 AI skill，结果还是忽高忽低；
  3) 中段拆 4 个断点：输入不统一、角色没拆分、结果没人复核、材料没有归档；
  4) 给一套轻量解法：固定输入模板 + Skill 分工 + 节点复核 + archive 命名规则；
  5) 结尾做收藏/评论型 CTA。
- 正文语气：优先使用“踩坑后复盘”口吻，不写成工具测评，也不写成空泛方法论。
- 证据使用方式：
  - 可以写：Newrank 已优先检查；本轮未成功取得 `search/trend/skill` 可复核 detail；required fallback `yhslgg-arch/url-reader` 当前环境不可用；趋势判断建立在 Newrank 邻近公开标题级/摘要级线索上。
  - 不可以写：本轮拿到了 Newrank 详情页、榜单明细、热度值、排名或截图证明。

4. 给 Cover 的明确方向
- 封面标题方向：强认知反差，不做工具测评风。
- 可用封面文案方向：
  - `不是 AI 不够强，是你的 workflow 太散`
  - `同样是 AI skill，为什么别人越用越顺`
  - `别急着加工具，先把流程接起来`
- 视觉重点：流程断点、角色协作链路、稳定交付、可复用。
- 避免元素：榜单截图、虚构热度、夸张收益承诺、公开发布导向。

5. 给 Review 的复审口径
- 检查是否明确写出来源边界：Newrank 优先；`search/trend/skill` 本轮未取得可复核 detail；required fallback `yhslgg-arch/url-reader` 当前环境不可调用；因此没有新增详情页证据。
- 检查是否出现未验证的数据、排名、热度、爆文链接、截图式结论。
- 检查标题与正文是否只是借鉴传播结构，而非复制句子。
- 检查正文是否真正覆盖“谁负责、怎么接、如何复用、如何校验、如何归档”。
- 检查 `Viral Copy Breakdown` 是否写清 hook、结构、冲突点、承诺、证据类型、CTA。
- 检查输出是否支持归档：可直接落到 `date / timestamp+Chinese title / material files`。

6. Viral Copy Breakdown 要求
- Hook：先打破“AI 不够强/提示词不够长”的旧认知，再引出“问题其实出在流程没接好”。
- Structure：`旧认知失效 -> 来源边界说明 -> 趋势拼图 -> 真实断点 -> 轻量解法 -> CTA`。
- Conflict：表层是 Skill 越来越多，深层是结果仍然不稳。
- Promise：不是承诺爆，而是让读者更快判断自己卡在输入、分工、复核还是归档。
- Proof：证据只允许落到 Newrank 公开标题级/摘要级线索与“detail 未取得 / fallback 不可执行”的事实。
- CTA：以收藏、评论、复盘为主，不导向公开发布或外链跳转。

7. 风险边界
- 不碰 `master/main`。
- 不动 `node5`。
- 不做公开发布。
- 不编造趋势证据。
- 不把 fallback 当成已经成功执行。
- 不把未实际获取的页面内容包装成已完成抓取。

8. 交付说明
- 本轮 Boss 只写一个 boss task file。
- 下游角色以本文件与 `.role-sessions/Topic/TOPIC.md` 为准继续产出。
- `SAF-TaskAssignAndProgress.md` 本轮仓库内未检出，不额外引用不存在文件。
- 本文件已满足 archive-ready 交付要求，可直接作为本轮 Boss 唯一任务包归档。

9. Source Status Note
- 本轮尝试通过工具访问 `https://www.newrank.cn/search/trend/skill` 时未拿到可复核 detail。
- 当前工具留痕里，对该 URL 的直接抓取返回失败信息，不能据此扩写任何详情页事实。
- required fallback `yhslgg-arch/url-reader` 在当前环境未提供，因此只能如实记录未执行。
