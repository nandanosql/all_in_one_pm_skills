---
name: saas-economics-efficiency-metrics
description: Calculate and interpret SaaS unit economics — CAC, LTV, LTV/CAC ratio, payback period, net revenue retention, and magic number — to assess business health and growth efficiency.
type: component
domain: analytics
difficulty: advanced
estimated_time: "25-35 min"
prerequisites: ["north-star-metric"]
outputs: ["saas-metrics-dashboard"]
triggers:
  - "Calculate our unit economics"
  - "What's our LTV/CAC ratio"
  - "SaaS metrics analysis"
  - "Are our economics healthy"
---

## Purpose

Calculate and interpret critical SaaS economics — **CAC, LTV, LTV/CAC, payback period, NRR, and magic number** — to assess whether the business can grow sustainably and where to invest.

---

## Application

### Key Metrics Template

```markdown
# SaaS Economics: [Product Name]
**Period:** [Quarter/Year]

## Unit Economics

| Metric | Value | Benchmark | Health |
|--------|-------|-----------|--------|
| **CAC** (Customer Acquisition Cost) | $[#] | Industry: $[#] | 🟢/🟡/🔴 |
| **LTV** (Lifetime Value) | $[#] | ≥3x CAC | 🟢/🟡/🔴 |
| **LTV:CAC Ratio** | [#]:1 | >3:1 healthy | 🟢/🟡/🔴 |
| **Payback Period** | [#] months | <12 months | 🟢/🟡/🔴 |
| **Gross Margin** | [%] | >70% SaaS | 🟢/🟡/🔴 |
| **NRR** (Net Revenue Retention) | [%] | >110% | 🟢/🟡/🔴 |
| **GRR** (Gross Revenue Retention) | [%] | >85% | 🟢/🟡/🔴 |
| **Magic Number** | [#] | >0.75 invest more | 🟢/🟡/🔴 |
| **Rule of 40** | [%] | >40% | 🟢/🟡/🔴 |

## Formulas
- **CAC** = Total Sales & Marketing Spend / New Customers Acquired
- **LTV** = ARPU × Gross Margin × (1 / Churn Rate)
- **LTV:CAC** = LTV / CAC
- **Payback Period** = CAC / (ARPU × Gross Margin)
- **NRR** = (Starting MRR + Expansion - Contraction - Churn) / Starting MRR
- **Magic Number** = Net New ARR / Prior Quarter S&M Spend
- **Rule of 40** = Revenue Growth Rate + Profit Margin

## Interpretation
- [What's healthy and why]
- [What needs improvement]
- [Investment recommendation based on magic number]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Metrics** | 1-2 metrics | 4-5 metrics | Full dashboard (8+ metrics) |
| **Data Quality** | Estimated | Partially calculated | Fully calculated from real data |
| **Benchmarking** | No comparison | Industry benchmark | Industry + trend over time |
| **Interpretation** | Numbers only | What they mean | What to do about them |

---

## References

### Related Skills
- `skills/strategy/business-model-canvas/SKILL.md` — Revenue model context
- `skills/growth/growth-model/SKILL.md` — Growth projections
- `skills/launch/pricing-packaging-advisor/SKILL.md` — Pricing affects all metrics

### External Frameworks
- David Skok (Matrix Partners), SaaS metrics
- Bessemer Cloud Index — SaaS benchmarks

---

**Skill type:** Component
**Domain:** Analytics & Metrics
