# Dead Mansion — Codex instructions

## Project
- 2D side-scrolling zombie-hunter action platformer. References: Dangerous Dave gameplay, Dead Cells readability/detail, Broforce energetic action. Make original art; do not copy reference-game assets.
- Current build: static HTML Canvas/vanilla JS in index.html. Preserve working desktop keyboard and iPhone touch controls, browser compatibility and static hosting.
- Communicate in Russian. Explain changes and limitations plainly.

## Approved hero — locked design
- Read docs/HERO_DESIGN.md before any hero-related work.
- Do not redesign approved character without asking. The design is approved as Hero v1.0; minor production refinements are allowed.
- Dark burgundy/red cap, short stubble (not moustache), black leather jacket, longer blue jeans, boots, shotgun.
- Style between Dead Cells and Broforce: expressive detailed pixel art, compact readable silhouette.
- Required animations: idle, heavy breathing, run, jump, landing, shoot, hit reaction with clear knockback, death. More states may be added later.
- Use genuine transparent sprite frames/sheets, not rectangles masquerading as final art.

## Lessons from previous failures
- Never call primitive geometry a reference-quality finished character.
- Keep agreed details consistent across every animation.
- Inspect repository files and existing behavior before edits.
- Do not claim tests or visual quality checks that did not happen.
- Preserve gameplay and touch controls while changing rendering.
- Show screenshots/preview where possible; get visual approval before declaring assets final.
- Do not silently replace the tech stack or rewrite the whole game.

## Workflow
1. Inspect README.md, index.html, docs/HERO_DESIGN.md, git status and assets.
2. Plan a small change and define observable acceptance criteria.
3. Implement incrementally, maintaining a runnable index.html.
4. Test available controls, physics, combat, camera, enemies and restart; test mobile viewport when possible.
5. Report files changed, checks actually run, limitations and next step.
6. For sprite work, begin with idle, heavy breathing and run. Keep frame size, pivot, ground contact and proportions consistent. Only then expand to the other approved animations.
