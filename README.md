## 🔐 Smart Password-Based Door Lock System using Arduino

An affordable and efficient IoT-based door security system built using **Arduino UNO**, **Keypad**, and a **Servo Motor**, designed as a project for the academic year 2024–2025 and NAAC Project Presentations.

---

### 📌 Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Components Used](#components-used)
* [Circuit Diagram](#circuit-diagram)
* [How It Works](#how-it-works)
* [Installation & Setup](#installation--setup)
* [Results](#results)
* [Future Enhancements](#future-enhancements)

---

### 📖 Project Overview

This project aims to build a **Smart Password-Based Door Lock System** using Arduino that enhances security using a password mechanism. It eliminates the need for physical keys and offers a cost-effective alternative to expensive biometric systems.

> The system allows door access only when the correct password is entered using a 4x4 keypad. A servo motor is used to actuate the lock mechanism. The system is powered by an Arduino UNO which acts as the brain of the setup.

---

### ✨ Features

* 🔒 Secure password-based access
* ⚙️ Easy setup and customization
* 💰 Cost-effective and power-efficient
* 🔁 Password reset and auto-lock features
* 🔧 Modular design (easy to upgrade)

---

### 🧩 Components Used

| Component      | Description                     |
| -------------- | ------------------------------- |
| Arduino UNO    | Microcontroller board           |
| 4x4 Keypad     | Input module for password entry |
| Servo Motor    | Actuates lock (rotation-based)  |
| Jumper Wires   | For circuit connections         |
| Breadboard/PCB | For component mounting          |
| Power Supply   | Battery or USB-based power      |

![image](https://github.com/user-attachments/assets/e8656379-fd04-483b-bcef-53648066806a)
![image](https://github.com/user-attachments/assets/49b4130e-d626-49ca-9119-1e0cacbecbb8)
![image](https://github.com/user-attachments/assets/ac04c280-290f-4f0e-99dc-e34beec3be79)
![image](https://github.com/user-attachments/assets/2ffd9179-5117-4625-bcb5-0fc87be48383)

---

### 🧠 How It Works

1. **Password Setup**: A default password is hardcoded into the Arduino sketch.
2. **User Input**: User enters the password using the keypad.
3. **Password Validation**:

   * ✅ If correct: The servo motor rotates 90° to unlock.
   * ❌ If incorrect: The door remains locked.
4. **Auto-lock**: After a delay or a reset input, the servo returns to its initial (locked) position.

> The password can be changed directly from the Arduino code.

---
### Circuit Diagram
![image](https://github.com/user-attachments/assets/0bd4a04a-55c9-4793-9af7-24ca304a8288)


---
### 🛠 Installation & Setup

1. **Circuit Wiring**:

   * Connect 4x4 keypad to digital pins of Arduino.
   * Connect servo motor to a PWM pin (e.g., D9).
   * Use jumper wires for reliable connections.

2. **Upload Code**:

   * Use the Arduino IDE to upload the code.
   * Ensure the correct COM port and board are selected.

3. **Power On**:

   * Provide power via USB or external battery pack.

---

### 🖼️ Results

* The system successfully restricts access until the correct password is entered.
* Compact and scalable setup suitable for home, lockers, or offices.

![image](https://github.com/user-attachments/assets/caeb0efb-bad5-4307-8b5d-48ab0d7fc4d3)
![image](https://github.com/user-attachments/assets/2ebecc8b-8a91-4f44-89bf-843c31c325a5)


---
### 🔮 Future Enhancements

* 🔑 **Biometric Integration** (Fingerprint/Retina)
* 📱 **Bluetooth/Wi-Fi based remote control**
* 💬 **LCD/LED status display**
* 🧠 **AI & ML for access pattern detection**
* 🔒 **Multi-factor authentication**
* 🔋 **Solar/UPS-based power supply**
* 🗣️ **Voice recognition integration**
* 🌐 **IoT Smart Home ecosystem compatibility**

---
