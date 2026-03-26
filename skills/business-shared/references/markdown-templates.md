# Markdown Templates

All strategy files use rich markdown with YAML frontmatter for metadata and chaining.

## Business Plan Template

```markdown
---
type: business-plan
created: YYYY-MM-DD
last_reviewed: YYYY-MM-DD
business_type: startup | solo | corporation | project | other
review_cadence: yearly (with quarterly cleanup)
---

# Business Plan: {Company/Project Name}

## Vision
> One or two sentences describing the future state this company/project is working toward.

## Problem
What specific problem exists in the world that this addresses? Who feels this pain?

## Solution
How does this solve the problem? Keep this high-level -- focus on the approach, not feature lists.

## Unique Value
What makes this different from alternatives? Why will this win?

## Target User
Who specifically is this for? What do they look like, where do they spend time, what do they care about?

## Go-to-Market Strategy
How will this reach the target user? What channels, partnerships, or approaches?

## Personal Fit
Why is this the right person/team to build this? What unique knowledge, experience, or passion do they bring?

## Notes & Open Questions
Anything unresolved, assumptions to validate, or areas needing more thought.
```

## Core Focus Template

```markdown
---
type: core-focus
period: yearly | quarterly
year: YYYY
quarter: Q{N} (if quarterly)
created: YYYY-MM-DD
parent: ../core-focus.md (if quarterly, points to yearly)
status: active | completed | archived
---

# Core Focus: {Period Description}

> These are the 3-5 areas that matter most right now. Everything else is a distraction.

## Focus Areas

### 1. {Focus Area Name}
**Why this matters:** {Connection to business plan / upstream focus}
**What success looks like:** {Qualitative description of the desired state}
**Status:** Not Started | In Progress | On Track | At Risk | Complete

### 2. {Focus Area Name}
...

## What We're NOT Focusing On
Things that might seem important but are intentionally deferred. This prevents scope creep.

- {Thing} -- why it's deferred
- {Thing} -- why it's deferred
```

## Outcomes Template

```markdown
---
type: outcomes
period: yearly | quarterly | monthly
year: YYYY
quarter: Q{N} (if quarterly or monthly)
month: {month-name} (if monthly)
created: YYYY-MM-DD
parent: ../outcomes.md (points to parent period outcomes)
focus_ref: ./core-focus.md (points to same-period core focus)
status: active | completed | archived
---

# Outcomes: {Period Description}

## Progress Summary
| Outcome | Target | Current | Status |
|---------|--------|---------|--------|
| {name}  | {goal} | {now}   | On Track / At Risk / Behind / Complete |

## Outcomes

### Focus Area: {Name from Core Focus}

#### Outcome 1: {Specific measurable goal}
- **Metric:** {What you're measuring}
- **Target:** {Specific number or state}
- **Deadline:** {Date}
- **Current:** {Where things stand now}
- **Status:** Not Started | In Progress | On Track | At Risk | Behind | Complete
- **Notes:** {Any context}

#### Outcome 2: {Specific measurable goal}
...

### Focus Area: {Next Name from Core Focus}
...

## Flagged Issues
- [ ] {Any outcomes that are off-track relative to the parent period}
```

## Tasks Template (Monthly)

```markdown
---
type: tasks
period: monthly
year: YYYY
quarter: Q{N}
month: {month-name}
created: YYYY-MM-DD
parent_outcomes: ./outcomes.md
status: active | completed | archived
---

# Tasks: {Month YYYY}

## Monthly Projects

### Project: {Name} (maps to Outcome: {outcome name})
> Brief description of what this project accomplishes

- [ ] {High-level task or milestone}
- [ ] {High-level task or milestone}
- [ ] {High-level task or milestone}

### Project: {Name} (maps to Outcome: {outcome name})
...

## Carry-Over from Last Month
- [ ] {Incomplete items from previous month}

## Completed
- [x] {Tasks finished this month}
```

## Tasks Template (Weekly)

```markdown
---
type: tasks
period: weekly
year: YYYY
quarter: Q{N}
month: {month-name}
week: W{N}
created: YYYY-MM-DD
parent_tasks: ../tasks.md
status: active | completed | archived
---

# Tasks: {Month} Week {N}

## Weekly Goals
> What does "a good week" look like? 2-3 sentences max.

## Task Breakdown

### {Day Name}, {Date}
- [ ] {Specific task} (maps to: {monthly project})
- [ ] {Specific task}
- [ ] {Specific task}

### {Day Name}, {Date}
- [ ] {Specific task}
- [ ] {Specific task}

...

## Carry-Over from Last Week
- [ ] {Incomplete items}

## Completed This Week
- [x] {Done tasks}

## Blockers / Notes
- {Anything preventing progress}
```

## Status Tags Reference

Use these consistently across all files:

| Tag | Meaning |
|-----|---------|
| Not Started | Haven't begun work |
| In Progress | Actively working on it |
| On Track | Progressing as expected toward deadline |
| At Risk | May not hit target without intervention |
| Behind | Will not hit target at current pace |
| Complete | Done and verified |
| Deferred | Intentionally moved to a later period |
| Dropped | Removed from scope entirely |
