# Cited Q&A — TaskFlow Competitor Intelligence

Five real questions asked in the notebook, with the answers NotebookLM returned and the source each claim cited. Citations use the `[S#]` IDs from `sources.md` (in the app they appear as clickable numbered chips that jump to the exact sentence).

> These answers are an illustrative reference of what good cited output looks like. Your own notebook will cite *your* sources.

---

### Q1. "What are the three biggest weaknesses customers complain about for each competitor? Cite the source for each."

**Answer:**
- **Plannr** — (1) The new Timeline view is slow on large boards; several reviewers report lag past ~500 tasks **[S3]**. (2) No native mobile app, only a mobile web view **[S3]**. (3) The cheapest paid plan caps you at 3 projects **[S4]**.
- **GridWork** — (1) Steep learning curve; users say the spreadsheet model confuses non-technical teammates **[S7]**. (2) Automations break silently and are hard to debug **[S6][S7]**. (3) Minimum 5-seat purchase makes it expensive for tiny teams **[S8]**.
- **Kanbanly** — (1) API is rate-limited to 100 calls/min, which blocks heavy integrations **[S11]**. (2) Offline mode still can't create attachments **[S9]**. (3) The free tier is capped at 2 boards **[S12]**.

*Why it's trustworthy:* every weakness is pinned to a review or a docs/pricing page, not to marketing copy.

---

### Q2. "Where does each competitor's marketing claim not match what reviewers actually say?"

**Answer:**
- Plannr's homepage promises "blazing-fast timelines" **[S1]**, but G2 reviewers specifically call the Timeline view slow at scale **[S3]** — a claim-vs-reality gap.
- GridWork markets itself as "the spreadsheet your whole team will love" **[S5]**, yet the Reddit thread repeatedly flags that non-technical teammates struggle with it **[S7]**.
- Kanbanly's launch post headlines "true offline mode" **[S9]**, while its own docs and Capterra reviews note attachments don't sync offline **[S9][S10]**.

---

### Q3. "Which competitor is cheapest for a 3-person team, and what's the catch?"

**Answer:** For 3 people, **Plannr** is cheapest on paper because it bills per user with no seat minimum **[S4]**, but its entry plan caps you at 3 active projects **[S4]**. **GridWork** forces a 5-seat minimum, so a 3-person team pays for 5 **[S8]**. **Kanbanly** has a free tier but it's limited to 2 boards **[S12]**. Net: Plannr wins on price for a small team unless you need more than 3 projects.

---

### Q4. "What did each competitor ship most recently?"

**Answer:** **Plannr** shipped a **Timeline (Gantt-style) view** in its 4.0 release **[S2]**. **Kanbanly** shipped **mobile app 2.0 with offline mode** **[S9]**. GridWork's most recent documented change in these sources is an **automations setup revamp**, though no dated launch post was included **[S6]** — *gap in our sources; add GridWork's changelog to answer this fully.*

*Note how NotebookLM flags when the sources can't fully answer instead of inventing a date — that honesty is the point of citation-backed retrieval.*

---

### Q5. "Give me one positioning angle TaskFlow could use against each competitor, backed by a cited weakness."

**Answer:**
- **vs Plannr:** "Fast timelines even on 1,000-task boards" — directly answers the slowness reviewers report **[S3]**.
- **vs GridWork:** "No spreadsheet learning curve — usable on day one by non-technical teammates" — answers the top complaint in the Reddit thread **[S7]**.
- **vs Kanbanly:** "Unlimited API calls on every paid plan" — answers the 100 calls/min ceiling in their docs **[S11]**.

---

## What to copy into your own `qa.md`
Keep the pattern: **question → answer → the `[S#]` it cited**. If an answer has no citation, treat it with suspicion — a good NotebookLM answer always shows *where it came from*.
