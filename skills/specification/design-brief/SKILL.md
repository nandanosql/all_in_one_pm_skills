---
name: design-brief
description: Create a design brief that clearly communicates the product context, user needs, constraints, and success criteria to the design team — bridging PM requirements and design execution.
type: component
domain: specification
difficulty: beginner
estimated_time: "15-25 min"
prerequisites: ["proto-persona", "problem-statement"]
outputs: ["design-brief-document"]
triggers:
  - "Write a design brief"
  - "Brief the design team"
  - "Create a design spec"
  - "Hand off requirements to design"
---

## Purpose

Create a design brief that clearly communicates **product context, user needs, constraints, and success criteria** to the design team — ensuring designers have everything they need to create solutions without constant back-and-forth.

---

## Application

### Design Brief Template

```markdown
# Design Brief: [Feature/Initiative Name]

**Author:** [PM Name] | **Date:** [Date]
**Designer(s):** [Assigned designer(s)]
**Priority:** [P0/P1/P2] | **Target Sprint:** [Sprint #/Date]

---

## 1. Context & Background
[Why are we doing this? What's the business/user context?]

## 2. User & Persona
- **Primary persona:** [Name + role + context]
- **User scenario:** [When/where/why they encounter this]
- **Current experience:** [How they handle it today — pain points]

## 3. Problem to Solve
[Clear problem statement — what's broken or missing]

## 4. Goals
### Must Have (P0)
- [Critical requirement — non-negotiable]
- [Critical requirement]

### Should Have (P1)
- [Important but not blocking]

### Nice to Have (P2)
- [Enhancement if time allows]

## 5. Constraints
- **Technical:** [API limitations, platform constraints, existing component library]
- **Business:** [Legal, brand guidelines, compliance requirements]
- **Timeline:** [Hard deadlines, dependencies]
- **Accessibility:** [WCAG level, screen reader support]

## 6. Inspiration & References
- [Link to competitive examples]
- [Link to design patterns to consider]
- [Screenshots of current experience]

## 7. Success Criteria
- [How we'll know the design is successful]
- [Usability metric or qualitative goal]
- [User behavior we want to see]

## 8. Open Questions for Design
- [ ] [Question PM wants design's perspective on]
- [ ] [Trade-off to explore in design]

## 9. Review Plan
- **First review:** [Date] — Low-fidelity concepts
- **Second review:** [Date] — High-fidelity with interactions
- **Final sign-off:** [Date] — Production-ready specs
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Problem Clarity** | Feature request | Problem described | Problem + evidence + user context |
| **Constraints** | None mentioned | Some listed | Technical + business + timeline + a11y |
| **Success Criteria** | "Make it look good" | Qualitative goals | Measurable criteria |
| **Prioritization** | Everything is P0 | Some prioritization | Clear P0/P1/P2 with rationale |

---

## References

### Related Skills
- `skills/discovery/proto-persona/SKILL.md` — Persona for section 2
- `skills/specification/prd-template/SKILL.md` — PRD feeds the design brief
- `skills/specification/acceptance-criteria-guide/SKILL.md` — Success criteria format

---

**Skill type:** Component
**Domain:** Specification & Design
