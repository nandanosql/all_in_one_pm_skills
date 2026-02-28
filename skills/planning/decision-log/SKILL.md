---
name: decision-log
description: Document product decisions with context, alternatives considered, rationale, and revisit criteria. Creates institutional memory that prevents re-litigating settled decisions.
type: component
domain: planning
difficulty: beginner
estimated_time: "5-10 min per entry"
prerequisites: []
outputs: ["decision-log-entry"]
triggers:
  - "Log this product decision"
  - "Document why we chose X over Y"
  - "Create a decision record"
  - "Architecture decision record"
---

## Purpose

Document product decisions with their **context, alternatives, rationale, and revisit criteria** — creating institutional memory that prevents teams from re-litigating settled decisions while enabling informed revisits when circumstances change.

---

## Key Concepts

### Why Decision Logs Matter

- **Prevents re-litigation:** New team members can read *why* a decision was made instead of proposing the rejected option
- **Enables revisits:** When context changes, you know which decisions to re-evaluate
- **Creates accountability:** Decisions have owners and dates
- **Reduces "we should have...":** Captures what you knew *at the time*

---

## Application

### Decision Log Entry Template

```markdown
## Decision: [Title — e.g., "Use GraphQL over REST for API v2"]

**Date:** [YYYY-MM-DD]
**Decision maker(s):** [Names/roles]
**Status:** [Proposed / Accepted / Deprecated / Superseded by #XX]

### Context
[What situation prompted this decision? What problem needed solving?]

### Options Considered
| Option | Pros | Cons |
|--------|------|------|
| **[Option A — chosen]** | [Pro 1, Pro 2] | [Con 1] |
| [Option B — rejected] | [Pro 1] | [Con 1, Con 2] |
| [Option C — rejected] | [Pro 1] | [Con 1, Con 2] |

### Decision
[Which option was chosen and why]

### Consequences
- [Expected positive consequence]
- [Expected negative consequence (tradeoff accepted)]

### Revisit When
- [Condition that would make this decision worth re-evaluating]
- [Timeline for mandatory review, if applicable]
```

---

## Examples

### ✅ Good Entry

```markdown
## Decision: Build sandbox onboarding instead of skip-to-dashboard option

**Date:** 2026-02-15 | **Decided by:** PM Lead, Eng Lead, Design Lead
**Status:** Accepted

### Context
72% of trial users drop off at "Connect Data Source" step. We need to reduce 
this friction without removing the data connection requirement entirely 
(since connected users convert 4x higher).

### Options Considered
| Option | Pros | Cons |
|--------|------|------|
| **Sandbox with demo data** | No credentials needed; shows real value | Extra dev work; users still need to connect later |
| Skip to empty dashboard | Fastest to build | Users see zero value; defeats purpose |
| OAuth-only connection | Reduces credential friction | Only works for 40% of data sources |

### Decision
Sandbox with demo data. Users experience core value immediately, then are 
prompted to connect real data after their "aha moment."

### Revisit When
- If sandbox users don't connect real data within 14 days (goal: 60% connect)
- If OAuth coverage exceeds 80% of data sources (reconsider OAuth-only)
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Context** | None | Brief | Full situation + problem + constraints |
| **Alternatives** | Decision only | 2 options | 3+ options with pros/cons |
| **Rationale** | "We decided X" | Reason given | Reason tied to evidence/criteria |
| **Revisit Criteria** | None | Vague timeline | Specific triggering conditions |
| **Accessibility** | In someone's head | In a doc somewhere | In a shared, searchable log |

---

## References

### Related Skills
- `skills/planning/risk-assessment/SKILL.md` — Risky decisions need extra documentation
- `skills/planning/prioritization-advisor/SKILL.md` — Prioritization decisions to log
- `skills/communication/stakeholder-map/SKILL.md` — Know who needs to be informed

### External Frameworks
- Architecture Decision Records (ADR) — Michael Nygard

---

**Skill type:** Component
**Domain:** Planning & Prioritization
