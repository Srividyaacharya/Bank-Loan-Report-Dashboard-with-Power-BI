## 🏦 Bank Loan Report Dashboard - Power BI Project

#### 📊 Dashboard View - [Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGQyMmU4ODItZGMyMi00NDQ4LTkyYTMtNWU4NjIxNDAzNDkyIiwidCI6IjU2MGY2MzA2LWZiZjItNGJhYy1hZTllLWQyMTQ4YzU5OTNiNyJ9)

## 📊 Project Overview

This project aims to provide financial institutions with data-driven insights into loan application trends, funding disbursement, repayment details, and borrower behavior. The interactive Power BI dashboard enables effective tracking of loan performance, risk assessment, and strategic decision-making.

## ✅ Objectives

- Analyze loan application trends, funded amounts, and repayment histories.
- Distinguish between Good Loans and Bad Loans using loan status.
- Assess key borrower characteristics like employment length and homeownership.
- Visualize data with meaningful, interactive Power BI charts.
- Support data-driven lending strategies and risk evaluation.

##  Key Performance Indicators (KPIs)

###  General KPIs
- **Total Loan Applications** (overall and MTD)
- **Total Funded Amount** (overall and MTD)
- **Total Amount Received** (overall and MTD)
- **Average Interest Rate** (overall and MTD)
- **Average Debt-to-Income (DTI) Ratio** (overall and MTD)

###  Good Loan KPIs
> *Loans with status "Fully Paid" or "Current"*
- Good Loan Application %
- Total Good Loan Applications
- Good Loan Funded Amount
- Good Loan Total Received Amount

###  Bad Loan KPIs
> *Loans with status "Charged Off"*
- Bad Loan Application %
- Total Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Total Received Amount


## Dashboard 1: Summary

**Purpose:** Track overall loan performance and monitor month-over-month changes.

**Visuals:**
- KPI cards (Total Loans, Funded Amount, Received Amount)
- MoM % change indicators
- Slicers for loan status, term, purpose, etc.
  
![image](https://github.com/user-attachments/assets/f48acce7-8088-4714-915c-9ab39903b4e3)

## Dashboard 2: Overview

**Purpose:** Provide visual trends and breakdowns.

**Visual Elements:**
- **Monthly Trends (Line Chart):** Total Applications, Funded Amount, Received Amount
- **State-wise Analysis (Filled Map):** Regional performance
- **Loan Term Analysis (Donut Chart):** 36 vs 60 months
- **Employment Length Analysis (Bar Chart):** By employment duration
- **Loan Purpose Breakdown (Bar Chart):** Top reasons for loans
- **Home Ownership (Tree Map):** Rent vs Own vs Mortgage

![image](https://github.com/user-attachments/assets/a3fdf6e2-5e8e-484e-ab46-cf8b40a01abc)

## Dashboard 3: Details

**Purpose:** Serve as a consolidated data view.

**Features:**
- Complete grid view by loan status
- Metrics: Funded amount, Received amount, Avg. interest rate, Avg. DTI
- Filters for drill-down by term, region, loan purpose

![image](https://github.com/user-attachments/assets/5c769cc5-cad1-4616-b4fb-515c65e32f3c)


## 🛠️ Methodology

1. **Data Collection** – Historical loan applications and repayment data
2. **Data Cleaning** – Handle nulls, correct data types, remove outliers
3. **EDA** – Identify trends, anomalies, and key borrower segments
4. **Data Modeling** – Build clean Power BI data model with relationships
5. **Dashboard Development** – Create interactive visuals using DAX & Power BI

## 📌 Conclusion

The **Bank Loan Report Dashboard** empowers financial stakeholders to:
- Monitor loan health and trends in real time
- Identify profitable and risky borrower segments
- Enhance lending policies with data-driven decisions

## 🧠 Tech Stack

- **Power BI**
- **DAX**
- **Excel / CSV**

