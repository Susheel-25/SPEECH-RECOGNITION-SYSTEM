# SPEECH-RECOGNITION-SYSTEM

**COMPANY:** CODTECH IT SOLUTIONS

**NAME:** KUNTUMALLA BUGGA SUSHEEL

**INTERN ID:** CT04DZ1724 

**DOMAIN:** Embedded Systems

**DURATION:** 4 WEEKS  

**MENTOR:** NEELA SANTOSH  

**DESCRIPTION:**


## 📌 Task 4: SPEECH-RECOGNITION-SYSTEM


It is a **Speech Recognition–based Device Control System** using **Arduino UNO**.  
Since **Tinkercad** does not provide a Speech Recognition Module (like Elechouse Voice Recognition V3), I have simulated the speech input using the **Serial Monitor**.

In real hardware, the commands would be captured using a speech module and processed by Arduino to control devices such as lights or fans.  
In Tinkercad simulation, I type the commands into the Serial Monitor to mimic speech input.

---

## 🎯 Features
- Control multiple devices using voice commands *(simulated via Serial Monitor in Tinkercad)*.
- Supports commands:
  - `Light On`
  - `Light Off`
  - `Fan On`
  - `Fan Off`
- Can be adapted to work with real Voice Recognition hardware.

---

## 🛠 Components Used (Tinkercad Simulation)
- Arduino UNO  
- Breadboard  
- 2 × LEDs (Light, Fan)  
- 2 × 220Ω Resistors  
- Jumper Wires  

> **Note:** In a real setup, an **Elechouse Voice Recognition Module V3** or similar would replace the Serial Monitor input.

---

## 🔌 Circuit Connections
| Arduino Pin | Component   | Description |
|-------------|-------------|-------------|
| Pin 8       | LED1 (+)    | Light Control |
| GND         | LED1 (-) via 220Ω resistor |  
| Pin 9       | LED2 (+)    | Fan Control |
| GND         | LED2 (-) via 220Ω resistor |  
| USB Port    | Serial Monitor | Speech Command Simulation |

---

## 📷 Circuit Diagram (Tinkercad Simulation)
![Image](https://github.com/user-attachments/assets/f5455e2b-e730-4037-922c-2d6bb109ce02)

## Output:
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/4d295a77-8ea5-432d-81af-70dfbfb3c470" />


---
