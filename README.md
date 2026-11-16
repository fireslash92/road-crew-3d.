# محاكي التحكم بالمعدات التعليمي (Road Crew 3D)

دائرة الطرق بمحافظة البريمي

A browser simulator of the heavy equipment used to build a road, from earthworks to the final asphalt rolling. Everything runs in a single `index.html` with three.js loaded from a CDN. There is no build step.

## Machines

| Stage | Machines |
|---|---|
| Earthworks | Bulldozer, Motor Grader, Dump Truck |
| Subgrade and base | Water Truck, Padfoot Compactor, Smooth Drum Roller |
| Paving | Cold Milling Machine, Asphalt Distributor, Asphalt Paver |
| Asphalt compaction | Tandem Asphalt Roller, Pneumatic Tire Roller |

Each machine has its own levers, toggles and readouts, and changes the ground it works on: blades cut and cast soil, water darkens it, rollers compact it, the paver lays a mat and the milling machine removes old asphalt.

## Controls

- **Touch:** joystick to drive, hold the lever buttons to move the attachment.
- **Keyboard:** `W/S` throttle, `A/D` steer, `R/F`, `Z/X`, `C/V`, `B/N` for the levers, `T` and `G` for toggles, `U` for reload or refill.
- **Top bar:** change machine, camera (orbit, chase, cab), autopilot, job site (raw ground, graded base, worn asphalt road), sound.

## Run it

Open `index.html` in a browser, or enable GitHub Pages for this repository (Settings, Pages, deploy from the `main` branch) to play it from a link. An internet connection is needed to load three.js.
