@ALL
归档路径建议：2026-04-05 / 20260405-123612+AI技能开始拼交付闭环了，真正拉开差距的是谁能把流程稳定跑完 / material files

本轮 Boss 任务包

1. 人群与目标
- 目标人群：想把 AI 真正接进稳定产出的个人创作者、内容运营、小团队负责人、独立开发者。
- 核心问题：同样都在接 AI skill / OpenClaw / workflow，为什么有人能稳定交付，有人每次都像重新开一轮。
- 本轮目标：产出一套可预览、可复审、可手动发布的小红书内容包，不做自动公开发布。
- 归档要求：所有下游产物统一对齐 `2026-04-05 / 20260405-123612+AI技能开始拼交付闭环了，真正拉开差距的是谁能把流程稳定跑完 / material files`。

2. 本轮已核验状态
- 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
- 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，允许继续工作。
- 已查找 `SAF-TaskAssignAndProgress.md`；当前仓库未检出该文件，本轮如实记录缺失状态，不虚构其内容。
- 已优先检查 `https://www.newrank.cn/search/trend/skill` 作为首要入口；当前未取得可复核的 trend detail。
- 本轮对 Newrank 入口的 `WebFetch` 返回 `API Error 400`，错误指向当前请求模型不受支持，因此不能把本轮检查写成成功取数。
- 规则要求在 Newrank detail 不可用时使用 `yhslgg-arch/url-reader` 作为 required fallback；但当前会话可用 skill 只有 `simplify` 与 `claude-api`，未提供该 skill，因此不能把 fallback 写成已执行成功。
- 当前可安全延续的证据边界，仅包括：Newrank 公开可见标题/摘要级线索，以及仓库既有留痕中已经整理过的同类公开线索。

3. 主题要求
- 主题优先级：先看 Newrank 趋势入口 `https://www.newrank.cn/search/trend/skill`。
- 检索关键词边界：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill`。
- 本轮主题必须优先收口到：AI 技能内容开始拼交付闭环了，真正拉开差距的是谁能把流程稳定跑完。
- 不把主题写成“哪个 Skill 最热”，而写成“Skill 越多之后，为什么更需要把输入、分工、复核、归档接成闭环”。
- 当前可安全引用的趋势线索，只能作为方向判断，不可扩写成未核验榜单 detail：
  - 《百度电商Skill登陆OpenClaw，五大能力全开放》
  - 《腾讯再推“养虾”新措施，上线“中国专供”SkillHub》
  - 《装上了，然后呢？我们盘点了“养龙虾”的11种经典玩法》
  - 《腾讯ima宣布上线 ima skills》
  - 《百度秒哒应用生成Skill上线，面向全球用户开放》
  - 《百度网盘GenFlow全新升级，融合OpenClaw，支持多人AI协作》
  - 《你和最会玩“龙虾”的人，可能只差这8个硬核Skills》
- 当前更稳妥的趋势判断：讨论重点正在从“会不会提问、会不会装工具”，转向“能不能把 Skill 接进一条稳定产出链”。

4. 给 Topic 的明确交付口径
- 必须明确写出来源边界：Newrank 优先；`search/trend/skill` 本轮未取得可复核 detail；required fallback `yhslgg-arch/url-reader` 当前环境不可用。
- 必须明确哪些关键词只有邻近趋势信号，哪些关键词证据较弱，不得把弱信号写成强结论。
- Topic 必须输出：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- Topic 必须包含单独小节：`Viral Copy Breakdown`。
- Topic 必须包含单独小节：`Rewrite Direction`。
- Topic 只能拆传播结构，不得复制标题原句、导语原句、摘要原句。
- Topic 的 archive 信息必须统一更新到：
  - `date: 2026-04-05`
  - `timestamp: 20260405-123612`
  - `archive_title: AI技能开始拼交付闭环了，真正拉开差距的是谁能把流程稳定跑完`
  - `archive_package: 2026-04-05 / 20260405-123612+AI技能开始拼交付闭环了，真正拉开差距的是谁能把流程稳定跑完 / material files`

5. 给 Draft 的明确交付口径
- Draft 必写中文标题、2 个备选标题、中文正文、标签/设置区块。
- Draft 必写一个单独小节：`Viral Copy Breakdown`。
- Draft 必须重写爆款结构，不得照搬新闻标题、摘要、导语或 Topic 原句。
- 标题优先方向：
  - AI技能开始拼交付闭环了，真正拉开差距的是谁能把流程稳定跑完
  - 同样都在接 AI skill，为什么有人稳定交付，有人每次重来
  - 不是 AI 不够强，是你还没把 Skill 接进流程里
- 正文建议框架：
  1) 先做认知反转：不是 AI 不行，而是 workflow 没接好；
  2) 再给痛点代入：为什么同样的 AI skill，结果总是忽高忽低；
  3) 中段拆 4 个流程断点：输入不稳定、角色不清、结果无人复核、材料没有归档；
  4) 给一套轻量解法：固定输入模板 + Skill 分工 + 节点复核 + archive 命名规则；
  5) 结尾做收藏/评论型 CTA。
- 正文语气：优先使用“踩坑后复盘”口吻，不写成工具测评，也不写成空泛方法论。
- 正文证据边界：只能引用 Topic 已确认的公开线索和来源状态，不得补写未核验热度值、排名、互动量、截图结论或详情页正文。

6. 给 Cover 的明确方向
- 封面标题方向：强认知反差，不做工具测评风。
- 可用封面文案方向：
  - 不是 AI 不够强，是你的 workflow 太散
  - 同样是 AI skill，为什么别人越用越顺
  - 别急着加工具，先把流程接起来
- 视觉重点：流程断点、协作链路、稳定交付。
- 避免元素：榜单截图、虚构热度、夸张收益承诺。
- Cover 的归档信息也必须统一到 `20260405-123612` 对应包。

7. 给 Review 的复审口径
- 检查是否明确写出来源边界：Newrank 优先、`search/trend/skill` 未核验、`yhslgg-arch/url-reader` 当前环境不可调用，因此没有新增可核验 detail 页证据。
- 检查是否出现未验证的数据、排名、热度、爆文链接或截图结论。
- 检查标题与正文是否只是借鉴结构，而非复制句子。
- 检查正文是否真正覆盖“谁负责、怎么接、如何复用、如何校验、如何归档”。
- 检查 `Viral Copy Breakdown` 是否写清 hook、结构、冲突点、承诺、证据类型、CTA。
- 检查 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260405-123612`。
- 检查最终产物仅用于预览、复审与手动发布，不自动公开发布。

8. Viral-copy 统一要求
- 只拆方法，不抄句子。
- 重点拆：hook pattern、structure pattern、conflict point、promise、proof、CTA。
- 必须明确写出：保留什么、改写什么、绝不能复制什么。
- 本轮推荐保留的传播主线：
  - 先打掉“差距来自提示词/模型”的旧认知；
  - 再提出“真正差距来自流程闭环”的新判断；
  - 中段用流程断点承接痛点；
  - 结尾给轻量可执行解法与互动 CTA。

9. 风险边界
- 不碰 `master/main`。
- 不动 `node5`。
- 不做公开发布。
- 不编造 Newrank detail。
- 不把 fallback 当成已经成功执行。
- 不把公开标题级线索包装成完整榜单或详情页事实。

10. 交付说明
- 本轮 Boss 只写一个 boss task file：`Boss/BOSS-CYCLE-20260405-123612.md`。
- 下游角色继续产出时，必须统一使用本文件给出的 archive package，不得沿用旧时间戳。
- `SAF-TaskAssignAndProgress.md` 本轮未在仓库中检出，不额外引用不存在文件。
- 本文件已满足 archive-ready 交付要求，可直接作为本轮 Boss 唯一任务包归档。
