---
name: pestel-analysis
description: Analyze external macro-environment factors — Political, Economic, Social, Technological, Environmental, Legal — that could impact your product strategy and market decisions.
type: component
domain: strategy
difficulty: intermediate
estimated_time: "25-35 min"
prerequisites: []
outputs: ["pestel-analysis-document"]
triggers:
  - "Analyze external factors affecting our product"
  - "Run a PESTEL analysis"
  - "What macro trends should we consider"
  - "External environment analysis"
---

## Purpose

Systematically analyze the **macro-environment factors** that could impact your product strategy. PESTEL covers six dimensions: Political, Economic, Social, Technological, Environmental, and Legal — ensuring you don't miss external forces that could create opportunities or threats.

---

## Key Concepts

### The PESTEL Framework

| Factor | What to Analyze | PM Impact |
|--------|----------------|-----------|
| **Political** | Government policy, trade, regulation, stability | Market access, compliance costs |
| **Economic** | Growth, inflation, exchange rates, consumer spending | Pricing, demand, budget cycles |
| **Social** | Demographics, culture, lifestyle trends, attitudes | User behavior, market sizing |
| **Technological** | Innovation, automation, R&D, adoption curves | Build vs. buy, competitive moats |
| **Environmental** | Sustainability, climate, energy, ESG | Product requirements, brand risk |
| **Legal** | Privacy laws, IP, labor, industry-specific regulations | Compliance, feature constraints |

---

## Application

### For Each Factor

```markdown
## [Factor]: [Political / Economic / Social / Technological / Environmental / Legal]

**Current State:**
- [Key fact or trend]

**Direction:** [Increasing / Stable / Decreasing]

**Impact on Our Product:**
- [Specific implication]

**Time Horizon:** [Immediate / 1-2 years / 3-5 years]

**Risk Level:** [High / Medium / Low]

**Action Required:**
- [ ] [Specific response or monitoring action]
```

### Summary Matrix

```markdown
| Factor | Key Trend | Impact | Risk | Action |
|--------|-----------|--------|------|--------|
| Political | [Trend] | [H/M/L] | [H/M/L] | [Action] |
| Economic | [Trend] | [H/M/L] | [H/M/L] | [Action] |
| Social | [Trend] | [H/M/L] | [H/M/L] | [Action] |
| Technological | [Trend] | [H/M/L] | [H/M/L] | [Action] |
| Environmental | [Trend] | [H/M/L] | [H/M/L] | [Action] |
| Legal | [Trend] | [H/M/L] | [H/M/L] | [Action] |
```

---

## Examples

### ✅ Good Example (Technology Factor)

```markdown
## Technological: AI/LLM Integration Becoming Table Stakes

**Current State:** 78% of B2B SaaS products announced AI features in 2025.
Enterprise buyers now expect AI-assisted workflows as standard.

**Direction:** Accelerating rapidly

**Impact:** Our product needs AI-powered features within 2 quarters or we'll 
be perceived as legacy. Key opportunity: AI for automated report generation 
(aligns with core user pain point).

**Risk Level:** High (competitive threat if we don't act)

**Action:**
- [ ] Assess top 3 AI integration opportunities by March
- [ ] Ship MVP AI feature by Q3
```

### ❌ Bad Example

```markdown
## Technology: Technology is changing fast. We should keep up.
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Coverage** | 1-2 factors | 4-5 factors | All 6 factors |
| **Specificity** | Generic observations | Trends named | Data-backed with sources |
| **Actions** | None | "Monitor" | Specific, time-bound actions |
| **Relevance** | Academic exercise | Somewhat connected to strategy | Directly tied to product decisions |
| **Time Horizons** | Not considered | Single horizon | Short + medium + long term |

---

## Common Pitfalls

### Pitfall 1: Analysis Without Action

**Fix:** Every factor should end with a concrete action. If there's no action, it's decoration.

### Pitfall 2: Missing "So What?"

**Fix:** Always connect to your product: "This means we need to [specific change]."

---

## References

### Related Skills
- `skills/strategy/swot-analysis/SKILL.md` — PESTEL feeds the external half of SWOT
- `skills/strategy/positioning-statement/SKILL.md` — External context shapes positioning
- `skills/discovery/company-research/SKILL.md` — Competitor response to same external forces

---

**Skill type:** Component
**Domain:** Strategy & Vision
