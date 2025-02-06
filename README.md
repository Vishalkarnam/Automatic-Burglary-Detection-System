Automatic Burglary Detection System
An automatic burglary detection system built using Arduino Uno, PIR Motion Sensor, and GSM SIM 800 C Module. This system helps detect unauthorized entry into a shop after business hours and notifies the owner via SMS and call.

Features:
Detects motion using PIR sensor
Sends SMS alerts to the owner's phone
Makes a call to notify the owner
Can be configured to work only after business hours
Simple and cost-effective solution
Components Required:
Arduino Uno
PIR Motion Sensor
GSM SIM 800 C Module
12V Adapter
Jumper Wires
Breadboard (optional)
Wiring:
PIR Motion Sensor:

VCC → 5V pin on Arduino
GND → GND pin on Arduino
OUT → Digital Pin 7 on Arduino (or any other digital pin)
GSM SIM 800 C Module:

VCC → 5V pin on Arduino
GND → GND pin on Arduino
TX → Digital Pin 8 on Arduino
RX → Digital Pin 9 on Arduino
Power Supply:

12V adapter to power the system.
Setup:
Connect the components as shown in the wiring section.
Insert the SIM card into the GSM SIM 800 C module.
Load the provided code to the Arduino Uno.
