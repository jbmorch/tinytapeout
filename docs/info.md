<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The goal is to create an 8-line counter, similar to a 4017 decade counter but with only 8 outputs instead of 10.

## How to test

Set enable to high and pulse the clock input with a square wave.

## External hardware

Use a microcontroller (like an Arduino or ESP32 module) to control the clock. Send the outputs to the individual segments of a 7-segment LED display (with the optional 8th segment that is the decimal point).

