# ![Title Saying Hackpill](https://raw.githubusercontent.com/AdamTuraj/hackpill/main/Images/logo.png)

**The Hackboard may be overkill, but Hackpill is here to fill the smaller shoes!**

The Hackpill is a small but versatile board at a small cost.

![A 3d view of the hackpill](https://raw.githubusercontent.com/AdamTuraj/hackpill/main/Images/3D_View.png)

Hackpill has the following features:

- 48MHz Cortex M0 Core with 32 Kb of Flash and 6 Kb of SRAM
- 32 GPIO pins
  - 1 SPI Interfaces
  - 1 I2C Interface
  - 1 CAN Interface
  - 1 USART Interface
  - 1 I2S Interface
  - 11 PWM Pins
  - 10 ADC's (Analog pins)
- An addressable LED
- USB C port for flashing and power

## Assembly

> [!CAUTION]
> The USBLC6 and diode may be orientated wrong. Ensure all components are properly orientated before ordering!

This board can be assembled through JLCPCB. The price for 5 assembled boards is around $35 USD without headers.

### Work with Arduino

> [!NOTE]
> You must have an STLink to continue. They can be bought standalone or with a Nucleo board.

A more detailed guide will be written up shortly. You may now use [STM32Duino](https://github.com/stm32duino/Arduino_Core_STM32) to make it work with Arduino.

## License

Hackclub is licensed under the MIT License. See the full license text in [LICENSE](LICENSE).
