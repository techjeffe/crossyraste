# Crossy Raste

A Crossy Road-style browser game themed around surviving Indian tech-city traffic.

## Play Online
**[techjeffe.github.io/crossyraste](https://techjeffe.github.io/crossyraste/)** — hosted via GitHub Pages, no download needed.

## How to Play
1. Play it live at the link above, or open `index.html` directly in a browser (Chrome, Firefox, or Safari) — no server needed either way.
2. Use arrow keys or WASD to move the tourist (🧍‍♂️).
3. On mobile, swipe to move.
4. Cross as many lanes as possible without getting hit by vehicles.

## Game Features
- **7 lane types**: Footpath, Auto-rickshaw, Bus, Car, Bike pack, Roundabout, Pothole, Barrier
- **Progressive rush-hour system**: 8AM (calm) → 9-10AM (busy) → midday (chaos) → 6-7PM (peak, with rain) → 8PM+ (night, headlights)
- **Procedural sound**: honks, hops, death, level-up, roundabout fanfare and rain, all generated with the Web Audio API (no audio files)
- **Parallax skyline**: buildings scroll slower than the road for depth
- **Mobile-friendly**: touch swipe controls, and the tile size scales with the viewport (compact on phones, larger on big/fullscreen desktop displays)
- **10 rotating Bengaluru-flavored death messages**

## Technical Details
- Single self-contained `index.html` — HTML5 Canvas + vanilla JavaScript, no build step, no JS libraries
- Only external dependency is the Google Font "Poppins"
- Works from `file://` directly, no server required
- Tile-based grid, camera follows the player; vehicles move continuously while the player hops tile-by-tile
- 60fps game loop via `requestAnimationFrame`

## Controls
- **Desktop**: Arrow keys or WASD
- **Mobile**: Swipe up/down/left/right
- **Restart**: Click/tap "Try Again", or press Space/Enter, on the game-over screen

Enjoy surviving Bengaluru traffic! 🛺🚌🚗
