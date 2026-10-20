---
name: competitor-analysis
description: >-
  Analyze competitor products, identifying UX patterns, feature sets, strengths,
  and weaknesses. Create structured comparison matrices and opportunity maps.
  Use this skill when the team needs to understand the competitive landscape or
  draw inspiration from existing solutions. Primarily used during the Understand
  and Sketch & Ideate phases.
---

# Competitor Analysis

## Analysis Framework

### 1. Identify Competitors
- **Direct competitors:** Products solving the same problem for the same users
- **Indirect competitors:** Products solving a similar problem differently
- **Aspirational references:** Products from other domains with excellent UX patterns worth learning from

### 2. Analyze Each Competitor

For each competitor, evaluate:
- **Target audience:** Who are they designed for?
- **Key features:** What do they offer?
- **UX strengths:** What do they do well? (interactions, flows, visual design)
- **UX weaknesses:** Where do they fall short? (friction, confusion, gaps)
- **Unique differentiator:** What makes them distinct?
- **Platform approach:** Native, cross-platform, web, or desktop? Compare with the production stack recorded for this sprint.

### 3. Use Tools

- Use the `fetch` MCP to gather information from competitor websites, app store listings, review sites
- Use the `figma` MCP to reference design patterns if competitor teardowns exist in Figma
- Screenshot analysis if images are provided

## Output

Use the template at `assets/templates/competitor-matrix-template.md`.
Save to `docs/references/competitor-analysis.md`.

### Opportunity Mapping

After the matrix is complete, identify:
1. **Table stakes:** Features/patterns every competitor has (we need these too)
2. **Differentiators:** Where competitors are weak that we could be strong
3. **Innovation opportunities:** Needs no competitor addresses well
4. **UX patterns to adopt:** Successful patterns we should consider
5. **UX patterns to avoid:** Common mistakes across competitors
