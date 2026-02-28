---
name: ab-test-design
description: Design rigorous A/B experiments with hypothesis, sample size, control/variant setup, statistical significance, and decision criteria — avoiding the common traps that make experiments useless.
type: component
domain: growth
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["epic-hypothesis"]
outputs: ["experiment-document"]
triggers:
  - "Design an A/B test"
  - "Set up an experiment"
  - "Should we A/B test this"
  - "Experiment design"
---

## Purpose

Design rigorous A/B experiments that produce **trustworthy, actionable results** — with clear hypothesis, proper sample sizing, correct control/variant setup, and pre-defined decision criteria. Avoids the common traps that make most experiments statistically meaningless.

---

## Application

### Experiment Design Template

```markdown
# Experiment: [Name]

## Hypothesis
**We believe that** [change]
**for** [user segment]
**will** [improve metric]
**because** [causal mechanism]

## Setup
- **Primary metric:** [What you're measuring]
- **Control:** [Current experience]
- **Variant:** [Changed experience]
- **Traffic split:** [50/50, unless good reason otherwise]
- **Segment:** [Who's included/excluded]

## Sample Size & Duration
- **MDE (minimum detectable effect):** [X% lift you care about]
- **Baseline conversion:** [Current rate]
- **Statistical significance:** [95% — standard]
- **Required sample size:** [Calculated]
- **Estimated duration:** [Days to reach sample size]

## Decision Criteria
- **Ship variant if:** [Primary metric improves by ≥X% with p<0.05]
- **Ship control if:** [No significant difference OR negative impact]
- **Extend if:** [Trending positive but not yet significant]
- **Guard rails:** [Metrics that must NOT regress]

## Analysis Plan
- **Primary:** [Metric + analysis method]
- **Secondary:** [Additional metrics to monitor]
- **Segmentation:** [Sub-groups to analyze]
```

### Traps to Avoid

| Trap | Problem | Fix |
|------|---------|-----|
| **Peeking** | Checking results daily | Wait for full sample size |
| **Multiple metrics** | Testing 10 metrics, one hits p<0.05 | Pre-declare primary metric |
| **Underpowered** | Too small a sample to detect real effects | Calculate sample size BEFORE launch |
| **Novelty effect** | New thing gets attention, not better | Let experiment run 2+ weeks |
| **Selection bias** | Non-random assignment | True random traffic split |

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Hypothesis** | No hypothesis | Vague | Specific with causal mechanism |
| **Sample Size** | "We'll run it a week" | Estimated | Calculated with MDE |
| **Decision Criteria** | "We'll see" | Ship/don't ship | Ship/extend/kill with guardrails |
| **Statistical Rigor** | No significance testing | P-value checked | Pre-registered analysis plan |

---

## References

### Related Skills
- `skills/planning/epic-hypothesis/SKILL.md` — Experiments test epic hypotheses
- `skills/analytics/funnel-analysis/SKILL.md` — Funnel data for baseline
- `skills/growth/activation-optimization/SKILL.md` — Common A/B test area

### External Frameworks
- Ron Kohavi, *Trustworthy Online Controlled Experiments* (2020)
- Evan Miller's A/B Test Sample Size Calculator

---

**Skill type:** Component
**Domain:** Growth & Optimization
