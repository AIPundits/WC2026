# Post-match Recap: Norway (NOR) vs Senegal (SEN)

**Fixture:** 043 — 2026-06-22
**Total cost:** $0.0977

## NOR AI Pundit

Got the winner, got both predicted scorers, and the basic dynamic — Senegal's pace in transition earning them goals while Norway's quality edge held — played out exactly as reasoned. The part I missed was scale: predicting 2-1 in what turned into a 3-2 thriller means I was too conservative on both teams' attacking output against Senegal's leaky defence. I noted in my rebuttal that Senegal's defensive fragility under France was the key vulnerability, and Haaland duly exploited it *twice* — yet I still capped Norway at two and Senegal at one, which contradicts my own analysis. The one thing I'd revise: once I had identified that Senegal conceded three to France and that their back four had clear structural issues, I should have pushed the goal expectancy up to at least 3-4 total rather than anchoring on a tidy 2-1.

```json
{
  "got_right": ["Norway win", "Haaland as scorer (doubled up)", "Sarr as Senegal's attacking threat (scored twice)", "Senegal desperation opening transition space"],
  "got_wrong": ["Underestimated total goals on both sides", "Capped Senegal at one goal despite identifying their genuine attacking quality", "Underestimated Norway's attacking output despite my own Round 1 evidence of profligacy"],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "Having identified Senegal's defensive structural fragility against France, I should have pushed total expected goals up to 4-5 rather than anchoring on a conservative 2-1 margin that contradicted my own analysis."
}
```

## SEN AI Pundit

The result direction was correct and the core reasoning held — Haaland scored (twice, not once), Sarr scored (twice, not once, which I'd flagged as Senegal's attacking threat), and the must-win pressure on the Lions of Teranga did exactly what I said it would: forced them open, created space, and gave Norway's counter-attack a highway. What I underestimated was the *volume* — 2-3 rather than 1-2 — and that's a calibration miss, not a structural one; I knew both sides could score, I just didn't push the goal expectation high enough given Norway's 4-0 Round 1 demolition and the tactical inevitability of an open, end-to-end game. Pedersen's goal was the detail I missed entirely — I was so focused on Haaland as the decisive outlet that I discounted Norway's other attacking contributors in a match where Senegal were committed forward. One specific change: I should have weighted Norway's total goal threat more systematically — not just through Haaland but through the width and secondary runners — and bumped the over-2.5-goals probability significantly given the match conditions I'd already correctly identified.

```json
{
  "got_right": ["Norway winning the match", "Haaland scoring", "Sarr scoring", "Senegal must-win pressure forcing open play that benefited Norway's counter-attack"],
  "got_wrong": ["Underestimated total goal volume (predicted 1-2, actual 2-3)", "Missed Pedersen as a goal threat — over-indexed on Haaland as sole Norway outlet", "Underestimated Sarr's ability to contribute twice despite the losing context"],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "I would have pushed the expected goal total higher — my structural analysis correctly identified an open, end-to-end game, but I didn't follow that logic through to a 5-goal scoreline, which was the natural consequence of the conditions I'd already correctly described."
}
```
