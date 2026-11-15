# Dirty Dozen Racing

The Holy Grail's twelve criteria, one number: the **top three of every race
with 8+ runners**, each selection showing its **total score in a box on its
right**. Tap a pick to see all twelve boxes.

- Never scores anything itself — the Holy Grail's published day files
  (`projects/holy-grail/data/`) are the sheet of record; this slices the top
  three out of every race.
- Money is stamped off the Grail's own ledger, replayed fresh on every
  publish: **£10 bank · 1% of the bank on every pick · each-way at
  Ladbrokes (½ win · ½ place at 1/5 odds)**. Void races never stake.

Published by `~/racing-scripts/dirty_dozen.py --publish` — 05:10 each
morning (waits for the Grail's 05:00 sheet) and every 30 minutes,
13:00–22:00, via `results-refresh.sh` so results trickle in live.
