---
name: press-release
description: Write a future-dated press release to clarify product vision using Amazon's Working Backwards method. Forces clarity on customer benefit, problem solved, and success metrics before building.
type: component
domain: strategy
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["positioning-statement"]
outputs: ["press-release-document"]
triggers:
  - "Write a press release for a new feature"
  - "Use Working Backwards"
  - "Help me clarify the product vision"
  - "Amazon PR FAQ"
---

## Purpose

Write a future-dated press release that describes your product/feature as if it's already launched — forcing clarity on **who benefits, what problem is solved, and what makes it remarkable** before you build anything. Based on Amazon's Working Backwards methodology.

---

## Key Concepts

### Amazon Working Backwards

Write the press release **before building the product.** If the press release is boring, the product will be boring. If you can't articulate the benefit in customer language, you don't understand the customer well enough.

### Press Release Structure

| Section | Purpose |
|---------|---------|
| **Headline** | Clear benefit in customer language |
| **Subheadline** | Who it's for + key value |
| **Problem** | Customer pain point (their words) |
| **Solution** | What we built and how it works |
| **Quote (internal)** | Why we built this (executive voice) |
| **How It Works** | Simple explanation of the experience |
| **Quote (customer)** | What a customer would say |
| **Call to Action** | How to get started |

---

## Application

### The Full Template

```markdown
# [HEADLINE: Clear, Benefit-Driven Title]

**[City, Date]** — [Company Name] today announced [Product/Feature Name],
a [brief description] that helps [target customer] [key benefit].

## The Problem

[2-3 sentences describing the customer pain point in the customer's own language.
Not your internal jargon. Not your feature set. The customer's actual frustration.]

## The Solution

[Product/Feature Name] [solves the problem by...]. Key capabilities include:

- **[Capability 1]:** [Benefit in customer terms]
- **[Capability 2]:** [Benefit in customer terms]
- **[Capability 3]:** [Benefit in customer terms]

## Internal Quote

"[Executive name], [title] at [Company], said: '[Why we built this.
What it means for our mission. Forward-looking vision statement.]'"

## How It Works

[3-4 sentences describing the customer experience. Walk through what a
customer actually does, step by step. Keep it simple enough for a
non-technical reader.]

## Customer Quote

"[Customer name], [role] at [Company], said: '[What they would say about
the product. Focus on the outcome and feeling, not the features. Make it
sound like a real person, not marketing copy.]'"

## Getting Started

[Product/Feature Name] is available [today/starting date] for [who can access it].
[Pricing info if applicable.] To get started, [specific action].

For more information, visit [link].
```

---

## Examples

### ✅ Good Example

```markdown
# MetricFlow Eliminates Manual Reporting for Product Teams

**San Francisco, March 2026** — MetricFlow today announced Unified Product 
Analytics, a new capability that automatically combines usage, revenue, and 
customer feedback data into decision-ready dashboards — saving product managers 
5+ hours per week of manual data compilation.

## The Problem
Product managers at mid-market SaaS companies typically spend Monday mornings
exporting data from 4-5 tools, copying into spreadsheets, and building 
presentations for leadership meetings. By the time the data is formatted,
it's often already stale.

## Customer Quote
"I used to spend every Monday morning as a data janitor instead of a product
leader. Now I walk into Monday standups with live dashboards that update 
themselves. I've literally reclaimed a full workday every week."
— Maya Chen, Product Manager at DataStack (150-person B2B SaaS)
```

### ❌ Bad Example

```markdown
# MetricFlow Launches New AI-Powered Analytics Platform

MetricFlow announced its innovative, AI-powered, best-in-class analytics
solution leveraging state-of-the-art machine learning algorithms for
data-driven organizations seeking to optimize their business intelligence
capabilities.
```

**Why this fails:** Jargon-heavy, no specific customer, no specific problem, no specific benefit. Could be any company's press release.

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Customer Clarity** | No specific target | Named segment | Specific persona with context |
| **Problem** | Not stated or vague | Described but internal jargon | Customer's own words |
| **Benefit** | Feature list | General value | Quantified outcome |
| **Quotes** | Generic marketing speak | Decent but corporate | Sounds like a real person said it |
| **Excitement** | Would you click? No. | Maybe interesting | Compelling — you'd read more |

---

## Common Pitfalls

### Pitfall 1: Writing for Investors, Not Customers

**Fix:** If your press release sounds like a pitch deck, rewrite it. Customers don't care about your "paradigm-shifting platform."

### Pitfall 2: Too Many Features

**Fix:** Highlight 2-3 capabilities max. Focus on the ONE big benefit.

---

## References

### Related Skills
- `skills/strategy/positioning-statement/SKILL.md` — Positioning feeds the headline and value prop
- `skills/strategy/product-vision-statement/SKILL.md` — Internal quote echoes the vision
- `skills/discovery/proto-persona/SKILL.md` — Customer quote uses persona voice

### External Frameworks
- Amazon Working Backwards — Ian McAllister, Colin Bryar & Bill Carr

---

**Skill type:** Component
**Domain:** Strategy & Vision
