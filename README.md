# FOC ESC HARDWARE
FOC(Field-Oriented Control) ESC is aimed at high-performance BLDC motor control.

The purpose of creating this repository is to share the hardware designs to:
1. Get feedback from the community and improve them;
2. Attract people that are interested in this and have the capability to join the software development.

## Advantages of FOC

- Independent, simple control of torque and flux
- Provide smooth torque over the entire speed range
- Provide rated torque near zero speed
- Speed up the dynamic process of acceleration and deceleration

- Reduce mechanical vibration caused by torque fluctuations
- Reduce noise
- Improve efficiency
- Improve speed accuracy and responsiveness

## Hardware Designs
Hardware designs delivered by the project are listed below. We use AD(Altium Designer) for design.

### Prototype PAC5523

Prototype PAC5523 is our first FOC ESC hardware design. More info [here](https://github.com/AirFleetTeam/FOC_ESC-hardware/blob/master/PAC5523/README.md).

### Prototype G431 4IN1

Prototype G431 4IN1 is a 30.5x30.5mm 4IN1 ESC which can be easily amounted on drones. This design uses STM32G431KBU6 QFN32 chips. Reference design from STM's B-G431B-ESC1. More info [here](https://github.com/AirFleetTeam/FOC_ESC-hardware/blob/master/STM32G431/README.md).

- 2 phase current
- High performance BEMF circuit
- Support up to 6s
- SPI communication
- 4 SK6812 RGB programmable LEDs

### Hall Sensor

For sensored FOC, we designed a hall sensor board.

## Commercial Use

This project is under GPLv3.0, all files are **FOR development ONLY**. For commercial use, please contact us.

## Getting Start

We are active in betaflight slack group, join us in #open_esc_firmware. 

Open the issues page and submit what you think to us.
