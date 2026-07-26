# 📊 Power Query & ETL Portfolio

This repository contains practical hands-on projects, dataset transformations, and automated ETL (Extract, Transform, Load) workflows built using **Microsoft Power Query in Excel 365 Desktop**.

---

## 🏆 Featured Capstone Project: End-to-End Sales Pipeline

* **File**: `PQ_Capstone_Project.xlsx`
* **Objective**: Automate the consolidation and cleaning of raw sales, customer, and product datasets into a unified analytical data model (`Sales_Master_Enriched`).
* **Key Transformations**:
  * **Customer Data**: Split `Full_Name` and `Location_Code`, generated custom `Country_Group` logic via `Conditional Column`.
  * **Sales Data**: Handled date conversion errors (`Replace Errors` $\rightarrow$ `null`), calculated delivery duration (`Subtract Days`), and computed total revenue (`Total_Revenue`).
  * **Data Modeling**: Merged 3 raw sources using `Merge Queries as New` into a clean star-schema friendly dataset.

---

## 📁 Practice Exercises

| File | Description | Key Tools Used |
| :--- | :--- | :--- |
| `PQ_Lesson11_Practice.xlsx` | Text transformation & customer segmentation | `Split Column`, `Merge Columns`, `Conditional Column` |
| `PQ_Lesson12_Practice.xlsx` | Reshaping wide quarterly sales reports into tall tables | `Unpivot Other Columns`, `Pivot Column` |
| `PQ_Lesson13_Practice.xlsx` | Handling date calculations and string-to-date conversion errors | `Replace Errors`, `Subtract Days` |
