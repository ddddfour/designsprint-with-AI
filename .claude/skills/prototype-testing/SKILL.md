---
name: prototype-testing
description: >-
  Facilitate prototype testing sessions by generating test scripts, structuring
  feedback capture, and analyzing test results. Use this skill during the Test
  phase when preparing for, conducting, or analyzing usability testing sessions
  with real users.
---

# Prototype Testing

## Test Preparation

### 1. Create a Test Script
Use the template at `assets/templates/test-script-template.md`.

Based on:
- Sprint questions from the Understand phase (in `docs/sprint-journal/`)
- The critical user flow in the prototype
- Specific design decisions the team wants to validate

### 2. Prepare Feedback Capture Forms
Use the template at `assets/templates/feedback-capture-template.md`.

One form per test session. The observer fills this in during the session.

### 3. Define Success Criteria
Before testing, agree on:
- Task completion: can users complete the critical flow?
- Time on task: are key actions quick enough?
- Error rate: how often do users take wrong paths?
- Satisfaction: do users feel the experience is good?

## During Testing

### Session Structure (30-45 minutes)
1. **Welcome** (3 min) — Explain the session, set expectations
2. **Background questions** (5 min) — Understand the participant's context
3. **Task scenarios** (15-25 min) — Observe the participant using the prototype
4. **Follow-up questions** (5-7 min) — Probe specific observations
5. **Wrap-up** (2 min) — Thank participant, ask for any final thoughts

### Team Roles
- **Moderator** (1 person): Guides the session, asks questions, keeps time
- **Observer(s)** (rest of team): Take notes, fill feedback forms, no direct interaction

### Observation Tips
- Note what users **do**, not just what they say
- Capture exact quotes for impactful moments
- Record where users pause, backtrack, or show confusion
- Don't help or explain unless the user is completely stuck

## Analysis

### After Each Session (5-10 min debrief)
Quick sync with the team:
- Biggest surprise?
- What confirmed our assumptions?
- Any critical issues to note?

### After All Sessions

1. **Compile observations** from all feedback capture forms
2. **Identify patterns** — What did multiple participants struggle with?
3. **Severity rate each finding:**
   - **Critical:** Blocks task completion, user cannot proceed
   - **Major:** Causes significant confusion or frustration, but user recovers
   - **Minor:** Cosmetic issue or mild preference, doesn't impair function
4. **Map to sprint questions** — Which questions from the Understand phase are now answered?
5. **Create recommendations** — Prioritized list of changes

### Output
Save to `docs/test-results/`:
- `session-N.md` — Individual session notes
- `analysis.md` — Cross-session patterns and findings
- `recommendations.md` — Prioritized action items

## Recommended Number of Sessions

For a small team sprint: **3-5 sessions** is the target. Research shows 5 users find ~85% of usability issues. With time constraints, 3 sessions still surface the most critical problems.
