---
name: sprint-documentation
description: >-
  Create and maintain sprint documentation including daily journal entries,
  decision logs, meeting notes, and sprint artifacts. Use this skill when the
  team needs to document sprint activities, log decisions, capture insights, or
  create any structured documentation artifact during the sprint. Should be
  invoked at the end of each sprint session or when significant decisions are
  made.
---

# Sprint Documentation

## Documentation Structure

| Directory | Content | Naming |
|-----------|---------|--------|
| `docs/sprint-journal/` | Daily activity logs | `day-N-phase.md` |
| `docs/design-decisions/` | Decision records | `NNNN-title.md` |
| `docs/user-research/` | Research synthesis | Descriptive names |
| `docs/business-context/` | Business analysis | Descriptive names |
| `docs/test-results/` | Usability findings | `session-N.md`, `analysis.md` |
| `docs/references/` | External references | Descriptive names |

## Daily Sprint Journal

Create a journal entry at the end of each sprint session. Use the template from `assets/templates/daily-journal-template.md`.

**File:** `docs/sprint-journal/day-N-phase.md` (e.g., `day-1-understand.md`)

**When to create:** End of each working session, or when transitioning between phases mid-day.

## Decision Records

Create a decision record whenever the team makes a significant design or process decision. Use the template from `assets/templates/decision-log-template.md`.

**File:** `docs/design-decisions/NNNN-title.md` (e.g., `0001-prototype-technology.md`)

**When to create:**
- Technology or tool choices
- Design direction selections (end of Decide & Storyboard)
- Scope changes
- User flow decisions
- Any choice the team might want to revisit or explain later

## Best Practices

- Document decisions as they happen, not retroactively
- Include the "why" - rationale is more valuable than the "what"
- Cross-reference related documents (link to research that informed a decision)
- Keep entries concise - aim for clarity over comprehensiveness
- Use quotes from team discussions to capture reasoning
- Tag decisions with the sprint phase they occurred in
