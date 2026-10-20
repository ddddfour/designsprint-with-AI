# Sprint Workflow Rules

## Phase-Specific Behavior

### Understand Phase (Day 1)
- Prioritize asking clarifying questions and analyzing inputs over proposing solutions
- Help synthesize diverse inputs (research data, business context, competitor info) into clear problem statements
- Flag assumptions and knowledge gaps explicitly
- Encourage the team to explore the problem space before jumping to solutions

### Ideate Phase (Day 2)
- Generate many distinct alternatives rather than converging early
- Push beyond obvious solutions — suggest unexpected approaches, analogies from other domains
- Quantity over quality at this stage — avoid self-censoring ideas
- When asked for ideas, provide at least 3–5 meaningfully different options

### Decide Phase (Day 3)
- Help evaluate ideas against sprint goals, user needs, and technical constraints
- Use structured comparison (pros/cons, scoring matrices) rather than gut feel
- Surface trade-offs explicitly — do not hide complexity
- Help the team make decisions and document the rationale

### UX Foundation Phase (Days 4–5)
- Focus on establishing solid structural foundations: IA, navigation, layout patterns
- Keep wireframes low-to-mid fidelity — avoid premature visual polish
- Ensure UX principles are derived from research, not just best practices
- Check accessibility early: reading order, touch targets, screen reader flow

### UX Advanced Phase (Days 6–7)
- Go deep on every feature: all states, edge cases, error handling, micro-interactions
- Maintain consistency across features — flag contradictions or pattern breaks
- Consider the conventions of the platforms recorded on Day 1 alongside custom patterns
- Use the Day 7 hallway test to catch major issues before prototyping

### Prototype Phase (Days 8–9)
- Build fast, iterate often — the prototype is for demonstration and informal testing
- Use design system tokens consistently — never hardcode values
- Keep interactions simple but realistic enough for stakeholder review
- Focus on the critical user flows identified during Decide
- Write user stories with clear acceptance criteria alongside the prototype

### Review & Handoff Phase (Day 10)
- Help prepare a compelling stakeholder presentation: problem → solution → demo → next steps
- Ensure the handoff package is complete and organized
- Categorize stakeholder feedback: accepted, needs discussion, out of scope
- Connect findings back to original sprint goals and user needs

## General Sprint Rules

- Always check the current sprint day in `docs/sprint-journal/` before choosing an approach
- Log significant decisions in `docs/design-decisions/` using the decision record format
- When the team seems stuck, suggest a timeboxed activity or a change of approach rather than pushing through
- Small team (3–5 people): every voice matters, actively invite input from quieter participants
- Informal testing is woven throughout — encourage quick hallway tests whenever wireframes or prototypes reach a testable state
