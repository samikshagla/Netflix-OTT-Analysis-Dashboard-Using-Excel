# Netflix OTT Content Analysis (Excel + Power Query)

## 📌 Project Overview
This project analyzes Netflix OTT content data to understand content distribution, genre trends, audience targeting, and release patterns.  
The analysis was performed using **Excel and Power Query**, focusing on real-world data cleaning, transformation, and dashboard-driven insights.

---

## 🎯 Objective
To analyze Netflix’s content library and identify:
- Content type distribution (Movies vs TV Shows)
- Popular genres
- Audience targeting based on ratings
- Release trends over time
- Data quality gaps in OTT metadata

---

## 🛠 Tools & Technologies
- **Microsoft Excel**
- **Power Query** (ETL & data cleaning)
- **XLOOKUP**
- **Pivot Tables**
- **Charts & Slicers**
- **Excel Dashboards**

---

## 📂 Dataset
- **Source:** Netflix Titles Dataset (CSV)
- **Fields include:**  
  - Title type (Movie / TV Show)  
  - Genre  
  - Country  
  - Rating  
  - Release year  
  - Date added  

The dataset was loaded and cleaned using **Power Query** to simulate a real analyst workflow.

---

## 🔄 Data Preparation (Power Query)
- Promoted headers and fixed data types
- Removed irrelevant text-heavy columns
- Handled missing values (e.g., country → `Unknown`)
- Split genre column and extracted primary genre
- Extracted year from date fields
- Created clean, analysis-ready dataset

---

## 🧠 Feature Engineering
- Created **Primary Genre** column
- Mapped content ratings to **Audience Groups** using **XLOOKUP**
  - Kids
  - Teen
  - Adult
  - Not Rated

This step simulates a **lookup / join operation**, similar to SQL joins.

---

## 📊 Analysis Performed
- Movies vs TV Shows distribution
- Genre-wise content analysis
- Audience group distribution
- Content release trends over years
- Country-wise content contribution

Analysis was done using **Pivot Tables and Excel formulas**.

---

## 📈 Dashboard
An interactive dashboard was built to summarize insights, including:
- KPIs (Total Titles, % Movies, Top Genre, Top Audience Group)
- Genre distribution chart
- Audience group distribution
- Content release trend
- Filters for content type and audience group

---

## 🔍 Key Insights
- Movies dominate Netflix’s content library.
- Drama and Comedy are the most common genres.
- Adult-targeted content forms the majority of titles.
- Content production increased rapidly after 2015.
- Country metadata is missing for a significant portion of content.

---

## 📁 Project Structure
OTT_Content_Analysis.xlsx
│
├── Cleaned_Data
├── Reference_Data
├── Analysis
├── Pivot_Tables
├── Dashboard
└── Insights

---

## 🏁 Conclusion
This project demonstrates how **Excel and Power Query** can be used for end-to-end data analysis, from raw data ingestion to dashboard-driven insights.  
It reflects practical data analyst skills such as data cleaning, enrichment, summarization, and business interpretation.

---

## 📎 Author
**Samiksha Chauhan**  
Aspiring Data Analyst / Data Scientist  
