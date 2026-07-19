---
title: 'Limitations'
weight: 15
---

NitrousTracker is designed around the DS sound hardware. This informs some limitations of the tracker's functionality.

## Playback

- Songs which use more than 16 channels are not supported in the DS version of the tracker.
- Sample loop points are rounded up to a multiple of 2 samples (for 16-bit samples) or 4 samples (for 8-bit samples).

## Effects

- The sample offset effect (`9XX`) is fully implemented for non-looping samples. For looping samples, however, it will only work if the offset position is before the loop start; otherwise, the offset command is ignored.
- The playback routine operates under a 6 dB panning law (i.e. a centered sound is half the amplitude in each channel as a fully-panned sound). This means panned instruments will have a wider soundstage than on other players, which generally follow a 3 dB panning law.
  However, other DS audio engines (such as [maxmod](https://maxmod.org/) and [libxm7](https://github.com/sverx/libxm7)) also follow the 6 dB panning law.
