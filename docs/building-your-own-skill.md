# ✍️ Building Your Own Skill

> Step-by-step guide to creating a new PM skill from scratch.

---

## Before You Start

### What Makes a Good Skill?

A skill is worth creating when:

- ✅ It solves a **repeatable** PM task (not a one-off)
- ✅ It's based on a **recognized framework** or methodology
- ✅ It produces a **concrete artifact** or decision
- ✅ It can be **self-scored** against a quality rubric
- ✅ It takes **10-60 minutes** per use

A skill is NOT:

- ❌ A generic prompt ("write me a strategy")
- ❌ A one-time analysis with no reusable structure
- ❌ A tool tutorial (how to use Jira, Figma, etc.)
- ❌ A philosophical essay about product management

### Choose the Right Skill Type

| Choose... | When... |
|-----------|---------|
| 🧱 **Component** | The output is a single artifact (PRD, user story, battle card). Fill-in template, no back-and-forth. |
| 🔄 **Interactive** | The output depends heavily on context that varies each time. Needs clarifying questions first. |
| 🎭 **Workflow** | The process spans multiple phases and orchestrates other skills. End-to-end playbook. |

---

## Step-by-Step Guide

### Step 1: Start from the Template

Copy [`SKILL_TEMPLATE.md`](../SKILL_TEMPLATE.md) to your new skill directory:

```
skills/
└── [domain]/
    └── [skill-name]/
        └── SKILL.md
```

**Naming rules:**
- Folder name = `kebab-case` (e.g., `problem-statement`, `ab-test-design`)
- Must match the `name` field in frontmatter
- Be descriptive but short (2-4 words)

### Step 2: Fill in the Frontmatter

```yaml
---
name: your-skill-name
description: One line, ≤200 chars, what this skill does
type: component | interactive | workflow
domain: discovery | strategy | planning | specification | execution | launch | growth | analytics | communication | leadership
difficulty: beginner | intermediate | advanced
estimated_time: "15-30 min"
prerequisites: [list-of-skill-names-or-empty]
outputs: ["artifact-name"]
triggers:
  - "Natural language phrase that should activate this skill"
  - "Another trigger phrase"
  - "A third trigger phrase"
---
```

**Tips:**
- Write 3-5 triggers that sound like how a real PM would ask for help
- `prerequisites` should only list skills that *must* be done first (keep it short)
- `estimated_time` should reflect a typical session, not a power user

### Step 3: Write the Purpose

Write 1-3 sentences covering:
1. **What** this skill produces
2. **When** to use it
3. **What it's NOT** (scope boundary)

```markdown
## Purpose

[What this skill does and what artifact it produces.]

[When you would use this — the triggering scenario.]

[What this skill is NOT — prevent misuse.]
```

### Step 4: Document Key Concepts

```markdown
## Key Concepts

### [Name of Core Framework]
[Explain the framework with tables, diagrams, or lists]

### Why This Works
- [Reason 1]
- [Reason 2]
- [Reason 3]

### Anti-Patterns (What This Is NOT)
- **Not [X]:** [Why this doesn't apply]

### When to Use This
- [Scenario 1]
- [Scenario 2]

### When NOT to Use This
- [Scenario 1 — and what to use instead]
```

### Step 5: Build the Application Section

This is the core of the skill. Each step should:
1. Give clear instructions
2. Provide a **fill-in template** in a code block
3. Include **quality checks** after each step

```markdown
## Application

### Step 1: [Action Name]

[Instructions explaining what to do and why.]

\```markdown
**Field 1:** [What to fill in — with example placeholder]
**Field 2:** [What to fill in]
\```

**Quality check:**
- [ ] [Yes/no question to verify quality]
- [ ] [Another verification question]

---

### Step 2: [Next Action]
[Continue pattern...]
```

**How many steps?**
- Component skills: 4-7 steps
- Interactive skills: 3-5 phases with questions
- Workflow skills: 4-8 phases with sub-skills

### Step 6: Add Examples

Every skill needs at least one good and one bad example:

```markdown
## Examples

### ✅ Good Example
\```markdown
[Complete, realistic example — fully filled in]
\```
**Why this works:** [Explain what makes it excellent]

### ❌ Bad Example
\```markdown
[Complete bad example — realistic mistakes]
\```
**Why this fails:** [Explain what's wrong and how to fix it]
```

**Tips:**
- Make examples **realistic** (use believable product scenarios)
- Bad examples should contain **common** mistakes (not extreme failures)
- Explain *why* — not just *what*

### Step 7: Create the Quality Rubric

Design 5 dimensions that capture the most important quality signals:

```markdown
## Quality Rubric

Score each dimension 0-2. **Target: 8+ out of 10.**

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| [Dim 1] | [What's missing] | [What's partial] | [What's excellent] |
| [Dim 2] | ... | ... | ... |
| [Dim 3] | ... | ... | ... |
| [Dim 4] | ... | ... | ... |
| [Dim 5] | ... | ... | ... |

**If score < 8:** Revise the weakest dimension before finalizing.
```

**Dimension design tips:**
- Focus on the *most common* quality gaps, not edge cases
- Level 1 ("Partial") should capture the "typical first draft" quality
- Level 2 ("Excellent") should match what a senior PM would produce

### Step 8: Document Common Pitfalls

List 2-4 named failure modes:

```markdown
## Common Pitfalls

### Pitfall 1: [Descriptive Name]
**Symptom:** [What you'll see when this happens]
**Consequence:** [Why it's bad — what goes wrong downstream]
**Fix:** [How to avoid or correct it]
```

### Step 9: Add References

```markdown
## References

### Related Skills
- `skills/[domain]/[skill-name]/SKILL.md` — [How it relates to this skill]

### External Frameworks
- [Framework Name] — [Brief description and original source]
```

### Step 10: Final Footer

```markdown
---

**Skill type:** [component | interactive | workflow]
**Domain:** [Domain Name]
**Prerequisites:** [list or "None"]
```

---

## Quality Checklist

Before submitting your skill, verify:

- [ ] Frontmatter has all 9 required fields
- [ ] `name` matches the folder name
- [ ] 3-5 natural-sounding triggers
- [ ] Purpose is clear in 1-3 sentences
- [ ] Key Concepts section teaches the core framework
- [ ] Application has step-by-step with templates AND quality checks
- [ ] At least 1 good example + 1 bad example with explanations
- [ ] Quality rubric has 5 dimensions with 0/1/2 scoring
- [ ] 2-4 common pitfalls with symptom/consequence/fix
- [ ] References include related skills and external frameworks
- [ ] Footer matches frontmatter values

---

## File Structure

```
skills/
└── [domain]/
    └── [your-skill-name]/
        └── SKILL.md          ← Your skill file (required)
```

**Directory placement rules:**
- Skill goes in the directory matching its `domain` field
- Each skill gets its own subdirectory
- The file must be named `SKILL.md` (all caps)

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="skill-format-guide.md"><strong>📐 Skill Format Reference →</strong></a>
</p>
