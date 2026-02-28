---
name: company-research
description: Conduct deep-dive competitor or company analysis covering business model, market position, product strategy, strengths/weaknesses, and strategic implications for your product.
type: component
domain: discovery
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: []
outputs: ["company-research-brief"]
triggers:
  - "Research a competitor"
  - "Deep dive on a company"
  - "Analyze a competitor's product"
  - "Competitive intelligence"
---

## Purpose

Conduct a structured deep-dive analysis of a competitor or company covering their **business model, market position, product strategy, and strategic implications** for your own product decisions. Produces a reusable research brief that feeds into positioning, competitive battle cards, and strategy sessions.

---

## Key Concepts

### Research Framework

| Layer | What to Analyze |
|-------|----------------|
| **Business Model** | Revenue model, pricing, target segments, GTM |
| **Product** | Core features, UX quality, platform/integrations |
| **Market Position** | Market share, brand perception, growth trajectory |
| **Strategy** | Where they're investing, what they're saying, what they're *not* saying |
| **Implications** | What this means for YOUR product decisions |

### Anti-Patterns

- **Not opinion:** Back claims with evidence (public filings, product teardowns, reviews)
- **Not static:** Companies change — date your research and revisit quarterly
- **Not exhaustive:** Focus on what's strategically relevant to YOUR decisions

---

## Application

### Step 1: Company Overview

```markdown
## Company Research: [Company Name]
**Date:** [YYYY-MM-DD]
**Researcher:** [Name]
**Purpose:** [Why we're researching this company]

### Overview
- **Founded:** [Year]
- **Headquarters:** [Location]
- **Employees:** [Count]
- **Funding/Revenue:** [Stage, amount, or public revenue]
- **Target Market:** [Primary segments]
```

### Step 2: Business Model Analysis

```markdown
### Business Model
- **Revenue model:** [SaaS, marketplace, usage-based, etc.]
- **Pricing tiers:** [Free / Starter / Pro / Enterprise — key price points]
- **Primary buyer:** [Who signs the check]
- **Sales motion:** [Self-serve, inside sales, enterprise sales]
- **GTM channels:** [Content, PLG, outbound, partnerships]
```

### Step 3: Product Analysis

```markdown
### Product
- **Core value prop:** [One sentence]
- **Key features:** [Top 5 differentiating features]
- **Platform:** [Web, mobile, desktop, API]
- **Integrations:** [Key integrations]
- **UX quality:** [Assessment: excellent / good / functional / poor]
- **Recent launches:** [Last 2-3 major releases]
```

### Step 4: Strengths & Weaknesses

```markdown
### SWOT Snapshot
| Strengths | Weaknesses |
|-----------|------------|
| [S1] | [W1] |
| [S2] | [W2] |

| Opportunities | Threats |
|---------------|---------|
| [O1] | [T1] |
| [O2] | [T2] |
```

### Step 5: Strategic Implications

```markdown
### What This Means for Us
- **Threat level:** [High / Medium / Low]
- **Where they beat us:** [Specific areas]
- **Where we beat them:** [Specific areas]
- **Strategic response:** [What we should do differently]
- **Watch signals:** [What to monitor going forward]
```

---

## Examples

### ✅ Good Example

```markdown
## Company Research: Notion
**Date:** 2026-02-15 | **Purpose:** Evaluate overlap with our PM documentation tool

### Business Model
- Revenue: ~$10B valuation (2024), SaaS subscription
- Pricing: Free (limited), Plus ($10/mo), Business ($18/mo), Enterprise (custom)
- Sales: PLG-driven with emerging enterprise sales

### Strategic Implications
- **Threat level:** Medium — overlapping in documentation, but not PM-specific workflows
- **Where they beat us:** General-purpose flexibility, brand awareness, template marketplace
- **Where we beat them:** Purpose-built PM workflows, deeper analytics, better integrations
- **Response:** Double down on PM-specific value; don't try to out-Notion Notion
```

### ❌ Bad Example

```markdown
Notion is a popular tool. They have lots of users. We should watch them.
```

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Evidence** | All opinion | Some sourced data | Public data + product teardown |
| **Business Model** | Not analyzed | Revenue model only | Full go-to-market picture |
| **Product Analysis** | Feature list only | Features + UX assessment | Features + UX + trajectory |
| **Strategic Implications** | None | Generic observations | Specific, actionable for our product |
| **Recency** | Undated | Dated but stale | Current + watch signals |

---

## Common Pitfalls

### Pitfall 1: Feature Comparison Without Strategy

**Symptom:** Side-by-side feature checklist with no "so what?"

**Fix:** Features are table stakes. Analyze *strategy* — where are they investing, and what does that tell you about where the market is going?

### Pitfall 2: Ignoring Weak Signals

**Symptom:** Only analyzing public announcements.

**Fix:** Look at job postings (what they're hiring for), GitHub activity, patent filings, conference talks. These reveal future direction.

---

## References

### Related Skills
- `skills/discovery/competitive-battle-card/SKILL.md` — Distill research into a sales-ready battle card
- `skills/strategy/swot-analysis/SKILL.md` — Full SWOT framework
- `skills/strategy/positioning-statement/SKILL.md` — Position against competitors

---

**Skill type:** Component
**Domain:** Discovery & Research
