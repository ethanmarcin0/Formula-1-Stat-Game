# Live GitHub Pages Test Log — complete after publishing

Tester: Ethan Marcin · AI 101 Section 1
Date/time: PENDING
Live URL: https://ethanmarcin0.github.io/Formula-1-Stat-Game/
Browser/device: PENDING

**All five checks below are pending on GitHub Pages. No live results have been invented.** Historical local tests are listed separately at the bottom.

| # | Category | Steps on your live GitHub Pages site | Expected | Actual | Pass/fail |
|---|---|---|---|---|---|
| 1 | Normal input / both features | Select McLaren, Realistic, default plan; start race. Follow Norris onboard. Close expanded view; select Push, then pause. | Norris/Piastri belong to your team; twelve cars/models load; telemetry updates; selected pace changes; race time stops paused. | PENDING — record what you actually see | PENDING |
| 2 | Invalid input | Start a race, pause, choose Analysis. In Measured vs simulated, import evidence/invalid-telemetry.csv (save it locally first). | A visible “The file is not a valid Pitwall telemetry export.” message; no crash. | PENDING | PENDING |
| 3 | Repeated use | In normal (not expanded) race view, switch 1× → 5× → 1×, pause/resume five times, then Save race. Reload and resume the saved race. | No reset/duplicated grid; settings stay usable; restore is paused; time does not advance while paused. | PENDING | PENDING |
| 4 | Keyboard access | At setup, use Tab/Shift-Tab and Enter/Space to operate controls and start. Outside text fields, press Space twice and 1/3 to change speed. Use Tab to reach a strategy button. | Focus is visible; controls activate; Space pauses/resumes and speed shortcuts work outside fields. Record any keyboard failure. | PENDING | PENDING |
| 5 | Narrow-screen/phone | Open live link on your phone, or use browser responsive tools at 390 px width. Complete setup and try pause and a pace change; try 2D view if needed. | Essential text and controls remain reachable and usable. Record overflow, overlap or performance problems honestly. | PENDING | PENDING |

## One fix and retest

Live issue observed: PENDING — use an actual observation, do not invent a bug.
Steps to reproduce: PENDING.
Change made and file/commit: PENDING.
Retest on the SAME live GitHub Pages URL: PENDING.
Expected / actual / pass-fail: PENDING.

If no new live issue appears, ask the instructor whether the existing documented wheel-animation fix plus a live retest satisfies this portion. Do not label historical local testing as a new GitHub Pages result.

## Historical verification — separate from the five live tests

October 23, 2026: the assistant ran 111 local tests, all passing; see evidence/local-tests-2026-10-23.txt. The wheel-animation fix reduced an animation roughness metric by 65.8–71.3% on a recorded trace, with corner response, pause, phase continuity and reset checks; see evidence/wheel-stability-validation.json. These are consistency/presentation checks, not professional accuracy validation. The supplied screenshots show actual development versions on the original host, not GitHub Pages.
