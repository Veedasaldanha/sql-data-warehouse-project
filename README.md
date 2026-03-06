# Data Warehouse and Analytics Project

Welcome to the ** Data Warehouse and Analytics Project ** repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
	- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
	- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
	- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
	- **Scope**: Focus on the latest dataset only; historization of data is not required.
	- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

## Data Architecture

The Data Architecture for this project follows Medallion Architecture Bronze, Silver and Gold Layers:
<img width="771" height="721" alt="Data_architecture" src="https://github.com/user-attachments/assets/13afcd43-d6fd-4d25-a77e-f519de17299c" />

1. Bronze Layer: Stores raw data ingested directly from source systems with minimal or no transformation. It acts as the initial landing zone for preserving the original data.
2. Silver Layer: Contains cleaned, standardized, and transformed data derived from the Bronze layer. This layer improves data quality by removing duplicates, correcting formats, and applying business rules.
3. Gold Layer: Houses Business- Ready Data modeled into star schema required for reporting and Analytics.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

⸻

## 🌟 About Me

Hi there! I’m Veeda Saldanha. I’m an Intern passionate about Data Science, Data Warehousing, and Analytics. I enjoy teaching, building practical projects, and sharing knowledge in a simple and engaging way.
