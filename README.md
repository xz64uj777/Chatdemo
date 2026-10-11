# FIELD OPS 3D — Corps Response

The playable game in this repository is **Field Ops 3D**, based on the supplied `field_ops_3d_v08.zip` source (Site Crew v0.8). It replaces the old flat BuildWorks canvas prototype as the published game.

## Play

After the GitHub Pages workflow succeeds: https://xz64uj777.github.io/Chatdemo/

The game is a browser-first Three.js construction and field-operations simulator. It includes five machines, a multi-contract campaign, on-site material handling, equipment-specific guidance, touch controls, and local save progress.

## Controls and first steps

- Use the on-screen joystick to drive and steer; the camera follows the active machine.
- Use the equipment buttons to operate the bucket, hook, excavator tools, and other machine functions.
- Follow the job panel and waypoint marker to find the contract board, supply areas, and work zones.
- Open the in-game guide for machine-specific instructions.
- Progress is saved locally in the browser on that device.

## Source and deployment

- `field_ops_3d/parts/` contains the canonical compressed v0.8 source in ordered binary parts.
- `index.html` is a browser fallback loader; the GitHub Actions workflow reconstructs the original HTML, checks the JavaScript module syntax, and deploys the playable file to GitHub Pages.
- Three.js is loaded from jsDelivr, so an internet connection is required when starting the game.
- The previous BuildWorks prototype remains in Git history and can be restored if needed.

This is an evolving prototype. A successful syntax check does not replace real-device gameplay testing.
