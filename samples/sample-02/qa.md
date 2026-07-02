# Cited Q&A — Northwind Engineering Onboarding

Five real onboarding questions, the answers NotebookLM returned, and the source each cited (`[S#]` from `sources.md`). In the app the citations are clickable chips that open the exact page.

> Illustrative reference of correctly-cited onboarding answers. Your notebook will cite your own docs.

---

### Q1. "How do I request access to the production database, and who approves it?"

**Answer:** Submit an access request in the IT portal under **"Production Data Access"**; requests must include a business justification **[S2]**. Approval is a two-step process: your team lead approves first, then the Security on-call reviews and grants it **[S2]**. Production database access is time-boxed to 90 days and auto-expires unless renewed **[S2]**.

---

### Q2. "What do I need to set up on my first day?"

**Answer:** Per the setup guide: install the standard toolchain (editor, CLI, VPN client), enable **MFA on your Google and VPN accounts** **[S1][S8]**, request access to your team's repos, and join the team Slack channels listed in the directory **[S1][S7]**. The security basics doc requires disk encryption and a password-manager before you connect to any internal system **[S8]**.

---

### Q3. "How does the on-call rotation work and who do I escalate to?"

**Answer:** On-call runs a **weekly rotation**, handed over each Monday **[S4]**. If you can't resolve a page within the primary window, escalate to the **secondary on-call**, then to the **engineering manager** if still unresolved **[S4]**. Escalation contacts and the current rotation are in the on-call handbook **[S4]**.

---

### Q4. "How many days of PTO do I get and how do I request them?"

**Answer:** Full-time engineers accrue **20 days of PTO per year**, plus public holidays **[S5]**. Request leave through the HR portal at least **two weeks in advance** for anything over 3 days; your manager approves it **[S5]**. Unused PTO carries over up to a **5-day cap** **[S5]**.

---

### Q5. "What's our git workflow — can I push straight to main?"

**Answer:** No — **direct pushes to `main` are blocked** **[S6]**. Work on a feature branch, open a pull request, and get **at least one approving review** before merge **[S6]**. Deploys to production follow the deploy runbook and run only after CI passes **[S3][S6]**.

---

## What to copy into your own `qa.md`
Pick the 5 questions your team answers over and over in Slack. If NotebookLM's answer has no citation — or cites the wrong page — that tells you a doc is missing or unclear. Fixing that is half the value of this exercise.
