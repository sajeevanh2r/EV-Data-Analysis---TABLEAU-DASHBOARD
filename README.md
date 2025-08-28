# US Electric Vehicle (EV) Population Dashboard 📈🔌🚗

## Table of Contents
- [Project Overview](#project-overview)
- [Dashboard Screenshot](#dashboard-screenshot)
- [Key Features & Insights](#key-features--insights)
- [Interactive Filters](#interactive-filters)
- [Core KPIs](#core-kpis)
- [Detailed Visualizations](#detailed-visualizations)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [How to View the Dashboard](#how-to-view-the-dashboard)
- [Repository Structure](#repository-structure)
- [Contact](#contact)

---

## Project Overview
This project presents an interactive Tableau dashboard designed to provide a comprehensive analysis of the Electric Vehicle (EV) population in the USA. The dashboard allows users to explore key trends, distribution, and characteristics of both **Battery Electric Vehicles (BEVs)** and **Plug-in Hybrid Electric Vehicles (PHEVs)** through intuitive visualizations and key performance indicators (KPIs).

The aim is to offer quick, actionable insights into:
- EV market growth over the years  
- Geographical adoption patterns  
- Popular vehicle models and manufacturers  
- Clean Air Fuel Vehicle (CAFZ) eligibility status  

---

## Dashboard Screenshot
Here's a snapshot of the interactive dashboard:  

![Dashboard Screenshot](EV%20Dashboard.PNG)

---

## Key Features & Insights

### Interactive Filters
Located on the left sidebar, filters allow users to dynamically adjust the data displayed across the dashboard:
- **CAFZ Eligibility:** Filter by Clean Air Fuel Vehicle status  
- **EV Type:** Select BEV, PHEV, or All  
- **Model:** Drill down to specific EV models  
- **State:** Analyze data by US state  

### Core KPIs
The top section highlights critical metrics:

| KPI | Value | Description |
|-----|-------|-------------|
| **Total Vehicles** | 150,413 | Overall count of EVs (BEVs + PHEVs) in the dataset |
| **Average Electric Range** | 67.83 KM | Average electric range, indicating technological capability |
| **Total BEV Vehicles & %** | 116,745 (77.62%) | Number and percentage of BEVs, showing dominance of fully electric models |
| **Total PHEV Vehicles & %** | 33,668 (22.38%) | Number and percentage of PHEVs, reflecting hybrid market share |

---

## Detailed Visualizations
1. **Total Vehicles by Model Year (2012 Onwards)**  
   - Type: Line/Area Chart  
   - Purpose: Shows growth trend of EV population over time, highlighting peaks around 2022 (~37.1K vehicles).  

2. **Total Vehicles by State**  
   - Type: Choropleth Map  
   - Purpose: Displays EV registration density across US states.  

3. **Top 5 Total Vehicles by Make**  
   - Type: Horizontal Bar Chart  
   - Purpose: Highlights leading manufacturers like Tesla, Nissan, Chevrolet, Ford, BMW.  

4. **Total Vehicles by CAFZ Eligibility**  
   - Type: Donut Chart  
   - Purpose: Shows proportions of eligible, not eligible, and unknown vehicles.  

5. **Top 10 Total Vehicles by Model**  
   - Type: Table  
   - Purpose: Provides detailed view of popular EV models, including Make, EV Type, count, and % of total.  

---

## Data Source
The data represents the US EV population, based on publicly available EV registration datasets from state-level departments of licensing or energy. For production, a live, curated data source could be connected.  

---

## Technologies Used
- **Tableau Desktop:** For visualization and dashboard creation  

---

## How to View the Dashboard
1. Install Tableau Desktop (licensed copy).  
2. Download `EV ANALYSIS.twbx` from this repository.  
3. Open the workbook in Tableau Desktop.  
4. Use filters and hover over visualizations to explore insights.  

---

## Repository Structure
├── README.md
├── US_EV_Population_Dashboard.twbx
└── EV Dashboard.PNG

- `README.md`: Project overview and instructions  
- `EV ANALYSIS.twbx`: Tableau Packaged Workbook with all data and dashboard  
- `EV Dashboard.PNG`: Static image of the dashboard for quick preview  

---

## Contact
- **Author:** Radhakrishnan Sajeevan  


