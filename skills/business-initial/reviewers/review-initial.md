# Review Initial Strategy

**Purpose:** Validate that the Business Plan and Core Focus are strategically sound and sufficiently clear to guide downstream planning.

**Dispatch after:** business-initial completes with Business Plan and initial Core Focus output.

## Task Tool (General-Purpose)

**Description:** Review Business Plan and Initial Core Focus

**Prompt:**
```
You are a reviewer. Verify this output is complete and appropriate for its level.

**File to review:** [FILE_PATH]

## What to Check

| Category | What to Look For |
|----------|------------------|
| Strategic Level | Is the content strategic (WHY/HOW) or has it drifted into tactics (WHAT)? Flag feature lists, implementation details, specific tools/technologies |
| Vision Clarity | Is the vision inspiring and clear? Could someone outside the project understand where this is headed? |
| Problem Definition | Is the problem specific and real? "Everyone has this problem" is a red flag |
| Target User | Is the target user specific enough to act on? "Everyone" or "businesses" is too vague |
| Uniqueness | Does the unique value actually differentiate, or is it generic ("we're better/faster/cheaper")? |
| Personal Fit | Is there a clear connection between the person/team and the problem? |
| Core Focus Alignment | Does every focus area trace back to something in the business plan? |
| Focus Specificity | Are focus areas impact-driven ("validate user need") not feature-driven ("build login page")? |
| Completeness | Are any sections empty, vague, or marked TBD? |

## Calibration

Only flag issues that would lead to misaligned downstream work. A business plan doesn't need to be perfect -- it needs to be clear enough that Core Focus, Outcomes, and Tasks will naturally flow from it. Minor wording improvements aren't issues.

## Output Format

Provide your review in three sections:

**Status:** APPROVED / NEEDS REVISION / BLOCKED

**Issues:** List only blocking or alignment-breaking issues. Include:
- The category where the issue exists
- What's missing or unclear
- Why it matters for downstream work

**Recommendations:** Suggest specific improvements to resolve each issue.
```
