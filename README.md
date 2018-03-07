# Amanuensis
The Amanuensis is an automated songwriting and recording system aimed at ridding the process of anything left-brained, so that one need never leave a creative, spontaneous and improvisational state of mind, from the inception of the song until its final master. The program will construct a cohesive song structure, using the best of what you give it, looping around you and growing in real-time as you play. All you have to do is jam and fully written songs will flow out behind you wherever you go.

Currently The Amanuensis is nearing a fully fleshed-out Beta 1.0. The main task at hand is cleaning up the UI.

This version relies on MIDI to denote played notes and uses it to identify when a steady beat has been achieved. Longer steady spans are retained while the shorter ones they overlap are discarded. This is essentially the criteria used to determine which portions of your jam are "best" and works well in practice, although any other method could be implemented in future versions.

Although MIDI must always be present for The Amanuensis to work, this does not mean you can't use ordinary audio sources like acoustic drums or guitar. The program includes a versatile feature called The Singing Stream which can interpret any stream of data into MIDI, whether that be audio or readings from an external controller or a Kinect. This MIDI can then simply accompany that audio source (or another) in order to run the rhythmic analysis, or also be used to play VST instruments or samples.

These VSTs and samples are preloaded into The Amanuensis itself so no other software is needed to play MIDI. In addition, the PGUP and PGDN hotkeys allow you to quickly cue up a new sound at random or cycle back to previous ones. This either means a random plug-in from your specified VST folder with a random preset already selected or a new random sample from your specified drum sample folder for each pitch. These hotkeys are basically the only deliberately controlled functions that exist in the system; everything else is meant to be as automatic as possible. If you're not feeling the sound you're working with switching to another can be tedious and take you out of the moment, so this alleviates that.

For increased automation, there is a function that will "shuffle" your instrument at specified intervals of time or after periods of silence. In addition to giving you a new sound this will also switch you to a random MIDI channel, thereby allowing you to work with another layer of the song. Each song can be comprised of up to 16 tracks (one for each MIDI channel) which are each analyzed for rhythm and built independently, as well as simultaneously. This means an entire band can build a song together or a single player can rotate through every instrument as he or she works. The number keys as well as + and - can also be used to jump to other channels.