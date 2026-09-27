# Superstore Sales Analysis & EDA

A comprehensive Data Analysis and Exploratory Data Analysis (EDA) project built using **Python**, **Pandas**, 
and **Matplotlib**. This project analyzes retail data from the classic "Sample Superstore" dataset to uncover business 
insights, clean data, and visualize sales and profit performance.

---

## 🚀 Project Overview
The objective of this project is to process raw retail data, perform data cleaning
(handling duplicates and type casting), aggregate metrics by region, category, and state, 
and generate visual dashboards to help stakeholders make data-driven decisions.

---

## 🛠️ Tech Stack & Libraries
* **Python** (Programming Language)
* **Pandas** (Data Manipulation & Cleaning)
* **NumPy** (Numerical Computations)
* **Matplotlib** (Data Visualization & Subplots)

---

## 📈 Key Steps Performed in the Notebook

1. **Data Ingestion & Inspection:** 
   * Loaded the dataset using `latin1` encoding.
   * Inspected data types, column names, head, and tail rows to understand the schema.
2. **Data Cleaning:** 
   * Checked for null values and identified duplicate records.
   * Successfully dropped duplicate rows to ensure data integrity.
3. **Data Transformation & Aggregation:** 
   * Grouped data by `Ship Mode`, `Region`, `Segment`, and `State` to analyze performance metrics like Sales, Quantity, Profit, and Discounts.
   * Converted data types (`Sales` and `Profit`) for cleaner integer representation.
4. **Data Visualization & Dashboarding:** 
   * **Regional Sales:** Bar chart analyzing total sales across different regions.
   * **Category Quantity:** Horizontal bar chart representing product quantities.
   * **Top Profitable States:** Filtered for positive profits and visualized top-performing states using a pie chart.
   * **Multi-Panel Dashboard:** Combined charts using Matplotlib subplots (`plt.subplots`) for a clean executive summary view.
5. **Exporting Cleaned Data:** 
   * Exported the processed dataframe into a new CSV file (`cleaned_superstore_data.csv`) without the index column.

---

## 📊 Sample Visualizations / Insights
* **Top Sales Region:** Highlighted regional variations in performance.
* **Profitability Analysis:** Filtered out loss-making outliers to focus strictly on top-performing states by profit margin.

---

## 📂 File Structure
```text
├── sample_superstore_data.ipynb   # Main Jupyter Notebook containing the analysis
├── SampleSuperstore[1].csv        # Raw dataset
├── cleaned_superstore_data.csv    # Exported cleaned dataset
└── README.md                      # Project documentation
