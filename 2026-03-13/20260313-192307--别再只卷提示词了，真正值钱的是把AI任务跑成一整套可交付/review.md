# @REVIEW

## Review Result
- Verdict: **CONDITIONAL**
- Archive package target: `2026-03-14 / 20260313-192307+AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完 / material files`
- Publish boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Checklist
1. **Branch check**: PASS
   - `git branch --show-current` returned `RedbookClaw`.

2. **Newrank-first topic sourcing**: PASS
   - Topic explicitly prioritizes `https://www.newrank.cn/search/trend/skill` and states current detail extraction is unavailable: `TOPIC/topic-package.md:19-25`.
   - Topic does **not** fabricate ranking/detail data and limits claims to topic-direction judgment: `TOPIC/topic-package.md:21-24`, `TOPIC/topic-package.md:119-123`.

3. **Required fallback evidence (`yhslgg-arch/url-reader`)**: PASS WITH LIMITATION
   - Topic clearly records that the required fallback skill is unavailable in the current environment and was therefore not executed: `TOPIC/topic-package.md:22-23`, `TOPIC/topic-package.md:121-123`.
   - This matches the current skill availability and is honestly reported rather than fabricated.

4. **Viral-copy breakdown in Topic**: PASS
   - Topic includes both `Viral Copy Breakdown` and `Rewrite Direction`: `TOPIC/topic-package.md:54-117`.

5. **Draft includes rewrite notes**: PASS
   - Draft includes `## Viral Rewrite Notes`: `Draft/@DRAFT.md:91-95`.

6. **Draft rewrites structure instead of copying sentences**: PASS
   - Draft uses the approved structure shift from “prompt” to “workflow/交付” and adds an original four-step explanation (`找信号 / 分层判断 / 重写交付 / 归档留痕`), indicating structural adaptation rather than sentence copying: `Draft/@DRAFT.md:44-57`.
   - Review did not find obvious direct-copy viral phrasing lifted from Topic’s forbidden examples.

7. **Chinese archive-ready material**: PASS
   - Topic is Chinese and archive-oriented: `TOPIC/topic-package.md:1-3`.
   - Draft contains Chinese title/body/tags/settings: `Draft/@DRAFT.md:6-12`, `Draft/@DRAFT.md:13-89`.
   - Cover is Chinese and archive-aligned: `Cover/@COVER:3-19`, `Cover/@COVER:21-74`.

8. **Archive package consistency**: FAIL
   - Boss defines the required archive package as `2026-03-14 / 20260313-192307+AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完 / material files`: `Boss/BOSS-CYCLE-20260313-192307.md:17`, `Boss/BOSS-CYCLE-20260313-192307.md:24`.
   - Draft matches that package: `Draft/@DRAFT.md:3-4`, `Draft/@DRAFT.md:87-89`.
   - Cover matches that package: `Cover/@COVER:4-8`.
   - **Topic does not match** and still points to an old package `2026-03-13 / 20260312-183254-技能工作流选题包 / topic-package.md`: `TOPIC/topic-package.md:2`.
   - Topic also does not include the explicit `date / timestamp / archive_title / archive_package` metadata block required by Boss for this cycle.

## Required Rework
1. Update `TOPIC/topic-package.md` to the current cycle package:
   - `date: 2026-03-14`
   - `timestamp: 20260313-192307`
   - `archive_title: AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完`
   - `archive_package: 2026-03-14 / 20260313-192307+AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完 / material files`
2. Replace the stale archive suggestion at `TOPIC/topic-package.md:2` so Topic/Draft/Cover/Review all point to the same folder.
3. Keep the existing honest Newrank/fallback limitation wording; that part is acceptable and should not be expanded into fabricated detail.

## Final Decision
- **CONDITIONAL**
- Reason: sourcing honesty and rewrite quality pass, but Topic is not yet aligned to the required archive folder layout for this cycle.
