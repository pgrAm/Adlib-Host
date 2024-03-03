Adlib Host Version 1.2

Adlib Host is a utility designed to facilitate the composition of MIDI tracks
for the Adlib and other Yamaha OPL2 and OPL3 based cards (eg. SoundBlaster).
Adlib host allows your MS-DOS based PC to behave as MIDI module which
approximates the General MIDI spec. Hook up a sequencer or keyboard to your
MIDI input and jam away!

Usage:
	Launch ADLHOST.EXE from the DOS prompt, the program will try to autodetect
	your MIDI interface, if this does not work, or the wrong interface is 
	selected try speciying either: 
		-mpu401 to use an MPU401 compatible device
	or 
		-sbmidi to use a Creative SoundBlaster MIDI interface

At this point your Adlib card (or SoundBlaster/compatible) will begin playing
notes in response to an input on your MIDI interface such as a MIDI keyboard or
sequencer

New in verision 1.2:

	- Pitch bends are finally supported! range of + or - 2 semitones
	- Controller reset CC#121 is now supported
	- Fixed some artifacts when notes are played in quick succesion
	- Various other fixes

Copying:
	Feel free to share and make copies of Adlib Host as long as you include the
	associated documentation. The boring legal stuff is included in LICENSE.TXT

Contact <jake@jakedelmastro.com>

Copyright (C) 2018-2021 Jake S. Del Mastro
All rights reserved.