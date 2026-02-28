---
name: metrics-dashboard-design
description: Design an actionable product analytics dashboard — choosing the right metrics, layout hierarchy, alerts, and refresh cadence so the team uses it daily, not once.
type: interactive
domain: analytics
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["north-star-metric"]
outputs: ["dashboard-spec"]
triggers:
  - "Design our product dashboard"
  - "What metrics should we track"
  - "Build a metrics dashboard"
  - "Analytics dashboard setup"
---

## Purpose

Design a product analytics dashboard that the team **actually uses daily** — with the right metrics hierarchy, alert thresholds, and cadence. Avoids the "we built a dashboard and no one looks at it" trap.

---

## Application

### Question 1: Dashboard Purpose

**Agent asks:** "Who is this dashboard for and what decisions will it inform?"

1. **Executive** — Board/leadership visibility
2. **Product team** — Daily operational decisions
3. **Growth team** — Experiment monitoring
4. **Engineering** — System health and performance
5. **Cross-functional** — Shared alignment

### Question 2: North Star

**Agent asks:** "What's your North Star Metric?"

(References `skills/strategy/north-star-metric/SKILL.md`)

### Question 3: Metric Selection

**Agent asks:** "For each metric layer, which metrics matter most?"

```markdown
**Dashboard Hierarchy:**

### Layer 1: North Star (1 metric)
- [NSM — the one number everyone watches]

### Layer 2: Input Metrics (3-5 metrics)
- [Metric that drives NSM — e.g., activation rate]
- [Metric that drives NSM — e.g., weekly engagement]
- [Metric that drives NSM — e.g., referral rate]

### Layer 3: Health Metrics (3-5 metrics)
- [Revenue/business health]
- [Technical health — errors, latency]
- [Customer health — NPS, support load]

### Layer 4: Experiment Metrics (variable)
- [Active experiment KPIs]
```

### Output: Dashboard Specification

```markdown
# Product Dashboard Specification

## Layout
| Row | Metric | Type | Alert Threshold |
|-----|--------|------|----------------|
| Hero | [NSM] | Big number + trend | If drops > [X%] |
| Row 1 | [Input Metric 1] | Line chart (7-day) | If below [threshold] |
| Row 1 | [Input Metric 2] | Line chart (7-day) | If below [threshold] |
| Row 2 | [Health Metric 1] | Gauge | Red if below [X] |
| Row 3 | [Experiment] | A/B comparison | If significance reached |

## Refresh Cadence
- Real-time: [Metrics that need live data]
- Daily: [Most metrics]
- Weekly: [Slower-moving metrics]

## Review Ritual
- **Daily standup:** Glance at Layer 1
- **Weekly review:** Analyze Layers 1-3
- **Monthly deep-dive:** Full analysis + action planning
```

---

## References

### Related Skills
- `skills/strategy/north-star-metric/SKILL.md` — NSM definition
- `skills/analytics/funnel-analysis/SKILL.md` — Funnel metrics
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — Business metrics

---

**Skill type:** Interactive
**Domain:** Analytics & Metrics
