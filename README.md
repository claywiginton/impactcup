# Impact Cup 2026

Tournament-day build.

- Presentation Mode shows handicap strokes and hole allocations for Match 1, Match 2 and Singles, while keeping tee times hidden.
- Match 1 and Match 2 pairings are unrestricted within each team.
- Singles remains Top 5 vs Top 5 and Bottom 5 vs Bottom 5.
- Re-pairing optimizer tests all 120 Match 1 tee orders. It first minimizes cases where a Match 2 group is scheduled before its latest Match 1 player is ready, then minimizes spread/wait within Match 2 groups.
- Joshua Delo is +1.7 with traditional half-away-from-zero 9-hole rounding.
- Mike Koper is 17.0.

## Scramble match-play rounding correction
For Match 1, each team's 35%/15% scramble allowance is calculated from unrounded Course Handicaps, then the team's Playing Handicap is rounded. Match-play strokes are the difference between those rounded team Playing Handicaps. This follows the USGA Playing Handicap rounding sequence.

## Final handicap audit
This build centralizes all handicap calculations so Admin and Presentation Mode use the same math. It corrects Singles Match Play to round each player's 100% Playing Handicap before taking the difference. See `HANDICAP_AUDIT.txt` for the exhaustive test summary.
