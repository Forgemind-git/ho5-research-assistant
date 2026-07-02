# Sample 03 — Decision Knowledge Base (copy-and-use template)

> A ready-to-adapt template for a NotebookLM knowledge base over the scattered PDFs behind a big decision (a vendor, a health plan, a framework) — so every trade-off answer **cites where it came from**.

**This is a template** with a worked vendor example plus `<< … >>` blanks for your own decision.

## The problem statement

> *"You're weighing a big decision (a vendor, a health plan, a framework) and the material is scattered across PDFs and pages. Build a NotebookLM knowledge base over those sources and ask the trade-off questions that matter; every answer cites where it came from. Success: a notebook + a one-page cited decision brief + an Audio Overview."*

## Use it with your Claude.ai subscription

No API key, no code.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, **Create new notebook**.
2. **Add source** for each option: upload the **pricing PDF**, paste the **feature page URL**, add a **docs page**, and paste a **third-party review** (see [`sources.md`](./sources.md)). Cover each option evenly.
3. Ask the trade-off questions in [`qa.md`](./qa.md), e.g. *"Which option is cheapest at our size, and what's excluded? Cite each."*
4. Confirm each **citation** points at the right pricing/feature page. Paste answers into `qa.md`.
5. In **Studio**, generate a **Briefing doc**; copy into [`briefing.md`](./briefing.md) and turn it into a recommendation.
6. In **Studio**, generate an **Audio Overview** to gut-check the trade-offs; **Share** for a link.
7. **Share** the notebook so stakeholders can interrogate the sources themselves.

**No API key needed.** Genuine **RAG** — NotebookLM retrieves across all the PDFs at once and cites the source of each trade-off claim, which is how you defend the decision.

## Fill these in
- **Notebook name:** `<< e.g. Helpdesk Vendor Decision / Health Plan 2026 >>`
- **Shared notebook link:** `<< paste link >>`
- **Audio Overview link:** `<< paste link >>`

## The three template files
- **`sources.md`** — source-list template (example rows + blanks; works for vendors, health plans, or frameworks).
- **`qa.md`** — trade-off questions with one worked answer and blanks.
- **`briefing.md`** — a one-page decision brief template ending in a recommendation.

## Make it your own
- Swap the three example vendors for your real options — or make it a **health plan** (upload each plan's Summary of Benefits PDF) or a **framework** decision (upload docs + benchmark posts).
- Add the **contract/terms PDF** — lock-in and cancellation clauses are where citations matter most.
- Ask *"What risks or limits are mentioned that a buyer might miss?"*
