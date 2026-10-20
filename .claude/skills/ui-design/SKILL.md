---
name: ui-design
description: >-
  Create UI in the prototype medium the team recorded on Day 4. Generate screen
  layouts, component implementations, and interactive prototypes that follow the
  established design system. Use this skill during Prototyping when the team
  needs to create or iterate on UI screens, or translate wireframes and sketches
  into a testable prototype.
---

# UI Design

## Before Building

Read `docs/design-decisions/0001-prototype-technology.md`. Build only in the medium recorded there. This repo does not include a prototype scaffold, and this skill must not invent one.

If that decision does not exist yet, stop and help the team make it. Common media are a Figma prototype, a small coded prototype, or both. The choice belongs to the team.

## Process

### Creating a New Screen
1. Check the storyboard from Decide & Storyboard (in `docs/sprint-journal/`)
2. Use the design tokens in `design-system/tokens/` when the medium can consume them
3. Build the screen in the chosen medium. Do not hardcode colors, type, or spacing when tokens exist
4. Keep the screen on the critical user flow
5. Document the screen in `docs/design-decisions/` when it represents a significant design choice

### Iterating on Existing Screens
1. Understand what needs to change and why
2. Make the change in the chosen medium, preserving token usage
3. Walk the flow end to end
4. Note the iteration in the sprint journal

### When the Medium Is Figma
1. Ensure Figma MCP is authenticated (`/mcp` > figma)
2. Reference specific frames by their node URL
3. Build and adjust frames in the team file
4. Use Figma Make when the team wants live UI turned into editable frames

### When the Medium Is Code
1. Agree the language and location with the team, then create only those files
2. If the prototype is web-based, map tokens to the styling approach the team chose
3. Keep interaction logic only as rich as the test flow needs

## Design Principles for the Prototype

- **Match the target form factor:** Use the platforms recorded on Day 1.
- **Touch-friendly:** Minimum 44×44px touch targets when the product is used by touch.
- **Token-driven:** Every color, font size, and spacing value comes from tokens when the medium supports them.
- **Realistic content:** Use realistic text and data, not Lorem Ipsum, where possible.
- **Flow-complete:** Finish the critical user flow before polishing individual screens.

## Production Mapping

As you build, note the equivalent in the chosen production stack in `prototype/production-reference/README.md`. This helps the development team translate the validated prototype into production code.
