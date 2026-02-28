---
name: definition-of-done
description: Define clear, team-aligned "Definition of Done" criteria that specify exactly when a story/feature is complete across code, test, documentation, and deployment dimensions.
type: component
domain: execution
difficulty: beginner
estimated_time: "15-20 min"
prerequisites: []
outputs: ["definition-of-done-checklist"]
triggers:
  - "What does Done mean for our team"
  - "Define Definition of Done"
  - "Create our DoD checklist"
  - "What are our completion criteria"
---

## Purpose

Define clear, team-aligned criteria that specify exactly when a story or feature is **truly complete** — not just code-complete, but deployed, tested, documented, and ready for users.

---

## Application

### Definition of Done Template

```markdown
# Definition of Done

## Story Level DoD
A user story is "Done" when ALL of the following are true:

### Code
- [ ] Code written and peer-reviewed (PR approved)
- [ ] Follows team coding standards and style guide
- [ ] No known bugs or regressions introduced
- [ ] Feature flagged (if applicable)

### Testing
- [ ] Unit tests written and passing
- [ ] Integration tests written and passing
- [ ] Acceptance criteria validated (manual or automated)
- [ ] Edge cases tested
- [ ] Cross-browser/platform testing (if applicable)

### Documentation
- [ ] API documentation updated (if applicable)
- [ ] User-facing help docs updated (if applicable)
- [ ] Release notes drafted

### Deployment
- [ ] Deployed to staging environment
- [ ] Smoke-tested in staging
- [ ] Monitoring / alerting configured
- [ ] Rollback plan documented

### Product
- [ ] Demo'd to PM / stakeholders
- [ ] Analytics tracking implemented
- [ ] Success metrics baseline captured

## Epic/Feature Level DoD (additionally)
- [ ] All stories in the epic meet Story DoD
- [ ] End-to-end user flow tested
- [ ] Performance benchmarks met
- [ ] Security review completed (if applicable)
- [ ] Stakeholder sign-off received
```

### Adaptation by Team Maturity

| Team Stage | DoD Strictness | Focus |
|-----------|---------------|-------|
| **New team** | Start with 5-7 items | Basic code + test + deploy |
| **Growing** | 10-12 items | Add documentation + monitoring |
| **Mature** | Full checklist | Include performance + security |

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Completeness** | Code only | Code + tests | Code + tests + docs + deploy |
| **Specificity** | "Tests pass" | "Unit tests pass" | Types of tests + coverage target |
| **Team Alignment** | PM wrote it alone | Eng input | Whole team co-created |
| **Enforcement** | Optional | Manual check | Automated gates where possible |

---

## References

### Related Skills
- `skills/specification/acceptance-criteria-guide/SKILL.md` — AC feeds DoD validation
- `skills/execution/sprint-planning-facilitator/SKILL.md` — DoD is part of sprint planning
- `skills/execution/retrospective-facilitator/SKILL.md` — Review DoD effectiveness

### External Frameworks
- Scrum Guide — Definition of Done

---

**Skill type:** Component
**Domain:** Execution & Delivery
