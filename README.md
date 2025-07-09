# IoT-Water-Quality-System-Prototype

IoT Water Quality System Prototype 
— ideal for a capstone project with real-time monitoring, alerts, solar power, and a web dashboard.

✅ 1. 📦 Hardware Components (BOM)

| Component             | Suggested Part                              | Notes                               |
| --------------------- | ------------------------------------------- | ----------------------------------- |
| 🌞 Solar Panel        | 6V 2W solar panel                           | Powers the system during sunlight   |
| 🔋 Battery + Charging | 18650 Li-ion + TP4056 charger               | Power storage and protection        |
| 🔲 Microcontroller    | ESP32 Dev Board                             | Wi-Fi, low power, ADC support       |
| 💧 pH Sensor          | Gravity Analog pH Sensor V2                 | Monitors water acidity/basicity     |
| 🔌 TDS Sensor         | Gravity TDS Sensor (Total Dissolved Solids) | Measures water purity               |
| 🔆 Turbidity Sensor   | SEN0189 (DFRobot)                           | Measures cloudiness                 |
| 🌡️ Temp Sensor       | DS18B20 Waterproof                          | Water temperature                   |
| 📶 IoT Comm Module    | Built-in ESP32 Wi-Fi                        | For real-time monitoring            |
| ⚡ Voltage Regulator   | AMS1117 / Buck Converter                    | Regulate solar input to safe levels |
| 🪛 Other              | Jumper wires, breadboard or PCB             | Assembly                            |


✅ 2. 🧠 Sensor Integration with ESP32

pH Sensor → ADC pin (after voltage divider)
TDS Sensor → ADC pin
Turbidity Sensor → ADC pin
DS18B20 → Digital pin (one-wire)

✅ 3. 🌐 Web Dashboard & IoT Software

Platform Options:
Option A: Node-RED with Dashboard + MQTT (offline/local)
Option B: Blynk (cloud + mobile)
Option C: Firebase Realtime Database + Web app (custom)

We'll proceed with Option A (Node-RED + MQTT) for a full local prototype with:
Real-time water quality dashboard
Historical graphing (optional)
Alerts (e.g. pH too low, TDS too high)
Web UI via http://<device-ip>:1880/ui

/*
//Author: Wyder Lalangan
// GitHub Repository: https://github.com/WyderL24
// LinkedIn Profile: www.linkedin.com/in/wyderl
// Connect with Me: 
//      E-mail: wyderl24@gmail.com
*/
//       Skype: live:.cid.19f15983a80c2bd1
