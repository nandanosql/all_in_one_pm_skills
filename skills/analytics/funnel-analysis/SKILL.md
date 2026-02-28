---
name: funnel-analysis
description: Build and analyze conversion funnels — identify drop-off points, diagnose conversion blockers, and design interventions. Covers funnel types, analysis methods, and common misinterpretations.
type: component
domain: analytics
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: []
outputs: ["funnel-analysis-document"]
triggers:
  - "Build a conversion funnel"
  - "Where are users dropping off"
  - "Funnel analysis"
  - "Conversion rate optimization"
---

## Purpose

Build and analyze conversion funnels to identify **where users drop off, why they leave, and what to fix** — turning raw event data into prioritized improvement campaigns.

---

## Application

### Step 1: Define the Funnel

```markdown
## Funnel: [Name — e.g., "Trial to Paid"]

| Step | Event | Definition |
|------|-------|-----------|
| 1 | [Landing page visit] | [User arrives on landing page] |
| 2 | [Signup started] | [User clicks "Start trial"] |
| 3 | [Signup completed] | [User completes registration] |
| 4 | [Onboarding started] | [User begins setup] |
| 5 | [Activated] | [User completes activation event] |
| 6 | [Converted] | [User starts paid subscription] |
```

### Step 2: Measure Conversion

```markdown
| Step | Users | Conv. Rate | Drop-off |
|------|-------|-----------|---------|
| Landing page | 10,000 | — | — |
| Signup started | 3,200 | 32% | 68% |
| Signup completed | 2,400 | 75% | 25% |
| Onboarding | 1,800 | 75% | 25% |
| Activated | 670 | 37% | 63% |
| Converted | 252 | 38% | 62% |

**Overall funnel conversion:** 2.5%
**Biggest drop-offs:** Landing → Signup (68%), Onboarding → Activated (63%)
```

### Step 3: Diagnose Drop-offs

For each significant drop-off:

```markdown
### Drop-off: [Step A] → [Step B] ([%] drop)
**Hypotheses:**
1. [Reason — e.g., "Form is too long"] → Evidence: [Data/research]
2. [Reason] → Evidence: [Data]

**Recommended intervention:**
- [What to test + expected impact]
```

### Step 4: Prioritize Improvements

```markdown
| Leaky Step | Drop-off % | Potential Lift | Effort | Priority |
|-----------|-----------|---------------|--------|----------|
| [Step] | [%] | [Est. users saved] | [S/M/L] | [1/2/3] |
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Funnel Definition** | Not defined | Steps listed | Steps + events + clear definitions |
| **Data Quality** | Estimated | Some real data | Full tracking with reliable data |
| **Diagnosis** | "Users leave" | Drop-offs quantified | Quantified + hypotheses + evidence |
| **Action** | "Fix the funnel" | Interventions listed | Prioritized by impact/effort |

---

## References

### Related Skills
- `skills/growth/activation-optimization/SKILL.md` — Activation funnel deep-dive
- `skills/growth/ab-test-design/SKILL.md` — Test funnel interventions
- `skills/growth/growth-model/SKILL.md` — Funnel drives growth model

---

**Skill type:** Component
**Domain:** Analytics & Metrics
