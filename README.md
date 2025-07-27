# ESP32 GPS Tracker with NMEA Parsing

A GPS tracker implementation using ESP32 and a popular NEO-6M GPS module, parsing NMEA sentences to extract live location (lat, lon, speed, time).

## 🔧 Hardware
- ESP32
- GPS NEO-6M Module
- Jumper Wires

## ⚙️ Connections
| GPS NEO-6M | ESP32         |
| ---------- | ------------- |
| VCC        | 3.3V          |
| GND        | GND           |
| TX         | GPIO 16 (RX2) |
| RX         | GPIO 17 (TX2) |

## 🔍 Features
- Serial communication (9600 baud)
- NMEA sentence parsing using TinyGPS++
- Real-time location data

## 🛠️ Libraries Used
- [TinyGPSPlus](https://github.com/mikalhart/TinyGPSPlus)

## 📦 Setup Instructions
1. Clone the repo.
2. Open `src/gps_tracker.ino` in Arduino IDE/PlatformIO.
3. Install dependencies.
4. Upload code to ESP32.

## 🛰️ Output Sample (Serial Monitor)
Latitude: 12.9716
Longitude: 77.5946
Speed: 0.24 km/h
Satellites: 6
Time: 14:32:10


## 🧪 Future Upgrades
- GSM/BLE integration for remote tracking
- Location logging to SD card
- OLED display support

## 📃 License
MIT License

