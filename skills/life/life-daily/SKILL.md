---
name: life-daily
description: "Trigger on 'life daily check-in', 'personal daily check-in', 'life daily', 'daily life check-in', or similar daily personal planning requests when life strategy files exist. Runs a quick 2-minute logistic check-in: review today's intention and work through the TODO list."
---

# Life Daily Check-in

Purely logistic. Review the weekly priorities, pick what to work on today, and move on. Under 2 minutes.

## Hard Gate

This is NOT a reflection session. No mood checks, no gratitude prompts, no deep conversation. Just: what are you working on today? If someone needs to talk through something deeper, redirect to weekly or monthly.

If no weekly file exists, check for monthly goals. If nothing exists at all, suggest life-initial.

## Flow (2-3 exchanges max)

1. **Read the weekly plan** - Pull up this week's file if it exists. Scan for priorities and any notes from yesterday.

2. **Propose today's focus** - Based on the weekly plan and what's already done:
   - "Based on your weekly plan, here's what I'd suggest for today: [1-2 specific items]. Sound right?"
   - Lead with a proposal, not an open-ended question.
   - If they already mapped things to days during the weekly check-in, follow that.

3. **Adjust if needed** - If they have conflicts, meetings, or low energy, trim the list. One meaningful thing is fine.

4. **Update the file** - If a weekly file exists, note today's focus in it. Don't create a separate daily file.

5. **Send them off** - One sentence. Keep it brief.

## Example

> **Claude:** "Morning. Based on your weekly plan, today looks like: gym after work and scheduling that dentist appointment. Sound right?"
>
> **User:** "Yeah, but I'll skip the gym today. Long day ahead."
>
> **Claude:** "Got it. Dentist appointment it is. That's been on the list a while -- good to knock it out."

Done. 3 exchanges. Under 2 minutes.

## Key Principles

- **Logistic only** - What are you doing today? That's it.
- **Propose, don't ask** - Lead with specific suggestions from the weekly plan.
- **1-3 items per day** - One is fine. Three is plenty.
- **No mood checks** - Not the purpose of this check-in.
- **No gratitude prompts** - Save that for journaling.
- **Brief** - 2-3 exchanges max.
- **Update the weekly file** - Don't create separate daily files.
- **Redirect deep conversations** - If they want to rethink goals or process feelings, that's for weekly or monthly.

## Output

Modify the weekly `tasks` file if it exists. Don't create a separate daily file. This check-in is about action, not documentation.
