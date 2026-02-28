---
name: raci-matrix
description: Define clear roles and responsibilities using the RACI framework — Responsible, Accountable, Consulted, Informed — to eliminate ambiguity and prevent dropped balls on cross-functional initiatives.
type: component
domain: communication
difficulty: beginner
estimated_time: "15-20 min"
prerequisites: ["stakeholder-map"]
outputs: ["raci-matrix"]
triggers:
  - "Create a RACI matrix"
  - "Who is responsible for what"
  - "Define roles and responsibilities"
  - "RACI chart"
---

## Purpose

Define clear roles and responsibilities using the **RACI framework** — eliminating the "I thought you were doing that" problem on cross-functional initiatives.

---

## Application

### RACI Definitions

| Role | Definition | Rule |
|------|-----------|------|
| **R** — Responsible | Does the work | Can have multiple Rs per task |
| **A** — Accountable | Owns the decision / final approval | **Exactly one A per task** |
| **C** — Consulted | Provides input before decision | Two-way communication |
| **I** — Informed | Notified after decision | One-way communication |

### RACI Matrix Template

```markdown
# RACI: [Initiative/Project Name]

| Task/Decision | PM | Eng Lead | Design | Marketing | Exec |
|--------------|:---:|:--------:|:------:|:---------:|:----:|
| Define requirements | A | C | C | I | I |
| Technical architecture | C | A | I | I | I |
| UX design | C | C | A | I | I |
| Sprint planning | A | R | C | I | I |
| Development | I | A | C | I | I |
| QA / testing | C | A | R | I | I |
| Launch messaging | C | I | C | A | I |
| Go/no-go decision | R | C | C | C | A |
| Post-launch metrics | A | C | I | C | I |
```

### Validation Checklist

- [ ] Every row has exactly **one A** (single point of accountability)
- [ ] No one is **A** for everything (accountability overload)
- [ ] No row is missing an **A** (orphaned task)
- [ ] People marked **C** are actually consulted (not just CCed)
- [ ] **I** list is minimal (don't over-inform)

---

## Common Pitfalls

### Pitfall 1: Everyone is Accountable

**Fix:** Shared accountability = no accountability. One person is A, even if uncomfortable.

### Pitfall 2: Too Many Cs

**Fix:** Over-consulting creates Decision by Committee. Only C people whose input changes the decision.

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Completeness** | Few tasks | Most tasks covered | All key decisions + deliverables |
| **Accountability** | Multiple As per row | Usually 1 A | Always exactly 1 A |
| **Adoption** | Doc exists, unused | Referenced occasionally | Actively used for decisions |

---

## References

### Related Skills
- `skills/communication/stakeholder-map/SKILL.md` — Input to RACI
- `skills/planning/dependency-map/SKILL.md` — Dependencies create RACI needs
- `skills/communication/stakeholder-alignment-advisor/SKILL.md` — Alignment using RACI

---

**Skill type:** Component
**Domain:** Communication & Stakeholders
