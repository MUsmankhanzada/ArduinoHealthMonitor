# 🩺 Arduino Health Monitoring System

This project is a real-time **IoT-based health monitoring system** using an **Arduino**, multiple biomedical sensors (ECG, temperature, and pulse), and the **ESP8266 Wi-Fi module**. It continuously measures patient vitals, sends the data to an IoT platform, and displays the current readings on an LCD screen.

## 📦 Features

- 📡 Sends ECG, temperature, and pulse rate data to the cloud in real-time using ESP8266
- 🧠 Displays live sensor readings on a 16x2 LCD
- 🔁 Continuously monitors and transmits patient vitals
- ⚠️ Can be extended to include alert systems or data logging

## 🛠️ Components Used

| Component            | Description                          |
|---------------------|--------------------------------------|
| Arduino UNO / Nano  | Microcontroller board                |
| ESP8266 Wi-Fi       | For sending data to the IoT platform |
| ECG Sensor Module   | For capturing ECG signals            |
| Temperature Sensor  | e.g., LM35 or DS18B20                |
| Pulse Sensor        | Heart rate monitoring                |
| 16x2 LCD Display    | To show live sensor readings         |
| Resistors, Wires, Breadboard | Basic electronics           |

## 🧠 How It Works

1. **Sensors** capture ECG, body temperature, and heart rate.
2. **Arduino** reads analog/digital values from the sensors.
3. Values are **displayed on the LCD** in real-time.
4. The **ESP8266 module** sends the data to an IoT server (e.g., Thingspeak, Blynk, Firebase).
5. The system **continually monitors** and updates the vitals over Wi-Fi.

