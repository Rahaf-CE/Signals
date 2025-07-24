# 📈 Signal Periodicity Analysis in MATLAB

This repository contains a MATLAB-based analysis for verifying the **periodicity of discrete-time signals** in the context of **EE2312 - Signal and System** course.


## 🔍 First Signal Description

- **Type:** Discrete-Time Signal
- **Status:** Periodic
- **Tool:** MATLAB
- **Analysis:**
  - Plotted using `stem()` or `plot()`
  - Verified visually and mathematically
  - Fundamental period \( N = ... \)

---

## 🔧 MATLAB Instructions

### Example code snippet:

```matlab
n = 0:20;
x = cos(0.4 * pi * n);  % Example signal
stem(n, x);
title('First Signal');
xlabel('n'); ylabel('x[n]');
grid on;

 🧠 Learning Outcomes
How to detect periodicity in discrete-time signals

Understanding of fundamental period

MATLAB plotting and signal manipulation skills




# 🧪 ENEE2304 – Circuit Analysis PSpice Assignment

This repository contains simulations and analyses for **Circuit Analysis (ENEE2304)** using **PSpice**, focusing on:

- Superposition Theorem
- Thevenin Equivalent Circuits
- Load Power Optimization
- RC Circuit Transient Response


## 🧠 Assignment Topics

### 1. ✅ Superposition Theorem
- Analyze circuit twice, once for each source.
- Combine \( V_{o1} + V_{o2} \) and \( I_{o1} + I_{o2} \).
- Verified total \( V = 15.50 \text{V}, I = 7.044 \text{mA} \).

### 2. 🔌 Thevenin Equivalent & Maximum Power Transfer
- Found \( V_{TH} = 8.742 \text{V} \), \( R_{TH} ≈ 990 \Omega \).
- Max power = **19.348 mW** at \( R_L = 1000 \Omega \).
- Verified: \( R_L = R_{TH} \) at max power.

### 3. ⏱️ RC Time Constant Verification
- \( R = 10k \Omega, C = 0.1 \mu F \Rightarrow \tau = 1 \text{ms} \)
- From the graph:
  - \( V_{max} = 10V \)
  - \( V = 6.3V \) reached at \( t = 0.994 \text{ms} \)
  - Confirms \( \tau \approx 1 \text{ms} \)

---

## 📊 Results Summary

| Parameter                | Value         |
|-------------------------|---------------|
| Voltage across R3       | 15.50 V       |
| Current through R3      | 7.044 mA      |
| Max Power to RL         | 19.348 mW     |
| RL at Max Power         | 1 kΩ          |
| VTH                     | 8.742 V       |
| RTH                     | 990 Ω         |
| Time Constant (RC)      | 1 ms          |
| Verified τ from plot    | 0.994 ms      |

