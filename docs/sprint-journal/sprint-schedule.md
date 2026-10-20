# Sprint Schedule — Quick Reference

> 10 working days · ~6h/day · 3–5 people · Co-located

## Activity Tag Legend

| Tag | Meaning |
|-----|---------|
| Physical | Whiteboard, sticky notes, paper sketches, printed materials, wall space. Use a FigJam board for the same activities when the team is remote, and as a digital copy of the wall when they are together |
| Digital | Claude Code skills, Figma MCP, FigJam, laptops, markdown files in repo |
| Group | Whole team together (3–5 people) |
| Solo | Individual quiet work |
| Pairs | 2 people collaborating |
| Solo→Group | Start alone, then come together to share |

---

## Week 1: Understand and Decide

### Day 1 — Map & Understand

| Time | Activity | Mode | Setting | What happens |
|------|----------|------|---------|-------------|
| 0:00–0:30 | Kickoff & Tool Check | Digital | Group | Verify Figma MCP auth, fetch server, walk through repo structure. Use `/tool-setup`. |
| 0:30–1:15 | Lightning Talks | Physical | Group | Each person presents 10–15 min: business goals, user insights, known issues, constraints. Capture key points on whiteboard. |
| 1:15–1:30 | *Break* | | | |
| 1:30–2:15 | User Research Synthesis | Digital | Group | Feed interview transcripts, surveys, analytics into Claude (`/user-research-analysis`). Discuss personas & journeys on screen together. |
| 2:15–3:00 | Business Context Analysis | Digital | Group | Feed strategy docs, OKRs into Claude (`/business-context-analysis`). Review goals & constraints together on screen. |
| 3:00–3:15 | *Break* | | | |
| 3:15–4:00 | Competitor Landscape | Digital | Group | Use `/competitor-analysis` with fetch MCP to pull competitor sites/apps. Build comparison matrix together. |
| 4:00–4:45 | "How Might We" Notes | Physical | Solo→Group | **Solo (15 min):** Each person writes HMW questions on sticky notes silently. **Group (30 min):** Share, cluster on wall, dot-vote top themes. |
| 4:45–5:30 | Sprint Goals & Questions | Physical | Group | At the whiteboard: define problem statement (1–2 sentences), write 3–5 testable sprint questions, vote on top HMW areas. |
| 5:30–6:00 | Day 1 Journal & Token Setup | Digital | Group | Use `/sprint-documentation` to log the day. If brand assets available, run `/design-system-extraction`. |

**Outputs:** Problem statement, sprint questions, HMW clusters, research synthesis, competitor matrix, sprint journal entry.

---

### Day 2 — Sketch & Ideate

> **Note:** Day 2 is the most physical day of the sprint. Have markers, paper, sticky dots, and wall space ready.

| Time | Activity | Mode | Setting | What happens |
|------|----------|------|---------|-------------|
| 0:00–0:30 | Recap & Inspiration | Physical + Digital | Group | Review Day 1 wall (HMWs, goals). Browse competitor references and inspiring examples on screen. |
| 0:30–1:00 | Lightning Demos | Physical | Group | Each person presents 1–2 inspiring examples from *other* products/domains (3–5 min each). Sketch key ideas on whiteboard. |
| 1:00–1:15 | *Break* | | | |
| 1:15–1:25 | Crazy 8s — Round 1 | Physical | Solo | Fold paper into 8 panels. Sketch 8 different ideas in 8 minutes (1 min each). No talking, wild ideas welcome. |
| 1:25–1:45 | Share & React | Physical | Group | Pin sketches on wall. Silent review with sticky-dot favorites, then quick group discussion of standouts. |
| 1:45–1:55 | Crazy 8s — Round 2 | Physical | Solo | Second round, building on ideas you just saw. Push further. |
| 1:55–2:15 | Share & React — Round 2 | Physical | Group | Same pin-up and discussion format. |
| 2:15–2:30 | *Break* | | | |
| 2:30–3:30 | Concept Sketches | Physical | Solo | Each person picks their best 1–2 ideas and develops them into detailed 3-panel storyboards with annotations. Paper and markers. |
| 3:30–4:30 | Concept Presentations | Physical | Group | Each person presents their concept(s), ~5 min each. Team asks questions and notes "build-on" ideas. |
| 4:30–4:45 | *Break* | | | |
| 4:45–5:30 | Idea Catalog | Digital | Group | Photograph all physical sketches. Use Claude to compile an idea catalog with descriptions and key differentiators. |
| 5:30–6:00 | Day 2 Journal | Digital | Group | Use `/sprint-documentation` to log ideation themes and catalog. |

**Outputs:** Crazy 8s sketches (photographed), 3+ concept storyboards per person, digital idea catalog, sprint journal entry.

---

### Day 3 — Decide & Storyboard

| Time | Activity | Mode | Setting | What happens |
|------|----------|------|---------|-------------|
| 0:00–0:30 | Gallery Walk | Physical | Solo | Display all concept sketches on the wall. Each person reviews silently, adds sticky-note questions and comments. |
| 0:30–1:00 | Dot Voting | Physical | Group | Each person gets 5 dots. Vote on concepts (or parts of concepts) that best address sprint goals. Discuss voting patterns. |
| 1:00–1:15 | *Break* | | | |
| 1:15–2:00 | Structured Critique | Physical + Digital | Group | For top 2–3 concepts: strengths, risks, how it answers sprint questions. Use `/production-tech-analysis` to check feasibility against the recorded production stack. |
| 2:00–2:45 | Decision & MVP Scope | Physical | Group | Team decides on direction (can combine elements). Define in/out list for MVP scope. Capture rationale. |
| 2:45–3:00 | *Break* | | | |
| 3:00–4:00 | User Flow Mapping | Physical + Digital | Group | Map primary user flow(s) on whiteboard. Use `/concept-visualization` to create a clean Mermaid diagram. Identify all screens/states. |
| 4:00–5:15 | Storyboard Creation | Physical | Group | Create an 8–12 frame storyboard of the critical path on the wall. Enough detail to guide wireframing. Everyone contributes frames. |
| 5:15–5:30 | Decision Record | Digital | Group | Use `/sprint-documentation` to write a formal decision record: what was chosen, what was rejected, and why. |
| 5:30–6:00 | Day 3 Journal | Digital | Group | Log the decision day. Capture selected concept, MVP scope, and storyboard (photograph it). |

**Outputs:** Selected concept with rationale, MVP scope (in/out), user flow diagram, 8–12 frame storyboard, decision record, sprint journal entry.

---

### Day 4 — UX Foundation: Structure

| Time | Activity | Mode | Setting | What happens |
|------|----------|------|---------|-------------|
| 0:00–0:45 | Information Architecture | Physical + Digital | Group | Define app structure on whiteboard: screen hierarchy, content grouping. Use `/concept-visualization` to create a clean IA diagram. |
| 0:45–1:30 | Navigation Patterns | Digital | Group | Decide primary navigation (tabs, drawer, etc.). Use `/production-tech-analysis` to check it against the recorded production stack. Quick accessibility check on touch targets. |
| 1:30–1:45 | *Break* | | | |
| 1:45–2:45 | UX Principles | Physical | Group | Define 3–5 UX principles at the whiteboard (e.g., "Progressive disclosure over information overload"). Derive from research, not generic best practices. |
| 2:45–3:30 | Design Direction | Digital | Group | Establish visual direction. If brand assets exist, refine tokens with `/design-system-extraction`. Review and discuss on screen. |
| 3:30–3:45 | *Break* | | | |
| 3:45–4:45 | Prototype Technology Decision | Digital | Group | Team chooses the prototype medium. The repo includes no scaffold. Document as `0001-prototype-technology.md` with `/sprint-documentation`. |
| 4:45–5:30 | Wireframe Kickoff | Physical or Digital | Solo / Pairs | Begin low-fidelity wireframes for the first 2–3 screens of the critical path. Paper sketches or digital — team's choice. |
| 5:30–6:00 | Day 4 Journal | Digital | Group | Log IA decisions, UX principles, tech decision, and wireframe progress. |

**Outputs:** IA diagram, navigation decision, UX principles (3–5), design direction, prototype tech decision record, initial wireframes, sprint journal entry.

---

### Day 5 — UX Foundation: Wireframes & Patterns

| Time | Activity | Mode | Setting | What happens |
|------|----------|------|---------|-------------|
| 0:00–0:30 | Wireframe Review | Physical + Digital | Group | Review Day 4 wireframe progress. Align on emerging patterns and consistency. |
| 0:30–1:30 | Wireframe Sprint | Physical or Digital | Solo / Pairs | Divide remaining screens among team members. Work in parallel on wireframes for all key screens in the critical flow. |
| 1:30–1:45 | *Break* | | | |
| 1:45–2:45 | Wireframe Sprint (continued) | Physical or Digital | Solo / Pairs | Complete remaining screens. Include key states: empty, loading, error, populated. |
| 2:45–3:30 | Wireframe Walkthrough | Physical + Digital | Group | Walk through the complete flow as a team. Flag gaps, inconsistencies, and missing states. |
| 3:30–3:45 | *Break* | | | |
| 3:45–4:30 | Interaction Patterns | Digital | Group | Define recurring UX patterns together: list behavior, form validation, navigation transitions, loading states. |
| 4:30–5:15 | Accessibility Foundation | Digital | Group | Use `/accessibility-review` on wireframes: touch targets (at least 44×44px), reading order, screen reader flow, contrast. |
| 5:15–5:30 | Week 1 Retrospective | Physical | Group | Quick retro at the whiteboard: What's working? What should we adjust for Week 2? |
| 5:30–6:00 | Day 5 Journal + Week 1 Summary | Digital | Group | Use `/sprint-documentation` to log Day 5 and write a Week 1 summary. |

**Outputs:** Complete wireframes for all critical screens (with states), interaction pattern guidelines, accessibility review notes, Week 1 retro notes, sprint journal entry.

---

## Week 1 Summary: Activity Mode Breakdown

| Day | Physical | Digital | Group | Solo |
|-----|----------|---------|-------|------|
| **1** — Understand | Lightning Talks, HMW Notes, Sprint Goals | Tool Check, Research Synthesis, Business Analysis, Competitor Analysis, Journal | 7 activities | 1 (HMW writing) |
| **2** — Ideate | Lightning Demos, Crazy 8s ×2, Share & React ×2, Concept Sketches, Presentations | Recap browsing, Idea Catalog, Journal | 5 activities | 3 (Crazy 8s ×2, Concept Sketches) |
| **3** — Decide | Gallery Walk, Dot Voting, Decision, Storyboard | Critique, Flow Diagram, Decision Record, Journal | 6 activities | 1 (Gallery Walk) |
| **4** — Structure | IA Mapping, UX Principles | Navigation, Design Direction, Tech Decision, Wireframe Kickoff, Journal | 6 activities | 1 (Wireframe Kickoff) |
| **5** — Wireframes | Wireframe Review, Retro | Wireframe Sprints, Walkthrough, Interaction Patterns, Accessibility, Journal | 5 activities | 2 (Wireframe Sprints) |

**Key pattern:** The sprint starts physical and group-heavy (Days 1–3), then shifts to more digital and parallel work (Days 4–5).

---

## Week 2: Concept and Specification

| Day | Focus | Key Deliverables |
|-----|-------|-----------------|
| **6** | UX Advanced (Features pt. 1) | Detailed specs per feature (all states, edge cases), design system refinement |
| **7** | UX Advanced (Features pt. 2) | Remaining features, micro-interactions, hallway test |
| **8** | Prototyping | Interactive prototype (critical flow), epic-level user stories |
| **9** | Prototyping + Polish | Prototype complete, detailed user stories, informal user tests, accessibility review |
| **10** | Stakeholder Review & Handoff | Stakeholder presentation, feedback processing, handoff package, retrospective |

> Week 2 detailed schedule will be added at the end of Week 1, adjusted based on the Week 1 retrospective.

---

## Materials Checklist (Physical)

Needed for Week 1:
- Whiteboard + markers (multiple colors)
- Sticky notes (multiple colors + sizes)
- Dot stickers for voting (5 per person per voting round)
- Plain paper (A4/letter) for Crazy 8s and concept sketches
- Thick markers/Sharpies for sketching (forces low-fidelity)
- Wall space or large table for pinning up sketches
- Camera/phone for photographing physical artifacts
- A FigJam board for remote teams, or for a digital copy of the wall
- Timer app for timeboxing (especially Crazy 8s)

---

## Handoff Package (Day 10)

- Interactive prototype
- Design system (tokens + component specs)
- User stories with acceptance criteria
- UX specifications (IA, wireframes, feature details, interaction patterns)
- Decision records with rationale
- User research synthesis
- Production mapping notes
- Accessibility review results
