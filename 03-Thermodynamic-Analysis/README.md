# Module 03: Comprehensive Thermodynamic Analysis

## 1. Executive Overview & System Constants
This module provides the core First Law formulations, Steady-Flow Energy Balance (SFEE), and heat transfer calculations governing the 25 L storage water heaters across campus hostel blocks.

### Baseline Parameters
* **Storage Volume (V):** 25 Liters (Mass m = 25.0 kg)
* **Heating Element Power (P):** 2.0 kW (2000 W)
* **Specific Heat Capacity of Water (c_p):** 4.184 kJ/(kg·K)
* **Inlet Baseline Temperature (T_in):** 37.0 °C
* **Target Outlet Temperature (T_out):** 45.0 °C
* **Maximum Thermostat Cutoff (T_max):** 65.0 °C
* **Verified Standing Loss (Q_loss):** 0.511 kWh/24hr

---

## 2. First Law of Thermodynamics Analysis
For a stationary closed system during a batch heating process:

**Q_sensible = m × c_p × (T_out - T_in)**

### A. Operational Batch Calculation (37 °C → 45 °C)
* **Q_sensible = 25 kg × 4.184 kJ/(kg·K) × (45 °C - 37 °C)**
* **Q_sensible = 836.8 kJ**
* **Electrical Equivalent = 836.8 / 3600 ≈ 0.232 kWh**

### B. Full Reheating Cycle (25 °C → 65 °C)
* **Q_full = 25 kg × 4.184 kJ/(kg·K) × (65 °C - 25 °C) = 4,184 kJ (1.162 kWh)**
* **Ideal Reheat Time (Zero Loss):** t_ideal = 1.162 kWh / 2.0 kW = 34.8 minutes
* **Field Measured Reheat Time:** t_actual = 44.0 minutes
* **Active Thermal Efficiency:** η_thermal = (34.8 / 44.0) × 100 = **79.1%**

---

## 3. Steady-Flow Energy Equation (SFEE)
For continuous draw conditions across the control volume boundary:

**Q_dot - W_dot_shaft = m_dot × [ (h_out - h_in) + (V_out² - V_in²)/2 + g(z_out - z_in) ]**

Assumptions for stationary local electric geyser:
* Shaft work (W_dot_shaft) = 0
* Potential and kinetic energy changes (ΔPE, ΔKE) ≈ 0
* Enthalpy differential: Δh = c_p × (T_out - T_in)

Simplified Steady Rate Equation:
**P_electrical - Q_dot_loss = m_dot × c_p × (T_out - T_in)**

---

## 4. Heat Transfer & Dissipation Dynamics
During active heating, energy input is divided into useful thermal accumulation and ambient dissipation:

* **Electrical Input Power (P_in):** 2.000 kW
* **Useful Water Storage Rate (Q_dot_stored):** 1.585 kW
* **Active Dissipation Rate (Q_dot_loss):** 0.415 kW (415 W)
* **Standing Idle Loss (BEE Verified):** 0.511 kWh/24hr (21.29 W continuous)

---

## 5. Summary Findings
The system operates at a net active thermal conversion efficiency of **79.1%** during full reheat cycles. System losses are dominated by skin radiation during heating (415 W rate) and continuous standing loss (21.29 W continuous) when energized without water draw.
