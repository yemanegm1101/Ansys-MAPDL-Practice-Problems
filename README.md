# ANSYS MAPDL Practice Problems

This repository contains a set of ANSYS MAPDL input files (APDL .txt) for practice problems and example runs.

Repository files
- Problems:
  - [`Problems/Practice problems.pdf`](Problems/Practice problems.pdf)
- Scripts (APDL input files):
  - [`scripts/2D HEAT CONDUCTION.txt`](scripts/2D HEAT CONDUCTION.txt)   2D heat conduction example
  - [`scripts/2D- TRUSS ANALYSIS.txt`](scripts/2D- TRUSS ANALYSIS.txt)  2D truss analysis
  - [`scripts/3D SOLID OBJECT.txt`](scripts/3D SOLID OBJECT.txt)  3D solid object
  - [`scripts/Building concrete.txt`](scripts/Building concrete.txt)  Building concrete model
  - [`scripts/CORNER ANGLE BRACKET.txt`](scripts/CORNER ANGLE BRACKET.txt)  Corner angle bracket
  - [`scripts/HARMONIC ANALYS IS.txt`](scripts/HARMONIC ANALYS IS.txt)  Harmonic analysis
  - [`scripts/PLATE -PLANE STRESS.txt`](scripts/PLATE -PLANE STRESS.txt)  Plate plane-stress
  - [`scripts/power transmission tower Geometry.txt`](scripts/power transmission tower Geometry.txt)  Transmission tower geometry
  - [`scripts/Solid Steel plate.txt`](scripts/Solid Steel plate.txt)  Solid steel plate
  - [`scripts/SPANER -PLANE STRESS.txt`](scripts/SPANER -PLANE STRESS.txt)  Spaner plane stress
  - [`scripts/STEPPED BAR.txt`](scripts/STEPPED BAR.txt)  Stepped bar
  - [`scripts/Steel Bracket.txt`](scripts/Steel Bracket.txt)  Steel bracket

Quick APDL run examples
- Notes:
  - Replace `ansys` below with your local MAPDL/ANSYS executable.
  - Run from repository root or provide full paths.
  - Output files are directed to `results/` in the examples.

 ## per-file run commands (batch mode)
- 2D HEAT CONDUCTION:
  - ansys -b -i "scripts/2D HEAT CONDUCTION.txt" -o "results/2D_HEAT_CONDUCTION.out"
  <img width="586" height="440" alt="image1" src="https://github.com/user-attachments/assets/c374e225-89c9-4c66-b414-bda25fa5f984" />

- 2D- TRUSS ANALYSIS:
  - ansys -b -i "scripts/2D- TRUSS ANALYSIS.txt" -o "results/2D_TRUSS_ANALYSIS.out"
   <img width="584" height="438" alt="image6" src="https://github.com/user-attachments/assets/15853087-944f-4c2b-8162-bc84194d7ed6" />

  - 3D SOLID OBJECT:
     - ansys -b -i "scripts/3D SOLID OBJECT.txt" -o "results/3D_SOLID_OBJECT.out"
     <img width="584" height="438" alt="image9" src="https://github.com/user-attachments/assets/40fe15b2-5b15-42e6-bcdb-c659265a4295" />

- Building concrete:
  - ansys -b -i "scripts/Building concrete.txt" -o "results/Building_concrete.out"
  <img width="584" height="438" alt="image12" src="https://github.com/user-attachments/assets/a761b371-f8fd-4660-b43b-0eca959cafee" />

- CORNER ANGLE BRACKET:
  - ansys -b -i "scripts/CORNER ANGLE BRACKET.txt" -o "results/CORNER_ANGLE_BRACKET.out"
  <img width="584" height="438" alt="image2" src="https://github.com/user-attachments/assets/4efcbf05-9853-461d-bc88-c3433ec0e97a" />

- HARMONIC ANALYS IS:
  - ansys -b -i "scripts/HARMONIC ANALYS IS.txt" -o "results/HARMONIC_ANALYSIS.out"
  <img width="584" height="438" alt="image14" src="https://github.com/user-attachments/assets/4e45f730-5a9f-4ac0-9fa9-5a9ea0ca3969" />
  <img width="584" height="438" alt="image13" src="https://github.com/user-attachments/assets/dbbc41a9-6174-42f2-be86-98b30f184931" />


- PLATE -PLANE STRESS:
  - ansys -b -i "scripts/PLATE -PLANE STRESS.txt" -o "results/PLATE_PLANE_STRESS.out"
  <img width="584" height="438" alt="image4" src="https://github.com/user-attachments/assets/ce14e794-3e06-465b-95cd-b9cfffc43da0" />

- power transmission tower Geometry:
  - ansys -b -i "scripts/power transmission tower Geometry.txt" -o "results/power_transmission_tower.out"
  <img width="584" height="438" alt="image8" src="https://github.com/user-attachments/assets/5a54a7b1-f0ec-4a6a-b51c-f2a7cedee409" />

- Solid Steel plate:
  - ansys -b -i "scripts/Solid Steel plate.txt" -o "results/Solid_Steel_plate.out"
  <img width="584" height="438" alt="image11" src="https://github.com/user-attachments/assets/ad17edf0-f333-454a-988b-35c2c5f0a109" />

- SPANER -PLANE STRESS:
  - ansys -b -i "scripts/SPANER -PLANE STRESS.txt" -o "results/SPANER_PLANE_STRESS.out"
  <img width="584" height="438" alt="image3" src="https://github.com/user-attachments/assets/63b04df6-a970-4149-aa3a-b3b9235513f6" />

- STEPPED BAR:
  - ansys -b -i "scripts/STEPPED BAR.txt" -o "results/STEPPED_BAR.out"
  <img width="584" height="438" alt="image7" src="https://github.com/user-attachments/assets/8a0e23e6-acd9-425c-af05-50967d7f0745" />

- Steel Bracket:
  - ansys -b -i "scripts/Steel Bracket.txt" -o "results/Steel_Bracket.out"
  <img width="584" height="438" alt="image10" src="https://github.com/user-attachments/assets/3aa3f660-08de-484a-baef-1a1be6ac607c" />



Notes and troubleshooting
- If your MAPDL binary is named differently, use that name.
- Some file names contain spaces; quoting paths as shown is required on comad line.
- Results are directed to `results/` to keep solver outputs organized.


Contributing

- See [`CONTRIBUTING.md`](CONTRIBUTING.md) for contribution guidelines.



