# Leds Controlled Project Using Arduino and OpenCV

## Project Overview

This project enables control of five LEDs through hand gestures using an Arduino Uno and OpenCV. A camera captures real-time hand gestures, which are processed by OpenCV. Based on the recognized gesture, the Arduino is instructed to turn specific LEDs on or off.

## Connections

The LEDs are connected to the following Arduino pins:

- **LED1**: Pin 8
- **LED2**: Pin 9
- **LED3**: Pin 10
- **LED4**: Pin 11
- **LED5**: Pin 12

Each LED is connected through a 220Ω resistor to protect it from excess current. Connect the longer leg (anode) of each LED to the Arduino pin, and the shorter leg (cathode) to the ground.

