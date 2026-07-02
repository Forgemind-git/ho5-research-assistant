# Sources — Helpdesk Vendor Decision

The documents behind the decision, added to the NotebookLM notebook. Three vendors, evenly covered: pricing, features, docs, and one third-party review each. Answers in `qa.md` cite these by `[S#]`.

> Example set for a fictional decision between *HelpHub*, *DeskFlow*, and *CaseNest*. Replace with your real options (or a health plan / framework decision).

| ID | Option | Source type | Title / what it is | Link (example) |
|----|--------|-------------|--------------------|----------------|
| S1 | HelpHub | Pricing PDF | HelpHub plans & per-agent pricing | `helphub-pricing.pdf` |
| S2 | HelpHub | Feature page | HelpHub features — automation, SLAs | `https://helphub.example/features` |
| S3 | HelpHub | Third-party review | G2 review summary (4.3★, 210 reviews) | `https://g2.example/helphub` |
| S4 | DeskFlow | Pricing PDF | DeskFlow pricing (tiered, add-ons) | `deskflow-pricing.pdf` |
| S5 | DeskFlow | Docs page | DeskFlow docs — data export & API | `https://docs.deskflow.example` |
| S6 | DeskFlow | Third-party review | TrustRadius review summary (7.9/10) | `https://trustradius.example/deskflow` |
| S7 | CaseNest | Pricing PDF | CaseNest pricing & compliance add-on | `casenest-pricing.pdf` |
| S8 | CaseNest | Feature/security page | CaseNest security & compliance (SOC 2, HIPAA) | `https://casenest.example/security` |
| S9 | CaseNest | Third-party review | Capterra review summary (4.5★, 96 reviews) | `https://capterra.example/casenest` |
| S10 | All | Comparison article | Independent "Best helpdesk 2026" roundup | `https://review.example/helpdesk-2026` |

## How the sources were chosen
- **Pricing PDF per option** (`S1`, `S4`, `S7`) — the number the decision usually hinges on, plus what's excluded.
- **Feature/docs page per option** — capabilities and, crucially, **data export / lock-in**.
- **One third-party review per option** — the reality behind the sales pitch.
- **One neutral comparison article** (`S10`) — a cross-cutting source NotebookLM can use to balance vendor claims.

## Tips for your own version
- Include the **contract or terms PDF** if you can — cancellation and lock-in clauses are where you most want a citation.
- For a **health plan** decision, upload each plan's **Summary of Benefits PDF** — same shape, ask "which covers X and what's the deductible?".
- Keep vendor coverage even so comparisons are fair.
