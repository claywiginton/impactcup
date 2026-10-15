# Impact Cup 2026 — Final Tournament Build

## Teams
- Team MacDonald
- Team Walker

## Match formats
- Match 1 — Captain's Choice
- Match 2 — Best Ball / Four-Ball Match Play
- Match 3 — Singles
- Finale — details announced on the course

## Pairing rules
- Match 1 and Match 2: every pair must contain one Top-5 player and one Bottom-5 player from that team.
- Singles: Top-5 players face Top-5 players; Bottom-5 players face Bottom-5 players.
- Match 1 tee order is optimized after Match 1 and Match 2 pairings are entered to reduce re-pairing delays.

## Handicap allowances
- Match 1 — 2-player scramble: 35% of lower Course Handicap + 15% of higher Course Handicap (USGA/WHS recommended allowance).
- Match 2 — Four-Ball Match Play: 90% from the lowest unrounded Course Handicap in the foursome (USGA/WHS).
- Match 3 — Individual Match Play: 100% allowance (USGA/WHS).
- 9-hole Course Handicap: use the applicable 9-hole Course Rating, Slope Rating and par.
- Impact Cup 6-hole Singles procedure: calculate the full Front-9 difference, allocate strokes by the normal Front-9 stroke-index order, and use only strokes that fall on Holes 1-6.
- Finale: Impact Cup Committee rule. USGA does not publish an allowance for a 10-player team playing one alternate-shot ball.

## Cup
- 24 total points
- Team MacDonald retains at 12
- Team Walker wins at 12.5

## GitHub Pages
Publish from:
- Branch: main
- Folder: / (root)


## Presentation Mode
Presentation Mode shows Match 1 matchups only. Tee times are intentionally hidden because they may not be finalized when pairings are presented.


## Handicap correction
Joshua Delo's Handicap Index is **+1.7** (plus 1.7), represented internally as -1.7 for calculations.


## Roster update
Keenan Huskey (injured) has been replaced by Mike Koper at a provisional Handicap Index of 17.0. Team Walker Top 5 / Bottom 5 split updates automatically from the new roster order.


## Pairing rule update
Matches 1 and 2 allow any two teammates to pair together. Singles still require Top 5 vs Top 5 and Bottom 5 vs Bottom 5. The selector UI is simplified and Match 1 tee-order information appears only in the optimizer, not on each match card or Presentation Mode.


## Handicap audit correction
The 9-hole Handicap Index halving step now uses traditional half-away-from-zero rounding, which is required for correct handling of plus handicaps. Joshua Delo (+1.7) therefore becomes +0.9 for the halved Index step, rather than +0.8. USGA/WHS allowances remain 35%/15% for 2-person scramble, 90% for Four-Ball Match Play, and 100% for Singles Match Play.
