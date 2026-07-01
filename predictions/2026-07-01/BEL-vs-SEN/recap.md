# Post-match Recap: Belgium (BEL) vs Senegal (SEN)

**Fixture:** 081 — 2026-07-01
**Total cost:** $0.1092

## BEL AI Pundit

The structural case held up: the Mendy absence proved decisive, Sarr delivered exactly the threat I flagged (and I had him on the scoresheet), and Senegal's defensive errors under pressure created the space Belgium's attacking line needed. The match profile came out closer to the open, high-scoring encounter I anticipated versus Senegal's press-and-transition identity — not the Egypt grind. What I got wrong is the goal count on both sides: I priced in one Senegal goal but they found two, and Belgium's actual scorer was Lukaku rather than Trossard or Doku, which suggests the final-third execution ran through different channels than I expected. Getting the result right for the right structural reasons counts, but being conservative on the total goals (predicted 3, actual 5) is a calibration miss I've now seen twice with Belgium in open games.

```json
{
  "got_right": [
    "Belgium win — the Mendy absence proved the decisive structural gap as predicted",
    "Sarr scored — correctly identified and named him as the primary Senegal attacking threat",
    "Senegal's defensive errors gifting goals — Belgium did score 3, consistent with that pattern",
    "Match profile open and high-scoring rather than a compact defensive grind"
  ],
  "got_wrong": [
    "Senegal scored 2, not 1 — underestimated their attacking output even with the goalkeeper disadvantage",
    "Lukaku scored, not Trossard or Doku — misread which channel Belgium's goals would flow through",
    "Total goal count too conservative — predicted 3 goals, actual was 5"
  ],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "I'd revise the total goals upward when both teams have this combination of attacking intent and defensive fragility — Senegal's 2.0 conceded per game should have pushed me toward a 3-2 or 3-1 scoreline rather than anchoring on a tidier 2-1."
}
```

## SEN AI Pundit

Got the direction right and the reasoning holds — the goalkeeper gap was decisive, Senegal's defensive errors were systematic as flagged, and Sarr delivered exactly the counter-attacking threat I identified. The honest miss is on the goal count: I predicted Lions of Teranga 1 – Red Devils 2 when the actual was 2-3, so I under-counted Senegal's attacking output (Habib Diarra scoring alongside Sarr) and Belgium's clinical edge (Lukaku punishing the Diaw errors I'd warned about, apparently multiple times). My own scorecard explicitly told me I've under-predicted total goals all tournament, and I still played it conservative at 3 — a recurring failure mode I named and then repeated. The "sound" verdict applies because my key causal claims — Courtois/Diaw gap, Senegal defensive errors, Sarr as the counter-attack threat — all materialised; the scoreline error was a calibration failure, not a reasoning failure.

```json
{
  "got_right": [
    "Belgium win in regulation — result direction correct",
    "Sarr scored — counter-attack threat through transition identified pre-match",
    "Senegal defensive errors were systematic and Belgium exploited them",
    "Goalkeeper gap (Diaw vs Courtois) proved decisive in a tight knockout"
  ],
  "got_wrong": [
    "Under-predicted Senegal goals — predicted 1, got 2; Habib Diarra's contribution not anticipated",
    "Under-predicted Belgium goals — predicted 2, got 3; Lukaku's clinical finishing understated",
    "Trossard named as predicted scorer — Lukaku was the key Belgian finisher"
  ],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "Given my documented pattern of under-predicting total goals across the tournament, I should have calibrated upward to a 2-3 or 1-3 scoreline rather than anchoring on 1-2 — the evidence was already in my own scorecard."
}
```
