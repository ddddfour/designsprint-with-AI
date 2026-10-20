---
name: reference-gathering
description: >-
  Gather and organize external references for the design sprint including
  developer documentation, API specs, tool integration guides (Figma, Figma Make,
  Claude Code), brand guidelines, and competitor materials. Use this skill when
  the team needs to collect, fetch, or catalog reference material from URLs,
  documents, or design files. Relevant during the Understand phase and
  throughout the sprint when new references are needed.
---

# Reference Gathering

## Tools Available

### Fetch MCP Server
Use the `fetch` MCP tool to retrieve web content:
- Developer documentation pages
- API specifications
- Blog posts and articles
- Design system documentation from other products

### Figma MCP Server
Use the `figma` MCP tool to pull design references:
- Extract styles, variables, and component definitions from Figma files
- Capture layout patterns and design decisions from existing designs
- Access shared team libraries

### File Reading
For locally provided materials:
- PDFs (brand guidelines, strategy decks) - read directly
- Images (screenshots, mood boards) - view and describe
- Code files (existing design system code) - analyze for patterns

## Process

1. **Check existing references** - Read `docs/references/_index.md` to see what's already gathered
2. **Fetch the content** - Use the appropriate tool based on source type
3. **Summarize** - For each reference, produce:
   - **Source**: URL or file path
   - **Type**: Documentation / API / Brand / Competitor / Inspiration
   - **Key Takeaways**: 3-5 bullet points of what's relevant to the sprint
   - **Relevance**: How this informs sprint decisions
4. **Save** - Append the summary to `docs/references/_index.md` or create a separate file in `docs/references/` for substantial references
5. **Cross-reference** - Note if the reference is relevant to specific skills (e.g., brand guidelines relevant to `/design-system-extraction`)

## Reference Types

| Type | Where to Look | What to Extract |
|------|--------------|-----------------|
| Brand guidelines | Figma, PDFs, URLs | Colors, typography, voice/tone, logo usage |
| API documentation | URLs, developer portals | Endpoints, data models, capabilities |
| Design patterns | Competitor apps, design systems | UI patterns, interaction models |
| Technical docs | Docs for the chosen language, framework, and platform | Capabilities, constraints, best practices |
| User research | Provided files, analytics URLs | Insights, data points, quotes |
| Business context | PDFs, presentations | Goals, metrics, strategy |

## Output Format

For quick references, append to `docs/references/_index.md`:
```markdown
### [Reference Title]
- **Source:** [URL or file path]
- **Type:** [Documentation/Brand/Competitor/etc.]
- **Key takeaways:**
  - Point 1
  - Point 2
  - Point 3
- **Sprint relevance:** [How this informs our work]
```

For substantial references (>1 page of notes), create `docs/references/[descriptive-name].md`.
