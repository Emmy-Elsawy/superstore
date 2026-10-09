# Superstore Sales & Profitability Analysis

## 📌 Project Overview

This project explores a Superstore retail dataset using **Exploratory Data Analysis (EDA)** to understand sales performance, profitability, and business trends.

The goal is to go beyond simple calculations and answer meaningful business questions that can help a business owner understand performance and identify areas that may need further investigation.

## 🎯 Project Objectives

* Understand the dataset structure and assess its quality.
* Analyze sales and profit trends over time.
* Explore business performance through summaries and visualizations.
* Investigate business questions related to products, customers, regions, discounts, and profitability.
* Translate analytical results into clear, meaningful business insights.

## 📊 Dataset Overview

The dataset contains **9,994 rows and 21 columns**, covering information about orders, customers, products, sales, discounts, and profit.

| Dataset Metric | Value |
| -------------- | ----: |
| Total rows     | 9,994 |
| Total columns  |    21 |
| Unique orders  | 5,009 |
| Duplicate rows |     0 |

## 💡 Key Business Results

The following figures are based on the saved analysis outputs.

| KPI                   |        Result |
| --------------------- | ------------: |
| Total Sales           | $2,297,200.86 |
| Total Profit          |   $286,397.02 |
| Overall Profit Margin |        12.47% |
| Unique Orders         |         5,009 |

### 📈 Yearly Sales and Profit Trends

| Year |       Sales |     Profit | Profit Margin |
| ---- | ----------: | ---------: | ------------: |
| 2014 | $484,247.50 | $49,543.97 |        10.23% |
| 2015 | $470,532.51 | $61,618.60 |        13.10% |
| 2016 | $609,205.60 | $81,795.17 |        13.43% |
| 2017 | $733,215.26 | $93,439.27 |        12.74% |

**Initial observations:**

* Sales increased overall between 2014 and 2017.
* Annual profit also increased throughout the period.
* Profit margin reached its highest level in 2016 before decreasing slightly in 2017.
* Revenue growth and profitability should be examined together because higher sales do not automatically mean a higher profit margin.

These observations describe patterns in the dataset; they do not establish the causes of those patterns.

## 🔍 Analysis Approach

The project follows an exploratory data analysis workflow:

1. **Data Understanding** — identify what each row represents and understand the available columns.
2. **Data Quality Assessment** — inspect missing values, duplicate records, and unique identifiers.
3. **Exploratory Analysis** — investigate sales, profit, discounts, products, customers, regions, and time-based trends.
4. **Data Visualization** — use charts to make patterns and comparisons easier to understand.
5. **Business Interpretation** — connect the results to business questions and explain what the findings may mean.
6. **Conclusion** — summarize key findings and identify areas for further investigation.

## 🛠️ Tools and Technologies

* **Python** — analysis and calculations
* **Pandas** — data manipulation and analysis
* **NumPy** — numerical operations
* **Matplotlib** — data visualization
* **Jupyter Notebook** — interactive analysis and documentation

## 📁 Project Files

The project can be organized using the following structure:

```text
Superstore-EDA/
│
├── README.md
├── Superstore_EDA_Polished.ipynb
└── Superstore_EDA_Business_Report.pdf
```

* `README.md` — project overview, methodology, and selected findings.
* `Superstore_EDA_Polished.ipynb` — notebook containing the analysis, code, and saved outputs.
* `Superstore_EDA_Business_Report.pdf` — concise business-style report presenting selected results.

The dataset CSV is not included in this project structure and must be supplied separately to rerun the analysis.

## 🚀 How to Run the Project

### 1. Install Python

Install Python if it is not already available on your computer.

### 2. Install the Required Libraries

Open your terminal and run:

```bash
pip install pandas numpy matplotlib notebook
```

### 3. Prepare the Dataset

Place the Superstore CSV file in your project folder, or note its full file path.

### 4. Update the File Path

Open the notebook and update its data-loading cell to match the location of your CSV file. For example:

```python
import pandas as pd

data = pd.read_csv("your/path/to/Sample - Superstore.csv")
```

Replace the example path with the actual path to your dataset.

### 5. Run the Notebook

Open the notebook in Jupyter Notebook or VS Code and run the cells from top to bottom.

## ⚠️ Limitations

* The original dataset CSV is not included in this project.
* The headline figures and yearly results presented here come from saved analysis outputs and have not been independently recalculated from the original CSV in preparing this README.
* Findings may differ if a different version of the dataset is used.
* The analysis identifies descriptive patterns; additional investigation is needed before drawing causal conclusions.

## 👩‍💻 Author

**Emmy El-Sawy**
