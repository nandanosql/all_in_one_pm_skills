# 🤖 Using PM Skills with ChatGPT

> Complete guide for ChatGPT Projects, Custom GPTs, and GitHub Connectors.

---

## Which Method Should I Use?

| Method | Best For | Reusable? |
|--------|----------|-----------|
| **ChatGPT Projects** | Ongoing initiatives with multiple skills | ✅ Yes |
| **Custom GPTs** | Shared PM assistant for your team | ✅ Yes |
| **GitHub Connector** | Always-current skills from the repo | ✅ Yes |
| **Direct paste** | Quick one-off tasks | ❌ No |

---

## Option 1: ChatGPT Projects (Recommended)

Best for project-scoped work where you want files, chats, and instructions grouped together.

### Setup

1. Go to **ChatGPT** → create a new **Project**
2. Name it something like "PM Skills Workspace"
3. Upload skill files:
   - Download desired `SKILL.md` files from the [Catalog](../CATALOG.md)
   - Click **Add files** in the project and upload them
4. Add **Project Instructions**:

```
When solving PM tasks, use the uploaded skill files as the operating standard.
Follow each skill's sections in order: Purpose, Key Concepts, Application, 
Examples, Common Pitfalls, References.

For Interactive skills, ask all clarifying questions before generating output.
For Component skills, generate the complete template and self-score against 
the Quality Rubric (target: 8+/10).

If context is missing, ask up to 3 clarifying questions before drafting.
```

5. Every conversation in this project will automatically use your loaded skills

### Tips

- **Start with 1-3 skills** — too many files can dilute output quality
- **Create domain-specific projects** — e.g., "Discovery Sprint", "Launch Planning"
- **Re-upload skills** when the repo updates for the latest versions

---

## Option 2: Custom GPTs (Team Sharing)

Create a reusable PM assistant that your entire team can use.

### Setup

1. Go to **ChatGPT** → **Explore GPTs** → **Create a GPT**
2. Set the name and description:
   - Name: "PM Skills Assistant"
   - Description: "Product management expert powered by 103 battle-tested skills"
3. Upload skill files as **Knowledge**:
   - Upload the `SKILL.md` files your team uses most
4. Set **Instructions**:

```
You are a senior Product Management assistant powered by PM Skills.

## Core Behavior
1. When a user asks for PM help, identify which uploaded skill file applies.
2. Follow the skill's sections in order: Purpose → Key Concepts → Application.
3. Use the fill-in templates from the Application section.
4. Self-score every output against the Quality Rubric.
5. Proactively flag Common Pitfalls.

## Skill Types
- Component skills: Generate complete artifacts (PRDs, user stories, etc.)
- Interactive skills: Ask clarifying questions first, then guide through the process
- Workflow skills: Run multi-phase processes, announcing each phase

## Quality Standard
- Target 8+/10 on all quality rubrics
- If any dimension scores below 2, suggest improvements before finalizing
```

5. **Publish** the GPT (private, team, or public)

---

## Option 3: GitHub Connector (Always Current)

Connect ChatGPT directly to the PM Skills GitHub repository so it always reads the latest versions.

### Setup

1. In **ChatGPT** → **Settings** → **Apps** (or Connected Apps)
2. Connect **GitHub** and authorize access
3. In any chat, reference skills by path:

```
Use skills/discovery/problem-statement/SKILL.md from 
nandanosql/pm-skills to help me write a problem statement 
for our retention issue.
```

### Limitations

- Availability varies by ChatGPT plan and region
- May not work with private repos without additional configuration
- Best for occasional use; for heavy use, prefer Projects or Custom GPTs

---

## Option 4: Direct Paste (Quickest)

For one-off tasks when you don't need a reusable setup:

1. Open the `SKILL.md` file on GitHub
2. Click **Raw** to see plain text
3. Copy the entire contents
4. Paste into ChatGPT
5. Add your request below:

```
[Pasted SKILL.md contents above]

Using this skill, help me create user stories for our 
new notification preferences feature.
```

---

## Recommended Starter Kits

### 📦 Discovery Kit (3 files)
```
skills/discovery/problem-statement/SKILL.md
skills/discovery/jobs-to-be-done/SKILL.md
skills/discovery/proto-persona/SKILL.md
```

### 📦 Strategy Kit (3 files)
```
skills/strategy/product-vision-statement/SKILL.md
skills/strategy/okr-framework/SKILL.md
skills/strategy/positioning-statement/SKILL.md
```

### 📦 Execution Kit (3 files)
```
skills/specification/user-story/SKILL.md
skills/specification/prd-template/SKILL.md
skills/execution/definition-of-done/SKILL.md
```

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| ChatGPT ignores skill structure | Add the instruction snippet to Project or GPT instructions |
| Output is too short/shallow | Ask: "Follow the full Application section step-by-step" |
| GPT doesn't use uploaded files | Ensure files are in Knowledge (GPTs) or Files (Projects) |
| Quality rubric not applied | Ask: "Score this output against the quality rubric in the skill file" |
| GitHub connector not available | Fall back to file upload or copy-paste |

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="../CATALOG.md"><strong>📖 Browse Skills →</strong></a>
</p>
