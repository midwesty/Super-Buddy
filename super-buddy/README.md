# Super Buddy — v0.1

An original-IP browser superhero prototype. You run a program that turns a volunteer
into a super-person, then deploy into a living, destructible island city.

**Play:** open `index.html` in a browser (desktop Chrome or mobile Safari, landscape).
No build step — it loads three.js from a CDN.

## Deploy on GitHub Pages
Put `index.html` at the repo ROOT (not in a subfolder), make the repo public, then
Settings → Pages → Deploy from a branch → main → / (root). Live at
`https://<user>.github.io/<repo>/`.

## Controls
- Move: left joystick / WASD
- Look / aim: drag the screen / mouse-drag (vertical = tilt view up-down, full range); mouse wheel zooms on desktop
- Jump: ⤒ / Space (double-jump by default); 🦘 Super jump; hold jump at an exterior ladder to climb to a roof
- Powers (pick on the create screen): 🕊️ Flight · 💨 Super speed (stacks with flight) · 🖐️ Stretch (auto-locks nearest thing) · ✦ Blink (roof auto-snap) · 🔴 Laser · 🔥 Fireball · ❄️ Frost · 💪 Super strength · 🔼/🔽 Grow/Shrink · 🚀 Missiles · 🦘 Super jump · 👊 Punch (always on)
- Settings / Pause: ⚙ (top right) — All Sound / Music / Sound FX toggles

## World
Island city ringed by water with coastline, piers, and bridges with lighthouses.
Buildings vary (skyscrapers, churches, shops, domes) with rooftop water towers, vents,
huts, billboards, gardens, bird nests, fire escapes, and climbable ladders. Trees,
bushes, hydrants, lamps, and powerlines dress the streets — nearly everything is
destructible, and buildings collapse then get rebuilt by construction crews.

## Gameplay
Answer crime incidents (red street markers) for cash + public approval. Collateral
damage lowers approval.

## Tech
Single self-contained HTML file. Vanilla JS + three.js (r128, CDN). Procedural voxel
city, particle system, synthesized placeholder audio (swappable later).

*Prototype — systems and balance in active development.*
