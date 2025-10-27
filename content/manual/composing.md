---
title: 'Composing'
weight: 20
---

Now we come to the fun part. To record a song, press the \"record\"
button that is under the \"ren\" button. This button toggles record
mode. Now, when you press a key on the keyboard, an entry is added to
the pattern (the strange table on the top screen that we\'ve been
ignoring so far). Just try it out. Something like this will occur:

![](/nitroustracker/content/tracking/step5.png)

Here, blue stands for the note, orange for the instrument and green for
the volume. The first blue character is the note itself, in this case an
\"H\". The blue \"4\" is the octave of the note. You can chance the base
octave using the \"oct\" numberbox. The orange \"2\" means that we have
used instrument nr. 2 and the green \"FF\" is a hex value that means
that this note is played at maximum volume, which is standard.

The pattern is played from top to bottom. I.e. when you press \"play\",
it scrolls down and plays the notes, row after row. By pushing the d-pad
left or right, you can switch channels. Two notes that are in the same
row on different channels are played at the same time. To get some
practice, try to track the following:

![](/nitroustracker/content/tracking/step6.png)

The first channel is a drum pattern and the second channel is a stupid
melody, known as the swedish car symphony (it\'s not very famous). When
you make a mistake, you can just scroll up with the d-pad and correct
it. To clear a note, press the \"clr\" key right of the keyboard.
Holding the B button with accelerate scrolling.

![](/nitroustracker/content/tracking/step7.png)

You can also press the \"flp\" button on the top right of the screen and
make selections in the pattern by dragging the stylus. The \"cpy\"
button copies the selected area to the clipboard. The \"pst\" button
pastes it with the upper right corner at the current cursor position.

When you\'re ready, press the play button to listen to this annoying
song. You will realize that the pattern goes on even after the melody is
finished.

To change this, tap the note icon. This will bring you to the song view.
There is a numberslider named \"ptn len\". It\'s used by putting the
stylus down anywhere on it and then sliding it up or down. In our case,
we slide it down until the number reaches 20. When you scroll down in
the pattern using the d-pad, you will see that the pattern now ends at
the same time as the song.

![](/nitroustracker/content/tracking/step8.png)

Now we want our patterns to be looped three times to make the song even
more annoying. For this, we edit the pattern order table (the table on
the left). It currently has one entry that sais \"0 0\". This means that
pattern 0 is played at position 0. You can change the pattern by using
the \"\<\" and \"\>\" buttons right to it. Pushing \"\>\" will
automatically create a new empty pattern of the same size as the current
one. but since we only want one pattern, change it back to 0.

![](/nitroustracker/content/tracking/step9.png)

Press the \"ins\" button twice to insert the current pattern into the
pattern order table two more times. If you press play now, the pattern
will be played three times and you will notice how the highlighted item
in the pattern order table changes automatically.

![](/nitroustracker/content/tracking/step10.png)

Think that your song is too slow or too fast? Change the speed with the
\"tmp\" and \"bpm\" number boxes.

![](/nitroustracker/content/tracking/step11.png)

Currently the name of our song is \"unnamed\", as you can read below the
tempo settings. To change it to something more suitable, press the
\"\...\" button right of the name.

![](/nitroustracker/content/tracking/step12.png)

There we go :-) Now to save the song, press the \"three pancakes\" icon.

In the file dialog, select \"sng\" again, then navigate to the folder
where you want to save it. To enter a name, press \"\...\" right of the
empty name field. You don\'t have to enter \".xm\" in the end, because
it is appended automatically. Now press \"save\". When the window
disappears, it\'s safe to turn off your DS.

![](/nitroustracker/content/tracking/step13.png)

You can now copy the file to your computer and play it with Winamp, XMMS
or whatever you like. You can also edit it with a PC tracker like
[MilkyTracker](http://www.milkytracker.net/).

Well, this concludes my introduction to bad tracking. The following
tutorials will cover certain aspects in more detail and are certainly
worth a read if you want to get the most out of NitrousTracker.
