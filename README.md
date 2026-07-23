# Relay Driver Module PCB

A relay driver module PCB designed in **EasyEDA** using a **BC547 transistor** and **1N4007 flyback diode** to safely control a relay from a microcontroller or digital logic signal.

---

## 📖 Project Overview

This project demonstrates the design of a simple relay driver module PCB using EasyEDA.

The circuit uses a **BC547 transistor** to drive the relay, a **1N4007 flyback diode** to protect the transistor from back EMF, and an **LED indicator** to show the relay status.

The main objective of this project was to practice PCB design fundamentals, including schematic capture, component placement, PCB routing, and preparing files for PCB manufacturing.

---

## ✨ Features

- Relay driver using BC547 transistor
- Flyback diode protection
- LED relay status indicator
- Screw terminal for load connection
- Input header for microcontroller interface
- Single-layer PCB designed in EasyEDA

---

## ⚙️ Specifications

| Specification | Details |
|---------------|---------|
| PCB Software | EasyEDA |
| PCB Type | Single Layer |
| Relay | 5V |
| Driver | BC547 |
| Protection | 1N4007 Flyback Diode |
| Output | Screw Terminal |

---

## 🧰 Components Used

| Component | Purpose |
|-----------|---------|
| Relay | Switching the load |
| BC547 | Relay driver transistor |
| 1N4007 | Flyback protection |
| LED | Relay status indication |
| 470Ω Resistor | LED current limiting |
| 1kΩ Resistor | Base resistor |
| 10kΩ Resistor | Pull-down resistor |
| Screw Terminal | Output connection |
| Header Pins | Input connection |

---

## 🔄 Working Principle

When an input signal is applied, the BC547 transistor switches ON and energizes the relay coil. The LED indicates that the relay is active, while the 1N4007 flyback diode protects the transistor from voltage spikes generated when the relay is switched OFF.

---

## 🖼️ Project Gallery

### Circuit Schematic

![Circuit Schematic](images/Circuit_Schematic.png)

### PCB Layout

![PCB Layout](images/PCB_Top.png)

### PCB Routing

![PCB Routing](images/PCB_Tracing.png)

### 3D Front View

![PCB 3D Front](images/PCB_3D_Front.png)

### 3D Back View

![PCB 3D Back](images/PCB_3D_Back.png)

### 3D Side View

![PCB 3D Side](images/PCB_3D_Side.png)

---

## 📚 Skills Practiced

- Relay driver circuit design
- PCB schematic design
- Component placement
- PCB routing
- Flyback diode implementation
- Ground pour
- PCB 3D visualization
- Gerber file generation

---

## 🚀 Future Improvements

- Manufacture the PCB
- Test the circuit with a microcontroller
- Improve PCB layout
- Add optocoupler isolation
- Design a compact version

---

## 👨‍💻 Author

**Akhya Bairi**

B.Tech Electronics and Communication Engineering

Learning PCB Design • Embedded Systems • IoT
