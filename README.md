# DC-Motor Clockwise/Counter-Clockwise Movement

In this repository I will explain how I made a DC motor spins in both directions

# Step One : Connections 
## 1- Arduino Uno GND to GND port in H Bridge
## 2- Positive terminal of the 9V battery to the +12V terminal on the H bridge
## 3- Negative terminal of the 9V battery to the GND terminal on the H bridge
## 4- DC Motor connected to H bridge in OUT3, OUT4
## 5- H bridge IN1, IN2 connected to Arduino Uno digital pins 7,6

# Step Two : Coding

![image](https://github.com/httpsNumai/DC-Motor/assets/157239449/f599e504-f167-4f8d-879b-fd18ece87ebd)

This code will make the motor spin clockwise for 2 seconds, then stop for 1 second, and then spin counter-clockwise for 2 seconds, and repeat. Adjust the delays according to your motor's speed and requirements.
