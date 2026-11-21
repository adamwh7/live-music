---
area: "Music & Studio"
tags: [music, rig]
created: 2026-11-21
---

# Live Music Rig

This repo is the one place that holds everything about my live and recording rig. If it gets loaded onto a piece of gear, a copy lives here. If a firmware or app gets updated, it's logged here. If someone needs to know how the rig is wired, the diagram is here.

## What's in it

- **`equipment/hardware/`** has one folder per device. Each one has:
  - `README.md`: what the device does in the rig, its MIDI channel, and how it's connected.
  - `files/`: exact copies of what gets pushed to the device.
  - `firmware/LOG.md`: firmware versions over time.
  - `CHANGELOG.md`: a dated entry for every change pushed to the device.
  - `software/`: notes on the editor app, if the device has one.
- **`equipment/software/`** covers apps that aren't tied to one device: OnSong and Ableton.
- **`docs/`** holds the visual docs (signal flow, cabling, MIDI clock chain). These are published as a website through GitHub Pages.

## Devices

| Device | MIDI channel |
|---|---|
| [MIDI Captain 10S](equipment/hardware/midi-captain-10s/README.md) | 16 (receive; page switching TODO) |
| [HX Stomp](equipment/hardware/hx-stomp/README.md) | 1 |
| [RC-600](equipment/hardware/rc-600/README.md) | 2 |
| [BeatBuddy](equipment/hardware/beatbuddy/README.md) | 3 |
| [VE-500](equipment/hardware/ve-500/README.md) | 4 |
| [Nord Electro 3](equipment/hardware/nord-electro-3/README.md) | 5 |
| [TR-8S](equipment/hardware/tr-8s/README.md) | TODO (Kit and Pattern need separate channels) |
| [X-Air 18](equipment/hardware/x-air-18/README.md) | TODO |
| [APC40](equipment/hardware/apc40/README.md) | TODO |
| [U6MIDI Pro](equipment/hardware/u6midi-pro/README.md) | TODO (MIDI interface/router) |

## The one rule

Change the file here first, push it to the gear, and then add a line to that device's `CHANGELOG.md`. If the repo and the gear ever disagree, the repo is wrong and gets fixed.

## Heads up

This repo is public. Keep passwords, Wi-Fi keys and contact details out of it.
