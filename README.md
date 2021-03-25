# Adalight WS2812B (Ambilight for about 30$).
**This is for use with PlatformIO, see https://github.com/philibertc/adalight_ws2812b_arduino_ide for the Arduino IDE edition (you will need to download FastLED with the Arduino IDE's library manager).**

This is a fork of Adalight working with WS2811/WS2812 LED using the FastLED library (v 3.1).

Original author: https://github.com/Wifsimster

Prebuilt binaries are in the releases page.

Data pin of the LED strip goes on pin 6 (D6). You will need to edit the main.cpp file in platformio if you have more than 240 LEDs.

## What you need
- An Arduino Nano (genuine or not).
- A 1000µF (or more) electrolytic capacitor.
- A resistance between 200 and 600 Ohms.
- WS2812B RGB LED strip (max 240 LEDs) I recommend a strip with 60 LEDs/meter.
- A 5v power supply. To calculate the required current do: 0.06A × `NUM_LEDS`.
- A soldering iron and cables **or** Dupont wires and 3 lines LED strip edge connector.
- Solderless breadboard **or** proto-board (if you want to do a welded version).
- Prismatik (Linux, Windows, Mac): https://github.com/psieg/Lightpack/releases

## The circuit
![image](https://user-images.githubusercontent.com/57588282/112475769-76453500-8d71-11eb-9e01-6321eb142ff7.png)
