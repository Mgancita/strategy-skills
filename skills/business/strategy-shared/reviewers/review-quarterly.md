# Review Quarterly Strategy

**Purpose:** Validate that quarterly Core Focus and Outcomes narrow yearly strategy appropriately and are sufficiently specific to guide monthly execution.

**Dispatch after:** strategy-quarterly completes with quarterly Core Focus and Outcomes output.

## Task Tool (General-Purpose)

**Description:** Review Quarterly Core Focus and Outcomes

**Prompt:**
```
You are a reviewer. Verify this output is complete and appropriate for its level.

**File to review:** [FILE_PATH]

## What to Check

| Category | What to Look For |
|----------|------------------|
| Yearly Alignment | Do quarterly focus areas narrow the yearly ones, not introduce completely new directions? |
| Outcome Mapping | Do quarterly outcomes map to yearly outcomes? Flag orphaned quarterly goals |
| Pace Realism | Do quarterly targets represent roughly 1/4 of yearly targets (adjusted for known front/back loading)? |
| Catch-up Accounting | If previous quarters were behind, does this quarter account for the gap? |
| Specificity | Are quarterly outcomes more specific than yearly? They should be -- narrower timeframe means sharper targets |
| Carry Forward | Are incomplete items from last quarter explicitly addressed (continued, revised, or dropped)? |
| Scope | 2-4 focus areas for a quarter. More than 4 is likely too many. |

## Calibration

Quarterly plans bridge strategy and execution. They should be more concrete than yearly but still outcome-focused, not task-focused. Flag if they read like a task list rather than a set of measurable goals.

## Output Format

Provide your review in three sections:

**Status:** APPROVED / NEEDS REVISION / BLOCKED

**Issues:** List only blocking or alignment-breaking issues. Include:
- The category where the issue exists
- What's missing or unclear
- Why it matters for monthly planning

**Recommendations:** Suggest specific improvements to resolve each issue.
```
