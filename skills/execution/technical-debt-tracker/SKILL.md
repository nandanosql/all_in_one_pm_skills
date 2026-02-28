---
name: technical-debt-tracker
description: Systematically track, classify, and prioritize technical debt — creating visibility into hidden costs and making rational decisions about when to pay it down vs. accept it.
type: component
domain: execution
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: []
outputs: ["tech-debt-register"]
triggers:
  - "Track our technical debt"
  - "How do we manage tech debt"
  - "Create a tech debt tracker"
  - "Prioritize tech debt"
---

## Purpose

Systematically track, classify, and prioritize technical debt — creating **visibility into hidden costs** and enabling rational decisions about when to pay it down vs. accept it strategically.

---

## Key Concepts

### Tech Debt Classification

| Type | Example | Urgency |
|------|---------|---------|
| **Reckless & Deliberate** | "Ship it, we'll fix later" (and never do) | 🔴 High |
| **Prudent & Deliberate** | "We know this won't scale, but it's fine for 100 users" | 🟡 Medium (with trigger) |
| **Reckless & Inadvertent** | "We didn't know about this pattern" | 🔴 High (when discovered) |
| **Prudent & Inadvertent** | "Now we know a better way" | 🟢 Low (unless blocking) |

---

## Application

### Tech Debt Register Template

```markdown
# Technical Debt Register: [Product/Service]
**Last Updated:** [Date]
**Debt Budget:** [% of sprint capacity allocated — recommended 15-20%]

## Active Debt Items

| ID | Description | Type | Impact | Effort | Priority | Status |
|----|-----------|------|--------|--------|----------|--------|
| TD-001 | [What is it] | [Reck/Prud + Del/Inad] | [H/M/L] | [S/M/L] | [P0-P3] | [Open/In Progress/Paid] |
| TD-002 | [What is it] | [Type] | [H/M/L] | [S/M/L] | [P0-P3] | [Status] |

## Detailed Items (P0/P1 only)

### TD-001: [Title]
- **Description:** [What the debt is and where it lives]
- **Root cause:** [How did this happen?]
- **Impact if ignored:** [What breaks, degrades, or costs money]
- **Trigger for action:** [When this becomes urgent — e.g., >1000 users]
- **Estimated fix:** [Engineering effort to resolve]
- **Owner:** [Engineer or team responsible]

## Metrics
| Metric | Current | Target |
|--------|---------|--------|
| Total debt items | [#] | <[#] |
| P0 items | [#] | 0 |
| Sprint debt allocation | [%] | 15-20% |
| Avg age of P0 items | [days] | <14 days |
```

### Prioritization Framework

| Priority | Criteria | Action |
|----------|----------|--------|
| **P0** | Causes production issues, security risk, or blocks features | Fix this sprint |
| **P1** | Slows development significantly, degrading team velocity | Fix within 2 sprints |
| **P2** | Known suboptimal, but manageable | Scheduled quarterly |
| **P3** | Nice to improve, no active pain | Opportunistic (when touching that area) |

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Visibility** | Debt is invisible | Known but untracked | Tracked register with owner |
| **Classification** | All dumped together | By priority | By type + priority + trigger |
| **Allocation** | 0% sprint capacity | Ad hoc | Consistent 15-20% budget |
| **Decision Making** | "We'll get to it" | Priority-based | Impact + trigger-based with owner |

---

## References

### Related Skills
- `skills/execution/sprint-planning-facilitator/SKILL.md` — Allocate debt in sprint planning
- `skills/execution/retrospective-facilitator/SKILL.md` — Surface new debt in retros
- `skills/planning/risk-assessment/SKILL.md` — Debt creates technical risk

### External Frameworks
- Martin Fowler, Technical Debt Quadrant
- Michael Feathers, *Working Effectively with Legacy Code*

---

**Skill type:** Component
**Domain:** Execution & Delivery
