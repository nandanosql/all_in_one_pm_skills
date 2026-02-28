---
name: user-story-splitting
description: Break down large user stories into smaller, independently deliverable stories using 8 proven splitting patterns. Ensures each split story still delivers user value.
type: component
domain: specification
difficulty: intermediate
estimated_time: "10-20 min"
prerequisites: ["user-story"]
outputs: ["split-stories"]
triggers:
  - "This user story is too big"
  - "How do I split this story"
  - "Break down a large story"
---

## Purpose

Break down large user stories into smaller, independently deliverable stories that still deliver **user value**. Uses 8 proven patterns to find the right splitting strategy.

---

## Key Concepts

### 8 Splitting Patterns

| # | Pattern | Signal | Example |
|---|---------|--------|---------|
| 1 | **Workflow Steps** | Story covers multiple steps | "Checkout" → Review cart, Enter payment, Confirm |
| 2 | **Happy/Sad Path** | Error handling adds scope | "Login" → Success, Invalid credentials, Account locked |
| 3 | **Business Rules** | Multiple conditions/variations | "Discount" → By volume, by tier, by promo code |
| 4 | **Variations in Data** | Multiple input types | "Import" → CSV, Excel, API |
| 5 | **Operations (CRUD)** | Multiple actions on same entity | "Profile" → View, Edit, Delete |
| 6 | **Defer Performance** | Works but not fast enough | "Search" → Basic results, then fast/ranked results |
| 7 | **Simple/Complex** | Core vs. edge cases | "Address" → Single address, then multi-address |
| 8 | **Break Out a Spike** | Unknown technical feasibility | "ML feature" → Research spike, then implementation |

### Splitting Rules

- ✅ Each split story must deliver **independent user value**
- ✅ Each story should be **testable on its own**
- ✅ Combined splits should **cover the original story**
- ❌ Don't split by technical layer (frontend/backend/database)
- ❌ Don't split into "implement" and "test" stories

---

## Application

### Step 1: Identify Why It's Too Big

```markdown
**Original story:** [Paste the story]
**Why it's big:** [Multiple steps / Complex rules / Multiple paths / etc.]
**Estimated effort:** [Current estimate that's too large]
```

### Step 2: Choose a Pattern

```markdown
**Pattern selected:** [Pattern name]
**Rationale:** [Why this pattern fits the story's structure]
```

### Step 3: Split and Validate

```markdown
**Split stories:**

1. [Story 1 — smallest valuable increment]
   - Can be released independently? ✅/❌
   - Delivers user value alone? ✅/❌

2. [Story 2 — next increment]
   - Can be released independently? ✅/❌

3. [Story 3 — additional increment]
   ...

**Coverage check:** Do all splits combined = original story? ✅/❌
```

---

## Examples

### ✅ Good Split (Workflow Steps)

**Original:** "As a customer, I want to complete checkout so I can receive my order"

**Split:**
1. "As a customer, I want to review my cart so I can confirm items before paying" (MVP)
2. "As a customer, I want to enter payment details so I can pay for my order"
3. "As a customer, I want to receive an order confirmation so I know my order was placed"

### ❌ Bad Split (Technical Layers)

1. "Backend: Create payment API endpoint" ← Not a user story
2. "Frontend: Build checkout form" ← Not a user story
3. "Database: Create orders table" ← Not a user story

---

## References

### Related Skills
- `skills/specification/user-story/SKILL.md` — Write the resulting stories
- `skills/planning/epic-breakdown-advisor/SKILL.md` — Interactive splitting guidance

### External Frameworks
- Richard Lawrence, *Patterns for Splitting User Stories*

---

**Skill type:** Component
**Domain:** Specification & Design
