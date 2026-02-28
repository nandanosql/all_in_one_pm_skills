---
name: product-strategy-session
description: Facilitate a complete product strategy session — positioning, problem framing, solution exploration, prioritization, stakeholder alignment, and execution planning — over 2-4 weeks.
type: workflow
domain: strategy
difficulty: advanced
estimated_time: "2-4 weeks"
prerequisites: []
outputs: ["strategy-document", "roadmap", "stakeholder-presentation"]
triggers:
  - "Run a product strategy session"
  - "Align stakeholders on product strategy"
  - "Full strategy planning"
  - "Complete product strategy exercise"
---

## Purpose

Orchestrate a **complete product strategy session** from positioning through execution planning. This workflow sequences 12+ skills across 6 phases, typically over 2-4 weeks, to align the team on what to build, for whom, and why.

---

## Application

### Phase 1: Positioning & Market Context (Week 1, Days 1-2)

**Goal:** Define target customer, problem space, and differentiation.

| Activity | Skill | Time |
|----------|-------|------|
| Define positioning | `skills/strategy/positioning-workshop/SKILL.md` | 60 min |
| Create proto-personas | `skills/discovery/proto-persona/SKILL.md` | 45 min |
| Map jobs-to-be-done | `skills/discovery/jobs-to-be-done/SKILL.md` | 45 min |
| Run PESTEL analysis | `skills/strategy/pestel-analysis/SKILL.md` | 30 min |
| Run SWOT analysis | `skills/strategy/swot-analysis/SKILL.md` | 25 min |

**Decision Point 1:** Do we have enough customer context?
- ✅ YES → Proceed to Phase 2
- ❌ NO → Schedule discovery interviews (+1 week)

---

### Phase 2: Problem Framing & Validation (Week 1, Days 3-5)

| Activity | Skill | Time |
|----------|-------|------|
| Frame the problem | `skills/discovery/problem-framing-canvas/SKILL.md` | 60 min |
| Write problem statement | `skills/discovery/problem-statement/SKILL.md` | 30 min |
| Map customer journey | `skills/discovery/customer-journey-mapping-workshop/SKILL.md` | 60 min |

**Decision Point 2:** Is the problem validated?
- ✅ YES → Proceed to Phase 3
- ❌ NO → Run discovery cycle (+1-2 weeks)

---

### Phase 3: Solution Exploration (Week 2, Days 1-3)

| Activity | Skill | Time |
|----------|-------|------|
| Generate opportunity tree | `skills/specification/opportunity-solution-tree/SKILL.md` | 60 min |
| Write epic hypotheses | `skills/planning/epic-hypothesis/SKILL.md` | 45 min |
| Map user stories | `skills/specification/user-story-mapping-workshop/SKILL.md` | 90 min |

**Decision Point 3:** Do we need to test solutions before committing?
- ✅ YES → Design experiments (+1-2 weeks)
- ❌ NO → Proceed to Phase 4

---

### Phase 4: Prioritization & Roadmap (Week 2, Days 4-5)

| Activity | Skill | Time |
|----------|-------|------|
| Choose framework | `skills/planning/prioritization-advisor/SKILL.md` | 30 min |
| Score and prioritize | [Using chosen framework] | 60 min |
| Build roadmap | `skills/planning/roadmap-planning/SKILL.md` | 90 min |
| Define OKRs | `skills/strategy/okr-framework/SKILL.md` | 30 min |

---

### Phase 5: Stakeholder Alignment (Week 3)

| Activity | Skill | Time |
|----------|-------|------|
| Write press release | `skills/strategy/press-release/SKILL.md` | 30 min |
| Build presentation | `skills/communication/executive-presentation/SKILL.md` | 60 min |
| Map stakeholders | `skills/communication/stakeholder-map/SKILL.md` | 20 min |
| Present and refine | [Live session] | 60 min |

---

### Phase 6: Execution Planning (Week 4)

| Activity | Skill | Time |
|----------|-------|------|
| Break down epics | `skills/planning/epic-breakdown-advisor/SKILL.md` | 60 min |
| Write user stories | `skills/specification/user-story/SKILL.md` | 30 min each |
| Define DoD | `skills/execution/definition-of-done/SKILL.md` | 15 min |
| Plan first sprint | `skills/execution/sprint-planning-facilitator/SKILL.md` | 45 min |

---

## Complete Workflow Summary

```
Week 1: POSITION & FRAME
├─ Day 1-2: Market Context
│  ├─ positioning-workshop (60 min)
│  ├─ proto-persona (45 min)
│  ├─ jobs-to-be-done (45 min)
│  ├─ pestel-analysis (30 min)
│  └─ swot-analysis (25 min)
├─ Day 3-5: Problem Validation
│  ├─ problem-framing-canvas (60 min)
│  ├─ problem-statement (30 min)
│  └─ customer-journey-mapping-workshop (60 min)
└─ Decision: Problem validated?

Week 2: EXPLORE & PRIORITIZE
├─ Day 1-3: Solution Exploration
│  ├─ opportunity-solution-tree (60 min)
│  ├─ epic-hypothesis (45 min)
│  └─ user-story-mapping-workshop (90 min)
├─ Day 4-5: Prioritization & Roadmap
│  ├─ prioritization-advisor (30 min)
│  ├─ roadmap-planning (90 min)
│  └─ okr-framework (30 min)
└─ Decision: Need experiments?

Week 3: ALIGN
├─ press-release (30 min)
├─ executive-presentation (60 min)
├─ stakeholder-map (20 min)
└─ Present + refine (60 min)

Week 4: EXECUTE
├─ epic-breakdown-advisor (60 min)
├─ user-story (30 min × N)
├─ definition-of-done (15 min)
└─ First sprint planning (45 min)
```

---

## Common Pitfalls

### Pitfall 1: Skipping Problem Validation

**Fix:** Strategy without validated problems is strategy theater. Always run Phase 2.

### Pitfall 2: Strategy Session Without Executive Sponsorship

**Fix:** Strategy that leadership doesn't own won't survive contact with reality. Get exec buy-in before Phase 1.

### Pitfall 3: Strategy as Permanent Process

**Fix:** Strategy sessions have an end date. Set timeboxes for each phase and commit to decisions.

---

## References

### Skills Orchestrated
All skills in Domains 1-5 can be called upon by this workflow.

### External Frameworks
- Geoffrey Moore, *Crossing the Chasm* — Positioning
- Teresa Torres, *Continuous Discovery Habits* — Problem validation
- Marty Cagan, *Inspired* — Product strategy

---

**Skill type:** Workflow
**Domain:** Strategy & Vision
