# ⚡ Astable Multivibrator (2 kHz, 60% Duty Cycle)

## 📌 Overview
This project demonstrates the design, simulation, and PCB implementation of an **Astable Multivibrator** using BJTs. The circuit generates a continuous square wave without an external trigger. The target specifications were **frequency = 2 kHz** and **duty cycle = 60%**, verified through **Multisim simulation** and **Proteus PCB testing**.

---

## 🎯 Objectives
- Design a transistor-based astable multivibrator.
- Apply **RC time constant network analysis** to calculate TON, TOFF, and duty cycle.
- Simulate the circuit in **Multisim** and analyze waveforms.
- Build and verify the design using **Proteus PCB**.
- Compare theoretical, simulated, and hardware results.

---

## 🛠 Tools & Technologies
- **Simulation**: NI Multisim  
- **PCB Design & Verification**: Proteus  
- **Skills**:  
  - Analog circuit design  
  - RC timing and duty cycle analysis  
  - Multisim simulation and waveform analysis  
  - PCB design workflow  
  - Hardware validation and documentation  

---

## 📐 Design & Analysis
### Key Equations
- TON ≈ 0.693 × (R1 + R2) × C  
- TOFF ≈ 0.693 × R2 × C  
- Duty Cycle (%) = TON / (TON + TOFF) × 100  

### Verification Results
| Parameter | Theoretical | Simulation (Multisim) | PCB (Proteus) |
|-----------|-------------|------------------------|---------------|
| TON       | 0.300 ms    | 0.306 ms              | 0.260 ms      |
| TOFF      | 0.200 ms    | 0.209 ms              | 0.245 ms      |

---

## 📊 Applications
- Square wave generator for digital circuits  
- Clock source for sequential logic  
- LED flasher and tone generator  
- Timing oscillator in embedded systems  

---

## ✅ Conclusion
This project highlights the **complete analog design flow**: problem definition → theoretical analysis → simulation → PCB verification. It reflects strong skills in **analog circuits, network analysis, and EDA tools**—essential for careers in **Electronics, Embedded Systems, and VLSI**.

