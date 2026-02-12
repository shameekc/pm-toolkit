# PM Toolkit

A collection of frameworks, templates, prompt libraries, Cursor rules, and best practices for product management work — designed to be used with [Cursor](https://cursor.com).

---

## What's Inside

### `frameworks/`
Reusable strategy and decision-making frameworks.

| File | What it is |
|------|-----------|
| `rumelt-strategy-kernel.md` | Diagnosis → Guiding Policy → Coherent Actions |
| `gibson-biddle-dhm.md` | Delight, Hard to Copy, Margin-Enhancing (feature scoring) |
| `swot-analysis.md` | Strengths, Weaknesses, Opportunities, Threats |
| `devils-advocate.md` | Structured method to stress-test strategic decisions |
| `socratic-questioning.md` | Targeted questions to sharpen feature thinking |
| `impact-estimation.md` | Three-scenario ROI modeling for feature investments |

### `templates/`
Fill-in-the-blank templates for common PM deliverables.

| File | What it is |
|------|-----------|
| `prd-template-lenny.md` | Lightweight PRD (Lenny Rachitsky style) |
| `prd-template-detailed.md` | Comprehensive PRD with problem/solution/launch sections |
| `problem-analysis.md` | Synthesize quant + qual evidence into a problem statement |
| `experiment-readout.md` | A/B test results with topline, segments, quality, recommendation |
| `roi-scenarios.md` | Three-scenario business case (pessimistic / realistic / optimistic) |
| `strategy-document.md` | Full strategy doc using Rumelt's Kernel |
| `user-interview.md` | User interview notes with question bank and AI processing prompts |
| `meeting-notes.md` | Raw capture format + structured output format for meetings |
| `product-sync-notes.md` | Structured recurring product sync / cross-functional meeting notes |
| `meeting-follow-up-email.md` | Executive recap and quick team update email formats |
| `executive-email.md` | 3-paragraph executive email (Context → Insights → Recommendation) |
| `slack-update.md` | Short-form Slack updates with templates for 5 common situations |
| `notion-wiki-doc.md` | Long-form Notion/wiki documentation with full example |
| `press-release.md` | Two PR styles: Amazon PR/FAQ (pre-build) + Google Product Blog (launch) |

### `prompts/`
Ready-to-use prompts for Cursor, organized by workflow.

| File | What it covers |
|------|---------------|
| `data-analysis.md` | Funnel analysis, survey themes, experiment results, segmentation |
| `strategy.md` | Competitive research, framework application, devil's advocate |
| `prd-and-docs.md` | PRD generation, multi-perspective review, presentations, communication |

### `best-practices/`
Writing and presentation standards.

| File | What it covers |
|------|---------------|
| `presentation-action-titles.md` | McKinsey/BCG-style slide titles and deck structure |
| `communication-styles.md` | Executive email, Slack update, and Notion doc formats |

### `.cursor/rules/`
Cursor rules that auto-apply to every conversation in this project.

| File | What it does |
|------|-------------|
| `pm-assistant.mdc` | General PM assistant behavior (structured output, evidence-based, actionable) |
| `reviewer-engineer.mdc` | Engineering reviewer persona for PRD reviews |
| `reviewer-executive.mdc` | Executive reviewer persona for PRD reviews |
| `reviewer-user-researcher.mdc` | User research reviewer persona for PRD reviews |

### `image-generation/`
Image generation toolkit using Gemini 3 Pro.

| File | What it is |
|------|-----------|
| `image_gen.py` | Main generation module (handles API, sessions, saving) |
| `style_extract.py` | Extract style descriptions from any image |
| `get_style.py` | Retrieve prompts from your style library |
| `style-library.html` | Browse your saved styles (open in browser) |
| `README.md` | Setup and usage instructions |

### Root files

| File | What it is |
|------|-----------|
| `cursor-features-for-pms.md` | Quick reference to Cursor features useful for PM work |
| `customizing-the-toolkit.md` | How to add your own frameworks, personas, prompts, and rules |

---

## How to Use

1. **Open this folder in Cursor** as a project (or copy contents into your own project).
2. **The `.cursor/rules/` files auto-apply** to every conversation — the AI will behave as a PM assistant and know the reviewer personas.
3. **Reference frameworks and templates with `@`**: e.g. "Using @rumelt-strategy-kernel.md, create a strategy for..."
4. **Copy prompts from `prompts/`** and adapt them to your data and context.
5. **Add your own company context** — see `customizing-the-toolkit.md` for guidance.

---

## Customizing

This toolkit is a starting point. See **`customizing-the-toolkit.md`** for how to:

- Add your company context as a Cursor rule
- Create more reviewer personas (designer, data analyst, legal, sales)
- Add frameworks (RICE, JTBD, OKRs, Kano, etc.)
- Expand the prompt library
- Build slash commands for common workflows

---

## License

Use freely. Adapt to your needs.
