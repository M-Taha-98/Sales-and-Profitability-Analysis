<!-- 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-Taha-98/Sales-and-Profitability-Analysis/blob/main/Superstore_Sales_Analysis.ipynb)
-->

<div align="center">
  <table width="100%">
    <tr>
      <td align="center">
        <a href="https://colab.research.google.com/github/M-Taha-98/Sales-and-Profitability-Analysis/blob/main/Superstore_Sales_Analysis.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" />
        </a>
      </td>
      <td align="center">
        <a href="https://www.kaggle.com/code/mohammadtaha2024/superstore-sales-and-profitability-analysis/notebook?scriptVersionId=238158457">
          <img src="https://img.shields.io/badge/View%20Project%20on-Kaggle-20BEFF?logo=kaggle&logoColor=white" />
        </a>
      </td>
      <td align="center">
        <a href="https://www.linkedin.com/in/mohammadtaha-businessanalytics/">
          <img src="https://img.shields.io/badge/Visit%20Profile%20on-LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="Visit Profile on LinkedIn" />
        </a>
      </td>
    </tr>
  </table>
</div>

# Superstore Sales and Profitability Analysis
###### Comprehensive Project including Data Wrangling, Exploratory Analysis and Business Recommendations

![Data-driven-2](https://github.com/user-attachments/assets/d5c3c824-176c-4ca1-896e-e1a5edc4d4ea)
___
### Project Overview

The management team at a retail superstore chain is seeking a deeper understanding of its sales performance. This project investigates the impact of product categories, geographic regions, customer segments, and discounting strategies on overall profitability and performance.

### Data Source
The primary data used for this project is the "Superstore Dataset raw.csv" file which records each sale transaction within an order spanning from 2014 to 2017.

*Dataset Description*: 

The dataset contains retail transaction data with the following features:<br>

● Order Date: Date when the order was placed<br>
● Ship Date: Date when the product was shipped<br>
● Ship Mode: Shipping method used (e.g., Second Class, Standard Class)<br>
● Customer ID/Name: Information about the customer<br>
● Segment: Market segment (Consumer, Corporate, Home Office)<br>
● Region, State, City: Geographic location<br>
● Product ID/Name: Information about the product<br>
● Category / Sub-Category: Product hierarchy<br>
● Sales, Quantity, Discount, Profit: Financial details per transaction<br>

### Tools Used

- Python
- Libraries: Matplotlib, Seaborn, Numpy, Pandas

### Data Preparation/Cleaning
In the initial data preparation stage, following tasks are performed:
- Data loading and inspection
- Data validation 
- Data cleaning and formatting
- Handling missing and duplicate values
- Adding custom features

### Exploratory Analysis
In this stage, the data was explored to identify data’s structure, quality, and limitations:
- Data Profiling/ Initial Data Diagnostics/Data Summarization: descriptive statistics, cardinality check, data type inspection, correlation analysis.

### Data Analysis
The analysis step involved performing bivariate and multivariate analysis to explore how different features affect Sales/Profit as well as other features.

Few of the dimensions and relationships explored are:

- Which product categories and sub-categories are leading in revenue generation and those performing poorly.
- Impact of discount variability on margins across different product categories, and identifying profitable discount thresholds.
- Time series analysis: time-based trends in category level performance.
- Identifying customer segments that bring in the most volume and profit.
- Regional performance disparities.
- Analyzing performance of different ship modes and order delays to narrow logistical inefficiencies.

### Results/Findings
The insights are presented for key business areas:

- Seasonal Trend
- Overall Product Performance
- Product Portfolio Analysis
- Regional Analysis
- Customer Segmentation
- Discount Effectiveness
- Ship Mode and Delays Trend
  
### Recommendations
Based on the analysis, tailored actionable business recommendations are made categorized as follows:

- Product Strategy
- Regional Customer Growth and Retention
- Discount Optimization
- Addressing Logistical Shortcomings
  
### Limitations
The following assumptions and caveats are notified:

-  It is assumed that the discount value in each transaction record is applied to the total quantity purchased, not just to a single unit.
-  The absence of cost-related data—specifically unit cost price (COGS) and logistics costs limits the ability to fully explain certain observations.
 
### References

- [Stack Overflow](https://stackoverflow.com)
- [Matplotlib Library](https://matplotlib.org/)
- [Seaborn Library](https://seaborn.pydata.org/index.html)
___
<!-- 
[View on Kaggle](https://www.kaggle.com/code/mohammadtaha2024/superstore-sales-and-profitability-analysis/notebook?scriptVersionId=238158457)
-->

