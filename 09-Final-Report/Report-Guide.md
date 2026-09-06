# Comprehensive Thermodynamic Analysis & Technical Report

## 1. Executive Summary
This report analyzes the thermodynamic performance, electrical utilization, and standby energy loss of decentralized 25 L electric storage water heaters deployed across campus hostel blocks. Based on field-verified nameplate specs, BEE star-label data, and physical inspections, this study evaluates sensible heat conversion efficiency and thermal jacket retention.

---

## 2. Verified Field Specifications & System Parameters
Data collected directly from equipment nameplates (V-Guard Steamer Plus ECS 25 and Venus Magma Plus 25GV) establishes the baseline operating constants:

* **Storage Capacity ($V$):** $25\text{ Liters}$ ($25\text{ kg}$ water equivalent).
* **Heating Element Power ($P$):** $2000\text{ W}$ ($2.0\text{ kW}$).
* **Operating Supply:** $230\text{ V AC}, 50\text{ Hz}$ single-phase.
* **Tested Reheating Time ($t_{reheat}$):** $44\text{ minutes}$ ($0.733\text{ hours}$) to achieve mean hot water temperature.
* **Verified Standing Loss ($Q_{loss}$):** $0.511\text{ kWh per 24 hours}$ (BEE Certified under IS standards).
* **Max Working Pressure:** $0.8\text{ MPa}$ ($8\text{ bar} / 8\text{ Kg/cm}^2$).

---

## 3. Thermodynamic Formulations & Calculations

### Theoretical Sensible Heat Requirement
The sensible heat $Q$ required to elevate $25\text{ L}$ of water from ambient temperature ($37\ ^\circ\text{C}$) to standard output delivery ($45\ ^\circ\text{C}$) is given by:

$$Q = m \cdot c_p \cdot \Delta T$$

Where:
* $m = 25\text{ kg}$
* $c_p = 4.184\text{ kJ/(kg}\cdot\text{K)}$
* $\Delta T = 45\ ^\circ\text{C} - 37\ ^\circ\text{C} = 8\ ^\circ\text{C}$

$$Q = 25\text{ kg} \times 4.184\text{ kJ/(kg}\cdot\text{K)} \times 8\text{ K} = 836.8\text{ kJ}$$

### Electrical Energy Conversion
Converting thermal energy to kilowatt-hours ($\text{kWh}$):

$$E_{\text{thermal}} = \frac{836.8\text{ kJ}}{3600\text{ kJ/kWh}} \approx 0.232\text{ kWh}$$

### Full Temperature Cycle Energy (Ambient $25\ ^\circ\text{C} \rightarrow 65\ ^\circ\text{C}$)
For a full reheating cycle from $25\ ^\circ\text{C}$ to maximum cut-off ($65\ ^\circ\text{C}$, $\Delta T = 40\ ^\circ\text{C}$):

$$Q_{\text{full}} = 25 \times 4.184 \times 40 = 4184\text{ kJ} \approx 1.162\text{ kWh}$$

At $P = 2.0\text{ kW}$, theoretical heating time is:

$$t = \frac{1.162\text{ kWh}}{2.0\text{ kW}} = 0.581\text{ hours} \approx 34.8\text{ minutes}$$

Accounting for jacket loss during warmup brings actual measured reheating time to the specified $44\text{ minutes}$ ($\eta_{thermal} \approx 79.1\%$).

---

## 4. Standing Heat Loss Analysis
The verified standing loss rate is $0.511\text{ kWh/24hr}$ ($21.29\text{ W}$ continuous heat dissipation).

* **Daily Standby Energy Waste:** If left powered 24/7 without draw, each unit consumes $0.511\text{ kWh}$ purely maintaining internal tank temperature.
* **Campus Scale Loss (70 Units Total):**
  $$E_{\text{waste, daily}} = 70 \times 0.511 = 35.77\text{ kWh/day}$$
  $$E_{\text{waste, annual}} = 35.77 \times 365 = 13,056\text{ kWh/year}$$

---

## 5. Engineering Recommendations
1. **Automated Timer Relays:** Install programmable digital timer switches to isolate unit power between 11:00 PM and 5:00 AM, saving up to $25\%$ of annual standby losses.
2. **CPVC Line Thermal Lagging:** Insulate exposed Ashirvad CPVC distribution lines to lower immediate cold-water purge volume.
3. **Thermostat Setpoint Optimization:** Adjust internal thermostat settings from $65\ ^\circ\text{C}$ down to $50\ ^\circ\text{C}$ during off-peak seasons to reduce skin dissipation losses proportionally.
