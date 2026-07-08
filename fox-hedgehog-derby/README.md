# Fox & Hedgehog Derby

**Live:** https://mxtdnl.github.io/forecasting-tools/fox-hedgehog-derby/

**Intended standalone home (pending repository creation):** https://github.com/mxtdnl/fox-hedgehog-derby with Pages at https://mxtdnl.github.io/fox-hedgehog-derby/

An interactive classroom simulation on cognitive style and forecasting accuracy (foxes vs hedgehogs), built
as a single self-contained HTML file with no external dependencies. Four modules: (A) a twelve-question
forecasting tournament set in the fictional region of Veridia, raced against a Hedgehog bot (one big theory,
extremised) and a Fox bot (averages all drivers, moderates toward 50%), with a dart-throwing-chimp baseline;
(B) a Fame Meter that pays TV bookings for extremity and emphatic soundbites, ending in a fame-vs-accuracy
scatter; (C) a short interactive reading of the Soviet-collapse natural experiment; (D) a team-building
finale where hypothesis generation (hedgehog-scaled) and judgement/revision (fox-scaled) multiply, so mixed
teams beat pure ones.

## Purpose

To teach three points: aggregate expert forecasting was close to chance, but cognitive style split
performance; confident single-model forecasting earns fame and loses accuracy; and the mature lesson is
complementarity — hedgehogs generate bold hypotheses, foxes judge and revise them.

## Sources

- Tetlock, P. (2005), *Expert Political Judgment*, Princeton UP (≈28,000 forecasts, 284 experts; chs. 3–4).
- Tetlock, P. & Gardner, D. (2015), *Superforecasting*, ch. 10.
- Berlin, I. (1953), *The Hedgehog and the Fox* (Archilochus: "the fox knows many things, but the hedgehog
  knows one big thing").

## Instructor guide

Allow 25–30 minutes. Set a shared seed (top right) so the whole class forecasts the same twelve questions;
the intelligence briefs show each desk's model output, so students can consciously choose a strategy —
extremise one favoured driver, or average all three — and the race chart makes the consequence visible
immediately. Calibration (recorded as a code comment in `index.html`): across 60 seeds the Fox bot's mean
Brier is 0.177 vs the Hedgehog's 0.231, and the flat-50% chimp beats the Hedgehog on 35% of seeds —
reproducing Tetlock's "barely beats a chimp" aggregate without making the hedgehog a strawman. Useful debrief
questions: who beat the Fox bot, and how; who collected the most TV bookings, and what did it cost them; and
why the winning team in Module D is never all-fox. Students paste their "Copy results" summaries into Zoom
chat for comparison; passive click-through play lands in the middle grade band by design.
