---
name: business-health-diagnostic
description: Run a comprehensive business health check across revenue, unit economics, product metrics, and market position — identifying strengths, weaknesses, and the single most important metric to fix.
type: interactive
domain: analytics
difficulty: advanced
estimated_time: "30-40 min"
prerequisites: ["saas-economics-efficiency-metrics"]
outputs: ["business-health-report"]
triggers:
  - "How healthy is our business"
  - "Business health check"
  - "Product health diagnostic"
  - "Overall metrics assessment"
---

## Purpose

Run a comprehensive **business health diagnostic** across revenue, unit economics, product metrics, and market position — producing a health scorecard that identifies the single most critical issue to address.

---

## Application

### Turn 1: Revenue Health

**Agent asks:** "Tell me about your revenue metrics."
- MRR/ARR
- Growth rate (MoM or YoY)
- Revenue composition (new vs expansion vs existing)

### Turn 2: Unit Economics

**Agent asks:** "Let me assess your unit economics."
- CAC and trend
- LTV and how calculated
- Churn rate
- Payback period

### Turn 3: Product Health

**Agent asks:** "How's the product performing?"
- Activation rate
- DAU/MAU ratio (stickiness)
- Net Promoter Score
- Feature adoption rates

### Turn 4: Market Position

**Agent asks:** "Where do you stand competitively?"
- Market share estimate
- Win rate vs competitors
- Category trend (growing/shrinking)

### Output: Health Scorecard

```markdown
# Business Health Diagnostic

## Scorecard
| Dimension | Score (1-5) | Status | Key Concern |
|-----------|-----------|--------|------------|
| Revenue Growth | [#] | 🟢/🟡/🔴 | [Issue or "Healthy"] |
| Unit Economics | [#] | 🟢/🟡/🔴 | [Issue or "Healthy"] |
| Product Health | [#] | 🟢/🟡/🔴 | [Issue or "Healthy"] |
| Market Position | [#] | 🟢/🟡/🔴 | [Issue or "Healthy"] |
| **Overall** | **[#/20]** | **[Status]** | |

## 🎯 #1 Priority
**The single most important metric to fix:**
[Metric] — currently at [value], target [value]

**Why this matters most:**
[Because it's upstream of X other metrics / because it's at crisis level]

**Recommended action:**
[Specific intervention]

## Full Recommendations
1. **Revenue:** [Action]
2. **Unit Economics:** [Action]
3. **Product:** [Action]
4. **Market:** [Action]
```

---

## References

### Related Skills
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — Unit economics
- `skills/analytics/saas-revenue-growth-metrics/SKILL.md` — Revenue metrics
- `skills/growth/growth-model/SKILL.md` — Growth projections
- `skills/analytics/metrics-dashboard-design/SKILL.md` — Dashboard setup

---

**Skill type:** Interactive
**Domain:** Analytics & Metrics
