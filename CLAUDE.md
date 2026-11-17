# DECA Family Hub

A one-page family hub for **Denair Elementary Charter Academy**: the school calendar, the bell
schedule, the lunch menu, and Parents Club events. Personal, not a class activity.
Live at <https://rossdavilla.github.io/DECA/>.

## Layout

| File | What it is |
|---|---|
| `DECA26.html` | The whole hub — one self-contained file, HTML + CSS + JS inline, no dependencies and no build step. The views (`#v-home`, `#v-calendar`, `#v-schedule`, `#v-menu`, `#v-events`) are sections of this one page, switched client-side. |
| `DECA Docs (2026-27).pdf` | The school's own packet for the year — the source the page's dates, bell times and menus are transcribed from. |

There is no `index.html`: the published URL is
<https://rossdavilla.github.io/DECA/DECA26.html>.

## Keeping it current

The content is hand-transcribed from the PDF, so it goes stale. The usual update is the **lunch
menu**, which the school reissues monthly, then calendar dates and Parents Club events.

- Read the dates and menus out of `DECA Docs (2026-27).pdf` (or whatever newer packet Ross
  provides) rather than inventing them. If the packet does not cover the month being added, ask
  Ross for the new one instead of guessing.
- Keep the existing data shapes in the inline JS — add rows to the arrays that are already there.
- A new school year means a new packet and a new file name (`DECA27.html`); update the directory
  entry's `path` if that happens.

## Publishing

GitHub Pages serves `main` from the repository root, so a push to `main` is the deploy.

This app is already in `data/sites.json` in the
[`rossdavilla.github.io`](https://github.com/rossdavilla/rossdavilla.github.io) repo under the
`personal` tag. Only touch that entry if the file name or the description changes.
