# Solar Photovoltaic Installation Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Focus](https://img.shields.io/badge/Focus-Renewable%20Energy%20%7C%20Optimization-green)
![Status](https://img.shields.io/badge/Status-Academic%20Project-orange)

## Overview

This project simulates the energy production, efficiency, and economic viability of a **Grid-Connected Photovoltaic (PV) System** for a single-family residence in Catalonia, Spain.

Using meteorological data and physical models, the simulation optimizes the installation parameters to maximize energy yield and calculates the Return on Investment (ROI) considering current electricity prices.

## Key Objectives

* **Solar Irradiance Modeling:** Calculate the potential solar radiation based on geographical coordinates (Latitude/Longitude) and panel inclination.
* **System Sizing:** Determine the optimal number of panels and inverter capacity to meet the household's energy demand (~5kW peak).
* **Performance Analysis:** Estimate energy losses due to temperature, shadowing, and wiring (Performance Ratio).
* **Economic Assessment:** Calculate the payback period (amortization) and Net Present Value (NPV) of the installation.

## Methodology & Tech Stack

The analysis is implemented in **Python**, utilizing numerical methods to process solar data.

* **Core Libraries:** `numpy` (calculations), `matplotlib` (visualization), `pandas` (time-series data).
* **Data Sources:** PVGIS (Photovoltaic Geographical Information System) and local meteorological datasets.
* **Physics applied:** Calculation of Peak Sun Hours (PSH) and current-voltage (I-V) characteristic curves.


## Usage

1.  Clone the repository:
    ```bash
    git clone [https://github.com/sergimaralm/Solar-Energy-Installation-Analysis.git](https://github.com/sergimaralm/Solar-Energy-Installation-Analysis.git)
    ```
2.  Run the main simulation script:
    ```bash
    python solar_simulation.py
    ```

## Disclaimer & Credits

**Academic Project (UAB)**
* **Context:** Developed as a practical assignment for the Numerics Methods course.
* **Authors:** Developed in collaboration with classmates.
* **License:** Educational use only.
---
*Maintained by Sergi Martínez Almansa*


