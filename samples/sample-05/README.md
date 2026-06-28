# Sample 05 — Compound Savings Calculator

> User enters starting amount, monthly contribution, annual interest rate, and years. Shows final value, total contributed, and interest earned. A Chart.js line chart redraws live showing balance growth year by year.

## What This Tool Does

A live compound interest calculator with a visual chart. Adjust any input field and the chart and summary cards update instantly — no page reload.

**Inputs:**
- Starting amount (principal)
- Monthly contribution
- Annual interest rate (%)
- Time period (years)

**Outputs:**
- **Total Contributed** — principal plus all monthly deposits
- **Interest Earned** — the growth attributable purely to compounding
- **Final Value** — total balance at the end of the period
- **Chart** — two-line Chart.js chart showing Total Balance vs. Total Contributed year by year, making the power of compounding visually clear

**Calculation method:** Monthly compounding. The nominal annual rate is divided by 12 to compute a monthly rate. Each month: `balance = balance × (1 + monthlyRate) + monthlyContribution`.

## Use it with your Claude.ai subscription

No API key needed — just your normal Claude.ai login. Claude builds this calculator (chart and all) for you live as an **Artifact** (the preview panel on the right of the chat).

1. Open **Claude.ai** and start a new chat.
2. Copy the **example prompt** below and paste it in. Send it.
3. Claude builds the calculator in an **Artifact** panel on the right. Change the numbers and watch the chart redraw.
4. Want changes? Just ask — e.g. *"compound yearly instead of monthly"* or *"add an inflation slider"*. Claude updates the artifact.
5. To share it, click **Publish** for a link — or click the **`</>` code** button, copy the HTML, and save it as `index.html`. (A finished copy is already in this folder.)

## The example prompt

Copy this exactly into Claude.ai:

```
Build me an interactive compound savings calculator as an artifact (one self-contained HTML file). Use Chart.js loaded from a CDN for the chart.

Input fields:
- Starting amount
- Monthly contribution
- Annual interest rate (%)
- Number of years

Compound monthly (divide the annual rate by 12). As the user types, update live — no submit button — and show:
- Total contributed (starting amount plus all monthly deposits)
- Interest earned
- Final value
- A line chart that redraws showing "Total Balance" vs "Total Contributed" year by year

Use clean, modern styling with summary cards above the chart.
```

## Make it your own
- Reframe it for a loan payoff, a savings goal, or a subscription's lifetime cost.
- Ask Claude to add a goal line ("reach $50,000") and highlight when it's hit.
- Change the currency symbol and number formatting to your region.

## How to Use

1. Open `index.html` in any modern browser — requires internet access for the Chart.js CDN.
2. Adjust the four input fields.
3. Chart and summary cards update live as you type.
4. Hover over the chart to see exact values for any year.

## How to Host

**Locally:** Double-click `index.html` (requires internet for Chart.js CDN on first load).

**Static hosting:**
- [Netlify Drop](https://app.netlify.com/drop)
- [GitHub Pages](https://pages.github.com/)
- Any static file host

## Dependencies

- [Chart.js](https://www.chartjs.org/) via CDN (`cdn.jsdelivr.net`) — loaded at runtime, no install needed.

## Disclaimer

This tool is for illustrative and educational purposes only. It does not account for taxes, inflation, fees, or variable interest rates. It does not constitute financial advice.
