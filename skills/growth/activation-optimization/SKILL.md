---
name: activation-optimization
description: Diagnose and optimize user activation — the critical journey from signup to first value. Covers activation metrics, onboarding analysis, aha moment identification, and improvement strategies.
type: component
domain: growth
difficulty: intermediate
estimated_time: "25-35 min"
prerequisites: ["funnel-analysis", "north-star-metric"]
outputs: ["activation-strategy"]
triggers:
  - "How do we improve activation"
  - "Users sign up but don't come back"
  - "Onboarding optimization"
  - "Define our aha moment"
---

## Purpose

Diagnose and optimize the critical **signup-to-value journey** — finding the "aha moment," measuring time-to-value, and designing interventions that turn signups into activated, retained users.

---

## Application

### Step 1: Define Activation

```markdown
**Activation event:** [The specific action that correlates with long-term retention]
**How we found it:** [Correlation analysis / cohort analysis / intuition + data]
**Current activation rate:** [% of signups completing the activation event]
**Current time-to-activation:** [Median time from signup to activation event]
```

### Step 2: Map the Activation Funnel

```markdown
| Step | % Completion | Drop-off | Hypothesis for Drop-off |
|------|-------------|---------|------------------------|
| 1. Signup | 100% | — | — |
| 2. [First step] | [%] | [%] | [Why they leave] |
| 3. [Second step] | [%] | [%] | [Why they leave] |
| 4. [Aha moment] | [%] | [%] | [Why they leave] |
| 5. Activated | [%] | — | — |
```

### Step 3: Identify Interventions

```markdown
**Top 3 interventions (by expected impact):**

1. **[Intervention]**
   - Target: Step [#] (biggest drop-off)
   - Estimated impact: [+X% activation]
   - Effort: [S/M/L]
   - Test: [A/B test / prototype / fake door]

2. **[Intervention]**
   ...
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Activation Definition** | "When they sign up" | Activity-based | Data-validated correlation to retention |
| **Funnel Mapping** | Not mapped | Steps listed | Steps + drop-off % + hypotheses |
| **Interventions** | "Improve onboarding" | Specific ideas | Prioritized + effort-estimated + testable |

---

## References

### Related Skills
- `skills/analytics/funnel-analysis/SKILL.md` — Build the activation funnel
- `skills/growth/ab-test-design/SKILL.md` — Test interventions
- `skills/growth/retention-deep-dive/SKILL.md` — Activation drives retention

---

**Skill type:** Component
**Domain:** Growth & Optimization
