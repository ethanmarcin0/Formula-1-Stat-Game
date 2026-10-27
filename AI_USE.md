# AI Use Note

Ethan Marcin · AI 101 · Section 1

**Tool:** OpenAI Codex/ChatGPT coding assistant.

## What AI contributed

The assistant helped turn the idea into a scoped plan, implement the React/TypeScript browser game, build worker-based simulation and Three.js views, adapt supplied car meshes, write checks/documentation, research sources, diagnose bugs and prepare a static GitHub Pages upload copy. This is substantial AI-assisted development, not just spelling assistance.

## Human direction and changes

I chose the Formula 1 strategist concept and requested team selection, equal/realistic cars, speed controls, Monza, 3D/onboard cameras and telemetry. I provided car-model references and reported issues including braking, camera placement, pit-lane placement and shaky front tires. The assistant implemented code revisions in response. Driver profiles remain provisional policies, not trained copies of real drivers.

## Exact initial prompt

> I would like to make a formula 1 strategy game. Similar to f1 manager if you have seen those. We want to act as a race strategist and make it a simulator. I want full size tracks with the updated 2026 cars a regulations. The biggest plan i want to realistic drivers, maybe input ai agents in as driver but each one of them studies and learns a real life drivers method of racing. Then input that into each race weekend, we could start with only a few drivers to test, then move up to more later on. Let's also start as a 2d world at first, later on we could use blender or unity to make a full 3d world with real physics and driving methods. Lets plan this out from the start. Let me know what changes you want and how we should go about this?

## Exact follow-up prompt for the 3D revision

> Okay, we are going to act like a creative designer here/ 3d designer. I now want to make this into a 3d game, this is the big step to making the physics more realistic and better racing lines. I now want you to create a 3d world of the track monza and make the racing more realistic. Relate it to f126 for a good source or even fast f1 api for the real life telemetry of Monza. Also, how can we increase the reliability that this program could be used by a real race strategist/engineer? I would prefer and onboard camera or chase camera option for each car when in the 3d version of the game. Let me know what you think?

The follow-up made the desired viewing experience concrete by requesting an explorable 3D Monza and named camera modes. The before/after evidence shows the change from a 2D map to 3D onboard viewing. It does not prove professional accuracy.

## Additional exact bug-fix prompt

> Also, fix the front tires from shaking a lot.

The assistant smoothed visible steering corrections and preserved tire spin through contact position corrections and pit handoffs. Authoritative steering telemetry and simulation physics were not changed by this presentation fix.

## What was verified, and by whom

The assistant recorded 111 passing local automated tests on October 23, 2026, and browser checks on the development/public-demo hosts. The retained test output and wheel report are in evidence/. This does not mean 111 real-world accuracy checks, nor 111 GitHub Pages tests. Local subdirectory checks for this package are recorded in PACKAGE_CHECKS.md.

My required live GitHub Pages verification is still pending in TEST_LOG.md. After I upload, I must record actual observations, including failures, and review this note for accuracy before submitting. I am responsible for the final work and its claims.
