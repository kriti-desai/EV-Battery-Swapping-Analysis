# EV Battery-Swapping Network Analysis

## 📊 Data Analytics Hackathon

This project analyzes a simulated EV battery-swapping network to identify factors associated with unsuccessful battery-swap events and customer-support issues.

## 📌 Dataset Overview

- 3,877,013 swap events
- 152 stations
- 6 cities
- 6,500 batteries
- 20,000 riders
- 44,000 support tickets

## 🔍 Key Areas Analyzed

- Battery availability
- Demand pressure
- Temperature
- Battery State of Health (SOH)
- Battery retirement
- Customer-support tickets
- Unsuccessful swap events

## 💡 Key Findings

1. Lower battery availability is associated with higher unsuccessful swap rates.
2. Higher demand pressure is associated with increased unsuccessful swap occurrence.
3. Higher temperatures are associated with higher unsuccessful swap rates.
4. Battery retirement is strongly concentrated below 70% current SOH.
5. `no_battery_available` was the largest support-ticket category.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Statistical Analysis
- Google Colab

## 📁 Project Files

- `EV_Battery_Swapping_Analysis.ipynb` — Data analysis notebook
- `EV_Battery_Swapping_Network_Analysis.pdf` — Analysis report

## ⚠️ Note

The dataset is simulation-generated. The observed relationships represent associations and should not be interpreted as causal effects.
