---
name: discovery-process
description: Complete end-to-end discovery cycle — frame problem, plan research, conduct interviews, synthesize insights, validate solutions, and decide. Orchestrates 8+ component and interactive skills over 3-4 weeks.
type: workflow
domain: discovery
difficulty: advanced
estimated_time: "3-4 weeks"
prerequisites: []
outputs: ["discovery-report", "validated-problem-statement", "proto-personas", "opportunity-backlog"]
triggers:
  - "I need to run a full discovery cycle"
  - "We need to understand the problem before building"
  - "Run customer discovery"
  - "Start a discovery process"
---

## Purpose

Run a complete discovery cycle from **problem framing through validated solutions**. This workflow orchestrates multiple skills into a structured process that ensures you understand the problem, validate it with real users, and only commit to solutions backed by evidence.

---

## Key Concepts

### Discovery Process Overview

```
Week 1: UNDERSTAND
├─ Phase 1: Frame the Problem (Day 1-2)
├─ Phase 2: Plan Research (Day 3)
└─ Decision Point: Ready to research?

Week 2: RESEARCH
├─ Phase 3: Conduct Research (Week 1-2)
└─ Decision Point: Reached saturation?

Week 3: SYNTHESIZE & VALIDATE
├─ Phase 4: Synthesize Insights (End of Week 2)
├─ Phase 5: Generate & Validate Solutions (Week 3)
└─ Decision Point: Solution validated?

Week 4: DECIDE
└─ Phase 6: Decide & Document (End of Week 3-4)
```

### Anti-Patterns

- **Not a one-time event:** Discovery is continuous, not a "project phase"
- **Not optional:** Discovery isn't a luxury — it's the cheapest way to avoid building the wrong thing
- **Not just interviews:** Combines qualitative (interviews) + quantitative (analytics, surveys) evidence

---

## Application

### Phase 1: Frame the Problem (Day 1-2)

**Goal:** Define what problem you're investigating and for whom.

**Activities:**
| Activity | Skill Used | Time |
|----------|-----------|------|
| Write initial problem statement | `skills/discovery/problem-statement/SKILL.md` | 30 min |
| Create proto-personas | `skills/discovery/proto-persona/SKILL.md` | 30-60 min |
| Map jobs-to-be-done | `skills/discovery/jobs-to-be-done/SKILL.md` | 30 min |
| Challenge the framing | `skills/discovery/problem-framing-canvas/SKILL.md` | 45 min |

**Outputs:**
- [ ] Initial problem statement (hypothesis)
- [ ] 2-3 proto-personas
- [ ] JTBD statements
- [ ] Reframed problem (if applicable)

**Decision Point 1:** Do we have enough context to start research?
- ✅ YES → Proceed to Phase 2
- ❌ NO → Spend 1 more day on desk research and stakeholder interviews

---

### Phase 2: Plan Research (Day 3)

**Goal:** Design the research plan — who to talk to, what to ask, how to measure.

**Activities:**
| Activity | Skill Used | Time |
|----------|-----------|------|
| Prepare interview guide | `skills/discovery/discovery-interview-prep/SKILL.md` | 30 min |
| Design validation survey | `skills/discovery/survey-design/SKILL.md` | 30 min |
| Create competitive context | `skills/discovery/company-research/SKILL.md` | 45 min |

**Outputs:**
- [ ] Interview guide (5-8 interviews planned)
- [ ] Survey draft (if applicable)
- [ ] Competitive landscape overview

---

### Phase 3: Conduct Research (Week 1-2)

**Goal:** Talk to real users and gather evidence.

**Activities:**
- Conduct 5-8 discovery interviews
- Analyze behavioral analytics (funnels, drop-offs)
- Review support tickets and NPS verbatims
- Run validation survey (if sample size allows)

**Outputs:**
- [ ] Interview transcripts/notes with key quotes
- [ ] Analytics insights
- [ ] Survey results (if applicable)

**Decision Point 2:** Have we reached saturation?
- ✅ YES (hearing same themes from multiple sources) → Proceed to Phase 4
- ❌ NO → Schedule 3-5 more interviews; expand to adjacent segments

---

### Phase 4: Synthesize Insights (End of Week 2)

**Goal:** Turn raw data into actionable themes.

**Activities:**
- Cluster interview insights into themes (affinity diagram)
- Update proto-personas with validated attributes
- Map the customer journey based on actual data
- Identify the top 3-5 validated pain points

| Activity | Skill Used | Time |
|----------|-----------|------|
| Map validated journey | `skills/discovery/customer-journey-map/SKILL.md` | 45 min |
| Map validated journey (workshop) | `skills/discovery/customer-journey-mapping-workshop/SKILL.md` | 60 min |

**Outputs:**
- [ ] Insight themes (clustered, prioritized)
- [ ] Updated proto-personas
- [ ] Validated customer journey map
- [ ] Refined problem statement (incorporating evidence)

---

### Phase 5: Generate & Validate Solutions (Week 3)

**Goal:** Generate solution hypotheses and test them lightly.

**Activities:**
| Activity | Skill Used | Time |
|----------|-----------|------|
| Generate opportunity tree | `skills/specification/opportunity-solution-tree/SKILL.md` | 60 min |
| Write epic hypotheses | `skills/planning/epic-hypothesis/SKILL.md` | 30 min each |
| Design validation experiments | `skills/growth/ab-test-design/SKILL.md` | 30 min |

**Outputs:**
- [ ] Opportunity-solution tree
- [ ] 2-3 solution hypotheses with success criteria
- [ ] Lightweight validation results (concept tests, prototypes, or fake doors)

**Decision Point 3:** Did experiments validate a solution direction?
- ✅ YES → Proceed to Phase 6
- ❌ NO → Iterate on solution hypotheses or revisit problem framing

---

### Phase 6: Decide & Document (End of Week 3-4)

**Goal:** Commit to a direction and package findings for stakeholders.

**Activities:**
- Write the final discovery report
- Update the problem statement to "validated" status
- Create the initial opportunity backlog
- Present findings to stakeholders

**Outputs:**
- [ ] Discovery report (findings, recommendations, evidence)
- [ ] Validated problem statement
- [ ] Opportunity backlog (prioritized)
- [ ] Stakeholder presentation deck

---

## Complete Workflow Summary

```
Week 1:
├─ Day 1-2: Frame the Problem
│  ├─ problem-statement (30 min)
│  ├─ proto-persona (30-60 min)
│  ├─ jobs-to-be-done (30 min)
│  └─ problem-framing-canvas (45 min)
│
├─ Day 3: Plan Research
│  ├─ discovery-interview-prep (30 min)
│  ├─ survey-design (30 min)
│  └─ company-research (45 min)
│
└─ Decision: Ready to research?

Week 2:
├─ Conduct 5-8 interviews
├─ Analyze behavioral data
├─ Run validation survey
└─ Decision: Reached saturation?

Week 3:
├─ Synthesize insights
│  ├─ customer-journey-map (45 min)
│  └─ Cluster themes + update personas
│
├─ Generate & validate solutions
│  ├─ opportunity-solution-tree (60 min)
│  └─ epic-hypothesis (30 min each)
│
└─ Decision: Solution validated?

Week 4:
└─ Document & present
   ├─ Final discovery report
   ├─ Opportunity backlog
   └─ Stakeholder presentation
```

**Total estimated effort:** 25-40 hours over 3-4 weeks

---

## Common Pitfalls

### Pitfall 1: Skipping Customer Interviews

**Symptom:** "We already know what users want from support tickets."

**Fix:** Support tickets are biased toward vocal users with acute problems. Interviews reveal quiet majority needs.

### Pitfall 2: Not Reaching Saturation

**Symptom:** After 3 interviews, "We've heard enough."

**Fix:** Saturation typically requires 5-8 interviews per segment. If themes are still emerging, keep going.

### Pitfall 3: Discovery Without Decision Points

**Symptom:** Teams run discovery forever, never transitioning to execution.

**Fix:** Each phase has an explicit decision point. If the answer is "yes," move forward. Set timeboxes.

### Pitfall 4: Treating Discovery as a One-Time Activity

**Symptom:** "We did discovery last quarter, we don't need to do it again."

**Fix:** Discovery is continuous. Markets change, users evolve, assumptions expire. Run mini-discovery cycles quarterly.

---

## References

### Skills Orchestrated
- `skills/discovery/problem-statement/SKILL.md`
- `skills/discovery/proto-persona/SKILL.md`
- `skills/discovery/jobs-to-be-done/SKILL.md`
- `skills/discovery/problem-framing-canvas/SKILL.md`
- `skills/discovery/discovery-interview-prep/SKILL.md`
- `skills/discovery/survey-design/SKILL.md`
- `skills/discovery/company-research/SKILL.md`
- `skills/discovery/customer-journey-map/SKILL.md`
- `skills/discovery/customer-journey-mapping-workshop/SKILL.md`
- `skills/specification/opportunity-solution-tree/SKILL.md`
- `skills/planning/epic-hypothesis/SKILL.md`

### External Frameworks
- Teresa Torres, *Continuous Discovery Habits* (2021)
- Rob Fitzpatrick, *The Mom Test* (2013)
- Marty Cagan, *Inspired* (2017)

---

**Skill type:** Workflow
**Domain:** Discovery & Research
