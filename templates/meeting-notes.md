# Template: Meeting Notes

> **Format flexibility:** You do NOT need to follow this structure during the meeting. Jot notes however feels natural — messy bullets, stream-of-consciousness, abbreviations, incomplete sentences. AI agents are excellent at restructuring raw notes after the fact. The templates below show both the **raw capture** format (use during the meeting) and the **structured output** format (let the agent generate this).

---

## Part A: Raw Capture Template (Use During the Meeting)

Copy this into a new file and type freely. Don't worry about formatting.

```markdown
[meeting name] - [date, time]

attendees: [names and roles]
context: [what this meeting is about]

---

[just type as the meeting goes. bullets, fragments, whatever.]

- [topic discussed]
  - [what was said]
  - [who said it, if relevant]
  - [decisions, if any]

- [next topic]
  - [notes]

---

ACTION ITEMS:
- [owner]: [task] [deadline if mentioned]
- [owner]: [task]

OPEN QUESTIONS:
- [question that wasn't resolved]

DECISIONS:
- [what was decided]

PARKING LOT:
- [stuff that came up but wasn't the focus]
```

---

## Part B: Structured Output Template (Agent-Generated)

After the meeting, ask the agent to restructure your raw notes into this format.

```markdown
# [Meeting Name] — [Date]

**Attendees:** [Names and roles]
**Duration:** [Time]
**Purpose:** [One-line context]

---

## Key Decisions & Outcomes

**[Topic 1]**
- [Decision or outcome]
- [Supporting context]

**[Topic 2]**
- [Decision or outcome]
- [Supporting context]

---

## Discussion Summary

### [Topic 1 Name]
- [Key points discussed]
- [Different perspectives raised]
- [Data or evidence cited]

### [Topic 2 Name]
- [Key points discussed]

---

## Action Items

| Owner | Action | Due |
|-------|--------|-----|
| [Name] | [Task] | [Date] |
| [Name] | [Task] | [Date] |

---

## Open Questions
- [Unresolved question 1]
- [Unresolved question 2]

---

## Next Steps
- [What happens next]
- [Next meeting date, if set]
```

---

## Using AI to Process Meeting Notes

### Restructure raw notes

```
Clean up @meeting-notes-raw.md into a structured format with:
executive summary, key decisions, discussion summary by topic,
action items table (owner, task, due date), and open questions.
Keep it concise but don't lose important details.
```

### Generate a follow-up email

```
Using @communication-styles.md, write a follow-up email summarizing
@meeting-notes-raw.md. Use the executive email format: context,
key decisions, action items table, next steps. Keep it under 300 words.
```

### Extract action items only

```
Extract all action items from @meeting-notes-raw.md. Present as a table
with Owner, Action, Due Date, and Priority columns. Flag any items
that don't have a clear owner or deadline.
```

### Synthesize multiple meetings

```
I have notes from 3 meetings this week: @monday-sync.md, @wednesday-review.md,
@friday-retro.md. Create a single weekly summary with: decisions made,
action items (consolidated, deduplicated), open questions, and themes
across meetings.
```

### Identify missed follow-ups

```
Compare @last-week-notes.md action items with @this-week-notes.md.
Which action items from last week were completed? Which are still open?
Flag any that seem dropped.
```
