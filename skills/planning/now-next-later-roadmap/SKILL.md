---
name: now-next-later-roadmap
description: Build a time-horizon roadmap organized by confidence level — Now (committed), Next (planned), Later (exploratory) — that communicates strategy without false precision.
type: component
domain: planning
difficulty: beginner
estimated_time: "20-30 min"
prerequisites: ["epic-hypothesis"]
outputs: ["roadmap-document"]
triggers:
  - "Create a Now Next Later roadmap"
  - "Build a roadmap without dates"
  - "I need a strategic roadmap"
  - "Outcome-based roadmap"
---

## Purpose

Build a roadmap organized by **confidence level** rather than fixed dates — avoiding the false precision that makes traditional roadmaps lie. Communicates strategic direction while being honest about uncertainty.

---

## Key Concepts

### Three Horizons

| Horizon | Confidence | Detail Level | Commitment |
|---------|-----------|--------------|------------|
| **NOW** | High (>80%) | Epics with stories | Committed, in progress |
| **NEXT** | Medium (50-80%) | Epics with hypotheses | Planned, dependent on NOW |
| **LATER** | Low (<50%) | Themes/opportunities | Exploring, not committed |

---

## Application

### The Template

```markdown
# Product Roadmap: [Product Name]
**Last Updated:** [Date] | **Owner:** [PM Name]
**Strategy:** [One-line strategy statement]

## 🟢 NOW (Current Quarter)
*High confidence. Committed. In progress.*

### [Initiative 1]
- **Objective:** [What we're trying to achieve]
- **Key Result:** [How we'll measure success]
- **Status:** [On track / At risk / Blocked]
- **Key milestones:** [Dates this quarter]

### [Initiative 2]
...

---

## 🟡 NEXT (Next Quarter)
*Medium confidence. Planned. Dependent on NOW outcomes.*

### [Initiative 3]
- **Hypothesis:** [What we believe will happen if we build this]
- **Depends on:** [What needs to be true from NOW]
- **Open questions:** [What we still need to learn]

---

## 🔴 LATER (Future Quarters)
*Low confidence. Exploring. Not committed.*

### [Theme 1]
- **Opportunity:** [Market trend or user need]
- **Why it matters:** [Strategic alignment]
- **What we'd need to learn first:** [Discovery needed]
```

---

## Examples

### ✅ Good NOW Item

```markdown
### Sandbox Onboarding
- **Objective:** Reduce trial drop-off at data connection step
- **Key Result:** 7-day activation rate from 28% → 55%
- **Status:** On track — beta launching week of March 15
- **Depends on:** Design system component library (done)
```

### ❌ Bad Item

```markdown
### Improve onboarding (Q2)
- Build new onboarding flow
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **NOW Detail** | Initiative names only | Objectives listed | Objectives + KRs + status |
| **NEXT Framing** | Committed items | "Maybe" items | Hypotheses with dependencies |
| **LATER Framing** | Backlog dump | Themes | Themes + learning needed |
| **Strategy Link** | Items unconnected | Loosely connected | Every item traces to strategy |
| **Communication** | Internal only | Shared | Tailored versions per audience |

---

## Common Pitfalls

### Pitfall 1: Everything is NOW

**Fix:** If NOW has more than 3-5 initiatives, you have a prioritization problem, not a roadmap.

### Pitfall 2: LATER Becomes a Graveyard

**Fix:** Review LATER quarterly. Items that haven't moved in 2 quarters should be explicitly killed or promoted.

---

## References

### Related Skills
- `skills/planning/prioritization-advisor/SKILL.md` — Prioritize what goes in each horizon
- `skills/planning/epic-hypothesis/SKILL.md` — NEXT items should be hypothesis-framed
- `skills/strategy/okr-framework/SKILL.md` — NOW aligns with current OKRs

### External Frameworks
- Janna Bastow (ProdPad), Now-Next-Later framework
- Basecamp's Shape Up — Appetite-based planning

---

**Skill type:** Component
**Domain:** Planning & Prioritization
