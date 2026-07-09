<div align="center">

# 🧠 Analog Artificial Neuron Model

### *Design & Implementation using TL074 Quad Operational Amplifier*

<img src="images/banner.png" width="100%">

<br>

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Hardware-TL074-blue?style=for-the-badge)
![Simulation](https://img.shields.io/badge/Proteus-Verified-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/EEE-Project-red?style=for-the-badge)

### ⚡ Bringing Artificial Intelligence Concepts into Real Hardware

</div>

---

# 📖 Overview

Artificial Neural Networks are normally implemented in software.

This project demonstrates how the fundamental operation of a **single artificial neuron** can be implemented entirely using **analog electronic circuits**.

The mathematical neuron equation

```
y = f(ΣWiXi + b)
```

is converted into real voltage operations using **TL074 Operational Amplifiers**, allowing the neuron to process an analog input signal and produce a digital-like decision.

---

# ✨ Key Features

🧠 Analog Artificial Neuron

⚖ Adjustable Synaptic Weight

🎚 Adjustable Bias Voltage

🚦 Adjustable Threshold Level

💡 LED Output Indication

📈 Real-Time Signal Processing

🔬 Proteus Simulation

🛠 Hardware Breadboard Implementation

---

# 🏗 System Architecture

```text
      Input Signal
            │
            ▼
 ┌────────────────────┐
 │ Weight Multiplier  │
 └────────────────────┘
            │
            ▼
 ┌────────────────────┐
 │ Summing + Bias     │
 └────────────────────┘
            │
            ▼
 ┌────────────────────┐
 │ Activation Unit    │
 │ (Comparator)       │
 └────────────────────┘
            │
            ▼
      Binary Output
         (LED)
```

---

# 📸 Project Gallery

## Circuit Diagram

<p align="center">
<img src="images/circuit.png" width="900">
</p>

---

## Hardware Prototype

<p align="center">
<img src="images/hardware.jpg" width="700">
</p>

---

## Testing

<p align="center">
<img src="images/testing.jpg" width="700">
</p>

---

## Output Waveform

<p align="center">
<img src="images/output.png" width="800">
</p>

---

# ⚙ Working Principle

### Stage 1

Weighted Input

The input sine wave is amplified according to the selected weight.

---

### Stage 2

Bias Addition

A controllable DC bias shifts the signal vertically, representing neuron bias.

---

### Stage 3

Activation Function

The comparator compares the input signal with a threshold voltage.

```
Input > Threshold
        ↓
     Output = HIGH

Input < Threshold
        ↓
     Output = LOW
```

---

# 🧩 Components

| Component | Quantity |
|-----------|---------:|
| TL074 Quad Op-Amp | 1 |
| 10k Potentiometer | 3 |
| 10k Resistor | 4 |
| 100k Resistor | 1 |
| 1k Resistor | 2 |
| LEDs | 2 |
| Breadboard | 1 |
| ±9V Supply | 1 |

---

# 💻 Software

- Proteus 8 Professional

---

# 📁 Repository Structure

```text
📂 Analog-Artificial-Neuron-Model
│
├── README.md
├── Project_Report.pdf
│
├── images
│   ├── banner.png
│   ├── circuit.png
│   ├── hardware.jpg
│   ├── testing.jpg
│   └── output.png
│
├── circuit
│   ├── Artificial_Neuron.pdsprj
│   └── Artificial_Neuron.pdsn
│
├── datasheets
│   └── TL074.pdf
│
└── simulation
    └── waveform.png
```

---

# 📊 Results

✅ Weighted Summation Verified

✅ Bias Adjustment Verified

✅ Threshold Activation Verified

✅ Comparator Operation Verified

✅ LED Switching Verified

---

# 🌍 Applications

- Artificial Intelligence Education
- Neuromorphic Computing
- Analog Signal Processing
- Electronic Circuit Learning
- Hardware Neural Networks

---

# 📚 Documentation

📄 Full Project Report

📐 Circuit Diagram

📷 Hardware Images

📈 Simulation Results

---

# 👨‍💻 Author

## **Fardin Meah**

Electrical & Electronic Engineering (EEE)

---

<div align="center">

## ⭐ Star this repository if you found it useful!

*"Bridging Artificial Intelligence with Analog Electronics."*

</div>
