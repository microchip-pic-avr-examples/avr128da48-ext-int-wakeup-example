<img src="images/microchiptechnologyinc.png" height="60">

# AVR128DA48 External Interrupt Wake Up Example

This repository provides an Atmel Studio solution with a bare metal code example for an external interrupt wake up.
In the main loop, the program starts by entering the CPU in Sleep Mode. When the button is pressed, the CPU wakes up and blinks the LED. After those operations, the CPU returns to Sleep Mode.

## Configurations
- PC6 - LED0 led on Curiosity Nano board is configured as output pin
- PC7 - SW0 button on Curiosity Nano board is configured as input pin with pull-up enable
- SLPCTRL - Configured for entering Idle Mode

<img src="images/AVR128DA48_CNANO_instructions.PNG" height="250">

## Required Tools

- Atmel Studio 7.0.2397 or newer
- AVR-Dx 1.0.18 or newer Device Pack
- AVR128DA48 Curiosity Nano (DM164151)

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
