---
name: customer-journey-mapping-workshop
description: Facilitate a guided journey mapping session that walks through persona selection, stage-by-stage experience mapping, pain point identification, and opportunity prioritization.
type: interactive
domain: discovery
difficulty: intermediate
estimated_time: "45-60 min"
prerequisites: ["proto-persona"]
outputs: ["journey-map-document"]
triggers:
  - "Run a journey mapping workshop"
  - "Facilitate a customer journey session"
  - "Let's map the customer experience together"
---

## Purpose

Guide a team through creating a customer journey map step-by-step. This interactive skill asks adaptive questions to build a complete journey map — from persona selection through stage mapping, pain point identification, and opportunity prioritization.

---

## Key Concepts

### Workshop Flow

This workshop uses **6-8 adaptive turns** to build the journey map collaboratively:

1. Select & confirm the persona
2. Define the journey scope (start → end)
3. Map stages (actions, touchpoints)
4. Capture emotions and thoughts at each stage
5. Identify pain points and moments of truth
6. Prioritize improvement opportunities
7. Define next actions

### Facilitation Protocol

Use `skills/communication/workshop-facilitation/SKILL.md` as the interaction protocol:
- One question per turn with enumerated options
- Progress labels (e.g., "Stage 3/7: Pain Points")
- Context dump bypass: user can paste existing research to skip context questions
- Best guess mode: agent fills in reasonable defaults for fast iteration

---

## Application

### Turn 1: Select Persona

**Agent asks:** "Who is this journey map for? Choose an existing persona or describe one."

**Options:**
1. [If personas are available, list them]
2. "Let me describe the persona now"
3. "Use a generic user for now — we'll refine later"

---

### Turn 2: Define Scope

**Agent asks:** "What's the start and end point of this journey?"

**Options:**
1. **Full lifecycle** — First awareness through advocacy/churn
2. **Acquisition focused** — Discovery through first purchase
3. **Onboarding focused** — Sign-up through first value
4. **Retention focused** — Active use through renewal/churn
5. **Custom** — Define your own start and end points

---

### Turn 3-5: Map Each Stage

For each stage within scope, agent asks:

**Agent asks:** "Let's map **[Stage Name]**. What does [Persona] do here?"

Prompts for each stage:
- "What actions does [Persona] take?"
- "What channels or touchpoints are involved?"
- "What are they thinking at this moment?"
- "How are they feeling? (positive/neutral/frustrated/angry)"

---

### Turn 6: Pain Points & Moments of Truth

**Agent asks:** "Looking at the full journey, where are the biggest friction points?"

Prompts:
- "Which stage has the most drop-off or frustration?"
- "Are there any 'make or break' moments?"
- "Where does [Persona] consider abandoning the journey entirely?"

---

### Turn 7: Opportunities

**Agent asks:** "Based on the pain points, what are 3-5 opportunities to improve the experience?"

Agent ranks based on:
- Impact (high/medium/low)
- Effort (high/medium/low)
- Priority (recommended order)

---

### Output: Complete Journey Map

Agent generates a complete journey map document following the format in `skills/discovery/customer-journey-map/SKILL.md`.

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Persona Grounding** | Generic "user" | Named but vague | Specific persona with context |
| **Stage Coverage** | 1-2 stages only | Most stages | Full lifecycle with transitions |
| **Evidence Level** | All assumptions | Some data | Mix of data + tagged assumptions |
| **Pain Points** | Not identified | Listed but unranked | Ranked by severity + frequency |
| **Actionability** | No next steps | Generic improvements | Prioritized opportunities with owners |

---

## Common Pitfalls

### Pitfall 1: Workshop Without Data

**Fix:** Bring analytics, support tickets, and interview quotes. Pure-assumption maps are decorative, not useful.

### Pitfall 2: Only Mapping the Happy Path

**Fix:** Explicitly ask "Where does this break?" at each stage. Include failure paths and edge cases.

---

## References

### Related Skills
- `skills/discovery/customer-journey-map/SKILL.md` — Template and format guide
- `skills/discovery/proto-persona/SKILL.md` — Input: persona definition
- `skills/communication/workshop-facilitation/SKILL.md` — Facilitation protocol

---

**Skill type:** Interactive
**Domain:** Discovery & Research
