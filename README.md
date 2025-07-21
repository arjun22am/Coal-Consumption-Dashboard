# Coal-Consumption-Dashboard

This repository contains an interactive Tableau dashboard that analyzes coal consumption patterns across Indian Thermal Power Stations (TPS). It combines coal supply data with weather data to uncover insights that can help optimize resource planning and energy management.

---

## 📂 Project Files

- **`Indian_Coal_Consumption_Dashboard.twbx`** — Tableau Packaged Workbook (full dashboard)
  
- **`Coal_Dashboard_Image.pdf`** — Snapshot of the dashboard for quick preview
 
- **`Coal_Consumption_Dashboard_Documentation.docx`** — Full project documentation explaining data sources, analysis, visualizations, and key insights

- **`Python Scripts`** — Scripts written to fetch the data from api and to clean the data.

---

## 🚩 Problem Statement

India’s thermal power plants rely heavily on coal. However, there is often limited visibility into how different TPS and regions consume coal, their installed capacities, and how external factors like weather impact demand. This project solves this gap by presenting an interactive, data-driven dashboard.

---

## 📈 Key Insights

- **Vindhyachal STPS** is the largest coal consumer among top TPS.
  
- High installed capacity doesn’t always mean high consumption — e.g., Adani Power Limited Tiroda TPS.
  
- **Southern region** leads in average coal consumption, while the Northern region has the lowest.
  
- Seasonal peaks show higher demand during summer and pre-monsoon months.
  
- Coal sourcing heavily depends on CIL and Captive sources.
  
- Temperature trends correlate with coal consumption for some TPS.

---

## 🔍 Dashboard Overview

The Tableau dashboard includes:

- **Top 5 TPS Consumption:** Shows which TPS consume the most coal.
- **Top 5 Highest Installed Capacity:** Highlights the TPS with the highest capacity.
- **TPS Coal Consumption vs. Installed Capacity:** Compares consumption vs capacity.
- **Region-wise Average Coal Consumption:** Regional comparison.
- **Monthly Trends:** Time series analysis of coal usage.
- **Coal Source Breakdown:** Source-wise supply for each TPS.
- **Temperature Wise Consumption:** Impact of temperature on coal demand.

---

## 📊 Data Sources

| Coal-Related Data | Weather Data |

| **Source:** [National Power Portal - Monthly Coal Reports](https://npp.gov.in/) | **Source:** [Meteostat API via RapidAPI](https://rapidapi.com/) |

| Monthly records of coal supply, consumption, stock, and TPS-specific data | Historical & real-time weather data |

| Attributes: TPS name, Installed Capacity, Coal source (CIL, SCCL, Captive, E-Auction, Import, Others), Closing Stocks, Total Consumption | Attributes: Temperature, Precipitation, Wind Speed, Atmospheric Pressure |

---

## ⚙️ Tech Stack

- **Tableau** — Dashboard creation & visualization
- **Excel** — Data storage & cleaning
- **Python (Pandas, NumPy)** — Data preprocessing & calculations

---

## 🏆 Conclusion

This project gives stakeholders clear insights into coal consumption patterns, regional trends, seasonal impacts, and sourcing strategies. It helps inform better planning, supply chain management, and sustainable energy decisions.


---

## 📃 Documentation

For detailed methodology, charts explanation, and dataset description, see: **`Coal_Consumption_Dashboard_Documentation.docx`**

---

## 📧 Contact

**Author:** *[Arjun Mhatre]*  
**Email:** *[arjunmhatre2002am@gmail.coml]*  

---

⭐ *If you find this project helpful, feel free to ⭐ star this repo!*
