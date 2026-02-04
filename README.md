# 🐾 Animal Detection in Farms Using PIR Motion Sensors and IoT-Based Alert System

An **IoT-based automated farm protection system** designed to detect animal intrusion using **PIR motion sensors** and prevent crop damage through **audio and visual deterrents** with minimal human intervention.

---

## 📌 Project Overview

Agricultural fields often suffer crop losses due to animal intrusions. Traditional protection methods are manual, inefficient, and labor-intensive.  
This project presents a **low-cost, scalable IoT solution** that automatically detects animal movement and triggers deterrent mechanisms to protect crops effectively.

The system uses a **two-level detection approach**:
- **First Level:** Detects motion at the field boundary and plays predator sounds.
- **Second Level:** Activates high-intensity lights if the animal continues moving inward.

---

## 🛠️ Technologies Used

- **Hardware:**  
  - Arduino Uno  
  - PIR Motion Sensors  
  - LED Lights  
  - Audio Module (Speaker)  

- **Software:**  
  - Arduino IDE  
  - Embedded C  

- **Other Concepts:**  
  - Internet of Things (IoT)  
  - Motion Detection  
  - Wireless Monitoring  

---

## ⚙️ System Architecture

1. PIR sensors detect infrared radiation changes caused by animal movement.  
2. Sensor data is sent to the microcontroller (Arduino Uno).  
3. Based on detection level:
   - Predator sounds are played (audio deterrent).
   - High-intensity LEDs are activated (visual deterrent).
4. Alerts and control actions can be monitored remotely via IoT connectivity.

---

## 🔍 Modules Description

### 1️⃣ Motion Detection Module
- Uses PIR sensors placed at strategic locations.
- Detects animal movement based on heat signatures.
- Divided into **outer-layer** and **inner-layer** detection zones.

### 2️⃣ Audio Deterrent Module
- Plays randomized predator sounds upon first-level detection.
- Prevents animals from becoming accustomed to a single sound.

### 3️⃣ Visual Deterrent Module
- Activates high-intensity LED lights during second-level detection.
- Effective during night-time intrusions.

### 4️⃣ Control Module
- Arduino Uno processes sensor input and controls output devices.
- Executes detection logic and response mechanisms.

---

## 🚀 Installation & Execution

### Hardware Setup
1. Connect PIR sensors to the Arduino input pins.
2. Connect the LED lights and audio module via appropriate interfaces.
3. Ensure proper power supply to all components.

### Software Setup
1. Install **Arduino IDE**.
2. Connect Arduino Uno to the system via USB.
3. Upload the provided source code to the Arduino board.
4. Open **Serial Monitor** to observe sensor activity logs.

---

## ✅ Testing & Validation

- Simulated animal movement to test detection accuracy.
- Verified correct triggering of audio and light deterrents.
- Adjusted sensor sensitivity and response timing for optimal performance.

---

## 🌱 Advantages

- Reduces crop damage caused by animals  
- Minimizes human effort and monitoring  
- Low-cost and scalable solution  
- Effective during both day and night  

---

## 🔮 Future Enhancements

- Integration of camera modules for animal classification  
- AI-based detection to reduce false triggers  
- Mobile application for real-time alerts and configuration  

---

## 👨‍💻 Team Members

- A. Hema  
- K. Pavan Naga Kesava  
- Ch. Dhana Meghana  
- **B. Sasidhar**
