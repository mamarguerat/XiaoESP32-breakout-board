# XiaoESP32-breakout-board
Breakout board for SeedStudio XIAO ESP32 for IOT and smart home applications.

## Power input
There is 3 choices for powering the board:
* USB
* 3.7V Battery (charging with USB-C)
* External power 2-6V (such as 2 to 4 AA or AAA batteries)

## Usage

### I2C Grove connector
There is 4 I2C grove connector. This is for I2C slaves such as Seeed Studio grove sensors or others. Note that these connectors are only intended for I2C communication only. The I2C communication is on a 5V bus.

### SPI Screen connector
There is a connector for SPI communication. This connector has a Command/Data pin as well as BUSY and RESET pins for a screen. The Chip Select pin is always VCC or GND by a jumer. The SPI communication is on a 3.3V bus.

### GPIO
There is 3 GPIO available on the board. 2 of them have a pull-up resistor to VCC for a switch input. The third GPIO has a MOSFET to the 5V power for high current output.

## Developement
This project is under developement and can be modified
