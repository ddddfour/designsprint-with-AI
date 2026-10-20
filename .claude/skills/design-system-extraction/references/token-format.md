# W3C Design Tokens Format Reference

Based on the Design Tokens Format Module 2025.10 specification.

## File Format

- Media type: `application/design-tokens+json`
- File extensions: `.tokens` or `.tokens.json`
- Base format: JSON

## Token Properties

All specification-defined properties are prefixed with `$`:

| Property | Required | Description |
|----------|----------|-------------|
| `$value` | Yes | The token's value |
| `$type` | Recommended | The token type (color, dimension, etc.) |
| `$description` | Optional | Human-readable description |
| `$extensions` | Optional | Custom metadata |
| `$deprecated` | Optional | Whether the token is deprecated |

## Token Types

| Type | Example Value | Notes |
|------|--------------|-------|
| `color` | `#3366CC`, `oklch(0.5 0.2 240)` | Supports CSS Color Module 4. Example values only |
| `dimension` | `16px`, `1rem` | For spacing, sizes |
| `fontFamily` | `"Inter", sans-serif` | Font stack |
| `fontWeight` | `400`, `bold` | Numeric or keyword |
| `number` | `1.5` | Unitless numbers (line-height, etc.) |
| `duration` | `200ms` | For animations |
| `cubicBezier` | `[0.4, 0, 0.2, 1]` | Easing curves |
| `shadow` | Object with color, offset, blur, spread | Box shadows |
| `border` | Object with color, width, style | Border definitions |
| `gradient` | Array of color stops | Linear/radial gradients |
| `typography` | Composite object | Font family + size + weight + line-height |

## Groups

Tokens can be organized into nested groups:

```json
{
  "color": {
    "$description": "All color tokens",
    "primitive": {
      "blue-600": {
        "$value": "#3366CC",
        "$type": "color"
      }
    },
    "semantic": {
      "interactive": {
        "$value": "{color.primitive.blue-600}",
        "$type": "color"
      }
    }
  }
}
```

## Aliases / References

Reference other tokens using curly brace syntax:

```json
{
  "semantic-color": {
    "$value": "{color.primitive.blue-600}",
    "$type": "color"
  }
}
```

The path inside `{}` is the dot-separated path from the root of the token file to the referenced token.

## Cross-Platform Mapping

| Token (JSON) | Prototype (CSS) | Production |
|-------------|-----|-----------------|
| `color.primary: #3366CC` | `--color-primary: #3366CC` | Theme color in the chosen stack |
| `spacing.md: 16px` | `--spacing-md: 16px` | Spacing token in the chosen stack |
| `fontFamily.base: "Inter"` | `--font-family-base: "Inter"` | Font token in the chosen stack |

Record the real production column in `prototype/production-reference/README.md` once the stack is chosen.

## Tools for Transformation

- **Style Dictionary** — Industry-standard token transformer (JSON → CSS, Android XML, iOS, etc.)
- **Figma Tokens Plugin** — Export Figma variables as W3C tokens
- **Manual** — For sprint speed, CSS custom properties can be written directly from JSON
