---
name: north-star-metric
description: Define the single metric that best captures the core value your product delivers to customers. Covers selection, decomposition into input metrics, and common traps.
type: component
domain: strategy
difficulty: intermediate
estimated_time: "15-20 min"
prerequisites: ["product-vision-statement"]
outputs: ["north-star-metric-document"]
triggers:
  - "What's our north star metric"
  - "Help me define the key metric"
  - "What should we measure as our primary metric"
  - "North star metric"
---

## Purpose

Define the **single metric** that best measures the core value your product delivers. A good North Star Metric (NSM) aligns the entire company around customer value, predicts long-term business success, and decomposes into actionable input metrics teams can influence.

---

## Key Concepts

### What Makes a Good NSM

| Criteria | ✅ Good | ❌ Bad |
|----------|---------|--------|
| **Measures value** | Value delivered to customer | Revenue (internal metric) |
| **Predictive** | Precedes revenue growth | Lagging indicator |
| **Actionable** | Teams can influence it | Out of their control |
| **Simple** | One number, easy to explain | Composite index |
| **Leading** | Early signal of success | Only visible after the fact |

### NSM Decomposition Tree

```
North Star Metric
├── Input Metric 1 (Breadth: # of users reaching value)
├── Input Metric 2 (Depth: frequency of value delivery)
└── Input Metric 3 (Efficiency: speed to value)
```

---

## Application

### Step 1: Identify the Core Value

```markdown
**What is the core value your product delivers?**
[In one sentence, what does the user "get" from your product?]

**Game:** [What type of value game are you playing?]
- [ ] Attention — Time spent (social, media, entertainment)
- [ ] Transaction — Purchases or exchanges completed
- [ ] Productivity — Tasks completed or time saved
- [ ] Network — Connections made or interactions enabled
```

### Step 2: Define the NSM

```markdown
**North Star Metric:** [Name]
**Definition:** [Precise definition — what counts, what doesn't]
**Current value:** [Baseline]
**Target:** [Where you want it to be and by when]

**Why this metric:**
- It measures value to the customer because: [reason]
- It predicts revenue because: [reason]
- Teams can influence it because: [reason]
```

### Step 3: Decompose into Input Metrics

```markdown
**Input Metrics:**

| Input Metric | Owner | Current | Target | How to Move It |
|-------------|-------|---------|--------|---------------|
| [Metric 1] | [Team] | [#] | [#] | [Key lever] |
| [Metric 2] | [Team] | [#] | [#] | [Key lever] |
| [Metric 3] | [Team] | [#] | [#] | [Key lever] |
```

---

## Examples

### ✅ Good Examples

| Product | NSM | Why It Works |
|---------|-----|-------------|
| Spotify | Time spent listening | Measures value delivered to user |
| Airbnb | Nights booked | Measures value exchange |
| Slack | Messages sent per user per week | Measures engagement depth |
| Salesforce | Records created/updated | Measures productivity |

### ❌ Bad Examples

| Metric | Problem |
|--------|---------|
| Revenue | Lagging, internal-facing, doesn't measure value |
| # of signups | Vanity — doesn't ensure value delivery |
| Page views | Not connected to value for most products |
| NPS | Lagging, infrequent, not actionable daily |

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Value Proxy** | Revenue/vanity metric | Related to value but indirect | Directly measures value delivery |
| **Actionability** | Can't influence | Some levers | Clear input metrics with owners |
| **Simplicity** | Composite/index | Clear but needs explanation | One number, instantly understood |
| **Leading** | Lagging indicator | Concurrent | Leading indicator of growth |
| **Decomposition** | NSM only | Some input metrics | Full tree with owners + targets |

---

## Common Pitfalls

### Pitfall 1: Revenue as NSM

**Fix:** Revenue is the *outcome* of delivering value, not the value itself. Find what drives revenue by asking: "What value did the customer get that made them pay?"

### Pitfall 2: Metric That Can Be Gamed

**Fix:** "Messages sent" could be gamed by bots. Add quality gates: "Messages in threads with 2+ participants."

---

## References

### Related Skills
- `skills/strategy/product-vision-statement/SKILL.md` — NSM measures progress toward vision
- `skills/strategy/okr-framework/SKILL.md` — NSM often becomes a company-level key result
- `skills/analytics/funnel-analysis/SKILL.md` — Track NSM through the funnel

### External Frameworks
- Sean Ellis, *Hacking Growth* — North Star Metric concept
- Amplitude's North Star Playbook

---

**Skill type:** Component
**Domain:** Strategy & Vision
