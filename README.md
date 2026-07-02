# HO5 — Research Knowledge Base (starter template)

> Hands-on portfolio project · **Week 3** · **Solo** · module M9. Part of the **ForgeMind AI — AI Productivity Essentials** course.

**This is the copy-and-use starter.** Clone it, pick a problem statement, and each sample folder gives you a ready-made **template** — a source-list template, a cited-Q&A template, and a briefing template, each with example content already filled in. Swap in your own sources and you have a working NotebookLM knowledge base documented in your repo.

## Goal

**Done when:** you have a **NotebookLM knowledge base** that answers questions from **your own sources** **with citations** — plus a briefing (and/or an Audio Overview). Real retrieval-augmented generation (RAG), no code, no API key.

## What to ship

A NotebookLM notebook isn't code, so you ship its evidence as markdown (already scaffolded for you in each sample folder):

- **`sources.md`** — the source list (what went into the notebook).
- **`qa.md`** — cited Q&A (question → answer → the source it cited).
- **`briefing.md`** — a one-page briefing (or study guide).
- an **Audio Overview** link (if you used one), and a **shared notebook link**.

## Pick a problem statement

Each folder in [`samples/`](./samples/) is a copy-and-use template for one of these:

1. **Competitor intelligence** ([`sample-01`](./samples/sample-01/)) — a KB over competitors' sites, launch posts, reviews and docs; ask "what are their three biggest weaknesses?" with cited answers.
2. **Team onboarding** ([`sample-02`](./samples/sample-02/)) — a KB over your wiki, runbooks and policies; answer 5 real onboarding questions with correct citations.
3. **Big decision** ([`sample-03`](./samples/sample-03/)) — a KB over the scattered PDFs behind a vendor / health-plan / framework choice; every trade-off answer cites its source.
4. **Exam / certification** ([`sample-04`](./samples/sample-04/)) — a KB over your syllabus and readings; generate a study guide + FAQ and get cited revision answers.
5. **Industry reports** ([`sample-05`](./samples/sample-05/)) — a KB over the latest reports in your field; ask "what changed this quarter and why does it matter for us?" with cited answers.

Or bring your own (get it approved first).

## Use it with your Claude.ai subscription

No API key needed. This hands-on is no-code and uses **Google NotebookLM** (free with a Google account), with your **Claude.ai subscription** as the planning/polishing partner.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)** and sign in. Click **Create new notebook**.
2. Click **Add source** and add your real material — paste a **website URL**, upload a **PDF**, paste **copied text**, or add a **YouTube link**. Your sample's `sources.md` is your fill-in list.
3. Ask the ready-made questions in your sample's `qa.md`. Every answer comes back with **numbered citations** — click one to jump to the exact sentence.
4. In the **Studio** panel, generate a **Briefing doc**, **Study guide**, or **FAQ**, and an **Audio Overview**.
5. Click **Share** to get a viewable notebook link.
6. Fill in your sample's `sources.md`, `qa.md`, `briefing.md`, and paste your links.

## Where Claude.ai helps

- **Before:** ask Claude to help choose which sources to add and write sharp questions.
- **After:** paste NotebookLM's cited answers into Claude to tighten your briefing for a specific audience.

NotebookLM does the **cited retrieval over your sources**; Claude helps you **plan and polish**.

## How to use this repo

1. Click **Use this template** to create your own copy.
2. Pick a sample folder, build your notebook, and fill in its `sources.md`, `qa.md` and `briefing.md`.
3. Replace this section of the README with: what you built, the sources you used, and your notebook link.

---

*HO5 · Solo · ForgeMind AI Course · module M9 (Week 3)*

## 💡 Use your Claude.ai Pro plan wisely

Your Claude.ai Pro plan has a usage limit that resets every few hours. NotebookLM is free and separate, so most of this hands-on won't touch your Claude limit — but when you do use Claude to plan or polish:

- **Use the example questions** in each sample's `qa.md` — they're already written and tested.
- **One clear message** beats lots of vague back-and-forth.
- **Start a new chat when you switch tasks.** Long chats re-read every earlier message and use up your limit faster.
- **Don't paste big files over and over.** Paste once, then refer back to it.
- **Using Claude Code or Cowork?** This repo's `CLAUDE.md` makes Claude follow these same rules automatically, and `SKILL.md` is a reusable "token-wise" skill.

If you do hit the limit, it resets after a few hours — nothing you've saved is lost.
