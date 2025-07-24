# Integra Partners Automated Jobs for Tier 1

This repository contains Python scripts designed to automate routine IT Tier 1 operations at Integra Partners. These automations streamline processes, enhance data integrity, and reduce manual overhead—particularly across platforms like Essette, Salesforce, and Prism.

## 🧠 Overview
Each script is tailored to solve specific operational bottlenecks within Integra’s workflow. Common themes include:

- Data Cleaning and Standardization
Scripts that reformat HCPCS codes, align modifier columns, and consolidate inputs across multiple sources.

- Reconciliation Reports
Tools that compare datasets from different systems (e.g., Essette vs. Salesforce vs. Prism) to identify mismatches or incomplete updates.

- Excel Automation
Generation of clean, readable Excel reports from raw CSVs or exports from ticketing tools.

- Component Matching and Label Analysis
Analytical jobs that parse fields like Components and Labels from Jira exports to track ticket categories, volume by assignee, and more.


## 🔧  Key Projects
- Automated Report.ipynb
- HCPCS Formatting for Essette.ipynb
- HCPCS Formatting for Prism.ipynb
- HCPCS Formatting for Salesforce.ipynb


## 🧰  Tools Used
- Python (Pandas, datetime, collections)
- SQL Server
- Excel / CSV integrations