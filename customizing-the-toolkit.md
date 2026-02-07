# Customizing & Extending the Toolkit

This toolkit is a starting point. The more you tailor it to your company, product, and workflows, the more useful it becomes. Here's how.

---

## 1. Add Your Own Reviewer Personas

The toolkit includes three reviewer perspectives (engineer, executive, user researcher) in `.cursor/rules/`. You should add more that match your organization:

- **Data analyst** — Reviews PRDs for metric clarity, instrumentation gaps, and data feasibility.
- **Designer** — Reviews for UX coherence, accessibility, interaction patterns.
- **Legal/compliance** — Reviews for privacy, regulatory, and policy concerns.
- **Customer success / support** — Reviews for support burden, edge cases, and customer communication.
- **Sales / GTM** — Reviews for positioning, pricing clarity, and competitive differentiation.

Copy the structure of an existing reviewer file and adapt the focus areas, communication style, and review structure for each new persona.

---

## 2. Add Your Company Context as a Cursor Rule

Create `.cursor/rules/company-context.mdc` with:

- **Product terminology:** What you call things (e.g. "Workspace" vs "Project," "Sprint" vs "Cycle").
- **Personas:** Your real user personas with names, roles, pain points, and goals.
- **Company stage and priorities:** Series, ARR, current strategic focus (e.g. activation, retention, expansion).
- **Competitive positioning:** Who you compete with and how you differentiate.
- **Writing style:** Tone, voice, formatting conventions your team follows.

This rule auto-applies to every conversation, so the AI always knows your product context.

---

## 3. Add More Frameworks

The `frameworks/` folder can grow. Consider adding:

- **RICE scoring** — Reach, Impact, Confidence, Effort for prioritization.
- **Jobs to Be Done (JTBD)** — Framework for understanding user motivation.
- **Porter's Five Forces** — Industry structure analysis.
- **OKR planning** — Objectives and Key Results templates.
- **North Star Metric** — Framework for identifying your key metric.
- **Kano Model** — Categorizing features as must-have, performance, or delight.

Format each as a standalone markdown file with: overview, when to use, key questions, a template, common mistakes, and further reading.

---

## 4. Expand the Prompt Library

The `prompts/` folder contains starter prompts. Add your own for:

- **User research synthesis:** "Read these 8 interview transcripts and extract the top 5 themes with supporting quotes."
- **Sprint planning:** "Review the backlog and recommend what to include in the next sprint based on priority and capacity."
- **Competitive monitoring:** "Search the web for [competitor] product updates in the last 30 days."
- **Stakeholder communication:** "Rewrite this technical update as an executive email using @style-executive-email.md."
- **Retrospective analysis:** "Analyze this retro doc and identify the 3 most actionable improvements."

Save prompts that work well so you can reuse and refine them.

---

## 5. Add More Templates

The `templates/` folder can be extended with:

- **User story template** — As a [persona], I want [action] so that [outcome].
- **Sprint retro template** — What went well, what didn't, action items.
- **One-pager / brief** — Lightweight alternative to a full PRD.
- **Competitive analysis template** — Structured comparison across dimensions.
- **Post-mortem template** — Incident or launch post-mortem format.
- **Quarterly planning template** — Goals, themes, resource allocation.

---

## 6. Add Communication Style Guides

Create files in `best-practices/` for each communication format your team uses:

- Executive email, Slack update, Notion doc (included).
- **Add:** Jira ticket format, confluence page structure, investor update, board deck, all-hands talking points.

Reference these with `@` when asking the AI to write in a specific format.

---

## 7. Create Slash Commands

If you use Cursor's slash commands (`.cursor/commands/`), you can create shortcuts for common workflows:

- `/new-prd` — Opens the detailed PRD template and starts filling it in.
- `/review-prd` — Runs the three-perspective review on the current file.
- `/competitor-check` — Runs a web search for recent competitor updates.
- `/devil-advocate` — Challenges your current strategy using the devil's advocate framework.

---

## 8. Keep It Up to Date

- **After each project:** If you used a new prompt or framework that worked, add it to the toolkit.
- **Quarterly:** Review frameworks and templates; remove what you don't use, refine what you do.
- **When your product changes:** Update company-context rules so the AI stays current.

---

## General Principles

- **One file per concept.** Keep each framework, template, or reviewer in its own file so you can `@` reference it individually.
- **Self-contained.** Each file should make sense on its own — include enough context that someone (or the AI) can use it without needing other files.
- **Evidence over opinion.** When adding frameworks, include "when to use" and "common mistakes" sections so you (and the AI) apply them correctly.
- **Version control.** Since this is a git repo, commit after meaningful additions so you can track what changed and roll back if needed.
