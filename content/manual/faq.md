---
title: 'FAQ'
weight: 1
---

### NitrousTracker crashes!

Check if you have the newest version. If not, update. Else, [send a bug report](https://github.com/NitrousTracker/nitroustracker/issues) with reproduction steps immediately!

### How can I convert my songs to MP3?

First, convert your songs to .wav using either a PC tracker like MilkyTracker or using Winamp with the disk writer output plugin. Then, convert the wav file to mp3 using an mp3 encoder like lame.

### When I load a WAV sample, rel-note finetune settings are set to seemingsly random values.

OK, this is a bit unintuitive: In the XM format, samples are all saved with the same base frequency which is 8363 Hz. You cannot have samples at other frequencies, which sucks, but that's how they designed XM.  So, all frequency adjustments are done via the "relative note" and "finetune" settings. Now if you load a sample at some arbitrary sampling frequency intro NitrousTracker, it calculates the relative note and finetune settings such that it is played back at the original frequency even though internally it gets stored at 8386 Hz. This is confusing.

Also note that the frequency of the sound in the sample has **nothing** to do with the rel. note and finetune settings. When loading a sample, NitrousTracker just blindly copies it without even looking at it.

### What's the maximum recording time when recording samples through the microphone?

8 seconds. I'll increase this limit in the future. The sampling rate is 16384Hz and the bit rate is 16, and there's about 3 MiB of RAM (15 MiB on DSi), so in theory the maimum length of a sample can be 96 seconds.

### Can I use a RAM expansion with NitrousTracker?

Unfortunately not. I've looked into using RAM expansions, but the DS's sound hardware cannot play back sound from Slot-2 memory expansions, which makes them pretty useless for NitrousTracker. If you're close to the RAM limit, try reducing the number of samples, cutting samples, use loops in clever ways, or reduce the samples' sampling rates or bit rates using a wav editor like Audacity.

### What file format must my samples be in?

Your samples have to be WAV files without compression, otherwise they will not load or they will sound corrupted. For converting samples, I suggest [Audacity](https://www.audacityteam.org/), [LameDropXPd](http://www.rarewares.org/mp3-lamedrop.php) (for mass-converting mp3s), or FFmpeg for the more command-line inclined. Sampling rate does not matter and bit rate must be either 8 or 16 bit. Keep in mind that NitrousTracker generates different notes by playing back samples at different sampling rates, and that an increase by one octave doubles the playback rate. The DS's hardware mixer runs at 33 kHz, which means that samples above this sampling rate will be downsampled. Stereo samples are supported, but will be converted to mono upon loading. NitrousTracker has about 3 MiB of RAM (15 MiB on DSi) available, which is the total space that your samples may use (the RAM usage of music data is negligible).

### My samples sound corrupted when I load them into NitrousTracker!

Have a look at the previous question :-) Also, check the file system of your card using scandisk, fsck or disk utility.