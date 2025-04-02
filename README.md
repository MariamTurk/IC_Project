# 16-Bit CMOS Comparator Design

This repository presents the design, layout, simulation, and performance analysis of a 16-bit comparator built using CMOS technology. The project includes the development of 1-bit, 4-bit, and 16-bit comparators using PMOS and NMOS transistors along with basic logic gates like AND, OR, NAND, NOR, and NOT. The design was implemented and verified using the Electric VLSI tool and LTspice for simulation.

## 🧠 Authors
- Mariam Turk   
- Noura Manassra  

Department of Electrical and Computer Engineering, Faculty of Engineering and Technology  
Birzeit University, August 18, 2024

---

## 🧾 Abstract

This project implements a 16-bit digital comparator using CMOS (Complementary Metal-Oxide-Semiconductor) technology. The design process starts from a 1-bit comparator, builds up to a 4-bit version, and scales to a 16-bit comparator. Logic gates and transistor-level schematics are developed using Electric Binary 9.07, and their functionality is validated through LTspice simulations. This comparator outputs whether input A is greater than, less than, or equal to input B.

---

## 🔧 Technologies & Tools

- **CMOS Technology**: PMOS and NMOS transistors  
- **Logic Design**: AND, OR, NOT, NAND, NOR gates  
- **Design Tool**: [Electric VLSI Design System (v9.07)](http://www.staticfreesoft.com/productsFree.html)  
- **Simulation Tool**: [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html)

---

## 📐 Modules and Components

| Component | Description |
|----------|-------------|
| NOT Gate | Basic inverter using PMOS and NMOS |
| NAND Gate | Two-input NAND gate |
| NOR Gate | Two-input NOR gate |
| 4-bit AND/OR Gates | Built using multiple NAND/NOR configurations |
| 1-bit Comparator | AB', A'B, and equality logic |
| 4-bit Comparator | Cascaded 1-bit comparators + logic |
| 16-bit Comparator | Built from 4-bit comparators and logic |

---

## 🧪 Simulations

Each component was tested and simulated using LTspice. The following waveforms were analyzed:
- **Inverter Output**
- **Gate Delays**
- **Power Consumption**
- **Full 16-bit Comparator Timing and Logic Validation**

---

## 📊 Performance Analysis

| Metric     | Value                     |
|------------|---------------------------|
| Area       | 314,579.8425 µm²          |
| Delay      | 1.333 ns                  |
| Power      | ~10.043 nW (avg power)    |

---


## 🛠️ Challenges

- Complex layout connections and parasitic effects
- Mastering LTspice configuration for accuracy
- Managing wire spacing and signal integrity in large-scale layouts
