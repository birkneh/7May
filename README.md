# HIP-SAFE 70 · Gym Edition

A ~75–85 minute hip-protective full-gym workout app you run from your phone's home screen. Hypertrophy bias (8–12 reps), machine-heavy, with set/rep/weight tracking and an automatic rest timer.

## What's in the app

- **5 phases · 16 exercises · 41 working sets** at typical pacing
- Per-set **weight + reps inputs**, persisted on your phone via `localStorage`
- **Auto rest timer** kicks in the second you check off a set (with beep when rest ends)
- **Last-session weights** shown as a hint under each exercise
- Time-based blocks (cardio, plank holds, stretches) auto-advance with audio cues
- **Demo video** button on every move (opens YouTube search — stable even if specific videos disappear)
- Progress bar: sets done and minutes done

## Hip safety rules baked in

- Leg press depth limited above 90° knee bend (no deep hip flexion under load).
- Heavy emphasis on **glute medius** (hip abduction machine) and hamstrings — these protect the hip joint.
- No squats, no lunges, no jumping, no rotation under heavy load.
- Symptomatic side: same volume, lighter weight if needed.
- Stop if pain rises above 3/10 — the safety banner is the first thing the app shows.

## The program

| Phase | Duration | Exercises |
|---|---|---|
| 1 · Warm-Up | ~10 min | Bike/elliptical 8 min, banded glute activation 2 min |
| 2 · Lower Body Machines | ~30 min | Leg press · Leg curl · Hip abduction · Hip adduction · Calf raise |
| 3 · Core Stability | ~12 min | Cable Pallof press · Wood chop · Plank holds |
| 4 · Upper Body Machines | ~25 min | Lat pulldown · Chest press · Cable row · Shoulder press · Lateral raise |
| 5 · Cooldown | ~8 min | Easy bike · Mat stretches |

## Run it on your phone via GitHub Pages

1. Create a new public repo (e.g. `hip-safe-70`).
2. Upload `index.html` to the repo root.
3. **Settings → Pages → Source: Deploy from branch → main / (root) → Save**.
4. Wait ~60 seconds. Your URL will be:
   ```
   https://<your-github-username>.github.io/hip-safe-70/
   ```
5. Open that URL on your phone:
   - **iPhone (Safari):** Share → *Add to Home Screen*
   - **Android (Chrome):** menu → *Add to Home screen*

It now launches like a native app, full-screen.

## Buttons in the app

- **▶ BEGIN WORKOUT** — kicks off Phase 1 cardio with the timer.
- **▶ START** (on time-based moves) — countdown timer for that block, auto-advances when done.
- **▶ DEMO VIDEO** — opens YouTube search for that exercise.
- **Set checkbox** — marks a set complete and auto-starts the rest timer.
- **⏱ START REST** (per exercise) — manual rest timer if you skip the auto-trigger.
- **−15s / +15s** (on the timer bar) — nudge the current timer up or down.
- **↺ RESET TODAY** — clears today's checkboxes/inputs but keeps last-session weights.
- **⚠ CLEAR ALL DATA** — wipes everything stored on this device.

## Disclaimer

General fitness programming, not medical advice. If your hip pain is new, sharp, radiating, worsening, or interfering with sleep / walking, see a physiotherapist or sports-medicine doctor before pushing through.
