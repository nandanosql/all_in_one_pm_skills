---
name: technical-spec
description: Create a technical specification document that bridges product requirements and engineering implementation — covering architecture, APIs, data models, and technical decisions.
type: component
domain: specification
difficulty: advanced
estimated_time: "30-45 min"
prerequisites: ["prd-template"]
outputs: ["technical-spec-document"]
triggers:
  - "Write a technical spec"
  - "Create a tech spec for this feature"
  - "Document the technical approach"
  - "Engineering specification"
---

## Purpose

Create a technical specification that bridges **product requirements and engineering implementation**. Documents architecture decisions, API contracts, data models, and implementation approach so engineering can execute with confidence.

---

## Application

### Tech Spec Template

```markdown
# Technical Specification: [Feature Name]

**Author:** [Engineer/PM]
**PRD:** [Link to PRD]
**Status:** [Draft / In Review / Approved]
**Reviewers:** [Engineering leads, architects]

---

## 1. Overview
[1-2 paragraph summary: what we're building and why]

## 2. Goals & Non-Goals

### Goals
- [Technical goal 1]
- [Technical goal 2]

### Non-Goals
- [What's explicitly out of scope technically]

## 3. Proposed Solution

### Architecture
[System diagram or description of how components interact]

### API Design
[New endpoints with request/response schemas]

```
POST /api/v2/onboarding/sandbox
Request: { user_id: string, template: string }
Response: { sandbox_id: string, expires_at: timestamp }
```

### Data Model Changes
[New tables, schema changes, migrations needed]

### Key Technical Decisions
| Decision | Options | Choice | Rationale |
|----------|---------|--------|-----------|
| [Decision] | [A, B] | [A] | [Why] |

## 4. Implementation Plan

### Phase 1: [Foundation]
- [Task 1 — estimate]
- [Task 2 — estimate]

### Phase 2: [Core Logic]
...

## 5. Testing Strategy
- **Unit tests:** [What to test]
- **Integration tests:** [What to test]
- **Performance tests:** [Benchmarks]

## 6. Rollout Plan
- **Feature flag:** [Name]
- **Rollout %:** [Progressive rollout plan]
- **Rollback plan:** [How to revert if issues]

## 7. Monitoring & Alerting
- [Key metrics to watch]
- [Alert thresholds]
- [Dashboard links]

## 8. Open Questions
- [ ] [Technical question 1]
- [ ] [Technical question 2]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Architecture** | None | Text description | Diagram + component interaction |
| **API Design** | Endpoints only | Schemas included | Full contract + error cases |
| **Testing** | "We'll test it" | Test types listed | Specific cases + benchmarks |
| **Rollout** | Ship and pray | Feature flag | Progressive rollout + rollback |
| **Operability** | No monitoring | Metrics listed | Dashboards + alerts + runbooks |

---

## References

### Related Skills
- `skills/specification/prd-template/SKILL.md` — PRD that this spec implements
- `skills/specification/acceptance-criteria-guide/SKILL.md` — Ties to test cases
- `skills/execution/definition-of-done/SKILL.md` — Quality gates for completion

---

**Skill type:** Component
**Domain:** Specification & Design
