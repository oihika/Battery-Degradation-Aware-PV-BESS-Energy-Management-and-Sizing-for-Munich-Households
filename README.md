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


🧠 Methodology
📍 Munich, Germany case study
☀️ Synthetic hourly PV generation profile
🏠 Residential household load modeling
🔋 Battery SOC-based charge and discharge control
📉 Depth of discharge analysis
⏳ 15-year battery degradation modeling
🔁 Battery replacement year estimation
💰 Payback and LCOE calculation
⚙️ Battery sizing optimization
🚗 New Li-ion vs second-life EV battery comparison
⚡ Simple frequency support simulation
📁 Project Structure
📦 munich-pv-bess-battery-degradation
┣ 📜 munich_pv_bess_simulation.py
┣ 📜 requirements.txt
┣ 📜 munich_results_summary.csv
┣ 📜 munich_final_results.csv
┣ 📜 munich_hourly_profile.csv
┣ 📜 munich_frequency_support.csv
┣ 📄 ieee_munich_pv_bess_report_oihika_arpit.pdf
┣ 📊 01_munich_pv_load_profile.png
┣ 📊 02_munich_soc_tracking.png
┣ 📊 03_munich_depth_of_discharge.png
┣ 📊 04_munich_battery_degradation.png
┣ 📊 05_munich_replacement_year.png
┣ 📊 06_munich_payback_year.png
┣ 📊 07_munich_lcoe_impact.png
┣ 📊 08_munich_new_vs_second_life_capex.png
┣ 📊 09_munich_frequency_support.png
┗ 📜 README.md
📈 Results and Visualizations
☀️ Munich PV and Household Load Profile


🔋 Battery SOC Tracking


📉 Depth of Discharge


⏳ Battery Degradation Over 15 Years


🔁 Battery Replacement Year


💰 Payback Year


📊 LCOE Impact


🚗 New vs Second-Life EV Battery CAPEX


⚡ Frequency Support Simulation


🔍 Key Results
Metric	Result
Case study city	Munich, Germany
PV system size	6 kWp
Annual household load	4500 kWh/year
Project lifetime	15 years
Best battery type	Second-life EV
Best battery size	4 kWh
LCOE	0.400 EUR/kWh
Payback year	11
Replacement year	4
💡 Key Insights
Battery degradation strongly affects long-term PV-BESS economics.
Second-life EV batteries can reduce capital cost compared with new Li-ion batteries.
Larger batteries improve self-consumption but may increase LCOE.
Battery replacement timing is important for lifecycle planning.
For the selected Munich assumptions, a 4 kWh second-life EV battery gives the best LCOE.
Frequency support can be modeled as an additional grid service from the battery.
⚙️ Technologies Used
Python 🐍
NumPy
Pandas
Matplotlib 📊
CSV data analysis
PV-BESS energy simulation
Battery degradation modeling
🚀 How to Run
git clone https://github.com/your-username/munich-pv-bess-battery-degradation.git
cd munich-pv-bess-battery-degradation

pip install -r requirements.txt
python munich_pv_bess_simulation.py
📄 Report
The IEEE-style project report is included:

ieee_munich_pv_bess_report_oihika_arpit.pdf
The report contains:

Abstract
Methodology
System parameters
Battery cases
Output graphs
Key results
Conclusion
Python code appendix
🔮 Future Improvements
Use real Munich weather and irradiance data
Integrate smart meter household load data
Add dynamic electricity pricing
Include battery thermal degradation
Add CO₂ emission reduction analysis
Use AI-based load and PV forecasting
Build a Streamlit dashboard
Extend model for community microgrids
👨‍💻 Author
Oihika Arpit
Electronics & Communication Engineering
Renewable Energy, Battery Storage and Data Science Enthusiast

📜 License
This project is licensed under the MIT License.

About
A Python-based simulation and optimization of a degradation-aware residential PV-BESS energy system for Munich, Germany, featuring SOC tracking, depth of discharge, 15-year battery aging, replacement timing, payback, LCOE, battery sizing, second-life EV battery comparison, and frequency support.
```
            ↓
✅ Optimal Battery Sizing
