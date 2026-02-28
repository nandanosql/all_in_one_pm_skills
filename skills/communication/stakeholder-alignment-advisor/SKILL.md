---
name: stakeholder-alignment-advisor
description: Diagnose and resolve stakeholder misalignment — identifying root causes of disagreement, finding shared interests, and designing alignment strategies through structured conversation.
type: interactive
domain: communication
difficulty: advanced
estimated_time: "20-30 min"
prerequisites: ["stakeholder-map"]
outputs: ["alignment-strategy"]
triggers:
  - "My stakeholders are misaligned"
  - "How do I get everyone on the same page"
  - "Stakeholder alignment"
  - "People disagree on the direction"
---

## Purpose

Diagnose and resolve stakeholder misalignment — identifying **root causes of disagreement**, finding shared interests, and designing alignment strategies to get everyone pulling in the same direction.

---

## Application

### Turn 1: The Misalignment

**Agent asks:** "What's the misalignment? Who disagrees with whom about what?"
- Topic of disagreement
- Key stakeholders and their positions
- How long has this been misaligned?
- What's the impact of staying misaligned?

### Turn 2: Root Cause Analysis

**Agent classifies the misalignment type:**

| Type | Signal | Approach |
|------|--------|---------|
| **Information asymmetry** | People have different facts | Share data; single source of truth |
| **Priority conflict** | Different goals/OKRs | Escalate to shared executive |
| **Values/philosophy** | Different beliefs about what matters | Find shared principle, agree to disagree on details |
| **Personal/political** | Relationship or turf issues | Build 1:1 trust first |
| **Resource scarcity** | Fighting over same resources | Expand the pie or force a tradeoff |

### Turn 3: Alignment Strategy

```markdown
## Alignment Strategy

### Root Cause: [Type from Turn 2]

### Step 1: Build Common Ground
- [Shared interest/goal that everyone agrees on]
- [Data point everyone accepts as true]

### Step 2: Address the Gap
| Stakeholder | Their Position | Their Interest | Win for Them |
|------------|---------------|---------------|-------------|
| [Name] | [What they want] | [Why they want it] | [Acceptable outcome] |
| [Name] | [What they want] | [Why they want it] | [Acceptable outcome] |

### Step 3: Propose a Path Forward
**Proposed resolution:**
[Specific proposal that addresses both interests]

**Or, propose a decision-making process:**
- [ ] Data-driven: "Let's A/B test both approaches"
- [ ] Time-boxed: "Let's try X for 2 weeks, evaluate, adjust"
- [ ] Escalate: "Let's present both options to [executive] for decision"

### Step 4: Formalize Agreement
- [ ] Document the decision in `skills/planning/decision-log/SKILL.md`
- [ ] Communicate to all affected parties
- [ ] Set a review date to verify alignment holds
```

---

## References

### Related Skills
- `skills/communication/stakeholder-map/SKILL.md` — Know the players
- `skills/communication/negotiation-playbook/SKILL.md` — Negotiation tactics
- `skills/planning/decision-log/SKILL.md` — Document the resolution

---

**Skill type:** Interactive
**Domain:** Communication & Stakeholders
