# Post-match Recap: South Africa (RSA) vs Canada (CAN)

**Fixture:** 073 — 2026-06-28
**Total cost:** $0.0994

## RSA AI Pundit

The result direction — Canada winning in regulation — was exactly what the pre-match evidence pointed to, and the reasoning holds up: Davies' return transformed Canada's left flank, David was the primary threat as predicted, and Zwane's absence truly did cap RSA's creative ceiling to near-zero. What I got wrong was the counter-attack goal I assigned to Maseko; in practice, Canada's press was disciplined enough that Bafana Bafana couldn't manufacture even a single clear break, and I over-credited RSA's ability to nick one in transition against a side with Canada's defensive organisation. I also over-estimated Canada's goal output — the 0–1 scoreline tells you this was a tight, controlled match, not the two-goal Canada performance I projected. The calibration note about consistently under-predicting RSA ironically led me to hold a *higher* RSA win probability than the evidence supported, even as I correctly called the loss.

```json
{
  "got_right": [
    "Canada winning in regulation — the result direction was correct",
    "Zwane's suspension severely limiting RSA's creative output",
    "Davies' return as the most significant personnel factor of the match",
    "David identified as Canada's primary scoring threat"
  ],
  "got_wrong": [
    "Predicted RSA would score via Maseko counter-attack — RSA were shut out entirely",
    "Predicted Canada would score twice — Canada managed only one, the match was tighter than a 2-goal margin suggests",
    "Over-credited RSA's ability to break on the counter against Canada's defensive press"
  ],
  "reasoning_verdict": "fortunate",
  "one_thing_id_change": "I would have weighted Canada's defensive press more heavily against RSA's counter-attack threat — if Canada can nullify Maseko's transition runs (which their high-press system is specifically designed to do), the Maseko goal probability drops sharply and the 0-1 scoreline becomes the more likely outcome than 1-2."
}
```

## CAN AI Pundit

The result is correct but the scoresheet tells a slightly humbling story: I had Canada scoring twice and conceding once, the actual match delivered a single goal and a clean sheet. The right directional call was there — Davies' return genuinely did confront Broos' right side with a problem they hadn't prepared for, and that unlocking role proved decisive — but I over-trusted Canada's goals-against profile and under-trusted RSA's defensive resolve to sustain a clean sheet even against Davies at close to full sharpness. The Ronwen Williams form note I acknowledged in my rebuttal turned out to be load-bearing: he kept Bafana Bafana in it for long enough that Les Rouges had to grind out the single goal rather than find a second. I also had Maseko as a goal threat who would land a counter — that never materialised, which in hindsight reflects how well Canada managed their defensive shape once ahead.

```json
{
  "got_right": [
    "Canada win in regulation — correct directional call",
    "Davies' return created a qualitatively new problem for RSA's right side",
    "RSA's defensive discipline would make at least one goal difficult for Canada"
  ],
  "got_wrong": [
    "Predicted Canada score 2 — they scored only 1",
    "Predicted RSA would score via Maseko counter-attack — Canada kept a clean sheet",
    "Over-estimated Canada's true goal output; Qatar blowout discount wasn't applied sharply enough"
  ],
  "reasoning_verdict": "sound",
  "one_thing_id_change": "I would have weighted Ronwen Williams' in-tournament shot-stopping form more heavily as a downward pressure on Canada's expected goals, rather than briefly acknowledging it and leaving the 2-goal prediction unchanged."
}
```
