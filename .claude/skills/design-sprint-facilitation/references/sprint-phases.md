# Sprint Schedule — Day-by-Day Activity Guide

> 10 working days, ~6h/day. Small team (3–5), co-located with whiteboard/wall space + laptops.
> Production stack: chosen by the team on Day 1 and recorded in `docs/design-decisions/`. This schedule does not assume a language or framework.

---

## Week 1: Understand and Decide (Problem → Solution Space)

### Day 1 — Map & Understand

**Goal:** Build shared understanding of the problem, users, business context, and constraints. Define sprint goals.

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:30 | **Kickoff & Tool Check** — Verify Figma MCP, all team members connected, walk through repo structure | 👥 Group · 💻 Digital | `/tool-setup` |
| 0:30–1:15 | **Lightning Talks** (10–15 min each) — Each team member shares their perspective: business goals, user insights, known UX issues, technical constraints | 👥 Group · 📋 Physical | — |
| 1:15–1:30 | Break | | |
| 1:30–2:15 | **User Research Synthesis** — Process available research data (interviews, surveys, analytics, support tickets) into personas and journey maps | 👥 Group · 💻 Digital | `/user-research-analysis` |
| 2:15–3:00 | **Business Context Analysis** — Distill strategy docs, OKRs, business model into sprint-relevant goals and constraints | 👥 Group · 💻 Digital | `/business-context-analysis` |
| 3:00–3:15 | Break | | |
| 3:15–4:00 | **Competitor Landscape** — Map direct competitors, adjacent solutions, and inspiring examples | 👥 Group · 💻 Digital | `/competitor-analysis` |
| 4:00–4:45 | **"How Might We" Notes** — Convert insights into opportunity statements; write individually, then share and cluster on wall | 👤 Solo → 👥 Group · 📋 Physical | — |
| 4:45–5:30 | **Sprint Goals & Questions** — Define problem statement, vote on top 3–5 HMW areas, write 3–5 testable sprint questions | 👥 Group · 📋 Physical | — |
| 5:30–6:00 | **Day 1 Journal & Setup** — Document the day; if brand assets available, extract initial design tokens | 👥 Group · 💻 Digital | `/sprint-documentation`, `/design-system-extraction` |

**Outputs:**
- Problem statement (1–2 sentences)
- Sprint questions (3–5 testable questions)
- HMW focus areas (3–5 prioritized)
- User research synthesis (personas, journeys) → `docs/user-research/`
- Business context summary → `docs/business-context/`
- Competitor matrix → `docs/references/`
- Sprint journal → `docs/sprint-journal/day-1-understand.md`

---

### Day 2 — Sketch & Ideate

**Goal:** Generate a wide range of possible solutions. Quantity over quality.

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:30 | **Recap & Inspiration Review** — Review Day 1 outputs, browse gathered references, look at competitor approaches | 👥 Group · 📋 Physical + 💻 Digital | `/reference-gathering` |
| 0:30–1:00 | **Lightning Demos** — Each person presents 1–2 inspiring examples from other products/domains (3–5 min each). Capture key patterns on wall. | 👥 Group · 📋 Physical | — |
| 1:00–1:15 | Break | | |
| 1:15–1:25 | **Crazy 8s Round 1** — Fold paper into 8 sections, sketch 8 ideas in 8 minutes. One idea per box, maximum 1 minute each. Wild ideas welcome. | 👤 Solo · 📋 Physical | — |
| 1:25–1:45 | **Share & React** — Pin up Crazy 8s, silent review, then quick discussion of standout ideas | 👥 Group · 📋 Physical | — |
| 1:45–1:55 | **Crazy 8s Round 2** — Another round, building on what you saw. Push into unexpected territory. | 👤 Solo · 📋 Physical | — |
| 1:55–2:15 | **Share & React Round 2** | 👥 Group · 📋 Physical | — |
| 2:15–2:30 | Break | | |
| 2:30–3:30 | **Concept Sketches** — Each person develops their best 1–2 ideas into detailed 3-panel storyboards. Annotate how it works. | 👤 Solo · 📋 Physical | — |
| 3:30–4:30 | **Concept Presentations** — Each person presents concepts (5 min each). Capture reactions and build-on ideas. | 👥 Group · 📋 Physical | `/concept-visualization` |
| 4:30–4:45 | Break | | |
| 4:45–5:30 | **Idea Catalog** — Photograph physical sketches, compile all concepts digitally with key differentiators. Create summary of each. | 👥 Group · 💻 Digital | `/concept-visualization` |
| 5:30–6:00 | **Day 2 Journal** — Document ideation session, catalog ideas, note emerging themes | 👥 Group · 💻 Digital | `/sprint-documentation` |

**Outputs:**
- Crazy 8s sketches (photographed)
- 3+ detailed concept sketches per person
- Idea catalog with descriptions and differentiators
- Sprint journal → `docs/sprint-journal/day-2-ideate.md`

---

### Day 3 — Decide & Storyboard

**Goal:** Select the strongest direction. Define MVP scope. Create a storyboard to guide design.

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:30 | **Recap & Gallery Walk** — Display all concepts. Each person reviews silently, adds sticky-note questions or comments. | 👤 Solo · 📋 Physical | — |
| 0:30–1:00 | **Dot Voting** — Each person gets 5 dots. Vote on concepts (or parts of concepts) that best address the sprint goals. Discuss patterns. | 👥 Group · 📋 Physical | — |
| 1:00–1:15 | Break | | |
| 1:15–2:00 | **Structured Critique** — For top 2–3 concepts: What's strong? What are the risks? How does it address sprint questions? Feasibility check against the recorded production stack. | 👥 Group · 📋 Physical + 💻 Digital | `/production-tech-analysis` |
| 2:00–2:45 | **Decision & MVP Scope** — Team decides on direction (can combine elements). Define what's in MVP scope vs. later. Document rationale. | 👥 Group · 📋 Physical | — |
| 2:45–3:00 | Break | | |
| 3:00–4:00 | **User Flow Mapping** — Map the primary user flow(s) for the chosen concept. Identify all screens/states needed. | 👥 Group · 📋 Physical + 💻 Digital | `/concept-visualization` |
| 4:00–5:15 | **Storyboard Creation** — Create a 8–12 frame storyboard of the critical path. Enough detail to guide wireframing. | 👥 Group · 📋 Physical | `/concept-visualization` |
| 5:15–5:30 | **Decision Record** — Document the concept decision, MVP scope, and rationale | 💻 Digital | `/sprint-documentation` |
| 5:30–6:00 | **Day 3 Journal** — Document decision day, capture what was selected and why | 💻 Digital | `/sprint-documentation` |

**Outputs:**
- Selected concept with documented rationale → `docs/design-decisions/`
- MVP scope definition (in/out list)
- User flow diagram(s)
- 8–12 frame storyboard of critical path
- Sprint journal → `docs/sprint-journal/day-3-decide.md`

---

### Days 4–5 — UX Foundation

**Goal:** Establish the UX backbone: information architecture, wireframes, UX principles, and design direction.

#### Day 4 — Information Architecture & UX Principles

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:45 | **Information Architecture** — Define app structure: navigation model, screen hierarchy, content organization. Map it visually. | 👥 Group · 📋 Physical + 💻 Digital | `/concept-visualization` |
| 0:45–1:30 | **Navigation Patterns** — Decide on primary navigation approach (tabs, drawer, etc.). Check that it fits the recorded production stack. Quick accessibility check. | 👥 Group · 💻 Digital | `/production-tech-analysis`, `/accessibility-review` |
| 1:30–1:45 | Break | | |
| 1:45–2:45 | **UX Principles Definition** — Define 3–5 UX principles that guide the product (e.g., "Progressive disclosure over information overload"). Derive from user research & sprint goals. | 👥 Group · 📋 Physical | — |
| 2:45–3:30 | **Design Direction** — Establish visual direction and feel. Review brand assets, extract/refine design tokens. | 👥 Group · 💻 Digital | `/design-system-extraction` |
| 3:30–3:45 | Break | | |
| 3:45–4:45 | **Prototype Technology Decision** — Team chooses the prototype medium. No scaffold is included in the repo. Document the decision. | 👥 Group · 💻 Digital | `/production-tech-analysis` |
| 4:45–5:30 | **Wireframe Kickoff** — Begin low-fidelity wireframes for the first 2–3 screens of the critical path. Establish layout patterns. | 👤 Solo or Pairs · 📋 Physical + 💻 Digital | `/ui-design` |
| 5:30–6:00 | **Day 4 Journal** | 💻 Digital | `/sprint-documentation` |

#### Day 5 — Wireframes & UX Patterns

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:30 | **Wireframe Review** — Review Day 4 wireframe progress, align on patterns and consistency | 👥 Group · 📋 Physical + 💻 Digital | — |
| 0:30–1:30 | **Wireframe Sprint** — Continue wireframes for all key screens in the critical flow. Work in parallel (divide screens). | 👤 Solo or Pairs · 📋 Physical + 💻 Digital | `/ui-design` |
| 1:30–1:45 | Break | | |
| 1:45–2:45 | **Wireframe Sprint (continued)** — Complete remaining key screens. Include key states (empty, error, loading). | 👤 Solo or Pairs · 📋 Physical + 💻 Digital | `/ui-design` |
| 2:45–3:30 | **Wireframe Walkthrough** — Walk through the complete flow as a team. Identify gaps, inconsistencies, missing states. | 👥 Group · 📋 Physical + 💻 Digital | — |
| 3:30–3:45 | Break | | |
| 3:45–4:30 | **Interaction Patterns** — Define recurring UX patterns: how lists behave, how forms validate, how navigation transitions work. Document as guidelines. | 👥 Group · 💻 Digital | `/concept-visualization` |
| 4:30–5:15 | **Accessibility Foundation** — Review wireframes for accessibility: touch targets, reading order, screen reader flow, contrast requirements | 👥 Group · 💻 Digital | `/accessibility-review` |
| 5:15–5:30 | **Week 1 Retrospective** — Quick retro: What's working? What to adjust for Week 2? | 👥 Group · 📋 Physical | `/sprint-retrospective` |
| 5:30–6:00 | **Day 5 Journal + Week 1 Summary** | 💻 Digital | `/sprint-documentation` |

**Outputs (Days 4–5):**
- Information architecture diagram → `docs/references/`
- UX principles document (3–5 principles) → `docs/design-decisions/`
- Wireframes for all key screens in critical flow
- Interaction pattern guidelines
- Design direction / visual approach
- Prototype technology decision → `docs/design-decisions/0001-prototype-technology.md`
- Accessibility review notes
- Sprint journal → `docs/sprint-journal/day-4-ux-foundation.md`, `day-5-ux-foundation.md`

---

## Week 2: Concept and Specification

### Days 6–7 — UX Advanced (Feature Details)

**Goal:** Go deep on feature-level UX. Detail every interaction, edge case, and state for each feature in the MVP scope.

#### Day 6 — Feature Deep-Dives (Part 1)

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:30 | **Week 2 Kickoff** — Review Week 1 artifacts: wireframes, IA, UX principles. Prioritize features to detail this week. | 👥 Group · 💻 Digital | — |
| 0:30–1:30 | **Feature Detail: Feature A** — Full UX specification: all states, edge cases, error handling, micro-interactions. Mid-fi wireframes or mockups. | 👥 Group or Pairs · 💻 Digital | `/ui-design`, `/concept-visualization` |
| 1:30–1:45 | Break | | |
| 1:45–2:45 | **Feature Detail: Feature B** — Same depth as Feature A | 👥 Group or Pairs · 💻 Digital | `/ui-design`, `/concept-visualization` |
| 2:45–3:30 | **Feature Detail: Feature C** — Same depth | 👥 Group or Pairs · 💻 Digital | `/ui-design`, `/concept-visualization` |
| 3:30–3:45 | Break | | |
| 3:45–4:45 | **Cross-Feature Consistency Review** — Check patterns, terminology, and behavior are consistent across features | 👥 Group · 💻 Digital | `/accessibility-review` |
| 4:45–5:30 | **Design System Refinement** — Update tokens and component specs based on feature work. Add new components as needed. | 💻 Digital | `/design-system-extraction` |
| 5:30–6:00 | **Day 6 Journal** | 💻 Digital | `/sprint-documentation` |

#### Day 7 — Feature Deep-Dives (Part 2)

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–1:00 | **Remaining Features** — Detail any features not yet covered. Secondary flows, settings, onboarding. | 👥 Group or Pairs · 💻 Digital | `/ui-design`, `/concept-visualization` |
| 1:00–1:15 | Break | | |
| 1:15–2:15 | **Edge Cases & Error States** — Systematically review each feature for: empty states, error states, loading states, offline behavior, permission denied, etc. | 👥 Group · 💻 Digital | `/concept-visualization` |
| 2:15–3:15 | **Micro-Interactions & Transitions** — Define key animations, transitions, and feedback patterns. Consider the conventions of the platforms recorded on Day 1. | 👥 Group · 💻 Digital | `/production-tech-analysis` |
| 3:15–3:30 | Break | | |
| 3:30–4:30 | **Full Flow Walkthrough** — Walk through the entire app flow end-to-end. Identify any remaining gaps. | 👥 Group · 💻 Digital | — |
| 4:30–5:00 | **Quick Hallway Test** — Grab someone outside the team for a quick 15-min walkthrough of the wireframes. Note confusion points. | 👥 Group · 📋 Physical | `/prototype-testing` |
| 5:00–5:30 | **Incorporate Feedback** — Adjust based on hallway test findings | 👥 Group · 💻 Digital | — |
| 5:30–6:00 | **Day 7 Journal** | 💻 Digital | `/sprint-documentation` |

**Outputs (Days 6–7):**
- Detailed UX specs for each MVP feature (all states, edge cases, interactions)
- Updated/refined wireframes at mid-fi level
- Updated design system tokens and component specs → `design-system/`
- Hallway test notes
- Sprint journal → `docs/sprint-journal/day-6-ux-advanced.md`, `day-7-ux-advanced.md`

---

### Days 8–9 — Prototyping (+ User Stories)

**Goal:** Build an interactive prototype of the critical flow. Write user stories for development handoff.

#### Day 8 — Prototype Build

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–0:30 | **Prototype Planning** — Decide which flows to make interactive. Divide screens among team members. Set up prototype environment if not done. | 👥 Group · 💻 Digital | `/tool-setup` |
| 0:30–1:30 | **Screen Build Sprint** — Build first batch of screens following the design system and wireframes. | 👤 Solo or Pairs · 💻 Digital | `/ui-design` |
| 1:30–1:45 | Break | | |
| 1:45–3:00 | **Screen Build Sprint (continued)** — Continue building screens. Focus on the primary user flow first. | 👤 Solo or Pairs · 💻 Digital | `/ui-design` |
| 3:00–3:15 | Break | | |
| 3:15–4:15 | **Interaction Wiring** — Connect screens into a navigable flow. Add key interactions (buttons, forms, selections). Use realistic data. | 👤 Solo or Pairs · 💻 Digital | `/ui-design` |
| 4:15–5:00 | **User Stories — Epic-Level** — Begin writing user stories for the features. Start with epic-level stories, break down into tasks. | 👥 Group · 💻 Digital | `/sprint-documentation` |
| 5:00–5:30 | **Internal Walkthrough** — Quick team walkthrough of prototype progress. Identify blockers for Day 9. | 👥 Group · 💻 Digital | — |
| 5:30–6:00 | **Day 8 Journal** | 💻 Digital | `/sprint-documentation` |

#### Day 9 — Prototype Polish & User Stories

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–1:00 | **Prototype Completion** — Finish remaining screens and interactions. Polish the critical flow. | 👤 Solo or Pairs · 💻 Digital | `/ui-design` |
| 1:00–1:15 | Break | | |
| 1:15–2:15 | **User Stories — Detail Level** — Break epics into detailed user stories with acceptance criteria. Map stories to prototype screens. | 👥 Group · 💻 Digital | `/sprint-documentation` |
| 2:15–3:00 | **Production Mapping Notes** — Document how prototype components map to the chosen production stack. Note platform-specific considerations. | 💻 Digital | `/production-tech-analysis` |
| 3:00–3:15 | Break | | |
| 3:15–4:00 | **Informal User Test** — Find 2–3 people outside the team for quick tests (15 min each). Follow a lightweight test script. | 👥 Group · 📋 Physical + 💻 Digital | `/prototype-testing` |
| 4:00–4:30 | **Test Debrief & Quick Fixes** — Discuss findings, make critical fixes to the prototype | 👥 Group · 💻 Digital | — |
| 4:30–5:15 | **Accessibility Review** — Full accessibility review of the prototype. Check contrast, touch targets, reading order, screen reader flow. | 💻 Digital | `/accessibility-review` |
| 5:15–5:30 | **Handoff Prep** — Begin organizing materials for Day 10 stakeholder review | 👥 Group · 💻 Digital | — |
| 5:30–6:00 | **Day 9 Journal** | 💻 Digital | `/sprint-documentation` |

**Outputs (Days 8–9):**
- Interactive prototype covering the critical user flow → `prototype/`
- User stories with acceptance criteria → `docs/` or team backlog tool
- Production mapping notes → `prototype/production-reference/`
- Informal test findings
- Accessibility review results → `docs/test-results/`
- Sprint journal → `docs/sprint-journal/day-8-prototype.md`, `day-9-prototype.md`

---

### Day 10 — Stakeholder Review & Übergabe (Handoff)

**Goal:** Present the sprint outcome to stakeholders. Package everything for the development team.

| Time | Activity | Mode | Skills |
|------|----------|------|--------|
| 0:00–1:00 | **Presentation Prep** — Prepare the stakeholder walkthrough: problem → solution → prototype demo → next steps. Rehearse. | 👥 Group · 💻 Digital | — |
| 1:00–1:15 | Break | | |
| 1:15–2:30 | **Stakeholder Review** — Present to stakeholders: Sprint goals, key decisions, prototype demo, user stories, open questions. Capture feedback. | 👥 Group + Stakeholders · 💻 Digital + 📋 Physical | — |
| 2:30–3:00 | **Feedback Processing** — Team discusses stakeholder feedback. Categorize: accepted, needs discussion, out of scope. | 👥 Group · 📋 Physical | — |
| 3:00–3:15 | Break | | |
| 3:15–4:00 | **Handoff Package Assembly** — Ensure all artifacts are organized and accessible: prototype, design system, user stories, UX specs, decision records, research synthesis | 👥 Group · 💻 Digital | `/sprint-documentation` |
| 4:00–4:45 | **Development Team Walkthrough** (if available) — Walk the dev team through the design system, prototype architecture, production mapping, and user stories | 👥 Group · 💻 Digital | `/production-tech-analysis` |
| 4:45–5:00 | Break | | |
| 5:00–5:30 | **Sprint Retrospective** — What worked? What didn't? What would we do differently? Capture action items. | 👥 Group · 📋 Physical | `/sprint-retrospective` |
| 5:30–6:00 | **Final Journal Entry & Archive** — Complete sprint documentation. Ensure everything is committed to the repo. | 💻 Digital | `/sprint-documentation` |

**Outputs (Day 10):**
- Stakeholder feedback captured and categorized
- Complete handoff package:
  - Interactive prototype
  - Design system (tokens + component specs)
  - User stories with acceptance criteria
  - UX specifications (IA, wireframes, feature details, interaction patterns)
  - Decision records with rationale
  - User research synthesis
  - Production mapping notes
  - Accessibility review results
- Sprint retrospective → `docs/sprint-journal/day-10-review.md`
- Retrospective action items

---

## Activity Legend

| Symbol | Meaning |
|--------|---------|
| 👥 Group | Whole team together |
| 👤 Solo | Individual work |
| Pairs | Two people working together |
| 📋 Physical | Whiteboard, sticky notes, paper sketches, wall space. Remote teams use a FigJam board for the same activities |
| 💻 Digital | Laptops, Claude Code, Figma, FigJam, repo |
