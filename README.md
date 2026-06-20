# 🚨 AML  Transaction Monitoring Dashboard | Power BI

## 📖 Project Overview

This Transaction Monitoring Dashboard is a Financial Crime Analytics project developed using Power BI, Excel, Power Query, and DAX. The dashboard helps identify suspicious transaction patterns, monitor AML alerts, analyze customer risk categories, and support compliance teams in detecting potential money laundering activities.

The solution provides interactive visualizations that enable compliance analysts and risk teams to monitor transactions, investigate alerts, and gain insights into customer behavior and risk exposure.

---

# 🎯 Project Objectives

* Monitor financial transactions in real time.
* Detect suspicious transaction patterns.
* Identify high-risk customers.
* Track AML alerts and investigations.
* Improve compliance reporting.
* Support Anti-Money Laundering (AML) monitoring activities.

---

# 🔄 End-to-End Workflow

### Phase 1: Data Collection
Collected transaction monitoring data from Excel datasets containing customer, transaction, and alert information.

### Phase 2: Data Import
Imported all datasets into Power BI Desktop using Power Query.

### Phase 3: Data Cleaning
Performed data quality checks and data transformations.

### Phase 4: Data Modeling
Created relationships between tables and built a star schema model.

### Phase 5: Data Analysis
Conducted exploratory data analysis to identify trends and patterns.

### Phase 6: DAX Development
Created KPIs and business measures using DAX.

### Phase 7: Dashboard Design
Developed interactive dashboards and visualizations.

### Phase 8: Business Insights
Generated actionable insights for AML compliance monitoring.

---

# 📂 Data Source

The project uses three datasets.
**Contains customer profile information.**
**Original Format:** PDF
**Processed Format:** Structured Excel
https://1drv.ms/x/c/00b1e276a52f7d08/IQD-o4Q2uPzMTrvBNsXZrsDnAYevRvheYSujG-wkZ99_ey4?e=IedKcl

## **Customer_Details**

| Column Name   |
| ------------- |
| Customer_ID   |
| Customer_Name |
| Customer_Type |
| Country       |
| Risk_Category |
| KYC_Status    |

Total Records: 3,000

---

## **Transactions**

**Contains transaction-level details.**

| Column Name      |
| ---------------- |
| Transaction_ID   |
| Customer_ID      |
| Transaction_Date |
| Transaction_Type |
| Amount           |
| Currency         |
| Channel          |
| Status           |

**Total Records:** 15,000

---

## **Alert_Log
**
Contains suspicious activity alerts.

| Column Name          |
| -------------------- |
| Alert_ID             |
| Transaction_ID       |
| Alert_Type           |
| Alert_Date           |
| Severity             |
| Investigation_Status |

Total Records: 1,500

---

# 🧹 Data Cleaning & Data Preparation

The following steps were performed:

* Removed duplicate records.
* Validated Customer IDs and Transaction IDs.
* Corrected data types.
* Standardized column names.
* Handled missing values.
* Removed inconsistencies.
* Created relationships between tables.
* Optimized the Power BI data model.

---

# 📊 Excel Structuring

The dataset was organized into separate sheets for better maintainability.

### Raw Data Layer

* Customer_Details
* Transactions
* Alert_Log

### Structured Data Layer

* Cleaned Customer Data
* Standardized Transaction Data
* Validated Alert Records

### Reporting Layer

* KPI Calculations
* Aggregated Metrics
* Dashboard-ready Tables

---

# 🔄 Raw Converted Data

The raw data was transformed into analytical datasets through:

* Data cleansing
* Data validation
* Data normalization
* Data enrichment
* Relationship mapping

This ensured high-quality data suitable for reporting and analysis.

---

# ✅ Structured & Cleaned Data

The final dataset includes:

* Valid Customer Records
* Standardized Transaction Records
* Verified Alert Records
* Optimized Relationships
* Dashboard-ready Data Model

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

### Customer Analysis

* Customer segmentation
* Risk category distribution
* KYC status analysis


### Transaction Analysis

* Transaction trends
* Transaction amount analysis
* Channel performance analysis

### Alert Analysis

* Alert frequency
* Alert category distribution
* Investigation status analysis

### Risk Analysis

* High-risk customer identification
* Alert-risk correlation
---

# 💡 Key Insights

### Transaction Monitoring
* More than 15,000 transactions were monitored.
* Significant transaction activity observed across digital channels.

### Risk Monitoring
* High-risk customers generated notable transaction volumes.
* Risk segmentation improved customer monitoring.

### Alert Management
* Alert distribution revealed common suspicious activity patterns.
* Investigation tracking improved operational efficiency.

### Channel Analysis
* Mobile Banking and Online Banking contributed the highest transaction volumes.

---

# 🛠️ Tools & Technologies

## Data Visualization
* Microsoft Power BI
## Data Preparation
* Power Query
## Data Analysis
* DAX (Data Analysis Expressions)
## Data Source
* Microsoft Excel
## Domain Expertise
* AML (Anti-Money Laundering)
* KYC (Know Your Customer)
* Transaction Monitoring
* Compliance Reporting
* Financial Crime Analytics

---

# 📁 Repository Structure

Transaction-Monitoring-Dashboard/

├── Dataset/

│ └── Transaction_Monitoring_Dataset_15000_Records.xlsx

│

├── Dashboard/

│ └── Transaction_Monitoring_Dashboard.pbix

│

├── Images/

│ ├── Dashboard_Overview.png

│ └── Dashboard_Details.png

│

├── Documentation/

│ └── Project_Report.pdf

│

└── README.md
_ _ _

**📊** **Excel Data Structuring**

**Raw Converted Data**
<img width="1907" height="1005" alt="Screenshot 2026-06-17 192606" src="https://github.com/user-attachments/assets/216361f1-0a46-4639-9aae-be2cb09c8471" />

# **🖼️** **Dashboard Preview**

### Dashboard Overview
<img width="1182" height="662" alt="Screenshot 2026-06-17 182031" src="https://github.com/user-attachments/assets/600e4af5-e95d-4c26-a2aa-72b623c57923" />


### **Dashboard Details**

<img width="1162" height="647" alt="Screenshot 2026-06-17 182044" src="https://github.com/user-attachments/assets/aa203397-9510-46f6-96d7-bd5b7089c678" />


---

# **📊** **Power BI Dashboard**

* **Monthly Transaction Amount Trend**
<img width="418" height="251" alt="Screenshot 2026-06-17 190642" src="https://github.com/user-attachments/assets/5c47206d-c118-4d89-920b-eb55c0662fa2" />

* **Risk Category Analysis**
<img width="235" height="246" alt="Screenshot 2026-06-17 190726" src="https://github.com/user-attachments/assets/6766213f-600a-4256-b0ce-53d4e94bbe56" />

* **Investigation Status Analysis**
<img width="292" height="252" alt="image" src="https://github.com/user-attachments/assets/9cfdc223-fb97-47c3-b079-dd844fcc9e10" />
---
  
*  **Alert Type Distribution**
<img width="463" height="240" alt="Screenshot 2026-06-17 190838" src="https://github.com/user-attachments/assets/84ba61f9-a8f0-4713-ab44-0ae45116f300" />

* **Transaction Amount by Type**
<img width="482" height="242" alt="Screenshot 2026-06-17 190911" src="https://github.com/user-attachments/assets/b6a02c8f-132a-4307-adca-7ddc6a7050ef" />
  
* **Transactions by Channel**
<img width="487" height="312" alt="Screenshot 2026-06-17 190956" src="https://github.com/user-attachments/assets/7d13eff4-55b8-4606-b722-a3506540ebfb" />

* **Alerts Over Time**
<img width="637" height="315" alt="Screenshot 2026-06-17 191142" src="https://github.com/user-attachments/assets/2bd6d349-713f-456b-963f-dbe6292ad01f" />

  
* **Top 10 Customers by Transaction Amount** 
<img width="1152" height="330" alt="Screenshot 2026-06-17 191228" src="https://github.com/user-attachments/assets/293f8bf2-13e3-40c7-8681-251bd72d45ce" /> 
---

# 🌟 Project Highlights

✅ End-to-End Power BI Project

✅ AML Transaction Monitoring Solution

✅ 15,000+ Transactions Analyzed

✅ Interactive Dashboard Design

✅ Customer Risk Analysis

✅ Alert Investigation Tracking

✅ DAX KPI Development

✅ Compliance Reporting Dashboard

---

# 🚀 Future Enhancements

* Real-Time Transaction Monitoring
* Machine Learning Fraud Detection
* Predictive Risk Scoring
* Automated Suspicious Activity Reporting (SAR)
* Cloud Deployment using Azure
* Enterprise AML Integration

---

# ⚠️ Disclaimer

This project is developed solely for educational, learning, and portfolio purposes. The dataset used in this project is sample data and does not contain any real customer or financial information.

---

# 📜 License

MIT License

This project is open-source and available for educational and portfolio purposes.

---

# 👨‍💻 Author

## Jujare Sai Abhinay

B.Com (Computer Applications) Graduate | Aspiring KYC Analyst | AML Analyst | Power BI Developer

### 📧 Email

[jsaibhinay53@gmail.com](mailto:jsaibhinay53@gmail.com)

### 🔗 LinkedIn

https://www.linkedin.com/in/jujare-sai-abhinay-71a2b1363/

### 💼 Skills

* Power BI
* Excel
* DAX
* KYC
* AML
* Transaction Monitoring
* Financial Crime Analytics
* Compliance Reporting


