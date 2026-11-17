# Koi Jelly.

*Material Studies* — a Japanese castle stroll garden around a koi pond, cut out as a square block of clear jelly.

**Live:** https://st3r666.github.io/koi-jelly/

One self-contained `index.html`: plain JavaScript and WGSL, no libraries, no network requests. It needs a browser with WebGPU (Chrome or Edge 113+, Safari 26, Firefox 141+ on Windows).

- Real-time shallow-water heightfield (168²) with refraction, colour absorption, caustics, foam and ripples
- 16 koi in real varieties, medaka, mandarin ducks, a kingfisher, a grey heron, white-eyes, pond turtles, strollers, a monk and a boatman
- Four events: feed the koi, hanami, lantern night with fireworks, spring rain
- Synthesised WebAudio sound for events only

## Controls

| Action | Input |
| --- | --- |
| Stir the water | Drag on the pond |
| Tilt the jelly block | Drag on the ground |
| Orbit | Right-drag, or two fingers |
| Zoom | Wheel or pinch |
| Feed / Hanami / Lantern night / Rain | Space or 1, 2, 3, 4 |
| Fold the panel | H |
| Reset, pause, sound, view | R, P, M, V |

Tap the drum bridge to feed, a cherry to shake it, the bell tower for lantern night.

## Run locally

Open `index.html` in a WebGPU browser. URL options for testing: `?ev=night`, `?view=0-5`, `?palette=sakura`, `?warp=10`.
