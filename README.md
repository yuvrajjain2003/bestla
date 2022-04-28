# Bestla
Arduino code for a programmable Remote Controlled car using the NRF24L01 library.

This project was part of my APPL110 class at UNC-Chapel Hill in Spring 2022. The desgin consists of two separate components: the transmitter and receiver, which are, as the name suggests, responsible for transmitting signals through a joystick and receiving signals to guide the L298N Driver module to move in specified directions. 

### Transmitter

![alt text](https://github.com/yuvrajjain2003/bestla/blob/main/images/Receiver.png)

The transmitter sends the x and y values of the joystick to the receiver through the NRF24L01 Module.

### Receiver

![alt text](https://github.com/yuvrajjain2003/bestla/blob/main/images/Transmitter.png)

The Arduino Nano board will receive signals from the NRF24L01 bluetooth module, and based on these signals will command the L298N driver module to send varying voltage of electricity into the motors so that the wheels will rotate in a specific manner. When the Nano board receives signals from the joystick to move forward, it will give power to all wheels to rotate clockwise, and when the nano board receives signals from the joystick to move backwards, it will give power to all the wheels to rotate counter-clockwise to move backwards. Similarly, it will distribute power between the wheels to turn right and left based on the joystick values.
