# Production Stack

The production technology is chosen by the team. Record it on Day 1, before design critique, so later feasibility checks have something to check against.

Suggested decision record: `docs/design-decisions/0002-production-stack.md`.

## What to capture

- Platforms (web, iOS, Android, desktop, or a combination)
- Language and UI toolkit
- What is shared across platforms, and what stays platform-specific
- Constraints that should shape design (offline, authentication, payments, accessibility APIs)
- How design tokens will map into that stack

## Feasibility questions

When a design idea comes up, answer these against the recorded stack:

- Can this interaction be built with the standard components of that stack?
- Does it need platform-specific code?
- What is the rough effort, and does that change the sprint scope?

Write the answers in `prototype/production-reference/README.md` as the prototype takes shape.

## Often platform-specific

These frequently need native or server support. Confirm them against the chosen stack, and do not treat the list as a ban:

- Push notifications
- Camera and photo access
- Biometric authentication
- Payments
- Deep linking
- Background work

Do not let these kill ideas during ideation. Note them and revisit when the team converges.
