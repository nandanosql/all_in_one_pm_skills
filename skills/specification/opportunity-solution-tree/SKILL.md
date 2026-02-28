---
name: opportunity-solution-tree
description: Structure product decisions using Teresa Torres' Opportunity Solution Tree — connecting outcomes to opportunities to solutions to experiments in a visual hierarchy.
type: component
domain: specification
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: ["okr-framework", "problem-statement"]
outputs: ["opportunity-solution-tree"]
triggers:
  - "Create an opportunity solution tree"
  - "Map opportunities to solutions"
  - "Teresa Torres approach"
  - "Structure our solution options"
---

## Purpose

Structure product decisions using Teresa Torres' **Opportunity Solution Tree** — a visual hierarchy that connects business outcomes to customer opportunities to potential solutions to validation experiments. Prevents teams from jumping to solutions before understanding the opportunity space.

---

## Key Concepts

### The Tree Structure

```
                    OUTCOME
                 (Business goal)
                /       |       \
        Opportunity  Opportunity  Opportunity
       (Customer need/pain point)
        /        \         |
   Solution  Solution   Solution
   (Ideas to address opportunity)
    /     \
Experiment Experiment
(Cheapest way to test)
```

### Rules

1. **Outcomes** are business results you're trying to drive (from OKRs)
2. **Opportunities** are customer needs, pain points, or desires (from discovery)
3. **Solutions** are ideas for addressing opportunities (brainstormed)
4. **Experiments** are the cheapest way to test if a solution works
5. **Always compare 3+ solutions** per opportunity before picking one

---

## Application

### Step 1: Define the Outcome

```markdown
**Desired Outcome:** [From OKR — e.g., "Increase 7-day activation from 28% to 55%"]
**Why this outcome:** [Connection to business strategy]
```

### Step 2: Map Opportunities

```markdown
**Opportunities (customer needs that, if addressed, would drive the outcome):**

1. [Opportunity 1 — e.g., "Users don't understand core value during trial"]
   - Evidence: [Interview quotes, data]
   - Size: [# users affected]

2. [Opportunity 2 — e.g., "Data connection step is too technical"]
   - Evidence: [Drop-off data]
   - Size: [# users affected]

3. [Opportunity 3]
```

### Step 3: Generate Solutions (3+ per opportunity)

```markdown
**Solutions for Opportunity 1:**
| Solution | Effort | Confidence | Notes |
|----------|--------|-----------|-------|
| [Solution A] | [S/M/L] | [H/M/L] | [Rationale] |
| [Solution B] | [S/M/L] | [H/M/L] | [Rationale] |
| [Solution C] | [S/M/L] | [H/M/L] | [Rationale] |
```

### Step 4: Design Experiments

```markdown
**Experiment for [chosen solution]:**
- **Type:** [Prototype test / Fake door / A/B test / Concierge]
- **What we'll learn:** [Specific question]
- **Success criteria:** [Metric + threshold]
- **Duration:** [Days/weeks]
- **Cost:** [Effort to run]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Outcome** | Not defined | Vague goal | Measurable from OKR |
| **Opportunities** | Assumed | Listed from intuition | Evidence-backed from research |
| **Solution Diversity** | 1 solution (pet idea) | 2 solutions | 3+ solutions compared |
| **Experiments** | None (just build it) | High-cost experiment | Cheapest test possible |
| **Evidence** | All assumption | Some data | Research-backed at each level |

---

## References

### Related Skills
- `skills/strategy/okr-framework/SKILL.md` — Outcome comes from OKRs
- `skills/discovery/problem-statement/SKILL.md` — Opportunities from validated problems
- `skills/growth/ab-test-design/SKILL.md` — Experiment design

### External Frameworks
- Teresa Torres, *Continuous Discovery Habits* (2021)

---

**Skill type:** Component
**Domain:** Specification & Design
