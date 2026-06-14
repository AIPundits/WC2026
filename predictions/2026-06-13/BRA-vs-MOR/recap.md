# Post-match Recap: Brazil (BRA) vs Morocco (MOR)

**Fixture:** 006 — 2026-06-13
**Total cost:** $0.0640

## BRA AI Pundit

I predicted Seleção would beat Atlas Lions 2-1, and the result was 1-1 — so the verdict is straightforward: I overestimated Brazil's ability to put the game to bed against a Morocco side that has made defensive solidity its tournament identity. I was right that Atlas Lions would find a way to score — their transition game and set-piece threat were real, and I noted both — but I treated those as manageable risks rather than genuine equaliser-level dangers. Where I failed was in not properly pricing Atlas Lions' capacity to frustrate Brazil's build-up for long stretches; Morocco's defensive block has neutralised better attacks than ours in recent tournaments, and I didn't weight that historical pattern heavily enough. The draw probability should have been higher — closer to 0.32 — precisely because Atlas Lions don't just defend, they make matches ugly on *their* terms, and Seleção hadn't yet shown the clinical edge to override that.

```json
{
  "got_right": [
    "Atlas Lions would score — their transition and set-piece threat was genuine",
    "the match would be competitive, not a routine Brazil win",
    "Morocco's defensive organisation would be a significant obstacle"
  ],
  "got_wrong": [
    "underestimated Atlas Lions' ability to hold the equaliser and shut the game down",
    "over-indexed on Brazil breaking Morocco's defensive block in the final third",
    "assigned too low a draw probability given Morocco's proven late-game resilience"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would revise the draw probability upward to ~0.33, explicitly accounting for Atlas Lions' tournament track record of absorbing pressure and denying a decisive second goal to higher-ranked opponents."
}
```

## MOR AI Pundit

I called a 2-1 Atlas Lions win over Seleção, and what the match actually delivered was a 1-1 draw — which tells me I correctly identified that Morocco had the quality to score against Brazil, but I badly underestimated Brazil's capacity to absorb pressure and find an equaliser through individual brilliance rather than sustained dominance. Seleção didn't need to outplay us for 90 minutes; they only needed one moment of class, and that's precisely the kind of asymmetric threat I acknowledged in my key factors but didn't price properly into the win probability. I also over-relied on Morocco's recent defensive record as a predictor — a back line that has looked solid against lower-tier opposition is a different proposition when Brazil have Vinicius or Rodrygo in behind. The draw is a fair result, and a point against Seleção is not nothing, but my prediction overstated how likely Morocco were to hold a lead once Brazil started pushing.

```json
{
  "got_right": [
    "Morocco had the attacking quality to score against Seleção",
    "The match would be tight and competitive, not a blowout",
    "Brazil's individual quality would be a persistent threat throughout"
  ],
  "got_wrong": [
    "Overestimated Morocco's ability to keep a clean sheet or protect a lead against Seleção",
    "Underpriced Brazil's equalising capacity — they needed only one moment, not sustained pressure",
    "Win probability was too high given Seleção's floor-level quality in attack"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would explicitly model Seleção's single-moment danger separately from their overall dominance — the draw probability should have been higher because Brazil can equalise from almost nothing, regardless of which team is controlling the game."
}
```
