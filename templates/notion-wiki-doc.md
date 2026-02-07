# Template: Notion / Wiki Documentation

> **Format flexibility:** This is a generic structure for long-form documentation. Adapt sections to your content — not every doc needs every section. AI agents can restructure raw notes or meeting outputs into this format.

---

## The Format

```markdown
# [Title] — [Date or Quarter]

**Author:** [Name, Role]
**Last Updated:** [Date]
**Status:** [Draft / In Review / Final]

---

## Overview

[2–3 sentence summary. What is this document? Why does it exist?
A reader should know whether to keep reading after this section.]

## Background / Context

[Why this matters. History, previous decisions, what triggered this work.
Link to related docs, prior research, or parent initiatives.]

**Related docs:**
- [Link to related doc 1]
- [Link to related doc 2]

## Key Findings

### [Topic 1]
- [Finding with data]
- [Supporting evidence or quote]

### [Topic 2]
- [Finding with data]
- [Supporting evidence or quote]

### [Topic 3]
- [Finding with data]

## Implications

[What do these findings mean for the roadmap, strategy, or team?]

1. [Implication 1 — with business impact]
2. [Implication 2 — with business impact]
3. [Implication 3 — with business impact]

## Recommendations / Next Steps

[Clear recommendation with rationale.]

- [ ] [Action item] — Owner: [Name], Due: [Date]
- [ ] [Action item] — Owner: [Name], Due: [Date]
- [ ] [Action item] — Owner: [Name], Due: [Date]

**Success metrics:**
- [How we'll know this worked — metric and target]

## References

- [Link to data source]
- [Link to customer interviews]
- [Link to competitive analysis]
- [Link to related PRD or strategy doc]
```

---

## Style Guidelines

- **Use headers generously** — make it scannable for someone skimming
- **Include date and author** — docs get discovered months later
- **Add tables, callouts, toggles** — for complex or dense information
- **Link liberally** — to related docs, data sources, meeting notes
- **Write for the future reader** — someone 6 months from now should understand this without any prior context
- **Make it the source of truth** — if someone asks "where's the info on X?", this doc should be the answer

---

## Example: Feature Research Doc

# Dark Mode Feature Research — May 2024

**Author:** Sarah Chen, Senior PM
**Last Updated:** May 15, 2024
**Status:** Final

---

## Overview

Research findings from 15 enterprise customer interviews exploring dark mode as a potential Q2 feature. This doc consolidates findings, analyzes business impact, and provides recommendations for roadmap prioritization.

## Background / Context

Dark mode surfaced in Q1 sales calls as a common enterprise request. We conducted structured research to validate demand and understand use cases before committing engineering resources.

**Related docs:**
- Q2 Roadmap Planning (link)
- Enterprise Customer Feedback Log (link)

## Key Findings

### User Demand
- 15/15 enterprise customers interviewed
- 12/15 mentioned dark mode unprompted as top request
- $450K ARR represented in interview cohort
- 3 customers explicitly tied renewals to feature

### Use Cases
**After-hours work:** 80% of enterprise users work outside 9-5
- Async teams across timezones
- Late-night planning sessions
- Early morning review sessions

**Eye strain concerns:** Universal pain point
- "Our engineers work late. Dark mode isn't luxury, it's health" — DataCorp VP Eng

### Competitive Context
- Asana: Full dark mode, shipped 2022
- Linear: Dark mode default, highly praised
- Notion: System-based dark mode
- Our product: None ← competitive gap

## Implications

This isn't a design preference — it's a barrier to enterprise adoption:
1. **Expansion risk:** 3 customers waiting on this for broader rollout
2. **Competitive parity:** Table stakes for PM tools in 2024
3. **User satisfaction:** Directly impacts daily experience for power users

## Recommendations

**Prioritize dark mode for Q2 delivery.**

- [ ] Engineering scoping session — Owner: Alex, Due: May 20
- [ ] Design exploration — Owner: Design team, Due: May 17
- [ ] Roadmap re-prioritization discussion — Owner: Sarah, Due: May 22

**Success metrics:**
- Enterprise retention rate holds at 95%+
- 60%+ adoption among enterprise users within 30 days of launch
- Unblock 3 pending expansion conversations ($200K ARR)

## References

- Customer interview recordings (link)
- Competitive analysis spreadsheet (link)
- Engineering feasibility doc (link)
- Q1 Sales feedback compilation (link)

---

## Using AI to Generate Notion Docs

### From raw notes or meeting output

```
Using @notion-wiki-doc.md, turn @[raw-notes-or-analysis].md into a
Notion-style wiki page. Include Overview, Background, Key Findings
(with subheaders), Implications, Recommendations with owners and
deadlines, and References. Write it for someone reading 6 months
from now.
```

### From multiple sources

```
Synthesize @[source-1].md, @[source-2].md, and @[source-3].md into
a single Notion doc using @notion-wiki-doc.md as the format. Deduplicate
findings, resolve any conflicts between sources, and present a unified
view with clear recommendations.
```

### Update an existing doc

```
Update @[existing-doc].md with the latest findings from @[new-data].md.
Add a "Latest Update" section at the top, revise any sections that are
now outdated, and note what changed and why.
```
