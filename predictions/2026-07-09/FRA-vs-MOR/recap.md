# Post-match Recap: France (FRA) vs Morocco (MOR)

**Fixture:** 097 — 2026-07-09
**Total cost:** $0.1083

## FRA AI Pundit

The football gods have a sense of irony: my opening statement said **Les Bleus 2 – Morocco 0**, my rebuttal held at 2-0, and then in the final turn I let the Morocco pundit's Brazil argument talk me into conceding a Morocco goal — and they didn't get one. The clean sheet I had right from the start was correct; I abandoned it based on a reference point (Morocco scoring against Brazil) that ultimately didn't translate against France's defensive structure. Mbappé and Dembélé both scored, which I called in every single turn, and the overall read on Morocco's attacking limitations — Saibari out, Hakimi constrained, grinding rather than opening up — proved entirely accurate. The one element that looked risky, Tchouaméni's fitness, clearly didn't derail France's defensive organisation in the way I'd flagged.

```json
{
  "got_right": [
    "France win in regulation — no extra time required",
    "Mbappé and Dembélé as scorers — both named in every prediction turn",
    "Morocco's attacking limitations: Saibari absence, Hakimi constrained by yellow card, grinding style",
    "France's defensive superiority over Morocco's attacking output"
  ],
  "got_wrong": [
    "Abandoned clean sheet in final prediction after being moved by the Morocco-vs-Brazil reference point",
    "Ounahi threat in midfield space — cited as key risk, did not materialise",
    "Morocco's probability of scoring given their tournament evidence against elite opposition was overstated"
  ],
  "reasoning_verdict": "underconfident",
  "one_thing_id_change": "I would not have revised off the 2-0 clean sheet in the final turn — the Morocco vs Brazil data point was a weaker reference than I gave it credit for, and my own earlier reasoning about France's 0.4 conceded/game superiority over Netherlands and Brazil's defences was the more relevant evidence I should have held firm on."
}
```

## MOR AI Pundit

I got the result right — France win, narrow margin, no extra time needed — and I correctly identified their defensive quality as the dominant factor in this match. Mbappé and Dembélé scoring is exactly the kind of attacking output France's tournament form projected. Where I was wrong is the part I argued most confidently: I cited Morocco's goal against Brazil in regulation as evidence the Atlas Lions had genuine attacking quality against elite defences, and then built my entire goal prediction on that premise — Ounahi exploiting Tchouaméni's absence, multiple attacking routes through El Khannouss and Rahimi. France's back line shut all of it down. Morocco had a chance but couldn't convert; the 0.4 conceded/game wasn't noise, it was signal, and I didn't weight it heavily enough against my own team's output. My scorecard told me I'd been under-predicting Morocco goals — I used that to nudge upward, which turned out to be the wrong adjustment for this specific opponent.

```json
{
  "got_right": [
    "France winning the match — result direction correct",
    "No extra time required — France's quality sufficient to settle in 90 minutes",
    "France's defensive record (0.4 conceded/game) identified as the dominant structural factor",
    "Mbappé and Dembélé as attacking threats — France's forward line delivered on form"
  ],
  "got_wrong": [
    "Predicted Atlas Lions would score once — Morocco were kept to zero",
    "Ounahi threat exploiting Tchouaméni absence — France defended the space regardless",
    "Morocco's goal against Brazil used as evidence of scoring capacity against elite defences — did not transfer to this fixture",
    "Scorecard-driven upward adjustment on Morocco goals was the wrong calibration for this opponent"
  ],
  "reasoning_verdict": "overconfident",
  "one_thing_id_change": "I would weight France's 0.4 conceded/game and three clean sheets more heavily than Morocco's historical output against other elite sides — past scoring against Brazil does not transfer automatically, and the strength of France's specific defensive unit warranted a higher probability on Atlas Lions 0 goals."
}
```
