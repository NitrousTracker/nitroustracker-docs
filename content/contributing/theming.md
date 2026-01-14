---
title: 'Theming'
weight: 20
---

`.nttheme` files can be used to create NitrousTracker themes.

## .nttheme format

The format consists of `ID=hexcode` pairs, written like so:

```
0=000000 ; Background
1=000000 ; Envelope editor background
2=2c3034 ; Medium background
```

Unspecified colors are filled in with either the closest color by definition,
to preserve backwards compatibility, or with the default theme's color if that
is not possible.

### List of color IDs

| ID | Description |
| -- | ----------- |
| 0 | Background |
| 1 | Envelope editor background |
| 2 | Medium background |
| 3 | Light background |
| 4 | Lighter background |
| 5 | Light control / button gradient 1 |
| 6 | Dark control / button gradient 2 |
| 7 | Light control (disabled) |
| 8 | Dark control (disabled) |
| 9 | Selected tab |
| 10 | Unselected tab |
| 11 | List item gradient 1 |
| 12 | List item gradient 2 |
| 13 | List item gradient 1 (highlighted) |
| 14 | List item gradient 2 (highlighted) |
| 15 | Scrollbar background gradient 1 |
| 16 | Scrollbar background gradient 2 |
| 17 | Scrollbar thumb (inactive) |
| 18 | Scrollbar thumb (active) |
| 19 | Scrollbar arrow background gradient 1 |
| 20 | Scrollbar arrow background gradient 2 |
| 21 | Widget outline |
| 22 | Tab/tab box outline |
| 23 | List item separator line |
| 24 | Tab icon |
| 25 | Button icon and scrollbar arrows |
| 26 | Checkmark |
| 27 | Text |
| 28 | Text (light) |
| 29 | Text (buttons) |
| 30 | Text (value input) |
| 31 | Text (list items) |
| 32 | Text (highlighted list item) |
| 33 | Recording/signal (red) |
| 34 | Recording/signal (off, dark red) |
| 35 | Piano mapping label (naturals) |
| 36 | Piano mapping label (inverted, sharps) |
| 37 | Loop points |
| 38 | Envelope sustain line |
| 39 | Envelope line |
| 40 | Envelope point fill |
| 41 | Envelope point outline |
| 42 | Envelope point outline (active) |
| 43 | Memory usage: OK |
| 44 | Memory usage: Warning |
| 45 | Memory usage: Alert |
| 46 | Text entry cursor |
| 47 | Sample editor background |
| 48 | Sample editor background (selection) |
| 49 | Sample editor waveform |
| 50 | Sample editor waveform (selection) |
| 51 | Pattern - background |
| 52 | Pattern - channel number |
| 53 | Pattern - lines |
| 54 | Pattern - sublines |
| 55 | Pattern - lines (recording) |
| 56 | Pattern - cursor bar gradient 1 |
| 57 | Pattern - cursor bar gradient 2 |
| 58 | Pattern - cursor bar gradient 1 (highlight) |
| 59 | Pattern - cursor bar gradient 2 (highlight) |
| 60 | Pattern - row numbers |
| 61 | Pattern - notes |
| 62 | Pattern - notes (dark) |
| 63 | Pattern - instruments |
| 64 | Pattern - instruments (dark) |
| 65 | Pattern - volume |
| 66 | Pattern - volume (dark) |
| 67 | Pattern - effect command |
| 68 | Pattern - effect command (dark) |
| 69 | Pattern - effect parameter |
| 70 | Pattern - effect parameter (dark) |
| 71 | Pattern - selection |
| 72 | Pattern - row outline |
| 73 | Pattern - cursor outline |
| 74 | Pattern - mute/solo text color |
| 75 | Pattern - mute/solo gradient 1 |
| 76 | Pattern - mute/solo gradient 2 |
| 77 | Pattern - mute/solo gradient 1 (highlight) |
| 78 | Pattern - mute/solo gradient 2 (highlight) |
| 79 | Pattern - row numbers (highlight) |
| 80 | List item separator line (vertical) |
| 81 | Togglebutton background |
| 82 | Togglebutton text (off) |
| 83 | Togglebutton text (on) |
| 84 | Piano - full key color 1 |
| 85 | Piano - full key color 2 |
| 86 | Piano - half key color 1 |
| 87 | Piano - half key color 2 |
| 88 | Piano - full key color 1 (highlight) |
| 89 | Piano - full key color 2 (highlight) |
| 90 | Piano - half key color 1 (highlight) |
| 91 | Piano - half key color 2 (highlight) |
| 92 | Piano - outline |
| 93 | Text entry background |
| 94 | Text entry keys |
| 95 | Text entry key labels |
| 96 | Text entry modifier keys |
| 97 | Text entry pressed keys |
| 98 | Text entry modifier key labels |
| 99 | Sample editor zoom buttons |
| 100 | Message box title bar gradient 1 |
| 101 | Message box title bar gradient 2 |
| 102 | Message box title bar text |
