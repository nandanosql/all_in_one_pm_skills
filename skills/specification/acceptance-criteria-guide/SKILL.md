---
name: acceptance-criteria-guide
description: Write precise, testable acceptance criteria using Gherkin Given/When/Then format with happy path, error handling, edge cases, and boundary conditions.
type: component
domain: specification
difficulty: beginner
estimated_time: "10-15 min"
prerequisites: ["user-story"]
outputs: ["acceptance-criteria"]
triggers:
  - "Write acceptance criteria"
  - "How do I define acceptance criteria"
  - "Add Given When Then criteria"
---

## Purpose

Write precise, testable acceptance criteria that define **what "done" means** for a user story. Good acceptance criteria eliminate ambiguity between PM and engineering, enable automated testing, and prevent scope creep.

---

## Application

### Template

```markdown
## Acceptance Criteria for: [Story Title]

### Scenario 1: Happy Path — [Description]
**Given** [context/precondition]
**When** [user action]
**Then** [expected result]

### Scenario 2: Error Handling — [Description]
**Given** [context with error condition]
**When** [user action that triggers error]
**Then** [graceful error handling]

### Scenario 3: Edge Case — [Description]
**Given** [boundary condition]
**When** [user action at the boundary]
**Then** [expected behavior at edge]

### Scenario 4: Authorization — [Description]
**Given** [user without permission]
**When** [they attempt the action]
**Then** [appropriate denial response]
```

### Coverage Checklist

- [ ] Happy path covered
- [ ] Main error paths covered
- [ ] Boundary conditions defined (empty, max, null)
- [ ] Permission/authorization checks
- [ ] Performance expectations (if relevant)
- [ ] Each scenario is independently testable

---

## Examples

### ✅ Good

```markdown
### Scenario: User searches with valid keyword
**Given** I am on the product search page
**and** the product catalog contains items matching "wireless headphones"
**When** I enter "wireless headphones" in the search bar and press Enter
**Then** I see a list of matching products sorted by relevance
**and** each result shows product name, price, and rating
**and** results load within 2 seconds
```

### ❌ Bad

```markdown
Search should work and show results.
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Testability** | Vague | Mostly testable | Every scenario automatable |
| **Coverage** | Happy path only | Happy + some errors | Happy + errors + edges + auth |
| **Specificity** | "It should work" | General behavior | Observable, measurable assertions |

---

## References

### Related Skills
- `skills/specification/user-story/SKILL.md` — Stories that need acceptance criteria
- `skills/execution/definition-of-done/SKILL.md` — AC is part of Definition of Done

---

**Skill type:** Component
**Domain:** Specification & Design
