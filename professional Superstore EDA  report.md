# SUPERSTORE SALES & PROFITABILITY ANALYSIS

### Exploratory Data Analysis | Business Insights Report

**Project Type:** Exploratory Data Analysis (EDA)
**Tools:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook
**Dataset:** Superstore Retail Dataset
**Prepared by:** Emmy El-Sawy

---

## 1. Executive Summary

This project analyzes retail transaction data to understand sales performance, profitability, and business trends. The analysis uses exploratory data analysis (EDA) to examine the dataset, investigate business questions, and identify patterns that can support better business decisions.

The dataset contains 9,994 rows and 21 columns, covering information about orders, customers, products, sales, discounts, and profit.

The analysis recorded approximately **$2.30 million in sales** and **$286,397 in total profit**, with an overall profit margin of **12.47%**.

Yearly results show that both sales and profit increased overall between 2014 and 2017. However, the profit margin did not increase continuously, demonstrating why revenue and profitability should be examined together.

## 2. Business Performance at a Glance

| Key Performance Indicator |        Result |
| ------------------------- | ------------: |
| Total Sales               | $2,297,200.86 |
| Total Profit              |   $286,397.02 |
| Overall Profit Margin     |        12.47% |
| Total Dataset Records     |         9,994 |
| Unique Orders             |         5,009 |
| Duplicate Rows            |             0 |

*Note: These figures are taken from the saved analysis outputs.*

### What the KPIs tell us

* **Sales:** The business generated approximately $2.30 million in recorded sales.
* **Profit:** The recorded transactions generated approximately $286,397 in profit.
* **Profit margin:** Approximately 12.47% of sales remained as profit, based on total profit divided by total sales.
* **Dataset quality:** The initial checks identified no duplicate rows, supporting a cleaner starting point for analysis.

## 3. Dataset Understanding and Quality

The first stage of the project focused on understanding the data before drawing business conclusions.

### Dataset profile

* 9,994 records
* 21 columns
* 5,009 unique orders
* No duplicate rows identified
* No missing values identified in the initial data-quality check

The dataset includes fields describing orders, customers, geographical regions, products, sales, discounts, quantities, and profit.

These variables allow the investigation of questions such as which products generate revenue, where profitability differs, and how business performance changes over time.

## 4. Yearly Sales and Profitability

The yearly analysis compares sales, profit, and profit margin from 2014 through 2017.

| Year | Total Sales | Total Profit | Profit Margin |
| ---- | ----------: | -----------: | ------------: |
| 2014 | $484,247.50 |   $49,543.97 |        10.23% |
| 2015 | $470,532.51 |   $61,618.60 |        13.10% |
| 2016 | $609,205.60 |   $81,795.17 |        13.43% |
| 2017 | $733,215.26 |   $93,439.27 |        12.74% |

### Key observations

**1. Sales increased overall.**
Sales rose from approximately $484,247 in 2014 to $733,215 in 2017. The lowest sales among these four years occurred in 2015.

**2. Annual profit increased throughout the period.**
Recorded profit grew from approximately $49,544 in 2014 to $93,439 in 2017.

**3. Profit margin peaked in 2016.**
The highest annual profit margin was approximately 13.43% in 2016. It then declined to approximately 12.74% in 2017.

### Business interpretation

The results suggest that revenue growth and profit growth should be monitored alongside profit margin. Although 2017 recorded the highest sales and profit, its margin was lower than in 2016.

A useful follow-up would be to investigate whether product mix, discounts, regional performance, or other factors contributed to this margin change. The current trend alone does not establish its cause.

## 5. Exploratory Analysis and Business Questions

The project contains 25 business analyses intended to explore different aspects of retail performance.

The analyses should be interpreted through the questions they answer and the insights supported by their actual results—not simply by the number of calculations or charts produced.

Areas of investigation include:

* Sales and profit performance
* Changes over time
* Product and category performance
* Customer and regional comparisons
* Discount-related patterns
* Profitability and business performance indicators

The purpose is to connect data analysis to practical business questions and identify patterns that may deserve further investigation.

*The detailed results for each business question should be taken directly from the completed Jupyter Notebook. This report does not assign findings to individual questions without verified supporting outputs.*

## 6. Tools and Methodology

### Tools used

* **Python:** General-purpose programming and analysis
* **Pandas:** Data inspection, filtering, grouping, and aggregation
* **NumPy:** Numerical operations
* **Matplotlib:** Visualizing patterns and comparisons
* **Jupyter Notebook:** Organizing code, outputs, and explanations

### Analysis workflow

1. Inspect the dataset structure and understand the meaning of its columns.
2. Assess data quality, including missing values and duplicate records.
3. Define business questions that can be answered using the available data.
4. Calculate relevant metrics and group results for comparisons.
5. Create visualizations to make patterns easier to interpret.
6. Explain findings in business terms and identify useful follow-up questions.

## 7. Recommendations for Further Investigation

Based on the verified overall and yearly results, the following are useful next steps:

**Monitor profit margin alongside sales.**
A sales increase does not necessarily mean the business is becoming more efficient or profitable.

**Investigate the 2017 margin decline.**
Compare product categories, discounts, regions, and other available variables to identify possible contributors.

**Evaluate performance at multiple levels.**
Total business figures are useful, but product-, customer-, and region-level comparisons may reveal patterns hidden by overall averages.

**Validate recommendations with detailed results.**
Any operational recommendation should be supported by the corresponding analysis, rather than inferred from an overall trend alone.

These are directions for further analysis, not claims that a particular factor caused the observed results.

## 8. Limitations

* This is a descriptive exploratory analysis; it does not establish causal relationships.
* The results depend on the accuracy and scope of the supplied dataset.
* The original CSV was not independently reprocessed while preparing this report; the headline metrics and yearly results were taken from saved analysis outputs.
* Detailed findings and recommendations should be checked against the corresponding notebook outputs before making business decisions.

## 9. Conclusion

This Superstore EDA project demonstrates how retail transaction data can be organized and examined to understand business performance.

The recorded results show approximately $2.30 million in sales, $286,397 in profit, and an overall profit margin of 12.47%. Between 2014 and 2017, annual sales and profit increased overall, while the profit margin peaked in 2016 and declined slightly in 2017.

The main takeaway is that **business performance should be evaluated using multiple indicators rather than sales alone**. Combining data-quality checks, business questions, numerical analysis, and visualizations helps turn raw transaction records into more useful business insights.


