---
name: dependency-map
description: Visualize and manage cross-team and cross-system dependencies that create execution risk. Identifies blockers, critical paths, and coordination needs before they become surprises.
type: component
domain: planning
difficulty: intermediate
estimated_time: "15-25 min"
prerequisites: ["epic-hypothesis"]
outputs: ["dependency-map-document"]
triggers:
  - "Map our dependencies"
  - "What depends on what"
  - "Identify blockers and critical path"
  - "Cross-team dependency analysis"
---

## Purpose

Visualize and manage **cross-team and cross-system dependencies** that create execution risk. Identifies blockers, critical paths, and coordination needs so teams can plan around constraints instead of discovering them mid-sprint.

---

## Key Concepts

### Dependency Types

| Type | Example | Risk Level |
|------|---------|-----------|
| **Team-to-team** | "We need API from Platform team" | High — coordination required |
| **Feature-to-feature** | "Login must ship before settings" | Medium — sequencing needed |
| **External** | "Waiting on vendor integration" | High — outside your control |
| **Infrastructure** | "Needs new database schema" | Medium — technical coordination |
| **Data** | "Requires analytics pipeline" | Medium — often underestimated |

---

## Application

### Step 1: Map Dependencies

```markdown
## Dependency Map: [Initiative/Quarter]

### Our Deliverables
| # | Deliverable | Team | Depends On | Dependency Type | Status |
|---|-----------|------|-----------|----------------|--------|
| 1 | [Item] | [Us] | [Item from other team] | [Type] | [Clear/At risk/Blocked] |
| 2 | [Item] | [Us] | [Item from other team] | [Type] | [Status] |

### What Others Need From Us
| # | Deliverable | Requesting Team | Due Date | Status |
|---|-----------|----------------|----------|--------|
| 1 | [Item] | [Team] | [Date] | [Status] |
```

### Step 2: Identify Critical Path

```markdown
**Critical path (longest dependency chain):**
[A] → [B] → [C] → [Final deliverable]

**Total lead time:** [X weeks]
**Bottleneck:** [The dependency that has the least slack]
**Mitigation:** [How to reduce critical path length]
```

### Step 3: Dependency Management Plan

```markdown
| Dependency | Owner | Check-in Cadence | Escalation Trigger |
|-----------|-------|-----------------|-------------------|
| [Dep 1] | [Name] | [Weekly/biweekly] | [If delayed by >X days] |
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Coverage** | Internal only | Internal + 1 external | All dependency types mapped |
| **Ownership** | Unowned | Partially owned | Every dependency has an owner |
| **Critical Path** | Not identified | Listed but not analyzed | Identified with bottleneck + mitigation |
| **Cadence** | One-time map | Updated on request | Regular check-in schedule |

---

## References

### Related Skills
- `skills/planning/risk-assessment/SKILL.md` — Dependencies create risks
- `skills/planning/roadmap-planning/SKILL.md` — Dependencies affect sequencing
- `skills/communication/stakeholder-map/SKILL.md` — Dependency owners are stakeholders

---

**Skill type:** Component
**Domain:** Planning & Prioritization
