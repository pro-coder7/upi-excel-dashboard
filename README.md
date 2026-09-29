# 🔗 Project Links

**GitHub Repository:**  
https://github.com/pro-coder7/upi-excel-dashboard.git

**Excel Dashboard:**  
https://docs.google.com/spreadsheets/d/1AftO36b4CUWucLkwL12E_c-9gTAnCr2f/edit?usp=drive_link&ouid=106864234829090533893&rtpof=true&sd=true

**LinkedIn:**  
www.linkedin.com/in/sanchitgawande



# UPI Transaction Analysis Dashboard 📊

## 📌 Project Overview

The **UPI Transaction Analysis Dashboard** is an interactive Excel-based data analytics project designed to analyze and visualize UPI transaction data.

The project uses **Microsoft Excel** to transform raw UPI transaction data into meaningful business insights through:

* Data analysis
* Pivot Tables
* Pivot Charts
* Interactive dashboard
* Failure reason analysis
* Cashback analysis
* Transaction fee analysis
* Customer and demographic analysis
* Time-based transaction analysis
* Key insights and findings

The dashboard helps understand **transaction volume, transaction value, UPI application performance, customer demographics, transaction failures, cashback distribution, transaction fees, and transaction patterns over time**.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze UPI transaction data using Microsoft Excel.
2. Understand transaction volume and transaction value.
3. Compare different UPI applications.
4. Identify transaction patterns based on date and time.
5. Analyze transaction failures and their reasons.
6. Analyze cashback distribution across UPI applications.
7. Analyze transaction fees.
8. Study customer demographics such as age group and gender.
9. Create an interactive and visually appealing Excel dashboard.
10. Generate meaningful business insights from the data.

---

## 🛠️ Tools & Technologies Used

| Tool / Technology       | Purpose                                       |
| ----------------------- | --------------------------------------------- |
| Microsoft Excel         | Data analysis and dashboard development       |
| Excel Pivot Tables      | Data summarization                            |
| Excel Pivot Charts      | Data visualization                            |
| Excel Formulas          | Data calculations and analysis                |
| Excel Slicers           | Interactive filtering                         |
| Conditional Formatting  | Highlighting important values                 |
| Charts & Visualizations | Presenting insights                           |
| GitHub                  | Project version control and portfolio hosting |

---

## 📂 Dataset Information

The project contains a large UPI transaction dataset.

The main raw data sheet is:

**`raw_data_upi`**

The dataset contains approximately **502,887 transaction records** and **25 columns**.

### Important Dataset Columns

Some of the important fields include:

* Transaction ID
* Transaction Date
* Day
* Transaction Time
* Hour
* UPI App
* Customer ID
* Age Group
* Gender
* Country
* Transaction Amount
* Transaction Status
* Failure Reason
* Cashback
* Transaction Fee

These fields are used to analyze transaction behavior and generate dashboard metrics.

---

# 📊 Project Structure

The Excel workbook contains the following sheets:

### 1. Home

The **Home** sheet acts as the starting/navigation page of the workbook.

It provides access to the major sections of the project.

---

### 2. Pivot _table & Charts

This sheet contains Pivot Table-based analysis and supporting charts.

It is used to summarize large amounts of transaction data into useful metrics such as:

* Number of transactions
* Total transaction amount
* Total cashback
* Transaction trends
* UPI application performance
* Other analytical dimensions

The dataset contains approximately:

**502,887 transactions**

and a total transaction amount of approximately:

**₹442.48 Million**

---

### 3. raw_data_upi

This is the primary raw dataset used for the analysis.

It contains approximately:

**502,887 rows**

and:

**25 columns**

The sheet contains detailed transaction-level information.

Examples include:

* Transaction ID
* Date
* Time
* UPI App
* Customer ID
* Age Group
* Gender
* Country
* Transaction amount
* Transaction status
* Failure reason
* Cashback
* Transaction fee

The raw dataset serves as the foundation for the complete dashboard.

---

### 4. Failure_reason_count

This sheet analyzes unsuccessful UPI transactions based on their failure reasons.

Some failure reasons included in the analysis are:

* UPI Limit Exceeded
* Beneficiary Bank Offline
* Transaction Timeout
* Wrong UPI PIN
* Bank Server Down

This analysis helps identify the major reasons behind failed transactions.

---

### 5. image matrix

This sheet contains supporting calculations and analysis used for dashboard visualizations.

It includes information related to:

* UPI applications
* Application share
* States
* Performance-related calculations
* Supporting dashboard metrics

The calculations from this sheet are used to support the visual presentation of the dashboard.

---

### 6. cashback

This sheet analyzes cashback generated across different UPI applications.

Example analysis includes:

| UPI App    |      Cashback |
| ---------- | ------------: |
| PhonePe    | ₹1.68 Million |
| Google Pay | ₹0.76 Million |
| Paytm      | ₹0.51 Million |
| Amazon Pay | ₹0.17 Million |
| BHIM       | ₹0.14 Million |

This analysis helps understand how cashback is distributed among different UPI platforms.

---

### 7. Transaction fee

This sheet analyzes transaction fees generated by different UPI applications.

Example:

| UPI App    | Transaction Fee |
| ---------- | --------------: |
| PhonePe    |        ₹252,303 |
| Google Pay |        ₹113,716 |
| Paytm      |         ₹76,343 |
| Amazon Pay |         ₹26,034 |
| BHIM       |         ₹20,544 |

This provides a comparison of transaction fee contribution across UPI applications.

---

### 8. UPI Dashboard

This is the **main interactive dashboard** of the project.

The dashboard converts the detailed transaction data into easy-to-understand visualizations.

It provides an overview of important UPI transaction metrics and patterns.

The dashboard focuses on areas such as:

* Total transactions
* Transaction amount
* UPI application analysis
* Transaction trends
* Customer demographics
* Transaction failures
* Cashback
* Transaction fees
* Time-based transaction patterns
* Geographic analysis

Interactive elements such as filters/slicers can be used to explore the data from different perspectives.

---

### 9. Insights

The **Insights** sheet presents the major findings obtained from the analysis.

The purpose of this sheet is to convert numerical analysis into understandable business insights.

Examples of areas covered include:

* Transaction behavior
* UPI application usage
* Peak transaction hours
* Transaction failures
* Cashback distribution
* Customer demographics
* Transaction performance

---

### 10. Insights raw

This sheet contains the supporting calculations/data used to create the final insights.

It acts as a supporting analytical layer between the raw data and the final insights presented in the dashboard.

---

# 📈 Key Metrics

The analysis contains approximately:

### Total Transactions

**502,887 transactions**

### Total Transaction Amount

Approximately:

**₹442.48 Million**

### Total Cashback

Approximately:

**₹3.46 Million**

These metrics provide a high-level overview of the transaction dataset.

---

# 🔎 Key Analysis Areas

## 1. UPI Application Analysis

The project compares multiple UPI applications, including:

* PhonePe
* Google Pay
* Paytm
* Amazon Pay
* BHIM
* Cred Pay
* WhatsApp Pay

The analysis helps understand transaction activity and contribution across different applications.

---

## 2. Transaction Time Analysis

Transaction activity is analyzed using:

* Transaction Date
* Day
* Transaction Time
* Hour

This helps identify transaction patterns during different hours of the day.

For example, the analysis can be used to identify:

* Peak transaction hours
* Low transaction hours
* Daily transaction patterns
* Time-based transaction behavior

---

## 3. Failure Analysis

The project analyzes failed transactions and categorizes them according to failure reason.

Important failure categories include:

* UPI Limit Exceeded
* Beneficiary Bank Offline
* Transaction Timeout
* Wrong UPI PIN
* Bank Server Down

This helps identify operational areas that may require attention.

---

## 4. Cashback Analysis

Cashback is analyzed across different UPI applications.

This allows comparison of:

* Cashback distribution
* Cashback by application
* Transaction volume associated with cashback
* Overall cashback contribution

---

## 5. Transaction Fee Analysis

Transaction fees are analyzed across UPI applications.

This provides a comparison of the fee contribution generated by different platforms.

---

## 6. Customer Demographic Analysis

The dataset contains demographic information such as:

* Age Group
* Gender

This can be used to understand transaction behavior across different customer segments.

---

## 7. Geographic Analysis

The dataset contains geographic information such as country and state-level information used in the supporting analysis.

This allows the project to explore transaction activity across different geographical areas.

---

# 📊 Dashboard Features

The dashboard is designed to provide an easy-to-understand view of the UPI transaction data.

### Main features include:

* KPI cards
* Interactive charts
* Pivot-based analysis
* Slicers/filters
* UPI application comparison
* Transaction trend analysis
* Failure reason analysis
* Cashback analysis
* Transaction fee analysis
* Time-based analysis
* Demographic analysis
* Geographic analysis
* Insights section

---

# 💡 Business Questions Answered

This project can help answer questions such as:

1. How many UPI transactions are present in the dataset?
2. What is the total transaction amount?
3. Which UPI applications have the highest transaction activity?
4. What are the major reasons for transaction failures?
5. Which UPI applications contribute the most cashback?
6. How much transaction fee is generated by each UPI application?
7. During which hours is transaction activity higher?
8. How does transaction behavior vary across age groups?
9. How does transaction activity vary by gender?
10. Which failure reasons occur most frequently?
11. How is transaction activity distributed geographically?
12. What patterns can be identified from the overall UPI transaction data?

---

# 🧠 Skills Demonstrated

This project demonstrates practical skills in:

### Excel

* Data Cleaning
* Data Analysis
* Excel Functions
* Pivot Tables
* Pivot Charts
* Slicers
* Conditional Formatting
* Dashboard Design
* Data Visualization
* KPI Creation
* Business Insights

### Data Analytics

* Exploratory Data Analysis
* Trend Analysis
* Comparative Analysis
* Segmentation
* Failure Analysis
* Customer Analysis
* Performance Analysis
* Insight Generation

### Portfolio Skills

* Data storytelling
* Dashboard development
* Business problem solving
* Data visualization
* Analytical thinking

---

# 📁 Repository Structure

The GitHub repository can be organized as follows:

```text
UPI-Transaction-Analysis/
│
├── README.md
│
├── UPI_ANALYSIS_PROJECT.xlsx
│
├── screenshots/
│   ├── dashboard.png
│   ├── insights.png
│   └── pivot_analysis.png
│
└── documentation/
    └── project_notes.md
```

> If the Excel workbook is larger than GitHub's normal web-upload limit, the workbook can be hosted separately and the repository can contain the project documentation, screenshots, and access link.

---

# 🚀 How to Use the Project

### Step 1

Download the Excel workbook from the repository or the provided project link.

### Step 2

Open:

**`UPI_ANALYSIS_PROJECT.xlsx`**

using Microsoft Excel.

### Step 3

Start from the:

**Home**

sheet.

### Step 4

Navigate to:

**UPI Dashboard**

to view the main dashboard.

### Step 5

Use available filters/slicers to interact with the dashboard.

### Step 6

Visit the:

**Insights**

sheet to understand the major findings from the analysis.

---

# 📌 Important Note

This project is created for **data analytics learning and portfolio purposes**.

The dataset is used for analytical and educational purposes and should not be interpreted as official financial statistics or an official representation of any UPI service provider.

---

# 👨‍💻 Author

**Sanchit Anil Gawande**

### Role / Area of Interest

**Aspiring Data Analyst**

### Skills

* Microsoft Excel
* Data Analysis
* Data Visualization
* Dashboard Development
* SQL
* Power BI
* Python
* Machine Learning

---

# 🔗 Project Links

**GitHub Repository:**
*Add your GitHub repository link here*

**Excel Dashboard:**
*Add your Excel/Google Drive project link here if the workbook is hosted separately*

**LinkedIn:**
*Add your LinkedIn profile link here*

---

# ⭐ Project Highlights

> **UPI Transaction Analysis Dashboard | Microsoft Excel**

A comprehensive Excel data analytics project analyzing approximately **502K+ UPI transactions** and **₹442M+ transaction value**, with interactive dashboards, Pivot Tables, charts, failure analysis, cashback analysis, transaction fee analysis, demographic analysis, and business insights.
