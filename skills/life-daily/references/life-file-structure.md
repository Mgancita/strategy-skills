# Life Strategy File Structure

A simpler, flatter structure for personal life planning. No quarterly nesting—just yearly and monthly.

## Directory Layout

```
life-strategy/
  life-vision.md                    # Foundational document: what matters across life areas
  {YYYY}/
    {month-name}/
      check-in.md                   # Monthly reflection and intentions
      week-{N}.md                   # Weekly priorities and reflections (1-4 per month)
```

## File Discovery Order

When working with life strategy files, follow this discovery sequence:

1. **Start with `life-vision.md`** — Always. This is the north star. It establishes what matters to the person across different life areas, their time horizons, and themes.

2. **Then look for the current year folder** (e.g., `2026/`) — If it doesn't exist, it will be created when the first monthly check-in is created.

3. **Find the current month folder** (e.g., `march/`) — Months use lowercase names to keep paths clean. If it doesn't exist, create it when starting a monthly check-in.

4. **Read the monthly `check-in.md`** — This provides context for what the person is focusing on this month and their intentions.

5. **Check weekly files if needed** — `week-1.md`, `week-2.md`, etc., provide finer-grained tracking within the month.

## Creation Guidelines

### When Creating Life Vision
- Only create once, at the start of a life strategy practice.
- Update it infrequently (annually or when major life changes occur).
- Treat it as a reflective document, not a planning document.

### When Creating Monthly Check-ins
- Create once per month, ideally early in the month or at month-end reflection.
- Use lowercase month names in the folder path (e.g., `january/`, `february/`).
- The check-in is a moment to reflect on the previous month and set loose intentions for the next.

### When Creating Weekly Files
- Create as needed within a month—not mandatory every week.
- Use the format `week-1.md`, `week-2.md`, etc.
- Keep weekly check-ins very light—a few lines per section.

## Naming Conventions

- **Folders**: Year as `{YYYY}`, months as lowercase (`january`, `february`, ..., `december`)
- **Files**: Simple lowercase names (`check-in.md`, `week-1.md`, `week-2.md`)
- **Separators**: Use hyphens in week numbers (`week-1`, `week-2`, not `week_1`)

## Key Principles

- **Simplicity over completeness**: You don't need to check in weekly if monthly feels right.
- **Personal, not corporate**: Avoid treating this like a business strategy with KPIs.
- **Reflective, not prescriptive**: Life strategy is about understanding what matters, not optimizing it.
