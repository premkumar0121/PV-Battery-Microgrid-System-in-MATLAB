# PV-Battery Microgrid System with Bidirectional DC-DC Converter

**SKU:** 0104  
**Keywords:** Photovoltaic (PV) Systems, Bidirectional DC-DC Converter, Incremental Conductance MPPT, Battery Energy Storage System (BESS), MATLAB/Simulink.

---

## 📖 Abstract
The stochastic nature of solar irradiance presents significant challenges for the stability and reliability of modern microgrids. This project evaluates the design and performance of a 1000 W Photovoltaic (PV) system integrated with a 48 V Battery Energy Storage System (BESS) through a multi-stage power conversion architecture. 

Central to this system is a bidirectional DC-DC converter, which manages the power flow between the storage medium and a 220 V regulated DC bus. To maximize energy extraction, an Incremental Conductance (INC) Maximum Power Point Tracking (MPPT) algorithm is implemented. System performance was validated via MATLAB/Simulink across diverse irradiance profiles.

---

## ⚙️ System Specifications

| Component | Specification |
| :--- | :--- |
| **PV Array** | 1000 W total, 4 units of 250 W |
| **PV Parameters** | V_mp ≈ 30.7 V, nominal output ≈ 120 V |
| **Storage Medium** | 48 V battery, chemistry-independent |
| **DC Bus Reference** | 220 V DC, regulated |
| **PV Converter** | DC-DC boost converter |
| **Energy Interface** | Bidirectional DC-DC converter, buck/boost |
| **Output Stage** | H-bridge inverter for AC load |

---

## 📊 Operational Modes
The management logic categorizes system behavior into distinct primary modes to ensure the DC bus remains strictly at the 220 V reference:
* **Mode 1 (Surplus):** PV supplies Load & Battery (Charging).
* **Mode 2 (Deficit):** PV & Battery supply Load (Discharging).
* **Mode 3 (Night):** Battery exclusively supplies Load.
* **Mode 4 (Collapse):** DC Bus Voltage drops to 0V (Critical Shutdown).

---

## 🎥 Video Demonstration
To see the MATLAB/Simulink simulation in action under various irradiance scenarios, check out the video demonstration:  
📺 **[Watch the Simulation on YouTube](https://www.youtube.com/watch?v=lWogfJUjw_k)**
[![Watch the simulation on YouTube](https://img.youtube.com/vi/lWogfJUjw_k/maxresdefault.jpg)](https://www.youtube.com/watch?v=lWogfJUjw_k)
---

## 💻 Get the MATLAB/Simulink Model
The complete Simulink `.slx` model and associated project files are available for download.

🛒 **[Purchase and Download the Model Here (SKU: 0104)](https://www.lmssolution.net.in/product-page/pv-system-with-battery-storage-using-bidirectional-dc-dc-converter)**

> **Note:** For full mathematical modeling, control logic, and detailed transient response graphs, please view the [Full Technical Whitepaper (PDF) included in this repository.](#) *(Note to author: Link this to your uploaded PDF once it is in the repository!)*
