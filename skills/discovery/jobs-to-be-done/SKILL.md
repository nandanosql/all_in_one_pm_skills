---
name: jobs-to-be-done
description: Understand what customers are trying to accomplish using the JTBD framework. Captures functional, emotional, and social jobs to reveal true motivations behind product usage.
type: component
domain: discovery
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: []
outputs: ["jtbd-statement", "job-map"]
triggers:
  - "What job is the customer hiring our product for"
  - "Help me write a jobs to be done"
  - "I need to understand customer motivations"
  - "Why are people using our product"
---

## Purpose

Understand what customers are truly trying to accomplish — not what features they want, but what **progress** they're trying to make in their lives. JTBD reveals the underlying motivations that drive product adoption, switching behavior, and loyalty.

This is not a feature list or a requirements doc. It's a lens for understanding **why** people buy, use, and abandon products.

---

## Key Concepts

### The JTBD Framework

People don't buy products — they **hire** products to make progress in a specific circumstance.

**Three types of jobs:**

| Job Type | What It Captures | Example |
|----------|-----------------|---------|
| **Functional** | The practical task | "Help me track my expenses" |
| **Emotional** | How they want to feel | "Help me feel in control of my finances" |
| **Social** | How they want to be perceived | "Help me look financially responsible to my partner" |

### The JTBD Statement Format

```
When [situation/trigger],
I want to [motivation/action],
so I can [expected outcome].
```

**Advanced format (with constraints):**
```
When [situation/trigger],
I want to [motivation/action],
so I can [expected outcome],
but [current constraints/barriers].
```

### The Four Forces of Progress

Why people switch to a new solution:

```
PUSH (from current) ──────► ◄────── PULL (toward new)
"Current solution is        "New solution promises
 failing me"                 something better"

HABIT (stay with current) ─► ◄── ANXIETY (about new)
"I know how this works"     "What if the new thing
                             is worse?"
```

**Switch happens when:** Push + Pull > Habit + Anxiety

### When to Use This

- Defining product positioning (what job do we serve?)
- Prioritizing features (does this help the core job?)
- Understanding churn (what job is being underserved?)
- Competitive analysis (who else is hired for this job?)

### When NOT to Use This

- For tactical feature specs (use user stories)
- When you need UI-level detail (use design briefs)
- As a replacement for quantitative data (JTBD is qualitative)

---

## Application

### Step 1: Identify the Triggering Situation

```markdown
**Trigger event:** [What happened that created the need]
**Context:** [Circumstances surrounding the trigger]
**Frequency:** [How often this situation occurs]

**Example:** "When my quarterly board meeting is next week and I don't have revenue projections ready..."
```

**Quality check:**
- [ ] Is the situation specific (not evergreen)?
- [ ] Does it describe a real moment, not a general desire?

---

### Step 2: Define the Functional Job

```markdown
**Functional JTBD:**
When [specific situation],
I want to [concrete action],
so I can [measurable outcome].

**Job steps (job map):**
1. [Define] — Determine what needs to be done
2. [Locate] — Find inputs needed
3. [Prepare] — Set up to do the job
4. [Confirm] — Verify readiness
5. [Execute] — Perform the core action
6. [Monitor] — Check progress
7. [Modify] — Make adjustments
8. [Conclude] — Finish and wrap up
```

---

### Step 3: Uncover Emotional and Social Jobs

```markdown
**Emotional JTBD:**
When [situation],
I want to feel [emotional state],
so I can [emotional outcome].

**Social JTBD:**
When [situation],
I want to be seen as [social perception],
so I can [social outcome].
```

---

### Step 4: Map the Four Forces

```markdown
**Push (away from current solution):**
- [What's failing about the current approach]
- [Specific frustrations]

**Pull (toward new solution):**
- [What the new solution promises]
- [Specific benefits imagined]

**Habit (resistance to change):**
- [What's comfortable about the status quo]
- [Switching costs]

**Anxiety (fear of new):**
- [What could go wrong]
- [Unknowns about the new solution]
```

---

### Step 5: Identify Competing Solutions

```markdown
**Who else is hired for this job:**
| Solution | Job it serves | Why chosen | Where it falls short |
|----------|--------------|------------|---------------------|
| [Direct competitor] | [Same job] | [Reason] | [Gap] |
| [Indirect competitor] | [Partial job] | [Reason] | [Gap] |
| [Manual workaround] | [Same job, poorly] | [Free/familiar] | [Gap] |
| [Non-consumption] | [Job ignored] | [Not worth solving] | [Opportunity] |
```

---

## Examples

### ✅ Good Example

```markdown
**Functional JTBD:**
When I'm preparing for a quarterly board meeting and need revenue projections,
I want to pull accurate, segmented financial data into a presentation-ready format,
so I can present confidently and answer follow-up questions without scrambling.

**Emotional JTBD:**
When presenting at the board meeting,
I want to feel prepared and credible,
so I can maintain my reputation as someone who has the numbers.

**Social JTBD:**
When the CEO introduces my section,
I want to be seen as data-driven and strategic,
so I can build trust for my budget requests.

**Four Forces:**
- Push: Current tool requires manual export + reformatting (3 hours)
- Pull: New tool promises one-click board-ready reports
- Habit: "I know how to make my spreadsheet work"
- Anxiety: "What if the data is wrong and I look unprepared?"
```

### ❌ Bad Example

```markdown
**JTBD:** Users want better analytics so they can make decisions.
```

**Why this fails:** No situation context, generic user, vague outcome, no emotional/social dimension, no competing solutions analysis.

---

## Quality Rubric

Score each dimension 0-2. **Target: 8+ out of 10.**

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Situation** | Generic or missing | Named but vague | Specific trigger + context |
| **Functional Job** | "Want better X" | Action without outcome | Action + measurable outcome |
| **Emotional/Social** | Not explored | One dimension | Both emotional + social jobs |
| **Four Forces** | Not mapped | Push/Pull only | All four forces with specifics |
| **Competing Solutions** | Not listed | Direct competitors only | Direct + indirect + non-consumption |

---

## Common Pitfalls

### Pitfall 1: Feature-Level Job Statements

**Symptom:** "When I open the app, I want a dashboard, so I can see metrics."

**Consequence:** This is a feature request, not a job. It constrains solutions to "dashboard."

**Fix:** Go up one level: "When I start my Monday, I want to know if anything needs my attention, so I can prioritize my day." Now you can solve this many ways.

---

### Pitfall 2: Ignoring Emotional/Social Jobs

**Symptom:** JTBD analysis covers only functional tasks.

**Consequence:** You miss the real reasons people switch (or don't). Emotional jobs often trump functional ones.

**Fix:** Always ask: "How do they want to **feel**?" and "How do they want to **appear**?" These unlock positioning and messaging.

---

### Pitfall 3: Too Many Jobs

**Symptom:** 15 JTBD statements for one product.

**Consequence:** No clear positioning. Product tries to serve too many jobs and does none well.

**Fix:** Identify the **primary job** (the one people "hire" you for most) and 2-3 related jobs. Prioritize ruthlessly.

---

## References

### Related Skills
- `skills/discovery/proto-persona/SKILL.md` — Who has this job
- `skills/discovery/problem-statement/SKILL.md` — Problems that arise while doing the job
- `skills/discovery/customer-journey-map/SKILL.md` — Map the job's touchpoints
- `skills/strategy/positioning-statement/SKILL.md` — Position your product as the best hire for the job

### External Frameworks
- Clayton Christensen, *Competing Against Luck* (2016)
- Tony Ulwick, *What Customers Want* (Outcome-Driven Innovation)
- Bob Moesta, *Demand-Side Sales 101* (Four Forces)
- Alan Klement, *When Coffee and Kale Compete*

---

**Skill type:** Component
**Domain:** Discovery & Research
**Prerequisites:** None
