# Sample 04 — Prompt Readiness Self-Assessment

> A 10-question self-assessment on prompting skill (does the user include role? context? output format? etc.). Each yes=1 point. Returns a score band (Beginner/Practitioner/Expert) and 2-3 tailored improvement tips based on which answers were No.

## What This Tool Does

A self-assessment scorecard that evaluates a user's current prompting habits across 10 evidence-based best practices. The tool scores responses and returns a band-level result with specific, actionable tips for the areas the user is missing.

**The 10 dimensions assessed:**
1. Assigning a role to the AI
2. Providing context and goals
3. Specifying output format
4. Setting length expectations
5. Using few-shot examples
6. Defining the audience
7. Iterating on prompts
8. Adding negative constraints
9. Testing across edge cases
10. Chaining complex tasks into steps

**Score bands:**
| Score | Band |
|---|---|
| 0–3 | Beginner |
| 4–6 | Practitioner |
| 7–10 | Expert |

**Tips:** The 3 "No" answers that appear earliest in the list generate personalised improvement tip cards.

## Use it with your Claude.ai subscription

No API key needed — just your normal Claude.ai login. Claude builds this scorecard for you live as an **Artifact** (the preview panel on the right of the chat).

1. Open **Claude.ai** and start a new chat.
2. Copy the **example prompt** below and paste it in. Send it.
3. Claude builds the self-assessment in an **Artifact** panel on the right. Answer the questions to test it.
4. Want changes? Just ask — e.g. *"make it 8 questions instead of 10"* or *"change the topic to social-media skills"*. Claude updates the artifact.
5. To share it, click **Publish** for a link — or click the **`</>` code** button, copy the HTML, and save it as `index.html`. (A finished copy is already in this folder.)

## The example prompt

Copy this exactly into Claude.ai:

```
Build me a prompting-skills self-assessment scorecard as an artifact (one self-contained HTML file, no external libraries).

Ask 10 Yes/No questions about good prompting habits:
1. Do you assign a role to the AI?
2. Do you give context and your goal?
3. Do you specify the output format you want?
4. Do you set length expectations?
5. Do you give examples of what good looks like?
6. Do you define the audience?
7. Do you iterate and refine your prompt?
8. Do you add "don't do X" constraints?
9. Do you test prompts on tricky/edge cases?
10. Do you break complex tasks into smaller chained prompts?

Each Yes = 1 point. The "See My Score" button stays disabled until all 10 are answered. When the user submits, show: a score out of 10, a band (0-3 Beginner, 4-6 Practitioner, 7-10 Expert), 2-3 tailored improvement tips based on which answers were No, and a breakdown of every answer. Add a Retake button. Use clean, modern styling.
```

## Make it your own
- Rewrite the 10 questions for whatever skill you teach (writing, sales, design...).
- Change the band names and the advice to match your own framework.
- Ask Claude to add a "book a session" call-to-action under a low score.

## How to Use

1. Open `index.html` in any modern browser.
2. Answer all 10 Yes/No questions.
3. Press **See My Score** (enabled after all questions are answered).
4. View your band, score, personalised tips, and full answer breakdown.
5. Click **Retake Assessment** to start over.

## How to Host

**Locally:** Double-click `index.html`.

**Static hosting:**
- [Netlify Drop](https://app.netlify.com/drop)
- [GitHub Pages](https://pages.github.com/)
- Any static file host

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- No external dependencies
- No build step required
