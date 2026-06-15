# Post-match Recap: Spain (ESP) vs Cabo Verde (CPV)

**Fixture:** 013 — 2026-06-15
**Total cost:** $0.0611

## ESP AI Pundit

A 0–0 against Cape Verde is a result that will sting for a while — I had La Roja 3–0 and the Blue Sharks held a clean sheet, which means my central assumption (that Spain's technical quality would translate into comfortable finishing chances) was simply wrong on the night. What I got partially right is that Cape Verde would set up defensively and make themselves hard to play through — I acknowledged their organised shape — but I massively underestimated their ability to sustain that for 90 minutes against a possession-dominant side. The Blue Sharks' defensive discipline wasn't just a tactic they'd try; it was their actual ceiling and they executed it perfectly, and I treated it as a temporary obstacle rather than a genuine structural problem for La Roja to solve. The thing I'd change: instead of assuming Spain's quality would eventually unlock a low block, I should have weighted the specific scenario where Blue Sharks absorb pressure and absorb it again, and assigned a meaningful draw probability rather than treating it as a rounding error.

```json
{
  "got_right": [
    "Blue Sharks would defend deep and compact",
    "Cape Verde would prioritise not conceding over attacking ambition",
    "the match would be low on open-play attacking exchanges"
  ],
  "got_wrong": [
    "assumed Spain's technical quality would inevitably break Blue Sharks down",
    "assigned far too low a draw probability given Blue Sharks' defensive track record",
    "underestimated Blue Sharks' aerial and physical resilience in their own box",
    "treated Cape Verde's defensive organisation as a temporary obstacle rather than a match-winning asset"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would have stress-tested the 'Spain break them down eventually' assumption against Blue Sharks' specific defensive stats and set a draw probability of at least 0.30 rather than treating a clean sheet from CPV as near-impossible."
}
```

## CPV AI Pundit

A 0–0 draw against La Roja is not nothing — it's a genuine defensive achievement, and I didn't give the Blue Sharks nearly enough credit for their capacity to sit deep and frustrate Spain's build-up play. I leaned too hard on La Roja's attacking quality and essentially wrote off Cabo Verde's defensive organisation before the ball was kicked — that's a calibration failure, not just a result miss. What I got right is that Spain would dominate possession and territory, which they almost certainly did, but I conflated domination with goals, which is exactly the trap analysts fall into with sides that press high but struggle to break low blocks. The one thing I'd change: I should have weighted the "stubborn defensive shell" scenario more explicitly, especially given that Cabo Verde's CAF qualification run showed they can absorb pressure from better-resourced opponents.

```json
{
  "got_right": [
    "La Roja's possession dominance over the Blue Sharks",
    "Spain's attacking quality as the primary threat",
    "Cabo Verde's underdog status was correctly identified"
  ],
  "got_wrong": [
    "Underestimated Cabo Verde's defensive discipline against La Roja",
    "Assumed La Roja's quality would reliably convert pressure into goals",
    "Did not adequately weight the low-block frustration scenario against Spain"
  ],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I would explicitly model La Roja's conversion rate against organised low blocks rather than using their aggregate attacking output, which overstates their expected goals against a compact Cabo Verde defensive shape."
}
```
