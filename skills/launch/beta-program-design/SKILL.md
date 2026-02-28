---
name: beta-program-design
description: Design a beta program that validates product-market fit with early adopters — covering recruitment, success criteria, feedback loops, and graduation to GA.
type: component
domain: launch
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["launch-checklist"]
outputs: ["beta-program-plan"]
triggers:
  - "Design a beta program"
  - "How should we run a beta"
  - "Plan our beta launch"
  - "Beta testing strategy"
---

## Purpose

Design a beta program that validates **product-market fit** with early adopters before GA launch — covering recruitment, success criteria, feedback loops, and graduation criteria.

---

## Application

### Beta Program Template

```markdown
# Beta Program: [Product/Feature Name]

## Overview
- **Type:** [Closed / Open / Internal-only]
- **Duration:** [X weeks]
- **Target size:** [# participants]
- **Launch → GA criteria:** [Conditions for graduation]

## Participant Recruitment
### Ideal Beta User
- [Profile: existing power users / new segment / internal]
- [Selection criteria: company size, use case, engagement level]

### Recruitment Channels
- [ ] In-app opt-in banner
- [ ] Email to qualified users
- [ ] Internal nomination
- [ ] Community/social

## Feedback Loops
| Channel | Frequency | Purpose |
|---------|-----------|---------|
| In-app feedback widget | Continuous | Bug/friction reports |
| Weekly survey (5 questions) | Weekly | Satisfaction tracking |
| 1:1 interviews (5-8 users) | Biweekly | Deep qualitative insights |
| Usage analytics | Continuous | Behavioral data |
| Slack/Discord channel | Continuous | Community feedback |

## Success Criteria (Beta → GA)
| Metric | Target | Current |
|--------|--------|---------|
| Net Promoter Score | > 30 | — |
| Feature adoption rate | > 60% of beta users | — |
| Critical bugs | 0 remaining | — |
| User-reported satisfaction | > 4/5 | — |
| Performance benchmarks | [Target] | — |

## Timeline
| Week | Milestone |
|------|----------|
| 1 | Recruit and onboard beta users |
| 2-3 | Active beta, first feedback cycles |
| 4 | Mid-beta review and iteration |
| 5-6 | Final iteration and polish |
| 7 | Beta graduation decision |
```

---

## Quality Rubric

| Dimension | 0 | 1 | 2 |
|-----------|---|---|---|
| **Recruitment** | Random users | Target profile | Profile + criteria + channel plan |
| **Feedback** | "We'll ask them" | One channel | Multi-channel with cadence |
| **Success criteria** | "It went well" | Some metrics | Quantified thresholds for GA |
| **Action on feedback** | Collected, ignored | Triaged | Rapid iteration loop |

---

## References

### Related Skills
- `skills/launch/launch-checklist/SKILL.md` — Beta is a launch phase
- `skills/launch/gtm-strategy/SKILL.md` — Beta feeds GTM insights
- `skills/discovery/survey-design/SKILL.md` — Design beta surveys

---

**Skill type:** Component
**Domain:** Launch & GTM
