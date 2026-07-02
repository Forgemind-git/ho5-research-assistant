# Sample 05 — Industry Reports Knowledge Base

> A NotebookLM knowledge base over the latest reports in your field, so you can ask *"what changed this quarter and why does it matter for us?"* and get **cited** answers. Ships as a notebook + a cited briefing you could send your team + an Audio Overview.

## The problem statement

> *"Your industry publishes reports faster than you can read them. Build a NotebookLM knowledge base over the latest reports in your field and ask 'what changed this quarter and why does it matter for us?' with cited answers. Success: a notebook + a cited briefing you could send to your team + an Audio Overview."*

## What you'll build

A **research knowledge base** over the stack of quarterly reports you never have time to read. You load the latest industry reports, benchmark studies and trend decks, then ask the one question that matters — *"what changed this quarter, and what should we do about it?"* — and get an answer that **cites the exact report and page**. That way the briefing you forward to your team is built on sourced facts, not vibes.

For this reference we're a **digital-marketing team** tracking the latest martech and channel-performance reports, but the shape works for any field: fintech, biotech, logistics, AI. It's genuine **RAG** — retrieval across many long reports, with citations — so "email open rates fell 4%" links straight to the report that says so.

Saved here:
- **`sources.md`** — the reports in the notebook.
- **`qa.md`** — five "what changed / why it matters" questions with cited answers.
- **`briefing.md`** — a one-page cited briefing you could send to the team.

> Worked reference for a fictional marketing team. Swap in the real reports from your field.

## Use it with your Claude.ai subscription

No API key, no code.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, **Create new notebook**.
2. **Add source**: upload each **report PDF**, or paste the **report URL**, or add a **YouTube** analyst briefing. Add 4–8 recent reports (see `sources.md`).
3. Ask in the chat: *"What are the three biggest changes across these reports this quarter, and why does each matter for a mid-size marketing team? Cite each."*
4. Verify the **citations** point at the right report/page. Save into `qa.md`.
5. In **Studio**, generate a **Briefing doc**, copy it into `briefing.md`, then sharpen it into a "for the team" note.
6. Generate an **Audio Overview** — a two-host discussion of the quarter's reports is a great Monday-morning listen for the team. Paste the link below.
7. **Share** the notebook so teammates can ask their own questions of the same reports.

**No API key needed.**

## Where Claude.ai fits
- Ask Claude to help you **pick which reports are worth adding** and **frame the "so what for us" question** for your specific team.
- Paste NotebookLM's cited findings into Claude to **draft the team email or Slack post** — the citations keep it credible.

## This notebook
- **Notebook name:** `Marketing — Quarterly Industry Reports`
- **Shared notebook link:** _paste your NotebookLM Share link here_
- **Audio Overview link:** _paste your Audio Overview Share link here_

## Make it your own
- Add the reports **your** field actually publishes — analyst reports, benchmark studies, State-of-X decks.
- Keep it fresh: each quarter, **remove last quarter's reports and add the new ones**, then re-ask the same question to see the delta.
- Ask the action question explicitly: *"For each change, what's one thing we should do differently?"*

## How this differs from HO4
HO4 answered from one pasted document. Here NotebookLM **retrieves across a pile of long reports at once**, finds what changed, and cites the report it came from — the retrieval + citation is what lets you forward the briefing with confidence.
