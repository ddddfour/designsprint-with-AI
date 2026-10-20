---
paths:
  - "prototype/**"
---

# Prototype Coding Rules

- Do not start a prototype until the medium is recorded in `docs/design-decisions/0001-prototype-technology.md`
- Build only in that medium. This repo does not include a prototype scaffold
- The prototype is a disposable facade for usability testing, not production code
- Optimize for speed of iteration and realistic appearance, not code quality or architecture
- Match the form factor recorded with the production stack (phone, desktop, or both)
- When the chosen medium uses the design system, reference tokens in `design-system/tokens/` instead of hardcoding colors, type, or spacing
- Ensure touch-friendly interaction targets (minimum 44×44px) when the product is used by touch
