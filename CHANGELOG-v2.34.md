# v2.34 update

- Restored the original purple laser rendering/effects and used three independent effect instances for three simultaneous horizontal beams.
- Reduced black-hole rendering workload with lower-resolution rendering and fewer nebula/spiral/particle elements while keeping the same effect design.
- Fixed card-pack modal overflow; card backs now flip to reveal card faces.
- Added gear-based audio settings: music volume, sound-effects volume, and global sound toggle; settings persist locally.
- Reduced the catalog to 14 cards.
- Added permanent card-slot upgrade: starts at one slot, maximum five; first cost 500 coins and each next upgrade increases by 50%.
- Active card effects are combined when multiple cards are equipped.

## Validation
JavaScript syntax checks passed. ZIP integrity checked. Maven tests/build could not be run because Maven is not installed in this environment.
