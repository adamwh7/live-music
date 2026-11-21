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

Receives external control on channel 16. CC20 switches pages.

## Connections

TODO: what plugs into it and where it goes (MIDI, USB, power).

## Files

`files/` mirrors the pedal's drive (it shows up as MIDICAPTAIN when plugged into the computer). Page files live in `files/supersetup/` as `page1.txt`, `page2.txt`, and so on. The folder is empty until the files are copied over from the drive.

## Page file rules

The pedal silently skips a page file that breaks any of these:

- The whole file is one `[GlobalSetup]` block.
- No comment lines.
- LF line endings (the Mac/Linux kind, not Windows). The repo's `.gitattributes` keeps these files LF automatically.
- Start every new page by copying a page you know works, then edit the copy. Don't write one from scratch.

## Startup modes

- **Edit mode:** hold Key 1 while powering on. The drive shows up on the computer so you can copy files.
- **SuperMode:** hold Key A while powering on.

## Workflow

Edit the file here, copy it to the pedal's drive, test it, then log the change in `CHANGELOG.md`.
