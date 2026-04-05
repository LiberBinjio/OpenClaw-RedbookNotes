# @REVIEW

## Archive Package
- date: `2026-04-06`
- timestamp: `20260405-195232`
- archive_title: `AI技能内容开始从功能盘点走向角色编排，真正会被收藏的是能直接交接的Agent workflow`
- archive_package: `2026-04-06 / 20260405-195232+AI技能内容开始从功能盘点走向角色编排，真正会被收藏的是能直接交接的Agent workflow / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Result
- status: `CONDITIONAL`
- preview_readiness: `可预览、可复审，但当前不能算来源闭环完全通过版`
- overall_judgement: `本轮 Topic / Draft / Cover 已统一到 20260405-195232 archive package，Draft 也包含 Viral Rewrite Notes，正文整体属于结构改写而非句子照搬；但按规则要求，Newrank detail 不可用时应执行 yhslgg-arch/url-reader fallback 并记录抓取结果。当前环境未提供该 skill，因此本轮只能判定为 CONDITIONAL，不能判定为 PASS。`

## Required Checks

### 1. Topic 是否提到 Newrank 趋势证据或明确说明限制
- 结果：`PASS`
- 依据：`.role-sessions/Topic/@TOPIC:10`-`.role-sessions/Topic/@TOPIC:37` 明确写出首要来源是 `https://www.newrank.cn/search/trend/skill`，并如实记录本轮未取得可复核 detail，也没有把未核验内容写成事实。
- 复核结论：满足“Newrank-first 或明确限制”要求。

### 1a. Newrank detail 不可用时，是否使用 yhslgg-arch/url-reader fallback 并记录抓取结果
- 结果：`CONDITIONAL`
- 依据：`.role-sessions/Topic/@TOPIC:20`-`.role-sessions/Topic/@TOPIC:28` 已明确写出 required fallback 是 `yhslgg-arch/url-reader`，但当前环境只提供 `simplify` 与 `claude-api`，因此 fallback 未执行，也没有可归档的 fetched record。
- 复核结论：没有伪造 fallback 结果，这一点正确；但 required fallback evidence 仍缺，所以不能判定为完全通过。

### 2. Draft 是否包含 Viral Rewrite Notes
- 结果：`PASS`
- 依据：`.role-sessions/runtime/@DRAFT:68`-`.role-sessions/runtime/@DRAFT:73` 存在独立 `Viral Rewrite Notes` 段落。

### 3. Draft 是否是改写结构而不是复制句子
- 结果：`PASS`
- 依据：`.role-sessions/runtime/@DRAFT:17`-`.role-sessions/runtime/@DRAFT:56` 采用“来源边界说明 → 趋势判断 → 4 个流程节点 → 方法结论 → CTA”的重写结构；`.role-sessions/runtime/@DRAFT:68`-`.role-sessions/runtime/@DRAFT:73` 也明确声明保留传播结构、重写句式，不复制外部标题、导语或总结句。
- 复核结论：当前稿件属于重写 viral pattern，不是直接搬运 viral wording。

### 4. 是否产出中文 archive-ready material（title/body/tags/settings）
- 结果：`PASS`
- 依据：
  - Topic 归档元数据：`.role-sessions/Topic/@TOPIC:3`-`.role-sessions/Topic/@TOPIC:8`
  - Draft 标题与正文：`.role-sessions/runtime/@DRAFT:10`-`.role-sessions/runtime/@DRAFT:57`
  - Draft tags/settings：`.role-sessions/runtime/@DRAFT:58`-`.role-sessions/runtime/@DRAFT:66`
  - Cover 方案：`Cover/@COVER:26`-`Cover/@COVER:76`
  - Review 归档元数据：`Review/@REVIEW:3`-`Review/@REVIEW:8`
- 复核结论：中文标题、正文、标签、设置、封面候选与 archive folder layout 元数据已齐备。

## Additional Review Notes
- `.role-sessions/Topic/@TOPIC:119`-`.role-sessions/Topic/@TOPIC:176` 已包含 `Viral Copy Breakdown`，满足 Topic 端“produce viral-copy breakdowns”要求。
- `.role-sessions/Topic/@TOPIC:56`-`.role-sessions/Topic/@TOPIC:70` 已如实写清 Newrank 邻近公开线索与证据边界，没有冒充 `search/trend/skill` 直连详情。
- `.role-sessions/runtime/@DRAFT:24`-`.role-sessions/runtime/@DRAFT:30` 正确继承了 Newrank detail 缺失与 fallback 不可执行的来源边界，没有伪造榜单、热度、互动量或详情页正文。
- `Cover/@COVER:10`-`Cover/@COVER:16` 保持相同来源边界，并遵守“仅用于预览、复审与手动发布，不自动公开发布”。
- `.role-sessions/Topic/@TOPIC:3`-`.role-sessions/Topic/@TOPIC:8`、`.role-sessions/runtime/@DRAFT:3`-`.role-sessions/runtime/@DRAFT:8`、`Cover/@COVER:3`-`Cover/@COVER:8` 与本文件已统一到 `2026-04-06 / 20260405-195232+AI技能内容开始从功能盘点走向角色编排，真正会被收藏的是能直接交接的Agent workflow / material files`。

## Rework Items
1. 如果后续环境提供 `yhslgg-arch/url-reader`，需要对 `https://www.newrank.cn/search/trend/skill` 执行 required fallback，并把实际抓取路径、抓取结果、可引用边界写入 Topic 后再复审。
2. 如果当前环境仍无法提供该 skill，需要在最终归档说明里单独标注“required fallback 因环境缺失未执行”，避免被误读为已完成来源闭环。
3. 最终手动发布前，继续保持当前边界：只引用已核验的 Newrank 入口状态与邻近公开标题级线索，不补写未核验的热度、排名、互动数据、截图结论或详情页正文。

## Final Decision
- 当前结论：`CONDITIONAL`
- 可继续用途：`预览 / 复审 / 手动发布准备`
- 不可直接声称：`已完成 Newrank detail + url-reader fallback 的完整来源闭环`
- 发布边界：`不自动公开发布`
