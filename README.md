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
