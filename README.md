# Southwest Airlines: Financial Performance Analysis (1995–2025)

## Project Overview

This project analyses the long-term financial performance of **Southwest Airlines Co.** using quarterly financial data from the **U.S. Department of Transportation's Bureau of Transportation Statistics (BTS)**.

The analysis examines operating revenue, operating expenses, and operating profit between 1995 and 2025. It also investigates profitability, year-over-year growth, and the relationship between revenue growth and expense growth.

The project was developed using **Python and pandas**, with data visualisations used to identify major financial trends.

##  Objectives

The main objectives of this project were to:

* Analyse Southwest Airlines' long-term operating revenue growth.
* Examine changes in operating expenses.
* Evaluate operating profit and operating profit margins.
* Identify periods of strong and weak financial performance.
* Compare annual revenue growth with expense growth.
* Examine the impact of the 2020 downturn and subsequent recovery.

##  Data Source

The data was obtained from the **U.S. Department of Transportation's Bureau of Transportation Statistics (BTS)**.

The dataset, *Airline Quarterly Financial Review_Main_Both*, contains quarterly financial information for major U.S. airlines and is derived from Department of Transportation Form 41 reports.

For this project, the data was filtered to **Southwest Airlines Co.** and quarterly observations from 1995 to 2025.

##  Tools & Technologies

* Python
* pandas
* Matplotlib
* Google Colab
* Jupyter Notebook

##  Methodology

The analysis followed these main steps:

1. Loaded the BTS airline financial dataset into Python.
2. Inspected the dataset structure and available variables.
3. Selected the relevant financial measures:

   * Operating Revenues
   * Operating Expenses
   * Operating Profit (Loss)
   * Operating Profit (Loss) to Operating Revenue
4. Filtered the data to Southwest Airlines Co.
5. Selected quarterly observations to avoid mixing quarterly and annual records.
6. Converted financial values into numerical format.
7. Aggregated quarterly observations to calculate annual revenue, expenses, and operating profit.
8. Calculated operating profit margins.
9. Calculated year-over-year revenue and expense growth.
10. Calculated a revenue–expense growth differential to compare changes in revenue with changes in operating expenses.
11. Created visualisations to identify major trends and periods of financial change.

##  Key Findings

### Profitability

Southwest Airlines achieved its highest annual operating profit margin in **2015 at 20.77%**.

In 2015, revenue increased by **6.53%**, while operating expenses decreased by **4.13%**. This resulted in a positive revenue–expense growth differential of **10.66 percentage points**.

The weakest year was **2020**, when operating profit fell to approximately **−$6.15 billion** and the operating profit margin reached **−68.01%**.

In 2020, revenue declined by **59.66%**, while operating expenses declined by only **21.92%**, highlighting the impact of a large fall in revenue when costs cannot decline at the same rate.

### Recovery

Following the 2020 downturn, Southwest returned to **positive operating profit in 2022**.

Although revenue recovered strongly after 2020, profitability recovered much more slowly. By 2025, operating revenue had reached approximately **$28.06 billion**, while the operating profit margin was approximately **1.53%**, substantially below the 2015 peak of 20.77%.

### Overall Insight

The analysis shows that **revenue growth alone does not determine profitability**. The relationship between revenue and operating expenses is also important.

In 2015, revenue growth exceeded expense growth, coinciding with a strong operating margin. In contrast, 2020 shows how a sharp decline in revenue, combined with a smaller decline in expenses, coincided with significant operating losses.

##  Visualisations

The project includes visualisations of:

* Annual Operating Revenue
* Annual Operating Profit
* Annual Operating Profit Margin
* Annual Revenue Growth
* Annual Operating Expense Growth
* Revenue–Expense Growth Differential

##  Limitations

* The dataset begins in **Q3 1995**, meaning 1995 is an incomplete year.
* Annual figures were calculated by aggregating quarterly observations.
* The analysis focuses on operating revenue, operating expenses, and operating profit rather than net income, cash flow, or share-price performance.
* The revenue–expense growth differential is a custom analytical measure and is not a standard financial ratio.
* The analysis identifies relationships and trends but does not establish causation.

##  Skills Demonstrated

**Python · pandas · Data Cleaning · Data Analysis · Financial Analysis · Data Visualisation · KPI Analysis · Year-over-Year Analysis · Business Interpretation**

##  Project Structure

```text
Southwest-Airlines-Financial-Analysis/
│
├── Southwest_Airlines_Financial_Analysis.ipynb
└── README.md
