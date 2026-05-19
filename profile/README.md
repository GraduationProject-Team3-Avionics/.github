# 🎓 Graduation Project Team 3 — Avionics

Welcome to our graduation project repository!  
We are **Team 3 — Avionics**, developing an autonomous drone system by developing our own Flight Controller using STM32.
Purpose of the project is to make a Flight Controller which are best fit for our self-made VTOL.

---

## 📂 Our Repositories

| Repository | Description | Link |
|------------|-------------|------|
| STRIX-FC-V1 | Repository for Testing Navigation Algorithms | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/STRIX-FC-V1) |
| STRIX-FC-V2 | Repository for RTOS-based Flight Controller Testing | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/STRIX-FC-V2) |
| STRIX-FC-V3 | Repository for the First Integrated Flight Controller Implementation and Attitude Control | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/STRIX-FC-V3) |
| Ground Control System | Repository for the Ground Control System based on Nano ESP32 | [GitHub Repository](https://github.com/GraduationProject-Team3-Avionics/GroundControlSystem.git) |

---

## Development Environment
- STM32CubeMX
- STM32CubeIDE
- STM32CubeProgrammer
- u-blox u-center

## Hardware 
| Item | Module | Description |
|------|--------|-------------|
| MCU  | STM32F405RGT6 | Main Flight Controller MCU (168 MHz, 192 + 4 KB SRAM) |
| IMU  | EBIMU-900FV5-R3 | Attitude Sensor |
| Baro | DFROBOT BMP390L | Barometric Pressure Sensor |
| GNSS | u-blox NEO-M9N | GNSS Module |
| Comm | NRF24L01+ | RF Communication Module |
