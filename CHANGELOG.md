# Changelog

All notable changes to String Theory Cosmos are documented here.

## [2.0.0] — 2026-03-18

### Added
- **Ψuniverse Dynamics Engine** — fractal multi-scale coherence field with configurable depth (1–8 layers), coupling λ, phase rate ω, and decoherence η. Each layer applies force at scale L/2^k with coupling λ/k^β, modulated by a global phase oscillator.
- **Live Analysis Dashboard** — togglable right panel with real-time metric tiles (open/closed strings, radiation, horizon %, mean speed, kinetic energy), three time-series mini-charts (particle count, KE, horizon radius), Ψ fractal spectrum bar chart, and full Ψuniverse readout (global phase, fractal entropy, coherence index, spectral β, field amplitude).
- **Ψ-field Visualization** — concentric fractal rings rendered on the canvas, pulsing with layer amplitudes and global phase.
- **Extended Parameter Sweep** — sweep now supports Ψ coupling (λ) and fractal depth as sweep targets. Exports include psiCoherence, psiFractalEntropy, and psiSpectralBeta columns.
- **Collapsible Panel Sections** — each control group (Seed, Physics, Ψuniverse, Modes, Sweep) can be collapsed independently.
- **Keyboard shortcut** `A` to toggle the analysis dashboard.
- CHANGELOG.md, CONTRIBUTING.md, .gitignore added to repo.

### Changed
- **UI Overhaul** — redesigned from scratch with Outfit + JetBrains Mono typography, top bar navigation, dual-panel layout (controls left, analysis right), refined color system (cyan/gold/violet/green/rose accents), and improved responsive behavior.
- **Slider value readouts** — all sliders now display their current value in real time.
- **Export format** — JSON and CSV exports now include Ψuniverse fields (psiPhase, psiCoherence, psiFractalEntropy).
- Model version string updated to `2.0.0-psiUniverse`.

### Fixed
- Keyboard shortcuts no longer fire when typing in input fields.
- Chart canvases properly resize on window resize.

## [1.0.0] — 2026-03

### Added
- Fully deterministic evolution via integer seed (xmur3 + mulberry32 PRNG).
- Real-time visualization of vibrating open/closed strings, D-branes, Calabi-Yau projection, wormholes, eternal inflation bubbles, and evaporating black holes with Hawking radiation.
- 1 Hz time-series logging of observables (string counts, kinetic energy proxy, radial density, Hawking flux, horizon radius).
- Single-run export (JSON + CSV).
- Headless parameter sweep mode with multiple runs per point and averaged results.
- Full sweep export (JSON + CSV).
- Inflation modes: Standard Big Bang, Slow-roll, Eternal, Chaotic Multiverse.
- 11D M-theory mode toggle.
- Black hole evaporation with horizon shrinking and radiation burst reset.
- Hover tooltips and keyboard shortcuts (P, R, H).
- Click to add strings, double-click to reseed.
