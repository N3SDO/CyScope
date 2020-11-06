#CyScope

This is a 2-channel oscilloscope and waveform generator implemented on
a Cypress' PSoC5LP device. 
The implementation has been done for two evaluation kits:

  CY8CKIT-059 -> ScopePSoC
  See the file PSoC_5LP_Scope.docx for details on how to program and use
  the oscilloscope and waveform generator.

  FreeSoC2 -> ScopeFreeSoC2
  The file FreeSoC2_Scope.docx describes changes to use the original project
  on the Sparkfun kit including a hardware adapter for demonstration purpose.

The GUI is a TCL program baesed on the Open Instrumentation Project
created by Syscomp Electronic Design.

N3SDO ran across this and is quite impressed.  There are a few things that don't work quite the way I would like...
The X-Y screen does not allow you to input a negative offset, so it only uses the upper right quarter of the screen.
The Network analysis runine attempts to init and crashes every time for me.
I hope to be able to fix the network analysis function.
< Wish list >
I would also like a larger scope screen, and perhaps a scrolling chart recorder type function.
73  N3SDO
