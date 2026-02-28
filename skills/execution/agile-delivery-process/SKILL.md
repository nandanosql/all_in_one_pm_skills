---
name: agile-delivery-process
description: Orchestrate the complete agile delivery cycle — from sprint planning through execution, review, and retrospective — ensuring cadence, quality, and continuous improvement.
type: workflow
domain: execution
difficulty: intermediate
estimated_time: "Ongoing (per sprint)"
prerequisites: ["definition-of-done"]
outputs: ["sprint-deliverables"]
triggers:
  - "Set up our agile delivery process"
  - "Run an agile sprint end-to-end"
  - "Delivery process for our team"
---

## Purpose

Orchestrate the **complete agile delivery cycle** — from sprint planning through execution, review, and retrospective — ensuring consistent cadence, quality gates, and continuous improvement.

---

## Application

### Sprint Cadence (2-week example)

| Day | Activity | Skill | Duration |
|-----|----------|-------|----------|
| **Day 1** | Sprint Planning | `skills/execution/sprint-planning-facilitator/SKILL.md` | 45-60 min |
| **Daily** | Standup | `skills/execution/standup-optimizer/SKILL.md` | 15 min |
| **Mid-sprint** | Backlog Refinement | `skills/planning/epic-breakdown-advisor/SKILL.md` | 30-45 min |
| **Day 9** | Sprint Review (Demo) | `skills/execution/sprint-review-template/SKILL.md` | 30-45 min |
| **Day 10** | Retrospective | `skills/execution/retrospective-facilitator/SKILL.md` | 30-45 min |
| **Ongoing** | Stakeholder Updates | `skills/execution/stakeholder-update/SKILL.md` | 15 min/week |
| **Ongoing** | Blocker Resolution | `skills/execution/blocker-resolution-advisor/SKILL.md` | As needed |
| **Ongoing** | Tech Debt Tracking | `skills/execution/technical-debt-tracker/SKILL.md` | As needed |

### Quality Gates

```markdown
## Quality Gates per Sprint

### Pre-Sprint
- [ ] Sprint goal defined and agreed
- [ ] All stories have acceptance criteria
- [ ] Capacity confirmed (accounting for PTO, tech debt allocation)
- [ ] Dependencies identified and tracked

### During Sprint
- [ ] Blockers surfaced within 24 hours (not hidden)
- [ ] PR reviews within 1 business day
- [ ] Scope changes go through PM (no silent scope creep)

### End of Sprint
- [ ] All "Done" stories meet Definition of Done
- [ ] Demo shows working software, not slides
- [ ] Metrics captured and reviewed
- [ ] Retro action items created with owners
```

### Anti-Patterns to Monitor

| Anti-Pattern | Signal | Fix |
|-------------|--------|-----|
| **Sprint stuffing** | Velocity drops, carryover rises | Plan to 80% capacity |
| **No retro actions** | Same problems repeat | Track actions, review next retro |
| **Demo theater** | Stakeholders uninformed | Demo from user's perspective |
| **Standup monologues** | 30+ min standups | Walk the board, timebox |
| **Ghosted blockers** | Team works around instead of escalating | Create escalation culture |

---

## References

### Skills Orchestrated
All skills in Domain 5 (Execution) are used in this workflow:
- `skills/execution/definition-of-done/SKILL.md`
- `skills/execution/sprint-planning-facilitator/SKILL.md`
- `skills/execution/sprint-review-template/SKILL.md`
- `skills/execution/retrospective-facilitator/SKILL.md`
- `skills/execution/standup-optimizer/SKILL.md`
- `skills/execution/stakeholder-update/SKILL.md`
- `skills/execution/blocker-resolution-advisor/SKILL.md`
- `skills/execution/technical-debt-tracker/SKILL.md`
- `skills/execution/release-notes/SKILL.md`

---

**Skill type:** Workflow
**Domain:** Execution & Delivery
