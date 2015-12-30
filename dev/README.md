MIDI controller into USB
========================


Patch side
==========

- Described at [pd-tutorial](http://www.pd-tutorial.com/english/ch04s03.html) , the MIDI input objects are:
     - notein
     - midiin

Debugging: Check the midi debugger in "util" 
- you should hear a hum, which you can control the pitch
- pressing MIDI keyboard keys, or whatever, should change the values on the right

References
----------

- https://puredata.info/docs/faq/midiinput
- https://puredata.info/docs/faq/faqsection_view?section=Using%20Pd
- http://en.flossmanuals.net/pure-data/ch067_using-midi/

Device side
===========

General OSX:
- start Audio MIDI Setup
     - be in the MIDI Studio window
     - make sure your device shows up!  You can test with the Test Setup mode
- if you need to route software MIDI to/from PD you want the IAC Driver
- After you have set up something, your device should show up in PD under Preferences: MIDI Settings...

Rock Band keytar!
-----------------

- connect using a MIDI-USB controller: see a ([demo here](https://www.youtube.com/watch?v=IZUsD2uaaWc) from  [Unnecessary Blogage](http://anex-unnecessaryblogage.blogspot.com/2010/12/noobs-guide-to-using-rock-band-3.html) )
- two of the buttons (X and Y on Nintendo, or Circle and Square on the PlayStation) control the octaves

Arduino
=======

For example: a bunch of knobs
- See my notes at [git@github.com:monkeywidget/arduino_sandbox.git](https://github.com/monkeywidget/arduino_sandbox.git)
