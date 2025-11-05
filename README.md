# Recruitment-Hiring-Trends-Dashboard

 **Short Description**

This project was developed for a recruitment and selection firm managing a surge of data-related job inquiries from various sources. The data, received in inconsistent formats (both Normalised and Centralised), was cleaned, structured, and consolidated into a unified database.
The goal: to deliver a performance-optimized Power BI dashboard that enables the client to analyze hiring trends, job types, and skill demand across years and geographies.

**Tech Stack**

The solution was built using the following tools and technologies:

-Microsoft Power BI Desktop – Data modeling, visualization, and dashboard creation.
-Power Query (M Language) – Data extraction, transformation, and cleaning from multiple sources.
-DAX (Data Analysis Expressions) – For calculated columns, measures, and time intelligence.
-SQL / Excel / CSV – Source data files from multiple systems (structured + unstructured).
-Database Design – Created normalized relational structure before consolidation.
-Power BI Optimization Techniques – Query folding, star schema modeling, incremental refresh, and data reduction.

**Data Flow: SQL Server → Power BI**
📂 Raw Data Sources (CSV / Excel / APIs / Web Scraping)
        │
        ▼
🧹 Data Cleaning & Integration (SQL Server / Python ETL)
        │
        ▼
🗄️ SQL Server Database (Normalized + Consolidated Tables)
        │
        ▼
🔗 Power BI Data Connection (Direct Query / Import)
        │
        ▼
🧠 Data Modelling in Power BI (Relationships, DAX, Measures)
        │
        ▼
📊 Power BI Reports & Dashboards (Recruitment & Hiring Trends)


**Data Structure Challenges:**

-Mix of normalised and centralised data formats.
-Missing or inconsistent values in job details.
-Text-heavy unstructured columns (e.g., long job descriptions).
-Poorly defined relationships between multiple tables.
-Solution Approach:
-Standardized all datasets into consistent field names and formats.
-Designed relational tables and linked them via primary and foreign keys.

Created a final consolidated schema in Power BI following the model below:

Column Name	Description
**Job_id**	Unique identifier for each job posting.
**Job_title**	Name/title of the job position.
**Job_field**	Domain of the job (e.g., Data Science, Data Engineering).
**Company_name**	Organization offering the job.
**Job_location**	City/state or remote status of the role.
**Job_posting_date**	Original date of the job posting.
**Job_level**	Experience level (Entry / Mid / Senior).
**Job_type**	On-site, Hybrid, or Remote.
**Job_employment_type**	Permanent, Contractual, or Internship.
**Job_skills**	Required or preferred skills for the role.
**Summary**	Brief job description or overview.


**Features / Highlights**
  **Business Problem**

The recruitment firm struggled with messy, fragmented, and large datasets.
Inconsistent data sources led to unreliable insights.
The volume (7 lakh+ rows) caused report lag and inefficiency.
Unstructured job descriptions made information extraction complex.

**Project Goals**

To build an integrated, performance-optimized Power BI solution that:
Cleans and consolidates all job-related data into one unified schema.
Enables visual insights into hiring trends, job types, and skill demand.
Supports strategic decision-making through automated, data-driven analytics.

**Dashboard Preview**
![Dashboard Snapshot](https://raw.githubusercontent.com/the-bipul-kumar/Recruitment-Hiring-Trends-Dashboard/main/snapshot1.png)
![Dasboard Snapshot](https://github.com/the-bipul-kumar/Recruitment-Hiring-Trends-Dashboard/blob/main/snapshot2.png)
