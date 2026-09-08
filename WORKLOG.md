# Worklog

Newest entries at the top. Three devices — **Windows PC**, **MacBook**, **Mobile** —
share this file and nothing else: no shared chat, memory or disk. Each device:
`git pull` + read this *before* working; append an entry + commit + push *after*
working. Work recorded here is done — don't redo it. Use one of those three device
labels exactly (`brain` parses the field). Full protocol in `CLAUDE.md`.

## 2026-09-08 — Windows PC (the jewellery ERP joins the hub)

- **New `erp.html`, card 06 on the index, and a README row** — the jewellery ERP now sits
  beside the five research dashboards in the same card anatomy (tag, index, KPI strip,
  footer note, "Open dashboard"). Deliberately not a separate aesthetic: it is a sibling
  of the other five, not a landing page.
- **The page leads with what the system does, not how it looks** — the eleven departments
  by name, then the rules it will not break (no customer credit, owner-only accounts, one
  fixed making charge and one gem price, derived weights, s.269ST, gapless numbering,
  reversal never edit), then screenshots, then the build decisions, then what it is not.
- **Every figure on it was counted from the source, not recalled**: 281 endpoints, 90
  tables, 11 departments / 74 screens, 1,538 tests, 144-line barcode encoder. One claim
  was corrected before publishing — the barcode module had been written up as "about a
  hundred lines" and is 144.
- **Screenshots (`erp_shots/`) are the synthetic demo year, and the page says so.** Real
  books are never published and the ERP repo stays private, so a live demo was rejected:
  it would mean publishing the application itself, which contradicts the rule at the top
  of `CLAUDE.md`. A showcase page exposes nothing and cannot go down.
- Rejected: hosting a clickable instance on a free tier (Hugging Face Spaces sleeps after
  48h idle, Render spins down after 15 min) — both need the source public, and a
  cold-start on a resume click is worse than a page that always loads.
- **Reordered the hub**: SKU analytics is now 01 and the ERP 02, with the four trading
  dashboards following in their existing relative order (03-06). The two dashboards that
  are actual built systems now lead, rather than sitting fourth and sixth.
- **Added the usefulness and the USP, which the first cut was missing.** It described what
  the system does without saying why anyone should care. Two new sections lead the page
  now: *What it replaces* (four systems that do not talk to each other, plus a monthly
  re-keying step into Tally) and *What makes it different* (no subscription, works with the
  cable out, margin that cannot drift, the vendor-wax correction, s.269ST at the till, and
  every figure explainable because there is no model anywhere in it).
- **Next:** nothing open here. The ERP app's own interface work continues in `SKU_Analysis`.

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
