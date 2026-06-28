Week 1 Content

LED Blink Project

Project Title

Arduino LED Blink with Potentiometer Speed Control

Project Overview

This project introduces the basics of controlling an LED using an Arduino Uno. The LED blinks continuously, and its blinking speed can be adjusted with a potentiometer. To make the project more interactive, the Arduino also prints the number of blinks to the Serial Monitor in real time.

Hardware Required

- Arduino Uno
- LED
- 220 Ω resistor
- 10 kΩ potentiometer
- Breadboard
- Jumper wires
- USB cable

Circuit Connections

- Connect the LED's positive leg (anode) to digital pin 13 through a 220 Ω resistor.
- Connect the LED's negative leg (cathode) to the GND pin.
- Connect one outer pin of the potentiometer to the 5V pin.
- Connect the other outer pin to GND.
- Connect the middle pin (wiper) of the potentiometer to analog pin A0.

Uploading the Code

1. Connect the Arduino Uno to your computer using a USB cable.
2. Open the Arduino IDE.
3. Load the "led_blink.ino" sketch.
4. From Tools → Board, select Arduino Uno.
5. Choose the correct COM port from Tools → Port.
6. Click Verify to compile the code and check for errors.
7. Click Upload to transfer the program to the Arduino.
8. Open the Serial Monitor and set the baud rate to 9600 to see the blink count.

Expected Output

- The LED blinks continuously.
- Rotating the potentiometer increases or decreases the blinking speed.
- The Serial Monitor displays the blink count, for example:
  Blink count: 1
Blink count: 2
Blink count: 3
...

Troubleshooting Tips

- Make sure the correct Arduino board and COM port are selected in the Arduino IDE.
- Double-check all wiring, especially the LED polarity and potentiometer connections.
- Ensure the Serial Monitor baud rate is set to 9600.
- Verify that the 220 Ω resistor is connected in series with the LED.
- If the LED still doesn't blink, try uploading the code again and check for any compilation or upload errors.