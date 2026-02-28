---
name: standup-optimizer
description: Design effective standups — sync or async — that surface blockers, create accountability, and take only 15 minutes. Includes anti-patterns and format alternatives.
type: interactive
domain: execution
difficulty: beginner
estimated_time: "10-15 min"
prerequisites: []
outputs: ["standup-format"]
triggers:
  - "Our standups are ineffective"
  - "How should we run standups"
  - "Design an async standup"
  - "Improve team standups"
---

## Purpose

Design standups that actually **surface blockers and create accountability** without becoming status theater. Covers sync, async, and hybrid formats with anti-pattern detection.

---

## Application

### Question 1: Current Pain

**Agent asks:** "What's wrong with your current standups?"

1. Too long (>15 min)
2. No blockers surfaced
3. Status reporting (not valuable)
4. People disengaged
5. Timezone challenges
6. No standup yet — help me design one

### Question 2: Team Setup

**Agent asks:** "Team setup?"

1. Co-located / same timezone
2. Multiple timezones (overlap exists)
3. Fully distributed (no overlap)
4. Hybrid (some co-located, some remote)

### Output: Standup Format Recommendation

```markdown
# Standup Format: [Recommended Type]

## Format
**Type:** [Sync 15-min / Async Slack / Walk-the-board / Hybrid]
**Cadence:** [Daily / 3x week / 2x week]
**Time:** [Time or "async by" time]
**Duration:** [Minutes or "async reading"]

## Template
Each person answers:
1. "What did I complete since last standup?"
2. "What am I working on next?"
3. "Am I blocked on anything?"

## Rules
- [ ] 15 min maximum (use a timer)
- [ ] Blockers get taken offline, not solved in standup
- [ ] Walk the board (focus on work items, not people)
- [ ] Skip if nothing meaningful to share

## Anti-Patterns to Watch
- 🚫 Status reporting to the PM (peer-to-peer instead)
- 🚫 Problem-solving during standup (take offline)
- 🚫 Going over 15 minutes
- 🚫 People giving monologues
```

---

## References

### Related Skills
- `skills/execution/sprint-planning-facilitator/SKILL.md` — Sprint cadence
- `skills/execution/retrospective-facilitator/SKILL.md` — Improve standup in retros

---

**Skill type:** Interactive
**Domain:** Execution & Delivery
