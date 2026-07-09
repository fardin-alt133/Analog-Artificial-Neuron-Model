<div align="center">

# 🧠 Analog Artificial Neuron Model

### *Design & Implementation using TL074 Quad Operational Amplifier*

<br>

[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=github)](https://github.com)
[![Hardware](https://img.shields.io/badge/Hardware-TL074-blue?style=for-the-badge&logo=hardware)](https://github.com)
[![Simulation](https://img.shields.io/badge/Proteus-Verified-orange?style=for-the-badge&logo=circuitverse)](https://github.com)
[![Platform](https://img.shields.io/badge/EEE-Project-red?style=for-the-badge&logo=academia)](https://github.com)

<h4>⚡ Bringing Artificial Intelligence Concepts into Real Hardware ⚡</h4>

</div>

---

## 📖 Overview

Artificial Neural Networks (ANNs) are typically implemented using software algorithms. This project takes a different approach by demonstrating the hardware-level implementation of a **single artificial neuron using analog electronic circuits**.

The fundamental mathematical neuron model is given by:

$$y = f(\sum W_i X_i + b)$$

This equation is translated into real-time voltage operations using the **TL074 Quad Operational Amplifier**. The circuit seamlessly performs weighted summation, bias adjustment, and threshold-based activation to generate a distinct binary output signal.

---

## ✨ Key Features

* 🧠 **Analog Artificial Neuron Implementation** – Pure hardware-based decision making.
* ⚖️ **Adjustable Synaptic Weight** – Fine-tune input sensitivity.
* 🎚️ **Adjustable Bias Voltage** – Shift the activation baseline easily.
* 🚦 **Adjustable Threshold Level** – Flexible control over the activation function trigger point.
* 💡 **LED Output Indication** – Immediate visual feedback of the neuron's state.
* 📈 **Real-Time Signal Processing** – Zero algorithmic latency.
* 🔬 **Proteus Simulation Verification** – Fully tested pre-hardware design.
* 🛠️ **Breadboard Implementation** – Robust and clean physical prototyping.

---

## 🏗️ System Architecture

```text
          Input Signal
               │
               ▼
     ┌──────────────────┐
     │ Weight Adjustment │
     │   (Multiplier)    │
     └──────────────────┘
               │
               ▼
     ┌──────────────────┐
     │ Summing Amplifier │
     │  + Bias Addition  │
     └──────────────────┘
               │
               ▼
     ┌──────────────────┐
     │ Activation Unit  │
     │   Comparator     │
     └──────────────────┘
               │
               ▼
          Binary Output
              (LED)
⚙️ Working Principle1. Weighted Input StageThe input signal is scaled by an adjustable weight using an inverting/non-inverting operational amplifier configuration.$$\text{Output}_{\text{stage 1}} \propto W_i X_i$$$W_i$ = Synaptic Weight (Controlled via Potentiometer)$X_i$ = Input Signal (Voltage)2. Summation and Bias StageThe weighted signals are algebraically added together along with an adjustable bias voltage ($b$) to shift the net input:$$\text{Net Input} = \sum W_i X_i + b$$3. Activation Function (Hard Limiter)An op-amp comparator acts as the threshold activation function (Step Function):$$\text{Output} = \begin{cases} \text{HIGH (LED ON),} & \text{if } V_{\text{in}} > V_{\text{threshold}} \\ \text{LOW (LED OFF),} & \text{if } V_{\text{in}} \le V_{\text{threshold}} \end{cases}$$🧩 Components & ToolsHardware RequirementsComponentQuantityDescriptionTL074 Quad Op-Amp1Main processing unit (Summing & Comparator)10kΩ Potentiometer3Weight, Bias, and Threshold tuning10kΩ Resistor4Feedback and input mixing100kΩ Resistor1High gain scaling1kΩ Resistor2LED current limitingLED2Status and output displayBreadboard & Wires1Prototyping platformDual Power Supply1$\pm$9V DC supply railsSoftware UsedProteus 8 Professional – Circuit simulation and schematic capture.📁 Repository StructurePlaintext📂 Analog-Artificial-Neuron-Model
│
├
📊 Results & Verification[x] Weighted Summation: Successfully verified with linear scaling.[x] Bias Adjustment: Positive and negative offset tracking confirmed.[x] Threshold Activation: Clean voltage comparator transitions.[x] Visual Output: LED switching responsive with zero bouncing.🌍 ApplicationsNeuromorphic Computing Hardware ResearchAnalog Signal Processing & Waveform ShapingAcademic Demonstrations in EEE & AI CoursesHardware-in-the-loop (HIL) Neural Simulations👨‍💻 AuthorFardin MeahDepartment of Electrical & Electronic Engineering (EEE)Let's connect! Feel free to reach out for collaborations.😉 "Bridging Artificial Intelligence with Analog Electronics."Give a ⭐ if this project inspired your hardware journey!
