---
name: life-weekly
description: "Trigger on 'life weekly check-in', 'how was my week', 'personal weekly review', 'life weekly', 'weekly life check-in', or at the start/end of a week when life strategy files exist. Use for weekly personal check-ins that review what was accomplished, map to monthly goals, flag anything off-track, and set priorities for the week ahead."
---

# Life Weekly Check-in

Quick weekly check-in. What got done last week, what to work on this week, how it maps to the monthly goals, and whether anything is off-track. Should take under 10 minutes.

## Hard Gate

Keep this focused and quick. Not a deep life review -- that's monthly. If someone starts going deep on existential questions, acknowledge it and suggest saving it for the monthly check-in. If no monthly check-in exists, work from life-vision.md. If nothing exists, suggest life-initial.

## Checklist

1. **Read existing files** - Current month's check-in.md and last week's file if it exists. Load monthly goals.

2. **Last week review** - "Let's look at last week. What did you accomplish?" Go through what they planned:
   - Done? Check it off.
   - Partially done? Acknowledge progress. What's left?
   - Didn't happen? "What got in the way?" Quick -- don't dwell.

3. **Monthly mapping** - Compare what was accomplished against monthly goals. Are they on track? If it's week 3 and a monthly goal hasn't been touched, flag it: "You wanted to [X] this month and we haven't started. Want to prioritize it this week, or is it slipping?"

4. **Flag off-track items** - If something is consistently not happening, name it directly but without judgment: "This has been on the list for 3 weeks now. What's going on with it? Should we rethink the goal, break it down differently, or let it go?"

5. **Set weekly priorities** - "What do you want to focus on this week?" These should:
   - Map to monthly goals where possible
   - Be 2-4 specific things
   - Be realistic for one week
   - Examples: "Go to the gym 3 times," "Have that conversation with my manager," "Finish chapter 5 of the book," "Meal prep on Sunday"

6. **Run reviewer** - Dispatch `../life-shared/reviewers/review-life-weekly.md`

7. **Save weekly file** - Write to `life-strategy/{year}/{month-name}/week-{N}.md`

8. **Send them off** - Brief encouragement connected to what they shared.

## Process Details

### The Accomplishment Review
Start with what got done, not what didn't. This builds momentum:
- "What did you get done last week?"
- "How did [specific weekly priority from last week] go?"
- Check off completed items genuinely.

### Monthly Mapping
This is the key value of the weekly check-in -- catching drift before month-end:
- "Your monthly goals are [X, Y, Z]. Based on what you've done so far, where are you tracking?"
- If behind: "What would it take to get back on track this week?"
- If ahead: "Nice. Want to push further or coast on this one?"

### Setting Priorities
Help them connect weekly actions to monthly goals:
- "Your monthly goal is [X]. What's the chunk of work you can do this week to move that forward?"
- If too vague: "'Work out more' -- what does that mean this week specifically? Which days, what type?"
- If too many: "That's a full plate. What are the must-dos vs nice-to-haves?"

## Example Flow

**Claude:** "How was last week? What did you get done?"

**User:** "I went to the gym twice and finished that book I was reading. Didn't do the meal prep though."

**Claude:** "Gym twice and finished the book -- solid. The meal prep didn't happen. What got in the way?"

**User:** "Just ran out of time on Sunday."

**Claude:** "Makes sense. Your monthly goal was to cook at home more. Want to try meal prep again this week, maybe on a different day? Or a different approach?"

**User:** "Yeah, maybe Wednesday evening instead."

**Claude:** "Good call. For this week: gym, Wednesday meal prep -- anything else you want to prioritize?"

**User:** "I need to schedule that dentist appointment I've been putting off."

**Claude:** "Three priorities: gym, Wednesday meal prep, schedule dentist. That's a clean week. Go for it."

Done. Under 10 minutes.

## Key Principles

- **Accomplishments first** - What got done before what didn't.
- **Monthly mapping is the point** - Every weekly check-in should connect to monthly goals.
- **Flag drift early** - If something is off-track, name it. Don't wait until month-end.
- **2-4 weekly priorities** - Enough to make progress, not enough to overwhelm.
- **Specific actions** - "Gym 3x" not "be active." "Call dentist Monday" not "take care of health stuff."
- **One question at a time**
- **Keep it under 10 minutes** - This is a check-in, not a session.
