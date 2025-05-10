# DeltaT32 – Modular ESP32-C3 Wearable Hardware (KiCad 8)

**DeltaT32** adalah proyek desain perangkat keras modular berbasis **ESP32-C3 Mini-1**, dirancang untuk sistem wearable namun fleksibel untuk aplikasi embedded lainnya. Desain ini dibuat dengan menggunakan **KiCad 8**, terdiri dari unit utama ESP dan dua modul sensor terpisah (BMI160/270 & MPU9250).

Walau firmware belum dikembangkan, desain ini disusun agar **kompatibel dengan ekosistem [esp-rs (ESP32-Rust)](https://github.com/esp-rs)**, memungkinkan eksplorasi sistem embedded menggunakan bahasa Rust di masa mendatang.

---

## Struktur Direktori

```

DeltaT32/
├── Schematic/                         # Skematik dalam format PDF
├── Hardwares/
│   ├── esp-unit-c3-v3/               # Desain KiCad untuk board utama ESP32-C3
│   ├── sensor-bmi-v2/                # Desain KiCad untuk modul sensor BMI160
│   └── sensor-mpu-v2/                # Desain KiCad untuk modul sensor MPU6050
├── 3DModels/                          # Model 3D komponen (jika ada)
├── Archives/                          # Backup versi sebelumnya (.zip)
├── Materials/                         # File BOM (Bill of Materials) untuk setiap board
└── README.md                          # Dokumentasi proyek ini

````

---

## Spesifikasi Teknis

| Komponen       | Detail                                     |
|----------------|--------------------------------------------|
| MCU            | ESP32-C3 Mini-1                            |
| Sensor         | BMI160/270, MPU9250 (dengan board terpisah)|
| Desain         | Modular (mainboard + sensor detachable)    |
| CAD Software   | KiCad 8                                    |
| Kompatibilitas | esp-rs / ESP32-Rust (belum diuji)          |
| Output         | Skematik (PDF), BOM, 3D Model              |

---

## Kompatibilitas Firmware

Desain ini dirancang untuk mendukung penggunaan dengan **toolchain esp-rs**, namun **belum terdapat firmware atau pengujian langsung** menggunakan Rust.

> Link referensi: [https://github.com/esp-rs](https://github.com/esp-rs)

---

## Lisensi

Proyek ini dirilis di bawah lisensi **MIT License** — kamu bebas menggunakannya, memodifikasi, dan mendistribusikannya selama mencantumkan atribusi yang sesuai.

---

## Kontributor

* [@J58C](https://github.com/J58C) – Perancang dan pengelola proyek DeltaT32
