# I2M Electron nf

![I2M Electron](https://raw.githubusercontent.com/nanoframework/nf-Community-Targets/main/ChibiOS/I2M_ELECTRON_NF/resources/IngenuityMicro_Logo.svg)

## Electron community board

The board used in this community contribution is a STM32F411CEU6 based board from IngenuityMicro called Electron. The board has only 12 pins of which 3 are already used for 3.3V, 5V and GND, leaving use of only 9 pins.

These pins can be used for:

- 1 x TX/RX
- 4 x PWM
- 4 X ADC
- 1 x I2C
- 1 x SPI

In addition, the board has two on-board LEDs connected to PA1 and PA8 and are tested for use as GPIO, PWM.

Further information can be found on http://www.ingenuitymicro.com/products/electron/ where firmware, board layout and schema can be found.

![pins](https://github.com/nanoframework/nf-Community-Targets/blob/main/ChibiOS/I2M_ELECTRON_NF/resources/electronpins.png?raw=true)

## Managed helpers

Checkout the [C# managed helpers](https://github.com/nanoframework/nf-Community-Targets/tree/main/ChibiOS/I2M_ELECTRON_NF/managed_helpers) available for this board.

