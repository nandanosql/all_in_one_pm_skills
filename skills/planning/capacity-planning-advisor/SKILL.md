---
name: capacity-planning-advisor
description: Guide PMs through team capacity assessment — velocity, availability, technical debt allocation, and buffer planning — to create realistic sprint and quarterly commitments.
type: interactive
domain: planning
difficulty: intermediate
estimated_time: "15-20 min"
prerequisites: []
outputs: ["capacity-plan"]
triggers:
  - "How much can we commit to this quarter"
  - "Capacity planning for the team"
  - "How many story points can we deliver"
  - "Sprint capacity planning"
---

## Purpose

Assess team capacity realistically — accounting for velocity history, holidays, technical debt allocation, and uncertainty buffers — so commitments are achievable and stakeholder expectations are grounded in reality.

---

## Application

### Question 1: Team Size & Composition

**Agent asks:** "Tell me about your team."

Prompts: # of engineers, designers, QA, any part-time members, upcoming PTO

### Question 2: Historical Velocity

**Agent asks:** "What's your team's recent delivery velocity?"

1. **We track story points** — Average over last 3 sprints
2. **We track throughput** — Stories/tickets completed per sprint
3. **We don't formally track** — Gut sense of capacity

### Question 3: Known Constraints

**Agent asks:** "What constraints affect capacity this period?"

1. Holidays / PTO / conferences
2. Technical debt / maintenance commitments
3. On-call / support rotation
4. New team members ramping up
5. Cross-team dependencies

### Question 4: Allocation Strategy

**Agent asks:** "How do you want to split capacity?"

|Default allocation:
| Category | % | Rationale |
|----------|---|-----------|
| New features | 70% | Primary product work |
| Technical debt | 15% | Sustained quality |
| Bugs / support | 10% | Reactive work |
| Buffer | 5% | Unknown unknowns |

### Output: Capacity Plan

```markdown
# Capacity Plan: [Period]

**Team:** [# FTEs] effective
**Sprint length:** [X weeks]
**Sprints in period:** [#]

## Available Capacity
| Factor | Impact |
|--------|--------|
| Base velocity | [X pts/sprint] |
| PTO/holidays | [-Y pts] |
| New member ramp | [-Z pts] |
| **Adjusted velocity** | **[Net pts/sprint]** |

## Allocation
| Category | Points | % |
|----------|--------|---|
| Features | [#] | 70% |
| Tech debt | [#] | 15% |
| Bugs/support | [#] | 10% |
| Buffer | [#] | 5% |

## Can We Commit To...
| Initiative | Estimated | Fits? | Notes |
|-----------|-----------|-------|-------|
| [Init 1] | [X pts] | ✅/❌ | [Note] |
| [Init 2] | [X pts] | ✅/❌ | [Note] |

## Risks to Capacity
- [Risk 1 + mitigation]
- [Risk 2 + mitigation]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Data-Driven** | Guessing | Some history | 3+ sprints of velocity data |
| **Constraints** | Ignored | Some listed | All known constraints accounted |
| **Buffer** | 0% (will overcommit) | Token buffer | Realistic 10-15% uncertainty |
| **Allocation** | All features | Feature + debt | Feature + debt + bugs + buffer |

---

## References

### Related Skills
- `skills/planning/roadmap-planning/SKILL.md` — Capacity informs roadmap
- `skills/planning/dependency-map/SKILL.md` — Dependencies reduce available capacity
- `skills/execution/sprint-planning-facilitator/SKILL.md` — Sprint-level capacity

---

**Skill type:** Interactive
**Domain:** Planning & Prioritization
