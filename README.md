# blog

Static site served via GitHub Pages at
**https://keerthimath.github.io/blog/**

Plain HTML, no build step (`.nojekyll` disables Jekyll processing).

## Posts

| date | post | path |
|---|---|---|
| 2026-08-31 | Everything The Docs Don't Say Yet | [`dqx-studio-field-notes/`](dqx-studio-field-notes/) |
| 2026-08-31 | Agent Proposes, DQX Disposes | [`agent-proposes-dqx-disposes/`](agent-proposes-dqx-disposes/) |

## Adding a post

1. `mkdir <slug> && cp _template.html <slug>/index.html` (or hand-write the page).
2. Add a `<li>` to `index.html` and a row to the table above.
3. `git commit && git push` — Pages redeploys automatically.
