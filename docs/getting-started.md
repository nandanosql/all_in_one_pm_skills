# 🚀 Getting Started with PM Skills

> From zero to your first professional PM output in 5 minutes.

---

## What Is PM Skills?

PM Skills is a library of **103 ready-to-use skill files** that turn any AI assistant into a senior product management partner. Instead of crafting one-off prompts, you load a skill file and get:

- **Structured guidance** — step-by-step processes with fill-in templates
- **Quality rubrics** — self-scoring to ensure professional-grade output
- **Frameworks** — battle-tested methods (RICE, Kano, OKRs, JTBD, etc.)
- **Anti-pattern detection** — common mistakes flagged before they happen

> **Prompts are one-shot. Skills are permanent upgrades.**

---

## The 30-Second Version

```
1. Browse the Catalog → find a skill that matches your task
2. Open the SKILL.md file
3. Upload/paste it into your AI tool
4. Say: "Use this skill to help me [your task]"
5. Follow the AI's guided process → get professional output
```

---

## Step 1: Find the Right Skill

### By Task (Most Common)

| I need to... | Skill to use | Domain |
|-------------|--------------|--------|
| Define a problem clearly | [`problem-statement`](../skills/discovery/problem-statement/SKILL.md) | Discovery |
| Understand my customers | [`jobs-to-be-done`](../skills/discovery/jobs-to-be-done/SKILL.md) | Discovery |
| Write a product strategy | [`product-strategy-session`](../skills/strategy/product-strategy-session/SKILL.md) | Strategy |
| Set OKRs | [`okr-framework`](../skills/strategy/okr-framework/SKILL.md) | Strategy |
| Prioritize my backlog | [`prioritization-advisor`](../skills/planning/prioritization-advisor/SKILL.md) | Planning |
| Create a roadmap | [`now-next-later-roadmap`](../skills/planning/now-next-later-roadmap/SKILL.md) | Planning |
| Write a PRD | [`prd-development`](../skills/specification/prd-development/SKILL.md) | Specification |
| Write user stories | [`user-story`](../skills/specification/user-story/SKILL.md) | Specification |
| Run a sprint | [`agile-delivery-process`](../skills/execution/agile-delivery-process/SKILL.md) | Execution |
| Plan a product launch | [`launch-process`](../skills/launch/launch-process/SKILL.md) | Launch |
| Design an A/B test | [`ab-test-design`](../skills/growth/ab-test-design/SKILL.md) | Growth |
| Calculate SaaS metrics | [`saas-economics-efficiency-metrics`](../skills/analytics/saas-economics-efficiency-metrics/SKILL.md) | Analytics |
| Align stakeholders | [`stakeholder-alignment-advisor`](../skills/communication/stakeholder-alignment-advisor/SKILL.md) | Communication |
| Prepare for PM interviews | [`pm-interview-prep`](../skills/leadership/pm-interview-prep/SKILL.md) | Leadership |

### By Domain

The 103 skills are organized into **10 PM lifecycle domains**. Browse the full list in the [**Catalog →**](../CATALOG.md).

### By Skill Type

| Type | Count | Best For |
|------|-------|----------|
| 🧱 **Component** | 62 | Single artifacts — PRDs, user stories, OKRs, battle cards |
| 🔄 **Interactive** | 32 | Guided multi-turn sessions with adaptive questioning |
| 🎭 **Workflow** | 7 | End-to-end processes orchestrating multiple skills |

> **New to PM?** Start with Component skills — they're the most straightforward.
> **Experienced PM?** Jump to Interactive or Workflow skills for deeper sessions.

---

## Step 2: Choose Your AI Tool

PM Skills works with **any** AI assistant that can read text. Here's how to pick:

```
Do you code / use a terminal?
├── Yes → Claude Code, Gemini CLI, or Codex (best quality & control)
└── No
    ├── Want a quick one-off? → Paste skill into any AI chat
    └── Want reusable setup? → ChatGPT Projects or Claude Desktop
```

| Tool | Setup Effort | Best For | Guide |
|------|-------------|----------|-------|
| **Claude Code** | Medium | Power users, best output quality | [Guide →](using-with-claude.md) |
| **Claude Desktop** | Low | Non-technical, reusable sessions | [Guide →](using-with-claude.md) |
| **ChatGPT** | Low | Quick start, Projects for reuse | [Guide →](using-with-chatgpt.md) |
| **Gemini** | Low-Medium | Google ecosystem, CLI users | [Guide →](using-with-gemini.md) |
| **Codex** | Medium | OpenAI ecosystem, local repos | [Guide →](using-with-codex.md) |

---

## Step 3: Load and Use a Skill

### Method A: Copy-Paste (Works Everywhere)

1. Open the `SKILL.md` file in GitHub or your editor
2. Copy the entire contents
3. Paste into your AI chat
4. Tell the AI what you need:

```
I've loaded a PM skill. Use it to help me write a problem statement 
for our checkout abandonment issue.
```

### Method B: File Upload (ChatGPT, Claude)

1. Download the `SKILL.md` file
2. Upload it to your ChatGPT Project or Claude conversation
3. Ask the AI to follow the skill

### Method C: Local Repo (Claude Code, Gemini CLI, Codex)

```bash
# Clone the repo
git clone https://github.com/nandanosql/pm-skills.git

# Point your AI agent at a specific skill
# The agent reads and applies SKILL.md automatically
```

---

## Step 4: Get Professional Output

Once the skill is loaded, the AI will:

1. **Ask clarifying questions** (for Interactive skills)
2. **Walk you through each step** with templates to fill in
3. **Generate the complete artifact** (PRD, user story, roadmap, etc.)
4. **Self-score using the quality rubric** (0–2 per dimension, target: 8+/10)
5. **Flag common pitfalls** before you share with stakeholders

### Example Session

```
You: Use this skill to help me prioritize my product backlog.

AI: I'll help you prioritize using the Prioritization Advisor skill.
    First, let me understand your context:
    
    1. What type of product are you working on? (B2B SaaS / B2C / Platform / Internal)
    2. How many items are in your backlog? (~10 / ~25 / 50+)
    3. Who is the audience for this prioritization? (Your team / Leadership / Board)
    
    Based on your answers, I'll recommend the right framework 
    (RICE, ICE, Kano, MoSCoW, or WSJF) and guide you through it.
```

---

## What's Next?

| Your Situation | Next Step |
|---------------|-----------|
| "I want to master one domain" | [Domain Deep Dives →](domain-deep-dives.md) |
| "How do skills chain together?" | [Skill Chaining & Workflows →](skill-chaining-and-workflows.md) |
| "I want to create my own skill" | [Building Your Own Skill →](building-your-own-skill.md) |
| "I have questions" | [FAQ →](faq.md) |

---

<p align="center">
  <a href="../CATALOG.md"><strong>📖 Browse All 103 Skills →</strong></a>
</p>
