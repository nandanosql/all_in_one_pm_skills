---
name: pol-probe-advisor
description: Guide PMs through running and interpreting a Sean Ellis PMF survey — from survey distribution to segmented analysis and action planning based on results.
type: interactive
domain: growth
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["pol-probe"]
outputs: ["pmf-action-plan"]
triggers:
  - "Help me run a PMF survey"
  - "Interpret our Sean Ellis results"
  - "PMF survey advisor"
  - "What should I do with our PMF score"
---

## Purpose

Guide PMs through running and interpreting a PMF survey — from **distribution strategy to segmented analysis and action planning** based on the Sean Ellis "very disappointed" score.

---

## Application

### Turn 1: Survey Setup

**Agent asks:** "Have you run the survey yet, or are you planning to?"

If planning → Guide setup (sample, distribution, timing)
If results ready → Skip to analysis

### Turn 2: Results Input

**Agent asks:** "What were your results?"
- Sample size
- "Very disappointed" %
- "Somewhat disappointed" %
- "Not disappointed" %
- Open-text themes

### Turn 3: Interpretation

```markdown
## PMF Score: [X%] "Very Disappointed"

### Interpretation
- **≥40%:** 🟢 Strong PMF — Focus on scaling
- **25-40%:** 🟡 Getting there — Focus on improving core experience
- **<25%:** 🔴 Not yet — Focus on discovery, not growth

### Segment Analysis
**Who are the "Very Disappointed" users?**
- [Common traits: role, company size, use case]
- [What they value most (from Q2)]

**Who are the "Not Disappointed" users?**
- [Common traits — these are NOT your ICP]
- [Why they don't care]
```

### Turn 4: Action Plan

```markdown
## Recommended Actions

### If 🟢 Strong PMF (>40%)
1. Double down on your ICP (the "Very Disappointed" segment)
2. Invest in acquisition channels that reach this segment
3. Build features that deepen value for this segment

### If 🟡 Getting There (25-40%)
1. Interview "Somewhat Disappointed" users — what's missing?
2. Narrow your positioning to the "Very Disappointed" segment
3. Build the features that would make "Somewhat" → "Very"

### If 🔴 Not Yet (<25%)
1. Interview "Very Disappointed" users — understand their use case deeply
2. Pivot positioning to match their needs
3. Do NOT invest in growth — invest in discovery
```

---

## References

### Related Skills
- `skills/growth/pol-probe/SKILL.md` — Survey template
- `skills/growth/retention-deep-dive/SKILL.md` — Retention by PMF segment
- `skills/strategy/positioning-statement/SKILL.md` — Reposition based on PMF

---

**Skill type:** Interactive
**Domain:** Growth & Optimization
