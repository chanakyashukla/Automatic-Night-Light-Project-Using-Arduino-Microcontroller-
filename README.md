# Automatic-Night-Light-Project-Using-Arduino-Microcontroller-
The code is for the Arduino Nano Microcontroller to set up an automatic night light project.

# Automatic Night Light Project Using Arduino Nano

## Overview
This project implements an automatic night light using an Arduino Nano microcontroller. The system uses a Light Dependent Resistor (LDR) to measure ambient light levels and automatically controls an LED based on the surrounding darkness.

## Hardware Setup
- Connect 5V from the Arduino Nano to one leg of the LDR.
- Connect the other leg of the LDR to a 10K resistor, and connect it to analog pin A0 of the Arduino.
- Connect the other end of the 10K resistor to the GND of the Arduino.

## Code
The Arduino code reads the analogue input from the LDR and activates the LED when the ambient light level falls below a certain threshold. The system simulates a night light by turning on the LED in low-light conditions.

## Usage
1. Power the Arduino Nano setup.
2. The system will automatically monitor ambient light levels.
3. The LED will turn on when it's dark and turn off when it's bright.

## Notes
- Adjust the LDR threshold in the code if needed.
- Serial monitor output is available for monitoring.

## License
This project is provided under [license details, if applicable].

Feel free to modify and adapt the code for your specific needs!

