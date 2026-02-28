---
name: incident-postmortem
description: Run effective incident postmortems that are blameless, thorough, and produce real corrective actions — covering timeline reconstruction, root cause analysis, and prevention planning.
type: component
domain: leadership
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: []
outputs: ["postmortem-document"]
triggers:
  - "Write an incident postmortem"
  - "Run a postmortem"
  - "What went wrong analysis"
  - "Blameless postmortem"
---

## Purpose

Run **blameless, thorough postmortems** that reconstruct timelines, identify root causes, and produce corrective actions — turning incidents into organizational learning instead of blame games.

---

## Application

### Postmortem Template

```markdown
# Incident Postmortem: [Incident Title]

**Date of Incident:** [Date]
**Duration:** [Start → End, total duration]
**Severity:** [P0 / P1 / P2]
**Impact:** [Users affected, revenue impact, SLA breach]
**Author:** [Name]
**Postmortem Date:** [Date]

---

## 1. Summary
[2-3 sentences: what happened, what was impacted, how it was resolved]

## 2. Timeline
| Time (UTC) | Event |
|-----------|-------|
| [HH:MM] | [First signal / alert fired] |
| [HH:MM] | [Investigation started] |
| [HH:MM] | [Root cause identified] |
| [HH:MM] | [Fix deployed] |
| [HH:MM] | [Full recovery confirmed] |

## 3. Root Cause Analysis

### What Happened
[Technical description of what went wrong]

### Why It Happened (5 Whys)
1. **Why** did [symptom] occur? → Because [cause 1]
2. **Why** did [cause 1] happen? → Because [cause 2]
3. **Why** did [cause 2] happen? → Because [cause 3]
4. **Why** did [cause 3] happen? → Because [cause 4]
5. **Why** did [cause 4] happen? → Because [root cause]

**Root cause:** [The underlying systemic issue, not a person]

### Contributing Factors
- [Factor 1 — e.g., "No alerting on this metric"]
- [Factor 2 — e.g., "Deployment happened on Friday afternoon"]

## 4. What Went Well
- [Good thing 1 — e.g., "Detection was fast"]
- [Good thing 2 — e.g., "Team coordinated effectively"]

## 5. What Went Poorly
- [Bad thing 1 — e.g., "Took 2 hours to identify root cause"]
- [Bad thing 2 — e.g., "No runbook for this scenario"]

## 6. Action Items
| # | Action | Owner | Priority | Due Date | Status |
|---|--------|-------|----------|----------|--------|
| 1 | [Corrective action] | [Name] | [P0/P1] | [Date] | [Open] |
| 2 | [Preventive action] | [Name] | [P0/P1] | [Date] | [Open] |
| 3 | [Detection improvement] | [Name] | [P1/P2] | [Date] | [Open] |

## 7. Lessons Learned
- [Lesson 1 — systemic insight, not blame]
- [Lesson 2]
```

### Blameless Culture Rules

| Rule | Implementation |
|------|---------------|
| **No blame** | Focus on systems, not individuals |
| **Psychological safety** | Everyone can speak freely without fear |
| **Assume good intent** | People made the best decision with info they had |
| **Focus on prevention** | "How do we make this impossible?" not "Who did this?" |
| **Follow through** | Action items must be tracked and completed |

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Blamelessness** | Finger-pointing | Mostly blameless | Fully systemic analysis |
| **Root Cause** | Symptom identified | 2-3 Whys | Full 5 Whys to systemic root |
| **Action Items** | "Be more careful" | Specific actions | Actions + owners + due dates + tracking |
| **Follow-through** | Actions forgotten | Some tracked | All completed and verified |

---

## References

### Related Skills
- `skills/execution/retrospective-facilitator/SKILL.md` — Regular reflection
- `skills/planning/risk-assessment/SKILL.md` — Prevent future incidents
- `skills/planning/decision-log/SKILL.md` — Log corrective decisions

### External Frameworks
- Google SRE, *Postmortem Culture* — Blameless postmortems
- Toyota, 5 Whys — Root cause analysis

---

**Skill type:** Component
**Domain:** Leadership & Career
