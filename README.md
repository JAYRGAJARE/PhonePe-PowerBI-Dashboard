# 📱 PhonePe Payment Insights Dashboard — Power BI

An interactive **PhonePe-inspired payment analytics dashboard** built using **Microsoft Power BI**.  
The project analyzes transaction volume, transaction value, payment success, users, services, age segments, and weekday/weekend usage.

> **Note:** This is a data analytics portfolio project and is not an official PhonePe product or dashboard.

## 📊 Dashboard Preview

![PhonePe Power BI Dashboard](Screenshots/PhonePe_Dashboard.png)

## 🎯 Project Objective

The objective of this project is to transform transaction-level payment data into an interactive dashboard that helps answer questions such as:

- How many transactions were processed?
- What is the total transaction value?
- What percentage of transactions were successful?
- Which service generated the highest transaction value?
- Which users contributed the highest transaction value?
- How does transaction activity change over time?
- How does usage vary across age segments?
- Is usage higher on weekdays or weekends?

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query** — data loading and transformation
- **DAX** — KPI and analytical calculations
- **Microsoft Excel / CSV** — source data
- **Data Visualization** — interactive charts, slicers and KPI cards

## 📁 Project Structure

```text
PhonePe-PowerBI-Dashboard/
│
├── README.md
├── Dataset/
│   ├── PhonePe-Final-Dataset.xlsx
│   ├── All_Users.csv
│   └── All_Transactions.csv
│
├── PowerBI/
│   └── Phone_Pay_Analysis.pbix
│
├── Screenshots/
│   └── PhonePe_Dashboard.png
│
└── Documentation/
    ├── Project_Documentation.md
    └── DAX_Measures.md
```

## 📌 Dataset

The dataset contains two main tables:

### All_Users

| Column | Description |
|---|---|
| User_ID | Unique user identifier |
| Name | User name |
| Age | User age |
| Join_Date | Date the user joined |

### All_Transactions

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Amount | Transaction amount |
| User_ID | User identifier |
| Service | Payment service |
| Service Type | Specific service/category |
| Payment_Status | Transaction status |
| Reason | Status/reason information |
| Date | Transaction date |

## 📈 Dashboard KPIs

The dashboard presents:

- **Total Transactions:** 300K
- **Total Transaction Value:** ₹3.47B
- **Unique Users:** 108K
- **Successful Rate:** 96.00%

## 📊 Dashboard Visuals

### Transactions Over Time
Shows monthly transaction activity and helps identify changes in transaction volume/value across the year.

### Age Segment Contribution
Shows contribution from different age groups such as Young, Mid_Life, Working and Senior.

### Service Transaction Value Analysis
Compares transaction value across services including Loans, Insurance, Money Transfer and Recharge/Bills.

### Top 5 Users
Highlights the users with the highest transaction value.

### Weekday vs Weekend Usage
Compares transaction activity between weekdays and weekends.

### Insights Panel
Summarizes key findings from the dashboard, including the successful transaction rate and highest-value service.

## 🔎 Key Findings from the Dashboard

- The dataset contains **300,000 transactions**.
- Total transaction value is approximately **₹3.47 billion**.
- There are approximately **108K unique users**.
- The dashboard reports a **96% successful transaction rate**.
- **Loans** have the highest transaction value among the displayed services.
- Weekday usage is higher than weekend usage in the dashboard.
- Age segments provide an additional view of customer contribution.

## 💡 Business Questions Answered

1. Which service generates the highest transaction value?
2. What is the overall payment success rate?
3. Which users have the highest transaction value?
4. How does transaction activity change month by month?
5. Which age segment contributes the most?
6. What is the weekday vs weekend usage pattern?
7. How do payment statuses affect overall transaction performance?

## 🚀 How to Open the Project

1. Download or clone this repository.
2. Open `PowerBI/Phone_Pay_Analysis.pbix` using **Power BI Desktop**.
3. If Power BI asks for the data source, update the dataset path to the file inside the `Dataset` folder.
4. Refresh the data if required.
5. Use the Month and Payment Status filters to explore the dashboard.

## 👨‍💻 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Business Insight Generation
- Power BI Reporting

## 📌 Portfolio Use

This project was created as a **Data Analytics / Power BI portfolio project** to demonstrate practical dashboard development and business-oriented data analysis.

## 👤 Author

**Jay Gajare**

Skills: `Power BI` `SQL` `Python` `Pandas` `Excel` `Machine Learning`

