# Tournament Context — updated 2026-07-16

**Matches with results:** 102 (72 group stage, 30 knockout)
**Average goals/game (all matches):** 2.89
**Draw rate — group stage:** 27.8% (20 draws in 72 matches)
**Draw rate — knockout (level at 90 min):** 16.7% (5 in 30 matches)

## Knockout scoreline frequency (use this for knockout fixtures)

*30 knockout matches played. 5 went to extra time level at 90 min.* *Of 25 decisive results: 16 settled by 1 goal, 9 by 2+ goals.*

| Scoreline | Count | % of KO matches |
|-----------|-------|-----------------|
| 2-1 | 8 | 26.7% |
| 2-0 | 5 | 16.7% |
| 3-2 | 4 | 13.3% |
| 1-1 draw | 4 | 13.3% |
| 1-0 | 4 | 13.3% |
| 3-0 | 3 | 10.0% |
| 4-1 | 1 | 3.3% |
| 0-0 draw | 1 | 3.3% |

## Group stage scoreline frequency (context only for knockout fixtures)

*72 group stage matches. Use for individual team scoring patterns (a team that scored 8 group stage goals carries real attacking threat), but do not use group stage margins as a template for knockout scorelines — mismatches that produced blowouts in the group stage are rare in the knockout rounds.*

| Scoreline | Count | % of GS matches |
|-----------|-------|-----------------|
| 1-0 | 10 | 13.9% |
| 1-1 draw | 9 | 12.5% |
| 3-1 | 8 | 11.1% |
| 0-0 draw | 7 | 9.7% |
| 2-0 | 6 | 8.3% |
| 2-1 | 6 | 8.3% |
| 3-0 | 5 | 6.9% |
| 4-1 | 4 | 5.6% |
| 5-1 | 3 | 4.2% |
| 2-2 draw | 3 | 4.2% |
| 4-2 | 2 | 2.8% |
| 4-0 | 2 | 2.8% |
| 5-0 | 2 | 2.8% |
| 3-2 | 2 | 2.8% |
| 3-3 draw | 1 | 1.4% |
| 6-0 | 1 | 1.4% |
| 7-1 | 1 | 1.4% |

## Calibration notes for pundits

- **Tight margins dominate knockout results** — of 25 decisive knockout results, 16 were settled by exactly 1 goal and only 9 by 2 or more. A 1-goal winning margin (e.g. 1-0, 2-1) is the knockout norm; predict a 2+ goal gap only when there is a clear quality and fitness gap evidenced by this tournament.
- **Knockout draw rate (level at 90 min): 16.7% (5/30 matches)** — a draw at 90 min triggers extra time. Do not set `draw_probability` below this rate without strong evidence of a decisive winner.
- **Clean sheets occur in 43.3% of knockout matches (13/30)** — one side failing to score is a genuine and common outcome. If a team has scored in fewer than half their tournament matches, or the opponent has conceded fewer than 1 goal per game, 0 goals for that team is the correct default — not 1.
- **Group stage scoring volume is evidence about individual teams, not knockout scorelines** — a team that scored consistently in the group stage has proven attacking quality that carries into the knockouts. An inability to score in the group stage is equally telling. But use the knockout frequency table above as your scoreline prior, not the group stage table.
- **Group stage draw rate: 27.8%** — relevant only for group stage fixtures.
- **Blowouts are rare in knockout rounds** — they occurred in the group stage (6-0, 7-1) but the knockout data shows far tighter margins. Only predict a large margin if the quality gap is exceptional and evidenced by this tournament, not just reputation.
