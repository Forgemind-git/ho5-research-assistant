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

## Use it with your Claude.ai subscription

No API key needed — just your normal Claude.ai login. Claude builds this quiz for you live as an **Artifact** (the preview panel on the right of the chat).

1. Open **Claude.ai** and start a new chat.
2. Copy the **example prompt** below and paste it in. Send it.
3. Claude builds the quiz in an **Artifact** panel on the right. Click through the questions to test it.
4. Want changes? Just ask — e.g. *"add a 6th question about budget"* or *"change the plans to my own pricing tiers"*. Claude updates the artifact.
5. To share it, click **Publish** for a link — or click the **`</>` code** button, copy the HTML, and save it as `index.html`. (A finished copy is already in this folder.)

## The example prompt

Copy this exactly into Claude.ai:

```
Build me an interactive decision quiz as an artifact (one self-contained HTML file, no external libraries) that recommends which Claude plan fits the user: Free, Pro, Team, or API.

Ask 5 questions, each with 2-3 clickable answer options:
1. How they mainly use AI
2. How many people need access
3. How often they hit usage limits
4. Whether they need the most powerful models
5. Whether they need shared/central billing and admin control

Score the answers behind the scenes and, at the end, show a recommendation card with: the plan name, a clear one-sentence reason why, and a short list of that plan's key features.

Include a progress bar, Back and Next buttons (Next disabled until the current question is answered), and a Retake button. Use clean, modern styling.
```

## Make it your own
- Replace the four Claude plans with **your own** product tiers and prices.
- Rewrite the 5 questions to match how customers actually choose between your options.
- Ask Claude to add a "Talk to sales" button under the recommendation.

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
