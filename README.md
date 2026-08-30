# Aerospace Propulsion: Turbojet & Turbofan Performance Analysis

This repository contains numerical and experimental performance analyses for two major aerospace propulsion systems: a **micro-turbojet engine (AMT Olympus HP)** and a **high-bypass civil turbofan engine**, combining experimental test rig data post-processing with numerical simulations in **PROOSIS** and **MATLAB**.

---

## 1. Turbojet Test & Performance Analysis

Experimental testing and numerical modeling of the **AMT Olympus HP micro-turbojet engine** across varying rotational speeds ($36k - 108k \text{ RPM}$).

### Highlights
* **Calibration & Post-Processing**: Processing raw static pressure, total pressure, temperature, thrust, and fuel flow data.
* **Component Efficiency Evaluation**: Calculating compressor ($\eta_c$), turbine ($\eta_t$), and thermal ($\eta_{th}$) efficiencies across steady-state operational points (including low-RPM compressor stall phenomena).
* **PROOSIS Validation**: Modeling static ground-test conditions ($M_0 = 0$, ambient pressure/temperature at Madrid altitude) to validate experimental thrust against numerical predictions.

---

## 2. High-Bypass Turbofan Design & Off-Design Performance

Thermodynamic and aerodynamic modeling of a **civil high-bypass turbofan engine** comparing design cruise conditions to off-design operation (take-off, service ceiling, and low-speed flight).

### Highlights
* **On-Design Sizing & Nozzle Velocity Matching**: Sizing nozzle exit areas ($A_9$, $A_{19}$) under maximum cruise thrust and evaluating velocity matching ($v_9 = v_{19}$) effects on propulsive efficiency.
* **Parametric Sweep Studies**: Investigating performance trade-offs between fan pressure ratio ($\pi_f$), bypass ratio ($\text{BPR}$), specific thrust ($\text{sFn}$), and thrust specific fuel consumption ($\text{TSFC}$).
* **Off-Design Operating Envelopes**: Simulating take-off performance, ambient temperature sensitivity ($\Delta T$), and high-altitude service ceiling penalties.


---

## Tools & Technologies
* **PROOSIS**: Gas turbine performance simulation, component maps, and off-design partition solving.
* **MATLAB**: Experimental data post-processing, parameter estimation, and performance plotting.


*Universidad Carlos III de Madrid (UC3M) – Aerospace Propulsion*[cite: 3, 4]
