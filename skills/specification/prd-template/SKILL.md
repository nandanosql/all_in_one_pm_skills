---
name: prd-template
description: Create a comprehensive Product Requirements Document covering problem definition, user needs, solution design, technical requirements, success metrics, and launch criteria.
type: component
domain: specification
difficulty: intermediate
estimated_time: "45-60 min"
prerequisites: ["problem-statement", "proto-persona", "epic-hypothesis"]
outputs: ["prd-document"]
triggers:
  - "Write a PRD"
  - "Create a product requirements document"
  - "I need a PRD template"
  - "Document product requirements"
---

## Purpose

Create a comprehensive Product Requirements Document that serves as the **source of truth** for what you're building, why, for whom, and how you'll measure success. The PRD aligns product, engineering, and design before a single line of code is written.

---

## Application

### PRD Template

```markdown
# PRD: [Feature/Product Name]

**Author:** [PM Name]
**Date:** [YYYY-MM-DD]
**Status:** [Draft / In Review / Approved / In Development]
**Stakeholders:** [List key reviewers]

---

## 1. Problem Statement
[From skills/discovery/problem-statement — who, what, why, how big]

**User segment:** [Specific segment]
**Pain point:** [Observable problem]
**Impact:** [Quantified: users, revenue, time]
**Evidence:** [Data sources]

---

## 2. Goals & Success Metrics

### Objectives
- [Primary objective tied to company strategy]
- [Secondary objective]

### Key Results
| Metric | Baseline | Target | Timeline |
|--------|----------|--------|----------|
| [Primary] | [Current] | [Goal] | [When] |
| [Guard metric] | [Current] | [Don't regress] | [When] |

### Non-Goals
- [What this initiative explicitly does NOT address]
- [Scope boundaries]

---

## 3. User Stories & Requirements

### Target Persona
[From skills/discovery/proto-persona — name, role, context]

### User Stories
[From skills/specification/user-story]

#### Story 1: [Title]
- As a [persona], I want to [action], so that [outcome]
- Acceptance criteria: Given/When/Then

#### Story 2: [Title]
...

### Edge Cases
- [Edge case 1 — how to handle]
- [Edge case 2]

---

## 4. Solution Design

### Approach
[High-level solution description]

### User Flow
[Step-by-step user experience]

### Wireframes / Mockups
[Links to design files or embedded images]

### Key Design Decisions
| Decision | Options Considered | Choice | Rationale |
|----------|-------------------|--------|-----------|
| [Decision] | [A, B, C] | [B] | [Why] |

---

## 5. Technical Requirements

### Architecture
[High-level technical approach]

### APIs / Data Requirements
[New endpoints, data models, integrations]

### Performance / Scale
[Latency, throughput, data volume targets]

### Security & Privacy
[Data handling, access controls, compliance]

---

## 6. Launch Plan

### Rollout Strategy
- [ ] Internal dogfooding
- [ ] Beta (% of users)
- [ ] GA rollout
- [ ] Full launch

### Feature Flags
[If using progressive rollout]

### Launch Criteria
- [ ] All P0 stories completed
- [ ] Performance benchmarks met
- [ ] QA sign-off
- [ ] Documentation updated

---

## 7. Risks & Mitigations

[From skills/planning/risk-assessment]

| Risk | Probability | Impact | Mitigation |
|------|-----------|--------|-----------|
| [Risk 1] | [H/M/L] | [H/M/L] | [Plan] |

---

## 8. Timeline & Milestones

| Milestone | Target Date | Owner |
|-----------|-----------|-------|
| Design complete | [Date] | [Design] |
| Development start | [Date] | [Eng] |
| Beta launch | [Date] | [PM] |
| GA launch | [Date] | [PM] |

---

## 9. Open Questions
- [ ] [Question 1 — who will answer, by when]
- [ ] [Question 2]

---

## 10. Appendix
- [Links to research, related PRDs, technical docs]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Problem** | Not stated | Vague | Quantified with evidence |
| **Metrics** | None | General goals | Specific KRs with baselines |
| **Scope** | Unbounded | Some boundaries | Clear goals + non-goals |
| **User Stories** | Feature list | Stories without AC | Stories + Gherkin AC |
| **Risks** | Not assessed | Listed | Assessed with mitigations |

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Section 1 input
- `skills/discovery/proto-persona/SKILL.md` — Section 3 input
- `skills/specification/user-story/SKILL.md` — Stories format
- `skills/planning/risk-assessment/SKILL.md` — Section 7 input
- `skills/specification/prd-development/SKILL.md` — Workflow for building PRDs

---

**Skill type:** Component
**Domain:** Specification & Design
