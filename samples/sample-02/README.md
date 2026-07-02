# Sample 02 — Team Onboarding Knowledge Base (copy-and-use template)

> A ready-to-adapt template for a NotebookLM knowledge base over your team's wiki, runbooks and policies — so a new joiner can ask *"how do I request access?"* and get an answer that **cites the exact page**.

**This is a template** with a worked example filled in plus `<< … >>` blanks for your own docs.

## The problem statement

> *"New joiners on your team ask the same questions for weeks. Build a NotebookLM knowledge base over your team's wiki, runbooks and policy docs so anyone can ask 'how do I request access?' and get an answer that cites the exact page. Success: a notebook that answers 5 real onboarding questions with correct citations, plus a briefing doc, in your repo."*

## Use it with your Claude.ai subscription

No API key, no code. NotebookLM is free with a Google account.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, **Create new notebook**.
2. **Add source**: export your **Confluence/Notion wiki pages to PDF**, use **Google Docs** directly, or **paste text**. Add the 5–10 pages new joiners ask about (see [`sources.md`](./sources.md)).
3. Ask the ready-made questions in [`qa.md`](./qa.md), e.g. *"How do I request access to production, and who approves it?"*
4. Check each **citation** points at the right policy page. Paste your real answers into `qa.md`.
5. In **Studio**, generate a **Briefing doc** (and an **FAQ** — great for onboarding); copy into [`briefing.md`](./briefing.md).
6. (Optional) Generate an **Audio Overview** as a "welcome to the team" listen.
7. **Share** the notebook and give new hires the link.

**No API key needed.** This is genuine **RAG** — NotebookLM retrieves across your docs and cites the exact page, unlike HO4's single pasted document.

## Fill these in
- **Notebook name:** `<< e.g. MyTeam — Onboarding >>`
- **Shared notebook link:** `<< paste link >>`
- **Audio Overview link:** `<< optional >>`

## The three template files
- **`sources.md`** — source-list template (example rows + blanks for your docs).
- **`qa.md`** — five ready-to-ask onboarding questions with one worked answer and blanks.
- **`briefing.md`** — a "first week" briefing template to overwrite.

## Make it your own
- Add the **access-request policy** and **on-call runbook** first — highest-value citations.
- When a doc changes, re-upload it so answers stay correct.
