# Colombo Office Building Energy Simulation using eQUEST

## Overview
This project presents a complete building energy simulation carried out using **eQUEST (DOE-2)** for a multi-storey office building located in Colombo. The model was developed to evaluate the building's annual energy performance, HVAC cooling loads, electrical consumption, utility costs, and peak demand characteristics.

The simulation includes:
- Building geometry creation
- HVAC system modelling
- Internal load configuration
- Utility tariff modelling
- Annual energy simulation
- Cooling load analysis
- End-use energy breakdown

---

## Software Used
- eQUEST 3.64

---

## Building Information

| Parameter | Value |
|---|---|
| Building Type | Commercial Office Building |
| Location | Colombo |
| Number of Floors | 5 |
| Building Dimensions | 40 m × 40 m |
| Approximate Floor Area | 8000 m² |
| HVAC System | Chilled Water VAV System |
| Chiller Type | Water-Cooled Electric Centrifugal Hermetic |

---

## Simulation Objectives

The following analyses were performed:

1. Monthly energy consumption by end use
2. Annual energy consumption by end use
3. Monthly utility bills
4. Monthly peak demand by end use
5. Annual peak demand by end use
6. Cooling load summary
7. Specific Energy Consumption (SEC)
8. Cooling energy intensity

---

## Generated Reports

The following reports were generated using eQUEST:

- Monthly Energy Consumption by End Use
- Annual Energy Consumption by End Use
- Monthly Utility Bills
- Monthly Peak Demand by End Use
- Annual Peak Demand by End Use
- SS-C Building HVAC Load Summary
- SS-C System Load Hours
- Monthly Electric Peak Day Load Profiles

---

## Key Calculations

### Total Floor Area

Total Floor Area = 40 x 40 x 5 = 8000 m^2


---

### Specific Energy Consumption (SEC)

SEC = Annual Total Energy Consumption / Total Floor Area

Unit: kWh/m^2/year


---

### Cooling Energy Intensity

Cooling Energy Intensity = Annual Cooling Electrical Energy / Total Floor Area

Unit: kWh/m^2/year

---

## Project Files

Typical project files included in this repository:

| File Type | Description |
|---|---|
| `.pd2` | eQUEST project file |
| `.inp` | DOE-2 input file |
| `.pdf` | Exported reports |

---

## Folder Structure

```text
project/
│
├── model/
│   ├── office_building.pd2
│   ├── office_building.inp
│   └── office_building.sim
│
├── reports/
│   ├── annual_energy_consumption.pdf
│   ├── annual_peak_demand.pdf
|   ├── cooling_load_summary.pdf
|   ├── monthly_energy_consumption.pdf
|   ├── monthly_peak_demand.pdf
|   ├── annual_utility_bills.pdf
│   ├── simulation_outputs.pdf
│   └── calculations.pdf
│
└── README.md
