# Template: User Interview Notes

> **Format flexibility:** This is a suggested structure, not a requirement. AI agents can extract insights from any format — bullet points, raw transcripts, voice-memo dumps, Google Doc pastes, or polished notes. Use whatever is fastest for you during the interview. Structure it later (or let the agent do it).

---

## Metadata

| Field | Value |
|-------|-------|
| **Participant** | [Name] |
| **Role** | [Job title] |
| **Company** | [Company name] ([size], [stage/type]) |
| **Product/Plan** | [What they use, how many seats] |
| **Date** | [Date] |
| **Interviewer** | [Your name] |
| **Duration** | [Minutes] |

---

## Background

[1-2 sentences on who this person is, their context, how long they've used the product, and why they were selected for an interview.]

---

## Interview

**Q: [Question about current workflow / how they use the product]**

[Name]: "[Verbatim or paraphrased response]"

**Q: [Question about what's working well]**

[Name]: "[Response]"

**Q: [Question about pain points / frustrations]**

[Name]: "[Response]"

**Q: [Question about specific area of interest — e.g., onboarding, collaboration, a feature]**

[Name]: "[Response]"

**Q: [Question about comparison to alternatives / competitors]**

[Name]: "[Response]"

**Q: [Open-ended — "If you could change one thing..."]**

[Name]: "[Response]"

**Q: [Closing — "Anything else we should know?"]**

[Name]: "[Response]"

---

## Key Insights

- [Insight 1 — e.g., "Speed is the #1 reason they stay"]
- [Insight 2 — e.g., "Onboarding was confusing — had to create their own guide"]
- [Insight 3 — e.g., "Dark mode highly requested by engineering users"]
- [Insight 4]
- [Insight 5]

---

## Suggested Question Bank

Pick 5-8 questions per interview. Adapt to the persona and research goal.

### Discovery / Exploratory
- "Walk me through your typical day using [product]."
- "What were you using before? Why did you switch?"
- "What's working well? What's frustrating?"
- "Tell me about the last time you got stuck."

### Feature-Specific
- "How do you handle [specific workflow]?"
- "What do you wish [feature] could do that it can't today?"
- "If we changed [X], how would that affect your work?"

### Competitive / Alternatives
- "What other tools did you evaluate? Why did you choose us?"
- "Is there anything a competitor does that you wish we had?"

### Onboarding / Activation
- "What was your first experience like?"
- "How long before you felt productive?"
- "Did you need help getting started? From whom?"

### Closing
- "If you could wave a magic wand and change one thing, what would it be?"
- "Is there anything I didn't ask about that you think is important?"
- "Would you be open to a follow-up conversation?"

---

## Using AI to Process Interviews

After the interview, you can ask an agent to help with any of these:

```
Summarize @user-interview-[name].md into key insights, 
organized by theme. Flag any quotes that are especially strong
evidence for or against our current hypotheses.
```

```
I have 6 user interviews in @interviews/. Synthesize them into 
a single findings document. Group by theme, note frequency, 
include the strongest quotes, and flag conflicting viewpoints.
```

```
Review @user-interview-[name].md and identify: 
(1) unmet needs, (2) feature requests, (3) competitive mentions, 
(4) onboarding friction. Present as a table.
```
