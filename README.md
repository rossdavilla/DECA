# DECA Family Hub

A one-page family hub for Denair Elementary Charter Academy: the school calendar, the daily bell
schedule, the lunch menu, and Parents Club events, all on a phone-sized page.

**Live:** https://rossdavilla.github.io/DECA/DECA26.html

## What's in here

| File | What it is |
| --- | --- |
| [`DECA26.html`](DECA26.html) | The whole hub — one self-contained file. The Home, Calendar, Schedule, Menu and Events views are sections of this page, switched client-side. |
| `DECA Docs (2026-27).pdf` | The school's own packet for the year — the source every date, bell time and menu on the page is transcribed from. |

There is no `index.html`, so the page's address ends in `DECA26.html`.

## Keeping it current

The content is hand-transcribed from the packet, so it goes stale. The usual update is the lunch
menu, which the school reissues monthly, then calendar dates and Parents Club events. The data
lives in arrays inside `DECA26.html` — add rows to the ones already there.

A new school year means a new packet and a new file (`DECA27.html`).

## Running it

Open `DECA26.html` in a browser. No build step, no dependencies, nothing collected.
