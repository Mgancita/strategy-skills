---
name: business-weekly
description: Triggers on "weekly check-in", "weekly planning", "plan my week", "what should I do this week", "weekly review", "week ahead", "start of week", or on Mondays/Sundays when strategy files exist. Use this for weekly strategy check-ins that review monthly tasks, break them into weekly work chunks, check off last week's completions, and flag blockers.
---

# Strategy Weekly Check-in

## Purpose
Weekly check-in that reviews the monthly tasks and outcomes, breaks monthly projects into concrete weekly work chunks, checks off completed items from last week, and flags blockers or scope issues. This is where projects become specific deliverables.

## Hard Gate
Do NOT skip the review of last week. Checking off completions and acknowledging progress is important for momentum. If no monthly files exist, suggest running business-monthly first.

## Checklist

1. **Read shared references** - Load `../business-shared/references/file-structure.md` and `../business-shared/references/markdown-templates.md`
2. **Read existing files** - Load current month's outcomes.md and tasks.md, plus last week's tasks.md if it exists. If no monthly files, redirect to business-monthly
3. **Last week review** - Go through each task from the previous week. For each: is it done, partially done, or not started? Check off completed items. For incomplete items: "This didn't get done. What happened? Should it carry forward, get revised, or get dropped?"
4. **Monthly pace check** - Based on which week of the month we're in, are we on track for monthly outcomes? If it's week 3 and only 25% through a monthly outcome, flag it
5. **Weekly goals** - Ask: "What would make this a good week? In 2-3 sentences, what do you want to be true by Friday?" This is the qualitative gut-check before diving into specific tasks
6. **Weekly task breakdown** - Take the monthly projects and break them into this week's specific work. For each active monthly project: "What specifically can you accomplish on [project] this week?" These should be concrete deliverables or actions, not vague "work on X"
7. **Daily distribution (optional)** - Ask: "Want to roughly map these to days, or keep it as a weekly pool?" Some people find this helpful, others don't
8. **Present and approve the week** - Review what we've planned together
9. **Run reviewer** - Dispatch `../business-shared/reviewers/review-weekly.md`
10. **Save weekly tasks.md** - Write to `strategy/{year}/Q{N}/{month}/W{N}/tasks.md`
11. **Mention daily check-ins** - Let them know they can do quick daily check-ins to pick tasks for each day

## Process Details

### Last Week Review
"Let's start by looking at what you aimed for last week. [Read tasks.md from previous week] For each of these, was it completed, partially completed, or not started? Let's check off what's done and talk through what didn't happen."

### Monthly Pace Check
"It's [day] of [month], which is roughly week [N]. Looking at your monthly outcomes, where are we tracking? Are we on pace, ahead, or falling behind?"

### Weekly Goals
"Before we get into the task list, help me understand the shape of the week. What would make this a good week? In 2-3 sentences, what do you want to be true by Friday?"

### Task Breakdown Conversation
For each active monthly project:
- "Your monthly project is [X]. Last week you [accomplished Y or didn't start]. What's the next chunk of work you can finish this week?"
- If too many tasks: "That's a lot for one week. Which of these are must-dos vs nice-to-haves?"
- If too vague: "'Work on the landing page' -- can you be more specific? What part? What does done look like?"
- If too granular: "'Send 3 emails' sounds like a daily task. What's the bigger thing these emails are part of?"

### Daily Distribution (Optional)
"Let's loosely map these across the week. [Read their calendar/commitments if they share them] What days work best for what?"
- Spread work realistically -- don't front-load everything to Monday
- Account for meetings and energy levels
- Leave buffer -- don't fill every day to capacity

## Key Principles

- **Review before plan** - Always look at last week first. Progress recognition builds momentum
- **Concrete deliverables** - "Draft the proposal" not "work on the proposal". Each task should have a clear done-state
- **Realistic capacity** - A good week has 3-5 meaningful tasks, not 20. Quality over quantity
- **Blockers matter** - If something is stuck, surface it and decide what to do. Don't let blockers hide
- **Monthly alignment** - Every weekly task should connect to a monthly project. Avoid random tasks
- **Daily distribution is optional** - Don't force it if the user prefers working from a weekly pool
- **One question at a time** - Let them think and respond before moving forward
- **Keep it focused** - Aim for 10-15 minutes of conversation, not an hour. This is a check-in, not a deep dive

## Output Format

Save the weekly tasks to `strategy/{year}/Q{N}/{month}/W{N}/tasks.md` with:
- Week number and date range
- Connection to monthly projects
- Each task with clear deliverable and owner
- Any blockers or decisions to revisit
- Optional: daily assignments if they chose that
