# DeltaT32 – ESP32-C3 Wearable for Capstone Project (KiCad 8)

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

**DeltaT32** is a modular hardware design project based on the **ESP32-C3 Mini-1**, intended primarily for wearable systems, but versatile enough for general-purpose embedded applications. Created using **KiCad 8**, this project includes a main ESP unit and two detachable sensor boards (BMI160/270 and MPU9250), making it ideal for both academic and practical applications.

This design has been created specifically to fulfill the requirements of a **Capstone Project**, integrating modern hardware design practices with real-world applications. Although firmware development is still pending, the hardware is designed to be compatible with the **[esp-rs (ESP32 Rust)](https://github.com/esp-rs)** ecosystem, providing a foundation for future development in Rust or other embedded programming languages.


## Project Structure

```

DeltaT32/
├── Schematic/ # PDF-format schematics
├── Hardwares/
│ ├── esp-unit-c3-v3/ # KiCad project for the main ESP32-C3 board
│ ├── sensor-bmi-v2/ # KiCad project for the BMI160 sensor board
│ └── sensor-mpu-v2/ # KiCad project for the MPU6050 sensor board
├── 3DModels/ # 3D models of components (if available)
├── Archives/ # Archived ZIP files of older versions
├── Materials/ # Bill of Materials (BOM) for each board
└── README.md # Project documentation

````


## Technical Specifications

| Component      | Description                                  |
|----------------|----------------------------------------------|
| MCU            | ESP32-C3 Mini-1                              |
| Sensors        | BMI160/270, MPU9250 (modular and detachable) |
| Design Style   | Modular: separate mainboard and sensor units |
| CAD Tool       | KiCad 8                                      |
| Firmware       | Not included (hardware only)                 |
| Rust Support   | Designed with esp-rs compatibility in mind   |
| Outputs        | Schematics, BOMs, 3D Visuals        |


## Firmware Compatibility

This hardware is designed to be compatible with the **[esp-rs (Rust for ESP32)](https://github.com/esp-rs)** ecosystem, but **no actual firmware has been implemented or tested** using Rust at this time. Custom firmware development in C, C++, or Rust.
