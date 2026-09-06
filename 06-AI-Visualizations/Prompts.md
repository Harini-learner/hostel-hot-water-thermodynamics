# AI Visualizations & Conceptual Schematics

---

## 1. Distributed Water-Heater System Schematic
> **Prompt:** Create a clean engineering schematic of a distributed electric storage water-heater system serving seven hostel buildings, with separate local heaters and no central boiler.

<svg viewBox="0 0 800 200" width="100%" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)" style="background:#0f172a; border-radius:10px; padding:16px;">
  <text x="400" y="25" fill="#f8fafc" font-size="16" font-weight="bold" text-anchor="middle">Distributed Water-Heater Architecture (7 Hostels)</text>
  <g transform="translate(10,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 01</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(120,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 02</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(230,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 03</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(340,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 04</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(450,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 05</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(560,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 06</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(670,45)">
    <rect width="100" height="50" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="50" y="22" fill="#f8fafc" font-size="11" font-weight="bold" text-anchor="middle">Hostel 07</text>
    <text x="50" y="38" fill="#38bdf8" font-size="10" text-anchor="middle">Local 25L</text>
  </g>
  <g transform="translate(340,115)">
    <rect width="120" height="60" rx="6" fill="#1e293b" stroke="#ef4444" stroke-width="2" stroke-dasharray="4"/>
    <text x="60" y="28" fill="#ef4444" font-size="12" font-weight="bold" text-anchor="middle">CENTRAL BOILER</text>
    <text x="60" y="45" fill="#ef4444" font-size="10" font-weight="bold" text-anchor="middle">(NOT USED)</text>
    <line x1="10" y1="10" x2="110" y2="50" stroke="#ef4444" stroke-width="3"/>
    <line x1="110" y1="10" x2="10" y2="50" stroke="#ef4444" stroke-width="3"/>
  </g>
</svg>

---

## 2. Educational Energy-Flow Diagram
> **Prompt:** Create an educational energy-flow diagram: electrical energy → heating element → water → hot-water outlet, with heat-loss arrows to surroundings.

<svg viewBox="0 0 800 240" width="100%" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)" style="background:#0f172a; border-radius:10px; padding:16px;">
  <text x="400" y="25" fill="#f8fafc" font-size="16" font-weight="bold" text-anchor="middle">Water Heater Energy Flow &amp; Conversion</text>
  
  <!-- Node 1 -->
  <g transform="translate(20, 60)">
    <rect width="140" height="65" rx="8" fill="#eab308"/>
    <text x="70" y="32" fill="#0f172a" font-size="12" font-weight="bold" text-anchor="middle">Electrical Energy</text>
    <text x="70" y="48" fill="#0f172a" font-size="10" text-anchor="middle">(Power Supply)</text>
  </g>
  
  <text x="180" y="98" fill="#f8fafc" font-size="20" font-weight="bold">→</text>
  
  <!-- Node 2 -->
  <g transform="translate(210, 60)">
    <rect width="150" height="65" rx="8" fill="#f97316"/>
    <text x="75" y="32" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Heating Element</text>
    <text x="75" y="48" fill="#ffedd5" font-size="10" text-anchor="middle">(Joule Heating I²R)</text>
  </g>
  
  <text x="380" y="98" fill="#f8fafc" font-size="20" font-weight="bold">→</text>
  
  <!-- Node 3 -->
  <g transform="translate(410, 60)">
    <rect width="150" height="65" rx="8" fill="#0284c7"/>
    <text x="75" y="32" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Water Mass (25 L)</text>
    <text x="75" y="48" fill="#e0f2fe" font-size="10" text-anchor="middle">(Sensible Heat Q)</text>
  </g>
  
  <text x="580" y="98" fill="#f8fafc" font-size="20" font-weight="bold">→</text>
  
  <!-- Node 4 -->
  <g transform="translate(610, 60)">
    <rect width="160" height="65" rx="8" fill="#10b981"/>
    <text x="80" y="32" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Hot Water Outlet</text>
    <text x="80" y="48" fill="#d1fae5" font-size="10" text-anchor="middle">(Useful Thermal Output)</text>
  </g>
  
  <!-- Loss Arrow 1 -->
  <path d="M 285 130 L 285 175" stroke="#ef4444" stroke-width="2.5" stroke-dasharray="4"/>
  <text x="285" y="195" fill="#ef4444" font-size="10" font-weight="bold" text-anchor="middle">Electrical Loss (Joule/Wiring)</text>
  
  <!-- Loss Arrow 2 -->
  <path d="M 485 130 L 485 175" stroke="#ef4444" stroke-width="2.5" stroke-dasharray="4"/>
  <text x="485" y="195" fill="#ef4444" font-size="10" font-weight="bold" text-anchor="middle">Standby Jacket Heat Loss (Q_loss)</text>
</svg>

---

## 3. Thermodynamics Infographic ($Q = m c_p \Delta T$)
> **Prompt:** Create a thermodynamics infographic explaining $Q = m c_p \Delta T$ for a 25 L water heater, using 37 °C inlet and 45 °C minimum reference outlet.

<svg viewBox="0 0 800 240" width="100%" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)" style="background:#0f172a; border-radius:10px; padding:16px;">
  <text x="400" y="25" fill="#f8fafc" font-size="16" font-weight="bold" text-anchor="middle">Heat Required Calculation: Q = m · c_p · ΔT</text>
  
  <!-- Mass -->
  <g transform="translate(20, 50)">
    <rect width="160" height="85" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="80" y="26" fill="#38bdf8" font-size="13" font-weight="bold" text-anchor="middle">Mass (m)</text>
    <text x="80" y="52" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">25 kg</text>
    <text x="80" y="70" fill="#94a3b8" font-size="10" text-anchor="middle">(25 Liters Water)</text>
  </g>
  
  <text x="198" y="100" fill="#f8fafc" font-size="20" font-weight="bold">×</text>
  
  <!-- Specific Heat -->
  <g transform="translate(215, 50)">
    <rect width="175" height="85" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="87" y="26" fill="#38bdf8" font-size="13" font-weight="bold" text-anchor="middle">Specific Heat (c_p)</text>
    <text x="87" y="52" fill="#f8fafc" font-size="16" font-weight="bold" text-anchor="middle">4.184 kJ/kg·°C</text>
    <text x="87" y="70" fill="#94a3b8" font-size="10" text-anchor="middle">(Water Heat Capacity)</text>
  </g>
  
  <text x="408" y="100" fill="#f8fafc" font-size="20" font-weight="bold">×</text>
  
  <!-- Temp Rise -->
  <g transform="translate(425, 50)">
    <rect width="175" height="85" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="87" y="26" fill="#38bdf8" font-size="13" font-weight="bold" text-anchor="middle">Temp Rise (ΔT)</text>
    <text x="87" y="52" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">8 °C</text>
    <text x="87" y="70" fill="#94a3b8" font-size="10" text-anchor="middle">(45 °C - 37 °C)</text>
  </g>
  
  <text x="618" y="100" fill="#f8fafc" font-size="20" font-weight="bold">=</text>
  
  <!-- Result -->
  <g transform="translate(635, 50)">
    <rect width="145" height="85" rx="8" fill="#10b981"/>
    <text x="72" y="26" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Thermal Energy (Q)</text>
    <text x="72" y="52" fill="#ffffff" font-size="17" font-weight="bold" text-anchor="middle">836.8 kJ</text>
    <text x="72" y="70" fill="#d1fae5" font-size="10" text-anchor="middle">(0.232 kWh)</text>
  </g>
  
  <!-- Footer Note -->
  <rect x="20" y="155" width="760" height="55" rx="8" fill="#1e293b" stroke="#334155" stroke-width="1"/>
  <text x="400" y="178" fill="#f8fafc" font-size="12" text-anchor="middle">Heating 25 L of inlet water from 37 °C to the required 45 °C reference output</text>
  <text x="400" y="196" fill="#38bdf8" font-size="12" font-weight="bold" text-anchor="middle">Requires a minimum energy input of 836.8 kJ (0.232 kWh) per cycle.</text>
</svg>
