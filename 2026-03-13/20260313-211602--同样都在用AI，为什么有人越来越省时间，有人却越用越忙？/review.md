# @REVIEW

## Review Result
- Verdict: **CONDITIONAL**
- Archive package target: `2026-03-14 / 20260313-195347+AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完 / material files`
- Publish boundary: `仅用于预览、复审与手动发布，不自动公开发布`

## Checklist
1. **Branch check**: PASS
   - `git branch --show-current` returned `RedbookClaw`.

2. **Newrank-first topic sourcing**: PASS WITH LIMITATION
   - Topic explicitly prioritizes `https://www.newrank.cn/search/trend/skill`: `.role-sessions/Topic/@TOPIC:20-25`.
   - Topic honestly states that usable Newrank detail data was not obtained and does not fabricate ranking/detail claims: `.role-sessions/Topic/@TOPIC:21-25`, `.role-sessions/Topic/@TOPIC:27-32`.

3. **Required fallback evidence (`yhslgg-arch/url-reader`)**: CONDITIONAL
   - Topic correctly records that the required fallback path exists and that the skill is unavailable in the current environment, so it was not executed: `.role-sessions/Topic/@TOPIC:24-25`, `.role-sessions/Topic/@TOPIC:30-31`.
   - This is honest and non-fabricated, but it is still a limitation against the ideal requirement because no fallback fetch evidence exists.

4. **Viral-copy breakdown in Topic**: PASS
   - Topic includes a clear `Viral Copy Breakdown` section with hook / structure / conflict / promise / proof / CTA style decomposition: `.role-sessions/Topic/@TOPIC:68-101`.
   - Topic also includes `Rewrite Direction`: `.role-sessions/Topic/@TOPIC:103-123`.

5. **Draft includes rewrite notes**: PASS
   - Draft includes `## Viral Rewrite Notes`: `Draft/@DRAFT.md:77-81`.

6. **Draft includes required viral-copy breakdown**: FAIL
   - Boss and task instructions require Draft to include a short `viral-copy breakdown` section.
   - Current Draft includes `Viral Rewrite Notes` but does **not** include a `viral-copy breakdown` section or equivalent labeled block: `Draft/@DRAFT.md:77-82`.

7. **Draft rewrites structure instead of copying sentences**: PASS
   - Draft follows the approved idea shift from “提示词” to “流程交付” and expands it through original structure, including来源边界、三种流程能力、内容生产链路、以及归档动作: `Draft/@DRAFT.md:18-67`.
   - Review did not find obvious direct copying of Topic’s example phrasing or a pasted viral sentence set.

8. **Chinese archive-ready material**: PASS
   - Topic is Chinese and archive-oriented with date/path guidance: `.role-sessions/Topic/@TOPIC:1-2`.
   - Draft contains Chinese title, body, tags/settings, and archive metadata: `Draft/@DRAFT.md:6-12`, `Draft/@DRAFT.md:13-75`.
   - Cover is Chinese and archive-aligned: `Cover/@COVER:3-19`, `Cover/@COVER:21-74`.

9. **Archive package consistency**: FAIL
   - Boss defines the required package as `2026-03-14 / 20260313-195347+AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完 / material files`: `Boss/BOSS-CYCLE-20260313-195347.md:21-23`.
   - Draft matches that package: `Draft/@DRAFT.md:3-4`, `Draft/@DRAFT.md:73-75`.
   - Cover matches that package: `Cover/@COVER:4-8`.
   - Review now matches that package.
   - **Topic does not fully match**: its archive suggestion is still `2026-03-14 / 20260313-195347+AI工作流技能拆解 / material files`, which differs from the unified Chinese title package required by Boss/Draft/Cover: `.role-sessions/Topic/@TOPIC:1-5`.
   - Topic also does not provide the explicit `date / timestamp / archive_title / archive_package` metadata block requested by Boss for this cycle.

10. **Do not publicly publish**: PASS
   - Boss, Draft, Cover, and this review all keep the boundary at preview/review/manual publish only: `Boss/BOSS-CYCLE-20260313-195347.md:17`, `Draft/@DRAFT.md:75`, `Cover/@COVER:8`, `Review/@REVIEW:6`.

## Required Rework
1. Update `.role-sessions/Topic/@TOPIC` to the unified package metadata required for this cycle:
   - `date: 2026-03-14`
   - `timestamp: 20260313-195347`
   - `archive_title: AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完`
   - `archive_package: 2026-03-14 / 20260313-195347+AI技能开始进入交付时代，真正拉开差距的不是提示词，而是你能不能把一整套流程稳定跑完 / material files`
2. Replace Topic’s current stale archive suggestion `2026-03-14 / 20260313-195347+AI工作流技能拆解 / material files` so Topic / Draft / Cover / Review all point to the same folder.
3. Add a short `viral-copy breakdown` section to `Draft/@DRAFT.md` to satisfy the explicit Draft requirement, while keeping the existing `Viral Rewrite Notes`.
4. Keep the existing honest Newrank limitation wording and the truthful note that `yhslgg-arch/url-reader` is unavailable in this environment. Do not expand that into fabricated detail.

## Final Decision
- **CONDITIONAL**
- Reason: Newrank-first sourcing honesty and rewrite quality are acceptable, but Topic archive metadata is not yet fully aligned to the required unified package, and Draft is still missing the explicitly requested short `viral-copy breakdown` block.
