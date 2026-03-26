---
name: business-quarterly
description: Quarterly strategy check-in triggered by "quarterly review", "quarterly check-in", "quarterly planning", "Q1/Q2/Q3/Q4 planning", "quarter review", "90-day plan", or at the start of a new quarter when strategy files exist. Use this for quarterly strategy check-ins that review the business plan for shifts, update focus areas for the quarter, set quarterly outcomes, and flag pace issues against yearly goals.
---

# Strategy Quarterly Check-In

## Purpose
Review the business plan for major shifts, refine yearly Core Focus into quarterly focus, set SMART quarterly Outcomes mapped to yearly ones, and flag if quarterly pace drifts from yearly targets.

## HARD GATE
- Do NOT skip the business plan check. Even if quick, always ask "has anything fundamentally changed?"
- Do NOT create files until the user explicitly approves the quarterly Core Focus and Outcomes.

## Checklist

### 1. Read Shared References
- Load `./references/file-structure.md` and `./references/markdown-templates.md`
- Understand the file conventions and naming patterns.

### 2. Read Existing Files
- Load the business-plan.md
- Load the current year's core-focus.md and outcomes.md
- Load the previous quarter's files if they exist

If no business-plan.md exists, redirect to business-initial.
If no yearly files exist, suggest business-yearly first.

### 3. Previous Quarter Review
If a prior quarter exists:
- Present a progress report on outcomes from last quarter
- Calculate percentage completion for each outcome
- Identify outcomes that were missed; ask why
- Decide: carry forward incomplete items that still matter, revise them, or drop them
- Include carried-forward items in the quarterly plan

### 4. Quick Business Plan Check
Ask: "Since last quarter, has anything fundamentally shifted in your market, your understanding of the problem, or your approach?"

Keep this to 1-2 follow-up questions max unless something major changed. If significant shifts emerge, flag that a full yearly strategy review might be warranted first.

### 5. Update business-plan.md
Update the `last_reviewed` date to today at minimum. Apply any shifts identified in step 4.

### 6. Quarterly Core Focus
Take the yearly Core Focus areas and sharpen them for this quarter.

Ask, one at a time:
- "Of your yearly focus areas, which 2-4 are most critical THIS quarter?"
- For each selected yearly focus: "What's the quarterly version of this? Get more specific."

Each quarterly focus should be a sharpened, more specific version of a yearly focus—not a new area.

### 7. Present and Approve Quarterly Core Focus
Show the refined quarterly focus areas to the user for approval before proceeding.

### 8. Run Reviewer
Dispatch `./reviewers/review-quarterly.md` with the quarterly focus areas for quality check.

### 9. Save Quarterly Core Focus
Save to `strategy/{year}/Q{N}/core-focus.md` with the user's approved quarterly focus areas.

### 10. Quarterly Outcomes
For each quarterly focus area, set SMART goals:
- Outcomes should map to yearly outcomes
- Targets should represent roughly 1/4 of the yearly target (adjust for carry-forward, catch-up, or intentional front/back-loading)
- Be explicit about the quarterly target, success metric, and how it connects to yearly progress

### 11. Pace Check
Compare quarterly outcome targets against yearly targets.

Flag if:
- The quarterly targets don't mathematically add up to the yearly target
- Previous quarters were behind, and this quarter doesn't account for the gap

Example: Yearly goal is 100 customers. Q1 target: 25, actual: 15. Q2-Q4 must cover 85 (≈28 per quarter). Flag: "You're 10 behind from Q1. Should we adjust Q2 to 35 to catch up, spread the gap across remaining quarters, or revise the yearly target?"

### 12. Present and Approve Outcomes
Show the quarterly Outcomes with pace check findings to the user for approval.

### 13. Save Quarterly Outcomes
Save to `strategy/{year}/Q{N}/outcomes.md` with the user's approved quarterly outcomes.

### 14. Route to Monthly
Suggest scheduling a monthly check-in to break the quarter into monthly execution milestones.

---

## Key Principles

**Fast business plan check:** This is not a full yearly review—just a "has anything changed?" If yes, dig deeper. If no, move on.

**Quarterly focus narrows yearly focus:** Refine, don't reinvent. Quarterly focus should be a sharper version of existing yearly focus areas.

**Pace tracking is critical:** The whole point of quarterly review is to catch drift early and decide whether to catch up, spread the gap, or revise targets.

**Carry forward honestly:** Incomplete items from last quarter deserve a real decision. Don't ghost them—continue, revise, or drop.

**One question at a time:** Guide the user through the process step by step. Avoid overwhelming multi-part questions.

**Everything chains upward:** Quarterly outcomes map to yearly outcomes. Quarterly focus maps to yearly focus. Business plan anchors both. Consistency matters.
