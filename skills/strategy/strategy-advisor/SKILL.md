---
name: strategy-advisor
description: Help PMs choose and apply the right strategic framework for their situation — Porter's, Blue Ocean, Ansoff, platform, or growth strategy — through adaptive assessment.
type: interactive
domain: strategy
difficulty: advanced
estimated_time: "30-45 min"
prerequisites: ["positioning-statement"]
outputs: ["strategy-recommendation"]
triggers:
  - "Which strategy framework should I use"
  - "Help me choose a strategic approach"
  - "How should I think about product strategy"
  - "Strategic framework recommendation"
---

## Purpose

Help product managers choose the **right strategic framework** for their situation through adaptive assessment. Different strategic challenges require different frameworks — this advisor matches your context (growth stage, competitive dynamics, market maturity) to the most effective approach.

---

## Key Concepts

### Strategy Framework Landscape

| Framework | Best For | Core Question |
|-----------|----------|---------------|
| **Porter's Five Forces** | Competitive analysis | "How attractive is this market?" |
| **Blue Ocean** | Market creation | "Can we make competition irrelevant?" |
| **Ansoff Matrix** | Growth direction | "Existing vs. new markets/products?" |
| **Jobs-to-be-Done** | Innovation | "What job should we solve?" |
| **Platform Strategy** | Network effects | "Can we build a two-sided market?" |
| **Lean Strategy** | Validation | "What's the fastest way to learn?" |
| **Disruption Theory** | Market entry | "Are we disrupting from below?" |

---

## Application

### Question 1: Strategic Challenge

**Agent asks:** "What's the primary strategic challenge you're facing?"

**Options:**
1. **Entering a new market** — "We want to expand into a new segment/geography"
2. **Defending market position** — "Competitors are gaining ground"
3. **Creating a new category** — "Nothing like this exists yet"
4. **Growth plateau** — "Our growth has stalled"
5. **Platform ambitions** — "We want to build a marketplace/platform"
6. **Pivot evaluation** — "Should we change direction?"

---

### Question 2: Market Maturity

**Agent asks:** "How mature is the market you're operating in?"

**Options:**
1. **Nascent** — Few competitors, customers don't know they need this
2. **Growing** — Multiple players, customers understand the category
3. **Mature** — Established players, features converging, price competition
4. **Declining** — Market is shrinking or being disrupted

---

### Question 3: Competitive Position

**Agent asks:** "How strong is your current competitive position?"

**Options:**
1. **Market leader** — #1 or #2 in our segment
2. **Strong challenger** — Known player but not dominant
3. **Niche player** — Strong in a small segment
4. **New entrant** — Just entering this market
5. **Incumbent being disrupted** — Established but under threat

---

### Question 4: Resources Available

**Agent asks:** "What resources can you commit to strategic initiatives?"

**Options:**
1. **Bootstrapped** — Minimal budget, small team
2. **Funded but constrained** — Some investment but tight roadmap
3. **Well-resourced** — Strong budget and team for strategic bets
4. **Enterprise** — Large organization with multi-year planning

---

### Output: Strategy Recommendation

```markdown
# Strategic Framework Recommendation

**Based on your context:**
- Challenge: [From Q1]
- Market Maturity: [From Q2]
- Position: [From Q3]
- Resources: [From Q4]

## Recommended Framework: [Framework Name]

**Why this fits:**
- [Rationale tied to each context dimension]

**How to apply it:**

### Step 1: [First step]
[Guidance + reference to relevant skill]

### Step 2: [Second step]
[Guidance]

### Step 3: [Third step]
[Guidance]

## Alternative Framework
If [conditions change], consider [alternative framework] because [reason].

## Red Flags to Watch
- [Signal that this framework isn't working]
- [Signal to switch approaches]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Context Fit** | Generic recommendation | Matches some context | Matches all 4 dimensions |
| **Practicality** | Theory only | Steps listed | Steps + skill references + examples |
| **Alternatives** | None | Mentioned | Alternative with switching criteria |

---

## References

### Related Skills
- `skills/strategy/swot-analysis/SKILL.md` — Internal/external assessment
- `skills/strategy/pestel-analysis/SKILL.md` — External forces analysis
- `skills/strategy/business-model-canvas/SKILL.md` — Business model design
- `skills/strategy/product-strategy-session/SKILL.md` — Full strategy workflow

### External Frameworks
- Michael Porter, *Competitive Strategy* (1980)
- W. Chan Kim, *Blue Ocean Strategy* (2005)
- Clayton Christensen, *The Innovator's Dilemma* (1997)
- Igor Ansoff, *Corporate Strategy* (1965)

---

**Skill type:** Interactive
**Domain:** Strategy & Vision
