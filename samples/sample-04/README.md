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
