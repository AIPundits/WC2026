# Post-match Recap: Canada (CAN) vs Qatar (QAT)

**Fixture:** 027 — 2026-06-18
**Total cost:** $0.1457

## CAN AI Pundit

I got the winner right and correctly identified that The Maroons' open-play attacking output was severely limited — their 6-0 capitulation confirms they had no route back once Canada took control, exactly as the quality gap suggested. But I badly underestimated the *scale* of that gap: I predicted 2-1 and worried about clean sheets based on my scorecard calibration, when in reality The Maroons' defence was not just beatable but historically leaky — conceding six, including a Jonathan David hat-trick and an own goal, is a total structural collapse, not a one-goal set-piece concession. My calibration adjustment (respecting Qatar's set-piece and Afif counter-attack threats more) was technically reasonable given the evidence available, but it overcorrected — The Maroons' defensive fragility against a direct, physical Canada attack was far worse than anything their Switzerland draw suggested. The scorecard lesson here is the opposite of Round 1: against significantly weaker opposition, I need to be less afraid of the clean-sheet prediction and more willing to back the quality gap to produce a margin, not just a narrow win.

```json
{
  "got_right": ["Canada win", "Larin and David as primary goal threats", "The Maroons' limited open-play attacking output", "quality gap was decisive"],
  "got_wrong": ["massively underestimated the scoring margin", "overweighted The Maroons' set-piece and defensive resilience based on Switzerland draw", "Afif counter-attack threat was never materialised", "scorecard over-correction led to excessive caution on scoreline"],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I would discard The Maroons' 1-1 draw with Switzerland as evidence of defensive solidity and instead weight the underlying quality gap more heavily — a deflected-header equaliser in stoppage time is not a sign of a backline capable of handling a David-Larin partnership for 90 minutes."
}
```

## QAT AI Pundit

I correctly identified that Les Rouges would win and that the Larin-David partnership was the central attacking threat — David's hat-trick and Larin's goal vindicated both those calls entirely. What I got catastrophically wrong was the margin: I predicted Les Rouges would score twice, they scored six, and that gap isn't noise — it reflects a fundamental failure to model how completely Canada's attacking unit could dismantle Qatar's low-block once it was breached. I flagged Les Rouges' quality edge but framed it as a "2-1 type of game," which in hindsight was anchored too heavily on Qatar's disciplined display against Switzerland rather than asking how badly that same structure could unravel under sustained, higher-quality pressure. The own goal from Manai is also a reminder that Les Rouges' set-piece and crossing delivery was a threat I acknowledged in reverse — for Qatar going forward — but failed to weight seriously enough in the direction Canada were actually delivering it.

```json
{
  "got_right": ["Les Rouges winning the match", "Larin-David partnership as the primary attacking mechanism", "Jonathan David as a goal threat", "Canada's overall quality superiority over Qatar"],
  "got_wrong": ["completely underestimated Les Rouges' winning margin", "failed to model how badly Qatar's low-block would collapse under sustained Canada pressure", "Les Rouges' ability to score 6 not remotely considered", "Canada's set-piece and crossing threat in attack underweighted"],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would stress-test the catastrophic loss scenario more explicitly — asking not just whether Les Rouges would win, but how badly Qatar's defensive structure could disintegrate against a David-Larin partnership with full home support, rather than anchoring on a tight scoreline based on Qatar's single disciplined display against a different opponent."
}
```
