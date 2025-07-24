# EXTI0 External Interrupt – STM32 Assembly Project

This project demonstrates how to configure and handle an external interrupt (EXTI0) on STM32 using ARM Assembly language. It sets up GPIOs, interrupt vectors, and the EXTI peripheral entirely in low-level assembly, without any external libraries or C runtime.

## Features

- Direct register-level configuration of:
  - RCC (clock enable)
  - GPIOA (input on PA0)
  - GPIOC (output on PC8/PC9)
  - AFIO and EXTI for external interrupt line 0
  - NVIC for enabling EXTI0 interrupt
- EXTI0 is triggered on falling edge of PA0
- Fully written in ARM assembly using Keil syntax

## Project Scope

- Simulation or hardware deployment using STM32 (Cortex-M3 architecture)
- Educational purpose: extensive understanding of interrupt handling at assembly level
