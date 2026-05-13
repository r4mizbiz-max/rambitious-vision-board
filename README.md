# Rambitious Vision Board

Interactive HTML vision board for Q2/Q3 2026 — the 60-day sprint from Stage 2 → Stage 3.

## Open locally

```bash
open ~/Code/rambitious-vision-board/index.html
```

Or just double-click `index.html` in Finder.

## Deploy to GitHub Pages (private repo OK)

```bash
cd ~/Code/rambitious-vision-board
gh repo create rambitious-vision-board --private --source . --remote origin --push
gh api -X POST /repos/r4mizbiz-max/rambitious-vision-board/pages \
  -f source[branch]=main -f source[path]=/
```

After ~30 seconds: live at `https://r4mizbiz-max.github.io/rambitious-vision-board/`.

(Pages on private repos requires a paid GitHub plan; if not, the repo can be public — there's nothing sensitive in the HTML.)

## What's in it

- **North Star** — where this build leads (pod model · 2027+)
- **Today's snapshot** — honest current state
- **3-vehicle pyramid** — Cam's layered vehicles (service agency → coach → mass-market high-ticket)
- **6 Pinpoint Scaling stages** — where you are now, where you're going
- **8-week sprint** — interactive cards (click to expand day-by-day plan)
- **Daily rhythm** — every weekday overlay
- **Hiring trigger calendar** — MRR-based, not feeling-based
- **DO NOT list** — Cam's anti-patterns by stage
- **Anchor quotes** — re-read when the build hurts
- **Vault stats** — 283 transcripts, 28 patterns, 6 clients, all linkable to Obsidian

## Update cadence

- **Every Sunday evening:** mark previous week wins. Scan upcoming anchor task.
- **Every weekday morning:** check today's anchor task + daily rhythm + one quote.

## Source

Pulled from:
- `~/Documents/RAMBITIOUS VAULT/00-Operating-Principles/Vision-Board-2026-Q2-Q3.md` (full MD version)
- `~/Documents/RAMBITIOUS VAULT/00-Operating-Principles/Master-Plan-To-100k.md`
- `~/Documents/RAMBITIOUS VAULT/02-SOPs/Team-Structure/Org-Chart-by-Scale-Stage.md`
- `~/Documents/RAMBITIOUS VAULT/Cam-England-Knowledge/_transcripts/2026-04-10-wSRXAbspxTE-*.md` (the $60M/yr video)
