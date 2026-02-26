# String Theory Cosmos

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18792437.svg)](https://doi.org/10.5281/zenodo.18792437)

**v1.1.0 — Research Instrument Edition**

An interactive, fully deterministic, browser-based toy model for exploring core concepts from string/M-theory and modern cosmology in a **single self-contained HTML file**.

### Features

- Fully deterministic evolution using integer seed (reproducible runs)
- Real-time visualization of vibrating open/closed strings, D-branes, Calabi-Yau projection, wormholes, eternal inflation bubbles, and evaporating black holes with Hawking radiation
- 1 Hz time-series logging of observables (string counts, kinetic energy proxy, radial density, Hawking flux, horizon radius)
- Single-run export (JSON + CSV)
- **New in v1.1**: Full headless parameter sweep mode — scan any parameter across a range, multiple runs per point, averaged results, live progress bar
- Sweep export (JSON + CSV) for further analysis in Python, Mathematica, etc.
- Clean UI with hover tooltips, keyboard shortcuts, and pause/live observables dashboard

### Copyright

Copyright © 2026 Nicolas B. Quiroz, MD. All rights reserved for the original work.

### License

MIT License — free to fork, modify, and use for research, education, or outreach.

### How to Use

1. Open `string-theory-cosmos.html` in any modern browser (no installation needed).
2. Adjust sliders and click on the canvas to add strings.
3. Double-click to reseed the universe.
4. Press **P** to pause and view live observables.
5. Use the **Parameter Sweep** panel (in the UI) for systematic parameter studies.
6. Export your data for further analysis.

### Citation

If you use this tool in research, education, or outreach, please cite it:

> **Nicolas B. Quiroz, MD (2026)**. *String Theory Cosmos v1.1 — Interactive Deterministic Toy Model with Parameter Sweep Mode*. Zenodo. https://doi.org/10.5281/zenodo.18792437

**BibTeX:**
```bibtex
@software{quiroz_string_theory_cosmos_2026,
  author       = {Nicolas B. Quiroz, MD},
  title        = {String Theory Cosmos v1.1 — Interactive Deterministic Toy Model with Parameter Sweep Mode},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18792437},
  url          = {https://doi.org/10.5281/zenodo.18792437}
}
