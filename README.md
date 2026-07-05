# Renewable-Energy-Consumption-Analytics-Dashboard

### Dashboard Link : https://public.tableau.com/views/RenewableEnergyConsumptionAnalyticsDashboard/RenewableEnergyConsumption?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Problem Statement

This dashboard provides comprehensive insights into renewable energy consumption and cost savings across different countries, regions, and renewable energy sources. It enables users to analyze monthly energy usage, compare regional performance, evaluate country-wise consumption patterns, and assess cost savings generated through renewable energy adoption.

The dashboard helps identify high-performing regions, compare renewable energy sources based on energy generation and financial savings, and supports data-driven decisions for sustainable energy planning.

Interactive visualizations allow users to explore renewable energy consumption trends across geographical regions and renewable energy sources.

---

## Technologies Used

- AWS S3
- Snowflake
- Tableau Desktop
- Tableau Public
- CSV Dataset

---

# Architecture

```text
CSV Dataset
      │
      ▼
AWS S3
      │
      ▼
Snowflake
      │
      ▼
Tableau Desktop
      │
      ▼
Calculated Fields
      │
      ▼
Interactive Dashboard
      │
      ▼
Tableau Public
```

---

## Steps Followed

- Step 1 : Uploaded the Renewable Energy Consumption dataset to an AWS S3 bucket.

- Step 2 : Connected Snowflake with AWS S3 using a Storage Integration and External Stage.

- Step 3 : Loaded the dataset from AWS S3 into Snowflake using the COPY INTO command.

- Step 4 : Connected Tableau Desktop to Snowflake and imported the required tables.

- Step 5 : Verified the imported data and ensured appropriate data types for analysis.

- Step 6 : Created visualizations to analyze Monthly Energy Usage (KWH) by Country, Region, and Energy Source.

- Step 7 : Built additional visualizations to compare Cost Savings (USD) by Country, Region, and Energy Source.

- Step 8 : Combined multiple worksheets into an interactive dashboard.

- Step 9 : Added labels, formatting, and dashboard layout enhancements for improved visualization.

- Step 10 : Published the dashboard to Tableau Public.

---

# Snapshot of Dashboard (Tableau Public)

<img width="1918" height="1078" alt="Screenshot 2026-07-06 012659" src="https://github.com/user-attachments/assets/c3518528-5b0a-4aa2-9001-d93d8b2221df" />

---

# Report Snapshot (Tableau Desktop)

## KWH by Country

<img width="1918" height="892" alt="Screenshot 2026-07-06 004624" src="https://github.com/user-attachments/assets/76ce923f-4fb4-49e4-b7e2-484024bf387f" />

---

## KWH by Region

<img width="1918" height="896" alt="Screenshot 2026-07-06 004613" src="https://github.com/user-attachments/assets/fa5fae13-6927-4e10-bb70-4db83de9cb76" />

---

## KWH by Energy Source

<img width="1918" height="898" alt="Screenshot 2026-07-06 004603" src="https://github.com/user-attachments/assets/a2d4c286-862f-4cf5-9c3f-b26d2178db88" />

---

## Cost Savings by Country

<img width="1918" height="892" alt="Screenshot 2026-07-06 004430" src="https://github.com/user-attachments/assets/51044180-f683-4429-b85b-e9deb24f2431" />

---

## Cost Savings by Region

<img width="1918" height="898" alt="Screenshot 2026-07-06 004527" src="https://github.com/user-attachments/assets/75df1fed-5618-4d7f-8fdf-b69085fab0f0" />


---

## Cost Savings by Energy Source

<img width="1882" height="887" alt="Screenshot 2026-07-06 004414" src="https://github.com/user-attachments/assets/0c5ff9f8-b986-4339-8d55-62879fc168dc" />


---


# Snapshot of Dashboard (Tableau Desktop)


<img width="1918" height="891" alt="Screenshot 2026-07-06 011429" src="https://github.com/user-attachments/assets/2dfd650f-1ae4-4def-aa68-fbe3c6454a20" />



---

# Report PDF

If you do not have Tableau Desktop installed, you can view the complete dashboard report in PDF format.

📄 **Renewable Energy Consumption Analytics Report**

[Download Report PDF](https://github.com/user-attachments/files/29679639/Renewable.Energy.Consumption.Analytics.Report.pdf)


---


# Insights

An interactive dashboard was created in Tableau Desktop and published to Tableau Public.

Following inferences can be drawn from the dashboard;

## [1] Monthly Energy Usage (KWH) Analysis

### KWH by Country

The dashboard analyzes Monthly Energy Usage (KWH) across different countries including:

- Argentina
- Australia
- Brazil
- Canada
- China
- France
- India
- Japan
- USA
- and other countries.

This visualization helps compare renewable energy consumption among countries and identify high energy-consuming nations.

---

### KWH by Region

Monthly Energy Usage (KWH) is analyzed across:

- Africa
- Asia
- Australia
- Europe
- North America
- South America

This enables comparison of renewable energy consumption across different geographical regions.

---

### KWH by Energy Source

The dashboard compares Monthly Energy Usage (KWH) across renewable energy sources including:

- Biomass
- Geothermal
- Hydro
- Solar
- Wind

This visualization helps identify the renewable energy source contributing the highest energy generation.

---

## [2] Cost Savings Analysis

### Cost Savings by Country

The dashboard compares Cost Savings (USD) generated by renewable energy adoption across multiple countries.

This helps evaluate the economic benefits achieved through renewable energy utilization.

---

### Cost Savings by Region

Cost Savings (USD) are analyzed across:

- Africa
- Asia
- Australia
- Europe
- North America
- South America

This enables regional comparison of financial savings resulting from renewable energy consumption.

---

### Cost Savings by Energy Source

The dashboard evaluates Cost Savings (USD) across renewable energy sources:

- Biomass
- Geothermal
- Hydro
- Solar
- Wind

This helps determine which renewable energy source provides the highest financial benefit.

---

## [3] Comparative Analysis

The dashboard enables users to compare:

- Energy Consumption across Countries
- Energy Consumption across Regions
- Energy Consumption by Energy Source
- Cost Savings across Countries
- Cost Savings across Regions
- Cost Savings by Energy Source

allowing users to identify consumption patterns and regional performance.

---

## [4] Business Insights

The dashboard helps organizations to:

- Monitor renewable energy consumption.
- Compare regional energy usage.
- Identify countries with high renewable energy adoption.
- Evaluate renewable energy sources based on energy generation.
- Analyze cost savings achieved through renewable energy.
- Support sustainable energy planning and decision-making.

The dashboard provides a comprehensive overview of renewable energy consumption and financial savings, enabling better analysis of renewable energy performance.

---

# Dashboard Features

The dashboard includes the following interactive features:

- Country-wise renewable energy consumption analysis.
- Region-wise energy usage comparison.
- Renewable energy source performance analysis.
- Cost Savings (USD) comparison across countries.
- Regional cost savings analysis.
- Renewable energy source cost savings comparison.
- Interactive dashboard combining multiple worksheets.
- Data labels for improved visualization and analysis.

---

# Business Value

This dashboard helps organizations to:

- Monitor renewable energy consumption across different countries.
- Compare renewable energy adoption across global regions.
- Evaluate the performance of renewable energy sources.
- Identify regions with higher renewable energy utilization.
- Analyze financial savings achieved through renewable energy adoption.
- Support sustainable energy planning and strategic decision-making.

---

# Files Included

This repository contains:

- Renewable Energy Consumption Analytics Dashboard.twbx
- Renewable Energy Consumption Analytics Report.pdf
- Snowflake SQL Scripts
- Dataset
- README.md

---

# How to Use

1. Clone this repository.

```bash
git clone https://github.com/uddipta089/Renewable_Energy_Consumption_Analytics
```

2. Upload the dataset to an AWS S3 bucket.

3. Create the required Snowflake objects (Database, Schema, Table, Storage Integration, Stage, and File Format).

4. Load the dataset from AWS S3 into Snowflake using the `COPY INTO` command.

5. Open the Tableau workbook (`.twbx`) in Tableau Desktop.

6. If required, reconnect the workbook to your Snowflake database.

7. Refresh the data source.

8. Explore the interactive dashboard and visualizations.
---

# Dashboard Link

Tableau Public

[Renewable Energy Consumption Analytics Dashboard](https://public.tableau.com/views/RenewableEnergyConsumptionAnalyticsDashboard/RenewableEnergyConsumption?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---


# Project Report

📄 **Download Dashboard Report**

[Renewable Energy Consumption Analytics Report (PDF)](https://github.com/user-attachments/files/29679523/Renewable.Energy.Consumption.Analytics.Report.pdf)


---

# GitHub Repository

[Renewable Energy Consumption Analytics](https://github.com/uddipta089/Renewable_Energy_Consumption_Analytics)

---

# Dataset

[Renewable Energy Consumption Dataset](https://github.com/user-attachments/files/29679506/Renewable_Energy_Usage_Sampled.csv)


---

# Author

**Uddipta Pathak**

LinkedIn:
[Uddipta Pathak](https://www.linkedin.com/in/uddipta-pathak-144272335/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BxGYUjRMARu6n%2BFP6WvNvHA%3D%3D)

GitHub:
[uddipta089](https://github.com/uddipta089)

Email:
<uddiptapathak0831@gmail.com>

---

# Acknowledgements

This project demonstrates practical implementation of:

- AWS S3
- Snowflake
- Tableau Desktop
- Tableau Public
- Data Visualization
- Dashboard Design
- Calculated Fields
- Business Intelligence

---

# Future Improvements

- Add interactive filters for Country, Region, and Energy Source.
- Develop trend analysis using time-series data.
- Integrate live renewable energy datasets.
- Include predictive analytics for future energy consumption.
- Enhance dashboard interactivity with advanced Tableau actions.
- Publish real-time dashboards using cloud data sources.

---
