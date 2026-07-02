# Sample 03 — Decision Knowledge Base (Vendor / Plan / Framework)

> A NotebookLM knowledge base over the scattered PDFs and pages behind a big decision, so every trade-off answer **cites where it came from**. Ships as a notebook + a one-page cited decision brief + an Audio Overview.

## The problem statement

> *"You're weighing a big decision (a vendor, a health plan, a framework) and the material is scattered across PDFs and pages. Build a NotebookLM knowledge base over those sources and ask the trade-off questions that matter; every answer cites where it came from. Success: a notebook + a one-page cited decision brief + an Audio Overview."*

## What you'll build

A **research knowledge base** that pulls all the decision material into one place. For this reference we're choosing a **customer-support (helpdesk) vendor** between three options — but the exact same shape works for a health plan, a cloud provider, or a frontend framework. You load each vendor's pricing PDF, feature page, docs and a third-party review, then ask the trade-off questions that actually decide it: *"which is cheapest at 15 agents?"*, *"which one locks me in?"*, *"which handles our compliance need?"* — and every answer **cites the exact page**.

This is real **RAG**: NotebookLM retrieves the relevant passage from across all the vendor docs and cites it, so your decision rests on sourced facts, not a sales rep's memory or yours.

Saved here:
- **`sources.md`** — every doc behind the decision.
- **`qa.md`** — five trade-off questions with cited answers.
- **`briefing.md`** — a one-page decision brief with a recommendation.

> Worked reference: choosing between *HelpHub*, *DeskFlow*, and *CaseNest*. Swap in your real options.

## Use it with your Claude.ai subscription

No API key, no code.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, **Create new notebook**.
2. **Add source** for each option: upload the **pricing PDF**, paste the **feature/comparison page URL**, add a **docs page**, and paste a **third-party review**. Cover each option evenly (see `sources.md`).
3. Ask the trade-off questions in the chat, e.g. *"Which option is cheapest for 15 agents, and what's excluded from that price? Cite each."*
4. Confirm each answer's **citation** points at the right pricing/feature page. Save into `qa.md`.
5. In **Studio**, generate a **Briefing doc** and copy it into `briefing.md`, then sharpen it into a recommendation.
6. In **Studio**, generate an **Audio Overview** — a two-host discussion of the trade-offs is a great way to gut-check the decision. Paste the link below.
7. **Share** the notebook so stakeholders can interrogate the sources themselves.

**No API key needed.**

## Where Claude.ai fits
- Ask Claude to help you **list the trade-off questions** that actually decide this (cost, lock-in, compliance, support).
- Paste the cited answers into Claude to **turn them into a decision brief** aimed at the person who signs off.

## This notebook
- **Notebook name:** `Helpdesk Vendor Decision`
- **Shared notebook link:** _paste your NotebookLM Share link here_
- **Audio Overview link:** _paste your Audio Overview Share link here_

## Make it your own
- Swap the three vendors for your real options — or make it a **health plan** decision (upload the plan-summary PDFs) or a **framework** decision (upload the docs and benchmark posts).
- Add the **contract/terms PDF** if you have it — lock-in and cancellation terms are where citations matter most.
- Ask the "what am I not seeing?" question: *"What risks or limits are mentioned that a buyer might miss?"*

## How this differs from HO4
HO4 answered from one pasted document. Here NotebookLM **retrieves across all the vendor PDFs and pages at once** and cites the source of each trade-off claim — the retrieval + citation is what lets you defend the decision.
