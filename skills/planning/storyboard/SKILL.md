---
name: storyboard
description: Visualize user journeys with 6-frame narrative storyboards. Creates a visual story of how a user encounters a problem and experiences the solution in context.
type: component
domain: planning
difficulty: beginner
estimated_time: "15-20 min"
prerequisites: ["proto-persona"]
outputs: ["storyboard-document"]
triggers:
  - "Create a storyboard for this feature"
  - "Visualize the user journey"
  - "Show how the user experiences this"
---

## Purpose

Create a **6-frame narrative storyboard** that visualizes how a user encounters a problem and experiences the solution in their real-world context. Storyboards build empathy and alignment by showing the human story behind the feature.

---

## Application

### The 6-Frame Template

```markdown
# Storyboard: [Feature/Solution Name]
**Persona:** [Name from persona]

## Frame 1: The Person
**[Who they are and their normal context]**
Scene: [Visual description]
Caption: [What's happening]

## Frame 2: The Trigger
**[The moment the problem arises]**
Scene: [Visual description]
Caption: [What triggers the need]

## Frame 3: The Problem
**[The frustration or pain point]**
Scene: [Visual description — show the emotion]
Caption: "[What they say/think]"

## Frame 4: The Discovery
**[How they encounter the solution]**
Scene: [Visual description]
Caption: [How they find your product/feature]

## Frame 5: The Experience
**[Using the solution]**
Scene: [Visual description — show the interaction]
Caption: [Key moment of the solution working]

## Frame 6: The Outcome
**[Life after the solution]**
Scene: [Visual description — show the improved state]
Caption: [The positive outcome achieved]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Narrative** | Disconnected frames | Logical sequence | Compelling emotional arc |
| **Specificity** | Generic user | Named persona | Person + context + emotion |
| **Problem** | Assumed | Stated | Shown through behavior |
| **Solution** | Feature-centric | User-centric | Value-centric with emotion |
| **Outcome** | "It's better now" | Specific improvement | Measurable, relatable change |

---

## References

### Related Skills
- `skills/discovery/proto-persona/SKILL.md` — Who the storyboard is about
- `skills/discovery/customer-journey-map/SKILL.md` — Journey data feeds the storyboard
- `skills/strategy/press-release/SKILL.md` — Similar storytelling for vision alignment

---

**Skill type:** Component
**Domain:** Planning & Prioritization
