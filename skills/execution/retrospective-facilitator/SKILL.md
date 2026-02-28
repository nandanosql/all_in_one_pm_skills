---
name: retrospective-facilitator
description: Facilitate engaging sprint retrospectives that surface real issues and produce actionable improvements — using multiple retro formats adapted to team context.
type: interactive
domain: execution
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: []
outputs: ["retro-action-items"]
triggers:
  - "Run a retrospective"
  - "Facilitate our retro"
  - "Sprint retrospective"
  - "Team reflection session"
---

## Purpose

Facilitate engaging sprint retrospectives that surface real issues and produce **actionable improvements**. Offers multiple retro formats to prevent retrospective fatigue and adapts to the team's current context.

---

## Key Concepts

### Retro Format Options

| Format | Best For | Flow |
|--------|----------|------|
| **Start/Stop/Continue** | Simple, reliable | What to start, stop, continue doing |
| **Mad/Sad/Glad** | Emotional check-in | What made you mad, sad, glad |
| **4Ls** | Comprehensive review | Liked, Learned, Lacked, Longed for |
| **Sailboat** | Visualization-oriented | Wind (helps), Anchors (slows), Rocks (risks) |
| **What If** | Innovation-focused | What if we tried X? What if we stopped Y? |

---

## Application

### Turn 1: Choose Format

**Agent asks:** "What kind of retro would be most useful?"

1. Standard (Start/Stop/Continue) — reliable default
2. Emotional (Mad/Sad/Glad) — after a tough sprint
3. Deep-dive (4Ls) — after a milestone or longer period
4. Forward-looking (Sailboat) — when planning big changes
5. Surprise me — agent picks based on context

### Turn 2: Gather Input

**Agent asks:** [Prompts based on chosen format]

For Start/Stop/Continue:
- "What should we START doing that we're not doing today?"
- "What should we STOP doing that isn't helping?"
- "What should we CONTINUE that's working well?"

### Turn 3: Discuss & Prioritize

Agent clusters themes and asks team to vote on top 3 issues

### Turn 4: Create Action Items

For each prioritized theme:

```markdown
## Action Item: [Title]
**Owner:** [Name]
**Due:** [By next retro / by date]
**Success criteria:** [How we'll know this is done]
**Track in:** [Where this will be tracked]
```

### Output: Retro Summary

```markdown
# Retrospective: [Sprint Name] — [Date]
**Format:** [Chosen format]
**Attendees:** [List]

## Themes Identified
1. [Theme 1 — # votes]
2. [Theme 2]
3. [Theme 3]

## Action Items
| # | Action | Owner | Due | Status |
|---|--------|-------|-----|--------|
| 1 | [Action] | [Name] | [Date] | [Open] |
| 2 | [Action] | [Name] | [Date] | [Open] |

## Previous Retro Actions — Status Update
| # | Action | Status |
|---|--------|--------|
| [From last retro] | [Done/In progress/Not started] |

## Celebration 🎉
[What went well that deserves recognition]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Participation** | PM monologue | A few voices | Whole team contributes |
| **Safety** | People hold back | Some honesty | Candid, blame-free |
| **Action Items** | None | Vague | Specific + owned + due date |
| **Follow-through** | Previous items ignored | Some tracked | All reviewed at next retro |

---

## References

### Related Skills
- `skills/execution/sprint-planning-facilitator/SKILL.md` — Planning with retro insights
- `skills/communication/workshop-facilitation/SKILL.md` — General facilitation

---

**Skill type:** Interactive
**Domain:** Execution & Delivery
