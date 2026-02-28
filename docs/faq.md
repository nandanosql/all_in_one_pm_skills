# ❓ Frequently Asked Questions

> Quick answers to the most common questions about PM Skills.

---

## General

### Do I need to use all 103 skills?

**No.** Most PMs regularly use 5-10 skills. Start with the ones that match your immediate needs:

- New to PM → Start with `problem-statement`, `user-story`, and `prioritization-advisor`
- Experienced PM → Jump to the skills for your current challenge
- Learning PM → Work through one [domain](domain-deep-dives.md) per week

### Which AI tool should I use?

See the quick decision guide:

| Your situation | Best choice |
|---------------|-------------|
| "I want the quickest start" | Paste into any AI chat |
| "I use Claude regularly" | [Claude Desktop/Web](using-with-claude.md) |
| "I use ChatGPT regularly" | [ChatGPT Projects](using-with-chatgpt.md) |
| "I want the best quality" | [Claude Code](using-with-claude.md) or [Gemini CLI](using-with-gemini.md) |
| "I want reusable team tools" | ChatGPT Custom GPTs |

### Can I use PM Skills with any AI, not just the listed ones?

**Yes.** PM Skills are plain Markdown files. Any AI that can read text can use them. The tool-specific guides are optimization tips, not requirements.

### Is PM Skills free?

**Yes.** The entire skill library is open source. The AI tools you use with it may have their own costs.

---

## Using Skills

### How do I know which skill to use?

Three ways:

1. **By task** — Check the [Getting Started](getting-started.md) table that maps "I want to..." to skills
2. **By domain** — Browse the [Catalog](../CATALOG.md) organized by PM lifecycle stage
3. **By trigger** — Each skill's YAML frontmatter lists natural language triggers

### What's the difference between Component, Interactive, and Workflow skills?

| Type | Behavior | Think of it as... |
|------|----------|-------------------|
| 🧱 **Component** | Fill-in template → artifact | A form + checklist |
| 🔄 **Interactive** | Q&A → customized guidance → artifact | A consultation |
| 🎭 **Workflow** | Multi-phase process → multiple artifacts | A guided project |

### Can I use multiple skills in one session?

**Yes.** See [Skill Chaining & Workflows](skill-chaining-and-workflows.md) for patterns. The basic approach:

```
Complete Skill A → use its output as input for Skill B → continue to Skill C
```

### What does the Quality Rubric score mean?

| Score | Quality | What to do |
|-------|---------|------------|
| 9-10 | Excellent | Share with stakeholders confidently |
| 7-8 | Good | Fix the lowest dimension, then share |
| 5-6 | Needs work | Revise 2+ dimensions |
| < 5 | Start over | Add more context, re-read the skill |

### The AI isn't following the skill format. What do I do?

Add this instruction at the start of your conversation:

```
Follow the uploaded skill file's sections in strict order: 
Purpose → Key Concepts → Application → Examples → Quality Rubric → Pitfalls.
Use the fill-in templates from the Application section exactly as written.
Self-score every output against the Quality Rubric.
```

---

## Customization

### Can I modify skills for my team?

**Absolutely.** Skills are Markdown files — fork the repo and customize:

- Add your product's context to examples
- Adjust quality rubric dimensions for your standards
- Add team-specific pitfalls you've encountered
- Modify templates to match your internal formats

### Can I create my own skills?

**Yes.** See [Building Your Own Skill](building-your-own-skill.md) for the full guide. Use the [`SKILL_TEMPLATE.md`](../SKILL_TEMPLATE.md) to get started.

### Can I combine multiple skills into one custom skill?

You can, but it's better to use **skill chaining** instead. Single skills that try to do too much produce worse output than focused skills chained together.

### How do I keep skills updated?

If you cloned the repo, pull the latest changes:

```bash
git pull origin main
```

If you uploaded files, re-download updated versions from the repository.

---

## Skill Quality

### Why do some skills produce better output than others?

Three factors:

1. **Context provided** — more context = better output
2. **AI model capability** — more capable models produce better results
3. **Skill complexity** — beginner skills are more straightforward; advanced skills need more context to shine

### How do I improve output quality?

1. **Add context** — product, market, team, constraints
2. **Use the rubric** — generate → score → fix weak dimensions → regenerate
3. **Try a better model** — GPT-4o/Claude Sonnet/Gemini Pro for complex skills
4. **Chain skills** — use a discovery skill before a specification skill

### Are the frameworks in skills always correct?

Skills are based on widely-recognized PM frameworks (RICE, Kano, OKRs, JTBD, etc.), but:

- Frameworks are tools, not rules — adapt them to your context
- No framework fits every situation — the "When NOT to Use This" sections help avoid misapplication
- External references in each skill link to original sources for deeper learning

---

## Contributing

### How can I contribute a new skill?

1. Read [Building Your Own Skill](building-your-own-skill.md)
2. Copy [`SKILL_TEMPLATE.md`](../SKILL_TEMPLATE.md)
3. Create your skill in `skills/[domain]/[skill-name]/SKILL.md`
4. Follow the quality checklist
5. Submit a PR

### What skills are missing?

Look for domains with fewer skills or gaps in the [Catalog](../CATALOG.md). Common requests:

- Industry-specific adaptations (fintech, healthcare, marketplace)
- More workflow skills (Growth and Analytics domains have none currently)
- Advanced leadership skills (board management, M&A product integration)

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a>
</p>
