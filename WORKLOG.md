# Worklog

Newest entries at the top. Each device: pull + read this before working, append + push after working.

## 2026-08-05 — Windows PC
- **Added `xau_inr.html`** — 5th dashboard. Systematic long-only rupee-gold book,
  22.4-year backtest (2003-12-02 → 2026-04-16, 5,782 bars, 995 trades).
  Headline 29.30% CAGR, Sharpe 1.709, MDD −22.69%, 24/24 positive years.
- Promoted XAU/INR out of Planned Extensions into the dashboard grid as card 05.
  Planned Extensions now tracks the **MCX contract rebuild** instead (blocked on
  exchange data access — mcxindia.com and Investing.com both 403 automated requests).
- Page deliberately carries its own caveats rather than burying them: hero is badged
  "Proxy series — not MCX", section 06 states the post-friction central estimate is
  **~22%, not 29%**, and it records that an earlier full-sample-selected result was
  discarded as contaminated.
- All figures generated from one run in the private XAU-INR repo
  (`scripts/page_numbers.py` → `reports/page_numbers.json`) and cross-checked against
  the page; HTML tag balance and internal links verified before push.
- Source research, data and parameters stay private per the existing pattern — only
  rendered results are public.

## 2026-07-16 — MacBook
- Set up cross-device worklog. Verified this repo is fully synced with GitHub (no unpushed/uncommitted changes).
