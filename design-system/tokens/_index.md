# Design Tokens

Token files in this directory use the W3C Design Tokens format (`.tokens.json`).

## Files

- `colors.tokens.json` — Color primitives and semantic color tokens
- `typography.tokens.json` — Font families, sizes, weights, line heights
- `spacing.tokens.json` — Spacing scale, border radius, elevation

## Format Reference

Each token follows this structure:
```json
{
  "token-name": {
    "$value": "the-value",
    "$type": "color",
    "$description": "What this token is for"
  }
}
```

Aliases reference other tokens: `"$value": "{color.primitive.blue-600}"`

## Populating These Files

Use `/design-system-extraction` to extract tokens from brand references (Figma files, PDFs, guidelines). The token files here contain placeholder structure — they'll be filled during the sprint.

## Using Tokens in the Prototype

After tokens are populated, map them into the prototype medium chosen on Day 4. The `/ui-design` skill does that mapping. Do not create a stylesheet unless the chosen medium needs one.
