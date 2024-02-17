# DC-Motor Clockwise/Counter-Clockwise Movement

In this repository I will explain how I made a DC motor spins in both directions

# Step One : Connections 
* Connect the components as follows:

## Arduino Uno:

* Connect the GND pin to the GND port on the H Bridge.
## Power Supply:

* Connect the positive terminal of a 9V battery to the +12V terminal on the H Bridge.
* Connect the negative terminal of the 9V battery to the GND terminal on the H Bridge.
## DC Motor:

* Connect the DC motor to OUT3 and OUT4 on the H Bridge.
## H Bridge and Arduino Uno:

* Connect IN1 and IN2 of the H Bridge to digital pins 7 and 6 on the Arduino Uno.

# Step Two : Coding

![image](https://github.com/httpsNumai/DC-Motor/assets/157239449/f599e504-f167-4f8d-879b-fd18ece87ebd)

This code will make the motor spin clockwise for 2 seconds, then stop for 1 second, and then spin counter-clockwise for 2 seconds, and repeat. Adjust the delays according to your motor's speed and requirements.
