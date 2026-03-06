# The-Price-of-Art
When creativity meets the market: a data exploration of art as an asset.
# The Price of Art: Data Cleaning & Forensic Audit 🎨📊

## Project Overview
This project focuses on the end-to-end data transformation and cleaning of a specialized art market dataset. The primary objective was to convert raw, heterogeneous auction data into a high-integrity "Golden Record" optimized for Business Intelligence and market trend analysis.

## Data Cleaning Methodology
A rigorous **Deep Forensic Audit** was performed to ensure 100% data density. Key interventions include:

* **Chronological Standardization:** Extracted and validated numeric years from complex string formats, creating a clean `year_numeric` attribute.
* **Categorical Imputation:** Performed manual research for missing values in `period` and `movement` columns based on artist biographies and historical context.
* **Boolean Transformation:** Standardized over 390 unique signature descriptions into a binary `is_signed` (Yes/No) feature.
* **Condition Grouping:** Simplified fragmented condition reports into logical categories (Excellent, Good, Fair, etc.) for streamlined filtering.

## Final Dataset Specifications
* **Observations:** 754
* **Attributes:** 9 standardized columns.
* **Data Integrity:** 100% completion rate (zero null values).

## Visualizations & Insights
The exploratory data analysis and visual storytelling phase is currently being conducted using **Power BI**. This phase explores price correlations with artistic movements, the impact of artist signatures on valuation, and chronological market trends.

> **Note:** The link to the interactive Power BI Dashboard will be added here upon completion of the visualization phase.

---
*Status: Data Cleaning Phase - Completed | Visualization Phase - In Progress*