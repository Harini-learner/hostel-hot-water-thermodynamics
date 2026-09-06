# Thermodynamic Analysis of Electric Storage Water Heaters in Seven Girls' Hostels

## Project Overview

This repository presents a field-based thermodynamic study of the distributed electric storage water-heater system serving **seven girls' hostels**. The survey identified **58 heaters** distributed across the seven hostels and two heater brands: **V-Guard** and **Venus**.

The project combines thermodynamic theory, field observations, calculations, hostel-wise scaling, engineering recommendations, graphs, and an interactive simulator.

> **Data discipline:** Values marked **FIELD OBSERVATION** or **NAMEPLATE / DOCUMENT** come from the collected hostel evidence. Values marked **REFERENCE / CALCULATED** are calculated from those observations. No exact final temperature, flow rate, or actual electricity meter reading was invented.

## Real Field Dataset Used

| Parameter | Value | Basis |
|---|---:|---|
| Girls' hostels surveyed | 7 | FIELD OBSERVATION |
| Total heaters | 58 | FIELD OBSERVATION |
| Hostel 1 | 8 heaters | FIELD OBSERVATION |
| Hostel 2 | 8 heaters | FIELD OBSERVATION |
| Hostel 3 | 8 heaters | FIELD OBSERVATION |
| Hostel 4 | 8 heaters | FIELD OBSERVATION |
| Hostel 5 | 16 heaters | FIELD OBSERVATION |
| Hostel 6 | 4 heaters | FIELD OBSERVATION |
| Hostel 7 | 6 heaters | FIELD OBSERVATION |
| Heater brands | V-Guard, Venus | FIELD OBSERVATION |
| Representative storage capacity | 25 L | NAMEPLATE / DOCUMENT |
| Representative rated power | 2 kW | NAMEPLATE / DOCUMENT |
| Representative rated voltage | 230 V | NAMEPLATE / DOCUMENT |
| Frequency | 50 Hz | NAMEPLATE / DOCUMENT |
| Normal/inlet water temperature | ~37 °C | FIELD MEASUREMENT |
| Heated outlet water | >45 °C | FIELD MEASUREMENT |
| Long non-use hot-water availability observation | ~5 min | FIELD OBSERVATION |
| Frequent-use hot-water availability observation | ~1 min | FIELD OBSERVATION |
| Specific heat of water | 4.18 kJ/kg·K | REFERENCE PROPERTY |

## Important Interpretation

The observed **1 minute** and **5 minute** values describe hot-water availability/recovery as observed in use. They are **not automatically equal to heater ON-time**. Therefore, they must not be used as measured electrical consumption without an electrical energy measurement.

The observed hot-water temperature is **greater than 45 °C**, so 45 °C is used only as a conservative minimum/reference temperature in the heat calculation.

## Key Reference Calculation

For a 25 L storage volume, using water density ≈ 1 kg/L:

- Mass, `m ≈ 25 kg`
- Initial temperature, `T1 ≈ 37 °C`
- Reference final temperature, `T2 = 45 °C minimum`
- Temperature rise, `ΔT = 8 K`
- Specific heat, `cp = 4.18 kJ/kg·K`

`Q = m cp ΔT = 25 × 4.18 × 8 = 836 kJ ≈ 0.232 kWh`

This is the **reference sensible heat required for 25 kg of water to rise from 37 °C to 45 °C**. It is not the measured electrical consumption of a heater.

If a 2 kW heater operates continuously for a known duration `t`, electrical input is:

`E = P t`

For reference only:
- 1 minute at 2 kW = 0.0333 kWh
- 5 minutes at 2 kW = 0.1667 kWh

These are theoretical full-power values, not measured hostel consumption.

## Maximum Connected Load (Conditional)

If all 58 heaters were 2 kW units:

`P_total = 58 × 2 = 116 kW`

This is a **conditional maximum connected load**, not actual simultaneous demand. The exact brand distribution and simultaneous operating pattern must be measured before reporting actual demand.

## Repository Structure

- `01-Project-Overview/` — 28-heading academic study and project framing
- `02-System-Study/` — distributed heater system, boundaries and components
- `03-Thermodynamic-Analysis/` — Zeroth Law, First Law, heat transfer and SFEE
- `04-Calculations/` — field-based calculations and data interpretation
- `05-Graphs/` — charts generated only from available observations/calculated values
- `06-AI-Visualizations/` — prompts for non-fabricated conceptual visuals
- `07-Thermodynamics-Simulator/` — browser-based calculation simulator
- `08-Documentary/` — documentary plan and link placeholder
- `09-Final-Report/` — report structure and conclusion
- `10-Field-Evidence/` — evidence/photo placement guide

## 28 Main Headings

1. Introduction to the Hostel Hot-Water System  
2. Thermodynamic System, Surroundings and Boundary  
3. Open, Closed and Isolated System  
4. Working Substance – Water  
5. Thermodynamic State and Properties  
6. Intensive and Extensive Properties  
7. Thermodynamic Equilibrium  
8. Zeroth Law of Thermodynamics  
9. Temperature Measurement and Temperature Scales  
10. Thermodynamic Processes  
11. Heat and Work Interactions  
12. First Law of Thermodynamics  
13. Application of First Law to the Hot-Water System  
14. Internal Energy and Enthalpy  
15. Specific Heat Capacity of Water  
16. Heat Required for Water Heating  
17. Electrical Energy Input to the Heater  
18. Energy Conversion in the Water Heater  
19. Steady-Flow Energy Equation (SFEE)  
20. Application of SFEE to the Water-Heater System  
21. Flow of Water Through the System  
22. Heat Transfer and Modes of Heat Loss  
23. Thermodynamic Properties of Water  
24. Energy Losses and System Efficiency  
25. Experimental Observation and Data Collection  
26. Thermodynamic Calculations and Performance Analysis  
27. Energy-Saving Improvements and Engineering Recommendations  
28. Conclusion and Thermodynamic Significance

## How to Use

1. Open `01-Project-Overview/28-Content-Thermodynamic-Study.md` for the complete academic content.
2. Review `04-Calculations/` before inserting numbers into the final report.
3. Add your exact brand distribution when you have counted V-Guard vs Venus units.
4. Add exact temperature-vs-time measurements if you perform a timed experiment.
5. Add electrical meter readings if available.
6. Replace the documentary placeholder with your final video link.
7. Add only permitted hostel/heater photographs; avoid students and personal information.
8. Open `07-Thermodynamics-Simulator/index.html` in a browser to test calculations.

## Academic Integrity Note

This is a field-study portfolio, not a certified heater efficiency or electrical safety test. Manufacturer specifications and field observations should remain clearly separated from calculated/reference values.
