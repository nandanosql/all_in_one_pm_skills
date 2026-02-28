---
name: epic-hypothesis
description: Turn vague initiatives into testable hypotheses with success metrics. Links business outcomes to user behavior and defines clear success/failure criteria before building.
type: component
domain: planning
difficulty: intermediate
estimated_time: "15-25 min"
prerequisites: ["problem-statement"]
outputs: ["epic-hypothesis-document"]
triggers:
  - "Turn this initiative into a testable hypothesis"
  - "Write an epic hypothesis"
  - "Define success metrics for this epic"
  - "How will we know this initiative worked"
---

## Purpose

Transform vague product initiatives ("improve onboarding") into **testable hypotheses** with clear success metrics, linking business outcomes to user behavior changes. Ensures every epic has a defined definition of success *before* development begins.

---

## Key Concepts

### The Epic Hypothesis Format

```
We believe that [initiative/feature]
for [target user segment]
will achieve [business outcome]
as measured by [specific metrics].

We will know this is true when [success criteria].
We will know this is false when [failure criteria].
```

### Why This Works

- **Forces outcome thinking:** Not "what we'll build" but "what will change"
- **Makes failure cheap:** If the hypothesis is wrong, you learned something
- **Enables prioritization:** Hypotheses with higher expected impact get priority
- **Creates accountability:** Clear metrics = clear ownership of outcomes

---

## Application

### Step 1: State the Belief

```markdown
**We believe that:**
[Describe the initiative — what you plan to build or change]

**For:**
[Specific user segment affected]
```

### Step 2: Define the Expected Outcome

```markdown
**Will achieve:**
[Business outcome — revenue, retention, activation, efficiency]

**Because:**
[Causal logic — WHY you believe the initiative creates this outcome]
```

### Step 3: Define Success Metrics

```markdown
**As measured by:**
| Metric | Baseline | Target | Timeline |
|--------|----------|--------|----------|
| [Primary metric] | [Current] | [Target] | [By when] |
| [Guard metric] | [Current] | [Don't drop below] | [Same] |
```

**Guard metrics** ensure you don't optimize one metric at the expense of another (e.g., don't increase signups by degrading quality).

### Step 4: Define Pass/Fail Criteria

```markdown
**Success (continue investing):** [Primary metric] reaches [target] within [timeframe]
**Partial success (iterate):** [Primary metric] improves by [X%] but doesn't reach target
**Failure (pivot/kill):** [Primary metric] shows no meaningful change after [timeframe]
```

---

## Examples

### ✅ Good Example

```markdown
**We believe that** adding a guided sandbox onboarding experience
**for** trial users in their first 7 days
**will achieve** higher trial-to-paid conversion
**because** users who experience core value within their first session convert at 3x the rate of those who don't.

**As measured by:**
| Metric | Baseline | Target | Timeline |
|--------|----------|--------|----------|
| 7-day activation rate | 28% | 55% | 60 days post-launch |
| Trial-to-paid conversion | 4.2% | 7% | 90 days post-launch |
| Time-to-first-value | 45 min | 10 min | 30 days post-launch |

**Guard:** Support ticket volume should not increase by more than 10%.

**Success:** Activation rate ≥ 50% within 60 days
**Failure:** Activation rate < 35% after 60 days
```

### ❌ Bad Example

```markdown
We believe improving onboarding will help users. We'll measure this by tracking signups.
```

**Why this fails:** No specific user, no measurable target, no timeline, signups ≠ activation.

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Specificity** | "Improve X" | Named initiative | Initiative + segment + mechanism |
| **Metrics** | None or vanity | Primary metric | Primary + guard metrics with baselines |
| **Causal Logic** | Assumed | Stated but untested | Evidence-backed rationale |
| **Pass/Fail** | Not defined | Success only | Success + partial + failure criteria |
| **Timeline** | Open-ended | Vague ("soon") | Specific dates/durations |

---

## Common Pitfalls

### Pitfall 1: Unfalsifiable Hypothesis

**Symptom:** "This will improve user experience" — how would you know if it didn't?

**Fix:** Every hypothesis must have a failure condition. If you can't fail, you can't learn.

### Pitfall 2: No Guard Metrics

**Fix:** Without guard metrics, you might "improve" activation by making the metric easier to hit, not by actually helping users.

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Hypotheses should address validated problems
- `skills/planning/prioritization-advisor/SKILL.md` — Compare hypotheses for prioritization
- `skills/growth/ab-test-design/SKILL.md` — Design experiments to test hypotheses
- `skills/specification/user-story/SKILL.md` — Epic hypotheses decompose into stories

---

**Skill type:** Component
**Domain:** Planning & Prioritization
