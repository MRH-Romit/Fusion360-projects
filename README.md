# Fusion 360 Projects

A small collection of Fusion 360 models and assemblies. This README lists what each file is, how to open them in Fusion 360, and the near‑term roadmap for improvements.

## Contents

- Base of mechanical hand (`Base of mechanical hand_.f3z`): Fusion 360 archive of a multi‑component assembly for a mechanical hand base.
- Rotating part of a mechanical hand (`rotating part of a mechanical hand.f3d`): Single part intended to mate with the base; use for motion/fit studies.
- Bottle (`bottle.f3d`): Simple bottle model for practicing parametric features and appearances.
- PaperClip (`PaperClip.f3d`): Wire‑form part for bend/shape experiments and quick simulations.

## Open in Fusion 360

You can open either by uploading to your Data Panel or opening directly from disk.

Option A — Upload:
 
1) Open Fusion 360 and open the Data Panel (grid icon at top‑left).
2) Click Upload and select any of the files from this folder (`.f3d` or `.f3z`).
3) After upload completes, double‑click to open.

Option B — Open from disk:
 
1) In Fusion 360, go to File → Open → Open from my computer.
2) Pick the desired file and open it.

Notes:
 
- `.f3z` is a Fusion 360 archive that keeps referenced components together (best for assemblies like the mechanical hand base).
- `.f3d` is a single‑design file (good for individual parts like the rotating part, bottle, or paper clip).

## Working Tips

- Parameters: Use Modify → Change Parameters to adjust key dimensions when available.
- Document units: Check the Document Settings dropdown in the Browser to confirm units before measuring/exporting.
- Joints/As-Built Joints: For assemblies, use Assemble → As‑Built Joint to define motion without altering geometry.
- Appearance/Rendering: Use Appearance and Render workspaces for quick visuals and documentation.

## Roadmap / Future Plans

Mechanical Hand:
 
- Define joints and motion links between the base and rotating component.
- Run a Motion Study and verify clearances/interference.
- Add fasteners and hardware from the McMaster‑Carr Content Library.
- Prepare 3D‑printable variants with sensible tolerances and fillets.

Bottle:
 
- Add a matching cap; consider thread features or a snap fit.
- Apply labels/decals and generate a clean product render.

PaperClip:
 
- Explore material options and run a quick stress analysis for typical loads.
- Create size variants via parameters (wire diameter and overall length).

Repository hygiene:
 
- Export neutral formats (STEP for CAD exchange; STL for 3D printing) into an `exports/` folder.
- Add key screenshots/renders to a `docs/` folder for quick previews.
- Maintain brief revision notes as designs evolve.

## Exporting (recommended)

From Fusion 360:
 
- STEP (.step/.stp): File → Export → Type: STEP; ideal for sharing with other CAD.
- STL (.stl): Make → 3D Print or File → Export → STL; for slicing/printing.
- IGES (.igs) or SAT (.sat): Only if a target workflow requires it.

If you want, I can add a standard `exports/` and `docs/` structure and placeholders to keep things organized.

