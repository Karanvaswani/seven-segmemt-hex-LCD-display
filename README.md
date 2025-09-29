# 7-Segment Hexadecimal Display (VHDL)

## 📖 Introduction
This project implements a **7-segment hexadecimal display driver** using VHDL. It takes a 4-bit binary input and displays its corresponding hexadecimal digit (0–9, A–F) on a 7-segment module.  

## 🎯 Objective
- Learn how to decode binary values into 7-segment display outputs.  
- Apply Boolean expressions and truth tables in VHDL.  
- Simulate and test the design on FPGA or software tools.  

## 🛠️ Skills Covered
- VHDL coding and logic design  
- Boolean expression implementation  
- Segment mapping for hexadecimal digits  
- Functional simulation and verification  
- FPGA integration and modular design  

## 📂 Files Included
- `7segment.v` → VHDL source code for display driver  
- `testbench.vhd` → Testbench for simulation  
- `README.md` → Documentation  

## 📝 Assignment Tasks
1. Implement 7-segment logic in VHDL.  
2. Simulate outputs for all hexadecimal inputs (0–15).  
3. Document segment mapping (0–9, A–F).  
4. Extend design for multiple digits or counters (optional).  

## ✅ Outcome
The project provides hands-on experience in **digital design, Boolean logic, and FPGA programming**. It is reusable as a module in larger FPGA projects such as calculators, timers, and display systems.  

## 🚀 How to Run
1. Load `7segment.v` in your VHDL/FPGA environment (e.g., ModelSim, Vivado, Quartus).  
2. Run the provided `testbench.vhd`.  
3. Verify output patterns for all 16 input values.  
