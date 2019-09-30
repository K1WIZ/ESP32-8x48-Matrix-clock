# ESP32-8x48 Matrix Clock
Clock with six 8x8 Led-Matrix, Using MAX7219 FC16 Displays

Forked from https://github.com/schreibfaul1/ESP32-LED-Matrix-Clock

## needed:
- 6 x MAX7219 incl 8x LED-Matrix8x8
- 1 x ESP32 Dev Board
- breadboard, some wires etc.

define GPIOs, Brigthness and Timezones in the code.

## Improvements Made: 

1) Use of WiFiManager to establish wifi connection - avoid hard-coding credentials

*** Looking for Collaborators/Contributors ***

## Improvements Desired:

1) allow time zone offset selection to be established during initial setup via WiFiManager
2) modify code to render centered time on 8x64 array instead of 8x48 (seems foolish to have to cut an FC16 display in half
   to get an 8x48 array.  Plus, an 8x64 array will allow for nicer display of date info.
3) eliminate or translate any german code to english
4) streamline code where possible

## Video:

[![Video](https://img.youtube.com/vi/tIkXZ8vg2Gs/0.jpg)](https://youtu.be/tIkXZ8vg2Gs)
