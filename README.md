# Pitwall — AI 101 Midterm

Ethan Marcin · AI 101 · Section 1

**GitHub Pages live link:** https://ethanmarcin0.github.io/Formula-1-Stat-Game/
**Repository link:** https://github.com/ethanmarcin0/Formula-1-Stat-Game

The existing development demo is https://pitwall-f1-strategy.dusky-lily-6449.chatgpt.site/ . That is a separate host and does not satisfy the assignment's GitHub Pages requirement.

## Audience and purpose

Pitwall is for Formula 1 fans and students interested in race strategy. The player manages a team instead of directly driving. Its purpose is to explore how pace, tires, energy and pit choices affect a simulated dry race at Monza. It is a research/game prototype, not a validated professional engineering tool.

## Two working features

1. **Interactive race strategy:** select one of six teams, choose realistic/equal machinery, then manage pace, energy, tire compounds and pit commands for its two drivers. Pause, resume and accelerate the race.
2. **3D race viewing and telemetry:** follow any of twelve drivers using chase, onboard, cockpit, free-look or overview views. Inspect speed, braking, battery and aero status. A 2D view is available.

## How to use

Open the live GitHub Pages link in a modern browser. Select a team → Continue → select performance → Continue → configure the race → Go to the grid. Use the timing tower or Follow selector to inspect a driver. Change strategy in Your pit wall. Save race stores the race in this browser; restore opens paused. Pit windows warn you; they do not automatically pit your cars. Use two different dry compounds to meet the race's compound rule.

Space pauses/resumes and number keys 1–6 select race speeds. Shortcuts are inactive while typing in a field. For the most reliable access to playback/strategy controls, close the expanded camera view. Medium graphics and the 2D view can help slower devices. Free look: drag to orbit, scroll to zoom; its visible arrow/zoom buttons also work while paused.

## Files

- `index.html`, `assets/`, `models/`, JSON data and HTML notes: prebuilt static game; no npm or terminal is needed to publish this copy.
- `AI_USE.md`: exact project prompts and AI contribution disclosure.
- `EVIDENCE.md` and `evidence/`: genuine earlier/later development screenshots and a revision explanation.
- `TEST_LOG.md`: five live-GitHub-Pages checks to complete after publishing, plus separately labelled historical verification.
- `UPLOAD_GUIDE.md`: upload and Pages setup instructions.

## Sources and credits

- Adapted 2026 display cars by Dave Love SketchFab / Tyler_Dave, CC BY 4.0. Model-specific source links, transformations and source hashes: [model credits](model-credits.html), [model manifest](models/manifest.json). Sponsor textures/decals were removed. The supplied Monza display mesh is excluded because original redistribution permission remains unresolved.
- Geographic alignment: © OpenStreetMap contributors, ODbL, via the pinned track-atlas data. [Geometry attribution](geometry-attribution.txt), [derived geometry](monza-geometry.json), [track-atlas licence](TRACK_ATLAS_LICENSE.txt), [upstream attribution](TRACK_ATLAS_ATTRIBUTION.md.txt).
- Public telemetry: [OpenF1](https://openf1.org/docs/) and planned/offline [FastF1](https://docs.fastf1.dev/) importing. [Cached reference/provenance](telemetry-reference.json). Providers can share the same upstream feed and are not independent sensors.
- Regulations reference: frozen FIA Sporting Issue 08 / Technical Issue 20, August 5, 2026. Implementations and event-specific activation/energy maps are simplified. [FIA regulations](https://www.fia.com/regulation/category/2182).
- EA F1 25/2026 Season Pack was a presentation/camera reference. No EA game assets are included. [EA feature reference](https://www.ea.com/games/f1/f1-25/news/f1-25-features-deep-dive).
- Runtime/libraries: React, TypeScript, Vite and Three.js. Full engineering assumptions: [3D notes](3d-research.html).

## Known limitations

Dry single races only; no wet weather, full weekends, career or direct driving. Widths, elevation, banking, scenery, driver tendencies, tire forces and aerodynamic coefficients are provisional. Physics consistency does not establish real-world accuracy. Some contacts and imperfect racing lines remain possible. Car meshes are adapted display geometry, not manufacturer CAD. Public data cannot prove precise wheel-to-wheel paths. High detail may be slow on phones; desktop use is best, and the assignment still requires an actual narrow-screen/phone check. Hundreds of strategy-analysis scenarios can take hours.

The game runs locally in browser workers after assets load, with no required live AI calls or API keys. A first load needs hosting/network access; there is no guaranteed offline-install/service-worker feature. Browser saves do not transfer automatically between the development host and GitHub Pages, or between devices/private windows.

## Submission status

The static upload package was prepared on October 27, 2026 and added to this repository through Git. GitHub Pages publishes the root of main. The two links above are the repository and Pages addresses. All five assignment tests in TEST_LOG.md, an actual live fix/retest where applicable, and final Canvas submission remain to be completed. Existing local/development-host tests do not substitute for those live GitHub Pages checks.
