---
name: lean-ux-canvas
description: Facilitate a Lean UX Canvas session — linking business outcomes, users, outcomes, solutions, and hypotheses into a one-page alignment tool for cross-functional teams.
type: interactive
domain: specification
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: ["problem-statement", "proto-persona"]
outputs: ["lean-ux-canvas"]
triggers:
  - "Fill out a Lean UX Canvas"
  - "Run a Lean UX session"
  - "Align the team with Lean UX"
  - "Create a Lean UX hypothesis"
---

## Purpose

Facilitate a **Lean UX Canvas session** — linking business problems, user segments, user outcomes, solutions, and hypotheses into a one-page alignment tool that ensures the whole team is solving the same problem the same way.

---

## Application

### Turn 1: Business Problem

**Agent asks:** "What business problem are we trying to solve?"

```markdown
**Business Problem:**
[What is the business losing/missing? Revenue, efficiency, retention?]
```

### Turn 2: Business Outcomes

**Agent asks:** "What measurable business outcome would signal we've solved this?"

```markdown
**Business Outcomes:**
- [Outcome 1 — e.g., "Increase trial-to-paid conversion by 5%"]
- [Outcome 2]
```

### Turn 3: Users & Customers

**Agent asks:** "Who are the users affected? Which segment matters most?"

```markdown
**Users:**
- Primary: [Persona/segment]
- Secondary: [Persona/segment]
```

### Turn 4: User Benefits / Outcomes

**Agent asks:** "What user outcomes would drive the business outcomes above?"

```markdown
**User Outcomes:**
- [Users can accomplish X faster]
- [Users understand Y without help]
```

### Turn 5: Solution Ideas

**Agent asks:** "What solution ideas do we have? List 3+ without judgment."

```markdown
**Solutions:**
1. [Solution A]
2. [Solution B]
3. [Solution C]
```

### Turn 6: Hypotheses

**Agent asks:** "Let's turn the top solution into a testable hypothesis."

```markdown
**Hypothesis:**
We believe that [solution]
for [user segment]
will achieve [user outcome]
which will result in [business outcome].

We'll know we're right when [measurable signal].
We'll know we're wrong when [failure signal].
```

### Turn 7: MVP / Experiment

**Agent asks:** "What's the cheapest way to test this hypothesis?"

```markdown
**Experiment:**
- Type: [Prototype / Fake door / Concierge / A/B test]
- Duration: [X days/weeks]
- Success metric: [Specific threshold]
```

### Output: Complete Lean UX Canvas

```markdown
# Lean UX Canvas: [Initiative]

| Section | Content |
|---------|---------|
| **Business Problem** | [From Turn 1] |
| **Business Outcomes** | [From Turn 2] |
| **Users** | [From Turn 3] |
| **User Outcomes** | [From Turn 4] |
| **Solutions** | [From Turn 5] |
| **Hypothesis** | [From Turn 6] |
| **MVP / Experiment** | [From Turn 7] |
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Problem-Solution Fit** | Solution looking for a problem | Problem stated, solution assumed | Clear causal chain: problem → outcome → solution |
| **Hypothesis** | No hypothesis | Vague | Specific + testable + falsifiable |
| **Experiment** | "Build it and see" | Basic validation plan | Cheapest possible test with success criteria |

---

## References

### Related Skills
- `skills/specification/opportunity-solution-tree/SKILL.md` — Complementary framework
- `skills/planning/epic-hypothesis/SKILL.md` — Hypothesis format
- `skills/growth/ab-test-design/SKILL.md` — Experiment design

### External Frameworks
- Jeff Gothelf & Josh Seiden, *Lean UX* (2013)

---

**Skill type:** Interactive
**Domain:** Specification & Design
