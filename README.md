# 🔥 ESP32-Based Gas Leakage Alert System

An ESP32-based gas leakage detection and alert system simulated using Wokwi. The project uses an MQ-2 gas sensor to monitor gas levels and activates a buzzer and LED when the sensor reading exceeds a predefined threshold.

## 🚀 Features
- **Gas Detection:** Monitors gas levels using the MQ-2 sensor.
- **Audible Alert:** Activates a buzzer when the gas reading exceeds the threshold.
- **Visual Alert:** Turns on an LED to indicate potential gas leakage.
- **Real-Time Monitoring:** Displays sensor readings and system status through the Serial Monitor.
- **Simulation:** Developed and tested using the Wokwi online simulator.

## 🛠️ Technologies Used
- ESP32
- MQ-2 Gas Sensor
- Arduino C++
- Wokwi Simulator

## ⚙️ Working Principle
The ESP32 continuously reads the analog output of the MQ-2 gas sensor. When the reading reaches or exceeds a predefined threshold, the system activates the buzzer and LED and displays a warning message in the Serial Monitor. Otherwise, the system remains in normal monitoring mode.

## 🎯 Applications
- Educational embedded systems projects
- Gas leakage detection demonstrations
- Microcontroller and sensor interfacing experiments
- IoT project development and prototyping

## ⚠️ Disclaimer
This project is an educational prototype and is not a certified gas safety device. The sensor threshold is illustrative and must not be used as a reliable measurement of gas concentration or as a substitute for a certified gas detector.

## 👨‍💻 Author
Khan
