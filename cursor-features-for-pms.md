# Cursor Features for PMs — Quick Reference

A concise guide to the Cursor features most useful for product management work.

---

## Workspace Layout

Three panes: **File explorer** (left) | **Editor** (middle) | **AI Pane** (right).

- **File explorer** (`Cmd/Ctrl+B`): Browse your project files and folders.
- **Editor**: View and edit markdown, CSVs, or any file. Toggle markdown preview with `Cmd/Ctrl+Shift+V`.
- **AI Pane** (`Cmd/Ctrl+I` or `Cmd/Ctrl+L`): Where you talk to the AI. This is your main interface.
- **Terminal** (`` Ctrl+` ``): Run commands; rarely needed for PM work.

**PM scenario:** Your PRDs, research docs, data files, and frameworks all live in the file explorer. You edit in the middle pane and ask the AI to analyze, write, or review in the right pane.

---

## Three Modes

Switch with the mode picker, `Cmd/Ctrl+.`, or `Shift+Tab`.

| Mode | What it does | When to use |
|------|-------------|-------------|
| **Ask** | Read-only; analyzes but makes no changes. | Exploring unfamiliar docs. Quick research. "What does this file contain?" |
| **Agent** | Reads and writes files, runs commands. Default mode. | 80% of daily work: writing PRDs, analyzing CSVs, creating docs. |
| **Plan** | Researches context, asks clarifying questions, produces a structured plan, then executes on approval. | Complex multi-step projects: launch plans, strategy docs, multi-file deliverables. |

**PM scenario:** Use **Agent** for "write a PRD for feature X." Use **Plan** for "plan a multi-channel launch campaign" where you want to review the approach before anything is created.

---

## Referencing Files and Context

Three ways to give the AI context:

1. **@ mentions** (most common): Type `@filename.md` in the AI Pane. Also works with `@Folder`, `@Web`, `@Git`.
2. **Drag and drop**: Drag a file from the explorer into the AI Pane input box.
3. **Add to Chat**: Select text in the editor → click "Add to Chat" to send a specific excerpt.

**PM scenario:** "Using @rumelt-strategy-kernel.md, create a strategy doc" — the AI reads the framework file and applies it. No copy-pasting.

---

## Quick Inline Edits (`Cmd/Ctrl+K`)

Click anywhere in a file, press `Cmd/Ctrl+K`, and type an instruction. The AI edits right where your cursor is.

Good for: "Fix this typo," "Rephrase this paragraph," "Make this more concise."

**PM scenario:** You're reviewing a PRD draft. Click on a section, `Cmd+K`, "Make this success criteria more specific." Done.

---

## Project Rules (`.cursor/rules/`)

Markdown files in `.cursor/rules/` that auto-apply to every conversation. No `@` mention needed. Like persistent memory.

**What to put in rules:**
- Product terminology (e.g. "Workspace" not "Project")
- Persona definitions
- Writing style preferences
- Documentation standards

**PM scenario:** Create a `product-context.mdc` rule with your company's terminology, personas, and priorities. Every AI response will use your terms and reference your personas automatically.

**Two types:** Project rules (`.cursor/rules/` in this repo; apply to this project only) and Global rules (Cursor settings; apply to all projects).

---

## Web Search

The AI can search the web when you ask it to. Works in Agent and Plan modes.

**PM scenario:** "Search the web for Notion, Linear, and Asana's AI features and create a comparison table." Competitive research in one prompt.

---

## Markdown Preview & Editing

- **Preview toggle:** `Cmd/Ctrl+Shift+V` on any `.md` file.
- **Side-by-side:** Drag the preview tab next to the source for live preview.
- **WYSIWYG extension:** Install "Markdown Editor" by zaaack for Google Docs-style editing (`Cmd/Ctrl+Shift+Alt/Opt+M`).

**PM scenario:** Preview your PRD or strategy doc as formatted markdown before sharing.

---

## Model Selector

Bottom of the AI Pane. Switch between models (Claude, GPT, Gemini, etc.). For PM work (docs, analysis, strategy), use the best available model — PM work uses far fewer tokens than coding, so cost is minimal.

---

## Key Shortcuts Summary

| Shortcut | Action |
|----------|--------|
| `Cmd/Ctrl+I` or `Cmd/Ctrl+L` | Open AI Pane |
| `Cmd/Ctrl+K` | Quick inline edit |
| `Cmd/Ctrl+B` | Toggle file explorer |
| `Cmd/Ctrl+Shift+V` | Toggle markdown preview |
| `Cmd/Ctrl+.` or `Shift+Tab` | Switch AI mode (Ask/Agent/Plan) |
| `Cmd/Ctrl+Shift+P` | Command palette |
| `` Ctrl+` `` | Toggle terminal |
