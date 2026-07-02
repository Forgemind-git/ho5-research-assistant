# Sources — TaskFlow Competitor Intelligence

These are the sources added to the NotebookLM notebook. Three rivals, mixed source types (marketing pages, launch posts, third-party reviews, docs, pricing). Every citation in `qa.md` and `briefing.md` points back to one of these.

> Example set for the fictional company *TaskFlow*. Replace with your real competitors and real URLs. Keep the numbering — the Q&A cites these by `[S#]`.

| ID | Competitor | Source type | Title / what it is | Link (example) |
|----|-----------|-------------|--------------------|----------------|
| S1 | Plannr | Marketing page | Plannr homepage — "Project management, reimagined" | `https://plannr.example/` |
| S2 | Plannr | Launch blog post | "Introducing Plannr 4.0: Timeline view is here" | `https://plannr.example/blog/plannr-4` |
| S3 | Plannr | Third-party reviews | G2 reviews page (47 reviews, 4.1★) | `https://g2.example/plannr` |
| S4 | Plannr | Pricing page | Plannr pricing & plan limits | `https://plannr.example/pricing` |
| S5 | GridWork | Marketing page | GridWork homepage — "The spreadsheet that runs your team" | `https://gridwork.example/` |
| S6 | GridWork | Help docs | GridWork Help Center — "Setting up automations" | `https://help.gridwork.example/automations` |
| S7 | GridWork | Third-party reviews | Reddit r/projectmanagement thread on GridWork | `https://reddit.example/r/pm/gridwork` |
| S8 | GridWork | Pricing page | GridWork pricing (per-seat, min 5 seats) | `https://gridwork.example/pricing` |
| S9 | Kanbanly | Launch blog post | "Kanbanly mobile app 2.0 — offline mode" | `https://kanbanly.example/blog/mobile-2` |
| S10 | Kanbanly | Third-party reviews | Capterra reviews (128 reviews, 4.4★) | `https://capterra.example/kanbanly` |
| S11 | Kanbanly | Help docs | Kanbanly docs — "Integrations & API limits" | `https://docs.kanbanly.example/integrations` |
| S12 | Kanbanly | Pricing page | Kanbanly pricing & free-tier limits | `https://kanbanly.example/pricing` |

## How the sources were chosen
- **One marketing page per competitor** — captures how they *position* themselves (their claims).
- **One launch/blog post** — what they *just shipped* (the moving target).
- **One third-party review source** — where the honest weaknesses surface (G2, Reddit, Capterra).
- **One pricing/docs page** — hard limits and gaps competitors rarely advertise.

Mixing marketing (their claims) with reviews (customers' reality) is what lets NotebookLM answer *"where's the gap between promise and experience?"* with citations on both sides.

## Tips for your own version
- Paste review pages as **text** if the URL is behind a login — copy the visible reviews into a "Paste text" source.
- Keep each source focused; a 40-page PDF dilutes retrieval. Split very long docs.
- Re-add a competitor's launch post whenever they release something — then ask NotebookLM what changed.
