# 🔗 Skill Chaining & Workflows

> How the three-tier system composes skills into powerful multi-step processes.

---

## The Three-Tier Architecture

PM Skills uses a layered system where higher-tier skills orchestrate lower-tier ones:

```
╔═══════════════════════════════════════════════════════════════╗
║  🎭 WORKFLOW SKILLS (7)                                      ║
║  End-to-end processes that orchestrate multiple skills        ║
║  across phases. Think of these as "playbooks."               ║
╠═══════════════════════════════════════════════════════════════╣
║  🔄 INTERACTIVE SKILLS (32)              ↑ orchestrates      ║
║  Guided multi-turn sessions. The AI asks questions first,    ║
║  adapts to your context, then generates output.              ║
╠═══════════════════════════════════════════════════════════════╣
║  🧱 COMPONENT SKILLS (62)               ↑ uses              ║
║  Single-artifact generators with templates and rubrics.      ║
║  The building blocks of everything above.                    ║
╚═══════════════════════════════════════════════════════════════╝
```

---

## How Skills Connect

### Component → Interactive

Interactive skills **use** components as building blocks. For example:

```
🔄 Prioritization Advisor (Interactive)
├── recommends → 🧱 RICE scoring template
├── recommends → 🧱 Kano model template  
├── recommends → 🧱 MoSCoW template
└── generates  → prioritized backlog using the chosen framework
```

The advisor asks about your context, selects the right framework, then fills in the component template for you.

### Interactive → Workflow

Workflow skills **orchestrate** multiple interactive and component skills across phases:

```
🎭 Discovery Process (Workflow)
├── Phase 1: Problem Framing
│   ├── 🧱 Problem Statement
│   └── 🔄 Problem Framing Canvas
├── Phase 2: User Research
│   ├── 🧱 Proto-Persona
│   ├── 🧱 Jobs-to-Be-Done
│   └── 🔄 Discovery Interview Prep
├── Phase 3: Journey Mapping
│   ├── 🧱 Customer Journey Map
│   └── 🔄 Customer Journey Mapping Workshop
└── Phase 4: Synthesis
    ├── 🔄 Win-Loss Analysis
    └── output: Discovery Report
```

---

## Manual Skill Chaining

You don't need a Workflow skill to chain skills together. You can compose any skills manually.

### Basic Chain (Sequential)

Tell your AI to run skills in sequence:

```
I want to go from problem to PRD. Please run these skills in order:

1. skills/discovery/problem-statement/SKILL.md — Define the problem
2. skills/discovery/jobs-to-be-done/SKILL.md — Map the user's JTBD
3. skills/specification/prd-development/SKILL.md — Write the PRD

Complete each skill fully before moving to the next.
Use the output of each skill as input for the next.
```

### Branching Chain (Decision-Based)

Some chains depend on intermediate results:

```
Start with skills/planning/prioritization-advisor/SKILL.md

If the advisor recommends RICE → 
  generate a RICE scorecard for my 15 backlog items

If the advisor recommends Kano → 
  run a Kano survey design using skills/discovery/survey-design/SKILL.md

Either way, finish with skills/planning/now-next-later-roadmap/SKILL.md 
to create the roadmap from the prioritized output.
```

### Parallel Chain (Multiple Artifacts)

Generate multiple artifacts simultaneously:

```
For our new search feature, generate these artifacts in parallel:

1. skills/specification/user-story/SKILL.md → 5 user stories
2. skills/specification/acceptance-criteria-guide/SKILL.md → AC for each
3. skills/specification/design-brief/SKILL.md → design handoff brief

Ensure all three artifacts reference the same feature scope.
```

---

## Common Skill Chains (Recipes)

### 🔍 Discovery → Strategy

```
1. problem-statement → Define what's broken
2. proto-persona → Define who's affected
3. jobs-to-be-done → Understand what they're trying to do
4. positioning-statement → Position your solution
5. north-star-metric → Set your success metric
```

### 📋 Strategy → Planning

```
1. okr-framework → Set quarterly OKRs
2. user-story-mapping → Map the user's journey
3. prioritization-advisor → Prioritize the backlog
4. now-next-later-roadmap → Create the roadmap
5. epic-hypothesis → Define testable epics
```

### 📝 Planning → Specification

```
1. epic-breakdown-advisor → Split epics into stories
2. user-story → Write detailed user stories
3. acceptance-criteria-guide → Add Given/When/Then criteria
4. prd-development → Assemble the full PRD
5. technical-spec → Bridge to engineering
```

### 🚀 Specification → Launch

```
1. definition-of-done → Set quality gates
2. sprint-planning-facilitator → Plan the sprint
3. launch-checklist → Build launch readiness
4. gtm-strategy → Plan go-to-market
5. feature-announcement → Announce to users
```

### 📈 Launch → Growth

```
1. pol-probe → Measure product-market fit
2. activation-optimization → Optimize onboarding
3. ab-test-design → Design experiments
4. retention-deep-dive → Analyze retention
5. growth-model → Build a quantitative model
```

---

## Using the 7 Workflow Skills

Workflow skills are pre-built chains that handle orchestration automatically.

| Workflow | Domain | What It Orchestrates |
|----------|--------|---------------------|
| `discovery-process` | Discovery | 3-4 week discovery cycle (problem → persona → JTBD → research → synthesis) |
| `product-strategy-session` | Strategy | Full strategy across 6 phases (research → position → vision → OKRs → model → roadmap) |
| `roadmap-planning` | Planning | End-to-end roadmap (goals → priorities → dependencies → timeline → communication) |
| `prd-development` | Specification | PRD from research to approval (context → sections → review → iterate) |
| `agile-delivery-process` | Execution | Full sprint cadence with quality gates (plan → execute → review → retro) |
| `launch-process` | Launch | T-6 to T+2 launch (planning → readiness → go/no-go → launch → retro) |
| `executive-onboarding-playbook` | Leadership | 90-day onboarding (listen → diagnose → act) |

### How to Use a Workflow

```
Run skills/discovery/discovery-process/SKILL.md for our new 
enterprise admin panel. I have 3 weeks for discovery.

Context:
- Product: B2B SaaS project management tool
- Problem area: Enterprise customers need better admin controls
- Available resources: Access to 5 enterprise customers for interviews
```

The workflow will:
1. **Announce each phase** before starting
2. **Pull in sub-skills** as needed
3. **Generate phase deliverables** at each step
4. **Hand output forward** as input to the next phase
5. **Produce a final synthesis** at the end

---

## Tips for Effective Chaining

1. **Start small** — chain 2-3 skills before attempting 5+
2. **Provide context once** — the AI carries context between skills in the same session
3. **Review between steps** — don't autopilot through a 5-skill chain without checking intermediate output
4. **Use explicit handoffs** — say "Now switch to [next skill]" to make transitions clear
5. **Save intermediate artifacts** — if a session crashes, you don't lose earlier work

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a> ·
  <a href="../CATALOG.md"><strong>📖 Browse Skills →</strong></a>
</p>
