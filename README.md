# Embedded-MultiAgent-Assistant

A workflow designed to accelerate embedded systems development. This agentic system translates natural language requirements into deployable C code for STM32 microcontrollers.

## Core Features
*   **Standard Library Optimization:** Strictly generates code using the standard peripheral library instead of HAL, ensuring tighter memory control.
*   **Auto-Correction & Review:** Built-in Critic Agent that automatically flags hardware-specific logic errors (e.g., bypassing redundant `Delay_Init` to apply existing SysTick implementations).
*   **Sensor Integration:** Pre-trained on common hardware component configurations, enabling rapid deployment of modules like LCD1602 (via I2C) and DS18B20 environmental sensors.

## Current Status
Currently deployed locally for laboratory projects. Average processing time per peripheral integration reduced by 75%.
