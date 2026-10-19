# FIELD OPS 3D — Corps Response

The playable game in this repository is **Field Ops 3D**, based on the supplied `field_ops_3d_v08.zip` source (Site Crew v0.8). It replaces the old flat BuildWorks canvas prototype as the published game.

## Play

After the GitHub Pages workflow succeeds: https://xz64uj777.github.io/Chatdemo/

The game is a browser-first Three.js construction and field-operations simulator. It includes five machines, a multi-contract campaign, on-site material handling, equipment-specific guidance, touch controls, and local save progress.

v0.11 play loop: the wheel loader articulates at the center hitch, and the bucket only fills when the cutting edge is in the stockpile ($12/t) or a spoil mound (free). Tip into the dump truck. The truck hauls to the green road marker, raises the bed, then opens the tailgate to pour. The D7 pushes a windrow and grades with the blade down. Paving is a PAVE button on the truck. The crane hooks a girder off the beam rack and sets it over the abutment — the deck does not appear without a girder on the hook. The excavator keeps soil in the bucket until you dump it clear of the cut. Fuel is per machine. The top marker points at the current task.

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
