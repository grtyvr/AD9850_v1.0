# AD9850_v1.0
Larger version of the board for the SigGen project: 328p based AD9850 function generator.

It is based on the project:

http://www.vwlowen.co.uk/arduino/AD9850-waveform-generator/AD9850-waveform-generator.htm

Which in turn is based on AD9851 code from Andrew Smallbone - modified for AD9850
   http://www.rocketnumbernine.com/2011/10/25/programming-the-ad9851-dds-synthesizer

I have created the KiCad files for a board for this project.  This version takes out the 100K current limiting resistor for the display led (on is on the board already).  And it is powered not by a power jack but by pin header from a seperate power supply in the same case.
