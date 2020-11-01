# coffee-scales

[![PlatformIO CI](https://github.com/mortenfyhn/coffee-scales/workflows/PlatformIO%20CI/badge.svg)](https://github.com/mortenfyhn/coffee-scales/actions?query=workflow%3A%22PlatformIO+CI%22)

Digital kitchen scales, mainly intended for pourover coffee. The current prototype looks like this:

![A breadboard prototype in action](https://i.imgur.com/RPn1dWZ.jpg)

## Build and run the code
Using PlatformIO is easiest:
* `pio run -e feather328 -t upload` (change `feather328` if using a different device).

## Features
* 1/10 gram accuracy.
* Fast settling time.
* No measurement jitter.
* Timer that starts automatically when you add weight.

## Hardware
* A 1 kg straight bar load cell connected through an HX711 load cell amplifier.
* Two 4-digit 7-segment displays driven by TM1637 LED drivers.
* An Arduino Nano, might get replaced by a suitable MCU.
