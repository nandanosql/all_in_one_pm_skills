---
name: win-loss-analysis
description: Guide structured win/loss analysis to understand why deals are won or lost. Captures patterns across competitive dynamics, buyer behavior, and product gaps to improve win rates.
type: interactive
domain: discovery
difficulty: advanced
estimated_time: "30-45 min"
prerequisites: ["competitive-battle-card"]
outputs: ["win-loss-report"]
triggers:
  - "Why do we win or lose deals"
  - "Analyze our competitive wins and losses"
  - "I need to understand our close rate"
  - "Run a win loss analysis"
---

## Purpose

Systematically analyze why deals are won or lost to identify patterns in **competitive dynamics, buyer decision-making, product gaps, and sales execution**. Produces actionable insights that improve win rates, inform product roadmap, and sharpen competitive positioning.

---

## Key Concepts

### Win/Loss Analysis Framework

| Dimension | What to Analyze |
|-----------|----------------|
| **Product** | Feature gaps, UX, integrations, performance |
| **Price** | Pricing model, perceived value, ROI |
| **Process** | Sales cycle, demo quality, responsiveness |
| **People** | Relationships, trust, champion quality |
| **Competition** | Who else was in the deal, how they positioned |

### When to Use This

- Win rate drops below target
- Entering a new market segment
- Before roadmap planning (what gaps cost us deals?)
- Quarterly competitive review

---

## Application

### Question 1: Analysis Scope

**Agent asks:** "What scope of deals should we analyze?"

**Options:**
1. **Recent losses only** — Last quarter's lost deals
2. **Recent wins only** — Last quarter's wins to replicate
3. **Both wins and losses** — Full picture (recommended)
4. **Specific competitor** — Deals where [competitor] was involved
5. **Specific segment** — Deals in [market/size] segment

---

### Question 2: Data Available

**Agent asks:** "What data do you have access to?"

**Options:**
1. **CRM data only** — Deal records, stage history, close reasons
2. **CRM + sales notes** — Deal records + rep commentary
3. **CRM + buyer interviews** — Post-decision buyer conversations
4. **Full stack** — CRM + sales notes + buyer interviews + competitor intel

---

### Question 3: Deal Details

**Agent asks:** "Let's analyze specific deals. For each deal, tell me:"

```markdown
| Deal | Outcome | Competitor | Deal Size | Sales Cycle | Close Reason |
|------|---------|-----------|-----------|-------------|-------------|
| [1] | Won/Lost | [Comp] | [$] | [Days] | [Reason] |
```

(Agent probes deeper on 2-3 most representative deals)

---

### Question 4: Pattern Detection

Agent analyzes the data and asks confirming questions:

**Agent says:** "I'm seeing these patterns. Do these resonate?"

```markdown
**Win Patterns:**
- [Pattern 1 — e.g., "We win when there's a technical champion"]
- [Pattern 2]

**Loss Patterns:**
- [Pattern 1 — e.g., "We lose when procurement leads the process"]
- [Pattern 2]

**Product Gaps Mentioned:**
- [Gap 1 — frequency, deal impact]
- [Gap 2]
```

---

### Output: Win/Loss Report

```markdown
# Win/Loss Analysis Report

**Period:** [Date range]
**Deals analyzed:** [Count]
**Win rate:** [%]

## Key Findings

### Why We Win (Top 3 Themes)
1. **[Theme]:** [Description + evidence] (appeared in X/Y deals)
2. **[Theme]:** [Description + evidence]
3. **[Theme]:** [Description + evidence]

### Why We Lose (Top 3 Themes)
1. **[Theme]:** [Description + evidence] (appeared in X/Y deals)
2. **[Theme]:** [Description + evidence]
3. **[Theme]:** [Description + evidence]

### Product Gaps Costing Us Deals
| Gap | Deals Affected | Revenue Impact | Competitor Has It? |
|-----|---------------|----------------|-------------------|
| [Gap] | [#] | [$] | [Y/N — who] |

### Competitive Dynamics
| Competitor | Deals Faced | Won | Lost | Win Rate vs. Them |
|-----------|------------|-----|------|------------------|
| [Comp A] | [#] | [#] | [#] | [%] |

## Recommendations
1. **Product:** [What to build/fix to close gaps]
2. **Sales:** [Process/positioning changes to improve win rate]
3. **Marketing:** [Messaging adjustments based on buyer feedback]

## Next Steps
- [ ] Share findings with Product team (roadmap input)
- [ ] Update battle cards based on new patterns
- [ ] Schedule follow-up analysis in [timeframe]
```

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Sample Size** | 1-2 deals | 3-5 deals | 10+ deals with statistical patterns |
| **Data Sources** | CRM only | CRM + rep notes | CRM + buyer interviews |
| **Pattern Validation** | Single anecdotes | Themes across deals | Quantified frequency per theme |
| **Actionability** | "We should improve" | Specific product gaps | Prioritized actions with owners |
| **Balance** | Only losses analyzed | Wins + losses separate | Wins + losses compared for patterns |

---

## Common Pitfalls

### Pitfall 1: Only Analyzing Losses

**Fix:** Wins have as much signal. Understanding *why* you win lets you replicate conditions and qualify better.

### Pitfall 2: Taking the Sales Rep's Word As Truth

**Fix:** Sales reps often attribute losses to price. Talk to the buyer directly — the real reason is usually different.

---

## References

### Related Skills
- `skills/discovery/competitive-battle-card/SKILL.md` — Update battle cards with findings
- `skills/discovery/company-research/SKILL.md` — Deep-dive on competitors in losses
- `skills/growth/acquisition-channel-advisor/SKILL.md` — Optimize channels based on win patterns

---

**Skill type:** Interactive
**Domain:** Discovery & Research
