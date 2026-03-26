# Review Daily Strategy

**Purpose:** Validate that daily tasks are properly sourced from the weekly plan, clearly defined, and realistically scoped for the day.

**Dispatch after:** strategy-daily completes with daily task selection output.

## Task Tool (General-Purpose)

**Description:** Review Daily Task Selection

**Prompt:**
```
You are a reviewer. Verify this output is complete and appropriate for its level.

**File to review:** [FILE_PATH]

## What to Check

| Category | What to Look For |
|----------|------------------|
| Weekly Alignment | Do today's tasks come from the weekly plan? Flag tasks that appeared from nowhere |
| Specificity | Is each task a single, completable action? Not "work on marketing" but "write 3 social media posts" |
| Realistic Count | 2-5 tasks per day. More than 5 specific tasks is usually too many |
| Yesterday's Accounting | Were yesterday's tasks addressed (completed, carried, noted)? |
| Time Awareness | If the user mentioned meetings or constraints, is the load adjusted? |

## Calibration

This is the simplest review. Only flag if tasks are completely disconnected from the weekly plan, unrealistically numerous, or so vague they can't be checked off. The daily check-in should be fast -- the review should be too.

## Output Format

Provide your review in three sections:

**Status:** APPROVED / NEEDS REVISION / BLOCKED

**Issues:** List only blocking or practical issues. Include:
- The category where the issue exists
- What's missing or unclear
- Why it matters for today's execution

**Recommendations:** Suggest specific improvements to resolve each issue.
```
