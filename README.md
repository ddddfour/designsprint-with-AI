# AI-assisted Design Sprint

AI-assisted design sprint workspace for a small team (3-5 people), powered by Claude Code. The template is technology-neutral: record the production stack on Day 1, and choose the prototype medium on Day 4. No prototype scaffold is included.

## Getting Started

### Prerequisites

- [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) installed
- Node.js (for MCP server dependencies)
- A Figma account with Dev or Full seat (for Figma MCP)

### First-Time Setup

1. Clone this repo and open a terminal in the project directory
2. Run `claude` to start Claude Code
3. Run `/mcp` and authenticate with Figma (select figma > Authenticate)
4. Verify connections: `/mcp` should show `figma: connected` and `fetch: connected`

### Day 1 Kickoff

Use `/design-sprint-facilitation` to start. The Day 1 checklist covers:
1. Tool verification (`/tool-setup`)
2. Sprint scope and schedule
3. Production stack (platforms, language, UI toolkit — document in `docs/design-decisions/`)
4. Brand asset integration (`/design-system-extraction`)
5. Prototype medium, decided on Day 4 with no preset scaffold (document in `docs/design-decisions/0001-prototype-technology.md`)

## Sprint Phases

| Days | Phase | Key Skills |
|------|-------|------------|
| **1** | Map & Understand | `/design-sprint-facilitation`, `/reference-gathering`, `/user-research-analysis`, `/business-context-analysis`, `/competitor-analysis` |
| **2** | Sketch & Ideate | `/design-sprint-facilitation`, `/concept-visualization`, `/reference-gathering` |
| **3** | Decide & Storyboard | `/design-sprint-facilitation`, `/concept-visualization`, `/production-tech-analysis` |
| **4–5** | UX Foundation | `/ui-design`, `/concept-visualization`, `/design-system-extraction`, `/accessibility-review`, `/production-tech-analysis` |
| **6–7** | UX Advanced | `/ui-design`, `/concept-visualization`, `/design-system-extraction`, `/accessibility-review` |
| **8–9** | Prototyping + User Stories | `/ui-design`, `/production-tech-analysis`, `/prototype-testing`, `/sprint-documentation` |
| **10** | Stakeholder Review & Handoff | `/sprint-retrospective`, `/sprint-documentation` |

Use `/sprint-documentation` throughout to maintain the sprint journal and decision log. Use `/sprint-retrospective` at the end.

## Directory Structure

```
design-sprint/
├── CLAUDE.md                    # Project context for Claude Code
├── .mcp.json                    # MCP server configuration
├── .claude/
│   ├── rules/                   # Sprint behavior rules
│   └── skills/                  # 14 Claude skills
├── docs/
│   ├── sprint-journal/          # Daily activity logs
│   ├── user-research/           # Personas, journeys, JTBD
│   ├── business-context/        # Strategy summaries
│   ├── design-decisions/        # Decision records
│   ├── test-results/            # Usability findings
│   └── references/              # External references
├── design-system/
│   ├── tokens/                  # W3C Design Tokens (.tokens.json)
│   └── components/              # Component documentation
└── prototype/                   # Empty until the Day 4 medium decision
    └── production-reference/    # Prototype-to-production mapping notes
```

## Available Skills

| Skill | Description |
|-------|-------------|
| `/design-sprint-facilitation` | Guide sprint process across all phases |
| `/reference-gathering` | Fetch and catalog external references |
| `/tool-setup` | Configure MCP connections |
| `/sprint-documentation` | Create journal entries and decision logs |
| `/user-research-analysis` | Synthesize research into personas, journeys, JTBD |
| `/business-context-analysis` | Distill strategy docs into sprint context |
| `/competitor-analysis` | Structured competitor comparison |
| `/production-tech-analysis` | Feasibility guidance against the chosen production stack |
| `/design-system-extraction` | Extract brand tokens from references |
| `/ui-design` | Build UI in the prototype medium chosen on Day 4 |
| `/concept-visualization` | Diagrams, models, and visual explanations |
| `/accessibility-review` | WCAG compliance and inclusive design review |
| `/prototype-testing` | Test scripts, feedback capture, analysis |
| `/sprint-retrospective` | Team reflection and process improvement |

## MCP Servers

| Server | Purpose | Setup |
|--------|---------|-------|
| **figma** | Design files, token extraction, Figma Make, FigJam boards | Pre-configured. Auth via `/mcp` |
| **fetch** | Web content retrieval | Pre-configured. No auth needed |
