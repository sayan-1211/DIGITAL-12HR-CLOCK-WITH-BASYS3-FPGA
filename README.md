# DIGITAL-12HR-CLOCK-WITH-BASYS3-FPGA

Introduction : A digital clock displays the time digitally (i.e. in numerals), as opposed to an analog clock. It is a device that we use in our lives on a daily basis.

Objectives : 1) Designing a Digital 12hr clock using the seven-segment display of the Artix-7 Basys3 FPGA board, 2) There will be a method of showing seconds elapsed, 3) There will be modes of time setting and also features for showing AM/PM. 

Methodology :  The Artix-7 Basys3 FPGA board, which is a sponsored board by Xilinx and required to be hard-coded using the Xilinx Vivado software. In order to adjust the clock frequency of the digital clock with that of the system clock, we are devising the concept of the slow clock. The code has many subparts, including a separate module defined for the Seven segment display. An XDC constraint file is also defined for specifying port locations of the FPGA board. The code is first simulated, then bitstream is generated and flashed in the FPGA board.
 
Technical Aspects : The board has 4 seven-segment display, which displays hours and minutes in HH:MM format and also 12 LEDs which indicate elapsation of every 5 minutes (i.e., 12 x 5 = 60secs). There are also 2 dedicated LEDs, one of which indicate whether it’s AM/PM and the other one for clock resetting mode. The clock also boasts features like manual time resetting via use of 5 debouncing push-buttons, which include setting the clock to any particular time or shuffling between AM/PM.
