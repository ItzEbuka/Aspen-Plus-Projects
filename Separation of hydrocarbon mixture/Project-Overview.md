# **Hydrocarbon Separation — Aspen Plus Simulation**

## 🧪 Project Overview
This project focuses on the **separation of a multicomponent hydrocarbon mixture** using **Aspen Plus**.  
The feed mixture, composed of light and heavy hydrocarbons, undergoes a sequence of separation processes — including **flash separation**, **cooling and throttling**, **membrane gas separation**, and **column-based component isolation** — to achieve efficient recovery of key components such as hydrogen, methane, ethane, and propane.

---

## ⚙️ Process Description
A hydrocarbon feed stream containing **H₂, CH₄, C₂H₆, C₃H₈, C₆H₁₄, C₇H₁₆, and C₈H₁₈** enters the system at **30°C**, **3 bar**, and **120 kmol/h**.  
The overall process is outlined below:

1. **Adiabatic Flash Separator**  
   The feed undergoes an adiabatic flash with no pressure drop, producing vapor and liquid streams.

2. **Liquid Stream Path**  
   - The liquid outlet is cooled to **12°C** using a cooler (no pressure drop).  
   - The cooled liquid is throttled to **1 atm** using a valve.  
   - The outlet stream is split in an **80:20 ratio** to supply two different plant streams.

3. **Vapor Stream Path**  
   - The vapor phase is directed to a **membrane separator** that divides it into:  
     - A **hydrogen-rich stream**  
     - A **methane-rich stream** (97% methane recovery)  
     - A residual **ethane–propane mixture**  
   - The ethane–propane mixture is further processed in a **separation column** to isolate both components.

---

## 🧰 Simulation Setup
- **Software:** Aspen Plus  
- **Property Method:** Peng–Robinson (PR)  
- **Key Equipment:** Flash Separator, Cooler, Valve, Splitter, Membrane Separator, and Distillation Column  
- **Operating Basis:** Adiabatic flash, no pressure drop assumptions, 99% component closure  

---

## 📊 Expected Results
- **Liquid outlet:** Cooled, throttled, and distributed in two plant feed ratios.  
- **Vapor outlet:**  
  - High-purity H₂ and CH₄ product streams  
  - Ethane–propane separated to high purity via distillation  
- Demonstrates efficient **phase separation and component recovery** for mixed hydrocarbon systems.

---

## 🏷️ Keywords
`Aspen Plus` • `Hydrocarbon Separation` • `Flash Process` • `Membrane` • `Distillation` • `Chemical Engineering` • `Process Simulation`
