---
name: user-research-analysis
description: >-
  Analyze user research data and extract structured insights including user
  personas, journey maps, jobs to be done (JTBD), pain points, and needs. Use
  this skill when the team provides user research inputs (interview transcripts,
  survey data, analytics, observation notes) and needs them synthesized into
  actionable design inputs. Primarily used during the Understand phase.
---

# User Research Analysis

## Input Formats

This skill can process:
- Interview transcripts or summary notes
- Survey results (raw data or summaries)
- Analytics data (usage patterns, funnels, retention)
- Observation notes (field studies, usability tests)
- Support tickets or user feedback
- App store reviews

## Analysis Frameworks

### Personas
Create user personas from research data. Use the template at `assets/templates/persona-template.md`.
- Identify 2-4 distinct user archetypes from the data
- Ground each persona in real data points and quotes
- Focus on goals, behaviors, and context of use (not demographics for their own sake)
- Save to `docs/user-research/persona-[name].md`

### Journey Maps
Map the user's experience across touchpoints. Use the template at `assets/templates/journey-map-template.md`.
- Identify the key phases of the user's interaction
- Capture actions, thoughts, emotions, and pain points at each phase
- Highlight opportunity areas where design can improve the experience
- Save to `docs/user-research/journey-[scenario].md`

### Jobs to Be Done (JTBD)
Extract JTBD statements. Use the template at `assets/templates/jtbd-template.md`.
- Format: "When [situation], I want to [motivation], so I can [expected outcome]"
- Identify both functional and emotional jobs
- Prioritize by frequency and importance from the research data
- Save to `docs/user-research/jobs-to-be-done.md`

## Process

1. **Receive input** - Read the provided research materials
2. **Identify patterns** - Look for recurring themes, pain points, and behaviors across multiple data sources
3. **Synthesize** - Create structured outputs using the appropriate framework
4. **Support with evidence** - Include key quotes, data points, and source references
5. **Highlight tensions** - Note any contradictions between user needs and business goals (cross-reference with `docs/business-context/`)
6. **Save outputs** - Write to `docs/user-research/` with descriptive file names
