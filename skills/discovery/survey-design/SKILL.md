---
name: survey-design
description: Design effective customer surveys that yield actionable insights. Covers question types, bias avoidance, sampling, and analysis frameworks to replace vanity feedback with real signal.
type: component
domain: discovery
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["problem-statement"]
outputs: ["survey-document"]
triggers:
  - "I need to create a survey"
  - "Help me design a customer survey"
  - "I want to collect user feedback"
  - "Build a survey for research"
---

## Purpose

Design customer surveys that produce **actionable insights**, not vanity metrics. Covers question design, bias avoidance, sampling strategy, and analysis planning — so you get data you can actually make decisions with.

---

## Key Concepts

### Question Types

| Type | When to Use | Example |
|------|------------|---------|
| **Closed (rating)** | Quantify satisfaction, importance | "Rate 1-5: How easy was onboarding?" |
| **Closed (multiple choice)** | Categorize segments, preferences | "Which feature do you use most? A/B/C/D" |
| **Open-ended** | Discover unknowns, get verbatims | "What's the hardest part of your workflow?" |
| **NPS** | Benchmark overall sentiment | "How likely to recommend? (0-10)" |
| **Matrix** | Compare across dimensions | Rate features on importance + satisfaction |

### Bias Traps to Avoid

| Bias | Example | Fix |
|------|---------|-----|
| **Leading** | "How much do you love X?" | "How would you rate X?" |
| **Double-barreled** | "Is X fast and easy?" | Ask separately |
| **Acquiescence** | All agree/disagree scales | Mix positive/negative framing |
| **Social desirability** | "Do you use best practices?" | Ask about behaviors, not values |
| **Survivorship** | Only surveying active users | Include churned users |

### When to Use This

- Validating problem statements at scale
- Gauging feature demand before building
- Measuring satisfaction (CSAT, NPS, CES)
- Understanding churn reasons

### When NOT to Use This

- When you have < 50 potential respondents (do interviews instead)
- For exploratory discovery (interviews are better)
- When behavior data answers the question (use analytics)

---

## Application

### Step 1: Define Survey Objectives

```markdown
**Research question:** [What specific question are we trying to answer?]
**Decision it informs:** [What will we do differently based on results?]
**Target segment:** [Who should respond?]
**Sample size target:** [Minimum responses for statistical significance]
**Distribution method:** [In-app, email, social, panel]
```

### Step 2: Structure the Survey

```markdown
**Survey Structure:**

1. **Screener (1-2 questions)** — Filter for right respondents
2. **Context (2-3 questions)** — Establish respondent's situation
3. **Core questions (5-8 questions)** — Primary research objectives
4. **Demographics (2-3 questions)** — Segmentation data
5. **Open-ended (1-2 questions)** — Capture what you didn't think to ask

**Total:** 12-18 questions max (5-7 min completion)
```

### Step 3: Write Questions

For each question:

```markdown
**Q[#]:** [Question text]
**Type:** [Rating / MC / Open / NPS / Matrix]
**Purpose:** [What decision this informs]
**Options:** [Response options if applicable]
**Bias check:** [Is this leading, double-barreled, or biased? How did you fix it?]
```

### Step 4: Plan Analysis

```markdown
**Analysis plan:**
| Question | Analysis Method | Decision Threshold |
|----------|----------------|-------------------|
| [Q#] | [Mean, distribution, crosstab] | [If >X, then do Y] |
```

---

## Examples

### ✅ Good Question

```markdown
**Q3:** In the past 30 days, how many times have you needed to export data
       from [Product] to share with a colleague?
**Type:** Multiple choice
**Options:** 0 / 1-2 / 3-5 / 6-10 / More than 10
**Purpose:** Quantify demand for collaboration features
**Bias check:** Asks about behavior (not intention). Time-bounded. Specific.
```

### ❌ Bad Question

```markdown
**Q3:** Would you like better collaboration features?
```

**Why this fails:** Leading (implies current is bad), hypothetical (not behavioral), binary (no nuance).

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Objective** | No clear research question | Vague objective | Specific decision it informs |
| **Question Quality** | Leading/biased questions | Mostly clean | All questions bias-checked |
| **Length** | 25+ questions | 15-20 questions | 12-18 questions, 5-7 min |
| **Analysis Plan** | None | "We'll look at the data" | Pre-defined thresholds |
| **Sampling** | "Send to everyone" | Target segment identified | Sample size calculated |

---

## Common Pitfalls

### Pitfall 1: Survey Too Long

**Symptom:** 30+ questions, 15+ minute completion time.

**Fix:** Cut ruthlessly. If a question doesn't change a decision, delete it. Target 5-7 minutes.

### Pitfall 2: Only Surveying Happy Customers

**Symptom:** Survey sent to active users only.

**Fix:** Include churned users, trial dropouts, non-purchasers. The most valuable feedback comes from people who *didn't* convert.

### Pitfall 3: No Analysis Plan

**Symptom:** "We'll figure out what the data says after we collect it."

**Fix:** Write your analysis plan *before* sending. For each question, state: "If the answer is X, we will do Y."

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Surveys validate problem statements
- `skills/discovery/discovery-interview-prep/SKILL.md` — Use interviews for exploration, surveys for validation
- `skills/analytics/funnel-analysis/SKILL.md` — Combine survey data with behavioral analytics

### External Frameworks
- Erika Hall, *Just Enough Research* — Survey design principles
- Don Dillman, *Internet, Phone, Mail, and Mixed-Mode Surveys* — Sampling methodology

---

**Skill type:** Component
**Domain:** Discovery & Research
