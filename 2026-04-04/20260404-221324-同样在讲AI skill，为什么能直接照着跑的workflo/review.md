# @REVIEW

## Archive Package
- date: `2026-04-04`
- timestamp: `20260404-214101`
- archive_title: `AI图文内容别再堆功能了用户更想收藏能直接照着跑的工作流`
- archive_package: `2026-04-04 / 20260404-214101+AI图文内容别再堆功能了用户更想收藏能直接照着跑的工作流 / material files`
- publish_boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Review Result
- status: `FAIL`
- summary: `本轮 Topic 与 Draft 基本满足 Newrank-first、改写而非照搬、中文产物齐备与不自动发布等要求；但仍未达到 preview readiness。核心问题有三项：一是按规则要求的 yhslgg-arch/url-reader fallback 未实际执行，因此没有 fallback fetch 记录；二是 Boss、Topic、Draft、Cover 的 archive package 命名不一致，无法形成同轮统一归档；三是当前仓库内未见本轮 20260404-214101 对应的 material files 实际落盘。基于 Review/CLAUDE.md 规则，本轮应判定为 FAIL，并给出明确返工项。`

## Checks
### 1. Newrank-first topic sourcing
- PASS: `.role-sessions/Topic/@TOPIC:12-29` 明确写出首要来源是 `https://www.newrank.cn/search/trend/skill`，且保留了本轮实际检查路径与证据边界。
- PASS: `.role-sessions/Topic/@TOPIC:35-37` 明确限制只能把首页公开可见线索写成事实，不能补写排名、热度、详情页正文或截图结论。
- PASS: `.role-sessions/runtime/@DRAFT:26-30` 延续了 Newrank-first 与证据边界，没有把未核验 detail 扩写成事实。
- CONDITIONAL: `.role-sessions/Topic/@TOPIC:16-19` 声称可从 `__NEXT_DATA__` 读到公开线索，但 `.role-sessions/BOSS.md:15-21` 与 `.role-sessions/logs/Boss-20260404-214101.log:8-9` 的口径更保守，仅写“只见站点通用首页壳、未拿到趋势详情”。两处证据口径不完全一致，返工时应统一成同一边界说明。

### 1a. Required fallback evidence
- PASS: `.role-sessions/Topic/@TOPIC:20-28` 与 `.role-sessions/runtime/@DRAFT:26-27` 都如实说明：按任务要求应使用 `yhslgg-arch/url-reader` 作为 required fallback，但当前环境未提供该 skill，不能伪造已执行。
- FAIL: `.role-sessions/Topic/@TOPIC:27-28` 已明确写出 `actual_fallback_execution: 未执行`，因此并没有满足 Review 规则中“若 Newrank detail 不可用，则用 url-reader fallback 并记录抓取内容”的要求。
- FAIL: 当前会话技能列表只有 `simplify` 与 `claude-api`，没有 `yhslgg-arch/url-reader`；在 fallback 无法执行的前提下，本轮最多只能保留限制说明，不能视为 evidence complete。

### 2. Viral Rewrite Notes / breakdown
- PASS: `.role-sessions/Topic/@TOPIC:71-167` 提供了完整的 viral-copy breakdown，覆盖 hook、structure、conflict、promise、proof、CTA 与禁抄边界。
- PASS: `.role-sessions/runtime/@DRAFT:71-75` 包含独立 `Viral Rewrite Notes`，符合 Draft 必检项。
- PASS: `Cover/@COVER:19-25` 也提供了封面层的 viral-copy breakdown，并明确不复制外部句子。

### 3. Rewrite quality / anti-copy check
- PASS: `.role-sessions/runtime/@DRAFT:17-59` 正文采用“认知反差 -> 来源边界 -> 4 个 workflow 节点 -> 收束 CTA”的原创组织方式，整体看是借结构与节奏，不是照抄外部原句。
- PASS: `.role-sessions/runtime/@DRAFT:71-75` 明确声明保留的是钩子、推进节奏和收藏理由，而不是外部爆文句子本身。
- PASS: `Cover/@COVER:27-73` 封面候选与视觉说明延续同一判断，但未见直接复制 viral wording，也未虚构榜单结论。

### 4. Chinese archive-ready material
- PASS: `.role-sessions/Topic/@TOPIC:5-10`、`.role-sessions/runtime/@DRAFT:3-8`、`Cover/@COVER:3-8` 都给出了中文 archive package 字段与 `publish_boundary`。
- PASS: `.role-sessions/runtime/@DRAFT:10-69` 已提供中文标题、中文正文、tags、settings、source boundary，满足 Draft 交付要求。
- PASS: `Cover/@COVER:27-73` 已提供 4 个中文封面候选，满足至少 3 个 cover candidates 的要求。
- FAIL: `.role-sessions/BOSS.md:2` 给出的归档路径是 `2026-04-05 / 20260404-214101+AI技能别再只堆工具先把工作流跑通 / material files`，而 `.role-sessions/Topic/@TOPIC:3-9`、`.role-sessions/runtime/@DRAFT:4-8`、`Cover/@COVER:4-8` 使用的是 `2026-04-04 / 20260404-214101+AI图文内容别再堆功能了用户更想收藏能直接照着跑的工作流 / material files`。同轮 archive package 未统一。
- FAIL: 仓库中未找到本轮 `20260404-214101` 对应的归档目录与 material files 实际文件落盘；搜索结果显示该轮只有工作区文件与日志，没有对应归档目录文件。

### 5. Preview / publishing boundary
- PASS: `.role-sessions/Topic/@TOPIC:5-10`、`.role-sessions/runtime/@DRAFT:3-8`、`Cover/@COVER:3-8` 均保留“仅用于预览、复审与手动发布，不自动公开发布”的边界。
- PASS: `.role-sessions/current_task.md:18` 与 `Review/CLAUDE.md:5,15` 要求不自动公开发布；当前未见任何公开发布动作。

## Rework Items
1. 若后续环境提供 `yhslgg-arch/url-reader`，必须对 `https://www.newrank.cn/search/trend/skill` 执行 required fallback，并在 Topic 中补写实际抓取内容、抓取路径与记录边界；在此之前，fallback evidence 继续视为未完成。
2. 统一同轮 archive package 命名。Boss、Topic、Draft、Cover、Review 必须使用同一个 `date / timestamp+Chinese title / material files`，不能出现 `2026-04-05` 与 `2026-04-04`、不同中文标题并存的情况。
3. 将本轮 material files 实际落盘到统一 archive 目录，而不是只在工作区文件中声明 archive_package 字段。
4. 统一 Newrank 证据口径：如果只能确认站点首页壳或有限公开线索，就用同一套保守表述，不要让 Boss 与 Topic 出现一处说“只见首页壳”、另一处说“已提取到首页推荐标题”的不一致描述。
5. 保持当前 Draft 的改写方式与证据边界，不要把 Topic 中未核验的 `openclaw / copilot` detail、排名、热度或隐藏正文补写进最终稿。

## Preview Readiness
- current_result: `NOT PREVIEW READY`
- condition_note: `required fallback 未执行、归档命名不统一、material files 未实际落盘，这三项任一未补齐前，本轮都不应进入 preview ready。`
