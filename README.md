# An endless coast

A three.js beach-walk experience. A lone figure walks an endless, ruined shoreline while the camera follows from far behind in a single telephoto shot.

Rendered at low resolution, upscaled with nearest-neighbour filtering, quantised to a five-colour palette with a Bayer 4×4 ordered dither.

## Run

Live: https://kaochieh224.github.io/walk/

Or open `index.html` in a modern browser. It is a single file; three.js loads from jsDelivr.

## Controls

| Key | Action |
| --- | --- |
| Drag / ← → | Orbit the camera (behind the figure only; slowly recentres after 1 min idle) |
| Scroll | Zoom in / out (limited range) |
| O | Reset view |
| N | New shore (new random seed) |
| R | Rain on / off (fades in and out) |
| M | Sound on / off |
| P | Skip to the next palette (they also cycle on their own: dusk → rain → night → stalker, 15 min per loop) |
| H | Hide / show the UI (also the button top-right) |

On phones and tablets: drag with one finger to orbit, pinch with two fingers to zoom, double-tap to reset the view, and tap the labels bottom-right to toggle rain, sound and palette. Sound starts when you tap *Begin walking*.

A specific shore can be opened with a seed in the URL hash, e.g. `index.html#s12345`.

## Also here

**A slow afternoon** — lying in bed looking up at a turning ceiling fan while afternoon sun comes through the window. Same low-res dithered renderer, in natural colour. Live: https://kaochieh224.github.io/walk/fan/ (drag to turn your head; M sound, O reset view, H hide UI).

**By the window** — sitting at a table by a big aluminium window on the second floor, looking out at a tree-lined Taiwanese street: banyans and trimmed street trees, scooters and taxis stopping at the lights, people crossing, afternoon thunderstorms, dusk and night, and the garbage truck playing *Für Elise* at 7:20 pm. Live: https://kaochieh224.github.io/walk/window/ (drag to look around, look down to lean towards the glass; R rain, T later, M sound, O reset view, H hide UI).

## Files

- `index.html` — the whole experience
- `visual-spec.md` — visual specification and change log
- `fan/index.html`, `fan/visual-spec.md` — A slow afternoon
- `window/index.html`, `window/visual-spec.md` — By the window
