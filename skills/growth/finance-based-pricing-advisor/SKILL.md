---
name: finance-based-pricing-advisor
description: Guide pricing decisions using financial models — cost structure analysis, margin targets, break-even calculation, and unit economics to set sustainable price points.
type: interactive
domain: growth
difficulty: advanced
estimated_time: "25-35 min"
prerequisites: ["saas-economics-efficiency-metrics"]
outputs: ["pricing-financial-model"]
triggers:
  - "Price this based on our costs"
  - "Financial model for pricing"
  - "Break-even analysis for pricing"
  - "Cost-based pricing analysis"
---

## Purpose

Guide pricing decisions using **financial modeling** — analyzing cost structures, setting margin targets, calculating break-even points, and ensuring unit economics work at scale before setting prices.

---

## Application

### Turn 1: Cost Structure

**Agent asks:** "What are your costs? Let's build the cost model."

```markdown
## Cost Structure

### Fixed Costs (Monthly)
| Category | Amount |
|----------|--------|
| Infrastructure | $[X] |
| Team (salaries) | $[X] |
| Tools & licenses | $[X] |
| Office/overhead | $[X] |
| **Total Fixed** | **$[X]** |

### Variable Costs (Per Customer/Month)
| Category | Amount |
|----------|--------|
| Compute/storage | $[X]/customer |
| Support | $[X]/customer |
| Payment processing | [X]% of revenue |
| **Total Variable** | **$[X]/customer** |
```

### Turn 2: Revenue Targets

**Agent asks:** "What are your revenue and margin goals?"
- Revenue target (monthly/annual)
- Gross margin target (SaaS benchmark: >70%)
- Growth rate target

### Turn 3: Break-Even Analysis

**Agent generates:**

```markdown
## Break-Even Analysis

**Fixed costs:** $[X]/month
**Variable cost per customer:** $[X]/month
**Price per customer:** $[P]/month

**Contribution margin:** $[P - Variable cost] per customer
**Break-even customers:** [Fixed costs / Contribution margin] = [#] customers
**Current customers:** [#]
**Gap:** [# more customers needed]

## Scenario Analysis
| Price Point | Margin | Break-even (customers) | At 1000 users (profit) |
|------------|--------|----------------------|----------------------|
| $[Low] | [%] | [#] | $[X] |
| $[Mid] | [%] | [#] | $[X] |
| $[High] | [%] | [#] | $[X] |
```

### Turn 4: Recommended Price Range

```markdown
## Pricing Floor & Ceiling
- **Floor:** $[X]/mo (covers variable costs + target margin)
- **Ceiling:** $[X]/mo (willingness-to-pay limit)
- **Recommended:** $[X]/mo (optimal margin × conversion)

## Sensitivity
- If churn increases by 5%: [impact on unit economics]
- If CAC increases by 20%: [impact on payback period]
```

---

## References

### Related Skills
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — Unit economics
- `skills/growth/pricing-strategy/SKILL.md` — Full pricing strategy
- `skills/launch/pricing-packaging-advisor/SKILL.md` — Packaging decisions

---

**Skill type:** Interactive
**Domain:** Growth & Optimization
