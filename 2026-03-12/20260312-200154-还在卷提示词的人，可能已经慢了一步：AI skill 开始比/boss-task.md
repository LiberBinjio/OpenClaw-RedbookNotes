# Boss Cycle 20260312-200154

## 当前重点
- 当前继续以 Redbook 五角色内容工厂推进：Boss / Topic / Draft / Cover / Review。
- 本轮 Boss 只写一个任务文件，所有下游产物都必须能收进归档结构：`date / timestamp+中文标题 / material files`。
- 默认交付目标仍是可预览、可复审、可手动发布的内容包，不做自动公开发布。
- 严格遵守分支与边界：仅在 `RedbookClaw` 工作，不触碰 `main/master`，不修改 `node5`，且口径只面向 `@ALL` 与 `@BOSS`。

## 本轮实际动作
1. 已读取 `Boss/CLAUDE.md` 与 `.role-sessions/current_task.md`，并确认本轮仍需先验分支、只写一份 Boss 任务文件、统一 archive-ready 输出。
2. 已执行 `git branch --show-current`，当前分支为 `RedbookClaw`，符合继续工作的前提。
3. 已尝试读取 `Boss/SAF-TaskAssignAndProgress.md`；当前 `Boss/` 下不存在该文件，已如实记录缺失状态。
4. 已复核当前仓库中的 `@TOPIC`，确认 Topic 已如实写明：Newrank 入口被优先检查、可验证详情未成功取得、`yhslgg-arch/url-reader` 在当前环境不可用，因此不能伪造详情或 fallback 结果。
5. 已确认当前会话可用 skill 仅有 `simplify` 与 `claude-api`；任务要求中的 `yhslgg-arch/url-reader` 不在可用列表内，调用结果为 `Unknown skill`，因此本轮只能把该 fallback 作为未满足的环境限制留痕。
6. 已尝试直接抓取 `https://www.newrank.cn/search/trend/skill`，但网页抓取工具返回 `API Error 400`，因此本轮仍不能把该页细节写成已核实事实。
7. 已确认本轮可复用的稳定趋势表达边界：围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 五个任务指定关键词输出“方向型趋势包”，并明确哪些词当前没有直连详情。
8. 已确认本轮 archive package 必须统一为：`2026-03-12 / 20260312-200154+AI技能的下一波红利，不是更会聊天，而是更会把工作流跑通 / material files`。
9. 已确认本轮只准备预览、复审与手动发布所需内容，不执行任何公开发布动作。

## 本轮 Boss 任务
- 面向 `@ALL` 与 `@BOSS`：围绕单一中文主题继续收口，所有产物必须统一到同一个 archive package。
- 推荐统一主题：`AI技能的下一波红利，不是更会聊天，而是更会把工作流跑通`。
- 统一归档日期：`2026-03-12`。
- 统一归档包：`2026-03-12 / 20260312-200154+AI技能的下一波红利，不是更会聊天，而是更会把工作流跑通 / material files`。

### Topic 要求
- 必须先把 `https://www.newrank.cn/search/trend/skill` 作为一手入口写进来源状态，再决定本轮主话题。
- 必须优先围绕 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 这些关键词组织检索方向，并明确写出哪些词没有直接命中、哪些词只找到了方向级或邻近趋势信号。
- Topic 必须优先产出一个可直接支持“AI技能的下一波红利，不是更会聊天，而是更会把工作流跑通”的主选题。
- 如果 Newrank 详情不可用、受限或不稳定，必须明确写出：入口已检查、详情缺失/受限、当前不能把该页当成已验证细节来源。
- 如果 Newrank 详情不可用，按要求应先尝试 `yhslgg-arch/url-reader` fallback；但本轮 Boss 已确认当前环境 skill 缺失，不可执行，因此 Topic 必须把“fallback 要求存在，但当前会话 skill 缺失/不可调用”写成来源限制，不得伪造 fallback 结果。
- Topic 必须输出可直接交给 Draft 使用的中文 topic package，至少包含：主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown。
- 必须包含明确的 `Viral Copy Breakdown` 段落，至少拆出：hook、结构、冲突点、承诺、证据、CTA；只能拆模式，不能抄原句。
- 必须包含明确的 `Rewrite Direction` 段落，说明哪些模式保留、哪些表达改写、哪些句子绝不能复制。
- 必须把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮：`2026-03-12`、`20260312-200154` 与统一中文标题，避免 Topic 与 Draft / Cover / Review 落入不同归档包。
- 在趋势表达上，要优先收口到“AI 的价值正在从一次性回答升级成稳定执行完整流程”，而不是泛泛讨论模型能力。

### Draft 要求
- 必须继承 Topic 中真实可验证的来源状态，尤其是 Newrank-first 结果、详情抓取失败、fallback 不可用状态，以及当前未拿到深层详情的限制状态。
- 必须输出：1 个最终中文标题、2 个备选标题、1 篇中文正文、1 个 tags/settings 区块。
- 必须保留 `Viral Rewrite Notes` 或等价段落，清楚说明这是对爆款结构的改写，不是句子复制。
- 正文建议重点写清三段：为什么只把 AI 当聊天框会越来越不稳定、为什么 workflow skill 更容易沉淀成可复用结果、怎样把选题 / 写稿 / 审稿 / 归档串成一条可重复执行的内容生产线。
- Draft 必须产出中文标题、中文正文、标签，并附带简短 `viral-copy breakdown` 区块，满足当前任务要求。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。
- 不得公开发布，不得写成自动发布指令。

### Cover 要求
- 封面方向必须与统一中文标题一致，并支持归档目录下独立留存。
- 主标题建议突出：`AI技能的下一波红利`。
- 副标题建议突出：`不是更会聊天，而是更会把工作流跑通`。
- 视觉重点放在“从单次提问到完整执行”的升级感，以及选题、写稿、审稿、归档能被串起来的结果感。
- 标题与副标题尽量短促有力，页面逻辑清晰，方便后续预览与手动发布。
- 归档目录、时间戳、中文标题必须与本轮统一 package 完全一致。

### Review 要求
- 必须核验 Topic 是否优先使用了 Newrank 作为趋势来源，或明确说明了当前受限原因。
- 必须核验 Topic 是否写清：`openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`Copilot skill` 五个词当前的命中边界与证据强弱，不得把未命中的词写成已抓到详情。
- 必须核验 Topic 是否如实说明 `yhslgg-arch/url-reader` fallback 当前不可用；若写成“已抓到详情”，直接打回。
- 必须核验 Topic 是否补齐 `Viral Copy Breakdown` 与 `Rewrite Direction`。
- 必须核验 Draft 是否包含 `Viral Rewrite Notes` 与简短 `viral-copy breakdown`。
- 必须核验 Draft 是否保持“结构改写而非句子复制”。
- 必须核验 Topic / Draft / Cover / Review 的 archive timestamp 与 archive package 是否统一到 `20260312-200154`。
- 必须核验最终产物仅用于预览、复审与手动发布，不自动公开发布。

## 当前判断
- 当前最大风险仍是来源留痕失真：`https://www.newrank.cn/search/trend/skill` 没有稳定拿到可验证详情，就必须诚实写限制；指定 fallback skill 当前不可用，也必须诚实写不可用。
- 当前次级风险是 archive package 漂移：本轮所有下游都必须统一切到 `20260312-200154`，避免 Topic / Draft / Cover / Review 沿用旧时间戳导致归档包不一致。
- 当前内容机会点明确：用户对 AI 内容的价值判断，正从“会不会写 prompt”转向“能不能把一段流程稳定跑通并复用”。
- 因此本轮 Boss 的核心任务不是扩题，而是把来源优先级、fallback 状态、viral-copy breakdown、rewrite 边界、统一 archive package、以及非公开发布边界再次写清，供下游收口。
- 本轮未进行任何公开发布或外部可见发布动作。

## 归档要求
- 最终内容包必须能按 `date / timestamp+中文标题 / material files` 组织。
- `date` 层：`2026-03-12`。
- `timestamp+中文标题` 层：`20260312-200154+AI技能的下一波红利，不是更会聊天，而是更会把工作流跑通`。
- `material files` 层建议保留：
  - `Boss/BOSS-CYCLE-20260312-200154.md`
  - `@TOPIC`
  - `Draft/@DRAFT.md`
  - `Cover/@COVER`
  - `Review/@REVIEW`
  - 来源状态说明 / 选题依据摘要 / 正文依据摘要 / 封面方向说明 / 复审检查记录

## 结果
- 分支检查：通过（`RedbookClaw`）
- 指令文件读取：完成（`Boss/CLAUDE.md`、`.role-sessions/current_task.md`）；`Boss/SAF-TaskAssignAndProgress.md` 当前不存在
- 实际改动：新增 `Boss/BOSS-CYCLE-20260312-200154.md`
- 发布动作：未执行
