---
title: 'Reference card'
weight: 100
---

![](/nitroustracker/content/reference/ref.png)

## Tabs

![](/nitroustracker/content/reference/songtab.png) **The song tab**

Opens song controls, where you can change several song parameters.

![](/nitroustracker/content/reference/disktab.png) **The disk tab**

Opens the file browser there you can load and save samles and songs.

![](/nitroustracker/content/reference/sampletab.png) **The sample tab**

Here you can view and samples, record your own, make loops and tweak
sample properties.

![](/nitroustracker/content/reference/instab.png) **The instruments tab**

Here you can tune your instrument by making envelopes and assigning
samples to notes for multi-sample instruments.

![](/nitroustracker/content/reference/settingstab.png) **The settings tab**

Adjust settings to your preferences and connect to MIDI software or
hardware.

## ![](/nitroustracker/content/reference/songtab.png)&nbsp;Song controls

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/potctrls.png) | \"ins\" inserts the current pattern into the pattern order table at the current position.<br>\"cln\" clones the current pattern.<br>\"del\" deletes the highlighted pattern.<br>\"\<\" chooses the previous pattern<br>\"\>\" chooses the next pattern |
| ![](/nitroustracker/content/reference/channels.png) | \"sub\" deletes the last channel (in all patterns).<br>\"add\" adds a new channel after the last (in all patterns) |
| ![](/nitroustracker/content/reference/ramview.png) | Shows you the amount of used RAM. If this tuns red, better clean up! |
| ![](/nitroustracker/content/reference/ptnlen.png) | Changes the length of the current pattern (Usage: Put your pen down anywhere on the numberslider and slide the pen up or down) |
| ![](/nitroustracker/content/reference/speed.png) | \"tmp\" defines the tempo (coarse speed) lower = faster.<br>\"bmp\" defines the bpm (fine speed) lower = slower. |
| ![](/nitroustracker/content/reference/restartpos.png) | \"restart\" defines the position from where the song is restarted when it has reached the end. |
| ![](/nitroustracker/content/reference/name.png) | \"\...\" shows a typewriter for changing the name of the song |
| ![](/nitroustracker/content/reference/zap.png) | Shows a dialog box for zapping the patterns, the instruments or the entire song. |

## Editing / playback controls

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/keyboard.png) | This, ladies and gentlemen, is called a \"keyboard\". (Not actual size) |
| ![](/nitroustracker/content/reference/stopplay.png) | D\'uh! |
| ![](/nitroustracker/content/reference/loopptn.png) | Toggles pattern looping. |
| ![](/nitroustracker/content/reference/record.png) | Toggles record mode. |
| ![](/nitroustracker/content/reference/flp.png) | Flips the screens. |
| ![](/nitroustracker/content/reference/add.png) | Defines how many rows to scroll forward in the pattern when a note is entered. |
| ![](/nitroustracker/content/reference/oct.png) | Defines the base octave of the keyboard, i.e. if the value is 4, the leftmost key on the keyboard plays a C-4. |
| ![](/nitroustracker/content/reference/ins.png) | Inserts an empty note under the cursor, moving all notes below it down one row. |
| ![](/nitroustracker/content/reference/del.png) | Deletes the note under the cursor, moving all all notes below it up one row. |
| ![](/nitroustracker/content/reference/clr.png) | Deletes the note under the cursor. |
| ![](/nitroustracker/content/reference/stp.png) | Enters a stopnote, i.e. a silent note that stops the previously toggled note. |
| ![](/nitroustracker/content/reference/renplus.png) | \"ren\" shows a typewriter for renaming the currently selected instrument<br>\"+\" toggles the sample list forthe current sample and shows the sample mappings on the keyboard. |

## Pattern controls on the pattern screen

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/ms.png) | \"m\" mutes the channel.<br>\"s\" makes the channel play solo. You can select \"s\" on several channels to hear only these channels. |
| ![](/nitroustracker/content/reference/mutenone.png) | Unmutes / un-solos all channels. |
| ![](/nitroustracker/content/reference/vol.png) | The volume of the selected notes in the pattern. |
| ![](/nitroustracker/content/reference/cutcppst.png) | Cut, copy, paste the selected notes in the pattern. Paste pastes to the current cursor position. |
| ![](/nitroustracker/content/reference/sel.png) | Select whole column(s): make a selection over the columns you want to select and press this button. Without an existing selection, the column under the cursor is selected. |

## Sample controls

### ![](/nitroustracker/content/reference/smpedittab.png)&nbsp;Sample editor

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/smprec.png) | Record a sample with the microphone. Either hold A while recording, or press B to start/stop recording. |
| ![](/nitroustracker/content/reference/smpsel.png) | Selects all / nothing |
| ![](/nitroustracker/content/reference/smpfade.png) | Fades the selection in / out. If there is no selection, the whole sample is used. |
| ![](/nitroustracker/content/reference/smpamplitude.png) | Brings up a dialog for changing the sample amplitude. |
| ![](/nitroustracker/content/reference/smpreverse.png) | Reverses the selected part of the sample. If there is no selection, the whole sample is used. |
| ![](/nitroustracker/content/reference/smpdel.png) | Deletes the selected part. |

### ![](/nitroustracker/content/reference/smpsettingstab.png)&nbsp;Sample settings

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/smpvol.png) | Adjusts the sample volume (0 - 64). |
| ![](/nitroustracker/content/reference/pan.png) | Adjusts the sample\'s stereo panning (0 - 128). |
| ![](/nitroustracker/content/reference/smprelnote.png) | Sets the note relative to C-4 on the keyboard. |
| ![](/nitroustracker/content/reference/smpfinetune.png) | Fine-tunes the note (-128 - 127). |

### ![](/nitroustracker/content/reference/looptab.png)&nbsp;Loop settings

In this mode, loop points are displayed in the sample display, defining
the beginning and end of the loop.

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/looptypes.png) | \"none\" disables looping.<br>\"forward\" makes the selected region play in a forward loop.<br>\"ping-pong\" makes the selected region play in a loop forward and backward. |
| ![](/nitroustracker/content/reference/snap.png) | Snap to zero crossings: When you move the loop points, they are snapped to the closest zero crossing the sample to avoid clicking. |

## ![](/nitroustracker/content/reference/instab.png)&nbsp;Instrument controls

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/envon.png) | Enables / disables the volume envelope for this instrument. |
| ![](/nitroustracker/content/reference/drawenv.png) | Lets you draw a new envelope with the stylus. |
| ![](/nitroustracker/content/reference/adddel.png) | Add a new loop point after the selected one or<br/>Delete the selected loop point. |
| ![](/nitroustracker/content/reference/plusminus.png) | Zoom in or out. |

## Settings

| Widget | Description |
| - | - |
| ![](/nitroustracker/content/reference/handedness.png) | Choose if you\'re left-handed or right-handed. For lefties, the functions of the D-pad and the ABXY buttons are swapped. |
| ![](/nitroustracker/content/reference/dsmw.png) | [DSMIDIWiFi](https://web.archive.org/web/20150205173143/http://dsmidiwifi.tobw.net/) settings. \"connect\" connects to the access point. Sending and receiving can be toggled independently. |

## Button controls

| Button | Description |
| - | - |
| D-Pad | Scrolls in the pattern |
| B  | Accelerates vertical scrolling. |
| Start | Starts / pauses playback. |
| Select | Stops playback. |
| X or L | Flips the screens. |
| R + Up / Down | Scrolls to the beginning / end of the pattern. |
| Lid | Yes, the lid is a button :-)<br>Closing enters standby mode.<br>Opening leaves standby mode. |
| L + R + Start + Select | Force-reset the DS. |
