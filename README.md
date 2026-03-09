# Data Cleaning & Standardization: Property/Customer Dataset (Excel)

## 📌 Project Overview
This project focuses on the "Data Cleaning" phase of the data lifecycle. Using a raw dataset with over 5,000 rows of inconsistent entries, I performed a systematic cleanup to ensure data integrity and structural uniformity for downstream business reporting.

## 🛠️ Technical Workflow & Operations
I implemented a multi-step standardization process to transform the raw data into a "Single Source of Truth":

* **Deduplication:** Utilized the `Remove Duplicates` tool to identify and eliminate redundant records, ensuring each entry is unique.
* **Structural Standardization:** Used `Find & Replace` to fix inconsistent naming conventions (e.g., standardizing "Y/N" to "Yes/No") across the entire dataset.
* **Whitespace Management:** Applied the `TRIM` function and manual audits to remove leading and trailing spaces that cause VLOOKUP/Filter errors.
* **Data Type Alignment:** Standardized "Date" and "Currency" formats to ensure chronological sorting and mathematical accuracy.
* **Null Value Handling:** Filtered for blank/null entries and applied logical rules to either populate or remove incomplete data points.

## ❓ Business Problem Solved
Raw data often contains "noise" that skews final analysis. By performing this cleanup, I reduced the risk of reporting errors (such as double-counting sales) and ensured the dataset is 100% ready for Pivot Table analysis and Power BI visualization.

## 📊 Project Outcome
* **Initial State:** Messy, inconsistent dataset with duplicate entries and varied formats.
* **Final State:** A verified, standardized "Master Dataset" with 100% data integrity.

---
*Developed as a foundational portfolio project demonstrating attention to detail and data quality control.*
