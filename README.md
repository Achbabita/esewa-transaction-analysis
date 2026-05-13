# eSewa-transaction-analysis

## 📸 Dashboard Preview

<img width="892" height="488" alt="image" src="https://github.com/user-attachments/assets/ff7f5544-928a-41dc-8a4a-cfdb110e0291" />

##  Project Overview
This project analyzes dummy Esewa transaction data using Python and Power BI. The objective was to perform data cleaning, exploratory data analysis (EDA), visualization, and build an interactive dashboard to uncover transaction trends, payment behavior, and business insights.

---

##  Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

## 📂 Dataset Information
The dataset contains dummy Esewa transaction records with the following columns:

- Transaction_ID
- User_ID
- Transaction_Date
- Transaction_Type
- Amount_NPR
- Payment_Method
- Transaction_Status
- Merchant_Category
- City
- Device_Type

---

##  Data Cleaning
The following preprocessing steps were performed using Pandas:

- Removed duplicate records
- Handled missing values
- Converted date columns into datetime format
- Corrected data types
- Standardized categorical values
- Created new features:
  - Month
  - Day
  - Day Name
  - Year

---

##  Exploratory Data Analysis (EDA)

Performed analysis on:

- Transaction success and failure rate
- Monthly revenue trends
- Payment method usage
- City-wise transaction distribution
- Merchant category revenue
- Device usage behavior

Visualizations were created using Matplotlib and Seaborn.

---

##  Power BI Dashboard

The interactive Power BI dashboard includes:

- KPI cards
- Revenue trend analysis
- Payment method analysis
- Transaction status distribution
- Merchant category insights
- City-wise transaction analysis
- Interactive slicers and filters

---

## 📸 Dashboard Preview

<img src="images/dashboard.png" width="900">

---

##  Key Insights

- Most transactions were successfully completed.
- Wallet balance was the most frequently used payment method.
- Certain cities generated higher transaction volume.
- Merchant categories showed different revenue contributions.
- Transaction activity varied across months.
