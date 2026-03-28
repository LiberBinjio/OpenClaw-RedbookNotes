2026-03-18/20260318-132911+AI技能内容开始按流程分层：真正能带走结果的，不是更会聊，而是能把一条链路稳定跑完/

@REVIEW

## Archive Package
- date: `2026-03-18`
- timestamp: `20260318-132911`
- archive_title: `AI技能内容开始按流程分层：真正能带走结果的，不是更会聊，而是能把一条链路稳定跑完`
- archive_package: `2026-03-18 / 20260318-132911+AI技能内容开始按流程分层：真正能带走结果的，不是更会聊，而是能把一条链路稳定跑完 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Result
- status: `FAIL`
- summary: `Boss、Draft、Cover 已切到本轮归档包，Draft 的改写边界基本合格；但 Topic 仍停留在旧时间戳与旧标题，且未按 Boss 要求补齐 3-5 个备选题与 archive 字段统一，因此本轮不能判定 preview-ready。`

## Checks
### 1. Newrank-first topic sourcing
- PASS: `.role-sessions/Topic/@TOPIC:13-25` 明确把 `https://www.newrank.cn/search/trend/skill` 写为 first source，并说明本轮未成功取得可核验的深层详情正文。
- PASS: `.role-sessions/Topic/@TOPIC:15-21` 对 `openclaw`、`openclaw skill`、`AI skill`、`workflow skill`、`copilot skill` 的证据强弱做了区分，没有把邻近线索伪造成 `search/trend/skill` 直连详情。
- PASS: `.role-sessions/Topic/@TOPIC:21-25` 如实写出 `yhslgg-arch/url-reader` 是 required fallback，但当前会话 skill 不可用，因此没有伪造 fallback 执行结果。
- CONDITIONAL: 任务要求中 fallback 是 required。当前只能记录环境缺失，无法提供实际 fallback 抓取证据，因此该项只能按受限状态保留，不能算完整通过。

### 2. Viral-copy breakdown / rewrite guidance in Topic
- PASS: `.role-sessions/Topic/@TOPIC:76-136` 包含 `Viral Copy Breakdown`，覆盖 hook、structure、conflict、promise、proof、CTA、keep/change/must not copy。
- PASS: `.role-sessions/Topic/@TOPIC:140-158` 包含 `Rewrite Direction`，明确哪些模式保留、哪些表达改写、哪些句子不能复制。
- PASS: `.role-sessions/Topic/@TOPIC:38-50` 提供了爆款参考方向，满足“produce viral-copy breakdowns”的方向要求。
- FAIL: `.role-sessions/Topic/@TOPIC:5-7` 的 archive 路径仍是 `2026-03-18/20260318-132911+AI工作流技能热度观察/`，没有对齐 Boss 指定的统一中文标题与 `material files` 结构。

### 3. Topic package completeness
- FAIL: `Boss/BOSS-CYCLE-20260318-132911.md:31-34` 要求 Topic 至少输出主选题、3-5 个备选题、目标人群、趋势线索、viral references、rewrite angle、hook breakdown，并把 `date`、`timestamp`、`archive_title`、`archive_package` 全量更新到本轮；但 `.role-sessions/Topic/@TOPIC:5-7` 只给出简化归档建议路径，没有完整 `date / timestamp / archive_title / archive_package` 字段。
- FAIL: `Boss/BOSS-CYCLE-20260318-132911.md:31` 要求 3-5 个备选题；`.role-sessions/Topic/@TOPIC:11-16` 提供了 5 个备选题，这一项数量合格，但整体 package 结构仍不完整。
- FAIL: `.role-sessions/Topic/@TOPIC:164-172` 给 Draft 的标题建议没有对齐 Boss 统一主题，导致 Topic 主选题与 Draft / Cover / Boss 的统一标题发生漂移。

### 4. Draft rewrite quality and plagiarism boundary
- PASS: `Draft/@DRAFT.md:76-80` 包含 `Viral Rewrite Notes`，明确是结构改写，不是句子复制。
- PASS: `Draft/@DRAFT.md:17-65` 保留了“旧认知失效 -> 新差距出现 -> 流程场景 -> 行动建议”的传播结构，但具体表达为原创改写，未见直接抄写 Topic 原句。
- PASS: `Draft/@DRAFT.md:27-31` 对 Newrank 入口受限与 fallback 不可用状态保持诚实表述，没有把未执行的 fallback 写成已执行成功。
- FAIL: `Boss/BOSS-CYCLE-20260318-132911.md:69` 要求附带简短 `viral-copy breakdown` 区块；`Draft/@DRAFT.md:76-80` 只有 `Viral Rewrite Notes`，没有单独标注或呈现简短 `viral-copy breakdown` 区块。

### 5. Chinese archive-ready material
- PASS: `Draft/@DRAFT.md:10-74` 已具备中文标题、备选标题、中文正文、Tags / Settings，并明确仅用于预览、复审与手动发布。
- PASS: `Cover/@COVER:3-67` 已提供中文封面候选、归档信息与发布边界。
- FAIL: `.role-sessions/Topic/@TOPIC:5-7` 未形成 Boss 要求的统一 archive package 字段，且标题与统一包名不一致。
- FAIL: `Review/@REVIEW:1-9` 现已更新为本轮归档包，但整包仍因 Topic 漂移而不能算 archive-ready。

### 6. Archive package consistency
- PASS: `Boss/BOSS-CYCLE-20260318-132911.md:16,22-23,34,70,79,88,103-110` 已明确指定本轮统一归档包。
- PASS: `Draft/@DRAFT.md:3-8` 与 `Cover/@COVER:3-8` 已和 Boss 对齐到 `20260318-132911` 与统一中文标题。
- FAIL: `.role-sessions/Topic/@TOPIC:5-7` 仍使用不一致的 archive 标题与目录结构，未满足 Topic / Draft / Cover / Review 全部统一到 `20260318-132911` 的硬性要求。

### 7. Preview and publishing boundary
- PASS: `.role-sessions/Topic/@TOPIC:209-214`、`Draft/@DRAFT.md:66-74`、`Cover/@COVER:3-17,61-67`、`Review/@REVIEW:5-10` 均明确写明仅用于预览、复审与手动发布，不自动公开发布。

## Rework Items
1. 重写 `.role-sessions/Topic/@TOPIC` 的归档头部，补齐并统一 `date`、`timestamp`、`archive_title`、`archive_package`，必须对齐：`2026-03-18 / 20260318-132911+AI技能内容开始按流程分层：真正能带走结果的，不是更会聊，而是能把一条链路稳定跑完 / material files`。
2. 保持 Topic 现有的 Newrank-first 和 fallback 限制说明，但把主选题与给 Draft 的标题建议统一到 Boss 指定主题，避免 Topic 与 Draft / Cover 再次漂移。
3. 在 `Draft/@DRAFT.md` 中补一个简短、显式标注的 `viral-copy breakdown` 区块，满足 Boss 对 Draft 的硬性要求。
4. 修正后再次复核 Topic / Draft / Cover / Review 的 archive package 是否完全一致；在 Topic 未修正前，不应标记为 preview-ready。
5. 若后续环境补充 `yhslgg-arch/url-reader`，再补实际 fallback 抓取记录；若仍不可用，继续明确写成环境限制，不得伪造。

## Preview Readiness
- 当前结论：`FAIL`
- 原因：Newrank-first 与非抄写边界基本合格，但 Topic 未统一到本轮 archive package，且 Draft 缺少显式 `viral-copy breakdown` 区块，未满足 Boss 的硬性结构要求。
- 备注：完成上述 rework items 后再复审，才可考虑转为 CONDITIONAL 或 PASS。
