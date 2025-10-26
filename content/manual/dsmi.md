---
title: 'MIDI support (DSMI)'
weight: 90
---

{{< hint type=warning >}}
WiFi support has not been extensively tested by the NitrousTracker fork's developers. Caveat emptor.
{{< /hint >}}

### Who can NitrousTracker talk to?

NitrousTracker uses
[DSMI](https://web.archive.org/web/20150205173143/http://dsmi.tobw.net/)
for MIDI support. So, it can interact with MIDI software on any platform
(Linux, MacOS, Windows all work). It can act both as a receiver and a
sender of MIDI messages. Using a
[DSerial](https://web.archive.org/web/20150205173143/http://www.natrium42.com/shop/dserial2.php)
device and a special [MIDI cable](https://web.archive.org/web/20150205173143/http://www.natrium42.com/wiki/MIDI),
NitrousTracker can also send MIDI messages to MIDI hardware like
synthesizers, but it cannot yet receive MIDI messages from other MIDI
hardware. Unfortunately, the DSerial is not produced any more. I\'m
working on other hardware MIDI solutions, so stay tuned!

### How to connect NitrousTracker to MIDI software or hardware

It\'s easy! Just go to the settings tab and press connect. If a DSerial
is plugged in, NitrousTracker will use it, otherwise it will connect to
the wireless LAN and use wireless MIDI. The send and receive checkboxes
enable sending and receiving of MIDI messages (D\'uh! :) Refer to the
[DSMI documentation](https://web.archive.org/web/20150205173143/http://dsmi.tobw.net/index.php?cat_id=3)
for instructions on how to set up DSMIDIWifFi on your computer and check
the [troubleshooting page](https://web.archive.org/web/20150205173143/http://dsmi.tobw.net/index.php?cat_id=2)
in case something doesn\'t work right.

![](/nitroustracker/content/dsmi.png)

### What does NitrousTracker send/receive?

The only message type supported as of now are note-on and note-off
events. Timers and CCs will probably follow.

NitrousTracker sends MIDI note events both when you\'re jamming on the
keybaord and playing back a song. The MIDI channel corresponds to the
instrument. Likewise, when NitrousTracker receives MIDI events, it plays
the instrument that corresponds to the MIDI channel.