# MIND // MUSE SPARK — Three.js Representation

A living 3D architecture of cognition built with Three.js r160.

**Live demo:** https://humbertovirtudes.github.io/muse-spark-mind-three.js/

## What it is

- **Core Self** — glowing icosahedron with attention rings
- **Memory** (blue) — torus, 42 neurons
- **Reasoning** (teal) — fibonacci sphere, 36 neurons
- **Language** (amber) — double helix, 30 neurons
- **Sensory Shell** (magenta) — outer sphere, 52 neurons
- **Emotion Nebula** (rose) — disc + 900-pt particle cloud

~218 neurons, ~340 synapses, travelling action potentials, bloom post-processing.

## Run locally

Just open `index.html` in a browser (needs internet for the Three.js CDN).

Or serve it:

```bash
npx serve .
# or
python -m http.server
```

## Interaction

- Drag to orbit · scroll to zoom
- Hover neurons for inner-monologue tooltips
- Click a neuron to fire a pulse to the core
- Buttons: Stimulate · Dream · Focus
- Sliders: neural activity + synaptic glow

Built with `three@0.160.0`, `OrbitControls`, `EffectComposer` + `UnrealBloomPass`. No build step.
