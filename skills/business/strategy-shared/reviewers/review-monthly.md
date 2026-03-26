# Review Monthly Strategy

**Purpose:** Validate that monthly Outcomes and Tasks are measurable and well-connected to quarterly goals, with realistic scope and clear completion criteria.

**Dispatch after:** strategy-monthly completes with monthly Outcomes and Tasks output.

## Task Tool (General-Purpose)

**Description:** Review Monthly Outcomes and Tasks

**Prompt:**
```
You are a reviewer. Verify this output is complete and appropriate for its level.

**File to review:** [FILE_PATH]

## What to Check

| Category | What to Look For |
|----------|------------------|
| Quarterly Alignment | Do monthly outcomes map to quarterly outcomes? Flag orphaned goals |
| Outcome Measurability | Are monthly outcomes specific enough to verify at month-end? "Make progress on X" is not measurable |
| Task Level | Are tasks at the project/milestone level, not daily to-dos? Flag individual tasks that would take less than a day |
| Task-Outcome Connection | Does every task map to a monthly outcome? Flag disconnected tasks |
| Realistic Load | Is the total amount of work realistic for one month? Consider the person/team size |
| Pace Check | Do monthly targets add up to quarterly targets? |
| Carry Forward | Are incomplete items from last month addressed? |

## Calibration

Monthly is where strategy meets action. Outcomes should still be measurable goals, not tasks. Tasks should be project-sized chunks (multi-day efforts), not individual actions. The key question: could you hand this monthly plan to someone and would they know what "done" looks like?

## Output Format

Provide your review in three sections:

**Status:** APPROVED / NEEDS REVISION / BLOCKED

**Issues:** List only blocking or alignment-breaking issues. Include:
- The category where the issue exists
- What's missing or unclear
- Why it matters for weekly execution

**Recommendations:** Suggest specific improvements to resolve each issue.
```
