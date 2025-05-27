# 📊 Data Management I – Goal A & Goal B

### 👩‍💻 Student: Blessy Evangeline Aaron  
🎓 SRH University Heidelberg  
📁 Course: Data Management I (SS2024)

---

## 📌 Project Overview

This project focuses on **data quality assessment** and **intentional data uncleaning** for two distinct datasets:

- **Goal A:** Food Waste and Emissions Data  
- **Goal B:** Sales Data Analysis

Both goals simulate common data quality issues — such as missing values, duplicates, invalid entries, and formatting inconsistencies — for educational purposes.

---

## 🎯 Learning Objectives

- Understand and apply Data Quality Dimensions (DQDs)
- Demonstrate conformity, completeness, accuracy, validity, and uniqueness issues
- Practice uncleaning structured datasets for testing/teaching use cases
- Prepare data for ETL, SQL, and Tableau workflows

---

## 🧩 Included Files

### 📁 Goal A – Food Emissions & Waste
- `emmission_unclean.csv` – Dataset with emissions errors
- `Food_Emmisions.tfl` – Tableau flow file
- `Food_Emmisions.sql` – SQL script for database import
- `Food_Waste_Emissions.csv` – Clean food waste + emissions dataset
- `Foodwaste_unclean.csv` – Intentionally uncleaned data for Goal A
- `FoodWasteEmissionppt.pdf` – Summary presentation

### 📁 Goal B – Sales Data Simulation
- `Sales Data.csv` – Original clean dataset
- `Unclean_data.csv` – Intentionally corrupted data
- `Uncleaned_Data.tfl` – Tableau uncleaning workflow
- `Data Management/Goal B` – Goal B explanation document

---

## 🧪 Data Quality Modifications

| Dimension    | Example Issue (Goal B) |
|--------------|------------------------|
| **Conformity** | Mixed casing in City column |
| **Completeness** | ~40% of Sales column is empty |
| **Uniqueness** | Duplicate Product columns |
| **Validity** | ~30% of City replaced with "error" |
| **Accuracy** | Random text injected |
| **Consistency** | Mixed data types in columns |

Similar modifications are applied in **Goal A** datasets to simulate inconsistencies in food waste/emission records.

---

## 📂 Folder Summary

- `Goal A`: Focused on Food Emission data quality
- `Goal B`: Focused on Sales Data from Kaggle
- `*.csv`: Raw, clean, and intentionally uncleaned datasets
- `*.sql`: Scripts for relational schema loading
- `*.tfl`: Tableau flows showing uncleaning logic
- `*.pdf / .docx`: Documentation and presentation

---

## 🧠 Summary

This project illustrates how clean datasets can be intentionally uncleaned to simulate real-world data problems and train data practitioners in identifying and resolving data quality issues across multiple tools and formats.

---

