# Korg64-cv.ocd-NOON-SysEx
SysEx file for mapping the drum pads from Korg SQ64 to CV OCD for the Landscape NOON

Equipment used:
 - [Korg SQ64](https://www.korg.com/us/products/dj/sq_64/)
   - 4 track Sequencer
 - [cv.ocd](https://six4pix.net/product/cvocd/)
   - MIDI to CV adapter
 - [Landscape NOON](https://www.landscape.fm/noon)
   - Passive drum machine

For the NOON, Landscape has a good selection of sequencers that they have tested and recommend the [Arturia BeatStep Pro](https://www.arturia.com/products/hybrid-synths/beatstep-pro/overview).  I've already been invested in the Korg SQ64 over the last year so I wasn't interested in purchasing and learning another seuqencer.

On initial tests I found that the Korg SQ64 gate outputs would work with the NOON, but since the NOON is a passive drum machine, over time the power seemed to diminish to the point where the NOON would not make any sound.

I already had the cv.ocd, so I updated the settings so gate outputs 5-12 would line up with the Korg SQ64 drum pads, 1-8.  The cv.ocd pushes enough power to the Landscape NOON to function properly.

This github page is made to store the sysex file.

Instructions of use:
 - Download the sysex file
 - Plug in the cv.ocd to your computer with a usb > midi or midi interface (DO NOT HAVE OTHER MIDI DEVICES HOOKED UP DURING THIS PROCESS)
 - Push the sysex file to the device with a sysex program (do some googling for your OS)

The cv.ocd maps the following outputs
 - A: MIDI Channel 1 note
 - 1: MIDI Channel 1 trigger
 - B: MIDI Channel 2 note
 - 2: MIDI Channel 2 trigger
 - C: MIDI Channel 3 note
 - 3: MIDI Channel 3 trigger
 - D: MIDI Channel 4 note
 - 4: MIDI Channel 4 trigger
 - 5: MIDI Channel 10 trigger, note B1
 - 6: MIDI Channel 10 trigger, note C2
 - 7: MIDI Channel 10 trigger, note C#2
 - 8: MIDI Channel 10 trigger, note D2
 - 9: MIDI Channel 10 trigger, note D#2
 - 10: MIDI Channel 10 trigger, note E2
 - 11: MIDI Channel 10 trigger, note F2
 - 12: MIDI Channel 10 trigger, note F#2

Equipment:

Korg SQ64 MIDI Out (3.5mm to DIN adapater) > cv.ocd > Gates 5-12 > Landscape NOON
