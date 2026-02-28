---
name: saas-revenue-growth-metrics
description: Track and interpret SaaS revenue growth metrics — MRR breakdown, expansion revenue, net dollar retention, cohort revenue curves, and growth efficiency indicators.
type: component
domain: analytics
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["saas-economics-efficiency-metrics"]
outputs: ["revenue-growth-dashboard"]
triggers:
  - "Track our revenue growth"
  - "SaaS revenue metrics"
  - "MRR breakdown"
  - "Revenue growth analysis"
---

## Purpose

Track and interpret SaaS revenue growth metrics — **MRR components, expansion dynamics, net dollar retention, and growth efficiency** — to understand not just how much you're growing but the quality and sustainability of that growth.

---

## Application

### MRR Waterfall Template

```markdown
# Revenue Growth Report: [Period]

## MRR Waterfall
| Component | Amount | % of Starting MRR |
|-----------|--------|-------------------|
| Starting MRR | $[X] | — |
| + New MRR | $[X] | [%] |
| + Expansion MRR | $[X] | [%] |
| - Contraction MRR | -$[X] | [%] |
| - Churned MRR | -$[X] | [%] |
| **= Ending MRR** | **$[X]** | **[Net change %]** |

## Growth Quality Indicators
| Metric | Value | Benchmark | Health |
|--------|-------|-----------|--------|
| MRR Growth Rate | [%] | >10% MoM early, >3% mature | 🟢/🟡/🔴 |
| Net Dollar Retention | [%] | >110% | 🟢/🟡/🔴 |
| Gross Dollar Retention | [%] | >85% | 🟢/🟡/🔴 |
| Quick Ratio | [#] | >4 | 🟢/🟡/🔴 |
| Expansion % of new revenue | [%] | Increasing over time | 🟢/🟡/🔴 |

## Revenue by Cohort
| Cohort | Month 0 | Month 3 | Month 6 | Month 12 |
|--------|---------|---------|---------|----------|
| [Q1] | $[X] | $[X] | $[X] | $[X] |
| [Q2] | $[X] | $[X] | $[X] | — |

**Cohort expansion pattern:** [Revenue per cohort growing/flat/shrinking over time?]

## Growth Efficiency
| Metric | Value | What It Means |
|--------|-------|--------------|
| **CAC Payback** | [# months] | Time to recoup acquisition cost |
| **LTV/CAC** | [#]:1 | Return on acquisition investment |
| **Burn Multiple** | [#]x | Cash efficiency of growth |
| **Revenue per Employee** | $[X] | Operational efficiency |

## Key Insights
1. [Growth driver: what's working]
2. [Growth risk: what's concerning]
3. [Recommendation: what to do about it]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **MRR Breakdown** | Total MRR only | Components listed | Full waterfall with trends |
| **Retention** | Not tracked | GDR or NDR | Both GDR + NDR + Quick Ratio |
| **Cohort** | No cohort view | Monthly cohorts | Cohort revenue curves over time |
| **Efficiency** | Revenue number only | Growth rate | Rate + efficiency ratios |

---

## References

### Related Skills
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — Unit economics
- `skills/analytics/finance-metrics-quickref/SKILL.md` — Financial foundations
- `skills/growth/growth-model/SKILL.md` — Revenue projections

### External Frameworks
- Bessemer Cloud Index — SaaS benchmarks
- SaaS Capital, SaaS Metrics

---

**Skill type:** Component
**Domain:** Analytics & Metrics
