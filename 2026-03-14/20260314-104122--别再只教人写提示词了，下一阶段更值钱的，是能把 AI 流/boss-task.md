# Boss Cycle 20260314-104122

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际状态
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已尝试补查 `SAF-TaskAssignAndProgress.md` 相关文件命名，当前仓库仍未找到该文件，已如实记录缺失状态。
4. 已复核既有 Boss / Topic / Draft / Cover 产物样式，确认本轮仍应输出一份可直接驱动 Topic / Draft / Cover / Review 的统一任务文件。
5. 当前会话可用 skills 只有 `simplify` 与 `claude-api`；任务要求中的 `yhslgg-arch/url-reader` 当前不可用，因此 fallback 要求存在，但本轮不能执行，也不能伪造抓取结果。
6. 本轮任务明确要求 Topic 优先使用 `https://www.newrank.cn/search/trend/skill` 并产出 viral-copy breakdown；若 Newrank detail unavailable，必须如实写明限制，不能把 fallback 写成已执行。
7. 既有 Topic 留痕表明：已优先检查 Newrank 入口，并围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill` 尝试公开 markdown 端点；当前只拿到空模板/无有效趋势明细，因此不能把这些关键词扩写成已核实热度结论。
8. 本轮统一 archive package 采用：`2026-03-14 / 20260314-104122+AI技能内容开始拼交付，不再拼谁写出了更长的提示词，而是谁把整套流程做成可复用成果 / material files`。
9. 本轮继续只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能内容开始拼交付，不再拼谁写出了更长的提示词，而是谁把整套流程做成可复用成果`。
- 统一归档日期：`2026-03-14`。
- 统一归档包：`2026-03-14 / 20260314-104122+AI技能内容开始拼交付，不再拼谁写出了更长的提示词，而是谁把整套流程做成可复用成果 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只拿到了公开可见但不足以扩写为详情的线索。
- Topic 必须优先产出一个可直接支持“AI技能内容开始拼交付，不再拼谁写出了更长的提示词，而是谁把整套流程做成可复用成果”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失/受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-14`、`20260314-104122` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 在趋势表达上，要优先收口到“AI 内容真正开始分层，不再只比 prompt，而是比谁能交付一整条可复用流程”，而不是泛泛讨论模型能力。

### 本轮可用趋势线索
1. **Newrank 优先入口状态**
   - 一手入口仍是 `https://www.newrank.cn/search/trend/skill`。
   - 当前任务要求是优先使用该入口，但本轮已知留痕只证明：入口已检查，围绕优先关键词的公开 markdown 端点仅返回空模板或无有效明细；因此下游只能把它写成优先入口与检查对象，不能扩写成已核实正文事实。
2. **`openclaw` / `openclaw skill` 命中状态**
   - 既有留痕显示，这两个词都已作为优先关键词检查过，但公开 markdown 端点未返回可验证趋势详情。
   - 因此本轮可写的是“已优先检查，但详情不足”，而不是“这两个词已证实在 skill 趋势页爆发”。
3. **`AI skill` / `workflow skill` / `Copilot skill` 命中状态**
   - 既有留痕显示，这些关键词同样已被检查，但公开 markdown 端点未返回有效趋势明细。
   - 因此 Topic 只能把它们写成“检索过但当前公开细节不足”的状态，不得补写排行、热度、互动量或作者信息。
4. **趋势收口方向**
   - 当平台已存在 `skill` 观察入口，但目标关键词的公开详情又不稳定时，更稳妥的选题不是伪造热度，而是回到用户真正关心的结果：AI 到底能不能把一条工作流稳定跑完、能不能留下可复用成果。
   - 因而本轮内容判断应继续收口到“AI 内容从工具介绍转向结果交付、从单次回答转向流程复用”这一方向。
5. **来源限制说明**
   - 当前可确认的是 Newrank 入口存在且已被优先检查，以及优先关键词的公开 markdown 端点未返回有效明细。
   - 当前不能确认的是 `https://www.newrank.cn/search/trend/skill` 深层详情页正文、榜单数值、完整条目。
   - 指定 fallback `yhslgg-arch/url-reader` 在当前会话不可用，因此不能把 fallback 写成已执行成功。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果、公开检索仅得空模板/缺少有效明细、fallback 不可用状态，以及本轮未拿到深层详情的限制状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么只把 AI 当聊天框会越来越难形成复用价值、为什么 workflow skill 更容易沉淀成可反复调用的结果、怎样把选题 / 写稿 / 审稿 / 归档串成一条可重复执行的内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能内容开始拼交付`。
- 副标题建议突出：`不再拼长提示词，而是拼流程复用`。
- 视觉重点放在“从单次回答到整套执行链路”的升级感，以及选题、写稿、审稿、归档能被串起来的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 均已优先检查，但当前公开 markdown 端点未返回可验证趋势详情。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260314-104122`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 推荐选题边界
- 优先方向：AI 技能趋势、工作流技能、OpenClaw 相关大众化关注、Copilot/Agent 协作技能、节点式工作流、内容归档、内容复盘、material files 组织。
- 内容重点：不是泛泛讲 AI，而是讲“为什么很多 AI 内容还停在提示词层，而更容易被收藏和复用的是能让用户直接照着走一遍的路径型内容”。
- 本轮重点不是扩出多个主题，而是围绕单一主题收口，并把来源证据、fallback 状态、改写边界、归档统一要求写清楚。
- 禁止事项：
  - 不直接复制爆款原句。
  - 不伪造 Newrank 或 fallback 来源证据。
  - 不生成自动公开发布动作。
  - 不偏离统一中文标题与 archive package。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-14`。
- `timestamp+中文标题` 层：`20260314-104122+AI技能内容开始拼交付，不再拼谁写出了更长的提示词，而是谁把整套流程做成可复用成果`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260314-104122.md`
  - `.role-sessions/Topic/@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 检索来源备注
- Newrank 优先入口：`https://www.newrank.cn/search/trend/skill`
- 本轮可继承的来源边界：入口已检查；优先关键词的公开 markdown 端点返回空模板/无有效趋势明细。
- 上述留痕只可作为“检索过但详情不足”的证据使用，不能扩写成未验证正文事实。
- 当前会话可用 skill 列表未提供 `yhslgg-arch/url-reader`，因此 fallback 要求只能记录为未满足的环境限制。
- 本轮仍未获得 `https://www.newrank.cn/search/trend/skill` 的可验证详情页正文，因此只能记录为“已优先检查入口，但未成功取得可验证深层详情”。

## 当前判断
- 当前最大风险仍是来源留痕失真：`search/trend/skill` 精确详情没有稳定拿到，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是 archive package 漂移：本轮所有下游都必须统一到 `20260314-104122`，避免 Topic / Draft / Cover / Review 沿用旧时间戳导致归档包不一致。
- 当前内容机会点明确：用户对 AI 内容的价值判断，正从“会不会写 prompt”转向“能不能把一段流程稳定跑通并复用”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`SAF-TaskAssignAndProgress.md` 当前未找到
- 实际改动：新增 `Boss/BOSS-CYCLE-20260314-104122.md`
- 发布动作：未执行
