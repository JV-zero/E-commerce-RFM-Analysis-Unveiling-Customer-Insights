# E-commerce RFM Analysis: Unveiling Customer Insights

![RFM Analysis](https://www.example.com/RFM_image.png)

## Overview

In this project, I employed Python to conduct an RFM analysis for an e-commerce venture, aiming to unveil vital customer metrics—Recency, Frequency, and Monetary. By analyzing these metrics, we can enhance customer segmentation strategies and boost revenue through data-driven decision-making.

## Project Description

A company in the e-commerce sector hired us to gather Recency, Frequency, and Monetary (RFM) indicators for their customers. RFM stands for:

- **Recency:** Time since the customer's last purchase (in days)
- **Frequency:** Number of purchases made by the customer
- **Monetary:** Average order value for each customer, calculated as the mean of the total spent per order.

To achieve this, we received a dataset in CSV format containing customer purchase information. Our task was to build a Python script that generates an output CSV file containing only customer IDs and RFM metrics.

## Dataset Information

The dataset includes purchase information from an e-commerce platform operating in 37 countries. It comprises customer identifiers and purchase data.

## Tools and Technologies Used

- **Python:** Used for data analysis, manipulation, and visualization.
- **Pandas:** Utilized for data preprocessing and analysis.
- **NumPy:** Employed for numerical operations and calculations.
- **Matplotlib and Seaborn:** Utilized for data visualization.
- **Pandas-Profiling:** Used for automated exploratory data analysis (EDA).
- **Scikit-learn:** Employed for data preprocessing and model evaluation.

## Data Cleaning and Preprocessing

- Handled missing values using pandas methods.
- Removed rows with negative or zero values for quantity and unit price.
- Removed duplicate rows.
- Ensured correct data types for columns (e.g., CustomerID as integer, InvoiceDate as datetime).

## Exploratory Data Analysis (EDA)

- Conducted descriptive statistics and exploratory data analysis to understand the dataset.
- Visualized top countries by sales revenue and top-selling products.
- Analyzed total sales revenue per month to identify trends.

## RFM Calculation

- Calculated Recency, Frequency, and Monetary (RFM) metrics for each customer.
- RFM metrics were derived from the customer's last purchase date, the number of purchases, and the average order value.

## Conclusion

By conducting an RFM analysis, we gained valuable insights into customer behavior and preferences, allowing us to tailor marketing strategies and improve customer engagement. This project showcases the power of data analysis in driving business decisions and enhancing customer satisfaction.
