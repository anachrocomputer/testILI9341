# testILI9341
The ILI9341 is a common driver chip for colour LCDs.
It's often used to drive small displays such as those sold to Arduino
enthusiasts.
I have a couple of these displays, and also an Arduino-like STM32
Blue Pill module.
As a way to find out more about the Blue Pill, I took an existing
C program for the Philips/NXP LPC2119 and modified it to run as
an Arduino sketch on the STM32.

This Arduino sketch tests an ILI9341 display by initialising the chip
and generating a digital display, reminiscent of a seven-segment LED
display.
