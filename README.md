# sales-data-uncleaning-project
Simulated uncleaning of a cleaned sales dataset based on data quality dimensions such as conformity, completeness, validity, and uniqueness — for Data Management I project.

# 🧹 Sales Data Uncleaning Project – Data Management I

### 🎓 Course: Data Management I  
👩‍💻 Student: Blessy Evangeline Aaron  
📄 Dataset: Sales Data Analysis (Kaggle-based)

---

## 📌 Project Overview

This project explores the reverse process of data cleaning — simulating *unclean* data — using a previously cleaned sales dataset. The aim is to understand and demonstrate how various **data quality dimensions** (DQDs) can be intentionally distorted for academic and testing purposes.

---

## 🧪 Dataset Details

The original dataset includes:
- Order ID  
- Product  
- Quantity Ordered  
- Price Each  
- Order Date  
- Purchase Address  
- Month, Sales, City, Hour

---

## 🧬 Data Quality Dimensions Affected

| Dimension    | Change Introduced | Impact |
|--------------|-------------------|--------|
| **Conformity** | Changed "City" values to lowercase | Affects case sensitivity |
| **Validity**   | Replaced ~30% of "City" values with "error" | Introduces invalid entries |
| **Completeness** | Made ~40% of "Sales" values empty | Reduces completeness |
| **Uniqueness**  | Duplicated the "Product" column | Introduces redundancy |
| **Accuracy**    | Injected "RandomText" into 10% of rows | Introduces noise |
| **Consistency** | Mixed data types in columns | Disrupts uniformity |

---

## 🧾 Summary of Changes

- Introduced duplicates  
- Replaced values with `NULL`  
- Added random characters  
- Created case inconsistencies  
- Mixed data types across columns

---

## 📁 Files Included

- `Uncleaned_Data.tfl` – Raw modified dataset
- `Goal B.docx` – Documentation explaining uncleaning steps

---

## 🎯 Learning Objective

This exercise helps reinforce:
- Understanding of how data quality issues arise
- Practical knowledge of DQDs: completeness, conformity, uniqueness, accuracy
- The importance of clean data in analytics pipelines

---

## ✅ Status

> 📂 All modifications are intentional and documented for academic demonstration.

---

