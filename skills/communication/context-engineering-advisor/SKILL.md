---
name: context-engineering-advisor
description: Guide PMs in structuring information for AI-assisted workflows — context selection, prompt architecture, memory management, and output evaluation for AI-shaped product management.
type: interactive
domain: communication
difficulty: advanced
estimated_time: "20-30 min"
prerequisites: []
outputs: ["context-engineering-guide"]
triggers:
  - "How do I structure context for AI"
  - "Improve my AI prompts"
  - "Context engineering for PM work"
  - "AI-assisted product management"
---

## Purpose

Guide PMs in structuring information for AI-assisted workflows — **what context to provide, how to architect prompts, how to manage persistent context**, and how to evaluate AI outputs for PM tasks.

---

## Application

### Question 1: PM Task

**Agent asks:** "What PM task are you trying to do with AI assistance?"

1. Writing (PRDs, user stories, specs)
2. Analysis (competitive, market, data)
3. Facilitation (workshops, meetings)
4. Decision-making (prioritization, evaluation)
5. Communication (presentations, emails, updates)

### Question 2: Context Available

**Agent asks:** "What context do you have available?"

1. Product documents (PRDs, specs, roadmaps)
2. User research (interviews, surveys, analytics)
3. Competitive data (battle cards, market analysis)
4. Internal context (organizational knowledge, constraints)
5. Historical decisions (decision logs, meeting notes)

### Output: Context Engineering Guide

```markdown
# Context Engineering for: [PM Task]

## Context Selection
| Priority | Context Type | What to Include | Format |
|----------|-------------|----------------|--------|
| 1 (essential) | [Type] | [Specific items] | [How to structure] |
| 2 (helpful) | [Type] | [Specific items] | [How to structure] |
| 3 (nice-to-have) | [Type] | [Specific items] | [How to structure] |

## Prompt Architecture
```
[System context — role + constraints + quality criteria]
[Task context — specific inputs for this task]
[Output format — exact structure expected]
[Quality checks — self-evaluation criteria]
```

## Memory Management
- **Persist across sessions:** [What to save as reusable context]
- **Refresh per task:** [What's task-specific]
- **Discard:** [What adds noise]

## Output Evaluation
- [ ] Does the output reflect the context provided?
- [ ] Would a PM recognize this as quality work?
- [ ] Are there hallucinated facts? (Always verify claims)
- [ ] Does it match the expected format?
```

---

## References

### Related Skills
- `skills/strategy/ai-shaped-readiness-advisor/SKILL.md` — AI maturity assessment
- `skills/specification/prd-template/SKILL.md` — AI-assisted PRD writing

---

**Skill type:** Interactive
**Domain:** Communication & Stakeholders
