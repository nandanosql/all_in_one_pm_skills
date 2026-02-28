---
name: feature-investment-advisor
description: Evaluate whether to invest in, iterate on, or sunset existing features — using adoption data, effort costs, and strategic alignment to make rational investment decisions.
type: interactive
domain: growth
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["funnel-analysis"]
outputs: ["feature-investment-recommendation"]
triggers:
  - "Should we invest more in this feature"
  - "Is this feature worth keeping"
  - "Feature investment analysis"
  - "Should we sunset this feature"
---

## Purpose

Evaluate whether to **invest more, iterate on, or sunset** existing features — using adoption data, engineering costs, and strategic alignment to make rational feature portfolio decisions.

---

## Application

### Turn 1: Feature Context

**Agent asks:** "Which feature are you evaluating? Tell me about it."
- Feature name and purpose
- When it launched
- Target user segment

### Turn 2: Adoption Data

**Agent asks:** "What do the numbers say?"
- % of users who use this feature (adoption)
- Frequency of use (daily/weekly/monthly)
- Impact on retention (do users who use it retain better?)
- Revenue attribution (does it drive upgrades?)
- Support load (does it generate tickets?)

### Turn 3: Investment Assessment

**Agent asks:** "What does it cost to maintain and improve?"
- Engineering time spent on maintenance
- Bug volume
- Requested improvements backlog
- Competitive necessity (do competitors have it?)

### Output: Investment Recommendation

```markdown
# Feature Investment Assessment: [Feature Name]

## Scorecard
| Dimension | Score (1-5) | Evidence |
|-----------|-----------|---------|
| Adoption | [#] | [% users, frequency] |
| Retention Impact | [#] | [Cohort comparison] |
| Revenue Impact | [#] | [Upgrade correlation] |
| Strategic Alignment | [#] | [Fits current strategy?] |
| Maintenance Cost | [#] | [Eng hours/sprint] |
| **Total** | **[#/25]** | |

## Recommendation: [Invest / Iterate / Maintain / Sunset]

### If Invest (Score >18)
- [ ] Allocate [X] sprints for improvement
- [ ] Target metric: [Increase adoption from X% to Y%]

### If Iterate (Score 12-18)
- [ ] Run [specific experiment] to test improvement
- [ ] Revisit in [X weeks]

### If Maintain (Score 8-12)
- [ ] Bug fixes only, no new investment
- [ ] Monitor for decline

### If Sunset (Score <8)
- [ ] Plan EOL communication
- [ ] Migrate users to alternative
- [ ] Use `skills/launch/eol-message/SKILL.md`
```

---

## References

### Related Skills
- `skills/analytics/funnel-analysis/SKILL.md` — Usage data
- `skills/growth/retention-deep-dive/SKILL.md` — Retention impact
- `skills/launch/eol-message/SKILL.md` — If sunsetted

---

**Skill type:** Interactive
**Domain:** Growth & Optimization
