# ROBOTIS DYNAMIXEL Motor Example

STM32 example for ROBOTIS DYNAMIXEL Library.

Main code: [`src/main.c`](./src/main.c)

> Only tesed on [H42-20-S300-R](https://emanual.robotis.com/docs/en/dxl/pro/h42-20-s300-r/) and [H54-200-S500-R](https://emanual.robotis.com/docs/en/dxl/pro/h54-200-s500-r/), using STM32 NUCLEO-F446RE.

## Pin map

| NUCLEO-F446RE Board  | MAX485    |
| -------------------- | --------- |
| D3 (PB3)             | DE and RE |
| D2 (PA10, USART1_RX) | RO        |
| D8 (PA9, USART1_TX)  | DI        |

| DYNAMIXEL Connector | MAX485 |
| ------------------- | ------ |
| 1, GND              | --     |
| 2, VDD              | --     |
| 3, DATA+            | A      |
| 4, DATA-            | B      |

> Ref: [Communication Circuit](https://emanual.robotis.com/docs/en/dxl/pro/h42-20-s300-r/#communication-circuit)

## IDE
PlatformIO
