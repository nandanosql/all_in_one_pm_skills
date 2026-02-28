---
name: user-story-mapping-workshop
description: Facilitate a collaborative user story mapping session with a cross-functional team — walking through persona selection, backbone creation, task mapping, and release slicing in real-time.
type: interactive
domain: planning
difficulty: intermediate
estimated_time: "45-60 min"
prerequisites: ["user-story-mapping", "proto-persona"]
outputs: ["story-map"]
triggers:
  - "Run a story mapping workshop"
  - "Facilitate a user story mapping session"
  - "Story mapping with my team"
---

## Purpose

Facilitate a **collaborative user story mapping session** with a cross-functional team — walking through persona selection, backbone creation, task mapping, and release slicing in real time. Produces a shared visual artifact that aligns the team on scope and sequencing.

---

## Application

### Turn 1: Set the Stage

**Agent asks:** "Let's build a story map. First, tell me:"
1. What product/feature area are we mapping?
2. Who is in the room? (Roles — PM, eng, design, etc.)
3. Do you have personas defined, or should we create one now?

### Turn 2: Define the Persona & Goal

**Agent asks:** "Who is the primary user, and what is their overarching goal?"

```markdown
**Persona:** [Name]
**Goal:** [What they're trying to accomplish end-to-end]
```

### Turn 3: Build the Backbone

**Agent asks:** "Walk me through the major activities this user does, from start to finish. Think of it as chapter titles in their story."

Agent captures:
```markdown
**Backbone (left → right):**
[Activity 1] → [Activity 2] → [Activity 3] → [Activity 4] → [Activity 5]
```

Validation: "Can someone new read these left-to-right and understand the user's journey?"

### Turn 4: Add Tasks Under Each Activity

**Agent asks:** "For each activity, what specific tasks does the user perform? Let's go column by column."

For each activity:
- "What do they do in [Activity X]?"
- "What are the variations? (Happy path first, then alternatives)"
- "Anything else they might need to do?"

### Turn 5: Draw the Walking Skeleton

**Agent asks:** "Now, draw a horizontal line across the map. Everything above the line is your MVP — the thinnest end-to-end experience. For each column, which ONE task is essential for the user to accomplish the goal?"

### Turn 6: Define Release Slices

**Agent asks:** "Let's define Release 2 and 3. What tasks would make the experience meaningfully better in each release?"

### Output: Complete Story Map

```markdown
# Story Map: [Feature/Product]
**Persona:** [Name] | **Goal:** [Goal]
**Date:** [Today] | **Participants:** [List]

## Map

| [Activity 1] | [Activity 2] | [Activity 3] | [Activity 4] |
|:---:|:---:|:---:|:---:|
| **R1:** [Task] | **R1:** [Task] | **R1:** [Task] | **R1:** [Task] |
| **R2:** [Task] | **R2:** [Task] | **R2:** [Task] | **R2:** [Task] |
| **R3:** [Task] | **R3:** [Task] | — | **R3:** [Task] |

## Release Definitions
- **Release 1 (MVP):** [One-line goal]
- **Release 2:** [One-line goal]
- **Release 3:** [One-line goal]

## Open Questions
- [ ] [Question surfaced during mapping]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Backbone** | Feature list | Activity sequence | Narrative flow a user would recognize |
| **Participation** | PM solo | Some team input | Whole team contributing |
| **Release Slicing** | No slices | Feature-based cuts | Outcome-based thin slices |
| **Validation** | Assumed correct | PM reviewed | Team walked through end-to-end |

---

## References

### Related Skills
- `skills/planning/user-story-mapping/SKILL.md` — The component template this workshop uses
- `skills/specification/user-story/SKILL.md` — Stories derived from the map
- `skills/communication/workshop-facilitation/SKILL.md` — General facilitation protocol

---

**Skill type:** Interactive
**Domain:** Planning & Prioritization
