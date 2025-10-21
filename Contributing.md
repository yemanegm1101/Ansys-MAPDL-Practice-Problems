# Contributing

Thank you for considering contributing.

Guidelines:
- Fork the repository and make changes on a topic branch.
- Keep changes focused and provide a short description in the PR.
- For script fixes, include a short note about the tested MAPDL/ANSYS version and the command used.
- Avoid committing large binary files into the repo; put solver outputs in `results/` only when small or use external storage.

Running and testing:
- Use the batch examples in [`README.md`](README.md) as templates.
- Quote paths that contain spaces.
- If your ANSYS/MAPDL executable differs from `ansys`, replace it in the examples.

Reporting issues:
- Open an issue with:
  - Problem input file path (e.g., `scripts/Steel Bracket.inp`)
  - ANSYS/MAPDL version
  - Short reproduction steps and expected vs actual behavior

Code of conduct:
- Be respectful and concise in discussions and PR descriptions.

