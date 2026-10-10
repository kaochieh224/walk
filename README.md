# An endless coast

A three.js beach-walk experience. A lone figure walks an endless, ruined shoreline while the camera follows from far behind in a single telephoto shot.

Rendered at low resolution, upscaled with nearest-neighbour filtering, quantised to a five-colour palette with a Bayer 4×4 ordered dither.

## Run

Live: https://kaochieh224.github.io/walk/

Or open `index.html` in a modern browser. It is a single file; three.js loads from jsDelivr.

## Controls

| Key | Action |
| --- | --- |
| Drag / ← → | Orbit the camera (behind the figure only; recentres after 10 s idle) |
| Scroll | Zoom in / out (limited range) |
| O | Reset view |
| N | New shore (new random seed) |
| R | Rain on / off (fades in and out) |
| M | Sound on / off |
| P | Palette: dusk / rain / night |
| H | Hide / show the UI (also the button top-right) |

On phones and tablets: drag with one finger to orbit, pinch with two fingers to zoom, double-tap to reset the view, and tap the labels bottom-right to toggle rain, sound and palette. Sound starts when you tap *Begin walking*.

A specific shore can be opened with a seed in the URL hash, e.g. `index.html#s12345`.

## Files

- `index.html` — the whole experience
- `visual-spec.md` — visual specification and change log
