# Review Weekly Strategy

**Purpose:** Validate that weekly tasks are concrete, properly connected to monthly goals, and realistically scoped for the week ahead.

**Dispatch after:** strategy-weekly completes with weekly task breakdown output.

## Task Tool (General-Purpose)

**Description:** Review Weekly Task Breakdown

**Prompt:**
```
You are a reviewer. Verify this output is complete and appropriate for its level.

**File to review:** [FILE_PATH]

## What to Check

| Category | What to Look For |
|----------|------------------|
| Monthly Alignment | Does every weekly task connect to a monthly project? Flag random tasks |
| Task Concreteness | Are tasks specific deliverables ("draft the proposal") not vague activities ("work on the proposal")? |
| Realistic Capacity | 3-7 meaningful tasks per week is typical. More than 10 is a red flag |
| Completion Tracking | Are last week's items properly marked (complete/carried/dropped)? |
| Daily Distribution | If days are assigned, is work spread realistically? Not everything on Monday? |
| Blocker Visibility | Are known blockers surfaced? |

## Calibration

Weekly planning is practical, not strategic. Tasks should be clear enough that you know when they're done. Don't flag strategic concerns here -- that's for higher-level reviews. Focus on: is this a realistic, clear, actionable week?

## Output Format

Provide your review in three sections:

**Status:** APPROVED / NEEDS REVISION / BLOCKED

**Issues:** List only blocking or practical issues. Include:
- The category where the issue exists
- What's missing or unclear
- Why it matters for daily execution

**Recommendations:** Suggest specific improvements to resolve each issue.
```
