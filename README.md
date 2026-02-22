# MEG 315 — AD-HTC Integrated Biorefinery Dashboard

> **Applied Thermodynamics · University of Lagos (UNILAG)**  
> An interactive thermodynamic simulation dashboard for an Anaerobic Digestion – Hydrothermal Carbonization (AD-HTC) biomass power plant.



---

## Overview

This dashboard was built as part of MEG 315 — Applied Thermodynamics at the University of Lagos. It simulates and visualises the thermodynamic behaviour of an integrated AD-HTC biorefinery system, based on the methodology of:



---

## Features

- **Live thermodynamic calculations** — all outputs update in real time as you adjust input sliders
- **Biogas ICE (Otto Cycle)** — T-s diagram with 4 state points (inlet, compression, combustion, exhaust)
- **Rankine Steam Cycle** — h-s Mollier diagram with pump, boiler, turbine, and condenser states
- **Heat Integration Panel** — Pinch Analysis logic showing CHP waste heat vs. AD and HTC demand
- **Animated Process Schematic** — live material flow animation through AD → CHP → HTC → Hydrochar
- **Mass & Energy Charts** — daily biogas, digestate, hydrochar, electricity, and thermal outputs
- **Feedstock Selector** — switch between cattle manure, corn silage, sewage sludge, food waste, and mixed
- **HTC Temperature Slider** — adjusts hydrothermal carbonization temperature (180–260°C)
- **OLR KPI** — Organic Loading Rate displayed as kg VS/m³·day

---

## Thermodynamic Concepts Covered

| Concept | Application in Dashboard |
|---|---|
| First Law of Thermodynamics | CHP energy balance (electrical + thermal output) |
| Second Law / Exergy | Irreversibility in combustion and heat transfer |
| Otto Cycle | Biogas ICE T-s diagram (4 states) |
| Rankine / ORC Cycle | Steam bottoming cycle h-s Mollier diagram |
| Pinch Analysis | Heat integration: CHP → AD → HTC cascade |
| Mass Balance | AD digestate, HTC hydrochar, process water flows |
| LHV / HHV | Biogas lower heating value, hydrochar higher heating value |

---

## How to Use

1. Open the [live link] in any browser
2. Select a **feedstock** from the dropdown
3. Adjust sliders in the sidebar:
   - Feedstock mass flow rate
   - Compression ratio & peak temperature (Otto cycle)
   - Boiler pressure, condenser pressure & steam temperature (Rankine cycle)
   - HTC reactor temperature
4. Watch all KPI cards, charts, and diagrams update instantly

No installation required — runs entirely in the browser.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| HTML / CSS / JavaScript | Core dashboard |
| [Chart.js](https://www.chartjs.org/) | T-s, h-s, energy, and mass charts |
| [Tailwind CSS](https://tailwindcss.com/) | Styling |
| [Google Fonts — Inter & Space Grotesk](https://fonts.google.com/) | Typography |
| SVG | Animated process flow schematic |

---

## Based On

This dashboard contextualises the supply chain and process flowsheet optimisation methodology within the thermodynamic framework of MEG 315, including:

- Otto cycle analysis for biogas-fuelled CHP units
- Rankine/ORC cycle for waste heat recovery
- Pinch Analysis for heat integration between CHP, AD, and HTC
- First and Second Law efficiency calculations

---


