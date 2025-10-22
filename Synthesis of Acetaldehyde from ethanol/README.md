# ⚗️ Synthesis of Acetaldehyde from Ethanol — Aspen Plus Simulation

## 🧪 Overview
This project models the **production of acetaldehyde (CH₃CHO)** from **ethanol (C₂H₅OH)** through **vapor-phase dehydrogenation** using Aspen Plus. The process integrates **pumping, heating, reaction, cooling, flashing, membrane separation, and distillation** into a complete process simulation.

---

## ⚙️ Key Process Steps
1. **Feed Pressurization & Heating:**  
   Ethanol feed (400 kmol/h) is pumped to 8 bar and heated to 275 °C using a shell-and-tube exchanger (steam at 9 bar).

2. **Reaction:**  
   In an **isothermal PFR** (7 m × 11.5 cm) operating at 275 °C and 8 bar, ethanol converts to acetaldehyde and hydrogen.

3. **Cooling & Flashing:**  
   Reactor effluent is cooled to 25 °C, flashed to separate vapor and liquid streams.

4. **Membrane Separation:**  
   Hydrogen is removed from the liquid phase; vapor streams are combined and vented.

5. **Distillation:**  
   The purified liquid is separated in a **22-stage RadFrac column** (feed stage = 11, reflux ratio = 1.8, condenser = 6.5 bar).  
   90% of the column bottoms are recycled to the reactor.

---

## 🧰 Simulation Details
- **Software:** Aspen Plus  
- **Property Method:** PSRK  
- **Units Used:** Pump, Heater (Exchanger), PFR, Cooler, Flash, Separator, and RadFrac Column  
- **Recycle Integration:** 90% bottoms recycled, 10% purged  

---

## 📊 Expected Outcomes
- Acetaldehyde formation via ethanol dehydrogenation  
- Effective hydrogen removal through membrane separation  
- Purified acetaldehyde recovery in distillation column  
- Design and sizing of shell-and-tube exchanger for steam service  

---

## 🏷️ Keywords
`Aspen Plus` • `Acetaldehyde` • `Ethanol Dehydrogenation` • `PFR` • `RadFrac` • `Membrane Separation` • `Process Simulation`
