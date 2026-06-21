# Post-match Recap: Belgium (BEL) vs Iran (IRI)

**Fixture:** 038 — 2026-06-21
**Total cost:** $0.0982

## BEL AI Pundit

A goalless draw against Team Melli is the football equivalent of being told you were right about the danger but completely wrong about the outcome — I flagged Iran's defensive discipline, their 4-5-1 shape, and the real risk of De Bruyne being crowded out, and then proceeded to predict Belgium would score twice anyway. The calibration adjustment I made at the final turn — pulling win probability down to 0.55 — wasn't nearly far enough; Iran didn't just hold Belgium, they shut them out entirely, which means Lukaku's introduction didn't deliver the structural transformation I staked the prediction on. What I got wrong most fundamentally was treating Iran's Round 1 defensive fragility against New Zealand as the dominant piece of evidence, when in fact Ghalenoei's team showed they could tighten up completely against higher-quality opposition — Belgium generated nothing, not a near-miss, not a penalty shout, zero. The one thing I'd change is weighting Belgium's own attacking record more heavily: a team that needed an own goal to draw with Egypt in Round 1 should not have had 0.55 win probability against another disciplined, low-block side.

```json
{
  "got_right": [
    "Iran's defensive discipline and 4-5-1 shape were correctly identified as the key tactical threat",
    "De Bruyne being stifled in tight spaces was flagged as a genuine risk",
    "The match being competitive rather than a comfortable Belgium win was correctly anticipated"
  ],
  "got_wrong": [
    "Overweighted Iran's Round 1 defensive fragility vs New Zealand — they tightened up completely against Belgium",
    "Assumed Lukaku starting would transform Belgium's attacking output — it didn't produce a single goal",
    "Underestimated Belgium's own attacking limitations against a deep, disciplined block",
    "Draw probability of 0.27 was far too low — this match had draw written all over it"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would have stress-tested Belgium's attacking record more rigorously — a team that required an own goal to draw with Egypt had no business carrying 0.55 win probability against another well-organised defensive side like Team Melli."
}
```

## IRI AI Pundit

The 0–0 scoreline is a clean repudiation of my central premise: I was right that Ghalenoei would deploy a defensive block against Belgium, and I was right that De Bruyne had struggled against that exact shape in Round 1 — but I didn't have the conviction to follow that logic all the way to "Belgium may not score at all." I weighted Lukaku's threat too heavily, assuming his introduction would break the deadlock that eluded Belgium against Egypt, and I underestimated Iran's defensive resilience despite the travel disruption I'd flagged myself. The one result I should have taken more seriously from my own analysis: if Belgium couldn't carve open Egypt's 4-5-1 without an own goal, there was a plausible world where they couldn't carve open Iran's either — and I assigned it only 25% probability rather than the larger share it deserved.

```json
{
  "got_right": [
    "Belgium's Round 1 struggles against a compact 4-5-1 shape were a genuine warning — De Bruyne was stifled again",
    "Iran's defensive block holding for long stretches was a credible tactical outcome",
    "The draw probability I identified as a mitigating factor turned out to be the correct result"
  ],
  "got_wrong": [
    "Lukaku starting was not the game-breaking upgrade I assumed — Belgium still couldn't convert",
    "Iran's defensive resilience held despite the travel/recovery disruption I flagged as a disadvantage",
    "Predicted Taremi would score on the counter — Iran produced no goal at all, not just from Taremi",
    "Overweighted Belgium's quality advantage translating into goals, underweighted Iran's organisational discipline"
  ],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I identified Belgium's Round 1 vulnerability to a 4-5-1 as a key factor but then failed to let it suppress my Belgian goal-scoring expectation enough — if I had applied that logic consistently, I'd have pushed draw probability to 35%+ rather than 25%."
}
```
