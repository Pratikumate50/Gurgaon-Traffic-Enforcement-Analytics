# Gurgaon Urban Traffic Optimization & Enforcement Analytics Engine (Excel)

An end-to-end data analytics case study built using Microsoft Excel to analyze traffic infractions, public safety risks, and penalty collections across major transit corridors in Gurgaon, India.

##  Core Excel Analytical Implementations

*   **Data Cleaning & Imputation:** Resolved entry-level missing data errors in missing fine amounts by utilizing conditional logical functions (`IF`, `AND`, `VLOOKUP`) to map statutory penalty legal frameworks.
*   **Outlier & Typo Detection:** Deployed the statistical **1.5 IQR (Interquartile Range)** methodology in Excel using `QUARTILE.INC` functions to automatically isolate, flag, and cap manual logging typos (e.g., ₹29,000 entry mistakes).
*   **Behavioral Cohort Modeling:** Constructed multi-layered **Pivot Tables** to track repeat offender compliance trends, separating high-severity public hazards (DUIs, Speeding) from minor transit slips.
*   **Hotspot Geospatial Distribution:** Engineered an **Enforcement Priority Map** and Traffic Density Report utilizing advanced custom sorting and chart visual formatting to isolate top peak-demand violation zones.

##  Repository Structure
*   `data/gurgaon_traffic_violations_v2.xlsx` - Cleaned data tables with analytical formulas.
*   `README.md` - Executive portfolio brief and project overview.
