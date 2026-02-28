---
name: epic-breakdown-advisor
description: Guide splitting large epics into right-sized user stories using Richard Lawrence's 9 proven splitting patterns. Recommends the best pattern based on epic characteristics.
type: interactive
domain: planning
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["epic-hypothesis", "user-story"]
outputs: ["split-stories"]
triggers:
  - "This epic is too big"
  - "Help me break down this epic"
  - "Split this into user stories"
  - "Epic breakdown"
---

## Purpose

Guide splitting large epics into **right-sized user stories** using proven patterns. Recommends the best splitting strategy based on the epic's characteristics — workflow steps, business rules, data variations, user personas, or platform differences.

---

## Key Concepts

### 9 Splitting Patterns (Richard Lawrence)

| # | Pattern | When to Use | Example |
|---|---------|------------|---------|
| 1 | **Workflow Steps** | Epic follows a multi-step process | "Checkout" → Cart, Payment, Confirmation |
| 2 | **Business Rules** | Different rules for different cases | "Apply discount" → By tier, volume, promo |
| 3 | **Happy/Unhappy Path** | Error handling adds complexity | "Login" → Success, Wrong password, Locked |
| 4 | **Input Variations** | Multiple data types or sources | "Import data" → CSV, API, manual entry |
| 5 | **Data Types** | Different entities need same operation | "Notifications" → Email, SMS, push |
| 6 | **Operations (CRUD)** | Create, Read, Update, Delete | "Manage users" → Create, view, edit, disable |
| 7 | **Role/Persona** | Different users need different versions | "Dashboard" → PM view, Exec view, Dev view |
| 8 | **Platform** | Needs to work across contexts | "Search" → Web, mobile, API |
| 9 | **Performance** | Functional first, optimize later | "Report" → Generate (slow), then optimize |

---

## Application

### Question 1: Describe the Epic

**Agent asks:** "What's the epic? Share the title and a 2-3 sentence description."

### Question 2: Epic Characteristics

**Agent asks:** "What makes this epic big? (Select all that apply)"

1. Multiple workflow steps
2. Complex business rules
3. Multiple user types
4. Multiple platforms/channels
5. Error handling / edge cases
6. Performance requirements
7. Multiple data types

### Question 3: Apply Patterns

Agent recommends 2-3 splitting patterns and generates stories:

```markdown
## Recommended Split: [Pattern Name]

### Original Epic
[Epic description]

### Split Stories
1. **[Story 1]:** As a [persona], I want to [first slice], so that [value]
2. **[Story 2]:** As a [persona], I want to [second slice], so that [value]
3. **[Story 3]:** As a [persona], I want to [third slice], so that [value]
...

### Validation
- [ ] Each story delivers independent value
- [ ] Stories are small enough for 1 sprint
- [ ] Combined stories cover the original epic
- [ ] Stories are testable independently
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Pattern Fit** | Random split | Pattern applied but forced | Pattern matches epic nature |
| **Story Independence** | Stories depend on each other | Some independence | Each story deployable alone |
| **Coverage** | Stories miss parts of epic | Most covered | Full epic coverage + validation |
| **Size** | Still too big (multi-sprint) | Mostly right-sized | All stories fit in 1 sprint |

---

## References

### Related Skills
- `skills/specification/user-story/SKILL.md` — Write the resulting stories
- `skills/specification/user-story-splitting/SKILL.md` — Splitting patterns reference
- `skills/planning/epic-hypothesis/SKILL.md` — Epic that needs splitting

### External Frameworks
- Richard Lawrence, *Patterns for Splitting User Stories* (AgileForAll)

---

**Skill type:** Interactive
**Domain:** Planning & Prioritization
