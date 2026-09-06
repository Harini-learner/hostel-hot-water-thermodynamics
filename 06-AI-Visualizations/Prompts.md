# AI Visualizations

### 1. Distributed Water-Heater System Schematic
<svg viewBox="0 0 780 180" width="100%" xmlns="http://www.w3.org/2000/svg" style="background:#0f172a; border-radius:8px; padding:12px;">
  <text x="390" y="22" fill="#f8fafc" font-size="15" font-weight="bold" text-anchor="middle">Distributed Water-Heater Architecture (7 Hostels)</text>
  
  <g transform="translate(10,40)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 01 - H01</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  <g transform="translate(200,40)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 02 - H02</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  <g transform="translate(390,40)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 03 - H03</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  <g transform="translate(580,40)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 04 - H04</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  
  <g transform="translate(10,105)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 05 - H05</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  <g transform="translate(200,105)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 06 - H06</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  <g transform="translate(390,105)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#38bdf8" stroke-width="2"/>
    <text x="85" y="25" fill="#f8fafc" font-size="12" font-weight="bold" text-anchor="middle">Hostel 07 - H07</text>
    <text x="85" y="42" fill="#38bdf8" font-size="11" text-anchor="middle">⚡ Local Heaters (25L)</text>
  </g>
  <g transform="translate(580,105)">
    <rect width="170" height="55" rx="6" fill="#1e293b" stroke="#ef4444" stroke-width="2" stroke-dasharray="4"/>
    <text x="85" y="24" fill="#ef4444" font-size="11" font-weight="bold" text-anchor="middle">CENTRAL BOILER</text>
    <text x="85" y="40" fill="#ef4444" font-size="10" font-weight="bold" text-anchor="middle">(NOT USED)</text>
    <line x1="15" y1="10" x2="155" y2="45" stroke="#ef4444" stroke-width="2.5"/>
    <line x1="155" y1="10" x2="15" y2="45" stroke="#ef4444" stroke-width="2.5"/>
  </g>
</svg>

---

### 2. Educational Energy-Flow Diagram
<svg viewBox="0 0 800 210" width="100%" xmlns="http://www.w3.org/2000/svg" style="background:#0f172a; border-radius:8px; padding:12px;">
  <text x="400" y="24" fill="#f8fafc" font-size="15" font-weight="bold" text-anchor="middle">Water Heater Energy Flow &amp; Conversion</text>
  
  <g transform="translate(10, 45)">
    <rect width="160" height="60" rx="8" fill="#eab308"/>
    <text x="80" y="28" fill="#0f172a" font-size="12" font-weight="bold" text-anchor="middle">Electrical Energy</text>
    <text x="80" y="44" fill="#0f172a" font-size="10" text-anchor="middle">(Power Supply)</text>
  </g>
  
  <text x="188" y="80" fill="#f8fafc" font-size="20" font-weight="bold">→</text>
  
  <g transform="translate(210, 45)">
    <rect width="160" height="60" rx="8" fill="#f97316"/>
    <text x="80" y="28" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Heating Element</text>
    <text x="80" y="44" fill="#ffedd5" font-size="10" text-anchor="middle">(Joule Heating I²R)</text>
  </g>
  
  <text x="388" y="80" fill="#f8fafc" font-size="20" font-weight="bold">→</text>
  
  <g transform="translate(410, 45)">
    <rect width="160" height="60" rx="8" fill="#0284c7"/>
    <text x="80" y="28" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Water Mass (25 L)</text>
    <text x="80" y="44" fill="#e0f2fe" font-size="10" text-anchor="middle">(Sensible Heat Q)</text>
  </g>
  
  <text x="588" y="80" fill="#f8fafc" font-size="20" font-weight="bold">→</text>
  
  <g transform="translate(610, 45)">
    <rect width="180" height="60" rx="8" fill="#10b981"/>
    <text x="90" y="28" fill="#ffffff" font-size="12" font-weight="bold" text-anchor="middle">Hot Water Outlet</text>
    <text x="90" y="44" fill="#d1fae5" font-size="10" text-anchor="middle">(Useful Thermal Output)</text>
  </g>
  
  <path d="M 290 105 L 290 145" stroke="#ef4444" stroke-width="2" stroke-dasharray="4"/>
  <text x="290" y="165" fill="#ef4444" font-size="10" font-weight="bold" text-anchor="middle">Electrical Loss (Joule/Wiring)</text>
  
  <path d="M 490 105 L 490 145" stroke="#ef4444" stroke-width="2" stroke-dasharray="4"/>
  <text x="490" y="165" fill="#ef4444" font-size="10" font-weight="bold" text-anchor="middle">Standby Jacket Heat Loss (Q_loss)</text>
</svg>

---

### 3. Thermodynamics Infographic (Q = m · c_p · ΔT)
<svg viewBox="0 0 800 210" width="100%" xmlns="http://www.w3.org/2000/svg" style="background:#0f172a; border-radius:8px; padding:12px;">
  <text x="400" y="24" fill="#f8fafc" font-size="15" font-weight="bold" text-anchor="middle">Heat Required Calculation: Q = m · c_p · ΔT</text>
  
  <g transform="translate(10, 40)">
    <rect width="165" height="80" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="82" y="24" fill="#38bdf8" font-size="12" font-weight="bold" text-anchor="middle">Mass (m)</text>
    <text x="82" y="48" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">25 kg</text>
    <text x="82" y="66" fill="#94a3b8" font-size="10" text-anchor="middle">(25 Liters Water)</text>
  </g>
  
  <text x="192" y="88" fill="#f8fafc" font-size="20" font-weight="bold">×</text>
  
  <g transform="translate(210, 40)">
    <rect width="180" height="80" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="90" y="24" fill="#38bdf8" font-size="12" font-weight="bold" text-anchor="middle">Specific Heat (c_p)</text>
    <text x="90" y="48" fill="#f8fafc" font-size="15" font-weight="bold" text-anchor="middle">4.184 kJ/kg·°C</text>
    <text x="90" y="66" fill="#94a3b8" font-size="10" text-anchor="middle">(Water Heat Capacity)</text>
  </g>
  
  <text x="407" y="88" fill="#f8fafc" font-size="20" font-weight="bold">×</text>
  
  <g transform="translate(425, 40)">
    <rect width="175" height="80" rx="8" fill="#1e293b" stroke="#38bdf8" stroke-width="1.5"/>
    <text x="87" y="24" fill="#38bdf8" font-size="12" font-weight="bold" text-anchor="middle">Temp Rise (ΔT)</text>
    <text x="87" y="48" fill="#f8fafc" font-size="18" font-weight="bold" text-anchor="middle">8 °C</text>
    <text x="87" y="66" fill="#94a3b8" font-size="10" text-anchor="middle">(45 °C - 37 °C)</text>
  </g>
  
  <text x="617" y="88" fill="#f8fafc" font-size="20" font-weight="bold">=</text>
  
  <g transform="translate(635, 40)">
    <rect width="155" height="80" rx="8" fill="#10b981"/>
    <text x="77" y="24" fill="#ffffff" font-size="11" font-weight="bold" text-anchor="middle">Thermal Energy (Q)</text>
    <text x="77" y="48" fill="#ffffff" font-size="17" font-weight="bold" text-anchor="middle">836.8 kJ</text>
    <text x="77" y="66" fill="#d1fae5" font-size="10" text-anchor="middle">(0.232 kWh)</text>
  </g>
  
  <rect x="10" y="135" width="780" height="55" rx="8" fill="#1e293b" stroke="#334155" stroke-width="1"/>
  <text x="400" y="158" fill="#f8fafc" font-size="12" text-anchor="middle">Heating 25 L of inlet water from 37 °C to the required 45 °C reference output</text>
  <text x="400" y="176" fill="#38bdf8" font-size="12" font-weight="bold" text-anchor="middle">Requires a minimum energy input of 836.8 kJ (0.232 kWh) per cycle.</text>
</svg>
