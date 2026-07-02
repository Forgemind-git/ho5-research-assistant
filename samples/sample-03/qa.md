# Cited Q&A — Helpdesk Vendor Decision

Five trade-off questions, the answers NotebookLM returned, and the source each cited (`[S#]` from `sources.md`).

> Illustrative reference of well-cited decision answers. Your notebook cites your own PDFs.

---

### Q1. "Which option is cheapest for 15 agents, and what's excluded from that price?"

**Answer:** At 15 agents, **DeskFlow** is cheapest on base price **[S4]**, but automation and advanced SLAs are **paid add-ons** not in the base tier **[S4][S5]**. **HelpHub** costs more per agent but includes automation and SLAs in its mid plan **[S1][S2]**. **CaseNest** is the priciest because compliance features are bundled, not optional **[S7]**. Net: DeskFlow wins on sticker price only if you don't need the add-ons.

---

### Q2. "Which vendor makes it hardest to leave — what are the data-export and lock-in terms?"

**Answer:** **DeskFlow** offers a **full data export via API**, so lock-in is low **[S5]**. **HelpHub**'s export is limited to CSV of tickets (attachments not included), a partial lock-in risk **[S2][S3]** — reviewers mention export gaps **[S3]**. The provided sources don't include CaseNest's export terms, so this can't be answered for CaseNest yet — *add CaseNest's docs/contract to close the gap* **[S8]**.

---

### Q3. "We handle health data — which option meets HIPAA/SOC 2?"

**Answer:** **CaseNest** explicitly lists **SOC 2 Type II and HIPAA** support, with a compliance add-on **[S8][S7]**. HelpHub's feature page mentions SOC 2 but not HIPAA **[S2]**. DeskFlow's included sources don't mention HIPAA **[S5]**. For a health-data use case, CaseNest is the only clearly-compliant option in these sources.

---

### Q4. "What do reviewers say is each one's biggest weakness?"

**Answer:** **HelpHub** — limited/partial data export and clunky reporting **[S3]**. **DeskFlow** — nickel-and-diming via add-ons; total cost creeps up **[S6]**. **CaseNest** — steeper setup and higher price, though praised for support **[S9]**. The neutral roundup echoes these: DeskFlow "cheap base, expensive complete" and CaseNest "premium but compliant" **[S10]**.

---

### Q5. "Given we're a 15-agent team that needs SLAs but not HIPAA, which is the best value?"

**Answer:** **HelpHub** looks like the best fit: SLAs and automation are **included** in its mid plan, avoiding DeskFlow's add-on creep **[S1][S2][S4]**, and you don't pay CaseNest's compliance premium you won't use **[S7]**. The main watch-out is HelpHub's **limited data export** — negotiate a full-export clause before signing **[S2][S3]**.

---

## What to copy into your own `qa.md`
Ask the questions that actually swing the decision — **cost at your real size, lock-in, compliance, and the hidden weaknesses in reviews.** A trustworthy answer cites the pricing PDF or terms page, not a marketing headline.
