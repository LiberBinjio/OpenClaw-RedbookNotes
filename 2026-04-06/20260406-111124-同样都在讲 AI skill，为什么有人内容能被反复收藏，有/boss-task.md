@ALL
归档路径建议：2026-04-06 / 20260406-103429+别再把AI技能写成新功能清单了，真正能带走的是可交接的workflow / material files

# Boss Cycle 20260406-103429

## 1. 本轮已确认前提
- 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`。
- 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，满足继续工作的前提。
- 已检索 `SAF-TaskAssignAndProgress.md`，当前仓库内未检出该文件；本轮如实记录缺失状态，不伪造引用。
- 本轮 Boss 只写这一个 boss task file：`Boss/BOSS-CYCLE-20260406-103429.md`。
- 本轮交付边界仍为：可预览、可复审、可手动发布；不做自动公开发布。

## 2. 统一归档包
- `date`：`2026-04-06`
- `timestamp`：`20260406-103429`
- `archive_title`：`别再把AI技能写成新功能清单了，真正能带走的是可交接的workflow`
- `archive_package`：`2026-04-06 / 20260406-103429+别再把AI技能写成新功能清单了，真正能带走的是可交接的workflow / material files`
- `publish_boundary`：`仅用于预览、复审与手动发布，不自动公开发布`

## 3. 人群、问题、目标
- 目标人群：正在用 AI 做内容、运营、交付或协作，但还停留在“工具清单展示”的创作者、独立开发者、小团队负责人。
- 核心问题：很多 AI 内容还在反复列“又新增了什么 skill、又接入了什么能力”，但用户真正愿意收藏的不是新功能名录，而是这套能力如何被接进可交接、可复用、可复审的 workflow。
- 本轮目标：围绕一个中文主选题收口，为 Topic / Draft / Cover / Review 提供统一口径，让下游能产出一个支持归档、可预览、可复审、可手动发布的内容包。

## 4. 来源策略与限制
### 4.1 Newrank-first
- Topic 必须把 `https://www.newrank.cn/search/trend/skill` 作为一手优先入口写入来源说明。
- 本轮已优先尝试检查该入口，并围绕以下关键词组织选题判断：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill`。
- 当前会话里，对 Newrank 页面的直接抓取未成功取得可复核 detail：`WebFetch` 返回工具侧 `API Error 400`，提示请求模型不受支持。
- 因此本轮不能声称已成功获得 Newrank 详情页正文、榜单明细、热度值、排名、互动数据、截图结论或页面摘要。

### 4.2 Required fallback 状态
- 当前任务明确要求：若 Newrank detail 不可用，应使用 `yhslgg-arch/url-reader` 作为 required fallback。
- 但本轮会话可用 skill 只有 `simplify` 与 `claude-api`，未提供 `yhslgg-arch/url-reader`。
- 因此本轮只能如实记录：fallback 要求存在，但当前环境不可执行；禁止伪造 fallback 输出、摘要或页面细节。

### 4.3 当前可安全使用的证据边界
- 只能使用以下两类内容：
  1. `Newrank 已优先检查，但 exact detail 未成功取得` 这一事实；
  2. 既有留痕中已确认过的 Newrank 邻近公开标题级、摘要级趋势线索。
- 不可写成事实的内容包括：未直接核验的热度值、排名、互动量、详情页正文、截图证明、爆文原句。

## 5. 本轮可沿用的趋势线索
### 5.1 关键词优先级
1. `openclaw`
2. `openclaw skill`
3. `AI skill`
4. `workflow skill`
5. `copilot skill`

### 5.2 关键词命中状态
- `openclaw`：有稳定 Newrank 邻近线索，可作为生态公开讨论背景。
- `openclaw skill`：有 `OpenClaw + Skill` 邻近文章线索，但仍非 `search/trend/skill` 直连详情。
- `AI skill`：没有本轮直连详情，但可由技能生态、平台化接入、内容生产场景化等邻近信号支撑。
- `workflow skill`：没有本轮直连详情，但“节点式组织”“完整执行链路”“多人协作”“复审归档”等邻近信号仍可支持主题判断。
- `copilot skill`：本轮未拿到明确直连结果，证据最弱，只能写成检索不足。

### 5.3 可继续承接的邻近趋势表达
- 围绕 OpenClaw、Skill、技能平台分发、多人协作、工作流化调用的公开讨论正在汇合。
- 传播重点正在从“这个工具新增了什么能力”转向“这些能力能不能接住一整段工作”。
- 对内容创作者而言，单纯堆 AI skill 名单的带走价值在下降；能直接交接、复用、归档的一条 workflow 更容易形成收藏与二次使用。

## 6. 主选题与备选题
### 主选题
- `别再把AI技能写成新功能清单了，真正能带走的是可交接的workflow`

### 备选题
1. `同样都在讲 AI skill，为什么有人被收藏，有人只留下功能目录`
2. `不是 AI 技能不够多，而是你还没把它们接成一条可交接流程`
3. `OpenClaw 相关内容越来越多，真正稀缺的是能稳定交付的 workflow`
4. `AI内容差距，不再只是提示词差距，而是流程闭环差距`
5. `Skill 越来越多以后，真正值钱的是谁能把结果稳定交出去`

## 7. Topic 交付要求
- Topic 必须优先写明：`https://www.newrank.cn/search/trend/skill` 已作为一手入口检查，但本轮未取得可复核 detail。
- Topic 必须明确写出：required fallback `yhslgg-arch/url-reader` 按要求应执行，但当前环境无此 skill，因此无法执行，不能伪造结果。
- Topic 必须输出可直接交给 Draft 的中文 topic package，至少包含：
  - 主选题
  - 3-5 个备选题
  - 目标人群
  - 趋势线索
  - viral references
  - rewrite angle
  - hook breakdown
- Topic 必须单列 `Viral Copy Breakdown`，至少拆出：hook、结构、冲突点、承诺、证据、CTA。
- Topic 必须单列 `Rewrite Direction`，明确哪些模式保留、哪些表达必须重写、哪些句子绝不能复制。
- Topic 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新为本轮统一值。
- Topic 必须明确要求后续把 `@TOPIC.md` 正式落到统一 archive package 内，不能只停留在临时日志或会话文件里。

## 8. Viral Copy Breakdown
- **hook**：先打破“AI 内容只要多列几个新 skill / 多晒几个新功能就够了”的旧认知，再抛出真正更容易被收藏的是“能交接、能复用的一条 workflow”。
- **结构**：旧认知失效 → 来源边界说明 → 趋势拼图 → 为什么功能清单带不走 → 为什么 workflow 更容易被保存 → 轻量解法 → CTA。
- **冲突点**：表面上大家在比谁知道更多新能力、更多 skills，实际用户更在意的是有没有一条自己今天就能照着走、明天还能交给别人的路径。
- **承诺**：读者带走的不是一串工具名，而是一套可复用的内容交付思路：调研、提纲、起稿、复审、归档如何串起来。
- **证据**：只能使用本轮可核验的来源状态与既有留痕中的邻近趋势线索，不得编造 Newrank 详情或 fallback 结果。
- **CTA**：引导收藏、评论、复盘，不导向公开发布或站外跳转。

## 9. Rewrite Direction
- 保留的传播模式：强反差开场、用户痛点代入、流程拆解、可执行方法、结尾互动 CTA。
- 必须重写的部分：标题句式、段落衔接、案例表达、结尾号召。
- 绝不能复制的内容：任何外部原句、爆文句、新闻标题原句、未验证榜单表述、截图结论。
- 重写方向：
  - 把“新功能盘点”改写成“workflow 复盘”；
  - 把“AI 很强”改写成“这套流程能不能稳定接住结果”；
  - 把“抽象观点”改写成“别人能直接照着交接的路径说明”。

## 10. Draft 交付要求
- Draft 必须输出：
  - 1 个最终中文标题
  - 2 个备选标题
  - 1 篇中文正文
  - 1 个 tags/settings 区块
  - 1 个独立的 `viral-copy breakdown` 区块
- Draft 必须继承真实来源边界：Newrank-first、detail 未取得、required fallback 当前不可执行。
- Draft 必须明确这是“爆款结构改写”，不是句子复制。
- 正文建议重点写清三件事：
  1. 为什么只堆 AI skill 名单的内容越来越难形成收藏；
  2. 为什么可交接、可复用的 workflow 更容易被用户带走；
  3. 怎样把调研、提纲、起稿、复审、归档串成一条稳定内容链路。
- Draft 必须明确要求把 `@DRAFT.md` 正式落到统一 archive package 内，不能只停留在临时输出。

## 11. Cover 交付要求
- 封面方向必须与统一中文标题一致，并支持单独归档留存。
- 主标题建议：`别再把AI技能写成新功能清单了`
- 副标题建议：`真正能带走的是可交接的workflow`
- 可给 3 个 cover candidates，并明确主推版本。
- 视觉关键词：技能清单、流程链路、角色协作、复审节点、归档沉淀、可复用。
- 禁止元素：榜单截图、虚构热度、夸张收益承诺、自动发布暗示。
- Cover 必须明确要求把 `@COVER.md` 正式落到统一 archive package 内。

## 12. Review 复审口径
- 必须检查 Topic 是否优先使用了 Newrank 入口，或明确写出当前受限原因。
- 必须检查 Topic 是否如实写清：
  - `openclaw` 与 `openclaw skill` 目前只有稳定邻近线索；
  - `AI skill` 与 `workflow skill` 主要由邻近趋势判断支撑；
  - `copilot skill` 证据最弱。
- 必须检查 Topic 是否写清 required fallback `yhslgg-arch/url-reader` 当前环境不可执行；若写成“已抓到详情”，直接打回。
- 必须检查 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须检查 Draft 是否包含中文标题、正文、标签与独立 `viral-copy breakdown`。
- 必须检查 Draft 是否保持“结构改写而非句子复制”。
- 必须检查 `@TOPIC.md`、`@DRAFT.md`、`@COVER.md`、`@REVIEW.md` 是否都落到了统一 archive package 内，而不是只存在日志或临时目录。
- 必须检查 Topic / Draft / Cover / Review 的 `timestamp` 与 `archive_package` 是否统一到 `20260406-103429`。
- 必须检查最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 13. 风险边界
- 不碰 `master/main`。
- 不修改 `node5`。
- 不做公开发布。
- 不编造趋势证据。
- 不把 fallback 当成已经成功执行。
- 不把未实际获取的页面内容包装成已完成抓取。
- 不直接复制爆款原句、新闻原句或未验证外部表述。

## 14. 本轮交付说明
- 本轮 Boss 只写这一个 task file：`Boss/BOSS-CYCLE-20260406-103429.md`。
- 下游角色按本文件统一口径继续产出 Topic / Draft / Cover / Review。
- 最终内容包必须能按 `2026-04-06 / 20260406-103429+别再把AI技能写成新功能清单了，真正能带走的是可交接的workflow / material files` 组织。
- 本轮未执行任何公开发布动作。
