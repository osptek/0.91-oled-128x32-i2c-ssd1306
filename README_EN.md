# 0.91" 128×32 OLED I2C module (SSD1306) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides an **ESP-IDF sample project**. Datasheets and specifications will be added to `docs/` when available.

## Product overview

| Item | Description |
|:--|:--|
| Module | 0.91-inch **OLED** (monochrome), **128×32** resolution |
| Interface | **I2C** |
| Driver IC | **SSD1306** |
| Spec ID | **`0.91-oled-128x32-i2c-ssd1306`** is the common product designation in documentation |
| Related size | **0.96″ 128×64 OLED I2C** is in **`0.96-oled-128x64-i2c-ssd1315`** (SSD1315) — different size and driver |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `assets/` | Demo screenshots for sample projects (when available) |
| `docs/` | Datasheets and specifications (**to be added**) |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description |
|:--|:--|
| `examples/` root | ESP32-S3 bringup: SSD1306 I2C display and spectrum visualization demo |

### Sample project paths

| Description | Path |
|:--|:--|
| SSD1306 I2C bringup | `examples/esp32s3-0.91-oled-128x32-i2c-ssd1306-bringup/` |
