# Interactive Ombudsman Performance & Policy Monitoring Dashboard

### 📌 Project Overview
This project focuses on the architecture and design of an executive business intelligence dashboard. It is built to monitor case resolution performance, analyze Turnaround Times (TAT), and track complaint volumes across 24 regional ombudsman offices. The visual outputs are designed to serve as direct inputs for high-level policy formulation.

### 🛠️ Tech Stack
- **Dashboard & Modeling:** Power BI (DAX)
- **Data ETL & Cleaning:** Advanced Excel (Power Query)
- **Analytical Metrics:** Descriptive Statistics

### 🚀 Key Deliverables & Architecture
- **Data Transformation (ETL):** Designed a Power Query workflow to ingest raw data dumps, remove duplicate complaint IDs, and merge monthly performance records.
- **Relational Data Modeling:** Created a star schema database model linking a central `Complaints Fact Table` to `Regional Offices` and `Calendar` dimension tables.
- **Advanced DAX Analytics:** Structured custom measures to track average resolution days and evaluate Month-on-Month percentage spikes in consumer grievances.
- **Geographical Hotspot Analysis:** Integrated map visualizations to highlight regions with high traffic or low resolution speeds.

### 📈 Current Status: Active Architecture Phase
- [x] Data model strategy and schema design.
- [x] Core DAX metric documentation.
- [ ] Front-end dashboard visual layout deployment.
