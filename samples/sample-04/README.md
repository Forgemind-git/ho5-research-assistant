# Sample 04 — Exam / Certification Study Knowledge Base

> A NotebookLM knowledge base over your syllabus and dense readings that generates a **study guide** and **FAQ** and answers revision questions with **cited** answers you can trust. Ships as a notebook + study guide + 5 cited Q&A + an Audio Overview.

## The problem statement

> *"You're revising for an exam or certification from a syllabus and dense readings. Build a NotebookLM knowledge base over those materials, generate a study guide and FAQ, and ask questions that return cited answers you can trust. Success: a notebook with a study guide + 5 cited Q&A + an Audio Overview, documented in your repo."*

## What you'll build

A **research knowledge base** built from your real study materials: the exam guide, the syllabus, and the dense readings/whitepapers behind it. NotebookLM can then **auto-generate a study guide and an FAQ** from those materials, and answer any revision question with a **citation to the exact reading** — so you're revising from the source, not from something the model half-remembers (which is how you learn wrong facts).

For this reference we're revising for the **AWS Certified Solutions Architect – Associate** exam, but the shape works for any course: a university module, a medical board, a language cert. This is genuine **RAG** — retrieval across your readings, with citations — so when it says "S3 is object storage," you can click through to the page that says so.

Saved here:
- **`sources.md`** — the study materials in the notebook.
- **`qa.md`** — five revision questions with cited answers.
- **`briefing.md`** — the generated **study guide** (one page) plus FAQ pointers.

> Worked reference for the AWS SAA-C03 exam. Swap in your own syllabus and readings.

## Use it with your Claude.ai subscription

No API key, no code.

1. Go to **[notebooklm.google.com](https://notebooklm.google.com)**, sign in, **Create new notebook**.
2. **Add source**: upload the **exam guide PDF**, the **syllabus**, and your key **readings/whitepapers** (PDF or URL). Add lecture notes as **pasted text** if you have them (see `sources.md`).
3. In **Studio**, click **Study guide** — NotebookLM generates one from your materials. Click **FAQ** for a Q&A sheet. Copy the study guide into `briefing.md`.
4. Ask revision questions in the chat, e.g. *"When should I use S3 vs EBS vs EFS? Cite the reading."* Check the **citation**, then save into `qa.md`.
5. Generate an **Audio Overview** and listen to it as revision on the go. Paste the link below.
6. (Optional) **Share** the notebook with your study group.

**No API key needed.**

## Where Claude.ai fits
- Ask Claude to help you **turn the syllabus into a list of topics to quiz yourself on**.
- Paste NotebookLM's cited answers into Claude and ask it to **make flashcards** — the citations keep the cards accurate.

## This notebook
- **Notebook name:** `AWS SAA-C03 — Study`
- **Shared notebook link:** _paste your NotebookLM Share link here_
- **Audio Overview link:** _paste your Audio Overview Share link here_

## Make it your own
- Replace the AWS materials with **your** syllabus and readings. The exam guide + 3–6 core readings is a strong start.
- Use the **FAQ** and **Study guide** buttons first — they turn dense readings into a revision plan in seconds.
- Ask "explain X like I'm new to it, then cite where to read more" to combine a plain explanation with a trustworthy source.

## How this differs from HO4
HO4 answered from one pasted passage. Here NotebookLM **retrieves across your whole reading list** and cites the source — so a revision answer is always checkable against the actual material, which is exactly what you want before an exam.
