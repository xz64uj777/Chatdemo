# FIELD OPS 3D — Corps Response

The playable game in this repository is **Field Ops 3D**, based on the supplied `field_ops_3d_v08.zip` source (Site Crew v0.8). It replaces the old flat BuildWorks canvas prototype as the published game.

## Play

After the GitHub Pages workflow succeeds: https://xz64uj777.github.io/Chatdemo/

The game is a browser-first Three.js construction and field-operations simulator. It includes five machines, a multi-contract campaign, on-site material handling, equipment-specific guidance, touch controls, and local save progress.

v0.12 play loop: girders are 26 m and bear on both banks of the 22 m river. Each contract has its own site — flood control is the basin, the quarry road is the north-south lane, storm drain stays on the trench, and the depot yard is beside the warehouse. The D7 blade pushes a heightfield, a loaded truck leaves ruts, and the river bank is soft. Park the dump truck in the yellow load lane and the yard loader fills the bed. A clock and weather run over the site; rain slows the machines. Wear is serviced at the fuel island. The wheel loader steers as one machine again. The dump truck starts on the yellow load lane beside the pile. The crane still has to hook a girder before a deck appears.

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
