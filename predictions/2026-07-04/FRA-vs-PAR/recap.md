# Post-match Recap: France (FRA) vs Paraguay (PAR)

**Fixture:** 090 — 2026-07-04
**Total cost:** $0.2356

## FRA AI Pundit

The core call held up: Les Bleus won and kept the clean sheet, exactly as I argued Paraguay's limited attacking output (0.75/game) against our organised backline would produce. What I got right was the shape of the game — Albirroja's 5-3-2 was every bit the compact, suffocating structure I flagged, and it did precisely what I warned it might: it held France to fewer goals than our attacking record suggested. Where I erred was resolving that tension in the wrong direction — I acknowledged the risk that Paraguay's resilience would limit us to one, then predicted two anyway, and the 1-0 vindicated the compactness argument over the goal-tally argument. My clean-sheet read was sound and Maignan's backline delivered it; the second France goal I banked on never came, and Albirroja's defensive discipline is the reason.

The one thing I'd change: when I explicitly named a mechanism that would cap France at one goal, I should have trusted it enough to predict 1-0 rather than defaulting to the 2-0 that my earlier under-prediction habit was already pushing back against.

```json
{
  "got_right": [
    "France win and clean sheet — Paraguay's 0.75 goals/game couldn't breach Maignan's backline",
    "Paraguay's 5-3-2 was genuinely compact and suppressed France's goal output as flagged",
    "Almiron/Paraguay counter never materialised into a goal — regulation was France's territory"
  ],
  "got_wrong": [
    "Predicted France score 2 when their record suggested and Paraguay's shape limited them to 1",
    "Named the 'compact defence caps France at one' scenario but still predicted 2-0"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "When I explicitly identified Paraguay's compactness as a mechanism to cap France at a single goal, I should have committed to 1-0 rather than reflexively predicting 2-0."
}
```

## PAR AI Pundit

Called it right where it mattered on the scoreline shape: Albirroja were beaten in regulation, kept off the scoresheet exactly as the 0-goals default suggested, and Les Bleus needed their quality to break us down — the loss-in-regulation call holds up. Where I erred was the *margin*: I predicted France 2, and the 5-3-2 held them to one. That's the fourth time this tournament I've under-weighted Paraguay's shutdown capacity — I even flagged the calibration signal in my final turn and *still* left the second France goal in, when the honest read of our 1-conceded-in-270-minutes form should have pulled me to a 0-1 rather than 0-2. Alfaro's defensive block deserved more respect than my prediction gave it.

The one revision: I let France's attacking aggregate (3.25/game) anchor my opponent-goals number, when the sharper signal was Paraguay's own defensive trend — a single well-organised concession was always the more likely losing scoreline than a two-goal one.

```json
{
  "got_right": [
    "Loss in regulation — Albirroja beaten as predicted",
    "Paraguay's 0-goals default held against France's defence",
    "France needed their quality to break down the 5-3-2, no blowout"
  ],
  "got_wrong": [
    "Predicted 2 France goals — they scored only 1",
    "Under-weighted Paraguay's shutdown form despite flagging it as a calibration bias",
    "Named two French scorers when only one goal was required"
  ],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I'd anchor the opponent-goals number on Paraguay's own 1-in-270-minutes defensive trend rather than France's attacking aggregate, landing on 0-1 instead of 0-2."
}
```
