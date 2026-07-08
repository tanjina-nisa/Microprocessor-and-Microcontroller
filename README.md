# Nano Vibration Energy Harvester

A microcontroller-based energy harvesting system that converts mechanical vibrations (such as human footsteps) into usable electrical energy using piezoelectric sensors. The harvested energy is stored in rechargeable batteries and monitored in real-time using an ESP32 microcontroller with IoT capabilities.

---

## 📌 Project Overview

This project demonstrates how ambient mechanical vibrations can be converted into electrical energy through piezoelectric technology. The generated energy is conditioned, stored, regulated, and utilized to power low-power electronic devices while providing real-time monitoring through an ESP32-based web interface.

The system is designed as a proof-of-concept for sustainable energy harvesting in smart buildings, public walkways, universities, airports, and other high-footfall environments.

---

## ✨ Features

- Harvests electrical energy from footsteps and vibrations
- Converts AC output from piezoelectric sensors into usable DC power
- Stores harvested energy in a rechargeable Li-ion battery
- Regulates output voltage using an LM2596 Buck Converter
- Real-time voltage monitoring with ESP32
- LCD display for local monitoring
- IoT-based web dashboard for remote monitoring
- Modular and scalable hardware architecture

---

## 🛠 Technologies Used

### Hardware

- ESP32 Microcontroller
- Piezoelectric Sensors
- Bridge Rectifier
- 2S Li-ion Charging Board
- 7.2V Li-ion Battery
- LM2596 Buck Converter
- 16×2 LCD Display
- Breadboard
- LED Load

### Software

- Arduino IDE
- Embedded C / Arduino
- ESP32 Web Server
- ADC (Analog-to-Digital Conversion)

---

## ⚙️ System Workflow

```
Footstep
     │
     ▼
Piezoelectric Sensors
     │
     ▼
AC Voltage Generation
     │
     ▼
Bridge Rectifier
     │
     ▼
DC Output
     │
     ▼
2S Charging Board
     │
     ▼
Li-ion Battery
     │
     ▼
LM2596 Buck Converter
     │
     ▼
Stable 5V Output
     │
     ▼
ESP32 Microcontroller
     │
     ├── LCD Display
     └── Web Dashboard
```

---

## 📊 Project Highlights

- Converts mechanical vibrations into electrical energy
- Implements real-time voltage monitoring
- Demonstrates battery charging and power management
- Supports IoT-based remote monitoring
- Promotes sustainable and renewable energy solutions

---

## 📈 Experimental Results

- Peak Generated Voltage: **5.664 V**
- Maximum Output Voltage: **0.271 V**
- Total Harvested Energy: **0.023 J**
- System Efficiency: **8.70%**
- Successfully powered low-power embedded devices for demonstration.

---

## 💡 Applications

- Smart Buildings
- Smart Cities
- Public Walkways
- Railway Stations
- Airports
- Shopping Malls
- University Campuses
- IoT Sensor Networks
- Sustainable Energy Research

---

## 🚀 Future Improvements

- Increase the number of piezoelectric sensors for higher energy output
- Improve energy conversion efficiency
- Integrate supercapacitors for faster charging
- Develop a custom PCB
- Add cloud-based IoT monitoring
- Implement AI-based energy prediction and analytics

---

## 🎯 Skills Demonstrated

- Embedded Systems
- ESP32 Programming
- Arduino Development
- Sensor Interfacing
- Power Electronics
- IoT Development
- Circuit Design
- Energy Harvesting
- Battery Management
- Hardware Prototyping

---

## 👨‍💻 Authors

- **Tanjina Akter Nisa**
- **Md. Daudul Islam**
- **Saswata Ghosal**

Department of Computer Science & Engineering  
University of Asia Pacific

---

## 📄 License

This project was developed as an academic project for educational and research purposes.
