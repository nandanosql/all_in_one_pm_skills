---
name: customer-journey-map
description: Map the complete customer experience across all touchpoints using the NNGroup framework. Identifies pain points, emotions, and opportunities at every stage of the user journey.
type: component
domain: discovery
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: ["proto-persona"]
outputs: ["journey-map-document"]
triggers:
  - "Map the customer journey"
  - "I need to understand the user experience end to end"
  - "Where are users dropping off"
  - "Create a journey map"
---

## Purpose

Map the complete customer experience across all touchpoints — from first awareness through active use and advocacy. Identifies **pain points, emotional states, and opportunities** at every stage so you can prioritize improvements where they matter most.

This is not a feature flow or wireframe. It's a holistic view of the customer's experience with your product and brand.

---

## Key Concepts

### Journey Map Structure (NNGroup Framework)

A journey map is a table with stages as columns and lens rows:

| Lens | What It Captures |
|------|-----------------|
| **Stage** | Phase of the customer lifecycle |
| **Actions** | What the user does at each stage |
| **Touchpoints** | Where interaction happens (channels, interfaces) |
| **Thoughts** | What the user is thinking |
| **Emotions** | How the user feels (plotted as high/low) |
| **Pain Points** | Frustrations and barriers |
| **Opportunities** | Where you can improve the experience |

### Standard Stages

1. **Awareness** — How they discover you exist
2. **Consideration** — How they evaluate you vs. alternatives
3. **Acquisition** — How they sign up / buy
4. **Onboarding** — How they get started
5. **Usage** — How they use the product day-to-day
6. **Retention** — What keeps them (or doesn't)
7. **Advocacy** — How they recommend you (or churn)

### When to Use This

- Before redesigning a flow or experience
- When churn or drop-offs are unexplained
- To align cross-functional teams on the user experience
- Before writing PRDs (to see the big picture)

### When NOT to Use This

- For detailed UI flows (use wireframes or user flows)
- When you have no customer data at all (do discovery first)
- For technical system architecture (use system diagrams)

---

## Application

### Step 1: Define Scope and Persona

```markdown
**Journey for:** [Persona name from proto-persona]
**Scope:** [Start point → End point of the journey]
**Goal:** [What are we trying to learn from this map?]
**Data sources:** [Analytics, interviews, support data, etc.]
```

---

### Step 2: Map Each Stage

For each stage, fill in:

```markdown
## Stage: [Stage Name]

**User Goal:** [What they're trying to accomplish]

**Actions:**
1. [Action 1]
2. [Action 2]
3. [Action 3]

**Touchpoints:** [Website, email, app, sales call, support, etc.]

**Thoughts:** "[What they're thinking in their own words]"

**Emotion:** [😊 Positive / 😐 Neutral / 😤 Frustrated / 😡 Angry]

**Pain Points:**
- [Pain 1 — with severity: High/Med/Low]
- [Pain 2]

**Opportunities:**
- [How we could improve this stage]
```

---

### Step 3: Plot the Emotional Arc

```markdown
**Emotional Journey:**

😊 High ──┐          ┌──────┐
          │          │      │
😐 Mid ───┤ ─── ┐   │      └── ┐
          │     │   │           │
😤 Low ───┘     └───┘           └──

Stage:  Aware  Consider  Acquire  Onboard  Use  Retain  Advocate
```

Identify the **lowest emotional points** — these are your highest-priority improvement areas.

---

### Step 4: Prioritize Opportunities

```markdown
| Opportunity | Stage | Impact | Effort | Priority |
|-------------|-------|--------|--------|----------|
| [Opp 1] | [Stage] | [H/M/L] | [H/M/L] | [1-5] |
| [Opp 2] | [Stage] | [H/M/L] | [H/M/L] | [1-5] |
```

---

## Examples

### ✅ Good Example

```markdown
## Stage: Onboarding

**User Goal:** Set up my account and see first results

**Actions:**
1. Creates account (email/Google SSO)
2. Invited to connect data source
3. Waits for data sync
4. Views first dashboard (if they get here)

**Touchpoints:** Web app, setup wizard, email confirmations

**Thoughts:** "This better be worth it... Where are my credentials?
              Why is this taking so long? I'll come back later..."

**Emotion:** 😤 Frustrated (drops from 😊 after sign-up excitement)

**Pain Points:**
- Data source connection requires admin credentials user doesn't have (High)
- Sync takes 15+ minutes with no progress indicator (Med)
- First dashboard is empty template, no sample data (Med)

**Opportunities:**
- Offer sandbox data for immediate first-value experience
- Add credential-free connection option (OAuth)
- Show progress bar during sync with estimated time
```

### ❌ Bad Example

```markdown
## Onboarding
- Users sign up and set up their account
- It could be better
```

**Why this fails:** No actions, no emotions, no pain points, no evidence, no actionable insights.

---

## Quality Rubric

Score each dimension 0-2. **Target: 8+ out of 10.**

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Completeness** | 1-2 stages | Most stages covered | All lifecycle stages |
| **Evidence** | All assumed | Mix of data + assumption | Data-backed per stage |
| **Emotions** | Not tracked | General sentiment | Per-stage with quotes |
| **Pain Points** | Not identified | Listed without severity | Specific + severity + frequency |
| **Opportunities** | None listed | Generic improvements | Actionable with impact estimates |

---

## Common Pitfalls

### Pitfall 1: Inside-Out Mapping

**Symptom:** Journey stages map to your internal process (Marketing → Sales → Onboarding), not the customer's experience.

**Fix:** Write labels from the customer's perspective: "Discovering options," "Trying it out," "Getting started."

---

### Pitfall 2: Happy Path Only

**Symptom:** Journey shows the ideal flow. No drop-offs, no confusion, no negative emotions.

**Fix:** Include failure paths. The most valuable insights come from where things go wrong.

---

### Pitfall 3: No Data, All Assumptions

**Symptom:** Every cell is filled with what the team *thinks* happens.

**Fix:** Mark assumption vs. evidence. Then prioritize research to validate the biggest assumptions.

---

## References

### Related Skills
- `skills/discovery/proto-persona/SKILL.md` — Define who the journey is for
- `skills/discovery/problem-statement/SKILL.md` — Pain points become problem statements
- `skills/discovery/discovery-interview-prep/SKILL.md` — Validate the journey with users

### External Frameworks
- NNGroup Journey Mapping Guide — Nielsen Norman Group
- Service Design Blueprint — Bitner et al.

---

**Skill type:** Component
**Domain:** Discovery & Research
**Prerequisites:** proto-persona
