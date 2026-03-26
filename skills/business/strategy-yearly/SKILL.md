---
name: strategy-yearly
description: Deep annual review of the entire strategy stack. Triggers on "yearly review", "annual planning", "year in review", "plan for next year", "annual strategy", "yearly check-in", or at the start of a new year when strategy files exist. Use for comprehensive business strategy reviews that examine vision, refresh core focus areas, and set yearly measurable outcomes.
---

# Strategy Yearly Review

This skill guides a deep annual review of your entire strategy. You'll examine whether your vision and business plan still hold, refresh your focus for the year ahead, and set concrete yearly outcomes tied to impact.

## HARD GATE

**Do NOT skip the business plan review.** Even if you want to jump straight to setting outcomes, the yearly review always starts with examining whether your vision and strategy still make sense. This is where you catch shifts in the market, learnings from last year, or fundamental pivots that need to happen.

**Do NOT create files until you approve each section.** This is a conversation, not a form. We'll build as we go, and you'll see exactly what gets saved before it's locked in.

## Pre-Work Checklist

Before we begin:

1. **Read shared references** — I'll load the file structure guide and markdown templates from `../strategy-shared/references/` to ensure consistency
2. **Load existing strategy files** — I'll read your current `strategy/business-plan.md` and any prior year outcomes files
3. **Check for completeness** — If no business plan exists yet, I'll redirect you to the strategy-initial skill first
4. **Pull previous year's outcomes** — If prior year outcomes exist, we'll review them together and celebrate what hit

## The Yearly Review Process

### 1. Previous Year Reflection (If Applicable)

If you set outcomes last year, we'll look at them together. What did you hit? What didn't land? What changed mid-year that shifted priorities? This sets context for what's ahead and acknowledges real progress.

### 2. Business Plan Review — Section by Section

We'll walk through your current business plan one section at a time. For each section, the question is simple: **Does this still feel true?**

- **Vision** — A year ago you committed to a direction. Has that destination changed? Do you still believe it?
- **Problem** — Is the core problem you're solving the same? Has your understanding deepened?
- **Solution** — How has your approach evolved? What have you learned about what actually works?
- **Market & Audience** — Have your customers or market conditions shifted?
- **Competition & Differentiation** — Are you still solving a unique problem in a unique way?
- **Business Model** — Is how you make money still aligned with your strategy?
- **Success Metrics** — Are you measuring the right things?

This is a conversation. If something needs to change, we update it. If the plan needs a major rewrite, that's fine—that's what this annual check is for.

### 3. Update and Save Business Plan

After review, I'll save any changes to your `strategy/business-plan.md` with an updated `last_reviewed` date. This becomes your reference point for the year ahead.

### 4. Core Focus for the Year

Now we design the year. Based on your refreshed business plan, what are the 3-5 things that would make the biggest difference?

I'll propose focus areas and we'll refine them together. Each focus area should:
- Be impact-driven, not a feature list
- Trace clearly back to your business plan
- Answer: "Why does this matter? What changes if we nail this?"

### 5. Run Reviewer

I'll dispatch the yearly review validator to check that your focus areas are coherent, strategic, and well-grounded in your business plan.

### 6. Save Core Focus

Once approved, your core focus goes to `strategy/{year}/core-focus.md` using the Core Focus template from `../strategy-shared/references/markdown-templates.md` (with `period: yearly` and the correct year in frontmatter). This becomes your North Star for the year.

### 7. Set Yearly Outcomes (SMART Goals)

For each core focus area, we set 1-3 measurable outcomes. For each:
- **What's the metric?** — How do you measure success?
- **What's the realistic target for 12 months?**
- **How will you know you're on track at the halfway point?**

Outcomes must be SMART: Specific, Measurable, Achievable, Relevant, Time-bound.

### 8. Save Outcomes

Your yearly outcomes go to `strategy/{year}/outcomes.md`. These are your accountability anchors.

### 9. Bridge to Quarterly Planning

Once the year is locked, I'll suggest moving to quarterly check-ins to break the year into smaller cycles. Quarterly plans build the roadmap to hit your yearly outcomes.

## Key Principles

**Reflection before planning** — Always look back before looking forward. Progress compounds, and you learn from last year's attempts.

**Celebrate progress** — Acknowledge wins first. This isn't about what you missed; it's about what you built and what comes next.

**Honest assessment** — If the business plan needs a major rewrite, good. That means you learned something. Don't force last year's strategy onto this year.

**One question at a time** — No form-filling. Real strategy requires thinking, and thinking is sequential.

**Impact-driven focus areas** — Not feature lists or task lists. "Build API" is not a focus area. "Reduce customer onboarding friction by 50%" is.

**SMART outcomes** — Outcomes without measures are wishes. Measures without targets are noise. Targets without time bounds are procrastination.

**Everything chains upward** — Yearly outcomes map to core focus areas. Core focus areas map to the business plan. Each layer answers: "Why does this matter?"

---

## Ready?

Let's begin. I'll start by reading your existing strategy files. If you're starting fresh, let me know and we'll redirect to the initial strategy setup first.
