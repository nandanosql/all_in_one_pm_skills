---
name: launch-process
description: Orchestrate the complete product launch process — from T-6 weeks through launch day to T+2 weeks post-launch — coordinating product, engineering, marketing, sales, and support.
type: workflow
domain: launch
difficulty: advanced
estimated_time: "6-8 weeks"
prerequisites: ["prd-template"]
outputs: ["launched-product"]
triggers:
  - "Take me through the launch process"
  - "Full launch workflow"
  - "End-to-end launch planning"
---

## Purpose

Orchestrate the **complete product launch process** from early preparation through launch day to post-launch monitoring — ensuring all functions are aligned and nothing falls through the cracks.

---

## Application

### Phase 1: Pre-Launch Planning (T-6 to T-4 weeks)

| Activity | Skill | Owner |
|----------|-------|-------|
| Finalize PRD & scope | `skills/specification/prd-template/SKILL.md` | PM |
| Build GTM strategy | `skills/launch/gtm-strategy/SKILL.md` | PM + Marketing |
| Design beta program | `skills/launch/beta-program-design/SKILL.md` | PM |
| Set pricing/packaging | `skills/launch/pricing-packaging-advisor/SKILL.md` | PM |
| Map stakeholders | `skills/communication/stakeholder-map/SKILL.md` | PM |

### Phase 2: Build & Enablement (T-4 to T-2 weeks)

| Activity | Skill | Owner |
|----------|-------|-------|
| Complete development | `skills/execution/agile-delivery-process/SKILL.md` | Eng |
| Create launch checklist | `skills/launch/launch-checklist/SKILL.md` | PM |
| Draft feature announcements | `skills/launch/feature-announcement/SKILL.md` | Marketing |
| Write release notes | `skills/execution/release-notes/SKILL.md` | PM |
| Train sales & support | [Sales enablement] | PM + Sales |

### Phase 3: Beta (T-2 to T-1 week)

| Activity | Skill | Owner |
|----------|-------|-------|
| Run beta program | `skills/launch/beta-program-design/SKILL.md` | PM |
| Collect feedback | `skills/discovery/survey-design/SKILL.md` | PM |
| Iterate on issues | `skills/execution/blocker-resolution-advisor/SKILL.md` | Eng |
| Go/no-go decision | `skills/launch/launch-checklist/SKILL.md` | PM + Leadership |

### Phase 4: Launch Day (T-0)

| Activity | Owner |
|----------|-------|
| Enable feature flag (progressive rollout) | Eng |
| Publish announcements (email, blog, in-app) | Marketing |
| Monitor dashboards | Eng + PM |
| War room / rapid response channel | All |

### Phase 5: Post-Launch (T+1 to T+2 weeks)

| Activity | Skill | Owner |
|----------|-------|-------|
| Monitor key metrics | `skills/analytics/metrics-dashboard-design/SKILL.md` | PM |
| Collect user feedback | `skills/discovery/survey-design/SKILL.md` | PM |
| Send stakeholder update | `skills/execution/stakeholder-update/SKILL.md` | PM |
| Run launch retro | `skills/execution/retrospective-facilitator/SKILL.md` | PM |
| Plan iteration | `skills/planning/now-next-later-roadmap/SKILL.md` | PM |

---

## References

### Skills Orchestrated
All skills in Domain 6 (Launch & GTM) plus supporting skills from other domains.

---

**Skill type:** Workflow
**Domain:** Launch & GTM
