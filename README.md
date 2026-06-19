# Password-Based Door Lock System

A secure, embedded access control system designed around the **LPC2148 (ARM7 TDMI-S)** microcontroller. This project utilizes a 4x3 matrix keypad for password authentication, a 16x2 LCD for real-time user feedback, and a DC motor driven by an L293D IC to simulate a door-locking mechanism.

The system was fully simulated and verified in **Proteus** before hardware deployment.

---

## 🚀 Features

* **Secure Keypad Authentication:** Integrated a 4x3 matrix keypad with a robust debouncing and scanning algorithm, achieving **99% accuracy** in input recognition.
* **Real-Time Visual Feedback:** Uses a 16x2 character LCD to display system states (e.g., "Enter Password", "Access Granted", "Access Denied").
* **Motor-Driven Lock Control:** Drives a DC motor via an L293D H-bridge IC to securely lock or unlock the door based on authentication results.
* **Efficient Firmware:** Written entirely in **Embedded C**, optimizing register-level configurations for the ARM7 architecture.

---

## 🛠️ Hardware & Software Stack

### Hardware Components
| Component | Description |
| :--- | :--- |
| **LPC2148 Microcontroller** | Core ARM7-based MCU managing I/O and logic. |
| **4x3 Matrix Keypad** | User interface for password entry. |
| **16x2 LCD (LM016L)** | Displays real-time status messages to the user. |
| **L293D Driver IC** | Provides the high current required to drive the DC motor. |
| **DC Motor** | Simulates the physical deadbolt/door latch mechanism. |

### Software Tools
* **Keil uVision:** IDE used for writing firmware in Embedded C and compiling the hex file.
* **Proteus Design Suite:** Used for schematic capture and real-time interactive simulation.

---


