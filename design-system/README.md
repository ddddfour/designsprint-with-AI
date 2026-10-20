# Design System

This directory contains the design system for the sprint prototype, structured as platform-agnostic design tokens and component specifications.

## Structure

```
design-system/
├── tokens/                 # W3C Design Tokens format (.tokens.json)
│   ├── colors.tokens.json
│   ├── typography.tokens.json
│   └── spacing.tokens.json
└── components/             # Component specifications and documentation
```

## Design Tokens

Tokens follow the [W3C Design Tokens](https://www.designtokens.org/) format (2025.10 specification). This ensures:
- Platform-agnostic definitions (JSON)
- Transformation into the prototype medium, once the team chooses one
- Transformation into the theme or token format of whatever production stack the team records

### Token Hierarchy

1. **Primitive tokens** — Raw values (e.g., `blue-600: #3366CC`, an example only)
2. **Semantic tokens** — Purpose-based aliases (e.g., `color-interactive: {color.primitive.blue-600}`)
3. **Component tokens** — Specific usage (e.g., `button-background: {color.semantic.interactive}`)

### Populating Tokens

Use `/design-system-extraction` with brand guidelines, Figma files, or other references to populate the token files. This is a Day 1 sprint activity.

### Using Tokens

- **Prototype:** Map tokens into the medium chosen on Day 4. There is no prebuilt stylesheet
- **Production:** Map tokens into the chosen stack and record that mapping in `prototype/production-reference/README.md`

## Components

Component documentation lives in `components/` and describes:
- Component purpose and variants
- Which design tokens it uses
- Accessibility requirements
- Code reference in the prototype
