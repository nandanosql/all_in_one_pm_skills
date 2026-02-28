---
name: prd-development
description: Orchestrate the complete PRD development process — gathering requirements, writing the document, reviewing with stakeholders, and iterating to approval. Uses 8+ component skills.
type: workflow
domain: specification
difficulty: intermediate
estimated_time: "1-2 weeks"
prerequisites: ["problem-statement"]
outputs: ["approved-prd"]
triggers:
  - "Take me through the PRD process"
  - "Help me build a PRD from scratch"
  - "Full PRD development workflow"
---

## Purpose

Orchestrate the **complete PRD development process** from requirements gathering through stakeholder approval. Sequences research, writing, review, and iteration into a structured workflow.

---

## Application

### Phase 1: Requirements Gathering (Day 1-3)

| Activity | Skill | Time |
|----------|-------|------|
| Validate problem | `skills/discovery/problem-statement/SKILL.md` | 30 min |
| Confirm personas | `skills/discovery/proto-persona/SKILL.md` | 30 min |
| Map JTBD | `skills/discovery/jobs-to-be-done/SKILL.md` | 30 min |
| Write epic hypothesis | `skills/planning/epic-hypothesis/SKILL.md` | 20 min |
| Map dependencies | `skills/planning/dependency-map/SKILL.md` | 20 min |

### Phase 2: Solution Design (Day 3-5)

| Activity | Skill | Time |
|----------|-------|------|
| Build opportunity tree | `skills/specification/opportunity-solution-tree/SKILL.md` | 45 min |
| Write user stories | `skills/specification/user-story/SKILL.md` | 30 min each |
| Write acceptance criteria | `skills/specification/acceptance-criteria-guide/SKILL.md` | 15 min each |
| Assess risks | `skills/planning/risk-assessment/SKILL.md` | 25 min |

### Phase 3: Write the PRD (Day 5-7)

| Activity | Skill | Time |
|----------|-------|------|
| Draft PRD | `skills/specification/prd-template/SKILL.md` | 60 min |
| Tech spec (with eng) | `skills/specification/technical-spec/SKILL.md` | 45 min |
| Log key decisions | `skills/planning/decision-log/SKILL.md` | 15 min |

### Phase 4: Review & Approve (Day 7-10)

- Share with engineering for feasibility review
- Share with design for UX review
- Share with stakeholders for strategic alignment
- Iterate based on feedback
- Get sign-off

---

## Common Pitfalls

### Pitfall 1: Writing the PRD Before Research

**Fix:** The PRD is documentation of decisions, not the decision-making process. Phase 1 comes first.

### Pitfall 2: PRD as Waterfall

**Fix:** PRDs are living documents. Update them as you learn. Versioning + decision logs prevent confusion.

---

## References

### Skills Orchestrated
All skills in Domains 1-4 can feed this workflow.

---

**Skill type:** Workflow
**Domain:** Specification & Design
