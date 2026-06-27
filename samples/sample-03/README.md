# Sample 03 — Token & Context Window Explainer

> The user types any text into a textarea. The tool counts approximate tokens (chars/4), shows how many messages like this fit in different context windows (8k/32k/100k/200k), and colour-codes how full each window would be.

## What This Tool Does

An interactive explainer that makes the abstract concept of "tokens" and "context windows" tangible. As the user types or pastes text, the tool instantly shows:

- **Character count** — raw length of the text
- **Word count** — whitespace-split word count
- **Approximate token count** — estimated using the chars ÷ 4 heuristic
- **Context window visualisation** — a colour-coded bar for each major AI model showing how full the window is and how many messages of that length would fit

**Context windows shown:**
| Model | Window |
|---|---|
| GPT-3.5 Turbo | 4k tokens |
| GPT-4 / Claude Instant | 8k tokens |
| GPT-4 Turbo | 32k tokens |
| Claude 3 Haiku | 48k tokens |
| Claude 3.5 Sonnet | 200k tokens |
| Gemini 1.5 Pro | 1M tokens |

**Colour coding:**
- Green — under 25% full
- Yellow — 25–60% full
- Orange — 60–90% full
- Red — over 90% full (or exceeds window)

## How to Use

1. Open `index.html` in any modern browser.
2. Type or paste any text into the textarea.
3. Results update live — no button needed.

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

## Notes

Token count uses the simple `characters ÷ 4` approximation, which is accurate for typical English prose. For exact token counts, use the Anthropic or OpenAI tokenizer libraries.
