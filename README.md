
# Bestla - Remote Controlled Car

![Bestla Image](https://github.com/yuvrajjain2003/bestla/blob/main/images/Bestla.png)

This project is a programmable remote-controlled car that allows you to wirelessly control its movements using a joystick and the NRF24L01 library. It consists of two main components: the transmitter and the receiver. The transmitter captures joystick input and sends it to the receiver, which controls the car's movements.

## Table of Contents

- [Project Overview](#project-overview)
- [Components](#components)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The project was developed as part of the APPL110 class at UNC-Chapel Hill in Spring 2022. It allows you to control a remote-controlled car with precision and ease, making it a fun and educational project.

## Components

### Transmitter

![Transmitter Image](https://github.com/yuvrajjain2003/bestla/blob/main/images/Transmitter.png)

The transmitter includes the following components:

- Joystick Module: Captures X and Y values as input.
- NRF24L01 Module: Wirelessly transmits joystick data to the receiver.
- Arduino Board (e.g., Arduino Nano): Reads joystick values and transmits data to the receiver.

### Receiver

![Receiver Image](https://github.com/yuvrajjain2003/bestla/blob/main/images/Receiver.png)

The receiver includes the following components:

- NRF24L01 Module: Receives joystick data from the transmitter.
- Arduino Board (e.g., Arduino Nano): Processes received data and controls the car's movements.
- L298N Motor Driver Module: Controls the car's motors based on the received signals.

## Installation

To set up this project, follow these steps:

1. **Hardware Assembly:** Assemble the hardware components, including the joystick, NRF24L01 modules, Arduino boards, and the L298N motor driver module. Refer to the provided wiring diagrams or documentation.

2. **Arduino IDE:** Install the Arduino IDE if not already installed.

3. **Libraries:** Ensure you have the NRF24L01 library installed in your Arduino IDE.

4. **Transmitter Code:** Upload the transmitter code to the Arduino board on the transmitter side.

5. **Receiver Code:** Upload the receiver code to the Arduino board on the receiver side.

6. **Calibration:** Calibrate the joystick and fine-tune the motor control logic in the receiver code to suit your specific setup.

## Usage

Once the project is set up and both the transmitter and receiver are powered on, you can control the remote-controlled car using the joystick on the transmitter. Enjoy controlling the car's movements wirelessly!

## Customization

You can customize this project in several ways:

- Modify the control algorithm in the receiver code to change how the joystick input translates into motor control commands.
- Add additional features such as LED indicators, camera modules, or obstacle detection sensors.
- Experiment with different types of cars and motors for varying performances.

## Contributing

Contributions to this project are welcome. If you have improvements or new features to suggest, please open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE.md).
