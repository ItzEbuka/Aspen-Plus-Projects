# ⚗️ BTX Separation through Distillation — Aspen Plus Simulation

## 🧪 Overview
This project models the **distillation-based separation of BTX components** — benzene, toluene, and p-xylene — using **Aspen Plus**.  
The objective is to separate a mixed hydrocarbon feed into high-purity benzene (≥95%) and toluene (≥97%), while recovering p-xylene as the bottom product.

---

## ⚙️ Feed and Process Conditions
- **Feed Composition:**  
  - Benzene: 400 kg/h  
  - Toluene: 600 kg/h  
  - p-Xylene: 100 kg/h  
- **Feed Temperature:** 30 °C  
- **Feed Pressure:** 1.3 bar  
- **Product Pressures:**  
  - Benzene: 6 bar  
  - Toluene: 3 bar  
  - p-Xylene: 4 bar  

---

## 🔍 Simulation Strategy
1. **Property Verification:**  
   Validate component boiling points using the **Pure Component** and **PT Envelope** property methods.

2. **Equilibrium Analysis:**  
   Use a **Flash** block to determine **K-values** and **relative volatilities** for the light and heavy key components.

3. **Preliminary Design:**  
   Employ the **DSTWU** shortcut distillation model to estimate the **minimum reflux ratio** and **minimum number of stages**, then optimize **reflux ratio vs. stages**.

4. **Detailed Simulation:**  
   Implement a **DISTL (RadFrac)** block to simulate real column performance under actual operating conditions.

5. **Verification:**  
   Confirm the purity and phase condition of all product streams after the complete simulation.

---

## 🧰 Simulation Details
- **Software:** Aspen Plus  
- **Property Method:** Peng–Robinson (PR) or NRTL (depending on vapor–liquid system validation)  
- **Main Equipment:** Flash, DSTWU, and DISTL (RadFrac)  
- **Key Outputs:** Product purities, reflux ratio, number of stages, and product stream pressures  

---

## 📊 Expected Results
- Benzene recovered at ≥95% purity  
- Toluene recovered at ≥97% purity  
- p-Xylene collected as bottom product  
- Optimized column design with efficient reflux ratio and stage configuration  

---

## 🏷️ Keywords
`Aspen Plus` • `Distillation` • `BTX Separation` • `Benzene` • `Toluene` • `p-Xylene` • `DSTWU` • `RadFrac` • `Chemical Engineering`
