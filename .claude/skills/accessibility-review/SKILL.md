---
name: accessibility-review
description: >-
  Review designs and prototypes for accessibility compliance including WCAG 2.2
  guidelines, color contrast, touch target sizes, screen reader compatibility,
  and inclusive design patterns. Use this skill when reviewing UI designs or
  prototype code for accessibility, or when the team needs guidance on making
  designs more inclusive. Relevant from Decide & Storyboard through Prototyping and informal testing.
---

# Accessibility Review

## Quick Checklist

### Color & Contrast
- [ ] Text contrast ratio meets WCAG AA: 4.5:1 for normal text, 3:1 for large text
- [ ] Non-text elements (icons, borders, focus indicators) have 3:1 contrast ratio
- [ ] Information is not conveyed by color alone (use icons, patterns, or text labels too)
- [ ] Design works in both light and dark contexts

### Touch & Interaction
- [ ] Touch targets are at least 44×44px, or 48×48px where the recorded platform asks for it
- [ ] Adequate spacing between touch targets (minimum 8dp gap)
- [ ] Interactive elements have visible focus/pressed states
- [ ] No interactions require precise gestures (pinch, multi-finger) as the only option

### Content & Structure
- [ ] Headings follow a logical hierarchy (h1 > h2 > h3)
- [ ] Form inputs have visible labels (not just placeholder text)
- [ ] Error messages are clear, specific, and associated with the relevant field
- [ ] Loading states and progress are communicated
- [ ] Images have descriptive alt text

### Navigation
- [ ] Screen reader can navigate all content in logical order
- [ ] Current location/state is clearly indicated
- [ ] Back navigation is always available
- [ ] Modal dialogs trap focus appropriately

### Motion & Timing
- [ ] Animations respect `prefers-reduced-motion`
- [ ] No content auto-advances without user control
- [ ] Timeout durations are generous or adjustable

## Reviewing the Prototype

Review the medium recorded in `docs/design-decisions/0001-prototype-technology.md`. Two common cases:

### When the Prototype Is HTML/CSS
1. Check semantic HTML: headings, landmarks (`<main>`, `<nav>`, `<header>`), lists, buttons vs. links
2. Verify `alt` attributes on images
3. Check `aria-label` on interactive elements without visible text
4. Test keyboard navigation (tab order, enter/space activation)
5. Check color contrast with design token values

### For Figma Designs
1. Review layer naming for screen reader compatibility
2. Check text contrast against background colors
3. Verify touch target sizes on interactive elements
4. Confirm visual hierarchy matches reading order

## Common Issues

| Issue | Impact | Fix |
|-------|--------|-----|
| Placeholder-only labels | Screen readers skip them, they disappear on input | Add persistent visible labels |
| Icon-only buttons | Unclear purpose without visual context | Add `aria-label` or visible text |
| Low contrast decorative elements | Users with low vision miss important UI structure | Ensure 3:1 minimum for meaningful borders/dividers |
| Small touch targets | Users with motor impairments can't tap accurately | Minimum 48dp, with adequate spacing |
| Missing error association | Screen readers don't connect error to field | Use `aria-describedby` or proper HTML form structure |

## Production Accessibility Notes

Check accessibility against the platform APIs of the stack recorded on Day 1 (web, native, or both). Review at least:

- Names and roles exposed to assistive technology
- Focus order and keyboard access, where the platform has a keyboard
- Touch target size, where the platform is touched
- Contrast of text and meaningful non-text UI

Note anything that will differ between the prototype and production in `prototype/production-reference/README.md`.

## Output

Save accessibility findings in `docs/design-decisions/` as a decision record, or include in `docs/test-results/` if found during testing.
