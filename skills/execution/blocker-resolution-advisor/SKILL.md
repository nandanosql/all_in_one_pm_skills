---
name: blocker-resolution-advisor
description: Systematically diagnose and resolve project blockers — identifying root causes, escalation paths, and creative workarounds to keep delivery on track.
type: interactive
domain: execution
difficulty: intermediate
estimated_time: "10-20 min"
prerequisites: []
outputs: ["resolution-plan"]
triggers:
  - "We're blocked on something"
  - "How do I unblock this"
  - "Resolve a project blocker"
  - "We're stuck and can't move forward"
---

## Purpose

Systematically diagnose and resolve project blockers — identifying **root causes, escalation paths, and creative workarounds** to keep delivery on track when you hit walls.

---

## Application

### Turn 1: Identify the Blocker

**Agent asks:** "What are you blocked on? Describe the situation."

Follow-up probes:
- How long have you been blocked?
- Who/what is the dependency?
- What is the impact if unresolved?

### Turn 2: Classify the Blocker

**Agent classifies:**

| Type | Example | Typical Resolution |
|------|---------|-------------------|
| **Technical** | API not ready, system limitation | Workaround or parallel path |
| **Decision** | Waiting for stakeholder decision | Force a decision with deadline |
| **Resource** | Team doesn't have skills/bandwidth | Borrow, hire, or descope |
| **External** | Vendor/partner delay | Contract escalation, plan B |
| **Information** | Missing data or requirements | Research sprint, assumption-based pivot |
| **Organizational** | Competing priorities, politics | Escalation with evidence |

### Turn 3: Generate Resolution Options

**Agent generates 3 options per blocker:**

```markdown
## Blocker: [Description]
**Type:** [Classification]
**Days blocked:** [#]
**Impact:** [What's delayed and by how much]

### Resolution Options

**Option A: [Remove the blocker]**
- Action: [What to do — e.g., "Escalate to VP Eng with timeline impact"]
- ETA: [When this could unblock]
- Risk: [Risk of this approach]

**Option B: [Work around the blocker]**
- Action: [What to do — e.g., "Use mock API and integrate later"]
- ETA: [When this could unblock]
- Risk: [Risk of this approach]

**Option C: [Reduce scope to avoid the blocker]**
- Action: [What to do — e.g., "Ship without this feature, add in v2"]
- ETA: [When this could unblock]
- Risk: [Risk of this approach]

**Recommended:** [Option X because Y]
```

### Turn 4: Create Action Plan

```markdown
## Action Plan
1. [Immediate action — today]
2. [Follow-up action — by [date]]
3. [Escalation trigger — if not resolved by [date], do [X]]

**Owner:** [Name]
**Check-in:** [Date for blocker review]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Diagnosis** | "We're stuck" | Blocker named | Root cause + classification |
| **Options** | "Wait for it" | One option | 3 options (remove/workaround/descope) |
| **Urgency** | No timeline | Some urgency | Impact quantified + escalation trigger |

---

## References

### Related Skills
- `skills/planning/dependency-map/SKILL.md` — Dependencies that become blockers
- `skills/planning/risk-assessment/SKILL.md` — Blockers are realized risks
- `skills/communication/negotiation-playbook/SKILL.md` — Navigate stakeholder blockers

---

**Skill type:** Interactive
**Domain:** Execution & Delivery
