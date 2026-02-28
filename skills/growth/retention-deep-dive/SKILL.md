---
name: retention-deep-dive
description: Analyze user retention by building cohort charts, identifying retention drivers, diagnosing churn patterns, and designing re-engagement strategies.
type: component
domain: growth
difficulty: advanced
estimated_time: "30-40 min"
prerequisites: ["north-star-metric"]
outputs: ["retention-analysis"]
triggers:
  - "Why are users churning"
  - "Analyze our retention"
  - "Build a retention cohort analysis"
  - "How do we improve retention"
---

## Purpose

Analyze **why users stay or leave** through cohort analysis, retention curve benchmarking, churn pattern identification, and re-engagement strategy design.

---

## Application

### Step 1: Build Retention Cohorts

```markdown
## Retention Cohort Table

| Cohort | D1 | D7 | D14 | D30 | D60 | D90 |
|--------|----|----|-----|-----|-----|-----|
| Jan 2026 | [%] | [%] | [%] | [%] | [%] | [%] |
| Feb 2026 | [%] | [%] | [%] | [%] | [%] | [%] |
| Mar 2026 | [%] | [%] | [%] | [%] | [%] | [%] |
```

### Step 2: Analyze the Curve Shape

```markdown
**Curve type:** [📉 Declining → Flat | 📉 Continuous decline | 📈 Smile curve]
**Flattening point:** [Day/Week when retention stabilizes]
**Benchmark:** [Industry average for our product type]
**Health verdict:** [Healthy / Needs work / Critical]
```

### Step 3: Churn Analysis

```markdown
## Top Churn Reasons (from data + user research)

| Reason | % of Churners | Segment | Intervention |
|--------|-------------|---------|-------------|
| [Reason 1] | [%] | [Who] | [What to do] |
| [Reason 2] | [%] | [Who] | [What to do] |
| [Reason 3] | [%] | [Who] | [What to do] |
```

### Step 4: Retention Strategies

```markdown
## Retention Improvement Plan

### Short-term (This Quarter)
- [Action 1 — targeting biggest churn reason]
- [Action 2 — quick win]

### Medium-term (Next Quarter)
- [Habit loop design — trigger, action, reward]
- [Engagement feature]

### Long-term (6+ months)
- [Product moat — data, network, switching cost]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Cohort Data** | No cohorts | Monthly cohorts | Weekly/monthly + segmented |
| **Churn Reasons** | Assumed | Survey data | Multi-source (data + interviews + analytics) |
| **Benchmarking** | No comparison | Industry average | Industry + historical trend |
| **Strategies** | "Improve the product" | Specific ideas | Prioritized by impact + effort |

---

## References

### Related Skills
- `skills/analytics/funnel-analysis/SKILL.md` — Pipeline to retention
- `skills/growth/activation-optimization/SKILL.md` — Activation drives D1 retention
- `skills/analytics/cohort-analysis/SKILL.md` — Cohort method deep dive
- `skills/growth/ab-test-design/SKILL.md` — Test retention interventions

---

**Skill type:** Component
**Domain:** Growth & Optimization
