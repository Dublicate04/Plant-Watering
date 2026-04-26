# 🌱 Smart Plant Watering System

Automatic plant watering system
using ESP32 with soil moisture
sensor, relay controlled pump
and Blynk IoT control!

## 🛠️ Components
- ESP32 Dev Board
- Soil Moisture Sensor
- Relay Module
- Mini Water Pump
- 16x2 LCD I2C
- Jumper wires

## ⚡ Circuit Connections
| Component    | Pin | ESP32  |
|-------------|-----|--------|
| Moisture AO | AO  | GPIO34 |
| Relay IN    | IN  | GPIO26 |
| LCD SDA     | SDA | GPIO21 |
| LCD SCL     | SCL | GPIO22 |

## 🔧 Features
- Real-time moisture monitoring
- Auto pump ON when soil dry
- Auto pump OFF when soil wet
- Manual control via Blynk
- Push notifications

## 💧 Moisture Levels
- 0-30%  → DRY → Pump ON 🚿
- 30-70% → OK  → Monitor 👀
- 70%+   → WET → Pump OFF ✅

## 📱 Libraries Used
- LiquidCrystal_I2C
- BlynkSimpleEsp32
