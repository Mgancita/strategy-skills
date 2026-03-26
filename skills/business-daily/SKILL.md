---
name: business-daily
description: Triggers on morning/start-of-day planning requests like "daily check-in", "what should I do today", "plan my day", "today's tasks", "morning check-in", "start my day", or similar. Runs a quick 2-5 minute daily standup that reviews weekly tasks, sets 2-5 specific actions for today, and checks off yesterday's completions.
---

# Strategy Daily Check-in

Quick daily standup. Review yesterday, propose today's tasks, confirm, move on. Under 5 minutes.

## HARD GATE

Before starting, check:
- **Weekly tasks exist?** Look for `tasks.md` in the current week's strategy folder. If not found, check for a monthly `tasks.md`.
- **No weekly file?** Suggest running `business-weekly` first to set up the week.
- **No strategy files at all?** Suggest `business-initial` to bootstrap the system.

If the user is asking strategic questions (e.g., "Should I pivot my whole approach?" or "What's my actual goal?"), acknowledge and redirect: *"That's a great question, but it's bigger than the daily standup. Let's save that for your weekly check-in."*

## CHECKLIST

1. **Read the weekly plan** - Pull up the current week's `tasks.md`. Scan for yesterday's section (if it exists) and today's planned tasks.

2. **Yesterday's review** (30 seconds) - If yesterday's section exists: *"Yesterday you planned to [X, Y, Z]. How did those go?"* Ask for quick status: done, partially done, or didn't get to it. Check off completed items in the file. Don't dwell—just acknowledge and move forward.

3. **Propose today's tasks** (1 minute) - Based on the weekly plan and any carryover: *"Here's what I'd suggest for today based on your weekly plan: (1) [Task], (2) [Task], (3) [Task]. Does that look right, or do you want to adjust?"* Lead with a proposal. The user can modify or swap. Aim for 2-5 tasks.

4. **Quick gut check** (30 seconds) - *"Anything else on your plate today—meetings, appointments, energy constraints?"* Adjust the task list if needed. Keep it brief.

5. **Run reviewer** - Dispatch `./reviewers/review-daily.md` to quick-check task selection
6. **Update the file** - Modify the weekly `tasks.md` directly. Add or update today's section with the agreed tasks. Don't create a separate daily file.

7. **Send them off** (1 sentence) - Brief encouragement + one-sentence reminder of how today connects to the bigger picture.

## PROCESS FLOW

The daily check-in is a quick review, not a deep dive. Structure:

- **Lead with a proposal, not an open-ended question**
- **Get confirmation or adjustments in one exchange**
- **Be done in 2-4 total exchanges**

### Example:

> **Claude:** "Morning! Yesterday you planned to draft the proposal and send 3 outreach emails. How did those go?"
>
> **User:** "Got the proposal done, only sent 1 email."
>
> **Claude:** "Nice—proposal is done! I'll mark that complete. For today, based on your weekly plan, I'd suggest: (1) Send the remaining 2 outreach emails, (2) Review the analytics dashboard mockup, (3) Prep for tomorrow's user interview. Sound good?"
>
> **User:** "Yeah, but I have a 2-hour meeting in the afternoon so maybe just the emails and the mockup review."
>
> **Claude:** "Got it—focused day. I've updated your plan. The emails and mockup review are key to hitting your beta launch milestone. Go get 'em."

That's it. 4 exchanges, under 3 minutes.

## KEY PRINCIPLES

- **Speed above all** - This is a standup, not a planning meeting.
- **Propose, don't ask** - Lead with specific task suggestions from the weekly plan.
- **2-5 tasks per day** - More than 5 is unrealistic; fewer than 2 suggests tasks are too large.
- **Check off completions** - The small dopamine hit of checking boxes matters for momentum.
- **Connect to the bigger picture** - One brief reminder (max one sentence) of why today's tasks matter to the weekly or monthly goal.
- **Don't go deep** - If the user raises strategic questions, redirect to the weekly check-in.
- **Carry forward gracefully** - Incomplete tasks aren't failures; they're data to rescope.
- **Update the actual file** - Modify the weekly `tasks.md` directly; don't create a separate daily file.

## Notes

This is the most tactical and fastest check-in in the strategy system. Unlike other skills that explore one question at a time, this one should be structured and directive: propose, confirm, move on. The goal is momentum and clarity, not perfect planning.

If the user wants to spend 20 minutes rethinking their week or quarterly goals, that's a sign they need the weekly or monthly check-in instead. Stay focused on *today*.

This is the deepest level of the strategy system. There's no "next skill" after daily -- the cycle loops back. Their next scheduled check-in is the weekly review at the start of the next week.
