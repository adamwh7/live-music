---
area: "Music & Studio"
tags: [music, rig]
created: 2026-11-21
---

# MIDI Captain 10S

Paint Audio foot controller. Ten switches that send MIDI to the rest of the rig. Running firmware FW5.1 in SuperMode.

## In the rig

TODO: what this does in the live and recording setup.

## MIDI

Receives external control on channel 16. The knob (encoder) sends CC20 on channel 1, per `page0.txt`.

TODO: page switching over MIDI on channel 16 isn't confirmed yet. Which message does it and how?

## Connections

TODO: what plugs into it and where it goes (MIDI, USB, power).

## Files

`files/` mirrors the pedal's drive (it shows up as MIDICAPTAIN when plugged into the computer). Page files## Page file guidelines

These are habits, not hard rules:

- Start every new page by copying a page you know works, then edit the copy.
- Use one `[GlobalSetup]` block, LF line endings (the Mac/Linux kind, not Windows) and no comment lines. The repo's `.gitattributes` keeps page files LF automatically.

An older note said the pedal skips any page that breaks these. That came from one file that failed to load. `page2.txt` (MOM) has a lowercase `[globalsetup]` header and 11 comment lines, and it still loads on the pedal. So neither of those stops a page from loading. Why the original file failed is still unknown.

these files LF automatically.
- Start every new page by copying a page you know works, then edit the copy. Don't write one from scratch.

## Startup modes

- **Edit mode:** hold Key 1 while powering on. The drive shows up on the computer so you can copy files.
- **SuperMode:** hold Key A while powering on.

## Workflow

Edit the file here, copy it to the pedal's drive, test it, then log the change in `CHANGELOG.md`.
