# Module 04: Engineering Calculations & Mathematical Framework

## 1. Executive Summary & Parameter Summary
This module provides the complete numerical and mathematical framework governing the 58-unit campus water heating fleet (V-Guard & Venus 25 L units). 

| Parameter | Symbol | Value | Unit |
| :--- | :--- | :--- | :--- |
| Tank Storage Volume | V | 25.0 | L (kg) |
| Heating Element Rating | P | 2.0 | kW |
| Specific Heat Capacity | c<sub>p</sub> | 4.184 | kJ/(kg·K) |
| Inlet Temperature Baseline | T<sub>in</sub> | 37.0 | °C |
| Target Outlet Temperature | T<sub>out</sub> | 45.0 | °C |
| Max Thermostat Temperature | T<sub>max</sub> | 65.0 | °C |
| BEE Certified Standing Loss | Q<sub>loss</sub> | 0.511 | kWh/24hr |

---

## 2. Sensible Heat Requirements
Calculated using the First Law relation: **Q = m × c<sub>p</sub> × ΔT**

### A. Standard Operational Batch (37 °C to 45 °C)
* **Temperature Difference (ΔT):** 45 °C - 37 °C = 8 °C (8 K)
* **Thermal Energy Required (Q):** 25 kg × 4.184 kJ/(kg·K) × 8 K = **836.8 kJ**
* **Electrical Equivalent:** 836.8 kJ / 3600 kJ/kWh = **0.232 kWh**

### B. Full Cold-Fill Reheat (25 °C to 65 °C)
* **Temperature Difference (ΔT):** 65 °C - 25 °C = 40 °C (40 K)
* **Thermal Energy Required (Q):** 25 kg × 4.184 kJ/(kg·K) × 40 K = **4,184.0 kJ**
* **Electrical Equivalent:** 4,184.0 kJ / 3600 kJ/kWh = **1.162 kWh**

---

## 3. Energy Consumption & Fleet Scale
Calculations for single unit vs. total 58-unit campus fleet:

### Single Unit Consumption
* **Active Heating Cycles / Day:** 3 cycles (75 L total draw/day)
* **Useful Heating Energy:** 3 × 0.232 kWh = **0.696 kWh/day**
* **Standby Loss Addition:** 0.511 kWh/day
* **Total Daily Energy / Unit:** 0.696 + 0.511 = **1.207 kWh/day**

### Total Fleet Scale (58 Units across 7 Hostels)
* **Daily Fleet Consumption:** 58 units × 1.207 kWh/day = **70.01 kWh/day**
* **Annual Fleet Consumption:** 70.01 kWh/day × 365 days = **25,553.65 kWh/year**
* **Annual Standby Waste:** 58 units × 0.511 kWh/day × 365 days = **10,817.87 kWh/year**

---

## 4. System Efficiency & Thermal Losses

### Active Heating Cycle Efficiency
* **Theoretical Heating Duration (Zero Loss):** t<sub>ideal</sub> = 1.162 kWh / 2.0 kW = **34.8 minutes**
* **Field Reheat Duration:** t<sub>actual</sub> = **44.0 minutes**
* **Thermal Conversion Efficiency (η):** (34.8 min / 44.0 min) × 100 = **79.1%**

### Dissipation Rates
* **Active Surface Radiation Rate:** P<sub>loss</sub> = 2.0 kW × (1 - 0.791) = **0.418 kW (418 W)**
* **Idle Continuous Loss Rate:** 0.511 kWh / 24 hr = **0.0213 kW (21.3 W)**

---

## 5. Water Flow & Hydraulic Analysis

### Discharge Flow Rates
* **Nominal Gravity Outlet Discharge:** 4.2 L/min
* **Full Batch Discharge Duration:** 25 L / 4.2 L/min = **5.95 minutes**
* **Mass Flow Rate (m_dot):** 4.2 kg/min = **0.070 kg/s**

### Cold Water Purge Lag
* **Piping Dead-Leg Volume:** 1.2 L (inlet drop pipe)
* **Thermal Delay Duration:** 1.2 L / 4.2 L/min = **0.286 minutes (17 seconds)**
