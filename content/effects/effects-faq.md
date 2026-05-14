---
title: 'Effects FAQ'
weight: 15
---

## Why doesn't pressing on an effect do anything?

You need to be in record mode to input effects, similar to recording piano keystrokes. You also can only input effects which are implemented in NitrousTracker - pressing a greyed out effect will only display its description.

## Why are some effects greyed out?

They're not implemented yet by NitrousTracker's playback engine (a [fork](https://github.com/nitroustracker/libntxm) of [libntxm](https://github.com/0xtob/libntxm)). To see in detail which effects are supported, see [Implemented effects](./implemented.md).

## I entered an effect, but it didn't do anything.

Depending on the version of NitrousTracker you're using, the effects keyboard might have indicated that an effect is usable, despite it not being implemented (sorry!).

If an effect is listed as implemented but doesn't work, please [open an issue](https://github.com/NitrousTracker/nitroustracker/issues).

## Why doesn't the sample offset command work properly?

### The sample just plays from the beginning.

Due to limitations of the audio hardware of the Nintendo DS, currently, `09xx` is a 'best effort' implementation and only works properly when the sample either has no loop, or when the `09xx` command is for an offset **before** the loop start. Otherwise, it will just play from the start.

### The sample doesn't play at all.

`09xx`, in the XM format, is implemented differently to ProTracker's `09xx`. Instead of splitting the sample up into units of 1/256th, XM offset uses a fixed amount, that is, the sample's offset can be adjusted in fixed steps of 256 PCM samples. For short samples, a `09xx` command might jump past the end of the sample.

## I want (use "lerp"/"clr" / apply an effect command / apply an effect parameter) with many notes selected, but my selection disappears when I swap screens.

You need to be in FX mode before making your selection. Otherwise, it will be cleared when you switch screens.