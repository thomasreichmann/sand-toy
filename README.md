# Falling Sand

A falling sand simulation that runs entirely in a single HTML file. No dependencies, no build step — just open `index.html` in a browser.

## Elements

Sand, Water, Fire, Plant, Wood, Stone, Acid, Lava, Steam, Ice, Oil, Smoke, Salt, Gunpowder, Metal, Glass, Dust, Mud, Void, Clone, and Ember.

Elements interact with each other — fire burns wood and plants, lava melts ice into steam, acid dissolves materials, water dissolves salt, and so on.

## Physics

- **Gravity and velocity**: Particles accelerate as they fall, with per-element drag and terminal velocity.
- **Fluid dynamics**: Water and oil flow laterally through empty space (up to 4 cells/tick), with pressure equalization that pushes water through other water cells to find exits. Surface leveling keeps pools flat.
- **Splash on impact**: Water dropped from height briefly flashes bright on landing.
- **Depth shading**: Water renders in 5 tiers from bright surface highlights down to dark abyssal tones.

## Running

Open `index.html` in any modern browser. Works on desktop and mobile.
