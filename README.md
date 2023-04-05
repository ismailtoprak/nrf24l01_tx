
# NRF24L01 Full-Duplex Project
----
- This project is provide a full-duplex communication between two NRF24L01 modules.

## IDE and Toolchain Configurations
----
- CubeIDE Version
   - 1.12.0
- McuFamily
   - STM32F09RC

## PINOUT
----
| NRF24L01 | STM32F0 |
| --- | --- |
| `VCC` | 3.3V |
| `GND` | GND |
| `CE` | PA12 |
| `CSN` | PA11 |
| `SCK` | PA5 |
| `MOSI` | PA7 |
| `MISO` | PA6 |
| `IRQ` | NC |



## Release Notes
----
- v1.0
    - full duplex support is added.
    - SPI speed is set as 6.0Mbit/s
