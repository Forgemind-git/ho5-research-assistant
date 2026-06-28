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

## Use it with your Claude.ai subscription

No API key needed — just your normal Claude.ai login. Claude builds this explainer for you live as an **Artifact** (the preview panel on the right of the chat).

1. Open **Claude.ai** and start a new chat.
2. Copy the **example prompt** below and paste it in. Send it.
3. Claude builds the explainer in an **Artifact** panel on the right. Type or paste some text and watch the bars react.
4. Want changes? Just ask — e.g. *"add a row for a 1 million token window"* or *"explain in one line what a token is at the top"*. Claude updates the artifact.
5. To share it, click **Publish** for a link — or click the **`</>` code** button, copy the HTML, and save it as `index.html`. (A finished copy is already in this folder.)

## The example prompt

Copy this exactly into Claude.ai:

```
Build me an interactive "tokens and context windows" explainer as an artifact (one self-contained HTML file, no external libraries).

Give me a large textarea where I can type or paste any text. As I type, update live and show:
- Character count
- Word count
- Approximate token count (use the simple rule: characters divided by 4)

Then show a colour-coded horizontal bar for each of these AI models, showing how full its context window would be and roughly how many messages of this length would fit:
- GPT-3.5 Turbo (4k tokens)
- GPT-4 / Claude Instant (8k)
- GPT-4 Turbo (32k)
- Claude 3 Haiku (48k)
- Claude 3.5 Sonnet (200k)
- Gemini 1.5 Pro (1,000k)

Colour the bars: green under 25% full, yellow 25-60%, orange 60-90%, red over 90% or over the limit. Use clean, modern styling.
```

## Make it your own
- Change the model list to just the tools your team actually uses.
- Ask Claude to add a short, friendly sentence explaining why long context matters.
- Add a "cost estimate" line if you want to show roughly what a message would cost.

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
