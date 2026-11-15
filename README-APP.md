# Dirty Dozen Racing

The Holy Grail's twelve criteria, two boxes: the **top three of every race
with 8+ runners**, ranked by **how many of the twelve criteria the horse
scores in** — a criterion scores anything, it votes 1 point (**gold box**,
0–12; ties broken by raw points, the **green box**). Tap a pick to see all
twelve.

- Never scores anything itself — the Holy Grail's published day files
  (`projects/holy-grail/data/`) are the sheet of record; this slices,
  counts and ranks.
- **DD's own ledger**, settled with the Grail's bet maths: **£10 bank · 1%
  of the bank on every pick · each-way at Ladbrokes (½ win · ½ place at
  1/5 odds)**. Void picks never stake; a trio with a missing result stakes
  nothing until it's all in.

Published by `~/racing-scripts/dirty_dozen.py --publish` — 05:10 each
morning (waits for the Grail's 05:00 sheet) and every 30 minutes,
13:00–22:00, via `results-refresh.sh` so results trickle in live.
