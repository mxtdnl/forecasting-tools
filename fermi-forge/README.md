# Fermi Forge

**Live:** https://mxtdnl.github.io/forecasting-tools/fermi-forge/

**Intended standalone home (pending repository creation):** https://github.com/mxtdnl/fermi-forge with Pages at https://mxtdnl.github.io/fermi-forge/

An interactive classroom simulation on *breaking big questions down* (Fermi-isation), built as a single
self-contained HTML file with no external dependencies. Four modules: (A) Boiler Engineers of London — a
London-set restaging of Fermi's Chicago piano-tuner problem, contrasting a holistic direct guess with a
decomposed estimate, plus a seeded Monte Carlo demonstrator of error cancellation; (B) the Trinity paper-drop
yield estimate; (C) decomposing a geopolitical question in the style of the Good Judgment Project; (D) the
Drake equation as a sensitivity-analysis instrument, with an uncertainty tornado chart.

## Purpose

To teach three points: decomposition beats direct intuition for order-of-magnitude estimation; independent
per-factor errors partially cancel while correlated bias compounds; and sensitivity analysis identifies which
factor drives the uncertainty — and is therefore worth researching.

## Sources

- Tetlock, P. & Gardner, D. (2015), *Superforecasting*, ch. 5 (Fermi-isation; Good Judgment Project).
- Rhodes, R. (1986), *The Making of the Atomic Bomb*, Simon & Schuster (Fermi's Trinity paper-drop estimate).
- Drake, F. (1961), Green Bank conference (the Drake equation; seti.org).
- Gas Safe Register, *At a Glance Report 2023/24*: 150,729 registered engineers as at 31 March 2024
  (gassaferegister.co.uk, retrieved July 2026). The in-app London reference (~10,000) is derived by population
  scaling and flagged in-app as itself an estimate.

## Instructor guide

Allow 20–25 minutes. Set a shared seed (top right) so every student sees the identical run, then let students
work through modules A–D in order; each advances with a single primary button. The teachable moments are:
the reveal in Module A (most direct guesses are off by more than an order of magnitude; most decomposed chains
are not), the two histograms behind "Why does this work?" (independent errors cancel, correlated bias does
not), and Module D's tornado chart — ask students to narrow the top factor's range, re-run, and watch the
output spread collapse, then repeat with a bottom factor and watch nothing happen. The debrief screen includes
a "Copy results" button producing a plain-text summary students can paste into Zoom chat for comparison;
scoring places passive click-through play in the middle band by design, so grades reward engagement rather
than luck.
