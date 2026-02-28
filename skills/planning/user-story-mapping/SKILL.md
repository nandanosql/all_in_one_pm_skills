---
name: user-story-mapping
description: Organize user stories by workflow backbone using Jeff Patton's story mapping framework. Creates a visual narrative that reveals the minimum viable experience and release slicing.
type: component
domain: planning
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: ["proto-persona", "user-story"]
outputs: ["story-map-document"]
triggers:
  - "Create a user story map"
  - "Map user stories to the workflow"
  - "Story mapping exercise"
  - "Organize stories by user journey"
---

## Purpose

Organize user stories into a **visual narrative** that shows the user's workflow from left to right (the backbone) with story detail growing from top to bottom. Reveals the minimum viable experience and enables smart release slicing.

---

## Key Concepts

### Story Map Structure

```
BACKBONE (user activities, left → right)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Activity 1  │ Activity 2  │ Activity 3  │ Activity 4
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
User Task   │ User Task   │ User Task   │ User Task     ← MVP
────────────│─────────────│─────────────│───────────
User Task   │ User Task   │ User Task   │ User Task     ← Release 2
────────────│─────────────│─────────────│───────────
User Task   │ User Task   │ User Task   │ User Task     ← Release 3
```

- **Backbone (top row):** Major user activities in sequence  
- **Walking skeleton:** The thinnest possible end-to-end flow
- **Release slices:** Horizontal lines that group stories into releases

### Jeff Patton's Principles

1. **Story maps tell a story** — Left to right is the narrative of using the product
2. **Backbone first** — Map the big activities before details
3. **Walking skeleton** — The minimum flow that lets a user achieve the goal end-to-end
4. **Slice by outcome, not feature** — Each release delivers a complete (if thin) experience

---

## Application

### Step 1: Define the Narrative

```markdown
**Persona:** [Who is doing the work?]
**Goal:** [What are they trying to accomplish?]
**Starting point:** [Where does the journey begin?]
**End point:** [What does success look like?]
```

### Step 2: Map the Backbone

```markdown
**Backbone (major activities, in sequence):**
1. [Activity 1: e.g., "Discover the product"]
2. [Activity 2: e.g., "Sign up and set up"]
3. [Activity 3: e.g., "Complete first workflow"]
4. [Activity 4: e.g., "Share results"]
5. [Activity 5: e.g., "Return for next session"]
```

### Step 3: Add Tasks Under Each Activity

```markdown
| Activity 1 | Activity 2 | Activity 3 | Activity 4 |
|-----------|-----------|-----------|-----------|
| [Task 1a] | [Task 2a] | [Task 3a] | [Task 4a] |
| [Task 1b] | [Task 2b] | [Task 3b] | [Task 4b] |
| [Task 1c] | [Task 2c] | [Task 3c] | [Task 4c] |
```

Tasks are ordered **top to bottom by priority within each activity**.

### Step 4: Draw Release Slices

```markdown
**Release 1 (MVP):** [Row of minimum tasks per activity for complete flow]
**Release 2:** [Enhanced version with better UX/more features]
**Release 3:** [Full experience with edge cases handled]
```

### Step 5: Validate the Map

```markdown
**Validation checklist:**
- [ ] Can someone walk through Release 1 end-to-end and accomplish the goal?
- [ ] Does each release slice tell a complete story?
- [ ] Are there activities with no tasks in Release 1? (potential gap)
- [ ] Is the backbone in the right order from the user's perspective?
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Backbone** | Activity list only | Activities in sequence | User narrative, clear flow |
| **Completeness** | Tasks for 1-2 activities | Most activities covered | All activities with tasks |
| **Release Slicing** | No slices | Cut by feature | Cut by outcome (thin end-to-end) |
| **Walking Skeleton** | Not identified | Exists but gaps | Coherent, walkable MVP |
| **User-Centricity** | System operations | Mix of user/system | All user-perspective |

---

## Common Pitfalls

### Pitfall 1: Feature Columns Instead of Activity Columns

**Fix:** Columns should be user activities ("Search for a product"), not features ("Search bar"). Activities are stable; features change.

### Pitfall 2: One Activity Has All the Stories

**Fix:** If one column is 5x taller than others, it's likely multiple activities merged. Split it.

---

## References

### Related Skills
- `skills/specification/user-story/SKILL.md` — Stories that go into the map
- `skills/planning/prioritization-advisor/SKILL.md` — Prioritize within the map
- `skills/planning/roadmap-planning/SKILL.md` — Story map feeds the roadmap

### External Frameworks
- Jeff Patton, *User Story Mapping* (2014)

---

**Skill type:** Component
**Domain:** Planning & Prioritization
