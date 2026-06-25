# Class-D Audio Amplifier – Design & Simulation

A complete **Class-D Audio Amplifier** design project covering PWM generation, power stage design and output filtering. The project is supported with **LTspice simulations** and detailed design justification for each component.

---

## 📌 Project Overview

Class-D amplifiers achieve high efficiency by converting audio signals into high-frequency Pulse Width Modulated (PWM) signals and using switching power devices.

This project demonstrates a **Half-Bridge Class-D Amplifier**, designed from first principles and validated through simulation.

---

## 🏗️ System Architecture

```text
Audio Input
     │
     ▼
Comparator + Triangle Wave (PWM)
     │
     ▼
MOSFET Half-Bridge
     │
     ▼
LC Low-Pass Filter
     │
     ▼
Amplified Audio Output
```

---

## ✨ Design Highlights

- PWM-based audio modulation  
- High-frequency switching (**100 kHz**)  
- MOSFET half-bridge power stage  
- LC reconstruction filter   
- LTspice simulation validation  

---

## 🔧 Key Components

| Component | Description |
|------------|-------------|
| Comparator / Op-Amp | Generates PWM by comparing audio signal and carrier waveform |
| Triangle Wave Generator | Produces high-frequency PWM carrier signal |
| NMOS + PMOS | Half-bridge switching stage |
| Inductor (33 µH) | Output smoothing and filtering |
| Capacitor (2.7 µF) | Removes switching noise |
| ±12 V Supply | Symmetrical power rails |

---

## ⚙️ Working Principle

1. The audio signal is applied as the input.
2. A high-frequency triangle wave is generated.
3. The comparator compares the audio signal with the carrier waveform.
4. The comparator output produces a PWM signal.
5. The PWM drives the MOSFET half-bridge switching stage.
6. The output contains high-frequency switching components.
7. An LC low-pass filter reconstructs the amplified audio signal.

---

## 📊 Simulation

The circuit design and performance verification were carried out using **LTspice**.

Simulation analysis includes:

- PWM waveform generation
- MOSFET switching behavior
- Filter response
- Output waveform reconstruction
- Frequency response verification


## 📈 Specifications

| Parameter | Value |
|------------|--------|
| Amplifier Type | Half-Bridge Class-D |
| Switching Frequency | 100 kHz |
| Supply Voltage | ±12 V |
| Output Filter Inductor | 33 µH |
| Output Filter Capacitor | 2.7 µF |
| Simulation Software | LTspice |

---

## 🎯 Objectives

- Design a high-efficiency Class-D amplifier
- Generate PWM-based audio modulation
- Implement MOSFET switching power stage
- Design LC output filtering
- Validate circuit behavior through simulation
- Prepare a PCB-ready architecture

---

## 📝 Future Improvements

- Closed-loop feedback implementation
- Dead-time control optimization
- Higher output power capability
- Thermal analysis
- Full PCB fabrication and hardware testing

---
