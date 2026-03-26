# Strategy File Structure

All strategy files live in a `strategy/` directory within the user's workspace. Files are organized by time period in a nested hierarchy.

## Directory Layout

```
strategy/
  business-plan.md                    # The foundational document - vision, problem, solution, GTM
  {YYYY}/                             # Year directory (e.g., 2026/)
    core-focus.md                     # 3-5 yearly focus areas
    outcomes.md                       # Yearly SMART goals mapped to focus areas
    Q{N}/                             # Quarter directory (e.g., Q1/)
      core-focus.md                   # Quarterly focus areas (subset of yearly)
      outcomes.md                     # Quarterly SMART goals mapped to quarterly focus
      {month-name}/                   # Month directory (e.g., january/)
        outcomes.md                   # Monthly outcomes mapped to quarterly
        tasks.md                      # Monthly high-level project tasks
        W{N}/                         # Week directory (e.g., W1/)
          tasks.md                    # Weekly task chunks + daily task sections
```

## File Discovery

When a skill needs to find upstream files, it should search in this order:

1. **Business Plan:** `strategy/business-plan.md`
2. **Current Year Focus:** `strategy/{current-year}/core-focus.md`
3. **Current Year Outcomes:** `strategy/{current-year}/outcomes.md`
4. **Current Quarter Focus:** `strategy/{current-year}/Q{current-quarter}/core-focus.md`
5. **Current Quarter Outcomes:** `strategy/{current-year}/Q{current-quarter}/outcomes.md`
6. **Current Month Outcomes:** `strategy/{current-year}/Q{current-quarter}/{current-month}/outcomes.md`
7. **Current Month Tasks:** `strategy/{current-year}/Q{current-quarter}/{current-month}/tasks.md`
8. **Current Week Tasks:** `strategy/{current-year}/Q{current-quarter}/{current-month}/W{current-week}/tasks.md`

Use the current date to determine which quarter (Q1 = Jan-Mar, Q2 = Apr-Jun, Q3 = Jul-Sep, Q4 = Oct-Nov), month, and week-of-month to look for.

## Creating New Files

When creating a file for a new period:
- Create all necessary parent directories
- If the previous period's file exists, read it first to carry over any incomplete items
- Add a YAML frontmatter block with metadata (see markdown-templates.md)
- Link to the upstream document in the frontmatter

## File Naming

- Use lowercase for month names: `january`, `february`, etc.
- Week numbers are within the month (W1 through W5), not ISO week numbers
- Quarter numbers are 1-4
