# mfmic
Multi-Function Microphone for the ICOM IC-900/901

This repo holds the design data for the HM-133 Adapter (wired-remote), the IC-901 Remote Controller Adapter (RCA), and the MFmic adapter (used in the IC-900 B-Unit).

The design data is subdivided by MCU, Then subdivided into HW and SW.  At the moment, there are two MCUs: an SiLabs C8051-F531 (DTMF Adapter) and an ATTINY816 (RCA).  The RCA features several PCBs but only one of those contains the MCU.  The following lists the high-level Design Item List:

HM133:<br>
One (1) PCB and one (1) SW source package.  There is also an OpenSCAD 3D-printed housing included in the hardware section.

RCA:<br>
     IC901_SRAM100: holds the ATTINY816<br>
     IC901_KEYMUC400: holds the key-matrix muxing circuits<br>
     IC901_SRAM200: The 32K SRAM adapter PCB<br>
     IC901_LED300: A small, 7-seg LED display PCB for displaying the SRAM bank setting<br>

https://ke0ff.github.io/mfmic/ holds user field support documentation.
