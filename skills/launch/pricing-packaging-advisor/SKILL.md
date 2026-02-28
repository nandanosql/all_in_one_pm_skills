---
name: pricing-packaging-advisor
description: Guide pricing and packaging decisions — choosing a pricing model, setting price points, designing tier structure, and validating willingness-to-pay through adaptive assessment.
type: interactive
domain: launch
difficulty: advanced
estimated_time: "30-45 min"
prerequisites: ["positioning-statement", "business-model-canvas"]
outputs: ["pricing-recommendation"]
triggers:
  - "How should we price this"
  - "Design our pricing tiers"
  - "Pricing strategy"
  - "What should we charge"
---

## Purpose

Guide pricing and packaging decisions through adaptive assessment — choosing the right **pricing model, setting price points, designing tier structure**, and planning validation. Because pricing is the most impactful lever most PMs never touch.

---

## Application

### Question 1: Pricing Model

**Agent asks:** "What type of value does your product deliver?"

1. **Seat-based** — Value scales with team size
2. **Usage-based** — Value scales with consumption
3. **Outcome-based** — Value scales with results achieved
4. **Feature-gated** — Different capabilities at different tiers
5. **Freemium** — Free base + premium upgrades
6. **Hybrid** — Combination of above

### Question 2: Value Metric

**Agent asks:** "What's the most natural unit your customer associates with value?"

(e.g., per user, per transaction, per GB, per report generated)

### Question 3: Competitive Landscape

**Agent asks:** "What do competitors charge?"

| Competitor | Model | Price Range | Differentiation |
|-----------|-------|------------|----------------|
| [Comp 1] | [Model] | [$ range] | [How they differ] |

### Question 4: Target Segments

**Agent asks:** "How many segments/tiers do you need?"

1. **One tier** — Simple, single product
2. **Good/Better/Best** — Classic 3-tier
3. **Free + Paid** — Freemium model
4. **Custom only** — Enterprise pricing

### Output: Pricing Recommendation

```markdown
# Pricing Recommendation: [Product Name]

## Recommended Model: [Model Type]
**Value metric:** [Unit of value]
**Rationale:** [Why this model fits]

## Tier Structure

| | Free | Starter | Pro | Enterprise |
|--|------|---------|-----|-----------|
| **Price** | $0 | $XX/mo | $XX/mo | Custom |
| **Target** | [Who] | [Who] | [Who] | [Who] |
| **[Feature 1]** | ✅ Limited | ✅ | ✅ | ✅ |
| **[Feature 2]** | ❌ | ✅ | ✅ | ✅ |
| **[Feature 3]** | ❌ | ❌ | ✅ | ✅ |
| **[Feature 4]** | ❌ | ❌ | ❌ | ✅ |

## Validation Plan
1. **Van Westendorp survey** — Test price sensitivity with target users
2. **Conjoint analysis** — Test feature/price tradeoffs
3. **A/B test** — Test 2 price points with real conversion data

## Risks
- [Risk 1 + mitigation]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Model Fit** | Copied competitor | Matches product somewhat | Aligned to value delivery |
| **Segments** | One-size-fits-all | Basic tiers | Segment-matched tiers |
| **Validation** | Gut feel | Competitor benchmarking | Customer research + testing |
| **Packaging** | All features everywhere | Some gating | Strategic feature gating |

---

## References

### Related Skills
- `skills/strategy/business-model-canvas/SKILL.md` — Revenue model context
- `skills/strategy/positioning-statement/SKILL.md` — Value prop drives pricing
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — Unit economics

### External Frameworks
- Patrick Campbell (ProfitWell), Pricing methodology
- Van Westendorp Price Sensitivity Meter

---

**Skill type:** Interactive
**Domain:** Launch & GTM
