---
name: life-monthly
description: "Trigger on 'life monthly check-in', 'how's my life going', 'personal monthly review', 'life check-in', 'monthly life review', or at the start of a month when life strategy files exist. Use for monthly personal life check-ins that celebrate wins, update progress on goals, and set 2-4 realistic goals for the coming month."
---

# Life Monthly Check-in

Monthly personal check-in. Celebrate what went well, update what's been done, check in on existing TODOs, and set 2-4 realistic goals for the coming month. This should feel like catching up with a friend who keeps you accountable without being annoying about it.

## Hard Gate

If no `life-vision.md` exists, suggest running `life-initial` first. Without knowing what they care about, there's nothing to check in against. Do NOT create files until the person approves the summary.

## Checklist

1. **Read existing files** - Load `../life-shared/references/life-file-structure.md` and `../life-shared/references/life-templates.md`. Read `life-strategy/life-vision.md` and last month's check-in if it exists.

2. **Celebrate wins first** - Start here, always. "Before we look at what's next, what went well this month? What are you proud of, even if it's small?" Genuinely acknowledge what they share. Connect it to their goals if relevant: "You said you wanted to cook more at home, and you did it 3 times a week. That's real progress."

3. **Review last month's goals** - If a previous check-in exists, go through each goal one at a time:
   - Done? Check it off. Celebrate.
   - Partially done? Acknowledge progress. Ask what happened.
   - Not started? No judgment. "What got in the way?" Then decide: carry forward, revise, or drop.

4. **Update the TODO list** - Based on the review, update what's still active. Some items may need to be revised ("I set 'gym 4x/week' but 2x is more realistic"). Some may be done. Some may not matter anymore.

5. **Check in on life-vision goals** - Quick alignment: "Looking at your bigger goals, how are you feeling about progress? Anything that needs adjusting?" This isn't a deep review -- just a pulse check against the vision document.

6. **Set 2-4 goals for next month** - These should be:
   - Realistic and achievable in 30 days
   - Connected to their life vision or current priorities
   - Specific enough to know if they're done at month's end
   - Not overwhelming. 2-4 is the range. If they want more, push back: "That's a lot. Which of these matter most?"

7. **Present and approve** - Show the full picture: completed items, carried items, new goals. Get buy-in.

8. **Run reviewer** - Dispatch `../life-shared/reviewers/review-life-monthly.md`

9. **Save monthly file** - Write to `life-strategy/{year}/{month-name}/check-in.md`

10. **Mention weekly check-ins** - Let them know they can do weekly check-ins to track momentum through the month.

## Process Details

### Celebrating Wins
Don't rush past this. People tend to skip to what they didn't do. Redirect: "Hold on, before we get to what's next -- you actually [did the thing]. That matters." Even small wins count: "You said you'd call your parents more, and you did it twice. That's twice more than zero."

### Setting Monthly Goals
Help them be specific but don't turn it into a business exercise. The conversation should flow naturally:

- If vague ("be more active"): "What does that look like for you? Walking, gym, sports? How often feels realistic?"
- If too many goals: "I love the ambition, but 6 goals in a month is a lot. If you had to pick 3, which would make the biggest difference?"
- If not connected to vision: "How does this connect to what you said matters? I just want to make sure we're building toward something." If it's a new priority, that's fine -- update the vision.

### Handling Missed Goals
When something didn't happen, be curious, not judgmental:
- "What got in the way?"
- "Is this still important to you, or has something shifted?"
- "Want to carry it forward, change the target, or let it go?"

Dropping goals is fine. Life changes. What matters is the decision is conscious.

## Key Principles

- **Wins first** - Always celebrate before planning. This builds momentum.
- **Update, don't just add** - Review existing TODOs before creating new ones. Clear the decks.
- **2-4 goals max** - Enough to make progress, not so many that nothing gets done.
- **Specific and realistic** - "Read 2 books" not "read more." "Save $500" not "save money."
- **Conscious carry-forward** - Don't silently move missed items. Decide: keep, revise, or drop.
- **One question at a time** - Give them space.
- **Warm but honest** - If something keeps not happening month after month, gently name it: "This is the third month in a row this has been on the list. What's really going on?"

## File Output

Save to `life-strategy/{year}/{month-name}/check-in.md` using the template from `../life-shared/references/life-templates.md`.
