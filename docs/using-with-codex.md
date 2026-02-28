# 🤖 Using PM Skills with Codex

> Complete guide for OpenAI Codex in local workspace and ChatGPT-linked modes.

---

## Which Mode Should I Use?

| Mode | Best For | Setup |
|------|----------|-------|
| **Local Workspace** | Full file access, best quality, repeatable workflows | Medium |
| **ChatGPT-linked** | Use Codex within ChatGPT with GitHub access | Low |

---

## Option 1: Local Workspace (Recommended)

Codex can read skill files directly from your filesystem for the highest quality output.

### Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/nandanosql/pm-skills.git
cd pm-skills

# 2. Launch Codex with the repo as workspace
codex

# 3. Ask Codex to use a skill
> Read skills/specification/prd-template/SKILL.md and help me write 
  a PRD for our new search feature.
```

### How to Apply Skill Types

**Component skills** — single artifact generation:
```
Use skills/specification/user-story/SKILL.md to write user stories 
for the checkout redesign. Follow all steps and score against the rubric.
```

**Interactive skills** — guided multi-turn sessions:
```
Use skills/planning/prioritization-advisor/SKILL.md to help me choose 
a prioritization framework. Ask me your clarifying questions first.
```

**Workflow skills** — multi-phase orchestration:
```
Run skills/execution/agile-delivery-process/SKILL.md for our sprint 
planning. Follow each phase and pull in sub-skills as needed.
```

### Chaining Multiple Skills

```
I want to run a full discovery-to-spec session:

1. Start with skills/discovery/problem-statement/SKILL.md — define the problem
2. Then skills/discovery/jobs-to-be-done/SKILL.md — identify core JTBD
3. Then skills/specification/prd-development/SKILL.md — write the PRD

Walk me through each in sequence, completing one before moving to the next.
```

---

## Option 2: Codex on ChatGPT (GitHub-Connected)

Use Codex within ChatGPT to pull skills directly from the GitHub repository.

### Setup

1. In **ChatGPT**, go to **Settings** → **Apps** → connect **GitHub**
2. Authorize access to the PM Skills repo
3. In a Codex-enabled chat, reference skills by path:

```
Use skills/growth/ab-test-design/SKILL.md from nandanosql/pm-skills 
to help me design an A/B test for our new pricing page.
```

### Practical Prompt Pattern

```
From the nandanosql/pm-skills repository:
1. Read skills/analytics/funnel-analysis/SKILL.md
2. Apply it to analyze our signup-to-activation funnel
3. Use the templates from the Application section
4. Score the output against the Quality Rubric

Context:
- Product: B2B SaaS project management tool
- Funnel: Signup → Profile Setup → Create Project → Invite Team → First Task
- Current data: 1000 signups/month, 23% reach "First Task"
```

---

## Configuration Tips

### System Prompt (for Both Modes)

Add this to your Codex system prompt or prepend to conversations:

```
## PM Skills Operating Standard

When asked to use a PM skill:
1. Read the entire SKILL.md file before starting.
2. Follow sections in order: Purpose → Key Concepts → Application → Examples.
3. Use fill-in templates exactly as specified in Application.
4. Self-score against Quality Rubric (target: 8+/10).
5. Flag Common Pitfalls proactively.
6. Suggest Related Skills from the References section when appropriate.

For Interactive skills: complete all clarifying questions before generating.
For Workflow skills: announce each phase transition explicitly.
```

### Best Practices

1. **One skill at a time** for best output quality
2. **Provide context** — your product, market, team size, constraints
3. **Request scoring** — always ask Codex to evaluate against the rubric
4. **Iterate** — if quality score is below 8, ask Codex to improve the weakest dimension
5. **Save outputs** — Codex local workspace can write generated artifacts to files

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Codex doesn't find skill files | Make sure you're in the repo root directory |
| Output doesn't follow skill format | Add the system prompt above to your configuration |
| GitHub connection not available | Use local workspace mode instead |
| Quality rubric not applied | Explicitly ask: "Score this against the quality rubric" |
| Multi-skill chain breaks | Complete each skill fully before transitioning to the next |

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="../CATALOG.md"><strong>📖 Browse Skills →</strong></a>
</p>
