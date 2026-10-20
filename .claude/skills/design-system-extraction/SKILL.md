---
name: design-system-extraction
description: >-
  Extract brand information from reference materials (Figma files, PDFs, code,
  brand guidelines) and create a structured design system with tokens,
  component definitions, and usage guidelines. Use this skill when the team
  needs to establish or update the design system, extract colors/typography/
  spacing from existing brand assets, or create design tokens. Use during the
  Understand phase (Day 1 setup) and Prototype phase.
---

# Design System Extraction

## Extraction Sources

### From Figma (via MCP)
Use the `figma` MCP server to extract:
- **Variables/tokens**: Colors, spacing, typography defined as Figma variables
- **Styles**: Text styles, color styles, effect styles
- **Component definitions**: Component structure, variants, properties
- **Layout patterns**: Spacing, alignment, grid usage

### From PDFs / Documents
Read brand guideline documents to extract:
- Color palettes with hex/RGB values
- Typography specifications (font families, sizes, weights)
- Spacing rules and grid systems
- Logo usage and clear space rules
- Voice and tone guidelines

### From Code
Analyze existing codebases for:
- CSS custom properties or Sass variables
- Theme definitions
- Component libraries

## Token Output Format

Follow the W3C Design Tokens 2025.10 specification. See `references/token-format.md` for details.

### Process

1. **Gather** — Collect all brand reference materials
2. **Extract** — Pull out design values (colors, type, spacing)
3. **Organize** — Structure into primitive → semantic → component layers
4. **Write** — Save to `design-system/tokens/*.tokens.json`
5. **Apply to the prototype** — Once a prototype medium exists, map tokens into that medium. Do not create a web prototype only to hold CSS variables.
6. **Document** — Update `design-system/README.md` with any notes about the token structure

### Color Token Example

```json
{
  "color": {
    "primitive": {
      "blue-600": {
        "$value": "#3366CC",
        "$type": "color",
        "$description": "Example only. Replace with the team's brand color"
      }
    },
    "semantic": {
      "interactive": {
        "default": {
          "$value": "{color.primitive.blue-600}",
          "$type": "color",
          "$description": "Default interactive element color"
        }
      }
    }
  }
}
```

### CSS Output Example

```css
:root {
  /* Primitives */
  --color-primitive-blue-600: #3366CC;

  /* Semantic */
  --color-interactive-default: var(--color-primitive-blue-600);
}
```

## When Automated Extraction Falls Short

Figma MCP may not expose all design variables cleanly. In these cases:
- Ask the team to identify key values manually
- Screenshot relevant guideline pages and extract values visually
- Use reasonable defaults based on the brand's overall feel
- Document any assumptions in `design-system/README.md`
