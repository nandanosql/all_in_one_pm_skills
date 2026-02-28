# 📖 Glossary

> PM terminology and PM Skills system-specific terms.

---

## System Terms

| Term | Definition |
|------|-----------|
| **Skill** | A single `SKILL.md` file containing a structured PM framework with templates, rubrics, and examples. The atomic unit of the PM Skills system. |
| **Component Skill** (🧱) | A skill that generates a single artifact (PRD, user story, roadmap). No interactive questioning — just fill-in templates with quality checks. |
| **Interactive Skill** (🔄) | A skill that asks clarifying questions first, then adapts its output to your context. Multi-turn conversation with the AI. |
| **Workflow Skill** (🎭) | A skill that orchestrates multiple component and interactive skills across phases. A full end-to-end process. |
| **Domain** | One of 10 PM lifecycle categories (Discovery, Strategy, Planning, Specification, Execution, Launch, Growth, Analytics, Communication, Leadership). |
| **Frontmatter** | YAML metadata at the top of a `SKILL.md` file (between `---` delimiters). Contains name, type, domain, difficulty, triggers, etc. |
| **Triggers** | Natural language phrases in the frontmatter that should activate a skill (e.g., "Help me write a PRD"). |
| **Quality Rubric** | A 5-dimension scoring system (0-2 per dimension, target: 8+/10) that the AI uses to self-evaluate its output. |
| **Pitfall** | A named failure mode documented in a skill file with symptom, consequence, and fix. |
| **Skill Chain** | Running multiple skills in sequence where the output of one feeds into the next. |
| **Catalog** | The `CATALOG.md` file listing all 103 skills organized by domain. |

---

## PM Terminology

### Strategy & Vision

| Term | Definition |
|------|-----------|
| **OKR** | Objectives and Key Results — a goal-setting framework. Objectives are qualitative goals; Key Results are measurable outcomes. |
| **North Star Metric (NSM)** | The single metric that best captures the core value your product delivers to customers. |
| **Positioning** | How your product is perceived relative to competitors in the minds of your target customers. |
| **SWOT** | Strengths, Weaknesses, Opportunities, Threats — a strategic assessment framework. |
| **TOWS** | Strategic actions derived from SWOT — matching Strengths with Opportunities, addressing Weaknesses with Threats, etc. |
| **PESTEL** | Political, Economic, Social, Technological, Environmental, Legal — macro-environment analysis. |
| **Business Model Canvas** | Osterwalder's 9-block visual framework for describing how a business creates, delivers, and captures value. |
| **Working Backwards** | Amazon's approach of writing the press release before building the product. |

### Discovery & Research

| Term | Definition |
|------|-----------|
| **JTBD (Jobs-to-Be-Done)** | Framework for understanding customer motivation: what "job" is the customer "hiring" your product to do? |
| **Four Forces of Progress** | Push (current pain), Pull (new solution appeal), Anxiety (fear of change), Habit (inertia) — the forces that drive or resist product adoption. |
| **Proto-Persona** | A hypothesis-driven user archetype created from assumptions (not research). Includes confidence levels for validation. |
| **Mom Test** | Interview methodology that prevents asking leading questions. Named after the idea that even your mom will tell you the truth if you ask the right questions. |
| **5W1H** | Who, What, Where, When, Why, How — a structured problem framing approach. |
| **Battle Card** | A concise competitive reference document designed for sales teams with objection handling. |

### Planning & Prioritization

| Term | Definition |
|------|-----------|
| **RICE** | Reach, Impact, Confidence, Effort — a scoring framework for prioritizing features. |
| **ICE** | Impact, Confidence, Ease — a simpler 3-factor prioritization framework. |
| **Kano Model** | Classifies features as Must-be, Performance, Attractive, Indifferent, or Reverse quality. |
| **MoSCoW** | Must have, Should have, Could have, Won't have — a prioritization categorization method. |
| **WSJF** | Weighted Shortest Job First — SAFe's prioritization method based on cost of delay. |
| **Story Map** | Jeff Patton's method for organizing user stories along a user journey narrative (backbone + walking skeleton). |
| **Now-Next-Later** | A roadmap format organized by time horizons with decreasing confidence, not fixed dates. |
| **Epic** | A large body of work that can be broken down into smaller user stories. |
| **ADR** | Architectural Decision Record — a document template for recording technical decisions. |

### Specification & Design

| Term | Definition |
|------|-----------|
| **PRD** | Product Requirements Document — the detailed specification of what to build and why. |
| **User Story** | A short description of a feature from the user's perspective: "As a [user], I want [goal] so that [benefit]." |
| **Acceptance Criteria** | Testable conditions that must be met for a story to be considered "done." Often written in Gherkin format. |
| **Gherkin** | Given/When/Then syntax for writing acceptance criteria and BDD test scenarios. |
| **Lean UX Canvas** | A canvas combining business problem, assumptions, hypotheses, and experiments. |
| **OST** | Opportunity Solution Tree (Teresa Torres) — a visual framework mapping outcomes to opportunities to solutions to experiments. |
| **Three Amigos** | A session where PM, developer, and QA review a story together before development. |

### Execution & Delivery

| Term | Definition |
|------|-----------|
| **Sprint** | A fixed time-box (usually 1-2 weeks) during which a set of work is completed. |
| **Definition of Done (DoD)** | The checklist of criteria that every increment must satisfy before being released. |
| **Standup** | A brief daily meeting where team members share progress, plans, and blockers. |
| **Retrospective** | A team reflection meeting at the end of a sprint to identify improvements. |
| **Tech Debt** | Code or architecture shortcuts that create future maintenance burden. |
| **Velocity** | The amount of work a team completes per sprint, typically measured in story points. |

### Growth & Analytics

| Term | Definition |
|------|-----------|
| **PMF** | Product-Market Fit — the point where your product satisfies strong market demand. |
| **AARRR** | Pirate Metrics — Acquisition, Activation, Retention, Revenue, Referral — a growth funnel framework. |
| **A/B Test** | A randomized experiment comparing two variants to determine which performs better. |
| **Cohort Analysis** | Analyzing user behavior by grouping users by a shared characteristic (e.g., signup month). |
| **CAC** | Customer Acquisition Cost — the total cost to acquire a new customer. |
| **LTV** | Lifetime Value — the total revenue expected from a customer over their relationship with you. |
| **NRR** | Net Revenue Retention — measures revenue retained from existing customers including expansion and contraction. |
| **MRR Waterfall** | Monthly Recurring Revenue broken down by: new, expansion, contraction, and churn. |
| **Churn** | The rate at which customers stop using your product. |
| **Activation** | The moment a new user reaches "first value" — the aha moment. |

### Communication & Leadership

| Term | Definition |
|------|-----------|
| **RACI** | Responsible, Accountable, Consulted, Informed — a matrix for clarifying roles. |
| **BATNA** | Best Alternative To a Negotiated Agreement — your fallback position in a negotiation. |
| **Stakeholder Map** | A visual classification of stakeholders by influence and interest to determine engagement strategy. |
| **Blameless Postmortem** | An incident review focused on learning and prevention rather than assigning blame. |
| **5 Whys** | A root cause analysis technique: ask "why" five times to dig past symptoms to the fundamental cause. |
| **Influence Without Authority** | Techniques for driving outcomes when you don't have direct power over the people involved. |

---

<p align="center">
  <a href="README.md"><strong>📚 Back to Docs →</strong></a>
</p>
