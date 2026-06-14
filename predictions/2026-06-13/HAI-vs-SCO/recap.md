# Post-match Recap: Haiti (HAI) vs Scotland (SCO)

**Fixture:** 007 — 2026-06-13
**Total cost:** $0.0600

## HAI AI Pundit

Got the direction right — Haiti were the underdogs and the result confirms it. But I overstated Scotland's attacking potency, calling a 0-2 when the final whistle came at 0-1. That one-goal difference actually hints at something I underweighted: Les Grenadiers' defensive discipline. I predicted their backline would be breached twice based on Scotland's set-piece threat and attacking volume, and that didn't materialise. The second goal I invented in my reasoning never came — credit to Haiti's organisation, and a small rebuke to my threat-assessment of Scotland's attack.

The core logic — Haiti struggle to create and Scotland win through structure, not flair — held up. Where I went wrong was treating Scotland's goal-threat as closer to a 2.0 xG side than closer to 1.0. That's not a vibe error; it's a calibration error I can fix.

```json
{
  "got_right": ["Haiti would not score", "Scotland would win", "Haiti as clear underdogs", "result decided by a single defensive lapse"],
  "got_wrong": ["overestimated Scotland's attacking volume (predicted 2, got 1)", "underweighted Haiti's defensive resilience", "second goal never materialised despite my reasoning treating it as likely"],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would weight Haiti's recent defensive organisation more carefully against Scotland's actual chance-creation data, rather than defaulting to a 2-goal margin just because Scotland are the stronger side."
}
```

## SCO AI Pundit

Well. I predicted we'd lose 0-2 to Haiti, and Scotland went and won 1-0. I'll take the win — but I won't pretend the prediction was anything other than wrong.

I leaned too hard into Scotland's historical fragility in tournament openers and seemingly underweighted the quality gap between a UEFA side with World Cup experience and a Haitian squad making only their second-ever World Cup appearance. Whatever I cited about our defensive vulnerabilities clearly didn't account for the fact that Haiti's attacking threat was limited enough to make a clean sheet achievable. The 1-0 scoreline — grinding, narrow, probably tense — is very Scottish, and I should have recognised that as a plausible ceiling rather than discounting it. What I got right, presumably, was flagging it as a close, low-scoring match in structure; what I got catastrophically wrong was the direction of the result.

```json
{
  "got_right": ["low-scoring match structure", "game likely to be tight and contested"],
  "got_wrong": ["direction of result — predicted loss, Scotland won", "overestimated Haiti's attacking threat", "underestimated Scotland's defensive organisation", "too pessimistic about Scotland's ability to grind out a result"],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "Weight the head-to-head quality gap more explicitly — when Scotland face a team outside UEFA/CONMEBOL with limited World Cup pedigree, the base rate for a narrow Scotland win is higher than I credited."
}
```
