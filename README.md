# stm32-os
A basic RTOS for Cortex-M microcontrollers.

The broad goal of this project is to adapt things I learned from [Jonathan Valvano's book](http://users.ece.utexas.edu/%7Evalvano/arm/outline3.htm) to an STM32 project without using any vendor tooling or code.

The application goal of this project is to develop a pre-emptive scheduler that will enable the use of event based programming patterns.

## toolchain

I am developing primarily in Windows, using Make and Cortex-Debug in Visual Studio Code. My target is STM32F103C8T6 on a custom PCBA.

## development journal

[here](./dev-journal/dev-journal.md)
