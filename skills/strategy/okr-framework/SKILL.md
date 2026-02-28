---
name: okr-framework
description: Set clear Objectives and Key Results that connect team work to company strategy. Covers OKR writing, alignment, grading, and common mistakes that make OKRs useless.
type: component
domain: strategy
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["product-vision-statement"]
outputs: ["okr-document"]
triggers:
  - "Help me write OKRs"
  - "Set quarterly objectives"
  - "Create OKRs for the team"
  - "How do I define key results"
---

## Purpose

Set Objectives and Key Results that translate strategy into **measurable, time-bound goals** teams can actually rally behind. This skill covers OKR writing, vertical alignment (company → team → individual), and the pitfalls that make OKRs into pointless bureaucracy.

---

## Key Concepts

### OKR Structure

**Objective:** Qualitative, inspiring, memorable. Answers "Where are we going?"
**Key Results (2-5 per objective):** Quantitative, measurable, time-bound. Answers "How do we know we arrived?"

### The Alignment Cascade

```
Company OKR:  "Become the category leader in PM analytics"
     ↓
Team OKR:     "Prove product-market fit with mid-market SaaS PMs"
     ↓
Individual:   "Ship onboarding redesign that doubles activation"
```

### OKR Grading (Google-style)

| Score | Meaning |
|-------|---------|
| **0.0 - 0.3** | Failed to make progress |
| **0.4 - 0.6** | Progress but fell short |
| **0.7 - 0.8** | Delivered (target zone for stretch goals) |
| **0.9 - 1.0** | Nailed it (or goal wasn't ambitious enough) |

### Key Principles

- **Outcomes, not outputs:** "Increase activation rate to 60%" NOT "Ship 3 features"
- **Aspirational (stretch):** If you hit 100% every quarter, your goals are too easy
- **Public:** Everyone sees everyone's OKRs to enable alignment
- **Not compensation-linked:** OKRs ≠ performance reviews (or people sandbag)

---

## Application

### Step 1: Write the Objective

```markdown
**Objective:** [Inspiring, qualitative statement of direction]

**Quality checks:**
- [ ] Memorable — can you say it without reading it?
- [ ] Aspirational — does it stretch the team?
- [ ] Time-bound — achievable within the OKR period?
- [ ] Aligned — does it connect to company/team OKR above?
```

### Step 2: Write Key Results (2-5)

```markdown
**KR1:** [Metric] from [baseline] to [target] by [date]
**KR2:** [Metric] from [baseline] to [target] by [date]
**KR3:** [Metric] from [baseline] to [target] by [date]

**Key Result quality checks (for each):**
- [ ] Quantitative — is there a number?
- [ ] Has a baseline — do you know the starting point?
- [ ] Measurable today — can you actually track this?
- [ ] Outcome-focused — does it measure impact, not effort?
- [ ] Not gameable — can someone hit the number through the wrong behavior?
```

### Step 3: Check Alignment

```markdown
**Alignment check:**
- Company OKR this supports: [Which one?]
- Dependency on other teams: [List them]
- Potential conflicts with other team OKRs: [Any?]
```

---

## Examples

### ✅ Good OKR

```markdown
**Objective:** Make our onboarding so good that new users can't help but invite their team.

**KR1:** Increase 7-day activation rate from 28% to 55%
**KR2:** Decrease median time-to-first-value from 45 min to 10 min
**KR3:** Increase organic invitations from 0.3 to 1.2 per activated user
```

### ❌ Bad OKR

```markdown
**Objective:** Improve onboarding

**KR1:** Ship redesigned onboarding flow
**KR2:** Complete 10 user interviews
**KR3:** Update help docs
```

**Why this fails:** Objective is vague, all KRs are outputs (tasks), not outcomes (impact). Could ship all 3 and have zero improvement.

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Objective** | Task ("Ship X") | General direction | Inspiring + time-bound |
| **Key Results** | Outputs/activities | Mix of outputs + outcomes | All outcome-based with baselines |
| **Measurability** | Can't be measured | Can measure but no baseline | Baseline + target + tracking plan |
| **Alignment** | Standalone | Loosely connected | Clear cascade from company OKR |
| **Ambition** | Certain to hit | Reasonable | Stretch (70% confidence of hitting) |

---

## Common Pitfalls

### Pitfall 1: KRs Are Disguised Tasks

**Symptom:** "Ship onboarding v2", "Write 5 blog posts", "Complete research"

**Fix:** These are initiatives, not key results. Ask: "If we did this thing, what would change?" That change is the KR.

### Pitfall 2: Too Many OKRs

**Symptom:** 5 objectives with 5 KRs each = 25 things to track.

**Fix:** 1-3 objectives max, 2-4 KRs each. If everything is a priority, nothing is.

### Pitfall 3: OKRs That Punish Risk-Taking

**Symptom:** People set easy goals they know they'll hit because OKRs affect compensation.

**Fix:** Separate OKRs from performance reviews. OKRs track strategic progress, not individual performance.

---

## References

### Related Skills
- `skills/strategy/product-vision-statement/SKILL.md` — OKRs operationalize the vision
- `skills/strategy/north-star-metric/SKILL.md` — NSM often becomes a company-level KR
- `skills/planning/roadmap-planning/SKILL.md` — OKRs inform roadmap prioritization

### External Frameworks
- John Doerr, *Measure What Matters* (2018)
- Christina Wodtke, *Radical Focus* (2016)
- Google OKR Playbook

---

**Skill type:** Component
**Domain:** Strategy & Vision
