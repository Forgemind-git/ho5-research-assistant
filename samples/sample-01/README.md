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

## Use it with your Claude.ai subscription

No API key needed — just your normal Claude.ai login. This is exactly the kind of tool Claude builds for you as an **Artifact** (the live preview panel that appears on the right of the chat).

1. Open **Claude.ai** and start a new chat.
2. Copy the **example prompt** below and paste it in. Send it.
3. Claude builds the calculator live in an **Artifact** panel on the right. Type some numbers and watch it work.
4. Want it different? Just ask in plain English — e.g. *"add a field for number of weeks off per year"* or *"show the savings in euros"*. Claude updates the artifact.
5. To share it, click **Publish** on the artifact to get a link — or click the **`</>` code** button, copy the HTML, and save it as `index.html`. (This folder already has a finished copy you can open right now.)

## The example prompt

Copy this exactly into Claude.ai:

```
Build me a single-page interactive ROI calculator as an artifact (one self-contained HTML file, no external libraries).

Input fields:
- Team size (number of people)
- Hours spent on the task per week, per person
- Average hourly rate in USD
- Expected AI time-saving percentage (e.g. 30)
- Monthly tool cost in USD (optional)

As the user types, update the results live — no submit button. Show:
- Time saved per week (hours across the whole team)
- Hours freed per month
- Net cost saved per month (gross savings minus the tool cost)
- Annual net savings
- Payback period (how quickly the tool pays for itself)

Use clean, modern styling with result cards and big numbers. Make it look professional enough to share with a prospect.
```

## Make it your own
- Swap "AI tool" for whatever you actually sell — rename the inputs to match your product.
- Ask Claude to add your brand colours and a logo.
- Add a field that matters to your buyers (e.g. error-reduction %, or seats vs. usage pricing).

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
