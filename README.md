# 10 kW solar PV system design and feasibility study using RETScreen and HelioScope, covering site assessment, solar analysis, DC/AC design, shading, system losses, and financial modeling.

### King Khaled International Airport — Riyadh, Saudi Arabia

A photovoltaic system design and feasibility study focused on the engineering, simulation, electrical design, site assessment, and financial evaluation of a rooftop solar PV system.

---

## Project Summary

This project presents the design and feasibility analysis of a **10 kW AC solar photovoltaic system** for a commercial building at **King Khaled International Airport (KKIA), Riyadh, Saudi Arabia**.

The project evaluates the suitability of the selected rooftop using solar resource assessment, solar-path analysis, shading analysis, and PV system simulation. The proposed system is designed as a load-displacement system to reduce daytime electricity consumption from the utility grid.

The design integrates PV module selection, inverter sizing, DC string configuration, AC electrical design, protection, system losses, energy production analysis, and financial evaluation.

The project was developed using **RETScreen Expert and HelioScope**, with the electrical design developed in consideration of the **Canadian Electrical Code (CEC)** requirements used within the academic design process.

---

## Site & Solar Resource Assessment

**Project Location:** King Khaled International Airport, Riyadh, Saudi Arabia

The selected rooftop was evaluated based on:

- Solar resource availability
- Roof area and orientation
- Solar path throughout the year
- Potential shading
- Module spacing
- Electrical system integration
- Building load requirements

The RETScreen assessment reported an annual average horizontal solar radiation of approximately **5.78 kWh/m²/day**.

Monthly solar radiation ranged from approximately **3.76 kWh/m²/day in January** to **7.87 kWh/m²/day in June**, demonstrating strong solar availability at the selected site.

---

## System Configuration

| Parameter | Design Value |
|---|---:|
| AC System Capacity | 10 kW |
| DC Array Capacity | 13.8 kW |
| PV Modules | ~44 |
| Module Rating | 310 W |
| DC/AC Ratio | ~1.38 |
| System Type | Fixed Tilt |
| Module Orientation | Landscape |
| Module Tilt | 24° |
| Inverter Rating | 10 kW |
| Grid Connection | Building Service Panel |
| AC Voltage | 230 V |
| Frequency | 50 Hz |

The simulated DC array consists of approximately **44 × 310 W modules**, producing a total DC nameplate capacity of approximately **13.8 kW**.

---

## PV Module & Inverter Selection

Several PV module and inverter options were evaluated based on power rating, efficiency, temperature performance, compatibility, and system requirements.

### Selected PV Module

**JA Solar 310 W Monocrystalline Module**

The module was selected based on its thermal performance, efficiency, and price-to-output considerations.

### Selected Inverter

**Huawei SUN2000 10 kW Inverter**

The inverter was selected to satisfy the required AC output while allowing DC-side oversizing.

---

## DC Design

The DC system was developed using HelioScope to evaluate:

- Module arrangement
- String configuration
- Voltage and current limits
- DC/AC ratio
- Module spacing
- Electrical compatibility
- Rooftop layout

The proposed configuration uses approximately **44 modules arranged in two strings of 22 modules**, with the DC array connected through combiner equipment to the inverter.

---
## AC Design

The AC system connects the PV inverter to the building's electrical distribution system.

The proposed electrical path is:

```text
PV Array
   ↓
DC Combiner
   ↓
PV Inverter
   ↓
AC Disconnect
   ↓
AC Feeder
   ↓
Building Service Panel
   ↓
Utility Meter / Point of Common Coupling
   ↓
Utility Grid

