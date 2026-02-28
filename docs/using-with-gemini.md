# 🤖 Using PM Skills with Gemini

> Complete guide for Gemini Chat, Gemini CLI, and Google AI Studio.

---

## Which Gemini Tool Should I Use?

| Tool | Best For | Setup |
|------|----------|-------|
| **Gemini Chat** (gemini.google.com) | Quick tasks, paste-and-go | None |
| **Gemini CLI** | Power users, local repo, best quality | Medium |
| **Google AI Studio** | Prototyping, system instructions, testing | Low |
| **Gemini in Workspace** | Google Docs/Sheets workflow integration | Low |

---

## Gemini Chat (Web / App)

### Quick Start

1. Open [gemini.google.com](https://gemini.google.com)
2. Upload or paste a `SKILL.md` file
3. Add your request:

```
I've loaded a PM skill. Use it to help me [your task].
Follow the sections in order: Purpose → Key Concepts → Application.
Ask clarifying questions if needed, then generate the complete output.
Score it against the Quality Rubric at the end.
```

### Using Gems (Reusable Assistants)

1. Go to **Gemini** → **Gem Manager** → **New Gem**
2. Name it: "PM Skills Assistant"
3. Set the instructions:

```
You are a senior PM assistant powered by PM Skills. When the user asks for 
PM help:
1. Identify which skill applies from the uploaded context.
2. Follow the skill sections in order: Purpose → Key Concepts → Application → 
   Examples → Pitfalls → References.
3. For Interactive skills: ask all questions BEFORE generating.
4. For Component skills: produce the full template, then self-score.
5. Target 8+/10 on all quality rubrics.
```

4. Upload frequently used `SKILL.md` files
5. Save — every conversation with this Gem uses your skills

---

## Gemini CLI

The Gemini CLI provides the best output quality because it reads skills directly from your filesystem.

### Setup

```bash
# 1. Install Gemini CLI
npm install -g @anthropic-ai/gemini-cli

# 2. Clone the repo
git clone https://github.com/nandanosql/pm-skills.git
cd pm-skills

# 3. Start Gemini CLI
gemini
```

### How to Load Skills

**Single skill:**
```
Read skills/strategy/okr-framework/SKILL.md and help me set Q3 OKRs 
for our growth team.
```

**Multiple skills in sequence:**
```
First use skills/discovery/problem-statement/SKILL.md to define our problem.
Then use skills/strategy/north-star-metric/SKILL.md to establish our NSM.
```

**Workflow skill:**
```
Run skills/discovery/discovery-process/SKILL.md for a full discovery cycle 
on our enterprise onboarding problem.
```

### Tips for Gemini CLI

1. **Start from the repo root** so Gemini can navigate to any skill
2. **Use natural language triggers** — the YAML frontmatter lists trigger phrases
3. **Request quality scoring** after each output
4. **Chain skills** by saying "Now switch to [next skill]"

---

## Google AI Studio

AI Studio is great for testing skills with custom system instructions and adjusting model parameters.

### Setup

1. Open [aistudio.google.com](https://aistudio.google.com)
2. Create a new **Structured Prompt** or **Chat Prompt**
3. In **System Instructions**, paste your PM Skills operating instructions:

```
You are a senior PM assistant. When given a PM skill file, follow its 
structure exactly:
1. Purpose — understand when and why to use this skill
2. Key Concepts — internalize the frameworks
3. Application — follow each step, use the templates
4. Examples — reference good/bad examples for calibration
5. Quality Rubric — self-score every output (target 8+/10)
6. Common Pitfalls — flag proactively
7. References — suggest related skills when relevant
```

4. In the **User** turn, paste or upload a `SKILL.md` file + your request
5. Adjust **Temperature** (recommended: 0.3–0.7 for PM outputs) and test

---

## Gemini in Google Workspace

If your organization uses Google Workspace with Gemini enabled:

### In Google Docs
1. Open a Google Doc
2. Use **Help me write** or the Gemini side panel
3. Paste the relevant skill's Application section as context
4. Ask Gemini to follow the template

### In Google Sheets
1. For analytics skills (funnel analysis, SaaS metrics, cohort analysis)
2. Paste the framework from the skill file
3. Ask Gemini to help you build the spreadsheet model

> **Note:** Workspace Gemini has shorter context windows. Upload 1 skill at a time for best results.

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Gemini doesn't follow the skill structure | Add explicit instruction: "Follow each section in order" |
| Output too brief | Say: "Follow the full Application section with all steps and templates" |
| Quality rubric ignored | Ask: "Score this against the quality rubric from the skill file" |
| File upload not available | Use copy-paste instead |
| Gem doesn't retain skills | Re-upload files and verify they appear in the Gem's knowledge |

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="../CATALOG.md"><strong>📖 Browse Skills →</strong></a>
</p>
