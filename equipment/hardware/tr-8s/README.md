---
area: "Music & Studio"
tags: [music, rig]
created: 2026-11-21
---

# Roland TR-8S

Roland drum machine.

## In the rig

TODO: what this does in the live and recording setup.

## MIDI

Kit Ch and Pattern Ch must be set to two different channels. Neither is assigned yet (TODO).

### Start/Stop from the MIDI Captain (tested 2026-11-21)

- Cable: MIDI Captain MIDI OUT → TR-8S MIDI IN.
- Captain page3 "TR8S TEST": footswitch A sends Start (`[realtime][start]`), footswitch B sends Stop (`[realtime][stop]`).
- TR-8S settings, under UTILITY → MIDI: Rx Start/Stop = ON, Sync = AUTO.
- **Sync must be AUTO.** It only works on Auto. No other sync setting works.
- The tempo is set on the TR-8S itself. The footswitches only start and stop it.

## Connections

- MIDI IN ← MIDI Captain MIDI OUT.

TODO: audio, USB, power and any other MIDI connections.

## Files

`files/` holds exact copies of whatever gets pushed to this device. `firmware/LOG.md` tracks firmware versions. `CHANGELOG.md` logs every change pushed, with the date.
