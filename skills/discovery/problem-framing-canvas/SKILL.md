---
name: problem-framing-canvas
description: Lead through MITRE Problem Framing — Look Inward (biases, assumptions), Look Outward (stakeholders, context), Reframe (new perspectives) — to ensure you're solving the right problem.
type: interactive
domain: discovery
difficulty: advanced
estimated_time: "30-45 min"
prerequisites: ["problem-statement"]
outputs: ["problem-frame-document"]
triggers:
  - "Are we solving the right problem"
  - "Help me reframe this problem"
  - "I think we're approaching this wrong"
  - "Run problem framing"
---

## Purpose

Guide through the MITRE Problem Framing methodology to ensure you're solving the **right problem** — not just the first one you defined. Uses three lenses: **Look Inward** (examine your own biases), **Look Outward** (understand stakeholder perspectives), and **Reframe** (generate alternative problem definitions).

---

## Key Concepts

### MITRE Problem Framing

```
┌─────────────┐     ┌──────────────┐     ┌───────────┐
│ LOOK INWARD │ ──► │ LOOK OUTWARD │ ──► │ REFRAME   │
│             │     │              │     │           │
│ Your biases │     │ Stakeholder  │     │ New ways  │
│ Assumptions │     │ perspectives │     │ to see    │
│ Constraints │     │ Context      │     │ the       │
│ you impose  │     │ Real data    │     │ problem   │
└─────────────┘     └──────────────┘     └───────────┘
```

### Facilitation Protocol

This skill asks **6-8 adaptive questions** across three phases:

**Phase 1: Look Inward (2-3 questions)**
- What assumptions are you making?
- What constraints are self-imposed vs. real?
- Whose perspective is missing from your framing?

**Phase 2: Look Outward (2-3 questions)**
- Who else is affected by this problem?
- What data challenges your current framing?
- What would a different stakeholder say?

**Phase 3: Reframe (2 questions)**
- How would you state this problem if you had unlimited resources?
- What if the opposite of your assumption were true?

---

## Application

### Question 1: Current Problem Statement

**Agent asks:** "What problem are you currently trying to solve? Share your existing problem statement."

(User shares their current problem definition)

---

### Question 2: Look Inward — Assumptions

**Agent asks:** "What are you assuming is true about this problem? List 3-5 assumptions."

**Then agent challenges each:**
- "What evidence supports this?"
- "What would change if this assumption were wrong?"
- "Is this a fact or a belief?"

---

### Question 3: Look Inward — Constraints

**Agent asks:** "What constraints are you working within?"

**Options:**
1. **Budget/resource constraints** — Limited team, money, or time
2. **Technical constraints** — Platform, architecture, or integration limits
3. **Organizational constraints** — Politics, approvals, dependencies
4. **Market constraints** — Competitive pressure, timeline
5. **Other** (describe)

**Then agent asks:** "Which of these constraints are real vs. self-imposed?"

---

### Question 4: Look Outward — Stakeholders

**Agent asks:** "Who else is affected by this problem beyond the primary user?"

Prompts:
- "Who benefits if this problem is solved?"
- "Who is inconvenienced if this problem is solved?"
- "Whose behavior would need to change?"

---

### Question 5: Look Outward — Counter-Evidence

**Agent asks:** "What data or feedback contradicts your current understanding of the problem?"

---

### Question 6: Reframe — Alternative Framings

**Agent generates 3 alternative problem framings:**

```markdown
## Alternative Problem Framings

### Framing 1: [Shift in user segment]
"What if the problem isn't [current framing] but actually [reframed version]?"

### Framing 2: [Shift in root cause]
"What if the cause isn't [assumed cause] but [alternative cause]?"

### Framing 3: [Shift in scope]
"What if we zoom out/in: [broader or narrower problem]?"

## Recommended Framing
Based on the analysis: [recommendation with rationale]

## Next Steps
- [ ] Validate the new framing with [stakeholder/data source]
- [ ] Update the problem statement
- [ ] Share with team for alignment
```

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Assumption Surfacing** | None examined | Listed but unchallenged | Listed + evidence-tested |
| **Stakeholder Coverage** | Primary user only | 2-3 perspectives | Full stakeholder map |
| **Counter-Evidence** | None sought | Acknowledged but dismissed | Integrated into reframing |
| **Alternative Framings** | Same problem, different words | Genuinely different angle | Multiple valid reframings |
| **Actionability** | No next steps | "We should think about it" | Specific validation plan |

---

## Common Pitfalls

### Pitfall 1: Confirmation Bias

**Symptom:** Reframing exercise produces the same conclusion you started with.

**Fix:** Force yourself to argue the opposite position. If your reframe doesn't feel uncomfortable, you haven't actually reframed.

### Pitfall 2: Analysis Paralysis

**Symptom:** Endlessly reframing without committing to a direction.

**Fix:** Set a timebox. Reframe once, test the best framing with real users/data, then commit.

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Input: existing problem statement to reframe
- `skills/discovery/discovery-interview-prep/SKILL.md` — Validate new framing through interviews
- `skills/discovery/discovery-process/SKILL.md` — Full workflow that includes problem framing

### External Frameworks
- MITRE Problem Framing Guide — Three-lens approach
- Edward de Bono, *Six Thinking Hats* — Multi-perspective analysis

---

**Skill type:** Interactive
**Domain:** Discovery & Research
