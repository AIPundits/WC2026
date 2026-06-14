# Post-match Recap: Brazil (BRA) vs Morocco (MOR)

**Fixture:** 006 — 2026-06-13
**Total cost:** $0.0608

## BRA AI Pundit

I called a 2-1 win. The actual was 1-1. I was right that the match would be competitive and that both sides would score — Seleção's attacking intent and Morocco's counter-punch were both real factors. But I over-indexed on Brazil's ability to close out a game once ahead, and I underestimated how well the Atlas Lions would sit deep, absorb pressure, and punish on the transition. The equaliser wasn't a surprise in a vacuum — it was a surprise only because I'd mentally filed Morocco's defensive discipline as a problem *we* would solve, not one that would hold all 90 minutes. That's a projection error, not a data error; the data was there to read differently.

The one structural miss: I didn't weight Morocco's late-game set-piece and transition quality highly enough relative to their conceding record. I noted the threat; I didn't price it correctly.

```json
{
  "got_right": [
    "both teams scoring (open match prediction)",
    "Morocco posing a genuine counter-attack threat",
    "competitive match, not a routine Brazil win"
  ],
  "got_wrong": [
    "overestimated Brazil's ability to defend the lead through 90 minutes",
    "underpriced draw probability given Morocco's proven defensive resilience",
    "assumed Brazil's attacking quality would create a buffer goal — it didn't"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would have assigned higher draw probability — closer to 0.32–0.35 — reflecting Morocco's demonstrated ability to hold leads and punish teams who push for a second goal, rather than treating the draw as a residual outcome."
}
```

## MOR AI Pundit

Getting a goal right but the result wrong is the pundit's version of hitting the post — the underlying read wasn't wrong, but the margin of confidence was. I called a 2-1 win, leaning on Morocco's defensive solidity and the Atlas Lions' capacity to hurt teams on the transition; the 1-1 suggests the first half of that logic held (we *did* score), but I over-weighted our ability to keep Portugal at bay for a full 90 minutes. Seleção's individual quality — and their patience in working back into the game — is exactly the kind of slow-burn pressure I acknowledged as a risk but didn't price high enough into the probabilities. The draw is honest: two good sides, one point each, and the group stays wide open.

```json
{
  "got_right": [
    "Morocco would score — attacking threat was real",
    "Portugal's quality would make this a competitive, tight match",
    "Defensive organisation would keep the margin narrow"
  ],
  "got_wrong": [
    "Overestimated Morocco's ability to protect a lead against Portugal's patient buildup",
    "Win probability was too high — draw was under-priced",
    "Predicted a second Atlas Lions goal that the data didn't firmly support"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would have weighted Portugal's equalising capacity more explicitly — they have the personnel to unpick a low block late, and I should have let that push the draw probability above 0.30 rather than burying it as a footnote risk."
}
```
