# Boss Cycle 20260312-082404

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md`。
2. 已尝试读取 `.role-sessions/current_task.md`，当前路径不存在，已如实记录缺失状态。
3. 已尝试读取 `SAF-TaskAssignAndProgress.md`，当前仓库内不存在，已如实记录缺失状态。
4. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合要求，因此继续。
5. 已复核上一轮 Boss 文件 `Boss/BOSS-CYCLE-20260312-075409.md`、`Boss/BOSS-CYCLE-20260312-072600.md` 与 `Boss/BOSS-CYCLE-20260312-060333.md`，继续沿用“单主题收口 + archive package 统一 + 来源限制如实留痕”的推进方式。
6. 已再次确认当前任务要求：Topic 必须优先从 `https://www.newrank.cn/search/trend/skill` 获取趋势线索，并围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 组织方向。
7. 已再次确认：如果 Newrank detail 不可用，应使用 `yhslgg-arch/url-reader` 作为 fallback；但当前会话可用 skill 列表只有 `simplify` 与 `claude-api`，没有该 skill，因此只能如实记录 fallback 要求存在但当前环境不可调用，不得伪造抓取结果。
8. 本轮补充检索到的公开可见 Newrank 邻近线索仍主要停留在站点入口、榜单页与报告页层级，未拿到 `search/trend/skill` 的可验证详情页正文，因此不能把该入口写成已验证细节来源。
9. 结合前几轮已留痕内容与本轮检索结果，当前仍可稳定收口的趋势表达是：用户更愿意收藏“可直接复用的 AI 工作流 / 技能路径”，而非只给一句提示词的零散内容。
10. 已确认 Draft 必须改写爆款模式，不能复制原句；同时 Topic 与 Draft 都必须显式提供 `Viral Copy Breakdown` / `viral-copy breakdown`。
11. 已确认本轮继续只准备预览、复审与手动发布内容，不执行任何公开发布动作。
12. 已确认本轮输出必须支持 archive folder layout：`2026-03-12 / 20260312-082404+AI工作流内容为什么更容易被收藏和复用：因为用户真正想带走的不是一句提示词，而是一整套可直接照着走的路径 / material files`。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI工作流内容为什么更容易被收藏和复用：因为用户真正想带走的不是一句提示词，而是一整套可直接照着走的路径`。
- 统一归档日期：`2026-03-12`。
- 统一归档包：`2026-03-12 / 20260312-082404+AI工作流内容为什么更容易被收藏和复用：因为用户真正想带走的不是一句提示词，而是一整套可直接照着走的路径 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只找到了邻近趋势信号。
- Topic 必须优先产出一个可直接支持“AI 工作流内容为什么更容易被收藏和复用，因为用户真正想带走的不是一句提示词，而是一整套可直接照着走的路径”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失/受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须新增明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须新增明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-12`、`20260312-082404` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 在趋势表达上，要优先收口到“用户更愿意保存能直接复用的工作流内容”，而不是泛泛讨论某个 AI 工具是否更强。

### 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求是优先使用该入口，但本轮未拿到可验证的深层详情；因此下游只能把它写成优先入口与检查对象，不能扩写成已核实正文事实。
2. **关键词命中状态**
   - `openclaw`、`openclaw skill`：本轮未新增稳定可验证的直接命中结果。
   - `AI skill`、`workflow skill`、`Copilot skill`：本轮只拿到 Newrank 站点入口、榜单页、报告页或历史已留痕文章标题级邻近线索，可作为组织方向，但不能当成 `search/trend/skill` 详情页已核实证据。
3. **工作流 / 路径型表达仍可作为主趋势方向**
   - 可继续沿用上一轮已留痕的公开可见结果：`Kimi推出OpenClaw云托管服务，跻身总榜前十；字节Seedance 2.0助力即梦排名上升 | AI产品月榜`、`1条视频涨粉40万，科普圈“掌管AI的神”首次公开幕后制作全流程 | AI新榜独家`、`字节Trae上线Skills功能，总榜排名上升30位；PixVerse R1模型发布，海外榜排名上升21位 | AI产品周榜`。
   - 可借用结论：AI 内容叙事正在从单点功能展示，转向“全流程公开”“Skills 化表达”“可复用路径”这类更适合被收藏和复用的内容结构。
4. **报告页邻近线索**
   - 本轮补充检索到 Newrank 报告页《矩阵纪元：企业新媒体生态位与实践图谱 2025–2030》，其公开检索摘要涉及工具协同、AI 工具与矩阵管理工具的协作表达。
   - 该结果只能作为“工具协同 / workflow 仍是平台叙事方向”的邻近线索，不能扩写为未验证的报告正文细节。
5. **来源限制说明**
   - 当前能确认的仍主要是 Newrank 搜索/站内结果层级的标题与摘要级线索，以及上一轮已留痕的公开可见结果。
   - 本轮未成功新增 `https://www.newrank.cn/search/trend/skill` 的深层详情，因此不能把搜索入口当成已验证正文来源。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。
   - 本轮不得新增未经验证的在线细节，只能沿用已留痕的可见趋势线索继续收口。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果、公开检索仅得邻近信号、以及 fallback 不可用状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么只教提示词的内容越来越难形成收藏、为什么“可复用路径”更容易被用户带走、怎样把趋势验证 / Topic 拆解 / Draft 改写 / Cover 包装 / Review 复审 串成一条内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI工作流内容为什么更容易被收藏和复用`。
- 副标题建议突出：`用户真正想带走的不是一句提示词，而是一整套路径`。
- 视觉重点放在“趋势验证 → Topic 拆爆点 → Draft 改写 → Cover 包装 → Review 复审 → Archive 归档”这条链路的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw` 系关键词直接命中不足，但 `AI skill`、`workflow`、`Copilot`、`Skills`、`全流程公开`、工具协同等已形成邻近趋势证据。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260312-082404`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、Copilot/Agent 协作技能、Skills 化表达、节点式工作流、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在提示词层，而更容易被收藏和复用的是能让用户直接照着走一遍的路径型内容”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-12`。
- `timestamp+中文标题` 层：`20260312-082404+AI工作流内容为什么更容易被收藏和复用：因为用户真正想带走的不是一句提示词，而是一整套可直接照着走的路径`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260312-082404.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 检索来源备注
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 本轮补充检索到的公开可见 Newrank 邻近结果包括：
  - `https://newrank.cn/?utm_source=openai`
  - `https://img-newrank.newrank.cn/sq/download/424/%E6%96%B0%E6%A6%9C_%E7%9F%A9%E9%98%B5%E7%BA%AA%E5%85%83%EF%BC%9A%E4%BC%81%E4%B8%9A%E6%96%B0%E5%AA%92%E4%BD%93%E7%94%9F%E6%80%81%E4%BD%8D%E4%B8%8E%E5%AE%9E%E8%B7%B5%E5%9B%BE%E8%B0%B1%202025-2030.pdf?utm_source=openai`
  - `https://newrank.cn/ranktopic/douyin/27/7/2026-01-04?utm_source=openai`
- 可继续沿用的历史留痕结果见：
  - `Boss/BOSS-CYCLE-20260312-075409.md:41-67`
  - `Boss/BOSS-CYCLE-20260312-072600.md:45-67`
  - `Boss/BOSS-CYCLE-20260312-060333.md:40-60`
  - `Boss/CLAUDE.md:3-21`
- 上述链接与留痕当前仅可作为标题 / 摘要片段 / 邻近趋势方向级证据使用，不能扩写成未验证正文事实。
- 当前会话可用 skill 列表未提供 `yhslgg-arch/url-reader`，因此 fallback 要求只能记录为未满足的环境限制。

## 当前判断
- 当前最大风险仍是来源留痕失真：Newrank 详情拿不到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是把“AI工作流内容为什么更容易被收藏和复用”写成空洞结论，因此下游必须把“用户为什么真正想带走完整路径”讲具体。
- 本轮不新增未经验证的 Newrank 细节，只沿用当前任务上下文、本轮检索到的公开可见入口/报告/榜单结果与上一轮已记录的可见趋势线索继续收口。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`）；`.role-sessions/current_task.md` 与 `SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260312-082404.md`
- 发布动作：未执行
