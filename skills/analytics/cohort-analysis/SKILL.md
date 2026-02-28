---
name: cohort-analysis
description: Build cohort-based analyses to understand how user behavior changes over time. Covers signup cohorts, behavioral cohorts, acquisition cohorts, and retention curves.
type: component
domain: analytics
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: []
outputs: ["cohort-analysis-document"]
triggers:
  - "Run a cohort analysis"
  - "Build a retention cohort table"
  - "Analyze user cohorts"
  - "How do different user groups compare"
---

## Purpose

Understand how **user behavior changes over time** by grouping users into cohorts and tracking their metrics over comparable time periods. Reveals trends that aggregate data hides.

---

## Application

### Cohort Types

| Type | Groups Users By | Reveals |
|------|----------------|---------|
| **Signup cohort** | When they joined (week/month) | Is retention improving? |
| **Behavioral cohort** | What they did (activated, invited, etc.) | Which actions predict retention? |
| **Acquisition cohort** | How they found you (channel) | Which channels bring quality users? |
| **Feature cohort** | Which features they use | Does feature X drive retention? |

### Template

```markdown
# Cohort Analysis: [Type] — [Product Name]

## Cohort Definition
- **Cohort type:** [Signup / Behavioral / Acquisition / Feature]
- **Grouping criterion:** [Specific definition]
- **Time period:** [Date range]
- **Metric tracked:** [Retention / Revenue / Engagement / etc.]

## Cohort Table
| Cohort | N | Week 1 | Week 2 | Week 4 | Week 8 | Week 12 |
|--------|---|--------|--------|--------|--------|---------|
| [Jan W1] | [#] | [%] | [%] | [%] | [%] | [%] |
| [Jan W2] | [#] | [%] | [%] | [%] | [%] | [%] |
| [Feb W1] | [#] | [%] | [%] | [%] | [%] | [%] |

## Key Findings
1. **Trend:** [Are newer cohorts performing better/worse?]
2. **Critical period:** [When does the sharpest drop-off occur?]
3. **Flattening point:** [When does retention stabilize?]
4. **Anomalies:** [Any cohorts that significantly outperform/underperform?]

## Actions
- [Action based on finding 1]
- [Action based on finding 2]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Cohort Definition** | Unclear grouping | Time-based only | Multiple cohort types compared |
| **Time Span** | < 4 weeks | 1-3 months | 3+ months for trend detection |
| **Sample Size** | Too small (<50/cohort) | Adequate | Statistically significant |
| **Insights** | Data only | Observations | Observations + actions |

---

## References

### Related Skills
- `skills/growth/retention-deep-dive/SKILL.md` — Retention analysis
- `skills/analytics/funnel-analysis/SKILL.md` — Funnel by cohort
- `skills/growth/activation-optimization/SKILL.md` — Behavioral cohort for activation

---

**Skill type:** Component
**Domain:** Analytics & Metrics
