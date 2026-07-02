# Sample 01 — Competitor Intelligence Knowledge Base

> A NotebookLM knowledge base built over your competitors' websites, launch posts, reviews and docs. You ask *"what are their three biggest weaknesses?"* and get an answer that **cites the exact source**. Ships as a notebook + a cited gap-analysis brief + an Audio Overview, all documented here.

## The problem statement

> *"As a marketer you can't keep up with what competitors are shipping. Build a NotebookLM knowledge base over their sites, launch posts, reviews and docs, then ask 'what are their three biggest weaknesses?' and get answers that cite the exact source. Success: a notebook + a cited gap-analysis brief + an Audio Overview, documented in your repo."*

## What you'll build

A **research knowledge base** in Google NotebookLM. You add your competitors' real sources (marketing pages, launch blog posts, G2/Reddit reviews, help docs, pricing pages). NotebookLM reads only *those* sources and answers your questions with a **citation next to every claim** — so you can click through and check it came from a real place. That's the honest difference from a normal chatbot: this is **retrieval + generation (RAG)** over *your* material, not the model guessing from memory.

By the end you have four things saved in this folder:
- **`sources.md`** — the exact list of sources that went into the notebook.
- **`qa.md`** — five real questions with the cited answers NotebookLM gave.
- **`briefing.md`** — a one-page gap-analysis brief you could hand to your team.
- an **Audio Overview** link (NotebookLM turns the notebook into a two-host podcast).

> This sample is a **worked reference** for a fictional PM-software company, *TaskFlow*, sizing up three rivals. The sources below are illustrative examples — swap in your own real competitors.

## Use it with your Claude.ai subscription

You do **not** need an API key or any code. NotebookLM is free with a Google account, and this whole hands-on is no-code.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)** and sign in with your Google account. Click **Create new notebook**.
2. Click **Add source**. Add your competitors' material — you can paste a **website URL**, upload a **PDF**, paste **copied text**, or add a **YouTube link**. Aim for 6–12 good sources across 2–3 competitors (see `sources.md` for the shape).
3. Wait a few seconds for NotebookLM to ingest them. In the chat box, ask a real question, e.g. *"What are the three biggest weaknesses customers complain about for each competitor? Cite the source for each."*
4. Read the answer — every claim has a small **numbered citation**. Click one to jump to the exact sentence in the source it came from. Save the good Q&A into `qa.md`.
5. In the **Studio** panel, click **Briefing doc** (or **Study guide** / **FAQ**) to generate a summary. Copy it into `briefing.md`.
6. Still in **Studio**, click **Audio Overview → Generate**. In a couple of minutes you get a podcast-style discussion of your sources. Click **Share** to get a link and paste it below.
7. (Optional) Click **Share** at the top of the notebook to make it link-viewable, and paste that link below too.

**No API key needed.** Everything above uses your normal Google login.

## Where Claude.ai fits

Use your Claude.ai subscription as the *drafting partner around* the notebook:
- Ask Claude to help you **choose which sources** to add and **write sharp questions** to ask NotebookLM.
- Paste NotebookLM's cited answers into Claude and ask it to **tighten the gap-analysis brief** for a specific audience (e.g. your sales team).

NotebookLM gives you **cited retrieval over your sources**; Claude helps you **plan and polish**.

## This notebook

- **Notebook name:** `TaskFlow — Competitor Intelligence`
- **Shared notebook link:** _paste your NotebookLM Share link here_
- **Audio Overview link:** _paste your Audio Overview Share link here_

## Make it your own
- Replace the three example competitors with your real ones. Six to twelve sources is plenty to start.
- Add a **review** source (G2, Trustpilot, Reddit, app-store reviews) for each competitor — that's where the honest weaknesses live.
- Re-run the questions monthly. When a competitor ships something new, add the launch post as a source and ask *"what changed since last quarter?"*

## How this differs from HO4

HO4 was **in-context grounding** — you pasted text into a prompt and the model answered from that text. HO5 is real **retrieval**: NotebookLM stores many sources, *finds* the relevant passages for each question, and cites them. That retrieval step is what makes this genuine RAG.
