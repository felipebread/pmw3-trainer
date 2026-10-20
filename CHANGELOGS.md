# Changelog

## CT_alpha0001:

- Version Alpha 0001 (Alpha 1.0)
- First cheat table release.
- Added HP and lives editing.
- Added Disable Damage.
- No issues observed during testing.
- Wasn't publicly released.

## CT_alpha0002:

- Version Alpha 0002 (Alpha 1.1)
- Added Infinite Power-Up Duration.
- Confirmed working across all tested levels and power-ups.
- Can be enabled before or after collecting a power-up.
- No issues observed during testing.
- Wasn't publicly released.

## CT_alpha0002_DEBUG_1:

- Added potential pointer for powerup ID
- Development-only build. Not for public release
- Extensive testing confirmed the pointer is stable.

## PMW3GivePowerUp-Alpha1

- First development of a feature that gives Pac-Man powerups anywhere in the game.
- No issues observed during testing. Stable and works across levels.
- Development-only build. Does not include any other features.

## PMW3_CT_beta0001:

- Version Beta 0001 (Beta 1.0)
- First public beta.
- Merged CT_alpha0002_DEBUG_1 and PMW3GivePowerUp-Alpha1
- Added on-demand power-up.
- Available power-ups: Ghost Pellet, Chrome, Slowdown (beta), Loop, Super (Stomp), and Shock.
- Removed the following debug features: activation count, last requested ID, player-object address, and status diagnostic entries.
- Retained the current powerup ID entry and preserved all existing feature names and the cheat-table interface.
- Give Power-Up testing confirmed operation across level changes and game restarts, with or without a power-up already active.
- No issues observed during testing.

## PMW3_CT_beta1_1
- Version Beta 1.1
- Changed the naming scheme from xxxx to x.x
- Added super jump, super speed
- Cleaned up debugging code (reduced table file size by 30%!!!)
- No issues observed during testing.