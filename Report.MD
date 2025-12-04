# Introduction
This project was assigned to me as part of the **2025** Hackathon Program organized by 10alytics, which challenged participants to apply data analytics and visualization skills to real‑world economic issues. My focus was on Africa’s Fiscal Balance and Sustainability, analyzing the fiscal health of selected African countries between 2021 and 2025. The work followed a complete analytics workflow, beginning with data cleaning to ensure accuracy and consistency, followed by the separation of fact and dimension tables to build a robust star schema.
I then carried out data modelling to establish relationships between fiscal balances, countries, and years, and applied DAX analysis to create measures such as Net Fiscal Balance, Total Surplus, and Countries in Deficit/Surplus. Finally, I designed an interactive Power BI dashboard to visualize deficits, surpluses, and fiscal trends, providing actionable insights into Africa’s fiscal sustainability challenges.
Fiscal balance is a key indicator of economic sustainability, reflecting the difference between government revenues and expenditures. A surplus indicates fiscal strength, while a deficit signals potential vulnerability. This project leverages the Africa Fiscal Balance & Sustainability Dashboard to analyze the fiscal positions of selected African countries between **2021 and 2025.** 
The dashboard provides insights into deficits, surpluses, and overall regional trends, enabling policymakers and stakeholders to assess fiscal health and sustainability.

# Objectives
- To evaluate the fiscal balance of African countries over time.

- To identify countries with the largest deficits and surpluses.

- To highlight regional trends and sustainability challenges.

- To provide actionable recommendations for improving fiscal stability.

# Methodology

- **Data Source:** Fiscal data collected from country-level financial records.
- **Data Cleaning**
  - Removed duplicates and corrected inconsistent country names.

  - Handled missing values by replacing blanks with zero where appropriate.

  - Standardized fiscal balance figures to ensure comparability across countries.
- **Fact and Dimension Tables**
   - **Fact Table:** Contained transactional fiscal data (revenues, expenditures, balance type, year).

   - **Dimension Tables:** Included supporting structures such as Country, Year, and Balance Type.

This separation followed a star schema design, improving efficiency and clarity in analysis.

- **Data Modelling**
  - Established relationships between fact and dimension tables (e.g., linking fiscal balances to countries and years).

  - Ensured one‑to‑many relationships were correctly defined to avoid duplication in measures.

  - Created a semantic model that allowed flexible slicing by country, year, and balance type.

- **DAX Analysis**
  - Built measures for Total Surplus, Total Deficit, and Net Fiscal Balance.

  - Developed KPIs such as Countries in Surplus and Countries in Deficit using conditional DAX filters.

  - Applied logic to ensure only countries with positive surplus values were counted, aligning cards with table outputs.

- **Visualization Tools:** Interactive dashboard with bar charts, line charts, maps, and summary cards.
**[View My Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjliZWZkZjktNTVkNC00MzcyLWJjODEtZmE4ZDkyYjc4M2EyIiwidCI6ImZjY2Y0MmRmLTE2ZDktNGU4Ny1hNmUwLWU0OTYyMjAxN2Y3NCJ9)**

- **Metrics Analyzed:**

  - Net fiscal balance (aggregate deficit/surplus).

  - Largest deficit and surplus by country.

 - Number of countries in deficit vs. surplus.

 - Trends across years (2021–2025).


# Key Findings

- **Overall Position:** Africa’s combined fiscal balance is **($220.84M)**, showing a significant regional deficit.

- **Deficit Leaders:**

  - Nigeria dominates with **($199M)**, accounting for nearly **90%** of the total deficit.

  - Egypt ($16M) and South Africa **($4M)** also contribute notable shortfalls.

- **Surplus Contributors:**

  - Only South Africa **($77K)** and Ghana **($8K)** record meaningful surpluses.

  - Total surplus across all countries is just **$3.64M**, far below the deficit total.

- **Country Distribution:**

  - 9 countries are in deficit.

  - 2 countries show actual surpluses, underscoring widespread fiscal strain.

- **Yearly Trends:**

  - Fiscal balances remained flat from **2021–2023.**

  - Slight improvement in **2024.**

- Stronger recovery in **2025**, suggesting cautious optimism.

- **Geographic Spread:** Deficits are concentrated in larger economies, while surpluses are limited to smaller contributions.

# Recommendations
- Strengthen Fiscal Discipline in major economies like Nigeria and Egypt through tighter budget controls and improved revenue collection.

- Support Surplus Growth in South Africa and Ghana by diversifying revenue streams and investing in productive sectors.

- Enhance Regional Collaboration with stabilization funds and shared best practices to cushion against fiscal shocks.

# Conclusion
Africa’s fiscal outlook is heavily deficit‑driven, with Nigeria’s shortfall dominating the regional picture. Only **two countries** record meaningful surpluses, leaving most nations in deficit. While recent trends show slight improvement and signs of recovery by **2025**, fiscal sustainability remains fragile. Addressing large deficits in major economies and strengthening surpluses in smaller ones will be critical for long‑term stability across the continent.
