# Real Time Embedded System Project

## A real-time embedded system with 4 tasks to respond to the events below

> Tags: Salvo RTOS, C Programming, Real Time embedded Program

> Main file: https://github.com/Rishab2710/rtos-embedded-system/blob/main/RtosMain.c

> SalvoRTOS header file: https://github.com/Rishab2710/rtos-embedded-system/blob/main/salvocfg.h

> SalvoRTOS config files: https://github.com/Rishab2710/rtos-embedded-system/blob/main/salvomem.c

> Project Report: https://github.com/Rishab2710/rtos-embedded-system/blob/main/ProjectReport_RishabSingh.pdf
---------------------------------------------------------------------------------------------------------------------

### Task description:-

Task1: TASK_READ_TEMP_POT_P - To read the instantaneous values of on-board potentiometer & temperature sensor

Task2: TASK_KNIGHT_RIDER_P - To execute the sequential running of the previous project (Project Knight Rider) until direction changing trigger is pressed.

Task3: TASK_RUN_LED_P - To blink the LED at a specified interval (every 3s in the project).

Task4: TASK_PRINT_TEMP_POT - Use the UART and send the data received from Task1.

### Note: All the tasks are given equal priority of 10 as required by the project description and control flow. 



