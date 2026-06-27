# Sample 01 — AI Tool ROI Calculator

> A calculator where the user enters team size, hours spent on a task per week, hourly rate, and expected AI time saving (%). Returns: time saved per week, cost saved per month, and a payback period. Live-updating as user types.

## What This Tool Does

This single-page calculator helps teams quickly estimate the return on investment from adopting an AI tool. Enter four inputs and see the projected savings update in real time — no form submission required.

**Inputs:**
- Team size (number of people)
- Hours spent on the relevant task per week (per person)
- Average hourly rate (USD)
- Expected AI time saving percentage (e.g. 30%)
- Monthly tool cost (optional — enables payback period calculation)

**Outputs:**
- Time saved per week (hours across the whole team)
- Hours freed per month (team total and per-person breakdown)
- Net cost saved per month (gross savings minus tool cost)
- Annual net savings
- Payback period (how quickly the tool pays for itself)

## How to Use

1. Open `index.html` in any modern browser — no install or server needed.
2. Adjust the sliders/inputs to match your team's situation.
3. Results update instantly as you type.

## How to Host

**Locally:** Double-click `index.html` or drag it into a browser tab.

**Static hosting (free):**
- [Netlify Drop](https://app.netlify.com/drop) — drag the folder in
- [GitHub Pages](https://pages.github.com/) — push to a repo and enable Pages
- [Vercel](https://vercel.com/) — `vercel --prod` from this directory

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- No external dependencies
- No build step required
