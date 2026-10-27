# Prime: Star Run

Deep-space edition of Flappy PRIME. You fly the robot warrior Prime through a nebula, threading between asteroid gates. Single-file HTML canvas game, no dependencies, no external assets. Open index.html in a browser.

Controls: tap, click, or press Space / Up Arrow / Enter to flap. Tap or press again on the game over screen to retry. Press M or tap the speaker icon (top right) to mute or unmute.

Features:
- Deep-space nebula backdrop with a drifting, twinkling starfield. The nebula hue slowly drifts between violet and deep blue over time.
- Procedural planets drift past occasionally: a ringed gas giant, a red rocky world, and a blue ice planet.
- Asteroid gates: riveted metal shafts with embedded rock chunks and glowing energy emitter plates at the gap.
- Power-ups: energy orbs spawn in gate gaps sometimes. "S" (cyan) is a shield that blocks one hit and gives brief invulnerability. "T" (purple) slows time for about 5 seconds. HUD shows active power-ups.
- Hard mode after 15 points: narrower gaps and faster scrolling.
- Sound: a calm generative ambient pad loop built with WebAudio (starts on your first tap), plus soft chimes on each point, a muffled thud on impact, and a soft whoosh on each flap. Mute state is saved in localStorage.
- Prime's thruster glows brighter on each flap.
- Best score saved in localStorage.
