---
name: user-story
description: Create clear, concise user stories combining Mike Cohn's format with Gherkin acceptance criteria. Translates user needs into actionable development work with testable success criteria.
type: component
domain: specification
difficulty: beginner
estimated_time: "10-15 min"
prerequisites: ["proto-persona"]
outputs: ["user-story-document"]
triggers:
  - "Write a user story"
  - "Create a user story with acceptance criteria"
  - "Convert this requirement into a user story"
---

## Purpose

Create clear, concise user stories that combine Mike Cohn's "As a / I want / So that" format with Gherkin-style acceptance criteria. Translates user needs into **actionable development work** focusing on outcomes with testable success criteria.

---

## Key Concepts

### The Format

**Use Case (Mike Cohn):**
```
As a [specific persona/role]
I want to [action to achieve outcome]
so that [desired outcome — user's motivation]
```

**Acceptance Criteria (Gherkin):**
```
Scenario: [Brief description]
Given [initial context/preconditions]
  and [additional preconditions]
When [event that triggers the action]
Then [expected outcome]
```

### Quality Checks

- **"As a" specificity:** "Trial user" not "user"
- **"I want to" is an action:** Something the user does, not a feature
- **"So that" is motivation:** Why they care — not restating the action
- **One When, one Then:** Multiple = multiple stories (split them)

---

## Application

### Step 1: Gather Context

```markdown
**Persona:** [From proto-persona]
**Problem:** [From problem statement]
**Desired outcome:** [What success looks like]
```

### Step 2: Write the Story

```markdown
### User Story [ID]:

- **Summary:** [Brief value-focused title]

#### Use Case:
- **As a** [persona name or role]
- **I want to** [action user takes]
- **so that** [desired outcome]

#### Acceptance Criteria:

- **Scenario:** [Value description]
- **Given:** [Context/precondition]
- **and Given:** [Additional context]
- **When:** [Trigger — aligns with "I want to"]
- **Then:** [Outcome — aligns with "so that"]
```

### Step 3: Validate

- [ ] Is "So that" different from "I want to"?
- [ ] Can QA write tests from the acceptance criteria?
- [ ] Does the story fit in one sprint?
- [ ] Is it a user action (not a technical task)?

---

## Examples

### ✅ Good Example

```markdown
### User Story 042:

- **Summary:** Enable Google login for trial users to reduce signup friction

#### Use Case:
- **As a** trial user visiting the app for the first time
- **I want to** log in using my Google account
- **so that** I can access the app without creating and remembering a new password

#### Acceptance Criteria:
- **Scenario:** First-time trial user logs in via Google OAuth
- **Given:** I am on the login page
- **and Given:** I have a Google account
- **When:** I click "Sign in with Google" and authorize the app
- **Then:** I am logged into the app and redirected to the onboarding flow
```

### ❌ Bad Example

```markdown
As a user, I want a login button, so that I can log in.
```

**Why this fails:** Generic persona, solution embedded, "so that" restates the action, no acceptance criteria.

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Persona** | "A user" | Role-based ("admin") | Named persona with context |
| **Action** | Feature name | User action | Specific, observable action |
| **Motivation** | Missing or restated | General benefit | Unique motivation with outcome |
| **Criteria** | None | Vague | Gherkin with one When/Then |
| **Size** | Multi-sprint | Sprint-sized | 1-3 day estimate |

---

## Common Pitfalls

### Pitfall 1: Technical Tasks Disguised as Stories

**Fix:** "As a developer, I want to refactor the API" → Not a user story. Use an engineering ticket.

### Pitfall 2: Multiple When/Then Statements

**Fix:** Each When/Then pair is a separate story. Split using `skills/specification/user-story-splitting/SKILL.md`.

---

## References

### Related Skills
- `skills/specification/user-story-splitting/SKILL.md` — Break large stories
- `skills/discovery/proto-persona/SKILL.md` — "As a" persona
- `skills/planning/epic-hypothesis/SKILL.md` — Epics decompose into stories

### External Frameworks
- Mike Cohn, *User Stories Applied* (2004)
- Gherkin/Cucumber — Acceptance criteria format
- INVEST criteria — Independent, Negotiable, Valuable, Estimable, Small, Testable

---

**Skill type:** Component
**Domain:** Specification & Design
