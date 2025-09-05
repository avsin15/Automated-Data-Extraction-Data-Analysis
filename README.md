# Automated-Data-Extraction-Data-Analysis

Automated Daily Sales Report Pipeline-
This project automates the entire workflow of extracting, storing, and analysing daily sales reports received via Gmail. The pipeline leverages n8n, Supabase, and QuadraticHQ to seamlessly handle data ingestion, database management, analysis, and visualisation—eliminating manual effort and ensuring consistent, accurate reporting.


✨ Features:
-Email Integration: Automatically fetch daily sales reports from Gmail.

-Data Extraction: Parse and extract records from CSV attachments.

-Database Management: Insert and update sales data into PostgreSQL hosted on Supabase.

-Automated Analytics:

-Data cleaning, modelling, and exchange rate conversions.

-Generation of KPIs and performance metrics.

-Interactive dashboards and visualisations powered by QuadraticHQ.

-Scalable & Modular: Easily extend workflows, add new data sources, or adapt reporting needs.



🛠️ Technologies Used:

n8n – Workflow automation for email parsing and data pipeline orchestration.

Supabase – PostgreSQL backend for structured data storage and management.

QuadraticHQ – AI-powered data analysis, modelling, and visualisation.


📂 Workflow Overview:
n8n Workflow:
Connects to Gmail → Reads daily sales report emails → Extracts CSV data.
Inserts or updates rows in Postgres (Supabase) tables.

Supabase:
Acts as the central database storing structured sales data.
Provides secure, scalable, and queryable data access.

QuadraticHQ:
Connects directly to Supabase.
Performs analysis, cleaning, modelling, KPI formulation, and visualisation.
Delivers AI-enhanced insights for faster decision-making.


🚀 Benefits
-Saves time by eliminating manual data entry.

-Reduces human errors in reporting.

-Enables real-time insights and automated KPI tracking.

-Provides a robust, scalable solution for sales reporting workflows.
