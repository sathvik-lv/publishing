# Worklog

Newest entries at the top. Three devices — **Windows PC**, **MacBook**, **Mobile** —
share this file and nothing else: no shared chat, memory or disk. Each device:
`git pull` + read this *before* working; append an entry + commit + push *after*
working. Work recorded here is done — don't redo it. Use one of those three device
labels exactly (`brain` parses the field). Full protocol in `CLAUDE.md`.

## 2026-09-07 — Mobile (3-device worklog sync)

- Set the cross-device protocol up for **three** devices — Windows PC, MacBook and
  **Mobile** (this one, Claude on the web). It had only ever named two.
- Added **`CLAUDE.md`** carrying the protocol. This was the actual gap: the convention
  only lived inside `WORKLOG.md`, so a session that had not already been told to read
  the worklog never read it — which is why context kept being re-explained by hand and
  work got repeated. `CLAUDE.md` is loaded automatically on every device, so
  "pull → read WORKLOG → don't redo → append + push" now happens unprompted.
- Normalised this file's header to the wording shared by all 12 repos, naming the three
  device labels `brain` parses.
- Verified this repo was already exactly at `origin` before the change: clean tree,
  nothing ahead or behind.
- Recorded the standing rule in `CLAUDE.md` since this repo is public: only rendered
  results are published, and figures come from the source research repos rather than
  being hand-edited into the HTML.
- **Next:** nothing open here. The protocol applies from the next session on any device.

## 2026-08-05 — Windows PC (later)
- **Removed the "02 Planned Extensions" section from `index.html`** — the MCX contract-rebuild
  card was the only item in it, so the divider, the grid, and the orphaned `.planned-*` /
  `.divider` CSS all came out with it. `--amber` vars kept (still used by `.badge-warn`).
- Suggestions section renumbered 03 → 02. Tag balance verified.
- Note: the roadmap item itself is no longer surfaced anywhere public. If it should still be
  tracked, it needs a home outside `index.html`.

## 2026-08-05 — Windows PC
- **Added `xau_inr.html`** — 5th dashboard. Systematic long-only rupee-gold book,
  22.4-year backtest. Headline 29.30% CAGR, Sharpe 1.709, MDD −22.69%, 24/24 positive years.
- Promoted XAU/INR out of Planned Extensions into the dashboard grid as card 05.
  Planned Extensions now tracks the contract-level rebuild instead (blocked on
  exchange data access).
- Page carries its own caveats rather than burying them: hero badged "Proxy series",
  the friction section states the adjusted central estimate is **~22%, not 29%**, and
  it records that an earlier contaminated selection was discarded.
- All figures generated from a single run in the private research repo and
  cross-checked against the page; HTML tag balance and internal links verified.
- Signal inputs, parameters, data sources and repo internals stay private per the
  existing pattern — only rendered results are public.

## 2026-07-16 — MacBook
- Set up cross-device worklog. Verified this repo is fully synced with GitHub (no unpushed/uncommitted changes).
