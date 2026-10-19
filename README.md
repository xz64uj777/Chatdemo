# FIELD OPS 3D — Corps Response

The playable game in this repository is **Field Ops 3D**, based on the supplied `field_ops_3d_v08.zip` source (Site Crew v0.8). It replaces the old flat BuildWorks canvas prototype as the published game.

## Play

After the GitHub Pages workflow succeeds: https://xz64uj777.github.io/Chatdemo/

The game is a browser-first Three.js construction and field-operations simulator. It includes six machines, a multi-contract campaign, on-site material handling, equipment-specific guidance, touch controls, and local save progress.

v0.18: the dump truck lays rock base only. Hot mix is the black pile north of the approach. The asphalt paver fills there, lowers its screed, and turns each section black as it creeps west to east.

v0.17 adds per-machine engines, hydraulic whine, a backup alarm, horn (H), impact and tailgate sounds, exhaust smoke, and dust. Volume and mute live in Options. Audio starts after the first tap or key press.

v0.16 play loop: the finished pavement stops at the orange cones. The tan gap between those joints is the unfinished approach. Back the dump truck onto that dirt, raise the bed, and open the gate — rock falls out the rear and only counts there. Girders are 26 m and bear on both banks of the 22 m river. Each contract has its own site. Park the dump truck in the yellow load lane and the yard loader fills the bed. The wheel loader steers as one machine. The crane still has to hook a girder before a deck appears.

## Controls and first steps

- Use the on-screen joystick to drive and steer; the camera follows the active machine.
- Use the equipment buttons to operate the bucket, hook, excavator tools, and other machine functions.
- Follow the job panel and waypoint marker to find the contract board, supply areas, and work zones.
- Open the in-game guide for machine-specific instructions.
- Progress is saved locally in the browser on that device.

## Source and deployment

- `index.html` is the playable game. The GitHub Actions workflow checks the JavaScript module syntax and deploys that file to GitHub Pages.
- `field_ops_3d/parts/` is the older compressed v0.8 source. Pages does not publish it.
- Three.js is loaded from jsDelivr, so an internet connection is required when starting the game.
- The previous BuildWorks prototype remains in Git history and can be restored if needed.

This is an evolving prototype. A successful syntax check does not replace real-device gameplay testing.
