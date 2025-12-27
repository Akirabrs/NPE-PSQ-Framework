<p align="center">
  <img src="assets/npe_psq_banner.png" width="80%" />
</p>

<h1 align="center">NPE-PSQ-Framework</h1>

<p align="center">
  <b>Non-Perturbative Energy – Plasma Stability & Quantum-Inspired Control Framework</b><br>
  Modular framework for plasma stability modeling, prediction and control.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-success.svg"/>
  <img src="https://img.shields.io/badge/domain-plasma%20physics-blue.svg"/>
  <img src="https://img.shields.io/badge/control-predictive%20%26%20adaptive-purple.svg"/>
  <img src="https://img.shields.io/badge/hardware-ready%20for%20FPGA-orange.svg"/>
  <img src="https://img.shields.io/badge/license-MIT-lightgrey.svg"/>
</p>

---

## 🔥 Overview

The **NPE-PSQ-Framework** is a modular scientific framework designed to:

- Model plasma behavior in tokamak-like systems  
- Detect non-Gaussian precursors of instability  
- Predict disruptive events before thermal quench  
- Provide control-oriented outputs compatible with **real-time FPGA safety systems**

It is designed to integrate seamlessly with:

- **AEGIS** (Interlock & Safety Layer)
- **TITAN** (Predictive Control Brain)
- **AION / KRONOS** (Low-latency hardware execution)

---

## 🎥 Simulation Preview

<p align="center">
  <img src="assets/cmod_titan_simulation.gif" width="90%" />
</p>

<p align="center">
  <i>Forensic replay of Alcator C-Mod disruption with adaptive threshold detection.</i>
</p>

---

## 🧠 Core Concepts

✔ Non-Gaussian energy detection (kurtosis, RMS, adaptive limits)  
✔ Precursor identification (locked modes, phase coupling)  
✔ Predictive safety logic (pre-disruption shutdown)  
✔ Hardware-aware architecture (FPGA-friendly logic paths)

---

## 🧱 Architecture

<p align="center">
  <img src="assets/architecture_diagram.png" width="85%" />
</p>

```text
Sensors → Signal Intelligence → Statistical Core
        → Prediction Engine → Control Decision
        → Safety Interlock / FPGA / Actuators
