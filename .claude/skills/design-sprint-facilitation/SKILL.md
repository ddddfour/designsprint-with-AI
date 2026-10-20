---
name: design-sprint-facilitation
description: >-
  Facilitate and guide UX design sprint activities across the 10-day schedule:
  Understand → Ideate → Decide → UX Foundation → UX Advanced → Prototype → Review.
  Use this skill when the team needs guidance on sprint process, phase transitions,
  activity suggestions, timeboxing, or when they want to understand what to do next
  in the sprint. This is the primary skill for sprint workflow management.
  Optimized for a small team of 3-5 people.
---

# Design Sprint Facilitation

## Sprint Structure

This is a **10-day UX design sprint** across 2 weeks (~6h/day), progressing from problem understanding to a handoff-ready prototype with user stories.

### Week 1: Understand and Decide (Problem → Solution Space)

| Day | Focus | Key Output |
|-----|-------|------------|
| 1 | Map & Understand | Problem statement, sprint goals, research synthesis |
| 2 | Sketch & Ideate | Concept sketches, idea catalog |
| 3 | Decide & Storyboard | MVP scope, selected concept, storyboard |
| 4–5 | UX Foundation | IA, wireframes, UX principles, design direction |

### Week 2: Concept and Specification

| Day | Focus | Key Output |
|-----|-------|------------|
| 6–7 | UX Advanced | Detailed feature specs, all states and edge cases |
| 8–9 | Prototyping | Interactive prototype, user stories |
| 10 | Stakeholder Review & Handoff | Feedback, complete handoff package |

See `references/sprint-phases.md` for detailed day-by-day activity schedules with timeboxes.

## How to Facilitate

### Starting a Day
1. Check `docs/sprint-journal/` for the latest entry to understand where the team left off
2. Announce the day's goal and expected outputs (see schedule above)
3. Suggest the sequence of activities with timeboxes from the reference schedule
4. Confirm the plan with the team before starting — adjust timing if needed

### During Activities
- Keep activities timeboxed — suggest warnings at halfway and 5 minutes remaining
- For a small team (3–5): ensure everyone contributes; use round-robin for ideation
- Capture outputs in the appropriate `docs/` directory
- Use `/concept-visualization` for diagrams when verbal descriptions become unclear
- Mix physical (whiteboard, sketches) and digital (Claude, Figma) modes throughout the day
- For How Might We notes, Crazy 8s, dot voting, and the storyboard, use a wall when the team is together. Use a FigJam board when the team is remote, and as a digital copy of the wall either way. FigJam is available through the Figma MCP.

### Phase Transitions
Before moving to a new phase/day, confirm:
- All key outputs for the current day are documented
- The team agrees they have enough to proceed
- Open questions are captured in the sprint journal
- Create a journal entry with `/sprint-documentation`

### When the Team is Stuck
- Suggest a quick "How Might We" reframing exercise
- Propose looking at the problem from a different user's perspective
- Take a short break, then try a different activity format
- Review gathered references with `/reference-gathering` for inspiration

### Informal Testing
Testing is woven throughout the sprint (not a separate phase):
- **Day 7:** Quick hallway test of wireframes
- **Day 9:** Informal user tests of the prototype (2–3 people, 15 min each)
- Use `/prototype-testing` to generate lightweight test scripts

## Day 1 Kickoff Checklist

The first sprint session should cover:
1. Tool verification (`/tool-setup`) — confirm Figma MCP, all participants connected
2. Sprint scope definition — what user problem are we solving?
3. Sprint schedule walkthrough — review the 10-day plan with the team
4. Brand asset integration (`/design-system-extraction`) — extract tokens if brand materials are available
5. Begin Understand activities — lightning talks, research synthesis
