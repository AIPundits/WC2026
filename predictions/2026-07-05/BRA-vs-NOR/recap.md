# Post-match Recap: Brazil (BRA) vs Norway (NOR)

**Fixture:** 091 — 2026-07-05
**Total cost:** $0.1192

## BRA AI Pundit

The scoreline is the exact mirror of what I predicted — **Seleção 1–2 The Lions** where I had Seleção 2–1. I got Haaland scoring right, and I got "Norway score" right (the calibration adjustment held), but I had the whole result inverted. The structural argument I leaned on — Norway's leaky defence versus Brazil's prolific attack — simply didn't manifest: Seleção managed only one goal against a side I described as having "zero clean sheets," and The Lions found a second past a defence I called the tournament's best. The France blueprint I cited as the attacking template ended up being used against us rather than by us.

What I got badly wrong was dismissing the H2H signal too quickly. I called it "historical colour, not predictive data" — but four matches without a loss to Brazil is at minimum a warning I should have weighted more seriously, not rationalized away. My midfield injury concerns were valid, but I concluded they didn't erase the structural attacking advantage; in practice they appear to have hurt Brazil far more than I credited.

```json
{
  "got_right": [
    "Haaland scoring — retained him as a key threat throughout all three turns",
    "Norway finding the net — calibration adjustment to keep opponent scoring proved correct",
    "The margin being one goal — result settled by a single-goal difference"
  ],
  "got_wrong": [
    "Brazil winning — the result was the mirror image of my prediction",
    "Norway's defensive vulnerability — they held Seleção to one goal despite 'zero clean sheets' record",
    "Brazil's attacking output — 2.25 goals/game tournament average did not carry over against The Lions",
    "Dismissing the H2H signal — I called it decorative noise, but Norway's unbeaten record against Brazil was a genuine warning"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would have taken the H2H record more seriously as a structural signal rather than explaining it away, and weighted Brazil's midfield injury doubts as a more decisive suppressor of attacking output rather than a manageable downgrade."
}
```

## NOR AI Pundit

I got Haaland right — I said he'd convert one genuine chance against Marquinhos, and he did exactly that. What I got badly wrong is the rest of the picture: I called Brazil's defensive record the "dominant asymmetry," predicted their attack would do the damage our backline couldn't contain, and locked in a 1-2 loss with 53% probability on a Brazil win. Norway won 2-1. The Lions didn't just scrape a goal — they took the game, which means the midfield injury argument I made (Paqueta out, Casemiro uncertain) had a much larger effect on Brazil's attacking output than I credited, and Norway's own defensive improvement or Brazil's finishing let us down at the other end. The France 4-1 blueprint I kept citing turned out to be the wrong reference point — Vinicius and Rayan didn't replicate it.

```json
{
  "got_right": [
    "Haaland converting a genuine chance against Marquinhos — predicted him as scorer, he scored",
    "Brazil's midfield injury doubts (Paqueta out) as a structural weakness worth flagging",
    "Identified the match as genuinely uncertain, not a comfortable Brazil cruise"
  ],
  "got_wrong": [
    "Brazil's 0.5 goals conceded per game framed as the dominant asymmetry — Norway scored twice",
    "France 4-1 blueprint treated as the likely template — Brazil's wide attack did not replicate it",
    "Predicted loss for The Lions with 53% Brazil win probability — result was a Norway win",
    "Underestimated Norway's defensive resilience in a knockout elimination scenario"
  ],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I'd weight Brazil's attacking execution risk more heavily against a Norway side defending for their tournament lives, rather than assuming their group-stage defensive average would simply carry over against Haaland at peak form."
}
```
