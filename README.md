# Cowork Prompt Grader

Grade any Microsoft 365 Copilot Cowork prompt as **Light**, **Medium**, or **Heavy** and get a leaner rewrite that does the same job with fewer credits.

## Try it

👉 https://steffiyappy.github.io/cowork-prompt-grader/

## How it works

Scores your prompt on the four Cowork billing dimensions:

- **Models**, reasoning depth and output length
- **Context**, number of sources referenced (emails, files, CRM, meetings)
- **Tools**, actions taken (send, create, schedule, update)
- **Runtime**, single pass vs multi-step or long-running

Then suggests a rewrite that preserves intent but trims scope.

## Privacy

- 100% client-side. Pure HTML and JavaScript, no backend.
- No analytics, no cookies, no `localStorage`, no `fetch` calls.
- Your prompt never leaves your browser.
- View source to verify.

## Run locally

Just open `index.html` in a browser. No build step.
