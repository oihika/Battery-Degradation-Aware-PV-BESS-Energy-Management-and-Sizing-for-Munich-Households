# Battery-Degradation-Aware-PV-BESS-Energy-Management-and-Sizing-for-Munich-Households
Python simulation for Munich household PV-BESS energy management with SOC, DOD, 15-year battery degradation, replacement timing, payback, LCOE, sizing optimization, second-life EV battery comparison, and frequency support plots.

# ⚡ Battery Degradation-Aware PV-BESS Energy Management for Munich

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![Research](https://img.shields.io/badge/Research-PV--BESS-green?style=for-the-badge)
![Location](https://img.shields.io/badge/Case%20Study-Munich%2C%20Germany-red?style=for-the-badge)

## 🌞 Project Overview

This project presents a **Python-based simulation and optimization of a residential PV-BESS system for Munich, Germany**.

The model analyzes solar PV generation, household load demand, battery charging and discharging, **state of charge**, **depth of discharge**, **battery degradation over 15 years**, replacement timing, payback period, LCOE impact, battery sizing, and comparison between **new Li-ion batteries** and **second-life EV batteries**.

The objective is to identify an economical and technically reliable battery size for Munich households while considering long-term battery aging.

---

## 📌 Project Title

**Battery Degradation-Aware PV-BESS Energy Management and Sizing for Munich Households**

---

## 📊 System Architecture

```text
🌍 Munich Solar Resource Assumption
            ↓
☀️ PV Generation Model
            ↓
🏠 Residential Load Profile
            ↓
⚡ Hourly Energy Management Simulation
       ↙                    ↘
🔋 Battery Storage       🔌 Grid Import/Export
       ↓                    ↓
📉 SOC, DOD, Degradation, LCOE and Payback Analysis
            ↓
✅ Optimal Battery Sizing
