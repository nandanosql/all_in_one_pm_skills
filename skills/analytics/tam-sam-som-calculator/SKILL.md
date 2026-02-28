---
name: tam-sam-som-calculator
description: Guide PMs through calculating Total Addressable Market (TAM), Serviceable Addressable Market (SAM), and Serviceable Obtainable Market (SOM) using top-down and bottom-up approaches.
type: interactive
domain: analytics
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: []
outputs: ["market-sizing-document"]
triggers:
  - "Calculate our TAM SAM SOM"
  - "Market sizing"
  - "How big is our market"
  - "Total addressable market"
---

## Purpose

Guide PMs through calculating **TAM, SAM, and SOM** using both top-down and bottom-up approaches — producing defensible market size estimates for strategy, fundraising, and prioritization.

---

## Application

### Turn 1: Market Definition

**Agent asks:** "What market are you sizing?"
- Product/service
- Category
- Geographic scope
- Current vs. future market?

### Turn 2: Top-Down Approach

**Agent asks:** "Let's start with industry data."

```markdown
## Top-Down Market Sizing

### TAM (Total Addressable Market)
**Definition:** Total revenue opportunity if 100% market share
**Approach:** Industry report data × average revenue per customer
- Industry size: $[X]B (source: [Report])
- Relevant segment: [%] of total = $[X]B
- **TAM: $[X]B**

### SAM (Serviceable Addressable Market)
**Definition:** Portion of TAM our product can serve
**Filters applied:**
- Geography: [Countries/regions we serve]
- Company size: [Our target segment]
- Technology fit: [Who can actually use our product]
- **SAM: $[X]M** ([X]% of TAM)

### SOM (Serviceable Obtainable Market)
**Definition:** Realistic capture in 3-5 years
**Factors:**
- Current market share: [%]
- Growth rate: [% per year]
- Competitive intensity: [High/Med/Low]
- **SOM: $[X]M** ([X]% of SAM)
```

### Turn 3: Bottom-Up Validation

**Agent asks:** "Let's validate with bottom-up math."

```markdown
## Bottom-Up Validation

**Target customers:** [# potential customers matching our ICP]
**× Average revenue per customer:** $[X]/year
**× Expected penetration rate:** [X]%
**= Bottom-up SOM:** $[X]M

**Top-down vs Bottom-up comparison:**
- Top-down SOM: $[X]M
- Bottom-up SOM: $[X]M
- Delta: [%] — [Explanation of difference]
```

### Output

```markdown
# Market Sizing: [Product/Market]

| Metric | Value | Method |
|--------|-------|--------|
| **TAM** | $[X]B | Top-down from industry data |
| **SAM** | $[X]M | TAM filtered by segments we can serve |
| **SOM** | $[X]M | Bottom-up validated, 3-year target |

**Key assumptions:**
- [Assumption 1]
- [Assumption 2]

**Sensitivity:**
- If [assumption changes], SOM ranges from $[X]M to $[Y]M
```

---

## References

### Related Skills
- `skills/strategy/business-model-canvas/SKILL.md` — Revenue model context
- `skills/launch/gtm-strategy/SKILL.md` — Market segments
- `skills/analytics/business-health-diagnostic/SKILL.md` — Business health

---

**Skill type:** Interactive
**Domain:** Analytics & Metrics
