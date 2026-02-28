# 💡 Best Practices

> Tips, anti-patterns, and rules of thumb for getting the most out of PM Skills.

---

## Getting the Best Output

### 1. Provide Context First

Before using any skill, give the AI **background** about your product, market, and situation. The more specific you are, the better the output.

```
Context:
- Product: B2B SaaS project management tool for agencies
- Stage: Series A, 500 paying customers
- Team: 4 engineers, 1 designer, 1 PM
- Current focus: Reducing churn (8% monthly → target 4%)
```

### 2. Use One Skill at a Time (Usually)

Loading 10 skills simultaneously dilutes quality. Start with **1 skill**, complete it, then chain to the next.

**Exception:** Workflow skills are designed to use multiple skills — they handle the orchestration for you.

### 3. Always Request Quality Scoring

After the AI generates output, ask:

```
Score this against the quality rubric. If any dimension is below 2, 
suggest specific improvements.
```

This turns a "good enough" draft into a professional-grade artifact.

### 4. Iterate, Don't Regenerate

If the output isn't right, don't start over. Instead:

```
The "Impact" dimension scored 1/2. Improve it by:
- Adding revenue impact estimates
- Including strategic alignment with our Q3 OKRs
- Quantifying the opportunity cost of inaction
```

### 5. Match Skill Type to Your Need

| If you want... | Use... |
|----------------|--------|
| A quick artifact to fill in | 🧱 Component skill |
| Guidance on *which* approach to take | 🔄 Interactive skill |
| An end-to-end process | 🎭 Workflow skill |

---

## Common Mistakes (And How to Fix Them)

### ❌ Mistake 1: Using Skills as Prompts

**Bad:** "Write me a PRD" (ignoring the skill file)

**Good:** "Use the prd-development skill to walk me through creating a PRD for our new search feature. Follow each section in order."

**Why:** Skills have structure, quality checks, and pitfall detection. Vanilla prompts skip all of that.

---

### ❌ Mistake 2: Skipping the Key Concepts Section

**Bad:** Jumping straight to Application without understanding the framework.

**Good:** Read (or have the AI explain) the Key Concepts first. This grounds the output in proven methodology instead of generic AI writing.

---

### ❌ Mistake 3: Not Providing Context

**Bad:** "Help me prioritize my backlog."

**Good:** 
```
Help me prioritize 15 features for our B2B SaaS product. 
We're pre-PMF, resource-constrained (2 engineers), and 
focused on reducing time-to-value for new signups.
```

**Why:** Without context, the AI defaults to generic advice. With context, it adapts the framework to your specific reality.

---

### ❌ Mistake 4: Accepting the First Draft

**Bad:** Taking AI output at face value and sending it to stakeholders.

**Good:** 
1. Generate with skill → 2. Score with rubric → 3. Fix weak dimensions → 4. Review for accuracy → 5. Share

---

### ❌ Mistake 5: Loading Too Many Skills at Once

**Bad:** Uploading 20 skill files to a ChatGPT Project.

**Good:** Start with 1-3 related skills (e.g., the Discovery Kit: problem-statement + proto-persona + JTBD).

**Why:** More files = more dilution. The AI struggles to deeply apply 20 frameworks simultaneously.

---

### ❌ Mistake 6: Ignoring Anti-Patterns

**Bad:** Skipping the "When NOT to Use This" section.

**Good:** Read it first. If your situation matches a "When NOT" scenario, you'll save 30 minutes by choosing the right skill.

---

## Rules of Thumb

### The 30-Second Decision

```
I need a quick template to fill in    → Component skill
I need help deciding an approach      → Interactive skill  
I need a multi-step guided process    → Workflow skill
I just need terminology explained     → Glossary
I'm confused about which skill to use → Getting Started
```

### The 3-Skill Stack

When starting any new product initiative, these three skills cover 80% of your needs:

1. **`problem-statement`** — What's broken and for whom?
2. **`prioritization-advisor`** — Should we work on this now?
3. **`prd-template`** — What exactly should we build?

### Quality Score Interpretation

| Score | Meaning | Action |
|-------|---------|--------|
| **9-10** | Excellent — ready for stakeholders | Share with confidence |
| **7-8** | Good — minor gaps | Fix the lowest-scoring dimension |
| **5-6** | Fair — needs work | Revise 2+ dimensions before sharing |
| **< 5** | Poor — restart | Re-read the skill, add more context, regenerate |

### When to Use Discovery Skills vs. Specification Skills

```
"We think we know the problem" → Use Specification skills (PRD, stories)
"We're not sure what to build" → Use Discovery skills FIRST
"We disagree on the problem"   → Always start with Discovery
```

---

## Efficiency Tips

1. **Create AI tool presets** — save your PM Skills system instructions as a reusable template
2. **Bookmark your top 5 skills** — you'll use 10% of skills 90% of the time
3. **Use the Catalog as a menu** — scan it when you aren't sure which skill fits
4. **Save outputs to a PM wiki** — build an archive of your team's PM artifacts
5. **Share skills with your team** — consistency across PMs is a superpower

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a>
</p>
