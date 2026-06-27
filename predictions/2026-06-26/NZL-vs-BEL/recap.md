# Post-match Recap: New Zealand (NZL) vs Belgium (BEL)

**Fixture:** 066 — 2026-06-26
**Total cost:** $0.1048

## NZL AI Pundit

I got the direction right and the All Whites goal tally right — Elijah Just's strike was exactly the kind of set-piece-adjacent moment I'd flagged as the most realistic NZL contribution — but I was badly anchored on Belgium's two-game scoring drought. My reasoning treated "Belgium have only scored once in 180 minutes" as a structural ceiling rather than a context-specific suppression caused by Beiranvand and a man disadvantage. Against a defence that concedes 2.5 per game, Trossard, De Bruyne, and Saelemaekers ran riot, and the 1–5 scoreline is the kind of result that in hindsight was sitting right there in the data: NZL's defensive record plus Belgium's quality gap. I held Belgium to 2 goals because of their fitness concerns; De Bruyne scoring and Trossard bagging a brace tells you those concerns were overstated, or at least not enough to cap Belgium's output against this level of opposition.

The one thing I'd change: stop treating a team's scoring form against quality opponents as directly predictive against structurally weaker ones. Belgium's blankness against Iran and Egypt is a different data point to Belgium facing NZL's backline — I noted the distinction but didn't let it move my predicted scoreline far enough.

```json
{
  "got_right": [
    "All Whites losing the match",
    "All Whites scoring exactly 1 goal",
    "Belgium's attacking quality being the decisive factor",
    "NZL's porous defence (2.5 conceded/game) correctly identified as the structural vulnerability"
  ],
  "got_wrong": [
    "Capped Belgium at 2 goals — they scored 5",
    "Over-weighted Belgium's pre-match scoring drought as a ceiling rather than a context-specific suppression",
    "Lukaku and Doku as predicted scorers — Trossard (x2), De Bruyne, and Saelemaekers did the damage",
    "Fitness concerns for De Bruyne understated — he scored and clearly played a full part"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would separate Belgium's goal drought against high-quality keepers and strong opponents from their expected output against NZL's defence specifically — the same reasoning that flagged the quality gap should have pushed my Belgium goals prediction to 3 or 4, not kept it anchored at 2."
}
```

## BEL AI Pundit

I got the direction right — the quality gap was real, NZL conceded exactly as their defensive record suggested, and the one NZL goal I'd priced in duly arrived — but I badly capped the ceiling. I cited Lukaku and De Bruyne's fitness as a hard limit on Belgium's output, and De Bruyne went and scored anyway; the Red Devils put five past the All Whites while I was carefully hedging around two. The predicted scorers I named — Lukaku, Doku, Surman — didn't appear on the scoresheet at all, with Trossard's brace and Saelemaekers leading the charge instead, which tells me my attacking model was right in aggregate but wrong in its specific mechanism. Honest verdict: the structural reasoning about NZL's porousness was sound, but I let fitness-concern noise pull the goal tally down by three.

```json
{
  "got_right": [
    "Belgium win — quality gap against a porous NZL side was decisive",
    "NZL conceding multiple goals consistent with their 2.5 goals-per-game rate",
    "NZL scoring once — Elijah Just's goal matched the set-piece vulnerability I flagged"
  ],
  "got_wrong": [
    "Capped Belgium at 2 goals due to Lukaku and De Bruyne fitness concerns — De Bruyne scored and the team hit five",
    "Predicted scorers (Lukaku, Doku, Surman) were all wrong — Trossard and Saelemaekers led the line",
    "Significantly underestimated Belgium's attacking output once NZL's defensive block collapsed"
  ],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I would not treat sub-fit squad reports as a hard ceiling on goal output — when the opponent is structurally unable to defend, depth of squad quality fills the gap and fitness noise becomes much less predictive of the final scoreline."
}
```
