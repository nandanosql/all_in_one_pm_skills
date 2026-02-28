---
name: discovery-interview-prep
description: Plan and structure customer discovery interviews using Mom Test principles. Creates interview guides that uncover real behavior and pain, not hypothetical preferences.
type: interactive
domain: discovery
difficulty: intermediate
estimated_time: "20-30 min"
prerequisites: ["problem-statement"]
outputs: ["interview-guide"]
triggers:
  - "Help me prepare for customer interviews"
  - "I need to talk to users"
  - "Plan discovery interviews"
  - "How do I run a customer interview"
---

## Purpose

Plan and structure customer discovery interviews that reveal real behavior, not hypothetical preferences. Uses **Mom Test** principles to design questions that even your mom couldn't lie to you about — focusing on past behavior, specific situations, and verifiable facts.

---

## Key Concepts

### The Mom Test (Rob Fitzpatrick)

Three rules for useful questions:
1. **Talk about their life, not your idea** — Ask about their problems, not your solution
2. **Ask about specifics in the past, not hypotheticals** — "Tell me about the last time..." not "Would you..."
3. **Talk less, listen more** — You're here to learn, not pitch

### Question Quality Spectrum

| ❌ Bad (Hypothetical) | ✅ Good (Behavioral) |
|----------------------|---------------------|
| "Would you use X?" | "How do you solve X today?" |
| "Is this a problem?" | "Tell me about the last time X happened." |
| "How much would you pay?" | "What do you currently pay to solve this?" |
| "Do you like X?" | "How often do you use X?" |

### Facilitation Protocol

This interactive skill asks **4-5 adaptive questions** to build a customized interview guide:

1. **Research goal** — What are you trying to learn?
2. **User segment** — Who are you interviewing?
3. **Knowledge gaps** — What do you already know vs. assume?
4. **Interview context** — Format and constraints
5. **Hypothesis risks** — What could prove you wrong?

---

## Application

### Question 1: Research Goal

**Agent asks:** "What's the primary thing you're trying to learn from these interviews?"

**Options:**
1. **Validate a problem** — "I think users have problem X, need to confirm"
2. **Understand workflow** — "I want to see how users currently do task Y"
3. **Evaluate solution fit** — "I have a solution concept and want reactions"
4. **Discover unknowns** — "I don't know enough about the user's world yet"
5. **Other** (describe your goal)

---

### Question 2: Who Are You Interviewing?

**Agent asks:** "Who is your target interviewee?"

**Options:**
1. **Existing users** — Active users of your product
2. **Churned users** — People who stopped using your product
3. **Prospects** — People in your target market who don't use you yet
4. **Internal stakeholders** — Sales, support, engineering who interact with users
5. **Other** (describe)

---

### Question 3: What Do You Already Know?

**Agent asks:** "What do you believe is true about this topic? Be honest about what's assumption vs. evidence."

**User provides:** Free-text response about their current understanding and confidence level.

---

### Question 4: Interview Setup

**Agent asks:** "What's your interview context?"

**Options:**
1. **Remote (30 min)** — Video call, time-constrained
2. **Remote (60 min)** — Video call, full session
3. **In-person** — On-site or contextual inquiry
4. **Intercept** — Brief in-app or event-based
5. **Other** (describe)

---

### Output: Interview Guide

After collecting answers, generate:

```markdown
# Discovery Interview Guide

**Research goal:** [From Q1]
**Target:** [From Q2]
**Format:** [From Q4]
**Date range:** [Suggested]
**Number of interviews:** [Recommended: 5-8 for saturation]

---

## Before the Interview
- [ ] Review what you already know (avoid re-asking confirmed facts)
- [ ] Prepare recording setup (with permission)
- [ ] Send calendar invite with zero product context (avoid priming)

---

## Interview Script

### Opening (2-3 min)
"Thanks for your time. I'm trying to understand [general area].
There are no wrong answers — I'm learning from your experience.
Is it okay if I record this for notes?"

### Context Questions (5-10 min)
1. "Tell me about your role and what a typical day/week looks like."
2. "What tools do you use most for [relevant workflow area]?"
3. "[Context question specific to research goal]"

### Core Questions (15-30 min)
4. "Tell me about the last time you [behavior related to problem]."
   - Follow-up: "Walk me through exactly what happened."
   - Follow-up: "What was the hardest part?"
   - Follow-up: "How did you solve it?"

5. "[Behavioral question about frequency/severity]"
   - "How often does that happen?"
   - "What does it cost you? (Time, money, frustration)"

6. "[Question targeting the biggest assumption to validate]"

7. "[Question about current alternatives/workarounds]"
   - "What have you tried?"
   - "Why did/didn't that work?"

### Wrap-up (5 min)
8. "If you had a magic wand, what would you change about [process]?"
9. "Is there anything I didn't ask that I should have?"
10. "Can you introduce me to anyone else who deals with this?"

---

## After the Interview
- [ ] Write key quotes within 1 hour (memory fades fast)
- [ ] Tag insights: [Confirmed], [New], [Contradicts assumption]
- [ ] Update proto-persona if behavior pattern was unexpected
- [ ] Log in interview tracking sheet

---

## Analysis Template
| Interviewee | Key Quote | Insight | Confirmed/New/Contradicts |
|-------------|-----------|---------|--------------------------|
| [Name] | "[Quote]" | [Insight] | [Tag] |
```

---

## Quality Rubric

| Dimension | 0 (Missing) | 1 (Partial) | 2 (Excellent) |
|-----------|-------------|-------------|----------------|
| **Question Type** | All hypothetical | Mix of good/bad | All behavioral (Mom Test) |
| **Research Focus** | No clear goal | Broad objective | Specific hypothesis to test |
| **Follow-ups** | None planned | Generic | Contextual probes per question |
| **Analysis Plan** | None | "We'll see what comes up" | Pre-tagged insight categories |
| **Practical** | Academic exercise | Somewhat actionable | Ready-to-use script |

---

## Common Pitfalls

### Pitfall 1: Pitching Instead of Listening

**Symptom:** Interviewer describes their solution and asks "What do you think?"

**Fix:** Ban the word "we" from the interview. Talk about *their* life, not your product.

### Pitfall 2: Asking "Would You..."

**Symptom:** "Would you use a tool that does X?"

**Fix:** People are terrible at predicting their own behavior. Ask about the past: "Tell me about the last time you needed to do X."

### Pitfall 3: Not Recording Key Quotes

**Symptom:** After 5 interviews, notes say "They want better analytics."

**Fix:** Capture exact quotes immediately. "I spend Monday mornings doing data janitor work" is 10x more valuable than your summary.

---

## References

### Related Skills
- `skills/discovery/problem-statement/SKILL.md` — Interviews validate problem statements
- `skills/discovery/proto-persona/SKILL.md` — Interview findings refine personas
- `skills/discovery/survey-design/SKILL.md` — Follow up interviews with quantitative surveys

### External Frameworks
- Rob Fitzpatrick, *The Mom Test* (2013)
- Erika Hall, *Just Enough Research* (2013)
- Teresa Torres, *Continuous Discovery Habits* (2021)

---

**Skill type:** Interactive
**Domain:** Discovery & Research
