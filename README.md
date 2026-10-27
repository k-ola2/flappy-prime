# Prime: Earth Seasons

Robot warrior edition of Flappy Bird, set on Earth through four seasons. Single-file HTML canvas game, no dependencies. Open index.html in a browser.

Controls: tap, click, or press Space / Up Arrow / Enter to flap. Tap or press again on the game over screen to retry. Press M or tap the speaker icon (top-right) to mute.

Seasons: the game cycles SPRING, SUMMER, AUTUMN, WINTER every 20 points. Each change is a gradual 8 second crossfade, never a jump.
- SPRING: soft bright sky, fresh green hills, blossom trees, pink petals drifting. Pillars are mossy blossom-green stone with pink blossoms.
- SUMMER: warm golden sky with the sun, heat shimmer, sand ripples. Pillars are sandstone and terracotta.
- AUTUMN: amber sky, orange leaves falling. Pillars are bare tree trunks with branches and warm leaf caps.
- WINTER: pale cold sky, falling snow, snowy ground. Pillars are ice with icicles and frost glow.

Day and night: each season cycles through day and night over about 60 seconds. The sun crosses the sky by day and the moon by night, with stars after dark. Each season has its own night palette, and weather particles dim at night.

Music: a generative ambient pad that changes chords per season. Spring is light, summer warm, autumn mellow, winter quiet and crisp.

Features:
- Shield orb: about 1 in 8 gates carries an "S" orb. It blocks one hit and gives brief invulnerability.
- Gentle start: gaps are wide for the first 19 points. Each new season after that narrows the gaps and speeds the scroll a little.
- Best score saved in localStorage.
- Mute saved in localStorage.
