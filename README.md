# Trading Reports

Daily market analysis briefs — pre-market setup, mid-session pulse, and post-close recap — auto-published every U.S. trading day from a local Python pipeline and served as static HTML via GitHub Pages.

## The Reports

Three briefs are produced every weekday. Each is self-contained HTML (inline CSS + inline SVG, no build step, no external dependencies) so it renders the same in any browser, with all gauges, sector grids, and vol-structure charts intact.

### Pre-Market Brief — Day-Trade Edition

The morning setup. Index playbook for SPY/QQQ, single-name watchlist with gap analysis and trigger levels, vol structure (VIX9D / VIX / OVX / MOVE / VXN), futures snapshot, breadth, sector relative strength, and the day's catalysts. Frames the question: what is the highest-conviction read going into the open, and what would invalidate it?

### Mid-Day Pulse

A tape-vs-book check around lunch. How is the morning's thesis holding up — did the open hold or fade, where are dealers positioned now, what is the intraday vol regime saying? Adjusts the index playbook for the back half of the session.

### Closing Bell Recap

End-of-day review. What worked, what didn't, what the close tells us about the next session's setup. Captures the day's drivers (catalysts, unusual flow, vol shifts) and surfaces the carry-forward read.

## URL Convention

Every report has a permanent, date-stamped URL — historical briefs stay reachable forever
