@ALL
归档路径建议：2026-04-05 / 20260405-031655+AI技能开始卷落地了真正拉开差距的是谁能把Skill接进工作流 / material files

本轮 Boss 任务包

1. 人群与目标
- 目标人群：想把 AI 真正接进稳定产出的个人创作者、内容运营、独立开发者，以及正在尝试 agent / copilot / OpenClaw / skill 工作流的人。
- 核心问题：同样都在接 AI skill、copilot、workflow，为什么有人越用越顺，有人还是每次重来。
- 本轮目标：输出一套可预览、可复审、可手动发布的小红书内容包，不做公开自动发布。
- 归档要求：所有下游产物按 `2026-04-05 / 20260405-031655+AI技能开始卷落地了真正拉开差距的是谁能把Skill接进工作流 / material files` 对齐命名与整理。

2. 主题要求
- 主题优先级：先把新榜趋势入口 `https://www.newrank.cn/search/trend/skill` 写进来源状态，再决定本轮主选题。
- 本轮检索关键词边界：openclaw、openclaw skill、AI skill、workflow skill、copilot skill。
- 本轮实际来源状态：
  - 已按要求优先检查 Newrank 趋势入口。
  - 当前环境中直接 WebFetch 该目标页时返回模型不支持错误，未成功拿到可核验详情页内容。
  - 按规则应执行 `yhslgg-arch/url-reader` 作为 fallback，但当前会话可用 skill 仅见 `simplify` 与 `claude-api`，该 skill 不可调用，因此不能把 fallback 写成已完成。
  - 在不能获取 `search/trend/skill` 详情的前提下，已补充检查 Newrank / voice.newrank.cn 的公开邻近结果，可作为“趋势线索”而不是“趋势详情页结论”。
- 当前可安全使用的 Newrank 邻近线索：
  1. `百度电商Skill登陆OpenClaw，五大能力全开放`（voice.newrank.cn，2026-02-13）
  2. `百度秒哒应用生成Skill上线，面向全球用户开放`（newrank.cn，2026-03-17）
  3. `腾讯ima宣布上线ima skills`（voice.newrank.cn，2026-03-17）
  4. `腾讯再推“养虾”新措施，上线“中国专供”SkillHub`（voice.newrank.cn，2026-03-11）
  5. `网易云音乐接入OpenClaw`（newrank.cn，2026-03-22）
  6. `Minimax推出MaxClaw`（voice.newrank.cn，2026-02-26）
- 当前趋势判断只能收口到：
  - `openclaw` / `openclaw skill`：有相对稳定的 Newrank 邻近公开线索。
  - `AI skill`：可由多条 Skill 上线与接入类公开文章支持“技能化调用正在被持续内容化”。
  - `workflow skill`：可由 MaxClaw 中的 SOP planning、tool orchestration、capability configuration 等描述支持“工作流化执行能力正在被强化”为邻近趋势。
  - `copilot skill`：本轮仍无足够直连详情，不能伪造命中结果。
- 限制说明：本轮不得写入任何未验证的榜单细节、热度值、排名、爆文链接或 `search/trend/skill` 详情页正文细项。
- 主选题建议统一为：AI 技能开始卷落地了，真正拉开差距的，是谁能把 Skill 接进工作流。
- 主题表达重点：不是再讨论哪个模型更强，而是讨论谁能把技能、角色、流程、复核接成一条稳定交付链路。

3. 给 Topic / Draft 的明确交付口径
- Topic 必须先写明来源边界：Newrank 趋势入口已优先检查，但详情页未成功取得；指定 fallback `yhslgg-arch/url-reader` 当前环境不可调用；下文只能引用 Newrank 邻近公开线索。
- Topic 必须继续沿用并补强 `Viral Copy Breakdown`，明确拆出 hook、结构、冲突点、承诺、证据类型、CTA。
- Topic 必须写清 `Rewrite Direction`，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- Draft 必写中文标题、2 个备选标题、中文正文、标签。
- Draft 必写一个单独小节：`Viral Copy Breakdown` 或等价命名。
- Draft 必须重写爆款结构，不得照搬原句，不得把邻近线索写成榜单详情。
- 标题优先方向：
  - AI 技能开始卷落地了，真正拉开差距的是工作流
  - 同样接 Skill，为什么有人稳定交付，有人还在反复重来
  - 不是 AI 不够强，是你还没把 Skill 接进流程里
- 正文建议框架：
  1) 先做认知反转：不是 AI 不行，而是 Skill 只被当成单点工具；
  2) 再给痛点代入：同样接了 AI skill / copilot / OpenClaw，结果为什么还是忽高忽低；
  3) 中段拆 3 个流程断点：输入不稳定、角色不清、结果无人复核；
  4) 给一套轻量解法：固定输入模板 + Skill 分工 + 节点复核；
  5) 结尾做收藏/评论型 CTA。
- 正文语气：优先使用“踩坑后复盘”口吻，不写成纯工具测评，也不写成空泛方法论。
- 表达边界：只能引用本文件中已写明的可验证来源状态与邻近趋势线索，不得补写不可见细节。

4. Viral-copy 拆解重点
- Hook：用“误以为是模型问题，后来发现是流程问题”的认知反转切口。
- Structure：错误认知 → 真实问题 → 3 个断点 → 轻量方案 → CTA。
- Conflict：表层冲突是“继续换工具”，深层冲突是“没有把 Skill 接成可复用工作流”。
- Promise：承诺不要写成夸张增长，而要写成“让输出更稳定、返工更少、协作更顺”。
- Proof：优先使用“前后对比”“流程变化”“角色清晰后返工减少”这类证据类型，不使用虚构热度数据。
- CTA：适合引导收藏或评论，例如“你现在最卡的是提示词、流程，还是复核？”
- 禁止：复制别人的标题句、开头句、三段式原文；伪造 Newrank 榜单与热度；把 skill 不可用的 fallback 写成已完成。

5. 给 Cover 的明确方向
- 封面标题方向：强调“AI 技能开始卷落地”，不做工具清单风。
- 可用封面文案方向：
  - AI 技能开始卷落地了
  - 真正拉开差距的是工作流
  - 别再只加工具，先把 Skill 接起来
- 视觉重点：流程断点、角色协作、稳定交付。
- 避免元素：榜单截图、虚构排名、夸张收益承诺、未验证来源背书。

6. 给 Review 的复审口径
- 检查是否明确写出来源边界：Newrank 入口优先、详情未取到、WebFetch 失败、`yhslgg-arch/url-reader` 当前环境不可调用。
- 检查是否只把公开 Newrank / voice.newrank.cn 文章当作邻近趋势线索，而没有冒充为 `search/trend/skill` 详情页事实。
- 检查是否出现未验证的数据、排名、热度、爆文链接。
- 检查标题与正文是否只是借鉴结构，而非复制句子。
- 检查正文是否真正覆盖“谁负责、怎么接、如何复用、如何复核”。
- 检查 `Viral Copy Breakdown` 是否写清 hook、结构、冲突点、承诺、证据类型、CTA。
- 检查归档信息是否统一到 `2026-04-05 / 20260405-031655+AI技能开始卷落地了真正拉开差距的是谁能把Skill接进工作流 / material files`。
- 检查最终产物是否仅用于预览、复审与手动发布，不做自动公开发布。

7. 风险边界
- 不碰 master/main。
- 不动 node5。
- 不做公开发布。
- 不编造趋势证据。
- 不把 fallback 当成已经成功执行。
- 不把邻近公开文章包装成 `search/trend/skill` 详情页原始内容。

8. 交付说明
- 本轮 Boss 只写一个 boss task file。
- 下游角色以本文件与 `.role-sessions/Topic/TOPIC.md` 为准继续产出，但若两者冲突，以本轮时间戳与本文件来源边界为准统一收口。
- `SAF-TaskAssignAndProgress.md` 本轮未在仓库中检出，不额外引用不存在文件。
- 本文件已满足 archive-ready 交付要求，可直接作为本轮 Boss 唯一任务包归档。

9. 来源留痕
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 本轮可引用的 Newrank 邻近公开线索：
  - `https://voice.newrank.cn/study/detail/35CE5681E18CD946?utm_source=openai`
  - `https://newrank.cn/article/detail/34070?utm_source=openai`
  - `https://voice.newrank.cn/study/detail/D476CD4CE7677E9E?utm_source=openai`
  - `https://voice.newrank.cn/study/detail/7FFEEE81E4771445?utm_source=openai`
  - `https://newrank.cn/article/detail/34103?utm_source=openai`
  - `https://voice.newrank.cn/study/detail/67DCBB1F53F5FC6D?utm_source=openai`
- 上述链接当前仅可作为标题/摘要级邻近趋势线索使用，不能扩写成未验证正文事实。
