# Pac-Man World 3 Trainer

A Cheat Engine trainer (currently just a cheat table) for the PC version of **Pac-Man World 3**, with many cool features. Similar to my FPS uncap patch, this also targets the RELOADED NoDisc PAL release.

**Current version: Beta 1.2 (PMW3_CT_beta1_2)**

### AI Disclaimer
<sup><sub>Reported Engagement with AI Level</sub></sup>

*REAL 4: AI models were an active collaborator in the making of this project,*
*generating a major partion of the core content, code and data processing.*

## Features

- **HP** ; change Pac-Man's current health.
- **Lives** ; change the number of remaining lives.
- **Disable damage** ; prevent damage and the associated hit reactions. Falling into a reset hazard can still return Pac-Man to a safe location without taking HP.
- **Infinite Powerup Duration** ; keep a collected or granted power-up active. Can be enabled before or after activating a power-up.
- **Give Power-Up** ; activate Ghost Pellet, Chrome, Slowdown, Loop, Super, or Shock without collecting a pickup. Can also replace an already-active power-up.
*power up IDS: Ghost Power Pellet = 0, Metal Pac = 1, Slowdown = 2, Ribbon Loop = 3, Super Stomp = 4, Shock = 5*
- **Super Speed, Super Jump and Super Bouncinhg** ; multiplies Pac-Man's speed, jump and bounce height values.
- **Infinite Bouncing** ; allows Pac-Man to bounce infinitely
- **Always Strongest Bounce** ; Pac-Man will always perform the 3rd, strongest bounce.

## Usage

1. Open the latest release in Cheat Engine.
2. Start Pac-Man World 3..
3. Click Cheat Engine's process selector (the computer icon) and attach to **PMA_W32_M.exe**.
4. Click a group to expand it and reveal its features.

If Cheat Engine cannot attach or write to the game, ensure both programs have matching administrator permissions.

### Give a power-up

1. While playing a level, under Power-ups, enable **Give Power-Up (enable while playing a level)**.
2. Expand that entry to reveal **REQUEST power-up (edit Value once; NEVER freeze)**.
3. Double-click the request row's **Value** and choose the desired power-up from the dropdown.
4. Return to the game. The selected power-up activates, and the request returns to **Idle / no request**.

Repeat the selection whenever you want to activate another power-up. **Do not check or freeze the REQUEST row**; each selection is intended to request a single activation. Make requests while playing a loaded level.

### Super speed/jump/bouncing

1. Enable your desired feature.
2. Edit the multiplier value to your target.

## Roadmap
☑ HP and lives editing

☑ Damage disabler

☑ Infinite power up duration

☑ On-demand power ups.

☑ Super speed/jump

☑ Infinite bouncing

☐ Save and load coordinates

☐ Proper Trainer and UI

☐ More?

✘ Fly, noclip, other coordinate-based features: Game hates loading Pac-Man while off-bounds (could add in the distant future)

## Tested environment

Developed and tested on two machines running **Windows 10 22H2** using **Cheat Engine 7.6 and 7.7** and the **RELOADED NoDisc PAL version of the game.** *(SHA256 4DDA14F....)*

Compatibility with other game executables, operating systems, or Cheat Engine versions has not been verified.

## Version history

See [CHANGELOGS.md](CHANGELOGS.md) for the version history.

## License

The cheat table and accompanying documentation are available under the [public domain](LICENSE).

This is an unofficial personal project and is not affiliated with the game's developers or publishers. Pac-Man World 3, Cheat Engine and its associated trademarks belong to their respective owners.
