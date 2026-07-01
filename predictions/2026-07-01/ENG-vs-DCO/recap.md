# Post-match Recap: England (ENG) vs DR Congo (DCO)

**Fixture:** 080 — 2026-07-01
**Total cost:** $0.1165

## ENG AI Pundit

The scoreline landed exactly where I called it — Three Lions 2–1 Léopards — and the key structural arguments held: England's quality was decisive, the knockout dynamic forced DR Congo to commit forward and they paid for it, and Rice's return provided the midfield platform the Ghana match lacked. Kane scoring was the most predictable piece of the whole thing, and I had that right. Where I was wrong: I flagged Wissa through the Spence channel as the primary DCO counter-attack threat, but it was Cipenga — not Wissa — who got the goal, which suggests the specific tactical route I identified either didn't materialise or wasn't the real danger point. I also called Bellingham as a scorer, and without confirmation he got one of England's goals that remains an open miss.

```json
{
  "got_right": [
    "Scoreline: Three Lions 2–1 Léopards in regulation",
    "Kane scoring — identified as England's most reliable threat",
    "DR Congo scoring once — knockout dynamic forcing them forward, creating a vulnerability",
    "England winning in ninety minutes — draw probability at 0.28 reflected genuine uncertainty without triggering a different result call"
  ],
  "got_wrong": [
    "Wissa as the DCO goalscorer — it was Cipenga, not Wissa through the right-back channel",
    "Bellingham as a scorer — no confirmation he found the net",
    "Specific right-back channel threat via Wissa may have been overstated as the primary DCO route"
  ],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "I over-specified Wissa as the DCO goal threat — I should have distributed scorer probability across multiple DCO attackers rather than anchoring so heavily on one channel."
}
```

## DCO AI Pundit

The result landed exactly as called — **Léopards 1 – Three Lions 2**, one-goal margin, England's quality ultimately telling — and the broad reasoning framework held up: DCO were competitive throughout, never fragile, and the knockout dynamic eventually created the space England exploited. What I got wrong on the detail: I was so fixated on the Wissa-vs-Spence counter-attack channel as the DCO goal route that I listed Wissa as the scorer, but it was Cipenga who found the net, suggesting the goal came from a different source entirely — I over-indexed on one mechanism while the Léopards actually scored through a different avenue. On England's side, I predicted both Kane and Bellingham on the scoresheet, but only Kane appears in the result; Bellingham either didn't contribute a goal or my confidence in his goal threat was misplaced for this particular match. The scoreline prediction was sound, the scorer predictions were 1-for-3.

```json
{
  "got_right": [
    "Exact scoreline — Léopards 1–2 Three Lions",
    "One-goal margin call — England quality telling but not a comfortable cruise",
    "Kane on the scoresheet for Three Lions",
    "DCO defensive credibility — never conceded more than one goal, consistent with prior tournament pattern"
  ],
  "got_wrong": [
    "Wissa as DCO scorer — it was Cipenga, not Wissa, who found the net",
    "Bellingham as second English scorer — Kane scored but Bellingham did not",
    "Wissa-vs-Spence counter-attack as the primary DCO goal mechanism — evidently not how the goal came"
  ],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "I over-committed to Wissa as the sole DCO goal threat and should have acknowledged Cipenga and other central options as credible scorer candidates alongside him, rather than tying the whole DCO attacking narrative to a single channel."
}
```
