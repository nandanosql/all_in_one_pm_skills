---
name: risk-assessment
description: Identify, evaluate, and mitigate product risks across technical, market, usability, and business dimensions before committing resources. Produces a risk register with owners and contingencies.
type: component
domain: planning
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["epic-hypothesis"]
outputs: ["risk-register"]
triggers:
  - "What could go wrong with this initiative"
  - "Run a risk assessment"
  - "Identify risks before we start building"
  - "Create a risk register"
---

## Purpose

Systematically identify and evaluate risks across **four dimensions** — technical, market, usability, and business — before committing significant resources. Creates a risk register with ownership, impact assessment, and mitigation plans.

---

## Key Concepts

### Four Risk Dimensions (Marty Cagan)

| Risk | Question | Example |
|------|----------|---------|
| **Value** | Will customers want it? | "Users might not care about this feature" |
| **Usability** | Can users figure it out? | "The workflow is too complex for non-technical users" |
| **Feasibility** | Can we build it? | "ML model accuracy might be insufficient" |
| **Viability** | Does it work for the business? | "Unit economics don't work at this price point" |

### Risk Matrix

```
              IMPACT
         Low    Med    High
   Low  │  1  │  2  │  3  │
PROB Med │  2  │  4  │  6  │
   High │  3  │  6  │  9  │
```

---

## Application

### Step 1: Brainstorm Risks

For each dimension, list potential risks:

```markdown
### Value Risks
- [Risk 1: description + "What if..." scenario]
- [Risk 2]

### Usability Risks
- [Risk 1]
- [Risk 2]

### Feasibility Risks
- [Risk 1]
- [Risk 2]

### Viability Risks
- [Risk 1]
- [Risk 2]
```

### Step 2: Evaluate and Prioritize

```markdown
| # | Risk | Dimension | Probability | Impact | Score | Owner |
|---|------|-----------|------------|--------|-------|-------|
| 1 | [Description] | [V/U/F/B] | [H/M/L] | [H/M/L] | [1-9] | [Name] |
| 2 | [Description] | [V/U/F/B] | [H/M/L] | [H/M/L] | [1-9] | [Name] |
```

### Step 3: Mitigation Plans (Top Risks)

For each risk scoring ≥6:

```markdown
## Risk: [Name]
**Mitigation strategy:** [How to reduce probability or impact]
**Contingency plan:** [What to do if it happens anyway]
**Leading indicator:** [How we'll know early if this risk is materializing]
**Decision point:** [When we'll re-evaluate this risk]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Coverage** | 1 risk dimension | 2-3 dimensions | All 4 (value, usability, feasibility, viability) |
| **Specificity** | "Something might go wrong" | Named risks | Risks + probability + impact |
| **Mitigation** | None | "We'll watch it" | Specific actions + owners + indicators |
| **Honesty** | All low probability | Mix | Unflinching, includes uncomfortable truths |
| **Actionability** | List only | Risk register | Register + decision points + contingencies |

---

## Common Pitfalls

### Pitfall 1: Risk Assessment as Checkbox Exercise

**Fix:** If your risk assessment has zero high-probability items, you're being dishonest. Every initiative has real risks.

### Pitfall 2: Identifying Risks But No Mitigation

**Fix:** A risk without a mitigation plan is just a worry. Every high-scored risk needs an owner and a plan.

---

## References

### Related Skills
- `skills/planning/epic-hypothesis/SKILL.md` — Hypotheses have embedded risk assumptions
- `skills/planning/dependency-map/SKILL.md` — Dependencies create feasibility risks
- `skills/planning/decision-log/SKILL.md` — Risk decisions should be logged

### External Frameworks
- Marty Cagan, *Inspired* — Four risk dimensions
- PMBOK Risk Management — Risk register format

---

**Skill type:** Component
**Domain:** Planning & Prioritization
