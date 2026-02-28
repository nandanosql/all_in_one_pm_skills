---
name: sprint-planning-facilitator
description: Facilitate effective sprint planning — reviewing velocity, selecting stories, confirming capacity, identifying risks, and committing as a team. Interactive, turn-based session.
type: interactive
domain: execution
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: ["definition-of-done"]
outputs: ["sprint-plan"]
triggers:
  - "Run sprint planning"
  - "Facilitate our sprint planning session"
  - "Plan the next sprint"
---

## Purpose

Facilitate an effective sprint planning session that results in a **realistic, committed sprint plan** — reviewing team capacity, selecting prioritized stories, identifying risks, and getting team buy-in.

---

## Application

### Turn 1: Review Last Sprint

**Agent asks:** "How did the last sprint go?"

Prompts:
- Velocity (planned vs. actual)
- Carryover stories
- Key learnings

### Turn 2: Confirm Capacity

**Agent asks:** "What's the team's available capacity this sprint?"

Uses `skills/planning/capacity-planning-advisor/SKILL.md` logic

### Turn 3: Review Sprint Goal

**Agent asks:** "What is the sprint goal? (One sentence: what outcome does this sprint deliver?)"

### Turn 4: Select Stories

**Agent asks:** "Which stories from the backlog go into this sprint?"

Validation per story:
- Estimated?
- Acceptance criteria defined?
- Dependencies clear?
- Fits within remaining capacity?

### Turn 5: Identify Risks

**Agent asks:** "What could prevent us from reaching the sprint goal?"

### Output: Sprint Plan

```markdown
# Sprint Plan: [Sprint Name/Number]
**Dates:** [Start] — [End]
**Sprint Goal:** [One sentence]
**Capacity:** [X points / Y stories]

## Committed Stories
| # | Story | Points | Owner | Risk |
|---|-------|--------|-------|------|
| 1 | [Title] | [#] | [Name] | [None/dependency/complexity] |
| 2 | [Title] | [#] | [Name] | [Risk] |

**Total committed:** [X points] / [Y capacity] = [Z% utilization]

## Risks
- [Risk 1 + mitigation]

## Carryover from Last Sprint
- [Story + reason for carryover]
```

---

## References

### Related Skills
- `skills/planning/capacity-planning-advisor/SKILL.md` — Capacity assessment
- `skills/execution/definition-of-done/SKILL.md` — Quality gate
- `skills/execution/retrospective-facilitator/SKILL.md` — Post-sprint review

---

**Skill type:** Interactive
**Domain:** Execution & Delivery
