---
name: acquisition-channel-advisor
description: Evaluate and recommend customer acquisition channels based on product type, target audience, budget, and stage — covering organic, paid, referral, partnerships, and product-led growth.
type: interactive
domain: growth
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["positioning-statement"]
outputs: ["channel-recommendation"]
triggers:
  - "Which acquisition channels should we focus on"
  - "How do we acquire customers"
  - "Acquisition channel strategy"
  - "Where should we spend our marketing budget"
---

## Purpose

Evaluate and recommend **customer acquisition channels** based on product type, audience, budget, and stage — helping PMs focus limited resources on channels with the highest expected ROI.

---

## Application

### Turn 1: Product Context

**Agent asks:** "Tell me about your product and market."
- Product type? (B2B SaaS / B2C / Marketplace / Developer tool / etc.)
- Price point? (Free / <$50/mo / $50-500/mo / >$500/mo / Enterprise)
- Current stage? (Pre-launch / Early / Growing / Mature)

### Turn 2: Target Audience

**Agent asks:** "Where does your target audience spend time?"
- Where do they research solutions?
- What communities are they part of?
- What content do they consume?
- Are decisions individual or committee?

### Turn 3: Current Channels

**Agent asks:** "What have you tried and what do you know?"
- Current channels and their performance
- Budget constraints
- Team capabilities (content, sales, partnerships)

### Output: Channel Recommendation

```markdown
# Acquisition Channel Recommendation

## Recommended Channels (Priority Order)

### 🥇 Primary: [Channel Name]
- **Why:** [Fit with product/audience/stage]
- **Expected CAC:** $[Range]
- **Time to results:** [Weeks/months]
- **Getting started:** [First 3 actions]
- **Key metric:** [What to track]

### 🥈 Secondary: [Channel Name]
- **Why:** [Rationale]
- **Expected CAC:** $[Range]
- **Getting started:** [First 3 actions]

### 🥉 Experiment: [Channel Name]
- **Why worth testing:** [Rationale]
- **Minimum viable test:** [What to do]
- **Decision criteria:** [When to invest more / cut]

## Channels NOT Recommended (Yet)
| Channel | Why Not Now | Revisit When |
|---------|-----------|-------------|
| [Channel] | [Reason] | [Condition] |

## Channel Mix Budget
| Channel | % of Budget | Monthly Spend | Expected CAC |
|---------|------------|--------------|-------------|
| [Primary] | [%] | $[X] | $[X] |
| [Secondary] | [%] | $[X] | $[X] |
| [Experiment] | [%] | $[X] | $[X] |
```

---

## References

### Related Skills
- `skills/launch/gtm-strategy/SKILL.md` — GTM channel strategy
- `skills/growth/growth-model/SKILL.md` — Acquisition drives growth model
- `skills/analytics/saas-economics-efficiency-metrics/SKILL.md` — CAC measurement

### External Frameworks
- Gabriel Weinberg, *Traction* (2015) — 19 traction channels
- Brian Balfour, Channel-Model Fit

---

**Skill type:** Interactive
**Domain:** Growth & Optimization
