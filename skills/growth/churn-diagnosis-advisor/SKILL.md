---
name: churn-diagnosis-advisor
description: Diagnose churn causes through systematic analysis — segment churned users, identify patterns, map to churn archetypes, and recommend retention interventions.
type: interactive
domain: growth
difficulty: advanced
estimated_time: "25-35 min"
prerequisites: ["retention-deep-dive", "cohort-analysis"]
outputs: ["churn-diagnosis-report"]
triggers:
  - "Why are users churning"
  - "Diagnose our churn problem"
  - "Churn analysis"
  - "How do we reduce churn"
---

## Purpose

Diagnose churn causes through systematic analysis — **segment churned users, identify behavioral patterns, map to churn archetypes**, and recommend targeted retention interventions.

---

## Application

### Turn 1: Churn Data

**Agent asks:** "Tell me about your churn situation."
- Current churn rate (monthly/annual)
- Trend (improving/worsening/stable)
- How do you define churn? (Cancellation? Inactivity? Non-renewal?)
- Do you have exit survey data?

### Turn 2: Segment the Churned Users

**Agent asks:** "Let's segment who's churning. Do you see patterns?"

```markdown
## Churn Segments
| Segment | % of Churners | Avg Tenure | Behavior Before Churn |
|---------|-------------|-----------|---------------------|
| [Never activated] | [%] | <30 days | Never completed onboarding |
| [Early churn] | [%] | 1-3 months | Used briefly, stopped |
| [Mature churn] | [%] | 6+ months | Was active, then declined |
| [Price-driven] | [%] | Varies | Active but cancelled citing price |
```

### Turn 3: Map to Churn Archetypes

| Archetype | Signal | Root Cause | Fix |
|-----------|--------|-----------|-----|
| **Never got value** | Low activation, short tenure | Onboarding gap | Activation optimization |
| **Got value, lost it** | Was active, usage declined | Product relevance fading | Re-engagement, new value |
| **Found alternative** | Sudden stop, competitor mentions | Competitive loss | Feature parity, positioning |
| **Price sensitive** | Active but cites price | Value < perceived cost | Pricing, value communication |
| **Churned by accident** | Credit card failure, forgot | Passive churn | Dunning, reminders |

### Turn 4: Intervention Plan

```markdown
## Churn Reduction Plan

### Quick Wins (This Month)
- [Intervention 1 targeting highest-volume archetype]
- [Dunning/payment recovery if applicable]

### Medium-Term (This Quarter)
- [Activation improvements for "never got value"]
- [Re-engagement campaign for "got value, lost it"]

### Long-Term (Next Quarter)
- [Competitive response for "found alternative"]
- [Pricing adjustments for "price sensitive"]

### Metrics to Track
| Metric | Baseline | Target | Timeline |
|--------|----------|--------|----------|
| Overall churn | [%] | [%] | [Weeks] |
| [Archetype 1] churn | [%] | [%] | [Weeks] |
```

---

## References

### Related Skills
- `skills/growth/retention-deep-dive/SKILL.md` — Retention analysis
- `skills/growth/activation-optimization/SKILL.md` — Fix "never got value"
- `skills/growth/pol-probe/SKILL.md` — PMF drives retention

---

**Skill type:** Interactive
**Domain:** Growth & Optimization
