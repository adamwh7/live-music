---
area: "Music & Studio"
tags: [music, rig]
created: 2026-11-21
---

# BOSS VE-500

BOSS vocal effects pedal.

## In the rig

TODO: what this does in the live and recording setup.

## MIDI

Channel 4. Each assign is set to **momentary** mode. The MIDI Captain handles the on/off (latch): it sends 127 to turn an effect on and 0 to turn it off.

| VE-500 assign | CC | Controls |
|---|---|---|
| Assign 1 | CC85 | Reverb |
| Assign 2 | none | Blank: it wouldn't accept a CC |
| Assign 3 | CC87 | Delay. This is the FX1 block, even though the label on the pedal says FX2. |
| Assign 4 | CC86 | Harmony |

The MIDI Captain's page3 "11.21.26" uses these on keys 1, 2 and 3.

## Connections

TODO: what plugs into it and where it goes (MIDI, audio, USB, power).

## Files

`files/` holds exact copies of whatever gets pushed to this device. `firmware/LOG.md` tracks firmware versions. `CHANGELOG.md` logs every change pushed, with the date.

## Editor

Edited with BOSS Tone Studio. See [software/boss-tone-studio](software/boss-tone-studio/README.md).
