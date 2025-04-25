# 🚀 Missile Guidance System using P, PID, and ADRC Controllers

This project implements a real-time missile guidance system using classical and advanced control strategies—**Proportional (P), Proportional-Integral-Derivative (PID)**, and **Active Disturbance Rejection Control (ADRC)**—simulated and tested on the **Texas Instruments Delfino DSP board**.

## 📌 Overview

The goal of this project is to simulate and evaluate different control approaches for missile trajectory correction, minimizing error under disturbances. The implementation focuses on achieving optimal guidance using:

- Classical feedback (P and PID)
- Advanced robust control (ADRC)
- Real-time embedded simulation

## 🔧 Features

- Implementation of P, PID, and ADRC controllers in C
- Real-time simulation on TI Delfino DSP board
- Dynamic target tracking and course correction
- Comparative performance evaluation of controllers
- Designed for low-latency, high-reliability response

## 🧠 Control Strategies

| Strategy | Strength |
|----------|----------|
| **P**    | Simple and responsive, but prone to steady-state error |
| **PID**  | Versatile, balances speed and stability |
| **ADRC** | Robust under system uncertainties and external disturbances |

## 🛠 Hardware Used

- **TI Delfino DSP (TMS320F28379D)**
- UART/Serial connection for real-time parameter tuning
- Onboard DAC for waveform visualization (via oscilloscope)
- Host PC with Code Composer Studio


