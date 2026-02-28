---
name: recommendation-canvas
description: Structure product recommendations using a one-page canvas that captures the problem, proposed solution, expected impact, risks, and go/no-go decision criteria in a stakeholder-ready format.
type: component
domain: specification
difficulty: beginner
estimated_time: "15-20 min"
prerequisites: ["problem-statement"]
outputs: ["recommendation-canvas"]
triggers:
  - "Create a recommendation canvas"
  - "Structure my product recommendation"
  - "Present a product recommendation"
  - "One-pager for a proposal"
---

## Purpose

Structure product recommendations into a **one-page decision document** that captures problem, proposed solution, expected impact, risks, and decision criteria — making it easy for stakeholders to say yes, no, or "tell me more."

---

## Application

### Recommendation Canvas Template

```markdown
# Recommendation Canvas: [Initiative Name]

**Author:** [PM Name] | **Date:** [Date] | **Decision needed by:** [Date]

---

## 1. The Problem (Why)
[2-3 sentences: What user/business problem are we solving? Include data.]

## 2. The Recommendation (What)
[2-3 sentences: What do we propose doing? Be specific about scope.]

## 3. Expected Impact (How Much)
| Metric | Current | Expected | Timeline |
|--------|---------|----------|----------|
| [Primary] | [Baseline] | [Target] | [Weeks] |
| [Secondary] | [Baseline] | [Target] | [Weeks] |

## 4. Alternatives Considered
| Option | Pros | Cons | Why Not |
|--------|------|------|---------|
| [Alt 1] | [+] | [-] | [Reason] |
| [Alt 2] | [+] | [-] | [Reason] |

## 5. Investment Required
- **Engineering:** [X sprints / Y engineers]
- **Design:** [Effort level]
- **Other:** [Marketing, ops, etc.]

## 6. Key Risks
| Risk | Probability | Mitigation |
|------|-----------|-----------|
| [Risk 1] | [H/M/L] | [Plan] |

## 7. Decision Requested
- [ ] ✅ Approve — proceed to development
- [ ] 🔄 Approve with modifications: ___
- [ ] ❌ Reject — reason: ___
- [ ] ❓ Need more information: ___
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Problem** | Not stated | Stated | Quantified with evidence |
| **Alternatives** | Only the proposed option | 1 alternative | 2+ alternatives with tradeoffs |
| **Impact** | Qualitative only | Some metrics | Baseline + target + timeline |
| **Risks** | Not addressed | Listed | Probabili + mitigation |
| **Decision clarity** | Ambiguous ask | "Should we do this?" | Clear options with checkboxes |

---

## Common Pitfalls

### Pitfall 1: Burying the Recommendation

**Fix:** State your recommendation in section 2, not at the end. Stakeholders want to know your position upfront.

### Pitfall 2: No Alternatives

**Fix:** Always present at least 2 alternatives (including "do nothing"). Shows you've thought broadly.

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Problem section input
- `skills/planning/decision-log/SKILL.md` — Log the decision after
- `skills/communication/executive-presentation/SKILL.md` — Present the recommendation

---

**Skill type:** Component
**Domain:** Specification & Design
