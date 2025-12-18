# Thermal Desalination Process Simulation (DWSIM)

This repository contains a steady-state process simulation of a single-stage thermal desalination unit developed using **DWSIM**.

The project demonstrates the application of equilibrium flash separation and condensation for fresh water production from saline feed, with complete material and energy balance closure.

---

## Objective
To model a conceptual thermal desalination process and evaluate:
- Water recovery
- Salt rejection
- Thermal energy requirements

---

## Process Description
The simulated process consists of the following unit operations:

1. **Feed Preheater (E-101)**  
   Saline feed water is heated to provide sufficient thermal energy for flashing.

2. **Flash Separator (V-101)**  
   The heated stream undergoes equilibrium flash separation, producing:
   - A vapor phase enriched in water
   - A liquid brine stream containing dissolved salts

3. **Condenser (E-102)**  
   The flashed vapor is condensed to obtain fresh water (distillate).

A complete **Process Flow Diagram (PFD)** was developed, and steady-state material and energy balances were successfully closed.

---

## Key Results
- **Salt rejection:** ~99.98%  
- **Water recovery:** ~80% (under high thermal input conditions)  
- **Heater duty (E-101):** ~1208 kW  
- **Condenser duty (E-102):** ~1192 kW  

The results highlight the trade-off between water recovery and thermal energy input in single-stage thermal desalination systems.

---

## Tools and Methods
- **Simulation Software:** DWSIM  
- **Property Package:** NRTL / Electrolyte NRTL  
- **Approach:** Steady-state equilibrium flash separation  

---

## Notes
This model represents a **conceptual single-stage desalination process** intended for learning and analysis.  
Industrial desalination plants typically employ **multi-stage flash (MSF)** or **multi-effect distillation (MED)** systems to improve overall efficiency and reduce energy consumption.

---

## Author
Utkarsh Yadav  
Chemical Engineering, NIT Surat
