# Sample 05 — Industry Reports KB (copy-and-use template)

> A ready-to-adapt template for a NotebookLM knowledge base over the latest reports in your field — ask *"what changed this quarter and why does it matter for us?"* and get **cited** answers.

**This is a template** with a worked marketing example plus `<< … >>` blanks for your own field.

## The problem statement

> *"Your industry publishes reports faster than you can read them. Build a NotebookLM knowledge base over the latest reports in your field and ask 'what changed this quarter and why does it matter for us?' with cited answers. Success: a notebook + a cited briefing you could send to your team + an Audio Overview."*

## Use it with your Claude.ai subscription

No API key, no code.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, **Create new notebook**.
2. **Add source**: upload each **report PDF**, paste the **report URL**, or add a **YouTube** analyst briefing. Add 4–8 recent reports (see [`sources.md`](./sources.md)).
3. Ask the ready-made question in [`qa.md`](./qa.md): *"What are the three biggest changes this quarter, and why does each matter for us? Cite each."*
4. Verify the **citations** point at the right report/page. Paste answers into `qa.md`.
5. In **Studio**, generate a **Briefing doc**; copy into [`briefing.md`](./briefing.md) and shape it into a "for the team" note.
6. Generate an **Audio Overview** — a two-host discussion of the quarter's reports is a great Monday listen; **Share** for a link.
7. **Share** the notebook so teammates can ask their own questions of the same reports.

**No API key needed.** Genuine **RAG** — NotebookLM retrieves across a pile of long reports at once, finds what changed, and cites the report it came from (unlike HO4's single pasted document).

## Fill these in
- **Notebook name:** `<< e.g. Marketing — Quarterly Industry Reports >>`
- **Shared notebook link:** `<< paste link >>`
- **Audio Overview link:** `<< paste link >>`

## The three template files
- **`sources.md`** — source-list template (reports across your field; example rows + blanks).
- **`qa.md`** — "what changed / why it matters" questions with one worked answer and blanks.
- **`briefing.md`** — a one-page cited briefing template you could send the team.

## Make it your own
- Add the reports **your** field publishes — analyst reports, benchmark studies, State-of-X decks.
- Each quarter, **remove last quarter's reports and add the new ones**, then re-ask the same question to see the delta.
- Ask the action question explicitly: *"For each change, what's one thing we should do differently?"*
