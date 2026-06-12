# IRONLINE 3X · 4-Week Block (`4week.html`)

A BetterMe-style 4-week training program app you run from your phone. (Successor to HIP-SAFE 70 below — the hip restrictions were lifted once the hip was pain-free.)

- **12 sessions · 3 full-body workouts per week** on non-consecutive days (e.g. Mon/Wed/Fri): Lower Focus → Upper Focus → Legs & Arms
- **Common gym exercises only** — squat, leg press, lunges, Romanian deadlift, leg curl, leg extension, calf raises, chest press, pec deck, lat pulldown, cable row, shoulder press, lateral raise, biceps curl, triceps pushdown, plank, crunches
- **Every muscle group ≥2× per week within the 3 sessions**: quads A+C · hams A+C · glutes A+C · calves A+C · chest A+B · back A+B · shoulders A+B · biceps B+C · triceps B+C · core in all three
- **Progressive overload by week**: W1 Foundation 3×10–12 · W2 Build 3×12–15 · W3 Push 4×10–12 · W4 Peak 4×8–10, with rest periods that change per week
- **Session streak counter** and overall program progress bar; "next up" is always the first uncompleted session
- Per-set **weight + reps logging** with "last time" hints pulled from the same session the week before
- **Auto rest timer** on every checked set, countdown timers with beeps on timed blocks, demo-video buttons
- Everything persists on-device via `localStorage`

Deploy the same way as below (GitHub Pages), then open `https://<user>.github.io/7May/4week.html` and Add to Home Screen.

---

# HIP-SAFE 70 · Gym Edition (`index.html`)

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
