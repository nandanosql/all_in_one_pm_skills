---
name: pol-probe
description: Evaluate product-market fit using Sean Ellis' "Product of Love" approach — measuring user disappointment, must-have percentage, and emotional attachment to identify PMF strength.
type: component
domain: growth
difficulty: intermediate
estimated_time: "15-20 min"
prerequisites: ["survey-design"]
outputs: ["pmf-assessment"]
triggers:
  - "Do we have product-market fit"
  - "PMF survey"
  - "Sean Ellis test"
  - "How disappointed would users be"
---

## Purpose

Evaluate product-market fit using Sean Ellis' approach — measuring the **"very disappointed" threshold** and emotional attachment to quantify PMF strength and identify what makes your product a must-have.

---

## Application

### PMF Survey Template

```markdown
# Product-Market Fit Survey

## Core Questions

### Q1: The Sean Ellis Test
"How would you feel if you could no longer use [Product Name]?"
- Very disappointed
- Somewhat disappointed
- Not disappointed
- I no longer use [Product Name]

### Q2: Must-Have Drill-Down
"What is the primary benefit you receive from [Product Name]?"
[Open text]

### Q3: Who Benefits Most
"What type of person do you think would benefit most from [Product Name]?"
[Open text]

### Q4: Improvement
"How can we improve [Product Name] for you?"
[Open text]

### Q5: Alternative
"What would you use as an alternative if [Product Name] were no longer available?"
[Open text]
```

### Analysis Template

```markdown
# PMF Assessment: [Product Name]

**Survey Date:** [Date]
**Responses:** [N]

## Sean Ellis Score
| Response | Count | % |
|----------|-------|---|
| Very disappointed | [#] | [%] ← **THIS IS YOUR PMF SCORE** |
| Somewhat disappointed | [#] | [%] |
| Not disappointed | [#] | [%] |

**Benchmark:** ≥40% "Very disappointed" = strong PMF

## PMF Health: [🟢 Strong (>40%) | 🟡 Getting there (25-40%) | 🔴 Not yet (<25%)]

## Key Insights

### Who loves us most?
[Segment analysis of "Very disappointed" respondents]

### Core value (from Q2)
[Top themes from must-have benefit answers]

### Must-have persona (from Q3)
[Who do they say benefits most? This is your ICP.]

### Alternatives (from Q5)
[What they'd switch to — this is your competition]

## Recommendations
1. **Double down on:** [What the "very disappointed" segment values most]
2. **ICP focus:** [Target the segment with highest PMF score]
3. **Improve:** [Themes from improvement feedback]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Sample** | <20 responses | 20-50 responses | >50 from active users |
| **Segmentation** | Overall score only | By plan/tier | By behavior segment |
| **Analysis** | Score only | Score + themes | Score + segments + actions |

---

## References

### Related Skills
- `skills/growth/retention-deep-dive/SKILL.md` — PMF drives retention
- `skills/growth/pol-probe-advisor/SKILL.md` — Interactive assessment
- `skills/discovery/survey-design/SKILL.md` — Survey methodology

### External Frameworks
- Sean Ellis, *Hacking Growth* (2017)
- Rahul Vohra (Superhuman), PMF Engine

---

**Skill type:** Component
**Domain:** Growth & Optimization
