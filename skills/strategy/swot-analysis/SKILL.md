---
name: swot-analysis
description: Conduct a structured SWOT analysis — Strengths, Weaknesses, Opportunities, Threats — that connects internal capabilities to external forces for strategic decision-making.
type: component
domain: strategy
difficulty: beginner
estimated_time: "20-25 min"
prerequisites: []
outputs: ["swot-analysis-document"]
triggers:
  - "Run a SWOT analysis"
  - "What are our strengths and weaknesses"
  - "Strategic assessment of our product"
  - "Where are the opportunities and threats"
---

## Purpose

Conduct a structured analysis of your product's **internal strengths/weaknesses** and **external opportunities/threats** to inform strategic decisions. SWOT is simple to run but powerful when you connect the quadrants to concrete actions.

---

## Key Concepts

### The SWOT Matrix

```
         HELPFUL              HARMFUL
       ┌─────────────┬──────────────┐
   I   │ STRENGTHS   │ WEAKNESSES   │
   N   │             │              │
   T   │ What we     │ Where we     │
   E   │ do well     │ fall short   │
   R   │             │              │
   N   ├─────────────┼──────────────┤
   A   │             │              │
   L   │ What we     │ What could   │
       │ can exploit │ hurt us      │
   E   │             │              │
   X   │ OPPORTUNI-  │ THREATS      │
   T   │ TIES        │              │
       └─────────────┴──────────────┘
```

### The TOWS Extension (Making SWOT Actionable)

| Combination | Strategy |
|-------------|----------|
| **S-O** (Strength + Opportunity) | Leverage strengths to capture opportunities |
| **W-O** (Weakness + Opportunity) | Fix weaknesses to capture opportunities |
| **S-T** (Strength + Threat) | Use strengths to defend against threats |
| **W-T** (Weakness + Threat) | Mitigate weaknesses that amplify threats |

---

## Application

### Step 1: Fill the Quadrants

```markdown
## SWOT Analysis: [Product/Feature Name]
**Date:** [Date]

### Strengths (Internal + Helpful)
1. [S1: What competitive advantage do you have?]
2. [S2: What do customers praise?]
3. [S3: What resources/expertise do you uniquely have?]

### Weaknesses (Internal + Harmful)
1. [W1: Where do you consistently lose?]
2. [W2: What do customers complain about?]
3. [W3: What capabilities are you missing?]

### Opportunities (External + Helpful)
1. [O1: What market trends favor you?]
2. [O2: What competitor gaps can you exploit?]
3. [O3: What new segments are emerging?]

### Threats (External + Harmful)
1. [T1: What competitors are gaining ground?]
2. [T2: What regulations could impact you?]
3. [T3: What technology shifts could disrupt you?]
```

### Step 2: Generate TOWS Strategies

```markdown
## Strategic Actions

### S-O Strategies (Leverage)
- Use [Strength] to capture [Opportunity]: [Specific action]

### W-O Strategies (Improve)
- Fix [Weakness] to capture [Opportunity]: [Specific action]

### S-T Strategies (Defend)
- Use [Strength] to counter [Threat]: [Specific action]

### W-T Strategies (Avoid)
- Address [Weakness] before [Threat] amplifies it: [Specific action]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Balance** | Only S and O | All 4, but S>W | All 4 roughly equal (honest) |
| **Specificity** | Generic ("good team") | Named but vague | Evidence-backed specifics |
| **External Grounding** | Opinions only | Some market context | PESTEL + competitive intel |
| **Actionability** | Matrix only | SWOT only | SWOT + TOWS strategies |
| **Honesty** | Weaknesses hidden | Acknowledged but softened | Unflinching self-assessment |

---

## Common Pitfalls

### Pitfall 1: Strengths Outnumber Weaknesses 5:1

**Fix:** If you can't list as many weaknesses as strengths, you're doing it wrong. The value is in the honest assessment.

### Pitfall 2: SWOT Without Action

**Fix:** SWOT without TOWS strategies is just a list. Always generate strategic actions by connecting quadrants.

---

## References

### Related Skills
- `skills/strategy/pestel-analysis/SKILL.md` — External analysis feeds O and T quadrants
- `skills/discovery/company-research/SKILL.md` — Competitor research for threats
- `skills/strategy/positioning-statement/SKILL.md` — Strengths inform positioning

---

**Skill type:** Component
**Domain:** Strategy & Vision
