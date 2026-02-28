---
name: launch-checklist
description: Create a comprehensive product launch checklist covering GTM, technical readiness, marketing, sales enablement, support, and measurement — ensuring nothing falls through the cracks.
type: component
domain: launch
difficulty: intermediate
estimated_time: "30-45 min"
prerequisites: ["prd-template"]
outputs: ["launch-checklist"]
triggers:
  - "Create a launch checklist"
  - "What do we need before launch"
  - "Product launch readiness"
  - "Go/no-go checklist"
---

## Purpose

Ensure launch readiness across **all functions** — product, engineering, marketing, sales, support, and leadership — with a comprehensive checklist that prevents the "we forgot to..." moment.

---

## Application

### Launch Checklist Template

```markdown
# Launch Checklist: [Product/Feature Name]
**Target Launch Date:** [Date]
**Launch Type:** [🔵 Internal | 🟡 Beta | 🟢 GA | 🔴 Major]
**Launch Owner:** [PM Name]

---

## T-4 Weeks: Preparation

### Product & Engineering
- [ ] All P0 features complete and merged
- [ ] Feature flag configured for progressive rollout
- [ ] Performance benchmarks met
- [ ] Security review completed
- [ ] Accessibility audit passed
- [ ] Error handling and edge cases covered
- [ ] Rollback plan documented and tested

### Design
- [ ] Final designs approved and implemented
- [ ] UI copy finalized and reviewed
- [ ] Empty/error/loading states designed
- [ ] Responsive behavior verified

---

## T-2 Weeks: Enablement

### Marketing
- [ ] Messaging and positioning finalized
- [ ] Blog post / announcement drafted
- [ ] Email campaign prepared (existing users)
- [ ] Social media posts scheduled
- [ ] Landing page / feature page updated
- [ ] Product screenshots / demo video created

### Sales Enablement
- [ ] Sales team briefed on new feature
- [ ] Battle card updated (if competitive)
- [ ] Demo script updated
- [ ] FAQ document created
- [ ] Pricing changes communicated (if any)

### Customer Support
- [ ] Support team trained on new feature
- [ ] Help center articles written
- [ ] Known issues documented
- [ ] Escalation path defined
- [ ] Canned responses prepared

---

## T-1 Week: Final Checks

### Technical Readiness
- [ ] Load testing completed
- [ ] Monitoring dashboards configured
- [ ] Alerting thresholds set
- [ ] On-call rotation confirmed for launch week
- [ ] Database migrations rehearsed

### Stakeholder Readiness
- [ ] Executive briefing completed
- [ ] Legal review completed (if needed)
- [ ] Compliance approval (if needed)
- [ ] Partner notifications sent (if applicable)

---

## Launch Day

### Go/No-Go Decision
- [ ] All T-4, T-2, T-1 items completed
- [ ] Go/no-go meeting held with key stakeholders
- [ ] Decision: 🟢 GO / 🔴 NO-GO

### Execution
- [ ] Feature flag enabled (progressive %)
- [ ] Announcement published
- [ ] Team monitoring dashboards
- [ ] War room / Slack channel active for rapid response

---

## T+1 Week: Post-Launch

### Monitoring
- [ ] Key metrics tracked (adoption, errors, support load)
- [ ] User feedback collected and triaged
- [ ] Hot-fix process ready for critical issues

### Communication
- [ ] Internal retro scheduled (T+2 weeks)
- [ ] Customer feedback summary shared
- [ ] Success metrics reported to stakeholders
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Coverage** | Eng only | Eng + marketing | All functions (eng, marketing, sales, support) |
| **Timeline** | No timeline | Launch day only | T-4 through T+1 |
| **Rollback** | No plan | "We'll fix it" | Documented + tested rollback |
| **Measurement** | No metrics | Metrics listed | Dashboards configured pre-launch |

---

## References

### Related Skills
- `skills/launch/gtm-strategy/SKILL.md` — Marketing strategy for launch
- `skills/execution/release-notes/SKILL.md` — Announcement content
- `skills/launch/pricing-packaging-advisor/SKILL.md` — Pricing decisions

---

**Skill type:** Component
**Domain:** Launch & GTM
