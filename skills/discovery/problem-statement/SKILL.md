---
name: problem-statement
description: Frame a customer problem with evidence before jumping to solutions. Forces clarity on who's affected, what's broken, and why it matters — using the 5W1H framework.
type: component
domain: discovery
difficulty: beginner
estimated_time: "15-25 min"
prerequisites: []
outputs: ["problem-statement-document"]
triggers:
  - "I need to define the problem we're solving"
  - "Help me frame the customer problem"
  - "Write a problem statement"
  - "We're jumping to solutions too fast"
---

## Purpose

Frame a customer problem with evidence before jumping to solutions. This skill forces clarity on **who** is affected, **what** is broken, **why** it matters, and **how big** the impact is — so your team builds the right thing, not just the first thing someone suggested.

This is not a solution brief. It's the foundation that every PRD, epic, and user story should trace back to.

---

## Key Concepts

### The 5W1H Problem Frame

A complete problem statement answers six questions:

| Question | What It Captures |
|----------|-----------------|
| **Who** | Specific user segment affected |
| **What** | Observable behavior or gap |
| **Where** | Context where the problem occurs |
| **When** | Frequency and timing |
| **Why** | Root cause (not symptoms) |
| **How big** | Quantified impact (users, revenue, time) |

### Why This Works

- **Prevents solution bias:** Forces problem exploration before solution design
- **Creates shared understanding:** Everyone agrees on what's broken before debating fixes
- **Enables prioritization:** Quantified impact lets you compare problems objectively
- **Validates assumptions:** Evidence requirements surface what you actually know vs. assume

### Anti-Patterns (What This Is NOT)

- **Not a solution disguised as a problem:** "The problem is we don't have Feature X" ← This is a solution, not a problem
- **Not a complaint:** "Users are unhappy" ← Too vague, no actionable insight
- **Not a metric:** "Churn is 5%" ← This is a symptom, not the problem

### When to Use This

- Starting a new initiative or feature
- Justifying work in a roadmap or PRD
- Aligning stakeholders on what to solve
- Before any discovery research to clarify focus

### When NOT to Use This

- When the problem is already well-documented (update, don't restart)
- For bugs or technical issues (use bug reports)
- When you need a solution spec (write a PRD instead)

---

## Application

### Step 1: Identify the User Segment

Be specific. "Users" is too broad.

```markdown
**Who is affected:**
[Specific persona or segment — e.g., "Trial users in their first 7 days"]

**How many:** [Number or % of total user base]

**Evidence:** [Source: analytics, interviews, support tickets, etc.]
```

**Quality check:**
- [ ] Can you name a real person who has this problem?
- [ ] Is this a segment (not "all users")?

---

### Step 2: Describe the Observable Problem

State what's happening (or not happening) in concrete, observable terms.

```markdown
**What is happening:**
[Observable behavior — e.g., "72% of trial users abandon onboarding at step 3"]

**What should be happening:**
[Expected behavior — e.g., "Trial users complete onboarding and reach first value within 10 minutes"]

**Gap:**
[Delta between current and expected — e.g., "62% gap between current and target completion"]
```

**Quality check:**
- [ ] Is this stated as observable behavior (not an opinion)?
- [ ] Can someone else verify this independently?

---

### Step 3: Establish Context (Where & When)

```markdown
**Where it occurs:**
[Environment, workflow step, or touchpoint — e.g., "During web onboarding, specifically the 'connect your data source' step"]

**When it occurs:**
[Frequency and timing — e.g., "Every new signup; worse on mobile (85% drop vs 65% desktop)"]

**How long has this existed:**
[Timeline — e.g., "Since we added the data source integration in Q3 2025"]
```

---

### Step 4: Analyze Root Cause (Why)

Use the 5 Whys or Ishikawa to dig past symptoms.

```markdown
**Symptom:** [What you first noticed]
**Why 1:** [First-level cause]
**Why 2:** [Deeper cause]
**Why 3:** [Deeper still]
**Root cause hypothesis:**
[Your best understanding of the fundamental cause]

**Confidence level:** [High / Medium / Low]
**What would change your mind:** [Evidence that would disprove this]
```

---

### Step 5: Quantify Impact (How Big)

```markdown
**Users affected:** [Number and % of relevant segment]
**Revenue impact:** [$ lost, at-risk, or opportunity cost per month/quarter]
**Operational cost:** [Support tickets, manual workarounds, team time]
**Strategic impact:** [Alignment with company goals, competitive risk]

**If we do nothing:** [What happens in 3/6/12 months]
```

---

### Step 6: Assemble the Problem Statement

```markdown
# Problem Statement: [Descriptive Title]

## Summary
[User segment] is experiencing [observable problem] when [context],
resulting in [quantified impact]. This has been occurring since [timeline]
and is caused by [root cause hypothesis].

## Evidence
- [Data point 1 + source]
- [Data point 2 + source]
- [Data point 3 + source]

## Impact
- **Users:** [X affected]
- **Revenue:** [$Y at risk]
- **Strategic:** [alignment with goal Z]

## What Success Looks Like
[Measurable outcome — e.g., "Onboarding completion increases from 28% to 70%"]

## What We Don't Know Yet
- [Open question 1]
- [Open question 2]
```

---

## Examples

### ✅ Good Example

```markdown
# Problem Statement: Trial User Onboarding Abandonment

## Summary
Trial users in their first 7 days are abandoning onboarding at the "Connect Data Source"
step (Step 3 of 5), resulting in a 72% drop-off rate. This affects approximately 3,200
new signups per month and represents ~$480K in lost ARR annually. The root cause is that
the data source connection requires technical credentials most trial users don't have
access to immediately.

## Evidence
- Mixpanel funnel: 72% drop at Step 3 (last 90 days, n=9,600)
- Support tickets: 340/month mention "can't connect" or "where do I find credentials"
- Exit survey (n=180): 64% cite "too complicated" as reason for not completing

## Impact
- Users: 3,200/month affected (72% of trial signups)
- Revenue: ~$480K ARR (assuming 5% trial→paid at $250/mo ARPU)
- Strategic: Core growth metric (trial activation) blocked

## What Success Looks Like
Trial onboarding completion increases from 28% to 65%+ within 60 days of fix.

## What We Don't Know Yet
- Would a sandbox/demo data option satisfy the "connect data" requirement?
- Are there segments (technical users) who don't hit this barrier?
```

**Why this works:** Specific segment, quantified impact, root cause with evidence, clear success metric, honest about unknowns.

### ❌ Bad Example

```markdown
# Problem: Users don't like our onboarding

Users are complaining about onboarding. We should make it simpler.
Maybe add a tutorial or something.
```

**Why this fails:** No specific segment, no data, solution embedded in the problem, no impact quantification, no root cause analysis.

---

## Quality Rubric

Score each dimension 0-2. **Target: 8+ out of 10.**

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Specificity** | "Users" (generic) | Named segment but broad | Named persona + count |
| **Evidence** | Opinion only | Some data, one source | Multiple data sources, cited |
| **Impact** | Not quantified | Partial (users OR revenue) | Users + revenue + strategic |
| **Root Cause** | Not explored | Surface-level why | 5-Whys with confidence level |
| **Objectivity** | Solution embedded | Mostly neutral | Pure problem, no solutions |

**If score < 8:** Revise the weakest dimension before sharing with stakeholders.

---

## Common Pitfalls

### Pitfall 1: Solution Masquerading as Problem

**Symptom:** "The problem is we don't have a mobile app"

**Consequence:** Skips problem validation entirely. You might build a mobile app for a problem that has a simpler solution.

**Fix:** Reframe: *"Mobile users can't complete [task] because [reason]."* Now you can explore multiple solutions.

---

### Pitfall 2: Boiling the Ocean

**Symptom:** Problem statement covers 5 different issues for 3 different segments.

**Consequence:** Too broad to act on. Team can't align because everyone reads a different problem.

**Fix:** One problem per statement. If you have multiple problems, write multiple statements and prioritize.

---

### Pitfall 3: Metrics Without Meaning

**Symptom:** "Our NPS dropped 10 points"

**Consequence:** NPS is a lagging indicator. It tells you something is wrong but not what, why, or for whom.

**Fix:** Dig into the verbatims and segment data. Find the specific behavior driving the metric.

---

### Pitfall 4: Skipping "What We Don't Know"

**Symptom:** Problem statement reads as 100% certain.

**Consequence:** False confidence leads to building the wrong thing. You skip validation because "we already know."

**Fix:** Always include unknowns and confidence levels. It's intellectually honest and guides next steps.

---

## References

### Related Skills
- `skills/discovery/proto-persona/SKILL.md` — Define the "who" in your problem statement
- `skills/discovery/jobs-to-be-done/SKILL.md` — Understand what the user is trying to accomplish
- `skills/discovery/discovery-interview-prep/SKILL.md` — Validate your problem with real users
- `skills/discovery/discovery-process/SKILL.md` — Full discovery workflow that uses this skill

### External Frameworks
- 5W1H Problem Frame — Foundation of structured problem definition
- 5 Whys (Taiichi Ohno, Toyota) — Root cause analysis
- MITRE Problem Framing — Look Inward / Look Outward / Reframe

---

**Skill type:** Component
**Domain:** Discovery & Research
**Prerequisites:** None
