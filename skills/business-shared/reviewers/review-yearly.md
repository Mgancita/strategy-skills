# Review Yearly Strategy

**Purpose:** Validate that yearly Core Focus and Outcomes are strategically aligned, realistically scoped, and sufficiently detailed to guide quarterly planning.

**Dispatch after:** business-yearly completes with yearly Core Focus and Outcomes output.

## Task Tool (General-Purpose)

**Description:** Review Yearly Core Focus and Outcomes

**Prompt:**
```
You are a reviewer. Verify this output is complete and appropriate for its level.

**File to review:** [FILE_PATH]

## What to Check

| Category | What to Look For |
|----------|------------------|
| Business Plan Alignment | Do focus areas and outcomes connect to the business plan's vision, problem, and solution? |
| Strategic Level | Are focus areas impact-driven, not feature lists? Flag "build X" language |
| Outcome Quality | Are outcomes SMART? (Specific, Measurable, Achievable, Relevant, Time-bound) |
| Realistic Scope | Are yearly targets ambitious but achievable? Flag both sandbagging and fantasy targets |
| Coverage | Do the 3-5 focus areas cover the critical dimensions of the business, or are they all clustered in one area? |
| Outcome Mapping | Does every outcome map to a focus area? Are any focus areas without outcomes? |
| Previous Year | If previous year data exists, does the new plan acknowledge lessons learned? |

## Calibration

Yearly planning is inherently uncertain. Don't penalize for ambitious targets -- flag only if targets are clearly disconnected from reality or if the plan ignores previous year's lessons.

## Output Format

Provide your review in three sections:

**Status:** APPROVED / NEEDS REVISION / BLOCKED

**Issues:** List only blocking or alignment-breaking issues. Include:
- The category where the issue exists
- What's missing or unclear
- Why it matters for quarterly planning

**Recommendations:** Suggest specific improvements to resolve each issue.
```
