---
name: release-notes
description: Write user-friendly release notes that communicate what changed, why it matters, and how to use new capabilities — not technical changelogs.
type: component
domain: execution
difficulty: beginner
estimated_time: "10-15 min"
prerequisites: []
outputs: ["release-notes-document"]
triggers:
  - "Write release notes"
  - "What should we tell users about this release"
  - "Create a changelog"
---

## Purpose

Write release notes that users actually **want to read** — communicating what changed, why it matters, and how to use new capabilities. Not a git log, not a technical changelog — a user-facing communication.

---

## Application

### Template

```markdown
# Release Notes: [Version/Date]

## 🎉 What's New

### [Feature Name]
[One sentence: what it does and why you'll care]
[One sentence: how to use it or where to find it]

## 🔧 Improvements

- **[Area]:** [What improved, in user terms]
- **[Area]:** [What improved]

## 🐛 Bug Fixes

- Fixed an issue where [user-visible symptom]
- Resolved [user-visible problem]

## 📋 Coming Soon
[Optional: what's next, to build anticipation]
```

### Writing Rules

| Do | Don't |
|----|-------|
| "You can now export reports as PDF" | "Added PDF export endpoint" |
| "Dashboard loads 3x faster" | "Optimized database queries" |
| "Fixed login issues on Safari" | "Fixed WebKit session storage bug" |

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Language** | Technical/internal | Mostly user-friendly | Entirely user-perspective |
| **Value** | Feature names only | Features + descriptions | Features + why you'll care |
| **Completeness** | Partial | Most changes | All user-visible changes |
| **Tone** | Corporate/dry | Professional | Engaging and clear |

---

## References

### Related Skills
- `skills/launch/launch-checklist/SKILL.md` — Release notes are a launch step
- `skills/communication/executive-presentation/SKILL.md` — Internal announcement

---

**Skill type:** Component
**Domain:** Execution & Delivery
