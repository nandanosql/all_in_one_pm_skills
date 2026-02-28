---
name: ai-shaped-readiness-advisor
description: Assess whether you're "AI-first" (automating tasks) or "AI-shaped" (redesigning workflows). Evaluates 5 competencies and recommends which to build first.
type: interactive
domain: strategy
difficulty: advanced
estimated_time: "20-30 min"
prerequisites: []
outputs: ["ai-readiness-assessment"]
triggers:
  - "Am I using AI strategically"
  - "AI readiness assessment"
  - "Are we AI-shaped or just AI-first"
  - "How mature is our AI adoption"
---

## Purpose

Assess whether your team/organization is truly **AI-shaped** (redesigning how you work with AI) or merely **AI-first** (automating existing tasks). Evaluates five competencies and provides a maturity score with specific recommendations.

---

## Key Concepts

### AI-First vs. AI-Shaped

| AI-First (Task Automation) | AI-Shaped (Workflow Redesign) |
|---------------------------|-------------------------------|
| "Use AI to write PRDs faster" | "Redesign the PRD process with AI as a collaborator" |
| Same workflow, faster | Different workflow, better outcomes |
| Efficiency gains | Capability gains |
| Easy to adopt | Requires organizational change |
| Low ceiling on impact | High ceiling on impact |

### Five Competencies

1. **Context Engineering** — How well do you structure information for AI?
2. **Prompt Craft** — How well do you communicate with AI?
3. **Evaluation** — How well do you assess AI output quality?
4. **Integration** — How deeply is AI woven into workflows?
5. **Culture** — Does your team embrace AI as a partner?

---

## Application

### Question 1: Current AI Usage

**Agent asks:** "How is your team currently using AI in product work?"

**Options:**
1. **Not at all** — We haven't started
2. **Ad hoc** — Individual team members use ChatGPT/Claude sometimes
3. **Standardized** — We have defined AI tools and prompts for common tasks
4. **Integrated** — AI is built into our product workflows
5. **Native** — Our workflows were designed around AI capabilities from the start

---

### Question 2: Context Engineering

**Agent asks:** "When you use AI, how do you provide context?"

**Options:**
1. **Copy-paste everything** — Dump full documents into the prompt
2. **Selective sharing** — Choose relevant sections but no structure
3. **Structured context** — Use templates, personas, and constraints
4. **Memory architecture** — Maintain persistent context across sessions
5. **Automated context pipelines** — Systems that automatically prepare context

---

### Question 3-5: [Similar adaptive questions for Evaluation, Integration, Culture]

---

### Output: AI Readiness Assessment

```markdown
# AI Readiness Assessment

## Overall Score: [X/25]

| Competency | Score (1-5) | Level | Key Gap |
|-----------|------------|-------|---------|
| Context Engineering | [#] | [Label] | [Gap] |
| Prompt Craft | [#] | [Label] | [Gap] |
| Evaluation | [#] | [Label] | [Gap] |
| Integration | [#] | [Label] | [Gap] |
| Culture | [#] | [Label] | [Gap] |

## Maturity Level: [AI-First / Transitioning / AI-Shaped]

## Priority Recommendations
1. **Start with:** [Lowest-scoring competency] — [Specific action]
2. **Then build:** [Next priority] — [Specific action]
3. **Long-term:** [Highest-ceiling opportunity] — [Specific action]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Honesty** | Aspirational answers | Mostly honest | Evidence-based self-assessment |
| **Specificity** | "We use AI" | Named tools/workflows | Specific examples per competency |
| **Actionability** | Score only | Recommendations | Prioritized actions with timeline |

---

## References

### Related Skills
- `skills/communication/context-engineering-advisor/SKILL.md` — Deep dive on context competency
- `skills/strategy/product-vision-statement/SKILL.md` — AI-shaped vision integration

---

**Skill type:** Interactive
**Domain:** Strategy & Vision
