---
name: data-storytelling-advisor
description: Transform raw data and charts into compelling narratives — using the Situation-Complication-Resolution framework to make data actionable and persuasive for stakeholders.
type: interactive
domain: analytics
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: []
outputs: ["data-narrative"]
triggers:
  - "Help me tell a story with this data"
  - "Make this data compelling"
  - "Data storytelling"
  - "Present data to stakeholders"
---

## Purpose

Transform raw data into **compelling narratives** that drive decisions — using storytelling frameworks to make data actionable and persuasive instead of just informational.

---

## Application

### Turn 1: The Data

**Agent asks:** "What data do you have and who's the audience?"
- What metrics/data are you presenting?
- Who's the audience? (Exec / Team / Board / External)
- What decision should this data inform?

### Turn 2: Find the Story

**Agent asks:** "Let me help find the narrative in this data."

```markdown
## Situation-Complication-Resolution Framework

### Situation (Context)
"Here's where we are..."
[Current state — set the baseline]

### Complication (Tension)
"But here's what's changing/threatening/surprising..."
[The trend, gap, or anomaly that creates tension]

### Resolution (Recommendation)
"So here's what we should do..."
[The action the data supports]
```

### Turn 3: Build the Narrative

```markdown
## Data Story: [Title — headline, not label]

### The Headline
[One sentence: the insight, not the metric]
- ❌ "Q3 Churn Rate: 8.2%"
- ✅ "We're losing $180K/mo to preventable churn — here's how to fix it"

### The Context (1 slide/paragraph)
[Baseline + what we expected]

### The Insight (1-2 slides/paragraphs)
[What the data shows + why it matters]
[Visualizations that support the insight]

### The "So What" (1 slide/paragraph)
[What this means for the business/user]

### The Ask (1 slide/paragraph)
[Specific action or decision requested]
```

### Data Visualization Rules

| Do | Don't |
|----|-------|
| Title charts with the insight | Title with the metric name |
| Use color to highlight the story | Use rainbow colors |
| Show comparison (before/after, us/them) | Show standalone numbers |
| Use the simplest chart type | Use 3D pie charts ever |
| Annotate inflection points | Let the reader guess |

---

## References

### Related Skills
- `skills/communication/executive-presentation/SKILL.md` — Present data stories
- `skills/analytics/metrics-dashboard-design/SKILL.md` — Dashboard design
- `skills/analytics/funnel-analysis/SKILL.md` — Funnel data to story

### External Frameworks
- Cole Nussbaumer Knaflic, *Storytelling with Data*
- Barbara Minto, Pyramid Principle (SCR)

---

**Skill type:** Interactive
**Domain:** Analytics & Metrics
