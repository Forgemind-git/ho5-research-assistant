# HO5 — Research Knowledge Base

> Hands-on portfolio project · **Week 3** · **Solo** · module M8. Part of the **ForgeMind AI — AI Productivity Essentials** course.

## Goal

**Done when:** you have a **NotebookLM knowledge base** that answers questions from **your own sources** **with citations** — plus a briefing (and/or an Audio Overview). Real retrieval-augmented generation (RAG), no code, no API key.

## What you'll build

A research knowledge base in **Google NotebookLM**: you add real sources (docs, PDFs, web pages, videos), then ask questions that come back with a **citation next to every claim**. Because NotebookLM *retrieves* the relevant passage from your sources and *generates* an answer grounded in them, this is genuine **RAG** — and that's the honest distinction from HO4, which was in-context grounding (pasting text into a prompt), not retrieval.

You then generate a **study guide / FAQ / briefing doc** and, optionally, an **Audio Overview** (a two-host podcast of your sources).

## What to ship

A NotebookLM notebook isn't code, so you ship its *evidence* as markdown in your repo:

- **`sources.md`** — the source list (what went into the notebook).
- **`qa.md`** — a set of **cited Q&A** (question → answer → the source it cited).
- **`briefing.md`** — a one-page briefing (or study guide).
- an **Audio Overview** link (if you used one).
- a **README** documenting the notebook, and optionally a **shared notebook link**.

## Pick a problem statement

Choose **one** — or bring your own (get it approved first):

1. **Competitor intelligence.** As a marketer you can't keep up with what competitors are shipping. Build a NotebookLM knowledge base over their sites, launch posts, reviews and docs, then ask 'what are their three biggest weaknesses?' and get answers that cite the exact source. Success: a notebook + a cited gap-analysis brief + an Audio Overview, documented in your repo.
2. **Team onboarding.** New joiners on your team ask the same questions for weeks. Build a NotebookLM knowledge base over your team's wiki, runbooks and policy docs so anyone can ask 'how do I request access?' and get an answer that cites the exact page. Success: a notebook that answers 5 real onboarding questions with correct citations, plus a briefing doc, in your repo.
3. **Big decision.** You're weighing a big decision (a vendor, a health plan, a framework) and the material is scattered across PDFs and pages. Build a NotebookLM knowledge base over those sources and ask the trade-off questions that matter; every answer cites where it came from. Success: a notebook + a one-page cited decision brief + an Audio Overview.
4. **Exam / certification.** You're revising for an exam or certification from a syllabus and dense readings. Build a NotebookLM knowledge base over those materials, generate a study guide and FAQ, and ask questions that return cited answers you can trust. Success: a notebook with a study guide + 5 cited Q&A + an Audio Overview, documented in your repo.
5. **Industry reports.** Your industry publishes reports faster than you can read them. Build a NotebookLM knowledge base over the latest reports in your field and ask 'what changed this quarter and why does it matter for us?' with cited answers. Success: a notebook + a cited briefing you could send to your team + an Audio Overview.

Each of the five is fully worked as a reference in [`samples/`](./samples/) — open one to see the exact source list, cited Q&A and briefing you're aiming for. The landing page [`index.html`](./index.html) lists them all.

## Use it with your Claude.ai subscription

No API key needed. This whole hands-on is no-code and uses **Google NotebookLM** (free with a Google account), with your **Claude.ai subscription** as the planning/polishing partner.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)** and sign in. Click **Create new notebook**.
2. Click **Add source** and add your real material — paste a **website URL**, upload a **PDF**, paste **copied text**, or add a **YouTube link**. Aim for a handful of good sources.
3. Ask a real question in the chat. Every answer comes back with **numbered citations** — click one to jump to the exact sentence it came from.
4. In the **Studio** panel, generate a **Briefing doc**, **Study guide**, or **FAQ**.
5. In **Studio**, click **Audio Overview → Generate** for a podcast-style discussion of your sources.
6. Click **Share** to get a viewable notebook link.
7. Record the evidence in your repo: `sources.md`, `qa.md`, `briefing.md`, plus the links.

## Where Claude.ai helps

- **Before:** ask Claude to help choose which sources to add and write sharp questions.
- **After:** paste NotebookLM's cited answers into Claude to tighten your briefing for a specific audience.

NotebookLM does the **cited retrieval over your sources**; Claude helps you **plan and polish**. Different jobs.

## How to use this repo

1. Click **Use this template** to create your own copy.
2. Pick a problem statement, build your notebook, and fill in your sample's `sources.md`, `qa.md` and `briefing.md`.
3. Replace this section of the README with: what you built, the sources you used, and your notebook link.

---

*HO5 · Solo · ForgeMind AI Course · module M8 (Week 3)*

## 💡 Use your Claude.ai Pro plan wisely

Your Claude.ai Pro plan has a usage limit that resets every few hours. NotebookLM is free and separate, so most of this hands-on won't touch your Claude limit at all — but when you do use Claude to plan or polish:

- **Use the example prompts and questions** in each sample's README — they're already written and tested.
- **One clear message** beats lots of vague back-and-forth.
- **Start a new chat when you switch tasks.** Long chats re-read every earlier message and use up your limit faster.
- **Don't paste big files over and over.** Paste once, then refer back to it.
- **Using Claude Code or Cowork?** This repo's `CLAUDE.md` makes Claude follow these same rules automatically, and `SKILL.md` is a reusable "token-wise" skill.

If you do hit the limit, it resets after a few hours — nothing you've saved is lost.
