---
name: positioning-statement
description: Define who you serve, what problem you solve, and how you're different using Geoffrey Moore's positioning framework. Creates a clear, defensible market position.
type: component
domain: strategy
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["problem-statement", "proto-persona"]
outputs: ["positioning-statement-document"]
triggers:
  - "Define our product positioning"
  - "Write a positioning statement"
  - "How are we different from competitors"
  - "Who is this product for and why"
---

## Purpose

Define a clear, defensible market position that answers four critical questions: **Who** do you serve, **what** problem do you solve, **how** are you different, and **why** should anyone care. Uses Geoffrey Moore's positioning framework from *Crossing the Chasm*.

---

## Key Concepts

### Geoffrey Moore's Positioning Template

```
For [target customer]
who [statement of need/opportunity],
[product name] is a [product category]
that [key benefit/reason to buy].
Unlike [competitive alternative],
our product [key differentiator].
```

### Six Components

| Component | What It Answers |
|-----------|----------------|
| **Target Customer** | Who specifically is this for? |
| **Need/Opportunity** | What problem do they have? |
| **Product Category** | What kind of solution is this? |
| **Key Benefit** | What's the primary value delivered? |
| **Competitive Alternative** | What do they use today instead? |
| **Key Differentiator** | Why are you uniquely better? |

### Anti-Patterns

- **Not a tagline:** Positioning is internal strategy; taglines are external marketing
- **Not a feature list:** "We have AI, dashboards, and integrations" ← Features, not positioning
- **Not aspirational:** Position based on what you deliver today, not what you hope to be

### When to Use This

- Launching a new product or entering a new market
- Refining messaging after product-market fit
- Aligning sales, marketing, and product on "who we are"
- Before writing a PRD (to ground the scope)

### When NOT to Use This

- Pre-product (you don't know your market yet — do discovery first)
- For individual features (positioning is product-level, not feature-level)

---

## Application

### Step 1: Define Target Customer

```markdown
**Target Customer:**
[Specific segment — role, company size, industry, behavior]

**Not for:**
[Who this product is explicitly NOT for — this is as important as who it IS for]
```

**Quality check:**
- [ ] Can you name 10 real companies/people in this segment?
- [ ] Is this segment narrow enough to win but large enough to sustain a business?

---

### Step 2: State the Need

```markdown
**Need/Opportunity:**
Who [need statement — describe the problem in the customer's words, not your product's language]
```

**Quality check:**
- [ ] Would the customer recognize this as *their* problem?
- [ ] Is this a need they'd pay to solve?

---

### Step 3: Define Product Category

```markdown
**Product Category:**
[product name] is a [category label]

**Category strategy:**
- [ ] Existing category (compete): [e.g., "project management tool"]
- [ ] Adjacent category (reframe): [e.g., "product delivery platform"]
- [ ] New category (create): [e.g., "continuous discovery engine"]
```

---

### Step 4: Articulate Key Benefit

```markdown
**Key Benefit:**
That [primary benefit — must be measurable or demonstrable]

**Proof points:**
1. [Evidence that you deliver this benefit]
2. [Customer quote or metric]
3. [Case study or benchmark]
```

---

### Step 5: Name the Competitive Alternative

```markdown
**Competitive Alternative:**
Unlike [what they use today — could be a competitor, a spreadsheet, or "doing nothing"]
```

---

### Step 6: State the Differentiator

```markdown
**Key Differentiator:**
Our product [what makes you uniquely better — must be defensible and true TODAY]

**Defensibility test:**
- [ ] Can a competitor replicate this in 6 months?
- [ ] Is this a feature (copyable) or a capability (durable)?
```

---

### Step 7: Assemble the Full Statement

```markdown
# Positioning Statement

For **[target customer]**
who **[need/opportunity]**,
**[product name]** is a **[product category]**
that **[key benefit]**.
Unlike **[competitive alternative]**,
our product **[key differentiator]**.
```

---

## Examples

### ✅ Good Example

```markdown
For **mid-market SaaS product managers**
who **spend 5+ hours/week manually compiling product metrics across tools**,
**MetricFlow** is a **product analytics platform**
that **automatically unifies usage, revenue, and feedback data into decision-ready dashboards**.
Unlike **building custom dashboards in Looker or exporting to Google Sheets**,
our product **provides pre-built PM-specific views with anomaly alerts that require zero SQL**.
```

### ❌ Bad Example

```markdown
For everyone who wants better data,
MetricFlow is a powerful platform
that uses AI to provide insights.
Unlike other tools,
we're more innovative.
```

**Why this fails:** "Everyone" (no target), "better data" (vague need), "powerful" (meaningless), "AI" (not a benefit), "innovative" (not differentiating).

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Target** | "Everyone" | Named segment | Named + who it's NOT for |
| **Need** | Product-centric | Customer language but vague | Specific, recognized pain |
| **Benefit** | Feature list | General value | Measurable with proof points |
| **Differentiator** | "We're better" | Real but copyable | Defensible and unique |
| **Clarity** | Jargon-heavy | Mostly clear | A sales rep could say it cold |

---

## Common Pitfalls

### Pitfall 1: Positioning by Features

**Symptom:** "We have dashboards, AI, and integrations."

**Fix:** Features are how you deliver value, not the value itself. Lead with the benefit: "You'll never manually compile a report again."

### Pitfall 2: Trying to Be Everything

**Symptom:** Positioning targets 3 different segments with 5 different benefits.

**Fix:** Pick one primary position. You can have secondary positioning for other segments, but the primary must be sharp.

### Pitfall 3: Differentiating on Price

**Symptom:** "Unlike competitors, we're cheaper."

**Fix:** Price is the weakest differentiator — anyone can lower prices. Differentiate on value, approach, or capability.

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — The "need" should trace to a validated problem
- `skills/discovery/proto-persona/SKILL.md` — The "target customer" comes from personas
- `skills/discovery/competitive-battle-card/SKILL.md` — Competitive alternative analysis
- `skills/strategy/positioning-workshop/SKILL.md` — Facilitated session to build this collaboratively

### External Frameworks
- Geoffrey Moore, *Crossing the Chasm* (1991) — Positioning template
- April Dunford, *Obviously Awesome* (2019) — Modern positioning methodology

---

**Skill type:** Component
**Domain:** Strategy & Vision
