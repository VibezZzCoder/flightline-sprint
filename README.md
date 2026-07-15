# Flightline Sprint: Momentum Protocol

A complete three-heat arcade Red Light / Green Light championship in one self-contained, offline Canvas 2D file. It uses fictionalized, stylized, USAF-inspired training-field visuals and requires no installation or network connection.

Play the game at https://vibezzzcoder.github.io/flightline-sprint 
(or simply download a copy and play it locally offline)

## Screenshot

![Flightline Sprint gameplay in a mobile landscape viewport](docs/screenshots/flightline-sprint-mobile-landscape.png)

## Championship

Every championship runs through all three heats:

1. **Brake Check** teaches acceleration, coasting, and precise stops.
2. **Signal Run** adds six-lane pulsing gate banks and score chains.
3. **Final Protocol** combines tighter signals, more gates, faster rivals, placement scoring, and braking precision.

A caught or timed-out heat still awards limited progress points and advances to the next heat. The maximum championship score is 30,000. Bronze starts at 12,000, Silver at 20,000, and Gold requires 25,000 plus completion of all three heats.

## Features

- Momentum-based acceleration, coasting, and predictable braking
- Discrete movement across all six lanes, with lateral motion counted during Red
- Standard, Advanced, and Elite available immediately
- Fixed per-difficulty, per-heat seeds for repeatable record attempts
- Authored pulse gates with Perfect, Good, miss, chain, and multiplier scoring
- Per-difficulty championship, medal, heat, time, and gate-chain records
- Twelve non-colliding visual rivals with deterministic behavior
- Keyboard and mirrored multi-touch controls
- Pause, mute, reduced-motion support, embedded-asset fallbacks, and debug diagnostics
- Embedded visuals and audio with no external runtime requests

## How To Play Locally

Open `flightline-sprint.html` directly in a browser. No install, build step, local server, CDN, package manager, or external runtime dependency is required.

## Keyboard Controls

- `D` or `ArrowRight`: hold to accelerate; release to brake
- `W` or `ArrowUp`: move up one lane
- `S` or `ArrowDown`: move down one lane
- `P`: pause or resume
- `M`: toggle sound
- `F1` or `` ` ``: toggle debug overlay

Menus use normal buttons and can be navigated with the keyboard.

## Touch Controls

- Hold either bottom-corner `Hold ▶ Move` button to accelerate.
- Use the adjacent `▲` and `▼` buttons to change one lane at a time.
- Both mirrored control pods support multi-touch and either-thumb play.

## Scoring

- Gate Perfect: 500 base points
- Gate Good: 300 base points
- Each successful consecutive bank adds `0.25×`, capped at `2×`
- A miss resets the chain
- Every heat is normalized to 10,000 points
- Failed heats lose completion/time/placement bonuses and are capped at 3,500

## Records And Privacy

Records are stored locally and separately for Standard, Advanced, and Elite. If browser storage is unavailable or blocked, the game safely keeps records for the current session only. There are no accounts, analytics, network leaderboards, or online services.

## Project Status

`Momentum Protocol` is the current full-game mode. The exact source and playable release artifact is `flightline-sprint.html`; there is no separate build output.

## License

This project is licensed under the GNU General Public License v3.0 or later.

Copyright (C) 2026 VibezZzCoder

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

See `LICENSE` for the full license text.

## Unofficial Project Disclaimer

This is an independent project. It is not an official U.S. Air Force product. It is not endorsed by, sponsored by, or affiliated with the U.S. Air Force, the Department of the Air Force, or the U.S. Department of Defense.

The project uses fictionalized, stylized, military-inspired characters and settings. No official endorsement is implied.

## Trademarks And Official Marks

The GPL applies to this project's original code and original assets. It does not grant rights to use third-party trademarks, logos, seals, emblems, official marks, official insignia, or protected identifiers.

Do not imply ownership of or affiliation with the U.S. Air Force, Department of the Air Force, or Department of Defense.

## Korean Voiceover Credits

Green light red light by Sandermotions -- https://freesound.org/s/592876/ -- License: Creative Commons 0
