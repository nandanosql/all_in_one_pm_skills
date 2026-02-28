# 🤖 Using PM Skills with Claude

> Complete guide for Claude Code (CLI), Claude Desktop, and Claude Web.

---

## Which Claude Tool Should I Use?

| Tool | Best For | Setup |
|------|----------|-------|
| **Claude Code (CLI)** | Power users, best quality, multi-skill workflows | Medium |
| **Claude Desktop** | Everyday PM work, file uploads, reusable projects | Low |
| **Claude Web** | Quick one-off tasks, no installation needed | None |

---

## Claude Code (CLI)

Claude Code gives you the best output quality because it can read skill files directly from your local filesystem.

### Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/nandanosql/pm-skills.git
cd pm-skills

# 2. Start Claude Code in the repo directory
claude

# 3. Ask Claude to use a skill
> Use skills/discovery/problem-statement/SKILL.md to help me frame 
  our checkout abandonment problem.
```

### How to Load Skills

**Single skill:**
```
Read skills/planning/prioritization-advisor/SKILL.md and use it to help me 
prioritize our Q3 backlog.
```

**Multiple skills in sequence:**
```
First, read skills/discovery/problem-statement/SKILL.md and help me define the problem.
Then use skills/specification/prd-development/SKILL.md to turn it into a PRD.
```

**Workflow skill (orchestrates others automatically):**
```
Run the discovery process using skills/discovery/discovery-process/SKILL.md.
It will pull in related skills as needed.
```

### Tips for Claude Code

1. **Point Claude at the repo root** — it can navigate to any skill file
2. **Use trigger phrases** — each skill has triggers in its YAML frontmatter that activate it naturally
3. **Ask for quality scoring** — say "score this output against the quality rubric" after generation
4. **Chain skills explicitly** — "Now use [next skill] to continue" for multi-step workflows

---

## Claude Desktop / Claude Web

### Option 1: Upload Skill Files

1. Open a new Claude conversation
2. Click the **📎 attachment** icon
3. Upload one or more `SKILL.md` files from the repo
4. Tell Claude to follow the skill:

```
I've uploaded a PM skill file. Use it as the operating standard for our session.
Follow each section in order: Purpose → Key Concepts → Application → Examples.
Ask me up to 3 clarifying questions before drafting.
```

### Option 2: Copy-Paste

1. Open the `SKILL.md` file in GitHub or your editor
2. Copy the entire contents
3. Paste into the Claude chat window
4. Add your request after the pasted content

### Option 3: Claude Projects (Reusable)

1. Create a new **Claude Project**
2. Add skill files to the project's **Knowledge Base**
3. Set the project instructions:

```
When performing PM tasks, use the skill files in this project's knowledge base 
as operating standards. Follow each skill's sections in order: Purpose, Key Concepts, 
Application, Examples, Common Pitfalls, References. If context is missing, ask up 
to 3 clarifying questions before drafting. Self-score outputs against the Quality 
Rubric and flag any dimension scoring below 2.
```

4. Every conversation in this project will automatically use your loaded skills

---

## Recommended Instruction Snippet

Use this in any Claude setup for consistent results:

```
## PM Skills Operating Instructions

1. When I reference a PM skill, follow its sections in strict order:
   Purpose → Key Concepts → Application → Examples → Quality Rubric → Pitfalls
   
2. For Interactive skills: ask all clarifying questions BEFORE generating output.

3. For Component skills: generate the complete template, then self-score.

4. For Workflow skills: announce each phase and which sub-skills you're using.

5. After generating any artifact, score it against the Quality Rubric (target: 8+/10).
   If any dimension is below 2, suggest specific improvements.

6. Flag Common Pitfalls proactively — don't wait for me to ask.
```

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Claude ignores the skill structure | Re-paste the instruction snippet above at the start of the conversation |
| Output is too generic | Add project-specific context: your product, market, user segments |
| Claude skips the quality rubric | Explicitly ask: "Score this against the quality rubric" |
| File upload not working | Try copy-paste instead — some Claude plans have upload limits |
| Too many skills loaded at once | Start with 1-3 focused skills; more can dilute quality |

---

## Example Session

```
You: [Uploads prioritization-advisor SKILL.md]
     Help me prioritize features for our B2B SaaS product's Q3 roadmap.

Claude: I'll use the Prioritization Advisor skill to help you.
        
        First, let me understand your context:
        1. What type of decisions are you prioritizing? 
           (New features / Tech debt / Bug fixes / Mixed backlog)
        2. How many items need prioritization? (~10 / ~25 / 50+)
        3. Who will consume this prioritization? 
           (Engineering team / Leadership / Board)
        4. Do you have data on: revenue impact, reach, effort estimates?
        
        Based on your answers, I'll recommend RICE, ICE, Kano, MoSCoW, 
        or WSJF and walk you through applying it.

You: Mixed backlog of about 25 items, for leadership. 
     We have rough effort estimates but limited revenue data.

Claude: Given a mixed backlog with limited revenue data, I recommend 
        the ICE framework (Impact, Confidence, Ease)...
        [Continues with structured guidance]
```

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="../CATALOG.md"><strong>📖 Browse Skills →</strong></a>
</p>
