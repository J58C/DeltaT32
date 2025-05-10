# DeltaT32 – Modular ESP32-C3 Wearable Hardware (KiCad 8)

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

**DeltaT32** is a modular hardware design project based on the **ESP32-C3 Mini-1**, intended primarily for wearable systems but flexible enough for general-purpose embedded applications. The design was created using **KiCad 8**, and includes a main ESP unit and two detachable sensor boards (BMI160/270 and MPU9250).

Although firmware is not yet provided, the hardware is designed to be **compatible with the [esp-rs (ESP32 Rust)](https://github.com/esp-rs)** ecosystem, making it suitable for future development using the Rust programming language.


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

---

## Technical Specifications

| Component      | Description                                  |
|----------------|----------------------------------------------|
| MCU            | ESP32-C3 Mini-1                              |
| Sensors        | BMI160/270, MPU9250 (modular and detachable) |
| Design Style   | Modular: separate mainboard and sensor units |
| CAD Tool       | KiCad 8                                      |
| Firmware       | Not included (hardware only)                 |
| Rust Support   | Designed with esp-rs compatibility in mind   |
| Outputs        | Gerbers, Schematics, BOMs, 3D Visuals        |

---

## Firmware Compatibility

This hardware is designed to be compatible with the **[esp-rs (Rust for ESP32)](https://github.com/esp-rs)** ecosystem, but **no actual firmware has been implemented or tested** using Rust at this time. Custom firmware development in C, C++, or Rust.

---

## License

This project is released under the **MIT License** — feel free to use, modify, and distribute it with proper attribution.

---

## Author

* [@J58C](https://github.com/J58C) — Creator and maintainer of the DeltaT32 hardware project
