# Tactical Fighter Battles — Demo

This repository hosts the Windows demo download for Tactical Fighter Battles, a turn-based tactical hex wargame. Jet fighters and attack aircraft fight over a hex map with NATO-style counters. It is a board game that runs on a computer, not a flight simulator.

Source code is not in git and is not licensed. The playable build is a GitHub Release asset.

## Files in git

- `README.md` — download and play notes
- `LICENSE` — all rights reserved (Copyright © 2026 BSC Netowkrs, as written in the file)
- `.gitignore` — ignores `*.zip`, `*.exe`, `*.apk`, and `*.aab`; binaries are not committed

## Release

One published release, not a prerelease:

- **DEMO - 1.2.0** (tag `demo-1.2.0`, published 2026-09-06)
- Asset: [`TacticalFighterBattles-DEMO-1.2.0-windows.zip`](https://github.com/SaracorDev/Tactical-Fighter-Battles-Demo/releases/download/demo-1.2.0/TacticalFighterBattles-DEMO-1.2.0-windows.zip) (103,390,301 bytes)
- Release page: https://github.com/SaracorDev/Tactical-Fighter-Battles-Demo/releases/tag/demo-1.2.0

## How to run

Download the zip from Releases, unzip it anywhere, and double-click `TacticalFighterBattles.exe`. Godot does not need to be installed.

Published requirements: 64-bit Windows 10 or 11, and a GPU with Vulkan. Windows SmartScreen may warn because the build is unsigned (**More info** → **Run anyway**). A black window or an immediate exit can mean the GPU does not support Vulkan.

Published demo scope: United States and USSR only; eras 1–3 (1945–1990); dogfight and base destruction, plus three tutorials. No pilots, no campaigns, no extra nation packs. You command the attacker; defending jets intercept on their own. Gold hexes are the next step; grey hexes are where you can finish a fly.

## License

All rights reserved. Personal, non-commercial play is allowed. Original JSON add-ons (units, weapons, maps, missions, and similar data) may be written and shared. Copying, redistributing, or selling the game, executable, art, audio, or shipped data is not allowed. The Windows build bundles Godot, which is MIT-licensed by its authors. No warranty. See `LICENSE`.

## Status

Current public demo is **1.2.0**. Git history is one commit on `main`: `045642d` (“Add demo download README and license. No source.”), tagged `demo-1.2.0`. Tracked files contain no TODOs.

Last updated: 2026-10-17
