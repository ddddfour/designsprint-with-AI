---
name: production-tech-analysis
description: >-
  Analyze design and prototype decisions against the production stack the team
  recorded on Day 1. Use this skill when checking whether an interaction is
  feasible, when mapping prototype components to production equivalents, or
  when the team needs to understand constraints of their chosen platforms.
---

# Production Tech Analysis

## Technology Stack

This template does not assume a language, framework, or platform. On Day 1 the team records the production stack in `docs/design-decisions/` (platforms, language, UI toolkit, and what must stay platform-specific). Read that decision before giving feasibility advice.

See `references/production-stack.md` for what to capture and which questions to ask.

## When to Use This Skill

### During Design Decisions
- "Can we do [interaction pattern] on our stack?" — Check feasibility against the recorded stack
- "How complex would [animation/transition] be?" — Estimate effort in that stack
- "Should we use a platform-native component here?" — Recommend an approach

### During Prototyping
- Map elements in the chosen prototype medium to equivalents in the chosen stack
- Identify which prototype patterns translate directly and which need rethinking
- Note implementation considerations in `prototype/production-reference/README.md`

### Design Token Mapping
Tokens live in `design-system/tokens/`. Production mapping depends on the stack. When the prototype is web-based, the prototype column is CSS custom properties, as in this example:

| Prototype (CSS) | Production |
|-----------------|------------|
| `--color-primary` | Theme color in the chosen stack |
| `--font-size-base` | Body text style in the chosen stack |
| `--spacing-md` | Spacing token in the chosen stack |
| `border-radius` | Corner radius in the chosen stack |
| Flexbox/Grid | Layout primitive in the chosen stack |

## Feasibility

Answer these against the recorded stack. Do not import constraints from a stack the team did not choose.

### Usually straightforward
- Standard UI components (buttons, inputs, lists, cards)
- Navigation patterns (tabs, drawers, stack navigation)
- Form validation and data display
- Simple animations and transitions
- Shared state management

### Often needs platform-specific or server support
Confirm each item against the chosen stack:
- Push notifications
- Camera and photo access
- Biometric authentication
- Payments
- Deep linking
- Background work

### Often more effort
- Custom gesture handling
- Complex animation
- Custom drawing
- Accessibility beyond the toolkit defaults
- Offline use with sync

## Guidance for the Sprint

- Design for the form factor in the stack decision (phone, desktop, or both)
- Prefer patterns the chosen toolkit already supports
- When in doubt, try a thin slice in the chosen prototype medium and note the mapping question
- Do not let technical constraints kill ideas while the team is diverging — note them and revisit when the team converges
