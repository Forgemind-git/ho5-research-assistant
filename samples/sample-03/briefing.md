# Decision Brief — Helpdesk Vendor (HelpHub vs DeskFlow vs CaseNest)

*One-page cited decision brief generated from the NotebookLM notebook (Studio → Briefing doc), then turned into a recommendation. Every claim traces to a source in `sources.md`.*

## Recommendation
For a **15-agent team that needs SLAs/automation but not HIPAA**, choose **HelpHub** — SLAs and automation are included in its mid plan, avoiding DeskFlow's add-on creep and CaseNest's compliance premium `[S1][S2][S4][S7]`. **One condition:** negotiate a full data-export clause up front, because HelpHub's export is limited `[S2][S3]`.

## Trade-off at a glance

| Factor | HelpHub | DeskFlow | CaseNest |
|--------|---------|----------|----------|
| Price @ 15 agents | Mid `[S1]` | **Lowest base**, add-ons extra `[S4]` | Highest `[S7]` |
| SLAs/automation included | **Yes** `[S2]` | Add-on `[S5]` | Yes `[S8]` |
| Data export / lock-in | Limited (CSV, no attachments) `[S2][S3]` | **Full API export** `[S5]` | Not in sources `[S8]` |
| Compliance (SOC 2 / HIPAA) | SOC 2 only `[S2]` | Not stated `[S5]` | **SOC 2 + HIPAA** `[S8]` |
| Reviewer gripe | Export/reporting `[S3]` | Add-on cost creep `[S6]` | Setup effort/price `[S9]` |

## If the requirements change
- **Need HIPAA?** → CaseNest is the only clearly-compliant option `[S8]`.
- **Cost is everything and you'll skip add-ons?** → DeskFlow's base price wins `[S4]`.
- **Want lowest lock-in risk?** → DeskFlow's full export `[S5]`.

## Open items before signing
- Get **CaseNest's data-export terms** — missing from current sources `[S8]`.
- Confirm HelpHub will contractually guarantee **full export including attachments** `[S2]`.

## Audio Overview
A two-host audio discussion of these trade-offs was generated in NotebookLM (Studio → Audio Overview) — useful for a stakeholder who wants the gist before the meeting. Link: _paste your Audio Overview Share link here_.
