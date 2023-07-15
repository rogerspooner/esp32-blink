## Origin

Espressif sample project 'blink'.
Can be installed in VS Code with Espressif ESP-IDF.
Press F1 and type ESP-IDF: Sample
Further developed by Roger Spooner

## Hardware

ESP32-WROOM-D dev board
Breadboard. Plug right side of the WROOM in the breadboard, since it won't all fit.

Pin G5 -> 100R resistor -> Gnd

Pin G15 -> 10kR resistor or less -> Gnd or open circuit.

Hold BOOT button while flash process is connecting. Release it before the flashing completes.

# Configure and build

This is almost a clone of Espressif's sample project for ESP32. It works.

Some configurations may be in the build/ directory and not committed here.
In VS Code with Espressif ESP-IDF extension installed, run:
* ESP-IDF: Configure ESP-IDF extension
* ESP-IDF: Set Espressif device target
* ESP-IDF: SDK Configuration Editor
* ESP-IDF: Select port to use (COM, UART) 
  * (install CP2102 driver first to create COM3 port)
* ESP-IDF: Build your project
* ESP-IDF: Flash your project 
  * (hold down BOOT button on hardware)
* ESP-IDF: Monitor your device