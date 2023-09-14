# Bitduo
An open-source standalone Bitcoin miner built on the BM1397 chip made by ANTMINER. Bitduino (inspired by the Bitaxe miner made by Skot and the BM1397 hash board made by Pouyian, which can be proven) aims to be compatible with the esp-miner (somethingOS) made by Skot.

## Features inspired by the Bitaxe:
- Espressif ESP32-S3-wroom-1: Runs the OS and enables the miner to be standalone.
- ANTMINER BM1397: ASIC mining chips that perform the necessary calculations in Sha256 to mine that sweet Bitcoin.
- SSD1306 OLED: The 128×32 0.91-inch OLED lets you see what the OS shows/displays.
- Microchip EMC2101: Measures/reads the temperature of the BM1397's internal diode and controls a PWM fan.
- TI INA260: Power meter for checking power consumption.
- TI TPS40305: Buck Regulator for adjusting the BM1397's core voltage.
- Maximm DS4432U+: for digitally controlling the TPS40305 over I2C.

## Features to outshine the current Bitaxe (v2.2):
1. Multiple chained ASIC chips (multiple variants might be available in the future).
2. USB port for programming and debugging the ESP32.
3. Boot and reset buttons directly on board.
4. Built with JLCPCB and sourced with LCSC
5
## Hardware. 
Still under development.
