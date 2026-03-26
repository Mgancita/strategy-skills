---
name: Strategy Initial Setup
description: "First-time business strategy setup. Triggers on 'help me plan my business', 'business plan', 'strategy setup', 'I have a business idea', 'help me figure out what to focus on', 'start my strategy', or any first-time request to build a business plan or project strategy. Use this to create the foundational Business Plan (vision, problem, solution, target user, go-to-market) and initial Core Focus areas through guided conversation. Must be used before any other strategy skill."
icon: 🎯
category: strategy
---

# Strategy Initial Setup

Your business strategy starts here. This skill walks you through building a clear, focused Business Plan—the "why" and "how" that everything else hangs from. Then you'll define your first Core Focus areas so you know what actually matters to work on.

This is a conversation, not a form. We'll go one question at a time, and I'll probe deeper when answers feel vague. Don't worry about being perfect. The goal is clarity.

## Hard Gate

**Do not skip ahead.** I won't create any files until we've worked through your Business Plan together and you've approved it. This matters because rushing to tactics (feature lists, tool choices, specific deliverables) before you're clear on your WHY and HOW is how projects drift.

---

## Checklist

- [ ] Read shared references: `./references/file-structure.md` and `./references/markdown-templates.md`
- [ ] Check if you've already created a Business Plan (if so, skip to periodic review)
- [ ] Work through Business Plan questions one at a time
- [ ] Infer your business type from context (don't ask you to classify it)
- [ ] Present Business Plan summary for approval
- [ ] Validate the plan has clear WHY and HOW (not just WHAT)
- [ ] Create strategy directory and save business-plan.md
- [ ] Walk through 3-5 Core Focus areas for your first period
- [ ] Present Core Focus and get approval
- [ ] Run reviewer: dispatch `./reviewers/review-initial.md` to validate plan and focus areas
- [ ] Save core-focus.md to the right nested path (e.g., `strategy/2026/core-focus.md`)
- [ ] Route you to the next skill based on your business type

---

## Process Flow

**Phase 1: Intake & Clarification (20-30 min)**
→ Read references → Check for existing plan → Ask Business Plan questions one at a time → Build understanding

**Phase 2: Validation (10-15 min)**
→ Show you the plan → Get approval section by section → Validate WHY and HOW are clear

**Phase 3: Core Focus (10-20 min)**
→ Identify 3-5 focus areas for your first period → Make sure they're impact-driven, not feature-driven → Get approval

**Phase 4: Handoff (2-5 min)**
→ Create files → Suggest your next skill based on your business type

---

## Business Plan Questions

Ask these **one at a time**. Each question is its own message. Listen carefully and dig deeper if the answer is vague or tactical.

### Vision
*"What's the big picture? If everything goes right, what does the world look like because of this?"*

This should feel inspiring but grounded. "More people can read books" is vision. "Build an app with a blue homepage" is not. If you're stuck, think: what problem would be solved or what opportunity would exist that doesn't today?

### Problem
*"What specific problem are you solving? Who feels this pain the most?"*

Get concrete. "People struggle with X" is better than "the market needs Y." Identify the person or group that feels this pain most acutely. If you say "everyone," I'll push back—that's a sign you haven't narrowed your focus yet.

### Solution
*"How are you solving it? Not features—the approach."*

This is strategy, not a feature list. "We're making X faster through automation" is an approach. "We're building a React app with authentication and a database" is implementation. If you jump to features, I'll redirect you. The approach is how you're different and why your solution works.

### Unique Value
*"What makes this different? Why will people choose this over alternatives?"*

What's your unfair advantage? Unique insight? Better distribution? Stronger team? Don't say "nobody else is doing this"—people are almost always doing something similar. Focus on why your version will win.

### Target User
*"Who specifically is this for? Paint me a picture of your ideal user or customer."*

Name them. Describe their day. What are they already using? Where do they spend time? If you say "everyone," we're not done yet. If you say "engineers," we need to narrow: "senior software engineers at Series B startups who own infrastructure." Specificity matters because it shapes everything downstream.

### Go-to-Market
*"How will you reach them? Where do they already spend time?"*

Don't say "marketing" or "social media." Be specific. "We'll find them on Hacker News because they hang out there, and we'll get early customers through direct outreach to 50 CTO profiles on LinkedIn." That's real. This is how you reach your specific users, not where you wish they were.

### Personal Fit
*"Why you? What makes you the right person or team for this?"*

What unique knowledge, experience, passion, or network do you bring? If you've solved this problem before, if you know the industry, if you have a massive unfair advantage in reaching your users—that matters. This isn't ego; it's about realistic odds of success.

---

## Core Focus (First Period)

Once your Business Plan is done, we'll define **3–5 focus areas** for your first planning period. The length of that period depends on your business type:

- **Startup:** 6–12 months
- **Solo business:** 6–12 months
- **Corporation or established business:** 1 year
- **Time-bound project (school, client work):** Project duration

Each focus area should answer: *Why does this matter? What does success look like?* They should be impact-driven ("understand customer pain points deeply," "validate that users need this"), not feature-driven ("build feature X").

If you list something like "implement Stripe," I'll reframe it: "Ensure we can reliably process payments so we don't leave money on the table." The outcome, not the tool, is the focus.

---

## Key Principles

**One question at a time.** Never throw five questions at you. Conversation is better than interrogation.

**WHY > HOW > WHAT.** Strategic clarity (why does this exist?) beats tactical details (what tool do we use?). If you drift into tactics, I'll redirect.

**Flag specificity mismatches.** "Build a React app with Stripe and auth" is too detailed for this stage. "Build a product that makes X easy" is right. We'll get to implementation details later.

**Infer, don't classify.** I'll figure out whether you're running a startup, a solo business, a school project, or something else based on what you tell me. I won't ask you to pick a label.

**Impact over features.** Every focus area should trace back to something in your Business Plan. "Talk to 20 customers to validate our main assumption" is a focus area. "Build the dashboard" is not.

**Validate alignment.** Each core focus area must matter to your Business Plan. If it doesn't, it's either a distraction or missing context.

---

## Routing (After Handoff)

Once we're done, I'll recommend your next skill based on what you've told me:

**Early stage (idea phase, no revenue, no team yet):**
→ "Come back in a month for your first monthly check-in" or "Let's do a quarterly check-in when you're ready"

**Solo business with some traction:**
→ "Let's do a monthly check-in every first week of the month to track outcomes"

**Established business or larger org:**
→ "Let's do a yearly planning session to set your annual focus and outcomes" (use business-yearly)
→ Or if mid-year: "Let's do a quarterly check-in to set outcomes for the current quarter"

**Time-bound project:**
→ "Let's do monthly check-ins for the duration of the project"

---

## Let's Begin

Ready? I'll start by checking your workspace to see if you've already built a Business Plan. If not, we'll start with the Vision question.
