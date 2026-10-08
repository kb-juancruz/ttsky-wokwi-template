<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
 
A pushbutton and a switch are connected to a multiplexer; when the switch is off, the multiplexer's output corresponds to the pushbutton, sending a signal through an 8-flip-flop shift register that lights up the corresponding LEDs one by one. When the switch is turned on, the multiplexer outputs a single pulse into the shift register; upon reaching the end, the bit is fed back to the beginning, causing the LEDs to continue turning on and off in a loop.

## How to test

The LEDs are connected to outputs 0 through 7. With the switch closed, pressing the pushbutton should cause the LEDs to turn on and off one by one until the end is reached; when the switch is turned on, the LEDs will cycle on and off in a loop.

## External hardware

8 leds
