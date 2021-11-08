STM32(F103) Timer Example Code
-----------------------------------
This repository contains code sample for using timer in STM32. The code generated using STM32CubeMX inside STM32CubeIDE. Most of timer code resides inside `Core/Src/main.c` and `Core/Src/stm32f1xx_it.c` for the ISR.

Inside every project, there is a `logicdata` folder that contains capture data that captured using Logic Analyzer. Use [Logic (1.2.29 Beta)](https://support.saleae.com/logic-software/legacy-software/older-software-releases#logic-1.2.29-beta-last-version-of-logic-1.x) to open the file(s).

`Dummy Task` means a dummy task that imitates a task by using `HAL_Delay()` function with random delay time. It is used to simulating another task other than timer that executed by the microcontroller.
