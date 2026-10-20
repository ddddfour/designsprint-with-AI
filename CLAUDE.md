# UX Design Sprint Workspace

AI-assisted design sprint for a small team (3-5 people). This repo is a technology-neutral workspace for sprint activities, documentation, and prototyping. The production stack is chosen by the team and recorded on Day 1 — this template does not assume a language, framework, or platform.

## Directory Structure

- `.claude/skills/` - 14 Claude skills for sprint activities (see below)
- `.claude/rules/` - Behavioral rules for sprint phases and prototype coding
- `docs/` - All sprint documentation (journal, research, decisions, test results)
- `design-system/` - Design tokens (W3C format) and component specs
- `prototype/` - Empty until Day 4, when the team chooses a prototype medium. No scaffold is included
- `prototype/production-reference/` - Notes mapping the prototype to the chosen production stack

## MCP Servers

- **figma** - Figma remote MCP server. Provides access to design files, variable/token extraction, code generation from frames, Figma Make (live UI to Figma frames), and FigJam boards for workshop activities. Each user must authenticate once via `/mcp` > figma > Authenticate.
- **fetch** - Retrieves web content for reference gathering (docs, APIs, brand guidelines).

## Sprint Schedule & Skills

10-day sprint across 2 weeks (~6h/day). See `design-sprint-facilitation` skill for detailed day-by-day schedule.

| Days | Phase | Skills |
|------|-------|--------|
| **1** | Map & Understand | `design-sprint-facilitation`, `reference-gathering`, `user-research-analysis`, `business-context-analysis`, `competitor-analysis` |
| **2** | Sketch & Ideate | `design-sprint-facilitation`, `concept-visualization`, `reference-gathering` |
| **3** | Decide & Storyboard | `design-sprint-facilitation`, `concept-visualization`, `production-tech-analysis` |
| **4–5** | UX Foundation | `ui-design`, `concept-visualization`, `design-system-extraction`, `accessibility-review`, `production-tech-analysis` |
| **6–7** | UX Advanced | `ui-design`, `concept-visualization`, `design-system-extraction`, `accessibility-review` |
| **8–9** | Prototyping + User Stories | `ui-design`, `production-tech-analysis`, `prototype-testing`, `sprint-documentation` |
| **10** | Stakeholder Review & Handoff | `sprint-retrospective`, `sprint-documentation` |
| *Throughout* | | `sprint-documentation`, `tool-setup` |

## Conventions

- Design tokens: `.tokens.json` files in `design-system/tokens/` using W3C Design Tokens format
- Sprint journal: `docs/sprint-journal/day-N-phase.md` (e.g., `day-1-understand.md`, `day-4-ux-foundation.md`)
- Design decisions: `docs/design-decisions/NNNN-title.md` (e.g., `0001-prototype-technology.md`)
- All documentation is Markdown

## Day 1 Setup Tasks

IMPORTANT: These decisions are made collaboratively on sprint Day 1, not pre-baked:
1. **Tool verification** - Use `/tool-setup` to verify all MCP connections and Figma authentication
2. **Sprint scope definition** - What user problem are we solving? Define sprint goals.
3. **Brand asset integration** - Use `/design-system-extraction` to extract tokens from provided brand references (Figma files, PDFs, guidelines)
4. **Production stack** - Record platforms, language, and UI toolkit in `docs/design-decisions/`. Do this before design critique so feasibility checks have something to check against.
5. **Prototype medium** - On Day 4, the team chooses how to prototype. Do not assume a medium. Document the choice in `docs/design-decisions/0001-prototype-technology.md`
