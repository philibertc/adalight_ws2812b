# Adalight WS2812B (Ambilight for about 30$).
**This is for use with PlatformIO, go on https://github.com/philibertc/adalight_ws2812b/releases/download/v1.0/Adalight_WS2812b.ino for the Arduino IDE edition (you will need to download FastLED with the Arduino IDE's library manager).**

This is a fork of Adalight working with WS2811/WS2812 LED using the FastLED library.

Original author: https://github.com/Wifsimster

Data pin of the LED strip goes on pin 6 (D6). You will need to edit the main.cpp (or the .ino) file in PlatformIO (or Arduino IDE) if you have more than 240 LEDs.

## What you need
- An Arduino Nano (genuine or not).
- A 1000µF (or more) electrolytic capacitor.
- A resistance between 200 and 600 Ohms.
- WS2812B RGB LED strip (max 240 LEDs) I recommend a strip with 60 LEDs/meter.
- A 5v power supply. To calculate the required current do: 0.06A × `NUM_LEDS`.
- A soldering iron and cables Dupont wires and 3 lines LED strip edge connector.
- Solderless breadboard proto-board (if you want to do a welded version).
- Prismatik (Linux, Mac, Windows): https://github.com/psieg/Lightpack/releases

## The circuit
![image](https://user-images.githubusercontent.com/57588282/112475769-76453500-8d71-11eb-9e01-6321eb142ff7.png)

© Philibert Cheminot

All images can be reused as long as I am cited.
