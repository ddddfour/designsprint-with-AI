---
name: concept-visualization
description: >-
  Create visual explanations of concepts, workflows, architectures, and
  relationships using text-based diagrams (Mermaid, ASCII), structured models,
  and analogies. Use this skill when the team needs to visualize user flows,
  system architecture, information architecture, concept maps, or any abstract
  idea that benefits from visual representation. Useful across all sprint phases.
---

# Concept Visualization

## Diagram Types

### Mermaid Diagrams
Mermaid renders in most Markdown viewers (GitHub, VS Code, etc.).

#### User Flow
```mermaid
flowchart TD
    A[Open App] --> B{Logged In?}
    B -->|Yes| C[Dashboard]
    B -->|No| D[Login Screen]
    D --> E[Enter Credentials]
    E --> C
```

#### Journey Map (visual)
```mermaid
journey
    title User Purchase Journey
    section Discovery
      Browse products: 3: User
      Read reviews: 4: User
    section Purchase
      Add to cart: 5: User
      Checkout: 2: User
    section Post-purchase
      Track order: 4: User
```

#### Sequence Diagram (interactions)
```mermaid
sequenceDiagram
    User->>App: Opens screen
    App->>API: Fetch data
    API-->>App: Return results
    App-->>User: Display content
```

#### Mind Map (ideation)
```mermaid
mindmap
  root((Sprint Goal))
    User Needs
      Need 1
      Need 2
    Business Goals
      Goal 1
      Goal 2
    Constraints
      Technical
      Timeline
```

#### Information Architecture
```mermaid
flowchart TD
    Home --> Search
    Home --> Profile
    Home --> Feed
    Feed --> PostDetail
    PostDetail --> Comments
    Profile --> Settings
    Profile --> History
```

### ASCII Diagrams
For simple layouts or when Mermaid is overkill:

```
┌─────────────────────┐
│     Header Bar      │
├─────────────────────┤
│                     │
│   Content Area      │
│                     │
├─────────────────────┤
│ Tab 1 │ Tab 2 │ Tab3│
└─────────────────────┘
```

### Wireframe Sketches (ASCII)
```
┌──────────────────┐
│ ← Back    Title  │
├──────────────────┤
│ ┌──────────────┐ │
│ │  Image       │ │
│ └──────────────┘ │
│ Heading Text     │
│ Description...   │
│                  │
│ [Primary Action] │
│  Secondary Link  │
└──────────────────┘
```

## Analogies and Mental Models

When explaining complex concepts:
1. Identify what the team already understands
2. Find a parallel structure in a familiar domain
3. Map the key relationships
4. Note where the analogy breaks down

## When to Use What

| Situation | Tool |
|-----------|------|
| User flow or navigation | Mermaid flowchart |
| API or system interaction | Mermaid sequence diagram |
| Brainstorming or categorizing | Mermaid mind map |
| Screen layout exploration | ASCII wireframe |
| Information architecture | Mermaid flowchart (tree) |
| Emotional journey | Mermaid journey diagram |
| Simple relationship | ASCII or bullet points |

## Output Location

- Embed diagrams directly in the relevant `docs/` files
- For standalone visualizations, save in the appropriate docs subdirectory
- Reference diagrams in sprint journal entries
