# Health Flag — Illness in Race Week

**Date logged:** 2026-09-22 | Race: Ealing Half Marathon, Sun 2026-09-27 (5 days out)

## What happened

Josh reports fever and chest symptoms starting roughly mid-week of Sep 14-20, still not fully recovered as of Sep 22 (took Mon Sep 21 off work). Garmin data confirms the timeline:

- **Sep 17:** HRV crashed to 34ms overnight (baseline 130-160ms) — sharpest single-night drop of the build. Resting HR spiked to 54bpm.
- **Sep 18-19:** Body battery bottomed out (0% charged Sep 18, VERY_LOW through Sep 19). Worst 2-day stretch in the data.
- **Sep 20-21:** Recovery visible — body battery LOW then HIGH, big sleep + nap + long rest periods on Sep 21 (the sick day off work).
- **Sep 22:** Resting HR back to 42bpm (normal/good for Josh), weekly HRV average back to 54ms (BALANCED band). Training readiness MODERATE (53/100), driven by poor sleep history, not current HRV/recovery. Josh says he's "a lot better than yesterday" but not fully well.

## Why this needed a direct question, not a Garmin-only judgment

Garmin's HRV/RHR/body-battery metrics look encouraging by Sep 22, but they don't reliably indicate whether the post-viral myocarditis risk window (standard guidance: no exertion until 24-48h fever-free) has closed. Asked Josh directly; confirmed fever/chest symptoms were involved, and the "better than yesterday" answer didn't clearly confirm a full 24-48h fever-free window. Applied the standard rule rather than the Garmin readiness score to decide whether running was appropriate on Sep 22.

## Decision applied

Held Josh off running on Sep 22 despite him wanting to go out, pending a clearer fever-free confirmation. Full day-by-day plan and reasoning in `training/2026-09-21-week.md`. This is the illness-equivalent of the plan's #1 joint-pain rule (stop, no negotiation) — applied to a systemic illness for the first time this build.

## What to watch going forward

- If any chest tightness, dizziness, or unusually high HR-for-effort shows up on the first test run, stop immediately and treat as still recovering — don't push to "get one more day in" this close to race day.
- Race day goal has been reframed: A (sub-1:40) and B (1:42) are off the table for this race given zero taper running plus illness. Goal C (finish injury/illness-free, well-paced) is now the only goal — consistent with the dossier's own stated priority when goals conflict.

---

## Update — Fri 2026-09-25 (2 days out)

**Josh's report:** legs stretched out and feeling much better. **Chest is the only remaining symptom.** No mention of fever — treating the fever as resolved. Sleeping long, eating plenty of carbs.

**Objective markers all point away from active illness:**

| Marker | Sep 17 (illness peak) | Sep 22 | **Sep 25** |
|---|---|---|---|
| HRV (last night / weekly) | 34ms | — / 54ms | **71ms / 72ms, BALANCED** |
| Resting HR | 54 | 42 | **43** |
| Respiration (sleep / waking) | — | — | **14 / 13, range 8–20 — normal** |
| Training readiness | — | 53 MODERATE | **66 MODERATE** |
| Training status | — | DETRAINING | **RECOVERY** |

Respiration rate is the most useful new number for a chest complaint and it is completely flat — no elevation asleep or awake. Combined with RHR at his 43 baseline, HRV fully restored, and a normal HR-for-effort response on Wednesday's 1.78mi run (avg HR 128 at 10:35/mi), the acute infection has cleared.

**What is still unresolved, and it is the thing that decides the race:** which kind of chest symptom this is. Garmin cannot distinguish them.

- **Residual dry cough / congestion / rattly-on-coughing** → ordinary post-viral airway irritation, commonly lingers 2–3 weeks after the rest resolves. Not a contraindication to Sunday.
- **Tightness, pressure, pain, breathlessness disproportionate to effort, or palpitations** → the post-viral cardiac red flag this file was originally opened around. Not something to run through. No race, and a GP appointment.

Asked Josh directly rather than inferring it from the readiness score — same principle applied on Sep 22.

**Decision applied:** brought the test run forward to Friday (2.0mi max, HR ≤135, flat) and moved the complete rest day to Saturday, reversing the original Fri-rest / Sat-shakeout order. Rationale: there is no accumulated training fatigue for a Friday rest day to dissipate (acute load 25 vs chronic 219, ACWR 0.10), and running Friday leaves Saturday as reaction time if the chest behaves badly under load. Testing Saturday would leave none. Full reasoning in `training/2026-09-21-week.md`, Revision section.

**Sleep note:** Josh reported the watch cutting his sleep off at 3am. Nothing was lost — final sync recorded 00:22–08:54, 8h32m, awake time 0. The watch simply computed training readiness twice (03:44 off a partial night, sleep score 44, LOW 38; then 12:57 off the full night, sleep score 68, MODERATE 66). Worth recording because the early-morning readiness figure was misleadingly low and he may see that again.

However, duration is outrunning quality: REM was 25 min (5%, target 21–31%) and the night returned only +39 body battery versus +74 from a comparable 8.5hr night on Sep 22. Thursday night was 5h48m. Sleep history factor remains **39% POOR**. Deep sleep was excellent (19%). Direction of travel is right; the 7-day picture is still the weakest marker he has.

**Guardrail breach logged:** Sunday's 13.11mi race exceeds both ceilings by a wide margin — long-run ceiling 2.76mi (longest run in 3 weeks is 2.51mi), weekly ceiling 3.26mi. Flagged to Josh with reasons before the fact, per CLAUDE.md. Measured against the build's actual long-run peak (9.01mi on Aug 24, 9.00mi on Aug 31) it is +45%, which is the more honest read of joint risk than +422%. Mitigation is planned 9:1 walk-run from mile 1 rather than from mile 8.

**Update — Fri 2026-09-25, later:** Josh confirms the chest is "just a bit raspy" — no fever, no tightness/pressure/breathlessness/palpitations. That's the airway-irritation category, not the cardiac-flag category. **Cleared to race Sunday.** He wants to start steadier and build effort as he sees fit, rather than a fixed walk-run interval from mile 1 — see revised race-day approach in `training/2026-09-21-week.md`.
