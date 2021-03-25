# adalight_ws2812b
This is a fork of Adalight working with WS2811/WS2812 LED using the FastLED library (v 3.1).

FastLED library can be found on Github here : https://github.com/FastLED/FastLED

Prebuilt binaries are in the releases page.

Data pin of the LED strip goes on pin 6 (D6). You will need to edit the main.cpp file in platformio if you have more than 240 LEDs.

## What you need
- An Arduino Nano (genuine or not).
- A 1000µF (or more) electrolytic capacitor.
- A resistance between 200 and 600 Ohms.
- WS2812B RGB LED strip (max 240 LEDs) I recommend a strip with 60 LEDs/meter.
