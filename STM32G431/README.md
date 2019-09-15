# Prototype G431 4IN1

Prototype G431 4IN1 is a 30.5x30.5mm 4IN1 ESC which can be easily amounted on drones. This design uses STM32G431KBU6 QFN32 chips. Reference design from STM's B-G431B-ESC1.

[STM32G431KUB6](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus/stm32-mainstream-mcus/stm32g4-series/stm32g4x1/stm32g431kb.html) is a chip based on M4 core. Due to the small number of pins on this chip, we cannot make it support CAN-FD on the basis of FOC pin map.

- [I/O information](https://github.com/AirFleetTeam/FOC_ESC-hardware/blob/master/STM32G431/Pin_IO_assignments.md)
- [Schematic](https://github.com/AirFleetTeam/FOC_ESC-hardware/blob/master/STM32G431/PROTOTYPE_G431_4IN1_v1.0.pdf)
- [PCB](https://github.com/AirFleetTeam/FOC_ESC-hardware/blob/master/STM32G431/PROTOTYPE_G431_4IN1_v1.0.PcbDoc)

## Details

- 8 layers (3oz| 3oz| 3oz| 3oz| 2oz| 2oz| 2oz| 2oz)
- 2 phase current
- High performance BEMF circuit
- Support up to 6s
- 4 SK6812 RGB programmable LEDs
- SPI communication

![CruxOne_v1.2_top](images/PROTOTYPE_G431_4IN1_v1.0_top.png?raw=true "CruxOne_v1.2_top")
![CruxOne_v1.2_bottom](images/PROTOTYPE_G431_4IN1_v1.0_bottom.png?raw=true "CruxOne_v1.2_bottom")