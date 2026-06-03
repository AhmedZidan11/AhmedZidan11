# Ahmed Zidan

Embedded Software Developer | Mechatronics Engineer | STM32 · Embedded C · Motor Control

I am a mechatronics engineer with a strong focus on embedded software, control systems, and motion-control applications. My background combines industrial firmware development for drive systems with academic work in robotics, PID autotuning, MATLAB/Simulink, and control-system optimization.

I use this GitHub profile to document practical embedded projects that demonstrate my current work with STM32 microcontrollers, Embedded C, hardware interfaces, communication protocols, and control algorithms.

## Featured Embedded Projects

### Bare-Metal BLDC Speed Control on STM32F446RE

Repository: [BLDC_FOC_STM32F4_BareMetal](https://github.com/AhmedZidan11/BLDC_FOC_STM32F4_BareMetal)

A bare-metal STM32 motor-control project implemented in C using CMSIS/register-level programming only.
The firmware implements sensored BLDC speed control with AS5600 angle feedback, speed estimation, PI control, voltage-mode FOC, UART telemetry, and Python-based offline analysis.

**Focus areas:** Embedded C, STM32F4, bare-metal firmware, PWM, ADC, USART, motor control, PI control, FOC.

### STM32 CAN Air Quality Network

Repository: [stm32-can-air-quality-network](https://github.com/AhmedZidan11/stm32-can-air-quality-network)

A two-node STM32 embedded system for reading air-quality sensor data and transmitting it over a Classic CAN bus.
The sensor node reads SHT3x-DIS and SGP40 data over I2C, calculates a VOC Index, sends compact CAN frames through an MCP2515 module, and the receiver node decodes the data on a Nucleo-F446RE and prints it over UART.

**Focus areas:** Embedded C, STM32CubeIDE, STM32F4, I2C, SPI, Classic CAN, MCP2515, bxCAN, UART, sensor integration, interrupt/state-machine logic.

## Technical Focus

* Embedded C for STM32 microcontrollers
* Bare-metal firmware and STM32 HAL/CMSIS-based development
* Motor control, speed estimation, PWM generation, ADC-based sensing
* Communication protocols: I2C, SPI, UART, Classic CAN
* Git/GitHub-based project documentation and version control

## Background

* Mechatronics engineering with focus on control engineering and robotics
* Industrial experience in firmware development for drive and motion-control systems
* Academic experience in PID autotuning, robot modeling, MATLAB/Simulink, and control-system optimization

## Links

* [ResearchGate](https://www.researchgate.net/profile/Ahmed-Zidan-22) – selected academic publications in robotics and control engineering
* [LinkedIn](https://www.linkedin.com/in/ahmedzidan984/) – professional profile and work history

<!--
**AhmedZidan11/AhmedZidan11** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
