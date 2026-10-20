---
name: business-context-analysis
description: >-
  Analyze business context documents including strategy presentations, market
  analysis, business model canvases, and stakeholder inputs. Extract business
  goals, constraints, success metrics, and strategic priorities relevant to the
  design sprint. Use this skill when the team provides business documents that
  need to be distilled into sprint-relevant context. Primarily used during the
  Understand phase.
---

# Business Context Analysis

## Input Types

- Strategy presentations (PDF, slides)
- Business model canvas
- OKRs, KPIs, or success metrics documents
- Market analysis or research reports
- Stakeholder interview notes
- Product roadmaps

## Analysis Approach

### 1. Extract Core Elements

For each business document, identify:
- **Business objectives:** What is the organization trying to achieve?
- **Target market:** Who are the customers and what segments matter?
- **Success metrics:** How will success be measured? (KPIs, OKRs)
- **Constraints:** Budget, timeline, regulatory, technical, organizational
- **Competitive positioning:** Where does the product sit in the market?
- **Key assumptions:** What beliefs underpin the strategy?

### 2. Sprint Relevance Filter

Not everything in a business document is relevant to a design sprint. Focus on:
- Goals that the sprint prototype could demonstrate progress toward
- Constraints that limit design options
- Metrics that the prototype's user flows should optimize for
- Competitive gaps that the sprint concept should address

### 3. Tension Mapping

Cross-reference with user research (if available in `docs/user-research/`):
- Where do business goals align with user needs?
- Where do they conflict?
- Which tensions need to be resolved during the sprint?

## Output

Save to `docs/business-context/` using the template at `assets/templates/business-context-template.md`.

The output should be concise enough for the whole team to read in 5 minutes, while being specific enough to inform design decisions throughout the sprint.
