## **Microwatt-Powered Industrial IoT Safety SoC with Ultra-Low Power Wake-Up Receiver for Industry 4.0**

[![ChipFoundry](https://img.shields.io/badge/Platform-ChipFoundry-darkblue)](https://chipfoundry.io/challenges/microwatt)
[![Microwatt OpenPOWER](https://img.shields.io/badge/Core-Microwatt%20OpenPOWER-darkred)](https://github.com/antonblanchard/microwatt)
[![Caravel SoC](https://img.shields.io/badge/Integration-Caravel%20SoC-darkgreen)](https://github.com/efabless/caravel)
[![Tapeout Ready](https://img.shields.io/badge/Goal-Tapeout%20Ready-purple)](https://en.wikipedia.org/wiki/Photomask)


🔓 *In a world where industrial safety and medical reliability depend on ultra-low-power, always-on monitoring, current solutions fail due to high energy consumption, bulky batteries, and limited integration. Our proposed IndusGuard: Microwatt-Powered Safety Chip leverages open-source RISC-V/POWER architecture, energy harvesting, and a fully open RTL-to-GDSII flow to deliver a self-sustained, batteryless SoC for next-generation critical systems. By uniting ChipFoundry’s fabrication ecosystem with Caravel integration, this project **can** proves that India can lead in tapeout-ready, open silicon innovation—making real-world deployment not only possible but urgently necessary.*

![Image](https://github.com/user-attachments/assets/3d98cbc6-7ca3-4f79-8f1a-7e431ba99683)

# Problem Statement

Industrial environments (chemical plants, mining, oil & gas, manufacturing units) face critical safety challenges such as gas leaks, fire hazards, machinery failures, and worker accidents. Current IoT solutions ***rely on external microcontrollers (e.g., ESP32, STM32) that are high power***, costly, and not purpose-built for safety-critical real-time monitoring.

There is a lack of a dedicated low-power safety SoC that can:

• Continuously monitor multiple industrial sensors

• Run in ultra-low power with always-on wake-up logic

• Be easily programmed in a high-level language (MicroPython)

• Communicate securely with central monitoring systems.

 *To address these challenges, we propose a Microwatt-powered Industrial IoT Safety SoC that integrates a RISC-V OpenPOWER Microwatt CPU with custom accelerators, a multi-sensor interface, and an ultra-low-power wake-up receiver.*

🔑***By fabricating this chip, industries can deploy millions of safety nodes that run for years without battery replacement, enabling a safer, greener, and smarter industrial future.***

<img width="1117" height="813" alt="image" src="https://github.com/user-attachments/assets/42dab98f-a2c1-4e2c-8cf8-592842619a2a" />

# 📑 Proposal Summary

This project proposes a universal safety-focused IoT SoC integrating Microwatt with wake-up receivers and multiple sensors for low-power, high-reliability industrial monitoring. It addresses real-world safety problems, aligns with sustainability and Industry 4.0, and showcases open-source hardware innovation.

# Motivation

• By fabricating a dedicated SoC, we achieve:

   1 Ultra-low power operation (wake-up only on events).

   2 Compact integration of CPU + sensors + safety accelerator.

   3 Reliability & scalability for trillions of sensors in Industry 4.0.

***• Aligns with sustainability goals and open-source hardware adoption.***
