# ANSYS MAPDL Practice Problems

This repository contains a set of ANSYS MAPDL input files (APDL .inp) for practice problems and example runs.

Repository files
- Problems:
  - [`Problems/Practice problems.pdf`](Problems/Practice problems.pdf)
- Scripts (APDL input files):
  - [`scripts/2D HEAT CONDUCTION.inp`](scripts/2D HEAT CONDUCTION.inp) — 2D heat conduction example
  - [`scripts/2D- TRUSS ANALYSIS.inp`](scripts/2D- TRUSS ANALYSIS.inp) — 2D truss analysis
  - [`scripts/3D SOLID OBJECT.inp`](scripts/3D SOLID OBJECT.inp) — 3D solid object
  - [`scripts/Building concrete.inp`](scripts/Building concrete.inp) — building concrete model
  - [`scripts/CORNER ANGLE BRACKET.inp`](scripts/CORNER ANGLE BRACKET.inp) — corner angle bracket
  - [`scripts/HARMONIC ANALYS IS.inp`](scripts/HARMONIC ANALYS IS.inp) — harmonic analysis
  - [`scripts/PLATE -PLANE STRESS.inp`](scripts/PLATE -PLANE STRESS.inp) — plate plane-stress
  - [`scripts/power transmission tower Geometry.inp`](scripts/power transmission tower Geometry.inp) — transmission tower geometry
  - [`scripts/Solid Steel plate.inp`](scripts/Solid Steel plate.inp) — solid steel plate
  - [`scripts/SPANER -PLANE STRESS.inp`](scripts/SPANER -PLANE STRESS.inp) — spaner plane stress
  - [`scripts/STEPPED BAR.inp`](scripts/STEPPED BAR.inp) — stepped bar
  - [`scripts/Steel Bracket.inp`](scripts/Steel Bracket.inp) — steel bracket
- Results:
  - [`results/(store solver outputs here)`](results/(store solver outputs here))

Quick APDL run examples
- Notes:
  - Replace `ansys` below with your local MAPDL/ANSYS executable (e.g., `ansys202`, `mapdl`).
  - Run from repository root or provide full paths.
  - Output files are directed to `results/` in the examples.

Example per-file run commands (batch mode)
- 2D HEAT CONDUCTION:
  - ansys -b -i "scripts/2D HEAT CONDUCTION.inp" -o "results/2D_HEAT_CONDUCTION.out"
- 2D- TRUSS ANALYSIS:
  - ansys -b -i "scripts/2D- TRUSS ANALYSIS.inp" -o "results/2D_TRUSS_ANALYSIS.out"
- 3D SOLID OBJECT:
  - ansys -b -i "scripts/3D SOLID OBJECT.inp" -o "results/3D_SOLID_OBJECT.out"
- Building concrete:
  - ansys -b -i "scripts/Building concrete.inp" -o "results/Building_concrete.out"
- CORNER ANGLE BRACKET:
  - ansys -b -i "scripts/CORNER ANGLE BRACKET.inp" -o "results/CORNER_ANGLE_BRACKET.out"
- HARMONIC ANALYS IS:
  - ansys -b -i "scripts/HARMONIC ANALYS IS.inp" -o "results/HARMONIC_ANALYSIS.out"
- PLATE -PLANE STRESS:
  - ansys -b -i "scripts/PLATE -PLANE STRESS.inp" -o "results/PLATE_PLANE_STRESS.out"
- power transmission tower Geometry:
  - ansys -b -i "scripts/power transmission tower Geometry.inp" -o "results/power_transmission_tower.out"
- Solid Steel plate:
  - ansys -b -i "scripts/Solid Steel plate.inp" -o "results/Solid_Steel_plate.out"
- SPANER -PLANE STRESS:
  - ansys -b -i "scripts/SPANER -PLANE STRESS.inp" -o "results/SPANER_PLANE_STRESS.out"
- STEPPED BAR:
  - ansys -b -i "scripts/STEPPED BAR.inp" -o "results/STEPPED_BAR.out"
- Steel Bracket:
  - ansys -b -i "scripts/Steel Bracket.inp" -o "results/Steel_Bracket.out"

Example interactive run (start MAPDL, then within MAPDL prompt):
- /INPUT, scripts/Steel Bracket.inp
- /SOLVE
- /POST1, etc.

Notes and troubleshooting
- If your MAPDL binary is named differently, use that name (e.g., `ansys202`, `mapdl`).
- Some file names contain spaces; quoting paths as shown is required on shells.
- Results are directed to `results/` to keep solver outputs organized.

License
- This repository adds an MIT license in [`LICENSE`](LICENSE).

Contributing

- See [`CONTRIBUTING.md`](CONTRIBUTING.md) for contribution guidelines.
