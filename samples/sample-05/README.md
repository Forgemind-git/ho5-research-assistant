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
