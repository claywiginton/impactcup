# Impact Cup 2026

Final GitHub Pages build.

## Formats
- Match 1 — Captain's Choice: 5 points
- Match 2 — Best Ball / Four-Ball Match Play: 5 points
- Match 3 — Singles: 10 points
- Final — 10v10 Alternate Shot: 4 points

## Handicap method

### Match 1 — Captain's Choice
Uses the Front-9 Course Handicaps and the 35% low + 15% high 2-player scramble allowance.

### Match 2 — Best Ball / Four-Ball
Uses Back-9 Course Handicaps. Lowest player in the foursome plays from zero; the other players receive 90% of the difference.

### Partial-nine matches
For any match that plays only part of a nine, the app does **not** compress or prorate strokes into the holes being played.

Instead:
1. Calculate the normal full 9-hole handicap difference.
2. Round to the full 9-hole Playing Handicap difference.
3. Allocate those strokes by the actual 9-hole stroke-index order.
4. Only strokes that fall on holes actually being played count.

This applies to:
- Singles on Holes 1–6.
- Final on Holes 7–9.

Example: if a singles player has 5 strokes for the Front 9, those strokes fall on Holes 6, 7, 2, 4, 9. In a Holes 1–6 singles match, only Holes 6, 2, and 4 count, so the player receives 3 strokes.

## Cup scoring
- 24 total points
- Team Trey retains at 12
- Team Walker needs 12.5 to win

## GitHub Pages
Publish from:
- Branch: `main`
- Folder: `/ (root)`
