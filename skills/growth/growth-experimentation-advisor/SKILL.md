---
name: growth-experimentation-advisor
description: Design a structured growth experimentation program — identifying levers, generating hypotheses, designing cheap tests, and building a culture of data-driven experimentation.
type: interactive
domain: growth
difficulty: advanced
estimated_time: "25-35 min"
prerequisites: ["growth-model", "ab-test-design"]
outputs: ["experimentation-roadmap"]
triggers:
  - "Build a growth experimentation program"
  - "What experiments should we run"
  - "Growth experiment pipeline"
  - "Experimentation framework"
---

## Purpose

Design a structured growth experimentation program — identifying **high-leverage growth levers, generating hypotheses, designing cheap tests**, and building a backlog of experiments to run systematically.

---

## Application

### Turn 1: Growth Levers

**Agent asks:** "Where in your AARRR funnel is the biggest opportunity?"

Agent reviews:
- Current metrics per stage (acquisition, activation, retention, revenue, referral)
- Biggest drop-off points
- Most impactful lever (usually activation or retention)

### Turn 2: Hypothesis Generation

**Agent asks:** "For the [identified lever], let's brainstorm 5+ experiment ideas."

For each idea:
```markdown
**Hypothesis:** If we [change], then [metric] will [improve by X%]
**because** [mechanism/evidence]
**Effort:** [S/M/L]
**Expected impact:** [H/M/L]
```

### Turn 3: Prioritize Experiments

```markdown
## Experiment Backlog (Prioritized)

| # | Hypothesis | Lever | Impact | Effort | ICE Score | Status |
|---|-----------|-------|--------|--------|-----------|--------|
| 1 | [Hyp] | [Lever] | [H/M/L] | [S/M/L] | [#] | [Queue/Running/Done] |
| 2 | [Hyp] | [Lever] | [H/M/L] | [S/M/L] | [#] | [Status] |
```

### Turn 4: Experiment Design (Top 1-2)

Agent generates detailed experiment designs using `skills/growth/ab-test-design/SKILL.md`

### Output

```markdown
# Growth Experimentation Roadmap

## Current Quarter Focus
**Primary lever:** [Activation/Retention/etc.]
**Target metric:** [X → Y in Z weeks]
**Experiment velocity:** [# experiments per sprint]

## Experiment Pipeline
[Prioritized backlog from Turn 3]

## Cadence
- Weekly: Review running experiments
- Biweekly: Launch new experiments
- Monthly: Update growth model with learnings
```

---

## References

### Related Skills
- `skills/growth/ab-test-design/SKILL.md` — Design individual experiments
- `skills/growth/growth-model/SKILL.md` — Growth model drives lever selection
- `skills/growth/activation-optimization/SKILL.md` — Activation experiments

---

**Skill type:** Interactive
**Domain:** Growth & Optimization
