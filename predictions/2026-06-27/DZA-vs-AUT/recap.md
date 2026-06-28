# Post-match Recap: Algeria (DZA) vs Austria (AUT)

**Fixture:** 071 — 2026-06-27
**Total cost:** $0.2587

## DZA AI Pundit

I got the draw right — and I'll own that the incentive-structure reasoning (both sides have reason to protect a level result) did ultimately produce the correct outcome — but a 3–3 thriller is about as far from my predicted "cagey low-scoring affair" as it's possible to get while still ending in a draw. I said Algeria had a "thin attacking record against organised defences" and predicted a set-piece-dependent, low-block match; instead Les Fennecs scored three times including two from Mahrez in open play, which directly contradicts my core framing of their attacking limitations. I correctly flagged Arnautovic as Austria's aerial threat and he delivered, but Gouiri (my predicted scorer) didn't score — it was Mahrez who delivered twice, showing exactly the European-quality attacking output I'd been talking down in this debate. The one thing I'd change: I over-indexed on Algeria's tournament sample (two matches, limited goals against Argentina and a set-piece win over Jordan) and under-indexed on Petkovic's 28-match goal-scoring record as a truer baseline for what Les Fennecs can produce when the game opens up.

```json
{
  "got_right": ["draw outcome correctly predicted", "Arnautovic as Austria's primary goal threat", "incentive structure correctly identified as pushing both sides toward a share of the spoils"],
  "got_wrong": ["Algeria's attacking output against Austria dramatically exceeded my 'thin record vs organised defences' framing", "predicted a cagey low-scoring match — actual game was a wide-open 6-goal thriller", "Gouiri as predicted scorer — Mahrez (x2) and Belghali scored instead", "yellow card constraint on Sabitzer did not prevent him scoring"],
  "reasoning_verdict": "fortunate",
  "one_thing_id_change": "I would weight Petkovic's full 28-match goal-scoring base rate more heavily than a two-game tournament sample when assessing Algeria's attacking ceiling, rather than treating those two matches as the definitive evidence of their limitations."
}
```

## AUT AI Pundit

I called the draw and I named Arnautovic as a scorer — those two things landed. But the reasoning that got me to 1-1 was built on a defensive picture that completely fell apart: I argued Austria's low block would be difficult for Les Fennecs to breach, that Algeria's attacking record against organised sides was thin, and that both teams would play conservatively with the incentive to protect a level result. A 3-3 scoreline is the opposite of a careful, managed draw — Rot-Weiß-Rot conceded three times (including two from Mahrez, who I didn't flag at all), and my Gouiri scorer call was wrong too. The yellow-card constraint I cited as a reason for Austrian caution clearly didn't stop Sabitzer getting on the scoresheet in what turned out to be an open, attacking game. I got the outcome right but the match looked nothing like the game I predicted.

```json
{
  "got_right": [
    "draw as the correct result",
    "Arnautovic scoring for Rot-Weiß-Rot",
    "both sides finding the net"
  ],
  "got_wrong": [
    "massively underestimated goal volume (predicted 2 total, actual 6)",
    "Algeria's attacking threat vs organised defences — Mahrez scored twice, not a thin threat at all",
    "Austria's low-block defensive solidity — conceded 3, not 1",
    "Gouiri as Algeria's scorer — Belghali and Mahrez scored instead"
  ],
  "reasoning_verdict": "fortunate",
  "one_thing_id_change": "I should have weighted the tournament average of 2.97 goals per game more heavily against my low-scoring narrative — the evidence for a tight, cautious match was weaker than the base rate suggested, and I should have widened my scoreline distribution to include high-scoring draw scenarios like 2-2 or 3-3."
}
```
