# Automatic Pill Dispenser

An Arduino-powered **automatic pill dispenser** with a touchscreen interface and motor-driven delivery system. Designed to help individuals take the correct medication at the right time, this system vibrates and dispenses pills on a timed schedule, and displays important information on a TFT LCD screen.

---

## 🧠 Features

- **Touchscreen Interface** (FT6336 touch panel)
- **LCD Display** (480x320, ST7796S)
- **Motor-Controlled Pill Dispensing** with vibration and release mechanisms
- **Ultrasonic Sensor** to detect presence of pills or tray
- **Custom Logo Display** on boot using bitmap
- Configurable timing system (set via code)

---

## 🔧 Hardware Used

- **Arduino Mega 2560**
- **TFT LCD with Touch** (ST7796S via `LCDWIKI_SPI`)
- **FT6336G Capacitive Touch Controller**
- **4x DC Motors** for compartment and vibration
- **Ultrasonic Distance Sensor** (HC-SR04 or similar)
- **Wires, Power Supply, and Mounting Hardware**

---

## 🔌 Pin Configuration

| Component                | Arduino Pin |
|-------------------------|-------------|
| LCD CS                  | 10          |
| LCD DC/RS               | 9           |
| LCD RESET               | 8           |
| LCD LED                 | 5           |
| Touch INT               | 7           |
| Touch RST               | 6           |
| Touch SDA               | A4          |
| Touch SCL               | A5          |
| Ultrasonic Trig/Echo    | 40          |
| Vibration Motor 1       | 22, 23      |
| Vibration Motor 2       | 24, 25      |
| Top Dispense Motor      | 28, 29      |
| Bottom Dispense Motor   | 26, 27      |

---

## 🖥️ Libraries Required

Install these via the Arduino Library Manager:

- `LCDWIKI_GUI`
- `LCDWIKI_SPI`
- `FT6336G`
- `Arduino.h`

---

