# 📐 Skill Format Guide

> The complete anatomy of a PM Skills file — every field, every section, explained.

---

## Overview

Every skill in this system is a single **SKILL.md** file that follows a consistent structure. This consistency is what makes skills portable across AI tools and reliable in output quality.

```
SKILL.md = YAML Frontmatter + 7 Markdown Sections
```

---

## Part 1: YAML Frontmatter

The frontmatter is metadata at the top of every skill file, enclosed in `---` delimiters.

```yaml
---
name: problem-statement
description: Frame a customer problem with evidence before jumping to solutions.
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
---
```

### Field Reference

| Field | Required | Values | Description |
|-------|----------|--------|-------------|
| `name` | ✅ | kebab-case string | Unique identifier (matches the folder name) |
| `description` | ✅ | ≤200 chars | One-line summary of what the skill does |
| `type` | ✅ | `component` \| `interactive` \| `workflow` | Determines the skill's behavior pattern |
| `domain` | ✅ | One of 10 domains | Which PM lifecycle stage this belongs to |
| `difficulty` | ✅ | `beginner` \| `intermediate` \| `advanced` | Complexity level for the user |
| `estimated_time` | ✅ | String (e.g., "15-25 min") | How long a typical session takes |
| `prerequisites` | ✅ | Array of skill names | Skills that should be completed first |
| `outputs` | ✅ | Array of artifact names | What this skill produces |
| `triggers` | ✅ | Array of phrases | Natural language phrases that activate this skill |

### The Three Skill Types

| Type | Symbol | Behavior | Count |
|------|--------|----------|-------|
| **Component** | 🧱 | Generates a single artifact with fill-in templates. No back-and-forth. | 62 |
| **Interactive** | 🔄 | Asks clarifying questions first, then generates adaptive output. Multi-turn. | 32 |
| **Workflow** | 🎭 | Orchestrates multiple skills across phases. Announces transitions. | 7 |

### The 10 Domains

| Domain | Slug | Lifecycle Stage |
|--------|------|----------------|
| Discovery & Research | `discovery` | Understanding the problem space |
| Strategy & Vision | `strategy` | Setting direction and goals |
| Planning & Prioritization | `planning` | Deciding what to build and when |
| Specification & Design | `specification` | Defining what to build in detail |
| Execution & Delivery | `execution` | Building and shipping |
| Launch & GTM | `launch` | Bringing to market |
| Growth & Optimization | `growth` | Growing and improving |
| Analytics & Metrics | `analytics` | Measuring and learning |
| Communication & Stakeholders | `communication` | Aligning people |
| Leadership & Career | `leadership` | Leading and growing as a PM |

### Difficulty Levels

| Level | Target Audience | Example |
|-------|----------------|---------|
| **Beginner** | New PMs, first-time framework users | Problem Statement, User Story, RACI |
| **Intermediate** | Experienced PMs, familiar with frameworks | PRD, OKRs, Prioritization Advisor |
| **Advanced** | Senior/Staff PMs, complex multi-dimensional work | Strategy Session, Growth Model, VP Readiness |

---

## Part 2: Markdown Sections

Every skill file has **7 standard sections** after the frontmatter. Here's what each does and why it matters.

---

### Section 1: Purpose

```markdown
## Purpose

Frame a customer problem with evidence before jumping to solutions. This skill 
forces clarity on who is affected, what is broken, why it matters, and how big 
the impact is.

This is not a solution brief. It's the foundation that every PRD, epic, and 
user story should trace back to.
```

**What it does:** 1-3 sentences explaining *what* this skill produces, *when* to use it, and *what it's not*.

**Why it matters:** Helps the AI (and you) quickly decide if this is the right skill for the job.

---

### Section 2: Key Concepts

```markdown
## Key Concepts

### The 5W1H Problem Frame
[Core framework explained with tables, diagrams, etc.]

### Why This Works
[Bullet list of reasons this approach is effective]

### Anti-Patterns (What This Is NOT)
[Common misunderstandings to prevent wrong usage]

### When to Use This / When NOT to Use This
[Situational guidance]
```

**What it does:** Teaches the core framework, mental model, or methodology behind the skill.

**Why it matters:** The AI uses this section to ground its output in established PM practice rather than generic advice.

---

### Section 3: Application

```markdown
## Application

### Step 1: [Action Name]
[Instructions with context]

\```markdown
**Field:** [Template to fill in]
\```

**Quality check:**
- [ ] [Verification question]
```

**What it does:** Step-by-step instructions with **fill-in templates** and **quality checks** at each step.

**Why it matters:** This is the core engine of the skill. The AI generates output by following these steps and filling in the templates with your specific context.

---

### Section 4: Examples

```markdown
## Examples

### ✅ Good Example
[Complete filled-in example]
**Why this works:** [Explanation]

### ❌ Bad Example
[Complete bad example]
**Why this fails:** [Explanation]
```

**What it does:** Concrete good and bad examples that calibrate the AI's output quality.

**Why it matters:** Examples are the most powerful teacher. The AI uses these to understand the quality bar.

---

### Section 5: Quality Rubric

```markdown
## Quality Rubric

Score each dimension 0-2. Target: 8+ out of 10.

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| Specificity | ... | ... | ... |
| Evidence | ... | ... | ... |
```

**What it does:** 5-dimension scoring system (0-2 per dimension) that the AI uses to self-evaluate its output.

**Why it matters:** Forces consistent quality. If any dimension scores below 2, the AI should suggest improvements before you finalize.

**Scoring guide:**
- **0 (Missing):** The dimension is absent or completely inadequate
- **1 (Partial):** Present but incomplete or generic
- **2 (Excellent):** Thorough, specific, and professional-grade

**Target:** 8+ out of 10 across all 5 dimensions.

---

### Section 6: Common Pitfalls

```markdown
## Common Pitfalls

### Pitfall 1: [Descriptive Name]
**Symptom:** [What you'll see when this happens]
**Consequence:** [Why it's bad]
**Fix:** [How to avoid or correct it]
```

**What it does:** Named failure modes with symptoms, consequences, and fixes.

**Why it matters:** Proactive pitfall detection. The AI flags these during generation, not after you've shared a flawed artifact with stakeholders.

---

### Section 7: References

```markdown
## References

### Related Skills
- `skills/domain/skill-name/SKILL.md` — [How it relates]

### External Frameworks
- [Framework Name] — [Brief description and source]
```

**What it does:** Cross-references to related skills and external frameworks.

**Why it matters:** Enables skill discovery and chaining. After completing one skill, the AI can suggest related skills for your next step.

---

## Quick Reference: Section Checklist

Use this when reviewing or creating a skill:

- [ ] **Frontmatter** — All 9 fields present with valid values
- [ ] **Purpose** — Clear what/when/why in 1-3 sentences
- [ ] **Key Concepts** — Core framework + anti-patterns + when/when not to use
- [ ] **Application** — Step-by-step with templates + quality checks per step
- [ ] **Examples** — At least 1 good + 1 bad with explanations
- [ ] **Quality Rubric** — 5 dimensions, 0-2 scale, target 8+/10
- [ ] **Common Pitfalls** — 2-4 named pitfalls with symptom/consequence/fix
- [ ] **References** — Related skills + external frameworks

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="building-your-own-skill.md"><strong>✍️ Build a Skill →</strong></a>
</p>
