# Sample 02 — Team Onboarding Knowledge Base

> A NotebookLM knowledge base over your team's wiki, runbooks and policy docs, so a new joiner can ask *"how do I request access?"* and get an answer that **cites the exact page**. Ships as a notebook + 5 cited onboarding Q&A + a briefing doc.

## The problem statement

> *"New joiners on your team ask the same questions for weeks. Build a NotebookLM knowledge base over your team's wiki, runbooks and policy docs so anyone can ask 'how do I request access?' and get an answer that cites the exact page. Success: a notebook that answers 5 real onboarding questions with correct citations, plus a briefing doc, in your repo."*

## What you'll build

A **research knowledge base** in Google NotebookLM built from the docs a new hire actually needs: the team wiki, on-call runbooks, the security/access policy, the tooling setup guide, and the PTO/leave policy. A new joiner types a plain-English question and NotebookLM answers **from those documents only**, with a **citation to the exact page** — so nobody has to Slack a senior engineer for the tenth time.

This is genuine **retrieval-augmented generation (RAG)**: NotebookLM searches across all your onboarding docs, pulls the relevant passage, and cites it. It does not answer from the model's general knowledge — if the answer isn't in your docs, it says so.

Saved in this folder:
- **`sources.md`** — the onboarding docs that went into the notebook.
- **`qa.md`** — five real onboarding questions with cited answers.
- **`briefing.md`** — a one-page "first week" briefing for new joiners.

> Worked reference for a fictional team, *Northwind Engineering*. Swap in your real wiki and runbooks.

## Use it with your Claude.ai subscription

No API key, no code. NotebookLM is free with a Google account.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, click **Create new notebook**.
2. Click **Add source** and add your onboarding docs. Export **Confluence/Notion wiki pages to PDF**, or use **Google Docs** directly, or **paste text**. Add 5–10 pages (see `sources.md`).
3. Ask a real onboarding question in the chat, e.g. *"How do I request access to the production database, and who approves it?"*
4. Check the **citation** on the answer — click it to confirm it points at the right policy page. Save good Q&A into `qa.md`.
5. In **Studio**, click **Briefing doc** to generate a "start here" summary; copy it into `briefing.md`. (An **FAQ** doc is also great for onboarding.)
6. (Optional) Generate an **Audio Overview** so new joiners can listen to a "welcome to the team" walkthrough on day one.
7. Click **Share** to make the notebook link-viewable and give new hires the link.

**No API key needed.**

## Where Claude.ai fits
- Ask Claude to help you **list which docs a new joiner needs** and **turn messy wiki pages into clean pasteable text**.
- Paste NotebookLM's answers into Claude to **draft a friendly onboarding checklist** from them.

## This notebook
- **Notebook name:** `Northwind Eng — Onboarding`
- **Shared notebook link:** _paste your NotebookLM Share link here_
- **Audio Overview link:** _paste your Audio Overview Share link here (optional)_

## Make it your own
- Point it at your **real** wiki, runbooks and policies. Start with the 5 things new joiners ask most.
- Add the **access-request policy** and **on-call runbook** first — those are the highest-value citations.
- When a doc changes, re-upload the new version so answers stay correct.

## How this differs from HO4
HO4 grounded answers in a single pasted document. Here NotebookLM **retrieves across many docs** and tells you *which page* each answer came from — that citation-backed retrieval is what makes onboarding answers trustworthy.
