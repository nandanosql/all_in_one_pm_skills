---
name: prioritization-advisor
description: Guide PMs in choosing the right prioritization framework — RICE, ICE, Kano, MoSCoW, Value vs Effort, Cost of Delay — by asking adaptive questions about product stage, team context, and data availability.
type: interactive
domain: planning
difficulty: intermediate
estimated_time: "15-25 min"
prerequisites: []
outputs: ["prioritization-recommendation", "scored-backlog"]
triggers:
  - "Which prioritization framework should I use"
  - "Help me prioritize my backlog"
  - "How should I decide what to build next"
  - "Prioritization framework recommendation"
---

## Purpose

Help PMs choose the **right prioritization framework** by asking adaptive questions about product stage, team context, decision-making needs, and data availability. Then guide implementation with templates and examples.

---

## Key Concepts

### Framework Landscape

| Framework | Best For | Data Needed |
|-----------|----------|------------|
| **RICE** | Data-driven teams with metrics | High — need reach, impact data |
| **ICE** | Fast gut-check scoring | Low — subjective scores |
| **Value vs. Effort** | Quick visual prioritization | Low — 2x2 matrix |
| **Kano** | Feature delight classification | Medium — customer surveys |
| **MoSCoW** | Forcing hard scope decisions | Low — stakeholder input |
| **Cost of Delay** | Time-sensitive decisions | Medium — urgency data |
| **Weighted Scoring** | Complex multi-criteria decisions | Medium — stakeholder alignment |
| **Opportunity Scoring** | Customer-centric prioritization | Medium — importance/satisfaction gaps |

---

## Application

### Question 1: Product Stage

**Agent asks:** "What stage is your product in?"

1. **Pre-PMF** — Searching for product-market fit, experimenting rapidly
2. **Early PMF, scaling** — Found fit, growing, adding features
3. **Mature product** — Established, optimizing, incremental improvements
4. **Multi-product/platform** — Portfolio, cross-product dependencies

### Question 2: Team Context

**Agent asks:** "What's your team and stakeholder environment?"

1. **Small team, limited resources** — Need simple, fast framework
2. **Cross-functional, aligned** — Can use data-driven frameworks
3. **Multiple stakeholders, misaligned** — Need consensus-building
4. **Large org, complex dependencies** — Need coordination framework

### Question 3: Decision Challenge

**Agent asks:** "What's the primary prioritization challenge?"

1. **Too many ideas** — Need to narrow to top 10
2. **Stakeholder disagreement** — Need transparent process
3. **Lack of data-driven decisions** — Want metrics-based scoring
4. **Strategic vs. tactical tradeoffs** — Balancing long vs. short term

### Question 4: Data Availability

**Agent asks:** "How much data do you have?"

1. **Minimal** — New product, few metrics
2. **Some** — Basic analytics, some feedback
3. **Rich** — Usage metrics, A/B tests, surveys

### Output: Framework Recommendation + Implementation Guide

```markdown
# Prioritization Framework Recommendation

**Context:** [Summary from Q1-Q4]

## Recommended: [Framework Name]

**Why it fits:** [Rationale tied to each answer]

## Implementation

### Step 1: [Setup]
[Detailed guidance]

### Step 2: [Scoring/Evaluation]
[Template with example]

### Step 3: [Review and Decide]
[How to use the output]

## Scoring Template
| Item | [Criteria 1] | [Criteria 2] | [Criteria 3] | Score |
|------|-------------|-------------|-------------|-------|
| [Feature A] | [#] | [#] | [#] | [Total] |

## Alternative: [Second choice framework]
Consider if [condition].
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Context Fit** | Generic recommendation | Matches 1-2 dimensions | Matches all 4 context dimensions |
| **Actionability** | Framework name only | Steps listed | Full template + scored example |
| **Alternatives** | None | Mentioned | With switching criteria |

---

## References

### Related Skills
- `skills/planning/epic-hypothesis/SKILL.md` — Items to prioritize
- `skills/planning/roadmap-planning/SKILL.md` — Prioritization feeds the roadmap
- `skills/planning/now-next-later-roadmap/SKILL.md` — Output format

### External Frameworks
- Sean Ellis, RICE; Intercom, *Prioritization* articles

---

**Skill type:** Interactive
**Domain:** Planning & Prioritization
