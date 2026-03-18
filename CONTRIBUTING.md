# Contributing to String Theory Cosmos

Thanks for your interest in contributing! This project is a single-file research instrument, so contributions tend to be focused and self-contained.

## Ways to Contribute

- **Bug reports** — open an issue describing the problem, your browser/OS, and steps to reproduce.
- **Feature requests** — open an issue with a clear description of the proposed feature and why it would be useful for research or education.
- **Code contributions** — fork the repo, make your changes, and submit a pull request.
- **Physics feedback** — if you spot a modeling error or have suggestions for improving the toy model's fidelity, open an issue or discussion.

## Guidelines

1. **Single-file architecture** — the simulation lives in one self-contained HTML file with no external dependencies (except Google Fonts). Please keep it that way.
2. **Determinism** — all simulation logic must use the seeded PRNG (`rand()`), never `Math.random()`. A given seed and parameter set must always produce identical results.
3. **Keep it accessible** — the tool is designed for researchers, students, and curious people. Clear tooltips, readable code comments, and intuitive UI matter.
4. **Test before submitting** — open the file in at least two browsers (Chrome + Firefox recommended) and verify your changes don't break the simulation, exports, or sweep mode.
5. **Respect the model** — this is a phenomenological proxy system, not a claim about real physics. Keep that framing in any documentation or UI text.

## Code Style

- Vanilla JS, no frameworks (the file must remain self-contained).
- Use `const` / `let`, never `var`.
- Descriptive variable names; comments for non-obvious physics logic.
- CSS custom properties (variables) for colors and theming.

## Pull Request Process

1. Fork and create a feature branch (`git checkout -b feature/my-feature`).
2. Make your changes in `string-theory-cosmos.html`.
3. Test thoroughly (simulation, pause, export, sweep, keyboard shortcuts).
4. Submit a PR with a clear description of what changed and why.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

## Contact

For questions, reach out to **Nicolas B. Quiroz, MD** via [GitHub](https://github.com/BEPframework).
