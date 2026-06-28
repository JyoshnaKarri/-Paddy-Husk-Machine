# Paddy Husking Machine — Arduino Uno Based Automation

An embedded systems project that automates the paddy husking process using an Arduino Uno — controlling motor speed, detecting grain flow, and ensuring consistent husking without manual intervention.

**Hardware:** Arduino Uno  
**Language:** Embedded C  
**Domain:** Embedded Systems · Industrial Automation

---

## 🌾 Problem Statement

Traditional paddy husking is done manually or with uncontrolled machines — leading to inconsistent output, grain breakage, and wasted effort. This project automates the process using sensor-based control, ensuring the machine operates only when paddy is present and stops safely when the process is complete.

---

## ⚙️ How It Works

1. Sensor detects presence of paddy at the input
2. Arduino triggers the husking motor
3. Motor speed is controlled based on load/grain flow
4. Output sensor detects when husking is complete
5. System stops automatically — no manual switching needed

---

## 🔧 Hardware Components

| Component | Purpose |
|---|---|
| Arduino Uno | Main microcontroller — control logic |
| DC Motor / Relay Module | Drives the husking mechanism |
| IR Sensor / Proximity Sensor | Detects paddy presence at input |
| Output Sensor | Detects completion of husking |
| Power Supply | Powers motor and Arduino |
| Connecting Wires + Breadboard | Circuit connections |

---

## 💻 Software

- **Language:** Embedded C (Arduino IDE)
- **Logic:** Sensor-triggered motor control with automatic stop
- **Serial Monitor:** Used for real-time status logging during testing

---

## 📋 Working Flow

```
Power ON
   ↓
Sensor detects paddy → Motor starts
   ↓
Husking in progress → Motor runs at set speed
   ↓
Output sensor triggers → Motor stops
   ↓
System ready for next cycle

## 🚀 How to Run

1. Open `paddy_husking.ino` in Arduino IDE
2. Connect Arduino Uno via USB
3. Select **Board:** Arduino Uno and correct **Port**
4. Click **Upload**
5. Open Serial Monitor (9600 baud) to view status logs
6. Power the circuit and test with paddy input

---

## 🔗 Links

- 🌐 [Portfolio](https://jyoshnakarri.github.io/Jyoshna-Karri/)
- 💼 [LinkedIn](https://www.linkedin.com/in/jyoshna-k-5b1626401/)
