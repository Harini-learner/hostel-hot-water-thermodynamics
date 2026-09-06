# AI Visualizations & Conceptual Schematics

---

## 1. Distributed Water-Heater System Schematic
> **Prompt:** Create a clean engineering schematic of a distributed electric storage water-heater system serving seven hostel buildings, with separate local heaters and no central boiler.

<svg viewBox="0 0 800 320" xmlns="http://www.w3.org/2000/svg" style="width: 100%; height: auto; background: #0f172a; border-radius: 10px; padding: 16px;">
  <text x="400" y="30" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">Distributed Water-Heater Architecture (7 Hostels)</text>
  
  <!-- Central Boiler Crossed Out -->
  <g transform="translate(50, 80)">
    <rect width="130" height="180" rx="8" fill="#1e293b" stroke="#ef4444" stroke-width="2" stroke-dasharray="4"/>
    <text x="65" y="80" fill="#ef4444" font-size="14" font-weight="bold" text-anchor="middle">CENTRAL</text>
    <text x="65" y="100" fill="#ef4444" font-size="14" font-weight="bold" text-anchor="middle">BOILER</text>
    <line x1="20" y1="30" x2="110" y2="150" stroke="#ef4444" stroke-width="4"/>
    <line x1="110" y1="30" x2="20" y2="150" stroke="#ef4444" stroke-width="4"/>
    <text x="65" y="168" fill="#94a3b8" font-size="11" text-anchor="middle">NO CENTRAL PIPE</text>
  </g>

  <!-- Flow Divider -->
  <line x1="210" y1="80" x2="210" y2="260" stroke="#334155" stroke-width="2" stroke-dasharray="6"/>

  <!-- Decentralized Hostel Nodes -->
  <g transform="translate(240, 70)">
    <!-- Grid of Hostels H1 to H7 -->
    <g transform="translate(0,0)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 01 - H01</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>

    <g transform="translate(180,0)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 02 - H02</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>

    <g transform="translate(360,0)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 03 - H03</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>

    <g transform="translate(0,70)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 04 - H04</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>

    <g transform="translate(180,70)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 05 - H05</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>

    <g transform="translate(360,70)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 06 - H06</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>

    <g transform="translate(180,140)">
      <rect width="150" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
      <text x="15" y="25" fill="#f8fafc" font-size="13" font-weight="bold">Hostel 07 - H07</text>
      <text x="15" y="42" fill="#38bdf8" font-size="11">⚡ Local Heaters (25L)</text>
    </g>
  </g>
</svg>

---

## 2. Educational Energy-Flow Diagram
> **Prompt:** Create an educational energy-flow diagram: electrical energy → heating element → water → hot-water outlet, with heat-loss arrows to surroundings.

<svg viewBox="0 0 800 260" xmlns="http://www.w3.org/2000/svg" style="width: 100%; height: auto; background: #0f172a; border-radius: 10px; padding: 16px;">
  <text x="400" y="30" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">Water Heater Energy Flow & Conversion</text>

  <!-- Step 1: Electrical Input -->
  <g transform="translate(30, 80)">
    <rect width="140" height="70" rx="8" fill="#eab308"/>
    <text x="70" y="35" fill="#0f172a" font-size="13" font-weight="bold" text-anchor="middle">Electrical Energy</text>
    <text x="70" y="52" fill="#0f172a" font-size="11" text-anchor="middle">(Power Supply)</text>
  </g>

  <path d="M 170 115 L 210 115" stroke="#f8fafc" stroke-width="3" marker-end="url(#arrow)"/>

  <!-- Step 2: Heating Element -->
  <g transform="translate(210, 80)">
    <rect width="140" height="70" rx="8" fill="#f97316"/>
    <text x="70" y="35" fill="#ffffff" font-size="13" font-weight="bold" text-anchor="middle">Heating Element</text>
    <text x="70" y="52" fill="#ffedd5" font-size="11" text-anchor="middle">(Joule Heating I²R)</text>
  </g>

  <path d="M 350 115 L 390 115" stroke="#f8fafc" stroke-width="3"/>

  <!-- Step 3: Water Storage Tank -->
  <g transform="translate(390, 80)">
    <rect width="160" height="70" rx="8" fill="#0284c7"/>
    <text x="80" y="35" fill="#ffffff" font-size="13" font-weight="bold" text-anchor="middle">Water Mass (25 L)</text>
    <text x="80" y="52" fill="#e0f2fe" font-size="11" text-anchor="middle">(Sensible Heat Q)</text>
  </g>

  <path d="M 550 115 L 590 115" stroke="#f8fafc" stroke-width="3"/>

  <!-- Step 4: Hot Water Outlet -->
  <g transform="translate(590, 80)">
    <rect width="160" height="70" rx="8" fill="#10b981"/>
    <text x="80" y="35" fill="#ffffff" font-size="13" font-weight="bold" text-anchor="middle">Hot Water Outlet</text>
    <text x="80" y="52" fill="#d1fae5" font-size="11" text-anchor="middle">(Useful Thermal Output)</text>
  </g>

  <!-- Heat Loss Arrows -->
  <path d="M 280 150 L 280 200" stroke="#ef4444" stroke-width="3" stroke-dasharray="4"/>
  <text x="280" y="220" fill="#ef4444" font-size="11" font-weight="bold" text-anchor="middle">Electrical Loss (Joule/Wiring)</text>

  <path d="M 470 150 L 470 200" stroke="#ef4444" stroke-width="3" stroke-dasharray="4"/>
  <text x="470" y="220" fill="#ef4444" font-size="11" font-weight="bold" text-anchor="middle">Standby Jacket Heat Loss (Q_loss)</text>
</svg>

---

## 3. Thermodynamics Infographic ($Q = m c_p \Delta T$)
> **Prompt:** Create a thermodynamics infographic explaining $Q = m c_p \Delta T$ for a 25 L water heater, using 37 °C inlet and 45 °C minimum reference outlet.

<svg viewBox="0 0 800 280" xmlns="http://www.w3.org/2000/svg" style="width: 100%; height: auto; background: #0f172a; border-radius: 10px; padding: 16px;">
  <text x="400" y="30" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">Heat Required Calculation: Q = m · c_p · ΔT</text>

  <!-- Variable Cards -->
  <g transform="translate(40, 60)">
    <rect width="160" height="90" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="80" y="30" fill="#38bdf8" font-size="14" font-weight="bold" text-anchor="middle">Mass (m)</text>
    <text x="80" y="55" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">25 kg</text>
    <text x="80" y="72" fill="#94a3b8" font-size="11" text-anchor="middle">(25 Liters Water)</text>
  </g>

  <text x="220" y="115" fill="#f8fafc" font-size="22" font-weight="bold">×</text>

  <g transform="translate(240, 60)">
    <rect width="160" height="90" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="80" y="30" fill="#38bdf8" font-size="14" font-weight="bold" text-anchor="middle">Specific Heat (c_p)</text>
    <text x="80" y="55" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">4.184 kJ/kg·°C</text>
    <text x="80" y="72" fill="#94a3b8" font-size="11" text-anchor="middle">(Water Heat Capacity)</text>
  </g>

  <text x="420" y="115" fill="#f8fafc" font-size="22" font-weight="bold">×</text>

  <g transform="translate(440, 60)">
    <rect width="160" height="90" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="80" y="30" fill="#38bdf8" font-size="14" font-weight="bold" text-anchor="middle">Temp Rise (ΔT)</text>
    <text x="80" y="55" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">8 °C</text>
    <text x="80" y="72" fill="#94a3b8" font-size="11" text-anchor="middle">(45 °C - 37 °C)</text>
  </g>

  <text x="620" y="115" fill="#f8fafc" font-size="22" font-weight="bold">=</text>

  <!-- Result Card -->
  <g transform="translate(640, 60)">
    <rect width="130" height="90" rx="8" fill="#10b981"/>
    <text x="65" y="30" fill="#ffffff" font-size="14" font-weight="bold" text-anchor="middle">Thermal Energy (Q)</text>
    <text x="65" y="55" fill="#ffffff" font-size="17" font-weight="bold" text-anchor="middle">836.8 kJ</text>
    <text x="65" y="72" fill="#d1fae5" font-size="11" text-anchor="middle">(0.232 kWh)</text>
  </g>

  <!-- Summary Box -->
  <rect x="40" y="180" width="730" height="60" rx="8" fill="#1e293b" stroke="#334155" stroke-width="1"/>
  <text x="405" y="205" fill="#f8fafc" font-size="13" text-anchor="middle">Heating 25 L of inlet water from 37 °C to the required 45 °C reference output</text>
  <text x="405" y="225" fill="#38bdf8" font-size="13" font-weight="bold" text-anchor="middle">Requires a minimum energy input of 836.8 kJ (0.232 kWh) per cycle.</text>
</svg>
