---
name: growth-model
description: Build a quantitative growth model — mapping acquisition, activation, retention, revenue, and referral into a spreadsheet-ready framework with assumptions and sensitivity analysis.
type: component
domain: growth
difficulty: advanced
estimated_time: "40-60 min"
prerequisites: ["north-star-metric", "funnel-analysis"]
outputs: ["growth-model-document"]
triggers:
  - "Build a growth model"
  - "Model our user acquisition and revenue"
  - "AARRR funnel model"
  - "Revenue projection model"
---

## Purpose

Build a quantitative growth model using the **AARRR framework** (Acquisition, Activation, Retention, Revenue, Referral) — creating a spreadsheet-ready model with assumptions, projections, and sensitivity analysis.

---

## Application

### AARRR Growth Model Template

```markdown
# Growth Model: [Product Name]
**Period:** [Monthly/Quarterly projections]

## Assumptions
| Parameter | Value | Source | Confidence |
|-----------|-------|--------|-----------|
| Monthly traffic | [#] | [GA/marketing data] | [H/M/L] |
| Signup rate | [%] | [Current data] | [H/M/L] |
| Activation rate | [%] | [Current data] | [H/M/L] |
| Monthly retention | [%] | [Cohort data] | [H/M/L] |
| ARPU | [$] | [Revenue/users] | [H/M/L] |
| Referral coefficient | [#] | [Current data] | [H/M/L] |

## Funnel Model (Monthly)

| Stage | Month 1 | Month 3 | Month 6 | Month 12 |
|-------|---------|---------|---------|----------|
| Traffic | [#] | [#] | [#] | [#] |
| Signups | [#] | [#] | [#] | [#] |
| Activated | [#] | [#] | [#] | [#] |
| Active (retained) | [#] | [#] | [#] | [#] |
| Revenue | [$] | [$] | [$] | [$] |

## Sensitivity Analysis
| Scenario | Key Change | Revenue Impact |
|----------|-----------|---------------|
| **Bull** | Activation +10pts | [+$X/mo] |
| **Base** | Current assumptions | [$X/mo] |
| **Bear** | Retention -5pts | [-$X/mo] |

## Key Leverage Points
1. **Highest impact:** [Which funnel stage has most room + easiest improvement]
2. **Cheapest test:** [What to test first]
3. **Biggest risk:** [Which assumption, if wrong, breaks the model]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Assumptions** | Guesses | Some data | All data-sourced with confidence |
| **Projections** | Single scenario | 3 scenarios | 3 scenarios + sensitivity |
| **Leverage Points** | Not identified | Listed | Quantified impact per lever |
| **Usability** | Narrative only | Table format | Spreadsheet-ready |

---

## References

### Related Skills
- `skills/analytics/funnel-analysis/SKILL.md` — Data for the model
- `skills/growth/activation-optimization/SKILL.md` — Improve activation lever
- `skills/growth/retention-deep-dive/SKILL.md` — Improve retention lever
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — Unit economics

### External Frameworks
- Dave McClure, AARRR / Pirate Metrics
- Andrew Chen, Growth modeling

---

**Skill type:** Component
**Domain:** Growth & Optimization
