---
area: "Music & Studio"
tags: [music, rig]
created: 2026-11-21
---

# MIDI Captain 10S — Changelog

Newest at the top. One entry per change pushed to the device.

## 2026-11-21

- Added `page3.txt`, "TR8S TEST", cloned from `page0.txt` (ACST) to test controlling the TR-8S. keyA sends MIDI Start (green light). keyB sends MIDI Stop (red light). The keyA and keyB labels still read Verse and Chorus. Everything else is unchanged from page0. Copied to the pedal drive the same day.
- Renamed `page3.txt` from "TR8S TEST" to "11.21.26". Only the `page_name` line changed. Not copied to the pedal drive yet.
- Updated `page3.txt` ("11.21.26"). keyA (Start) and keyB (Stop) are unchanged.
  - keyC, keyD and keyE select HX Stomp snapshots 1, 2 and 3: ch1 CC69 values 0, 1 and 2. keyE keeps its long press (page down).
  - key1, key2 and key3 are now VE-500 on/off toggles on ch4: reverb CC85 (blue), delay CC87 (orange), harmony CC86 (purple). Each sends 127 on the first press and 0 on the second. The light is lit when on and dark when off. key1 keeps its long press (Load), and key3 keeps its long press (Tuner).
  - Removed from this page: Boost (HX CC53), Mute (RC-600 CC81), tap tempo (BeatBuddy CC117), BeatBuddy Fill (CC112), and the multi-device Stop on keyE.
  - Not copied to the pedal drive yet.

<!-- Template:
## YYYY-MM-DD
- What changed, and why.
-->
