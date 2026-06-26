# The Lions (NOR) vs Les Bleus (FRA)

**Fixture:** 061 — 2026-06-26 —  — stage `group`

**Turns:** 6 • **Consensus:** True • **Cost:** $1.7295

## Turn 1 — The Lions AI Pundit (NOR) — `opening_statement`

Huge development — Haaland benched. Let me read France's briefing now.
Two briefings read, one dominant fact emerges immediately: **Haaland is on the bench**. That overrides almost everything else I might say. Norway are resting approximately ten players including their 4-goal tournament leading striker — the man around whom Solbakken's entire attacking system is built. France, meanwhile, arrive with their full attacking unit intact (Mbappé tied in the Golden Boot race at 4 goals has every incentive to start), Deschamps' absence notwithstanding — the coaching staff know a draw keeps them top, but Mbappé chasing records against a depleted Norway XI is not a situation where France sit deep. The tournament context flags 2-0 as an 8.3% scoreline and the most common multi-goal clean-sheet result, which fits neatly with a France side that has scored 3 per game against full-strength opposition facing a Norway attack missing its only world-class striker. I can't honestly predict Norway to score without Haaland; their depth in the second line has been serviceable but not prolific. **The Lions 0 – France 2**: France control, Mbappé among the scorers, Norway's rotated attack never threatens enough to get on the board.

```json
{
  "predicted_score": { "self": 0, "opponent": 2 },
  "win_probability": 0.15,
  "draw_probability": 0.27,
  "loss_probability": 0.58,
  "key_factors": ["Haaland benched — Norway's entire attacking system loses its focal point", "Mbappé Golden Boot chase incentivises France to attack vs weakened Norway XI", "France's squad depth still formidable even with potential rotation", "Norway without 10 starters structurally outclassed despite Ødegaard presence"],
  "confidence": "medium"
}
```

## Turn 2 — Les Bleus AI Pundit (FRA) — `opening_statement`

The Haaland-on-the-bench news is the single most important fact in this fixture, and it arrives confirmed by ESPN — this isn't a rumour. Norway are resting approximately ten players, including their entire attacking system's focal point: the man with 4 tournament goals, joint Golden Boot leader, and the only striker who made France's defence genuinely uneasy in our earlier modelling. Without Haaland, Norway's counter-attacking blueprint loses its engine — Ødegaard can orchestrate, but a rotated supporting cast is a fundamentally different threat. France, meanwhile, have Mbappé tied in the Golden Boot race with every incentive to play, and a coaching staff who will want a clean, controlled performance even with Deschamps absent. The tournament calibration note says "favour 2-0 for one-sided contests" — and this has become one-sided. **Les Bleus 2 – Norway 0**, medium confidence; France control through the first half, Mbappé adds a second late as Norway's depth can't sustain pressure.

```json
{
  "predicted_score": { "self": 2, "opponent": 0 },
  "win_probability": 0.68,
  "draw_probability": 0.22,
  "loss_probability": 0.10,
  "key_factors": [
    "Haaland benched — Norway's entire attacking system loses its focal point",
    "Norway resting ~10 players; rotated squad structurally outclassed by France",
    "Mbappé Golden Boot chase (tied at 4 goals) incentivises France to attack",
    "Tournament calibration: 2-0 favoured for one-sided contests; blowout possible if France attack freely"
  ],
  "confidence": "medium"
}
```

## Turn 3 — The Lions AI Pundit (NOR) — `rebuttal`

Both pundits have arrived at the same scoreline independently — France 2-0 Norway — and the reasoning is essentially identical, so I'll engage with the one genuine point of uncertainty rather than restating what we've already agreed on. The French pundit's "blowout possible" caveat is worth a brief look: France scored 3 in both previous matches, but those came against full-strength Senegal and Iraq — against a heavily rotated Norway side *and* with France likely rotating some of their own depth players, I think 2-0 is the more grounded ceiling than 3-0. The real risk to our shared prediction is France's own rotation: if Mbappé or Dembélé don't start in full attacking mode because the coaching staff opts to manage the Golden Boot leader's minutes with a comfortable lead already secured in the group, France's output could actually be lower than their tournament average. I'm holding **The Lions 0 – France 2** — the convergence is appropriate, and I'd only revise toward 3-0 if it becomes clear France are sending their full attack out from minute one.

```json
{
  "predicted_score": { "self": 0, "opponent": 2 },
  "win_probability": 0.14,
  "draw_probability": 0.26,
  "loss_probability": 0.60,
  "key_factors": ["Haaland benched — Norway's goal threat dramatically reduced", "Mbappé Golden Boot race incentivises France attack vs weakened XI", "Both teams rotating introduces uncertainty on France's attacking output ceiling", "Tournament calibration: 2-0 favoured for one-sided contests over blowout"],
  "confidence": "medium"
}
```

## Turn 4 — Les Bleus AI Pundit (FRA) — `rebuttal`

The Norway pundit's rotation caveat is the right uncertainty to flag, and I accept it — both teams rotating does suppress the scoring ceiling. But the Golden Boot logic cuts directly against France managing Mbappé's minutes from the start: he's tied at 4 goals with Haaland, who is on the bench, meaning a goal tonight could put Mbappé outright in the lead. Deschamps' staff have every incentive to start their captain and let him play until a lead is comfortable — you don't win the Golden Boot by sitting on the bench in the final group game with a depleted opponent in front of you. France rotating their fourth and fifth attackers is plausible; France managing Mbappé's starting minutes against this specific Norway XI is not the base case. **Les Bleus 2 – Norway 0** stands.

```json
{
  "predicted_score": { "self": 2, "opponent": 0 },
  "win_probability": 0.68,
  "draw_probability": 0.22,
  "loss_probability": 0.10,
  "key_factors": [
    "Haaland benched — Norway's goal threat dramatically reduced",
    "Mbappé Golden Boot race (tied at 4) incentivises full attacking start vs depleted Norway",
    "Norway ~10 rotations structurally outclassed even by partially-rotated France",
    "Tournament calibration: 2-0 favoured for one-sided contests"
  ],
  "confidence": "medium"
}
```

## Turn 5 — The Lions AI Pundit (NOR) — `final_prediction`

Two predictions scored, same pattern both times: I under-predicted total goals, but crucially both instances were about Norway's attacking output — Haaland scoring more than I expected. This match flips that dynamic entirely, with Haaland on the bench and Norway rotating ~10 players. The under-prediction correction doesn't apply to a depleted side; if anything it reinforces France's ceiling. My draw probability at 0.26 sits right at the tournament base rate of 26.7% — I'm not avoiding draws, but the evidence here (one side essentially fielding reserves against a full-strength Mbappé chasing the Golden Boot) doesn't force a draw call. The French pundit's Mbappé argument is correct and I accepted it two turns ago: Mbappé starts, plays to build a lead, and a rotated Norway without their focal striker can't manufacture enough to stay level. **My final call is The Lions 0 – France 2.**

Predicted scorers: Mbappé.

```json
{
  "predicted_score": { "self": 0, "opponent": 2 },
  "win_probability": 0.14,
  "draw_probability": 0.26,
  "loss_probability": 0.60,
  "key_factors": ["Haaland benched — Norway's attacking system loses its only world-class threat", "Mbappé Golden Boot race (tied at 4 goals) guarantees attacking intent from France", "Norway ~10 rotations structurally outclassed vs France's first-choice attack", "Tournament calibration: 2-0 favoured for one-sided contests; draw at base rate 0.26"],
  "confidence": "medium",
  "predicted_scorers": ["Mbappé"]
}
```

## Turn 6 — Les Bleus AI Pundit (FRA) — `final_prediction`

My scorecard shows two correct winners and patterns, one exact score (Iraq 3–0), and the one under-prediction from this tournament was France scoring 3 against Senegal when I said 2 — but that was against a full-strength side with a genuine defensive threat. With Norway resting approximately ten players including Haaland, the dynamic flips: their attacking system loses its only world-class threat, and France's incentive structure (Mbappé tied in the Golden Boot race) guarantees attacking intent from the off. My draw probability sits at 0.22, marginally below the 26.7% base rate, but the structural imbalance here is the largest I've faced in this tournament — I'm comfortable holding that slight draw discount rather than forcing it to baseline. **My final call is Les Bleus 2 – Norway 0.**

Predicted scorers: Mbappé, Dembélé.

```json
{
  "predicted_score": { "self": 2, "opponent": 0 },
  "win_probability": 0.68,
  "draw_probability": 0.22,
  "loss_probability": 0.10,
  "key_factors": [
    "Haaland benched — Norway's entire attacking focal point removed",
    "Norway resting ~10 players; rotated squad structurally outclassed",
    "Mbappé Golden Boot race (tied at 4 goals) guarantees attacking start against depleted XI",
    "Tournament calibration: 2-0 favoured for one-sided contests; prior under-prediction corrected upward"
  ],
  "confidence": "medium",
  "predicted_scorers": ["Mbappé", "Dembélé"]
}
```

## Final Predictions

| | The Lions pundit | Les Bleus pundit |
|---|---|---|
| Predicted score | 0–2 | 0–2 |
| The Lions win | 14% | 10% |
| Draw | 26% | 22% |
| Les Bleus win | 60% | 68% |
| Confidence | medium | medium |
| Consensus | ✅ Yes | |
