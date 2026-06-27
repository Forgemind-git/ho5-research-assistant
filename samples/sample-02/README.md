# Sample 02 — AI Plan Recommendation Quiz

> A 5-question quiz that recommends which Claude plan (Free/Pro/Team/API) fits the user best. Each question has 2-3 radio button answers. After answering all, shows a recommendation card with a clear reason.

## What This Tool Does

A short decision quiz that scores the user's answers across four dimensions (use frequency, team size, usage limits, and need for admin control) and surfaces the best-fit Claude plan with a clear explanation and feature list.

**Questions cover:**
1. How the user primarily uses AI
2. How many people need access
3. How often they hit usage limits
4. Whether they need the most powerful models
5. Whether they need centralised billing / admin

**Recommendation plans:**
- **Claude Free** — light personal use, no card required
- **Claude Pro** — daily power users who want priority access
- **Claude Team** — organisations needing shared billing and collaboration
- **Claude API** — builders integrating Claude into software or workflows

## How to Use

1. Open `index.html` in any modern browser.
2. Answer each question by clicking an option.
3. Press **Next** after each answer; press **See My Result** on the last question.
4. View your recommended plan card with explanation.
5. Click **Retake Quiz** to start again.

## How to Host

**Locally:** Double-click `index.html`.

**Static hosting:**
- [Netlify Drop](https://app.netlify.com/drop) — drag the folder in
- [GitHub Pages](https://pages.github.com/)
- Any static file host (Cloudflare Pages, Vercel, etc.)

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- No external dependencies
- No build step required
