# Template: Product Sync / Cross-Functional Meeting Notes

> **Format flexibility:** This is one way to structure recurring product meetings. You can also just dump raw notes and ask an agent to restructure them into this format afterward.

---

## Metadata

```
[meeting name] — [date, time]

attendees: [names and roles]
context: [recurring cadence, purpose]
```

---

## Structure Per Topic

Repeat this block for each agenda item discussed:

```markdown
=== [TOPIC NAME] ===

CONTEXT:
- [Why this is being discussed / current state / key data]

DISCUSSION:
- [Key points, perspectives, data shared]
- [Name]: "[notable quote or position]"
- [Name]: "[counterpoint or concern]"

CONCERNS:
- [Name]: [concern raised]
- [Name]: [concern raised]

DECISIONS:
✓ [Decision made — approved / rejected / direction chosen]
⏸ [Decision deferred — reason, who owns next step]

OPEN QUESTIONS:
1. [Unresolved question]
2. [Unresolved question]

ACTION ITEMS:
- [Owner]: [task] by [deadline]
- [Owner]: [task] by [deadline]
```

---

## Closing Sections

Add these at the end of the notes:

```markdown
=== PARKING LOT ===
- [Topics that came up but weren't the focus — capture for later]

=== NEXT MEETINGS ===
- [date]: [meeting name / purpose]
- [date]: [meeting name / purpose]
```

---

## Multi-Meeting Day Summary

If you had multiple meetings in a single day, add a consolidated summary at the end:

```markdown
## Executive Summary

### Key Decisions & Outcomes

**Meeting 1: [Name] ([Key Attendees])**
- [Decision / outcome 1]
- [Decision / outcome 2]

**Meeting 2: [Name] ([Key Attendees])**
- [Decision / outcome 1]
- [Decision / outcome 2]

### Consolidated Action Items

| Owner | Action | Deadline |
|-------|--------|----------|
| [Name] | [Task] | [Date] |
| [Name] | [Task] | [Date] |

### Emerging Priorities
1. [Priority 1 — status / implication]
2. [Priority 2 — status / implication]

### Next Steps
- [What needs to happen next]
```

---

## Using AI to Process Product Sync Notes

### Restructure raw notes into this format

```
Clean up @product-sync-raw.md into structured product sync notes.
For each topic discussed, include: context, key discussion points,
concerns raised (with who raised them), decisions made, open questions,
and action items with owners and deadlines.
```

### Generate executive summary from detailed notes

```
Create an executive summary from @product-sync-notes.md. Include:
key decisions and outcomes (grouped by topic), consolidated action items
table, emerging priorities, and next steps. Keep it to one page.
```

### Compare this week vs last week

```
Compare @product-sync-week-12.md and @product-sync-week-13.md.
What decisions from last week were revisited? Which action items
carried over? What new topics emerged? Flag any shifting priorities.
```

### Extract prioritization decisions

```
From @product-sync-notes.md, extract the prioritization discussion.
Present as a table: Initiative, Effort Estimate, Team Impact,
OKR Alignment, Decision (Q1/Q2/Deferred), and Rationale.
```
