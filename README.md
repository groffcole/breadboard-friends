breadboard-friends
==================

A collection of cute breakout boards riding solderless breadboards, mostly for analog audio works

These PCB layouts and schematics are released under a Creative Commons cc-by-sa
3.0 license.

NOTE: This is a forked version of breadboard-friends and has two main differences from the original:
- There are two additional BBFs, one using Thonkiconn 3.5mm Jacks (bbf-thonkjacks) and another providing eurorack header with polarity protection for providing eurorack power to your breadboard from euro bus (bbf-europower). 
- This version has been updated to fit the power rails of the breadboards produced by [Assembly Specialist](http://www.assemblyspecialist.com/). The Assembly Specialist breadboard power rails have a wider spacing between them so the original BBFs do_not fit. Instead of 2x 10 pin DIL male headers for the power rails, use 4x 5 pin SIL male headers.

BBF-EUROPOWER Bill Of Materials (BOM)

- 2x 200ma PTC Poly Fuse or equivalent (or jumper wires if no fuse is required);
- 2x 10uF 25V Electrolytic Caps;
- 2x 1N5818 diodes or equivalent;
- 2x Ferrite Beads;
- 2x 10 Pin DIL male headers;
- 4x 5 pin SIL male headers.

BBF-THONKJACKS Bill Of Materials (BOM)

- 4x Thonkiconn Jacks;
- 1x 8 pin SIL female header;
- 4x 5 pin SIL male headers.
