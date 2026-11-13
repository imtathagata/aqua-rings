# Aqua Rings

A 3D take on the handheld water ring toss toy you had as a kid. Pump the water jets, watch the bubbles swirl, and float all 12 rings onto the pegs.

**▶ Play it: https://mailtathagatasarkar-a11y.github.io/aqua-rings/**

## How to play

| Do this | To |
| --- | --- |
| Press the orange **A** button on the toy, or any key on the left half of your keyboard | Fire the left jet |
| Press the orange **L** button on the toy, or any key on the right half of your keyboard | Fire the right jet |
| **Space** | Fire both |
| **Esc** | Restart |

Tap for a gentle lift, hold for a big gush. On a phone, use the two big buttons under the toy.

- **Easy**: rings get pulled gently onto a peg and stay there.
- **Hard**: tighter aim, and a strong jet can float rings back off.

## What's inside

- One file: [`index.html`](index.html). No build step, no install. Open it in a browser and play.
- [three.js](https://threejs.org/) for the 3D scene, loaded from a CDN.
- Custom lightweight water physics: buoyancy, drag, jet plumes and a sloped floor that funnels rings back to the nozzles.
- Bubbles, surface ripples and light patterns are drawn with small shaders, so it runs smoothly on modest laptops.
- Sound effects are synthesized live with the Web Audio API. No audio files.

Earlier iterations live in [`versions/`](versions).
