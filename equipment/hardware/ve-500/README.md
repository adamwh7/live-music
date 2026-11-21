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

Channel 4. Each assign is set to toggle mode, controlled by a CC (a numbered MIDI control message):

| VE-500 assign | CC | Controls |
|---|---|---|
| Assign 1 | CC85 | Reverb (FX1) |
| Assign 2 | none | Skipped: it wouldn't accept a CC |
| Assign 3 | CC86 | Harmony |
| Assign 4 | CC87 | Delay |

The MIDI Captain's page3 "11.21.26" uses these on keys 1, 2 and 3.

## Connections

TODO: what plugs into it and where it goes (MIDI, audio, USB, power).

## Files

`files/` holds exact copies of whatever gets pushed to this device. `firmware/LOG.md` tracks firmware versions. `CHANGELOG.md` logs every change pushed, with the date.

## Editor

Edited with BOSS Tone Studio. See [software/boss-tone-studio](software/boss-tone-studio/README.md).
