Visualize, detect, and explore credit card fraud trends using Power BI.

# 💳 Credit Card Transaction & Fraud Detection Dashboard

An interactive Power BI dashboard designed to analyze credit card transactions and identify fraud patterns across multiple U.S. cities. This report helps detect high-risk locations, fraud-prone transaction types, and merchant activity contributing to anomalies.


##  Dashboard Overview

The Power BI dashboard is split into three key analytical pages:

### 1️⃣ Credit Card Transaction Overview
- KPIs: Total Amount, Total Transactions, Fraud Cases, Fraud Rate, Average Amount
- Fraud by Year and Transaction Type
- Location-wise transaction bar chart with fraud overlay
- Monthly and daily trends in amount and volume
![Transaction Overview](https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/Screenshots/Screenshot%202025-07-26%20232141.png)


### 2️⃣  Analyzing Fraud Pattern
- Fraud vs Non-Fraud comparison
- Fraud by transaction type (purchase/refund)
- Monthly trends in fraud volume
- Fraud breakdown by Merchant ID
![Fraud Pattern](https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/Screenshots/Screenshot%202025-07-26%20232243.png)


### 3️⃣ Geographical Transaction Analysis
- Interactive slicers by location and year
- Fraud heatmaps and total transaction maps
- Location-wise transaction and fraud summaries
![Geographical Analysis](https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/Screenshots/Screenshot%202025-07-26%20232329.png)


##  Key Insights

- **Total Transactions:** 100,000  
- **Total Amount Processed:** ₹250M+  
- **Fraud Cases Detected:** 1,000  
- **Overall Fraud Rate:** 1%

###  Additional Findings:
- **Equal fraud share** between `purchase` and `refund` transactions
- **New York, Houston, and San Diego** report the most fraud
- **Merchant-level fraud tracking** helps pinpoint anomalies
- Spikes in fraud occur during **February**, **June**, and **December**


##  Screenshots

### Credit Card Transaction Overview
(https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/Screenshots/Screenshot%202025-07-26%20232141.png)

### Geographical Transaction Analysis
(https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/Screenshots/Screenshot%202025-07-26%20232329.png)

### Analyzing Fraud Pattern
(https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/Screenshots/Screenshot%202025-07-26%20232243.png)


##  Dataset
(https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/credit_card_fraud_dataset.csv)
The dataset includes the following fields:
- `TransactionID`
- `TransactionDate`
- `TransactionType` (purchase/refund)
- `Location`
- `Amount`
- `IsFraud` (0: Non-Fraud, 1: Fraud)
- `MerchantID`


##  Interactive Power BI Dashboard
(https://github.com/Kshitija-Agrawal/Credit-Card-Fraud-PowerBi/blob/main/credit%20card%20fraud.pbix)


##  Tools & Technologies

- **Power BI Desktop**
- Power Query (ETL & transformation)
- DAX (Data Analysis Expressions)
- Excel (.xlsx)
- Bing Maps integration (geo-visualization)



