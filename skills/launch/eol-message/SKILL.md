---
name: eol-message
description: Craft end-of-life communications for products and features being sunset — covering user notification, migration plans, timelines, and empathy-driven messaging.
type: component
domain: launch
difficulty: intermediate
estimated_time: "15-25 min"
prerequisites: ["stakeholder-map"]
outputs: ["eol-communication"]
triggers:
  - "Sunset a product"
  - "End of life communication"
  - "Deprecate a feature"
  - "How to communicate sunsetting"
---

## Purpose

Craft end-of-life communications that are **empathetic, clear, and actionable** — giving affected users adequate notice, migration options, and support while protecting the brand.

---

## Application

### EOL Communication Template

```markdown
# End-of-Life Plan: [Product/Feature Name]

**Decision Date:** [Date decided]
**Announcement Date:** [Date of first notification]
**Sunset Date:** [Date of final removal]
**Owner:** [PM Name]

---

## 1. What's Being Sunset
- [Product/feature name and description]
- [What it does for users today]
- [Current usage: # active users, # accounts affected]

## 2. Why
[Honest, empathetic explanation — e.g., "We've learned that X better serves..."]
- Don't say: "We're killing this because nobody uses it"
- Do say: "We're focusing our resources on [alternative] which better serves..."

## 3. Timeline
| Date | Milestone |
|------|----------|
| [Date] | First announcement (email + in-app) |
| [Date] | Reminder notification (30 days out) |
| [Date] | Final reminder (7 days out) |
| [Date] | Feature/product removed |
| [Date] | Data export deadline |

## 4. Migration Path
**Recommended alternative:** [What users should move to]
**Migration guide:** [Step-by-step instructions or link]
**Data export:** [How users can export their data + deadline]
**Support:** [Where to get help during transition]

## 5. Communication Plan
| Audience | Channel | Message | Owner |
|----------|---------|---------|-------|
| Active users | Email + in-app | Full announcement | [Name] |
| Enterprise accounts | Personal outreach | Tailored migration | [Name] |
| Partners/integrators | Email | API deprecation timeline | [Name] |
| Internal team | Slack + meeting | Context + FAQ | [Name] |
| Public | Blog/changelog | Public notice | [Name] |

## 6. FAQ
**Q: Why are you removing this?**
A: [Honest answer]

**Q: What should I use instead?**
A: [Alternative + how it compares]

**Q: What happens to my data?**
A: [Data export options + timeline]

**Q: Can I keep using it after [date]?**
A: [Clear answer — usually "no" with empathy]
```

### EOL Email Template

```markdown
Subject: Important update about [Product/Feature Name]

Hi [Name],

We wanted to give you advance notice that [Product/Feature] will be 
retired on [Date].

**What this means for you:**
[1-2 sentences about impact]

**What we recommend:**
[Migration option with link to guide]

**Your data:**
[Data export instructions + deadline]

**Need help?**
[Support link/email]

We know change is never easy, and we're committed to making this 
transition as smooth as possible.

[PM Name]
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Empathy** | Cold announcement | Acknowledges inconvenience | Genuinely empathetic + explains why |
| **Timeline** | No advance notice | Some notice | 60+ day notice with milestones |
| **Migration** | "Figure it out" | Alternative mentioned | Step-by-step guide + support |
| **Data** | Data lost | Export available | Export + adequate deadline |

---

## References

### Related Skills
- `skills/communication/stakeholder-map/SKILL.md` — Identify affected stakeholders
- `skills/launch/feature-announcement/SKILL.md` — Announcement format
- `skills/execution/release-notes/SKILL.md` — Changelog entry

---

**Skill type:** Component
**Domain:** Launch & GTM
