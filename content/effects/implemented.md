---
title: 'Implemented effects'
weight: 15
---

## Standard effect commands

| Effect | Description               | Status              |
|--------|---------------------------|---------------------|
| `0XY`  | arpeggio                  | implemented         |
| `1XX`  | portamento up             | partially implemented[^2]|
| `2XX`  | portamento down           | partially implemented[^2]|
| `3XX`  | portamento to note        | implemented         |
| `4XY`  | vibrato                   | implemented         |
| `5XX`  | portamento + volume slide | **not implemented** |
| `6XX`  | vibrato + volume slide    | **not implemented** |
| `7XY`  | tremolo                   | **not implemented** |
| `8XX`  | set note panning position | implemented         |
| `9XX`  | sample offset             | partially implemented[^1]|
| `AXY`  | volume slide              | implemented         |
| `BXX`  | jump to order             | implemented         |
| `CXX`  | set note volume           | implemented         |
| `DXX`  | pattern break             | implemented         |

## Exy commands (E subcommands)

| Effect | Description               | Status                           |
|--------|---------------------------|----------------------------------|
| `E0X`  | amiga LED filter toggle   | **not implemented, not planned** |
| `E1X`  | fine portamento up        | implemented                      |
| `E2X`  | fine portamento down      | implemented                      |
| `E3X`  | glissando control         | **not implemented**              |
| `E4X`  | vibrato control           | **not implemented**              |
| `E5X`  | set note fine-tune        | **not implemented**              |
| `E6X`  | pattern loop              | **not implemented**              |
| `E7X`  | tremolo control           | **not implemented**              |
| `E8X`  | set note panning position | **not implemented**              |
| `E9X`  | retrigger note            | **not implemented**              |
| `EAY`  | fine volume slide up      | **not implemented**              |
| `EBX`  | fine volume slide down    | **not implemented**              |
| `ECX`  | note cut                  | partially implemented                      |
| `EDY`  | note delay                | implemented                      |
| `EEX`  | pattern delay             | implemented                      |
| `EFX`  | "funk it"                 | **not implemented, not planned**                  |

## Extended/FT2 commands

| Effect | Description                       | Status              |
|--------|-----------------------------------|---------------------|
| `GXX`  | set global volume                 | **not implemented** |
| `HXY`  | global volume slide               | **not implemented** |
| `KXX`  | key-off                           | **not implemented** |
| `LXX`  | set envelope position             | **not implemented** |
| `PXY`  | panning slide                     | **not implemented** |
| `RXY`  | re-trigger note with volume slide | **not implemented** |
| `TXY`  | tremor                            | **not implemented** |
| `X1X`  | extra fine portamento up          | implemented[^3]     |
| `X2X`  | extra fine portamento down        | implemented[^3]     |

## Volume column commands

| Effect | Description                               | Status              |
|--------|-------------------------------------------|---------------------|
| `xx`   | set note volume                           | implemented         |
| `+x`   | volume slide up                           | **not implemented** |
| `-x`   | volume slide down                         | **not implemented** |
| `Dx`   | fine volume slide down (displayed as  ▼x) | **not implemented** |
| `Lx`   | panning slide left (displayed as  ◀x)     | **not implemented** |
| `Mx`   | portamento to note                        | **not implemented** |
| `Px`   | set note panning position                 | **not implemented** |
| `Rx`   | panning slide right (displayed as  ▶x)    | **not implemented** |
| `Sx`   | set vibrato speed                         | **not implemented** |
| `Ux`   | fine volume slide up (displayed as  ▲x)   | **not implemented** |
| `Vx`   | vibrato                                   | **not implemented** |

[^1]: Fully implemented for non-looping samples. For looping samples, will only work if the offset position is before the loop start, otherwise the offset command is ignored.

[^2]: Portamento commands are not currently fully accurate.

[^3]: `X1x` and `X2x` are supported by the playback engine, however as of NitrousTracker 0.6.1, have not been enabled in the effects keyboard. 