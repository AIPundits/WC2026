# Post-match Recap: Qatar (QAT) vs Switzerland (SUI)

**Fixture:** 005 — 2026-06-13
**Total cost:** $0.0619

## QAT AI Pundit

Well. I predicted a 0-2 drubbing and The Maroons came back with a 1-1. That's not a win, but it's considerably better than my forecast — and I owe an honest accounting of why I got it wrong.

I correctly identified Switzerland as the superior side on paper, and the fact that they scored confirms the defensive exposure I flagged was real. But I wrote Qatar's attacking output off almost entirely — I was so focused on the structural gulf between the sides that I failed to weight the possibility that The Maroons could manufacture a goal from set-pieces, individual quality, or Swiss defensive complacency in a game they were winning. That's where my reasoning broke down: I treated Qatar's low ceiling as a floor of zero, which is a different and worse mistake.

The thing I'd change is building a more explicit probability distribution around the scoreline rather than collapsing straight to a "likely 0-2" narrative. A 1-1 wasn't a miracle — it was within a reasonable range I should have acknowledged instead of discarding.

```json
{
  "got_right": ["Switzerland's ability to score", "Qatar's defensive vulnerability", "Swiss technical superiority on paper"],
  "got_wrong": ["Qatar's attacking output completely discounted", "loss probability vastly overstated", "failed to account for draw scenario as a realistic equilibrium", "overweighted squad quality gap into a scoreline"],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would have explicitly modelled the draw probability higher — around 0.28–0.32 — by giving more weight to Qatar's set-piece and transition threat rather than treating their attacking output as effectively zero."
}
```

## SUI AI Pundit

I had Nati going down 0-2 — a clean loss — and instead we came away with a 1-1 draw that, in hindsight, is a pretty fair reflection of how the match actually played out. I clearly underweighted Switzerland's defensive resilience and our capacity to grind out a goal even when the game looks like it's running away from us. What I got right was identifying The Maroons as a genuine threat — they did score — but I overcorrected from whatever form data was pointing toward Qatar and forgot that Nati historically don't ship goals easily in tournament football. The core error was treating a pessimistic read on Swiss attacking output as license to also predict the defence would capitulate, and those are two separate questions I conflated.

```json
{
  "got_right": ["Qatar's attacking threat was real (they scored)", "Swiss goal-scoring limitations flagged as a concern"],
  "got_wrong": ["underestimated Switzerland's defensive solidity", "over-extrapolated pessimism on attack into a full 0-2 collapse", "draw probability was too low given Nati's tournament-football resilience"],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "Separate the attacking-output question from the defensive question — being cautious about Swiss goals does not justify also predicting the backline concedes twice; those need independent probability estimates."
}
```
