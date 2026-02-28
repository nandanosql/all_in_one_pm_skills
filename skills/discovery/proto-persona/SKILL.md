---
name: proto-persona
description: Create hypothesis-driven user personas before doing full research. Uses behavioral attributes, goals, and frustrations to model target users quickly for early-stage alignment.
type: component
domain: discovery
difficulty: beginner
estimated_time: "15-20 min"
prerequisites: []
outputs: ["proto-persona-card"]
triggers:
  - "I need to define who my user is"
  - "Create a persona"
  - "Who is this product for"
  - "Help me build a user persona"
---

## Purpose

Create hypothesis-driven user personas before investing in full user research. Proto-personas capture your **best current understanding** of who your users are — their behaviors, goals, frustrations, and context — so your team has a shared reference point from day one.

This is not a research-validated persona. It's a testable hypothesis about your user that you'll refine through discovery interviews.

---

## Key Concepts

### Proto-Persona vs. Full Persona

| Proto-Persona | Full Persona |
|---------------|-------------|
| Based on assumptions + available data | Based on primary research |
| Created in 15-20 minutes | Created over 2-4 weeks |
| Hypothesis to validate | Validated representation |
| Use for early alignment | Use for design decisions |

### The Proto-Persona Card

A proto-persona captures four dimensions:

1. **Demographics & Context** — Who they are and where they work
2. **Behaviors** — How they currently solve the problem (observable actions)
3. **Goals & Needs** — What they're trying to achieve (desired outcomes)
4. **Frustrations & Pain Points** — What's blocking them (evidence of problems)

### Anti-Patterns (What This Is NOT)

- **Not a marketing segment:** "Males 25-34 in urban areas" ← Demographics alone aren't personas
- **Not aspirational:** "Sarah is a power user who loves our product" ← This describes who you wish they were
- **Not static:** Proto-personas should evolve as you learn — tag them with confidence levels

### When to Use This

- Starting a new product/feature with limited user research
- Aligning team on target user before discovery
- Feeding into problem statements, user stories, and journey maps
- Kickstarting a positioning workshop

### When NOT to Use This

- When you have validated personas from recent research (use those)
- As a substitute for user research (proto-personas are the start, not the end)
- For mature products where user segments are well-understood

---

## Application

### Step 1: Name and Summarize

```markdown
## Proto-Persona: [First Name + Role]

**One-liner:** [Who they are + primary goal in one sentence]
**Confidence:** [High / Medium / Low — how sure are you this person exists?]
**Based on:** [Source: interviews, support tickets, analytics, team knowledge, etc.]
```

---

### Step 2: Demographics & Context

```markdown
### Demographics & Context
- **Role/Title:** [e.g., "Marketing Manager at a 50-person B2B SaaS"]
- **Experience level:** [Junior / Mid / Senior]
- **Tech savviness:** [Low / Medium / High]
- **Company size:** [Range]
- **Reports to:** [Who they answer to]
- **Day-to-day tools:** [Software/tools they use daily]
```

**Quality check:**
- [ ] Is this specific enough to distinguish from other personas?
- [ ] Does the context affect how they'd use your product?

---

### Step 3: Behaviors (How They Currently Solve the Problem)

```markdown
### Behaviors
- [Observable action 1 — e.g., "Manually exports data to Excel weekly"]
- [Observable action 2 — e.g., "Asks engineering for custom reports via Slack"]
- [Observable action 3 — e.g., "Uses competitor tool X for task Y but not for Z"]

**Current workarounds:** [How they hack around the problem today]
**Time spent on workarounds:** [Hours/week estimate]
```

**Quality check:**
- [ ] Are these observable behaviors (not opinions about them)?
- [ ] Do the workarounds reveal unmet needs?

---

### Step 4: Goals & Needs

```markdown
### Goals & Needs
- **Primary goal:** [What they're ultimately trying to achieve]
- **Secondary goal:** [Related goal that influences decisions]
- **Success metric:** [How THEY measure success — not your product metric]

**Job-to-be-done:** When [situation], I want to [action], so I can [outcome].
```

---

### Step 5: Frustrations & Pain Points

```markdown
### Frustrations & Pain Points
- **Pain 1:** [Specific frustration + frequency]
- **Pain 2:** [Specific frustration + frequency]
- **Pain 3:** [Specific frustration + frequency]

**Biggest blocker:** [The one thing that, if solved, would matter most]
**Quote (real or hypothetical):** "[Something they'd actually say]"
```

---

### Step 6: Confidence Assessment

```markdown
### Validation Status
| Attribute | Confidence | Evidence Source |
|-----------|-----------|----------------|
| Demographics | [H/M/L] | [Source] |
| Behaviors | [H/M/L] | [Source] |
| Goals | [H/M/L] | [Source] |
| Pain Points | [H/M/L] | [Source] |

**Next validation step:** [What you'd do to increase confidence]
```

---

## Examples

### ✅ Good Example

```markdown
## Proto-Persona: Maya — Marketing Manager

**One-liner:** Mid-level marketing manager at a B2B SaaS who needs campaign performance data without relying on engineering.
**Confidence:** Medium
**Based on:** 3 customer interviews, 45 support tickets mentioning "reports"

### Demographics & Context
- **Role:** Marketing Manager, 3 years experience
- **Company:** 50-person B2B SaaS (Series A)
- **Tech savviness:** Medium (comfortable with tools, not SQL)
- **Reports to:** VP Marketing who demands weekly metrics
- **Tools:** HubSpot, Google Analytics, Slack, Google Sheets

### Behaviors
- Exports HubSpot data to Excel every Monday (45 min)
- Asks data team for custom queries via Slack (2-3 day turnaround)
- Screenshots dashboards for leadership presentations
- Maintains her own "shadow spreadsheet" of key metrics

### Goals & Needs
- **Primary:** Get campaign performance data in real-time without waiting
- **JTBD:** When my VP asks for campaign results, I want to pull a report instantly, so I can look competent and make faster decisions.

### Frustrations
- **Pain 1:** 2-3 day wait for custom reports from data team (weekly)
- **Pain 2:** Data is in 4 tools, no unified view (daily frustration)
- **Pain 3:** VP asks questions in meetings she can't answer on the spot

**Quote:** "I spend Monday mornings doing data janitor work instead of strategy."
```

### ❌ Bad Example

```markdown
## Persona: Marketing Professional
- Age: 25-45
- Likes social media
- Wants to do their job well
- Uses the internet
```

**Why this fails:** Generic demographics, no behaviors, no specific goals, no evidence, could describe anyone.

---

## Quality Rubric

Score each dimension 0-2. **Target: 8+ out of 10.**

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Specificity** | "A user" | Named + role | Name + role + context + tools |
| **Behaviors** | None listed | Generic behaviors | Observable, current workarounds |
| **Goals** | Vague ("be successful") | General goals | JTBD format with outcome |
| **Pain Points** | None or generic | Listed but not specific | Specific + frequency + impact |
| **Confidence** | Not assessed | Single confidence level | Per-attribute with evidence |

---

## Common Pitfalls

### Pitfall 1: Persona as Marketing Segment

**Symptom:** "Female, 25-34, urban, college-educated, $60-80K income"

**Consequence:** Demographics don't predict product usage. Two people with identical demographics may have completely different needs.

**Fix:** Lead with **behaviors and goals**, not demographics. Demographics are context, not identity.

---

### Pitfall 2: Aspirational Persona

**Symptom:** "Alex is a passionate early adopter who loves trying new tools"

**Consequence:** You're describing your ideal customer, not your actual user. Products designed for aspirational users miss real pain points.

**Fix:** Base the persona on observable evidence — support tickets, behavior data, interviews. Include frustrations.

---

### Pitfall 3: Too Many Personas

**Symptom:** 8 proto-personas, each with subtle differences.

**Consequence:** Team can't focus. Every feature is justified by "some persona."

**Fix:** Start with 2-3 max. If you can't distinguish two personas by their behaviors, merge them.

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Personas feed into problem statements
- `skills/discovery/jobs-to-be-done/SKILL.md` — JTBD framework for the "Goals" section
- `skills/discovery/discovery-interview-prep/SKILL.md` — Validate personas through interviews
- `skills/specification/user-story/SKILL.md` — Personas become the "As a [persona]" in stories

### External Frameworks
- Alan Cooper, *About Face* — Origin of personas in product design
- Jeff Patton, *User Story Mapping* — Proto-personas for lean teams
- Jobs-to-be-Done (Christensen) — Behavioral framing for goals

---

**Skill type:** Component
**Domain:** Discovery & Research
**Prerequisites:** None
