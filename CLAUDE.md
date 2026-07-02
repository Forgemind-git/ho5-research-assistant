# CLAUDE.md — Research Knowledge Base (HO5, starter)

Guidance for **Claude Code / Claude Cowork** when working in this repo. The student is on the
**Claude.ai Pro plan**, which is usage-limited — work economically so their limit stretches,
*even when they make mistakes*.

## About this project
A **NotebookLM research knowledge base** that answers questions from the student's own sources
**with citations** — real retrieval-augmented generation (RAG). It is built in **Google
NotebookLM** (free, no code, no API key); Claude's job here is to help the student **choose
sources, write sharp questions, and polish the briefing** — not to write code.
This is the **starter**: each folder under `samples/sample-01 … sample-05` is a copy-and-use
**template** — `sources.md`, `qa.md`, `briefing.md` with example content filled in and `<< … >>`
blanks for the student's own material. Start from those; help the student fill the blanks.

**Honest framing:** NotebookLM IS RAG (retrieval + generation over the student's sources). That
is the distinction from HO4, which was in-context grounding (pasting text into a prompt), not
retrieval. Keep that distinction accurate when explaining it.

## Spend tokens wisely (read this first)
- **Plan before you build.** State a 1–3 line plan, then make the whole change in one pass.
- **Use the example questions in the sample's `qa.md`** instead of writing new ones — they're tested.
- **Don't re-read or re-paste** files already shown in the conversation.
- **Keep replies short** — show only what changed, skip the preamble.
- **Make all related edits at once** — no trial-and-error loops.
- **Ask one clear question when unsure** rather than guessing and redoing the work.
- **Reuse the starter templates** — fill the `<< … >>` blanks, don't rebuild from scratch.

## This repo, specifically
- It's the **Research Knowledge Base** hands-on, built in **NotebookLM** — no API key, no code.
- **No API key is ever required.** There is no runtime code; the deliverables are markdown
  documenting the notebook. Don't invent scripts or backends.
- Help the student add real sources in NotebookLM and fill in `sources.md` / `qa.md` /
  `briefing.md`. Insist every saved answer keeps its **citation**.
- When helping on the `starter` branch, don't restructure the repo or touch `main`.

See `SKILL.md` for the reusable **token-wise** skill that carries these same rules into Claude.ai.
