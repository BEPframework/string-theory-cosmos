# String Theory Cosmos

**v2.0 — Ψuniverse Research Instrument**

An interactive, fully deterministic, browser-based toy model for exploring core concepts from string/M-theory and modern cosmology — now with **Ψuniverse fractal dynamics** — in a single self-contained HTML file.

---

### What's New in v2.0

- **Ψuniverse Dynamics Engine** — fractal multi-scale coherence field inspired by the BEP framework (fractal + quantum-like dynamics). Configurable fractal depth (1–8 layers), coupling strength (λ), phase rate (ω), and decoherence (η). Each layer applies force at scale L/2^k with coupling λ/k^β, modulated by a global phase oscillator.
- **Live Analysis Dashboard** — real-time metric tiles, time-series mini-charts (particle count, kinetic energy, horizon radius), Ψ fractal spectrum bar chart, and full Ψuniverse readout (global phase, fractal entropy, coherence index, spectral β, field amplitude).
- **Redesigned UI** — collapsible panel sections, refined typography (Outfit + JetBrains Mono), top bar navigation, and keyboard-accessible controls.
- **Extended Sweep Mode** — parameter sweeps now include Ψ coupling (λ) and fractal depth; exports include psiCoherence, psiFractalEntropy, and psiSpectralBeta columns.
- **Ψ-field Visualization** — concentric fractal rings rendered on the canvas, pulsing with layer amplitudes and global phase.

### Features

- Fully deterministic evolution via integer seed (identical results every time)
- Real-time visualization of vibrating open/closed strings, D-branes, Calabi-Yau projection, wormholes, eternal inflation bubbles, evaporating black holes with Hawking radiation, and Ψuniverse fractal field
- 1 Hz time-series logging of observables (string counts, kinetic energy, radial density, Hawking flux, horizon radius, Ψ coherence, fractal entropy)
- Single-run export (JSON + CSV)
- Headless parameter sweep mode — scan any parameter over a range with multiple runs per point and averaged results
- Full sweep export (JSON + CSV) for further analysis in Python, Mathematica, etc.
- Live analysis dashboard with real-time charts and Ψuniverse readout
- Clean UI with hover tooltips, collapsible sections, and keyboard shortcuts

### How to Use

1. Open `string-theory-cosmos.html` in any modern browser (no installation needed).
2. Adjust sliders and click on the canvas to add strings.
3. Double-click to reseed the universe.
4. Use keyboard shortcuts: **P** pause · **R** reseed · **H** hide controls · **A** toggle analysis.
5. Enable **Ψuniverse Dynamics** to activate the fractal coherence field and tune its parameters.
6. Open the **Analysis** panel to monitor live observables, time-series charts, and Ψ-field state.
7. Use the **Parameter Sweep** panel for systematic studies.
8. Export your data for further analysis.

### Ψuniverse Model

The Ψuniverse engine implements a fractal coherence field with `1/f^β` spectral scaling:

- **Fractal layers**: each depth layer *k* applies a radial + tangential force at spatial scale `L / 2^k` with coupling `λ / k^β`
- **Global phase oscillator**: `Ψ(t) = cos(ωt + φ_k)` modulates each layer with a golden-ratio phase offset
- **Decoherence**: stochastic perturbation `η` injected per scale to model quantum-like noise
- **Live diagnostics**: spectral β (estimated via log-log regression on layer amplitudes), fractal entropy (variance of layer amplitudes), and coherence index (velocity alignment)

This is a phenomenological proxy system designed for reproducible exploration and scientific communication, inspired by the BEP HRV analysis framework.

### Copyright

Copyright © 2026 Nicolas B. Quiroz, MD. All rights reserved for the original work.

### License

MIT License — free to fork, modify, and use for research, education, or outreach.

### Citation

If you use this tool, please cite:

> **Nicolas B. Quiroz, MD (2026)**. *String Theory Cosmos v2.0 — Interactive Deterministic Toy Model with Ψuniverse Dynamics*. GitHub. https://github.com/BEPframework/string-theory-cosmos

**BibTeX:**
```bibtex
@software{quiroz_string_theory_cosmos_2026,
  author       = {Nicolas B. Quiroz, MD},
  title        = {String Theory Cosmos v2.0 — Interactive Deterministic Toy Model with Ψuniverse Dynamics},
  year         = {2026},
  publisher    = {GitHub},
  url          = {https://github.com/BEPframework/string-theory-cosmos}
}
```
