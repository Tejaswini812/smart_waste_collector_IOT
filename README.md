# 🌊 CleanBot: The Smart Waste Collector

<div align="center">

![Project Banner](images/robot_model.jpg)

### 🚀 IoT-Based Water Surface Cleaning Robot

![Arduino](https://img.shields.io/badge/Arduino-UNO-blue?style=for-the-badge&logo=arduino)
![Bluetooth](https://img.shields.io/badge/HC--05-Bluetooth-green?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-C%2FC%2B%2B-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</div>

---

# 📖 About The Project

CleanBot is an IoT-based smart robotic system designed to collect floating waste from water bodies such as lakes, ponds, and rivers. The robot operates using Bluetooth communication and Arduino-based motor control to navigate across the water surface and collect floating trash efficiently.

The project helps in reducing marine pollution, minimizing manual labor, and promoting environmental sustainability using low-cost embedded system technologies.

---

# ✨ Features

✔️ Bluetooth-Based Wireless Control  
✔️ Real-Time Robot Navigation  
✔️ Floating Water Surface Operation  
✔️ Arduino UNO Based Processing  
✔️ Low-Cost Embedded System  
✔️ FSM (Finite State Machine) Logic  
✔️ Trash Collection Mechanism  
✔️ Eco-Friendly Design  
✔️ Easy Maintenance & Scalability  

---

# 🛠️ Hardware Components

| Component | Description |
|------------|-------------|
| Arduino UNO | Main microcontroller |
| HC-05 Bluetooth Module | Wireless communication |
| L298N Motor Driver | Controls motor movement |
| 12V DC Motors | Robot propulsion |
| 12V Battery | Power supply |
| Floating Chassis | Supports robot on water |
| Trash Scoop / Net | Collects floating waste |
| Connecting Wires | Hardware connectivity |

---

# 💻 Software Requirements

| Software | Purpose |
|----------|----------|
| Arduino IDE | Programming & Uploading Code |
| Embedded C/C++ | Logic Implementation |
| Arduino Bluetooth Controller App | Robot Control |
| Dabble App | Bluetooth Communication |

---

# 🎯 Project Objectives

- To develop a low-cost water cleaning robot.
- To reduce floating waste pollution in water bodies.
- To minimize human effort in waste collection.
- To implement Bluetooth-based wireless control.
- To provide real-time movement and navigation.
- To promote smart environmental sustainability.

---

# ⚙️ Working Principle

The CleanBot works using Bluetooth communication between a mobile application and the robot.

1️⃣ User sends movement commands from mobile app  
2️⃣ HC-05 Bluetooth module receives commands  
3️⃣ Arduino UNO processes the commands  
4️⃣ Arduino controls the L298N motor driver  
5️⃣ Motor driver activates DC motors  
6️⃣ Robot moves on water surface  
7️⃣ Front scoop collects floating waste  
8️⃣ Waste gets stored inside collection compartment  

---

# 🔄 Project Flow

```text
Mobile Application
        ↓
Bluetooth Commands
        ↓
HC-05 Bluetooth Module
        ↓
Arduino UNO
        ↓
L298N Motor Driver
        ↓
DC Motors
        ↓
Robot Navigation
        ↓
Trash Collection Mechanism
        ↓
Waste Storage
```

---

# 🏗️ System Architecture

<div align="center">

![System Architecture](images/system_architecture.jpg)

</div>

```text
+----------------------+
| Mobile Application   |
+----------------------+
           ↓
+----------------------+
| HC-05 Bluetooth      |
| Module               |
+----------------------+
           ↓
+----------------------+
| Arduino UNO          |
| Processing Unit      |
+----------------------+
           ↓
+----------------------+
| L298N Motor Driver   |
+----------------------+
           ↓
+----------------------+
| DC Geared Motors     |
+----------------------+
           ↓
+----------------------+
| Trash Collection     |
| Mechanism            |
+----------------------+
```

---

# 🔌 Hardware Connections

## 📍 HC-05 Bluetooth Module Connection

| HC-05 Pin | Arduino UNO |
|-----------|--------------|
| VCC | 5V |
| GND | GND |
| TXD | RX (Pin 0) |
| RXD | TX (Pin 1) |

---

## 📍 L298N Motor Driver Connection

| L298N Pin | Arduino UNO |
|------------|--------------|
| IN1 | Pin 8 |
| IN2 | Pin 9 |
| IN3 | Pin 10 |
| IN4 | Pin 11 |
| ENA | 5V / PWM |
| ENB | 5V / PWM |
| GND | GND |

---

## 📍 DC Motor Connection

| Motor | Connected To |
|-------|---------------|
| Left Motor | OUT1 & OUT2 |
| Right Motor | OUT3 & OUT4 |

---

## 📍 Power Supply Connection

| Component | Power Source |
|-----------|---------------|
| Arduino UNO | 12V Battery |
| L298N Driver | 12V Battery |
| DC Motors | Through L298N |

---

# 🧠 FSM (Finite State Machine) Logic

| Command | Action |
|----------|---------|
| F | Move Forward |
| B | Move Backward |
| L | Turn Left |
| R | Turn Right |
| S | Stop |

---

# 📋 Detailed Project Working

## 🔹 Step 1: Initialization
- Robot powers ON
- Bluetooth module initializes
- Arduino starts motor setup

---

## 🔹 Step 2: Bluetooth Communication
- Mobile app connects with HC-05
- Commands are transmitted wirelessly

---

## 🔹 Step 3: Command Processing
- Arduino reads received command
- FSM logic determines movement

---

## 🔹 Step 4: Motor Activation
- L298N receives control signals
- Motors execute movement

---

## 🔹 Step 5: Trash Collection
- Front scoop collects floating waste
- Waste stored inside collection area

---

## 🔹 Step 6: Stop / Return
- Robot stops after cleaning
- Waste removed manually

---

# 📷 Project Images

## 🔹 Complete Robot Model

```markdown
![Complete Robot](images/robot_model.jpg)
<img width="876" height="489" alt="image" src="https://github.com/user-attachments/assets/10665986-505d-4bcb-a172-fadb9f3c7372" />

```

---

## 🔹 Hardware Connection

```markdown
![Hardware Connection](images/hardware_connection.jpg)
<img width="898" height="639" alt="image" src="https://github.com/user-attachments/assets/19c7a259-b7fa-4c9e-aefe-1d79b65c6fae" />

```

---

## 🔹 Circuit Diagram

```markdown
![Circuit Diagram](images/circuit_diagram.jpg)
```

---

## 🔹 Working Model

```markdown
![Working Model](images/working_model.jpg)
<img width="878" height="528" alt="image" src="https://github.com/user-attachments/assets/7daf65d0-b4be-4230-bac0-76f9a7ad5bab" />

```

---

## 🔹 Trash Collection Mechanism

```markdown
![Trash Collection](images/trash_collection.jpg)
```

---

## 🔹 Arduino Setup

```markdown
![Arduino Setup](images/arduino_setup.jpg)
<img width="459" height="307" alt="image" src="https://github.com/user-attachments/assets/93394978-e166-4e05-bd8d-4648461335fb" />

```

---

## 🔹 Bluetooth App Control

```markdown
![Bluetooth Control](images/bluetooth_control.jpg)
<img width="322" height="329" alt="image" src="https://github.com/user-attachments/assets/46fba8c9-4540-4ea4-981e-0b72018cb343" />

```

---

# 📊 Performance Analysis

| Parameter | Existing System | Proposed System |
|------------|----------------|----------------|
| Response Time | 3–5 sec | ~1 sec |
| Collection Efficiency | 75% | 90% |
| Human Effort | High | Low |
| Control System | Manual | Bluetooth |
| Reliability | Medium | High |

---

# 🌱 Advantages

✅ Reduces Water Pollution  
✅ Minimizes Manual Labor  
✅ Low Operational Cost  
✅ Wireless Real-Time Control  
✅ Eco-Friendly System  
✅ Easy Maintenance  
✅ Portable & Scalable  

---

# 🌍 Applications

- Lake Cleaning
- Pond Cleaning
- River Cleaning
- Smart Waste Management
- Environmental Monitoring

---

# 🚀 Future Enhancements

🔹 Solar Powered Charging System  
🔹 AI-Based Waste Detection  
🔹 GPS Navigation System  
🔹 Obstacle Avoidance Sensors  
🔹 Autonomous Navigation  
🔹 IoT Cloud Monitoring  

---

# 📂 Project Folder Structure

```text
CleanBot/
│
├── Arduino_Code/
│   └── cleanbot.ino
│
├── images/
│   ├── robot_model.jpg
│   ├── hardware_connection.jpg
│   ├── system_architecture.jpg
│   ├── circuit_diagram.jpg
│   ├── working_model.jpg
│   ├── trash_collection.jpg
│   ├── arduino_setup.jpg
│   └── bluetooth_control.jpg
│
├── Documentation/
│   └── Project_Report.pdf
│
├── README.md
└── LICENSE
```

---

# 🏁 Conclusion

The CleanBot project successfully demonstrates a smart and cost-effective robotic solution for cleaning floating waste from water bodies. The integration of Arduino UNO, Bluetooth communication, DC motors, and FSM-based control provides smooth navigation and efficient trash collection. The project supports environmental sustainability while reducing human effort and operational cost.
<img width="876" height="489" alt="image" src="https://github.com/user-attachments/assets/e8db29db-94f2-4bda-804c-99cfc00ae8ac" />

---

# 👩‍💻 Developed By

### Tejaswini D  
🎓 Information Science & Engineering  
🏫 Global Academy of Technology, Bengaluru  

---

# 📚 References

1. Autonomous Robotic System for Collecting Garbage Over Small Water Bodies  
2. Water Surface Solid Waste Cleaning Robot for Ponds  
3. Android Application Controlled Water Trash Bot Using IoT  
4. Solar Powered RT-Bot River Trash Collecting Robot  
5. IEEE Research Papers on Smart Waste Management  

---

<div align="center">

## ⭐ If you like this project, give it a Star ⭐

</div>
