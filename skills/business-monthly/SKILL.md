---
name: business-monthly
description: Trigger on "monthly check-in", "monthly planning", "plan for this month", "what should I focus on this month", "monthly review", "month ahead", or at the start of a new month when strategy files exist. Use for monthly strategy check-ins that review quarterly focus, set monthly outcomes, and break outcomes into high-level project tasks.
---

# Strategy Monthly Check-in

## Purpose

Monthly check-in that reviews the quarterly Core Focus and Outcomes, sets monthly Outcomes, and breaks those outcomes into high-level project tasks. This is where strategy becomes actionable work.

## Hard Gate

Do NOT jump straight to tasks. Monthly outcomes come first, tasks come from outcomes. If there are no quarterly files (core-focus.md and outcomes.md for the current quarter), suggest running business-quarterly first, or business-initial if nothing exists.

## Checklist

1. **Read shared references** - Load `./references/file-structure.md` and `./references/markdown-templates.md`
2. **Read existing files** - business-plan.md, current quarter's core-focus.md and outcomes.md, and the previous month's files if they exist
   - If no quarterly files exist, stop and redirect to business-quarterly or business-initial
3. **Previous month review** - if prior month's outcomes.md and tasks.md exist:
   - Review what was targeted
   - Check off completed items
   - Ask about anything that stalled: "This didn't get done — is it still important, should it carry forward, or should we drop it?"
4. **Quarterly pace check** - Compare progress to date against quarterly outcomes
   - If in month 2 of quarter and only 20% through a quarterly outcome, flag it
   - Ask: "Are we on track, or do we need to adjust?"
5. **Monthly Outcomes** - For each relevant quarterly focus area, set 1–3 monthly outcomes
   - These should be achievable in ~30 days
   - Each should represent meaningful progress toward the quarterly target
   - Walk through one at a time with the user
6. **Present and approve Outcomes** - Show the full set; get buy-in before moving forward
7. **Run reviewer** - Dispatch `./reviewers/review-monthly.md` to sense-check outcomes against quarterly goals
8. **Save monthly outcomes.md** - Save to `strategy/{year}/Q{N}/{month-name}/outcomes.md`
9. **Monthly Tasks/Projects** - Break each outcome into 2–5 high-level project tasks or milestones
   - Not daily to-dos; these are "chunks of work" that might take a few days to a week
   - Examples: "Interview 5 potential users", "Draft landing page copy", "Set up analytics tracking"
10. **Present and approve Tasks** - Show the full list; get buy-in
11. **Save monthly tasks.md** - Save to `strategy/{year}/Q{N}/{month-name}/tasks.md`
12. **Route to weekly** - Suggest a weekly check-in to break the month into weekly work

## Process Details

### Setting Monthly Outcomes

Start with the quarterly focus and outcomes as your anchor:

- "Your quarterly focus is [X] with an outcome of [Y by end of quarter]. What would meaningful progress look like this month?"
- If they say something vague ("make progress on it"): "Can you put a number or specific milestone on that? What would you be able to point to at the end of the month?"
- If they say something too ambitious for one month: "That sounds like a quarter's worth of work. What's the subset that fits in a month?"

Go one outcome at a time. Don't batch them.

### Breaking Outcomes into Tasks

Help them think in projects, not to-dos:

- "To achieve [monthly outcome], what are the main chunks of work? Think projects or milestones, not individual tasks."
- Flag granular tasks: "Writing the email copy" is weekly/daily level. "Launch email campaign" is monthly level.
- Flag unmapped tasks: "How does this connect to your monthly outcomes?"

## Key Principles

- **Outcomes before tasks** - Resist jumping straight to doing
- **Monthly outcomes are stepping stones** - They should clearly add up to quarterly targets
- **Tasks are projects, not to-dos** - Save granular work for weekly/daily check-ins
- **Pace tracking continues** - Flag drift from quarterly goals early
- **Carry forward decisions** - Don't silently move incomplete items; make a conscious choice about whether they stay, evolve, or drop
- **One question at a time** - Keep the conversation focused
- **Everything chains upward** - Monthly outcomes → Quarterly outcomes → Annual vision

## File Structure

Save outputs using the nested directory structure from file-structure.md:
- `strategy/{year}/Q{N}/{month-name}/outcomes.md` - The monthly outcomes with supporting context
- `strategy/{year}/Q{N}/{month-name}/tasks.md` - The high-level monthly projects and milestones

Month directories use lowercase full names (e.g., `january`, `february`). Use the current date to determine the correct quarter and month path.
