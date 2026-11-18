# Pad → MIDI

A single web page that turns a USB or Bluetooth game controller into a MIDI note/CC controller.

**Live:** https://gghostdadd.github.io/gamepad-midi/

## Use

1. Open the page in **Chrome or Edge** (Safari has no Web MIDI).
2. Allow MIDI access, then press any button on the controller.
3. Pick a MIDI output.
   - Mac: enable the **IAC Driver** in Audio MIDI Setup → MIDI Studio.
   - Windows: install **loopMIDI** and add a port.
4. Keep the browser window open (it can sit behind other apps, just not minimized).

## Features

- Every button sends a note; each note is editable and saved per controller.
- Axes can send notes for − / + directions, act as a hat-switch D-pad (4 notes), send CC, or be turned off.
- Controller picture lights up with input and shows each part's note. Click a part, then press a control to re-learn it (Shift-click clears, Esc cancels).
- Channel, velocity, optional analog-button velocity, renumber from a first note, and an all-notes-off panic button.

Note names use 60 = C4.
