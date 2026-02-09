# 🌍 Global Energy Transition Tracker (1990 - 2024)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Teal?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **"Analyzing the global shift from fossil fuels to renewable energy: A data-driven approach to visualize efficiency, correlation, and environmental impact."**

---

## 📸 Dashboard Preview

### 1. Global Energy Transition Tracker (Overview)

<img width="1269" height="711" alt="image" src="https://github.com/user-attachments/assets/9611fe0e-ae6d-41c6-991f-31ff503fa640" />

### 2. Energy Transition Diagnostics (Deep Dive)

<img width="1268" height="712" alt="image" src="https://github.com/user-attachments/assets/a76adf50-5fb2-4f23-b33a-bd378e7dd51e" />

---

## 📖 Executive Summary
This project explores global energy consumption patterns over the last three decades using data from **Our World in Data (OWID)**. The objective was to diagnose the effectiveness of the global energy transition by answering critical business questions:
* **Adoption Rate:** How fast are major economies shifting to clean energy?
* **Dependency:** Which countries are still heavily reliant on fossil fuels?
* **Economic Impact:** Is there a correlation between Wealth (GDP) and Carbon Emissions? (Decoupling effect)

The dashboard is designed for **policymakers and energy analysts** to monitor KPIs, identify trends, and benchmark country performance dynamically.

---

## 📊 Dashboard Features & Key Insights

### 🔹 Page 1: Global Tracker (Overview)
* **Strategic KPIs:** Monitors **Renewables Share (%)**, identifies the **Primary Fuel Source** (e.g., Oil, Gas), and tracks **Fossil Dependency** levels.
* **Geospatial Analysis:** "Global Energy Footprint" map visualizes consumption scale and clean energy adoption across regions.
* **Top Performers:** Rankings of countries leading the green revolution (e.g., Germany, UK).
* **Energy Transition Journey:** Small multiple line charts allowing for a direct comparison of renewable adoption trends across peer countries (France, Germany, Poland, UK).

### 🔹 Page 2: Diagnostics (Deep Dive)
* **Efficiency Metrics:** Tracks **Emission Intensity (kg/kWh)** and **Energy Use per Person (MWh)** to measure sustainability.
* **The Gap Closer:** A comparative analysis of **Total Fossil vs. Total Renewables** (TWh) to visualize if the gap is narrowing over time.
* **Wealth vs. Carbon Intensity:** A scatter plot analyzing the relationship between GDP per Capita and CO2 Emissions.
    * *Key Insight:* High-income nations are showing signs of "Decoupling" (growing GDP while lowering emissions), whereas developing nations show a linear correlation.
* **Real Impact Analysis:** A combo chart contrasting the rise of **Clean Energy** against **Total Emissions** to evaluate the effectiveness of green policies.

---

## 🛠️ Tools & Technologies Used
* **Microsoft Power BI Desktop:** Main tool for data visualization and dashboard creation.
* **Power Query (M Language):** Used for ETL processes (Data cleaning, unpivoting columns, handling missing values).
* **DAX (Data Analysis Expressions):** Created complex measures for time-intelligence and dynamic calculations:
    * `CALCULATE`, `DIVIDE`, `SUMX` for aggregation.
    * `Time Intelligence` for Year-over-Year (YoY) growth.
    * `Variables (VAR)` for cleaner and more performant code.
    * `Dynamic Formatting` for custom units (e.g., "MWh/person", "kg/kWh").
* **Data Modeling:** Built a Star Schema (optimized for performance) connecting Fact tables with Dimension tables.
How to Use
1.Download the .pbix file from this repository.
2.Open it with Power BI Desktop.
3.Use the Play Axis on the Diagnostics page to see the time-lapse animation of global development from 1990 to 2024.
4.Hover over charts to see custom Tooltips with detailed metrics.

Author
Watcharapol Anekthanaset Master's Student in Data Science | Ex-Sales Engineer 
Contact me : www.linkedin.com/in/watcharapon-anaketanaset-1043b9147

---

## 📂 Project Structure
```bash
├── 📁 assets              # Screenshots (overview.png, diagnostics.png) and GIF demos
├── 📄 Energy_Analysis.pbix # The Power BI source file (Download to view)
├── 📄 owid-energy-data.csv # Raw dataset (Sample)
└── 📄 README.md           # Project documentation
