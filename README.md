# 💳 Credit Card Fraud Analysis Dashboard
### Project Overview

This project focuses on analyzing credit card transaction data to uncover patterns and insights related to fraudulent activities. The goal is to understand the distribution and characteristics of fraudulent transactions using data exploration and visualization techniques.

### Data Source

Credit Card Data: The primary dataset used for analysis is the "creditcard.CSV" file, containing detailed information about each credit card.

### 📂 Dataset Access
The dataset is hosted externally due to its large size.  

👉 [Download the dataset from Google Drive](https://drive.google.com/file/d/1wJQCUxcvTnuosWGgYCqhVFpaklFZnhlP/view?usp=drive_link)

### Tools

- **Excel** - Data Cleaning
- **Power Query** – Data transformation and preparation.
- **Google Drive** – Hosting large dataset file.
- **Power BI** - creating reports


### Data Description

The dataset contains anonymized credit card transaction records.
Key columns include:

- Time – time (in seconds) between transactions

- Amount – transaction amount

- V1–V28 – anonymized numerical variables derived from PCA transformation

- Class – indicates whether a transaction is fraudulent (1) or legitimate (0)

 ### Analysis Steps

- **Data Cleaning** – Checked for missing values, duplicates, and anomalies.

- **Exploratory Data Analysis (EDA)**:

 Examined data distribution and transaction frequency.

 Compared fraudulent vs. non-fraudulent transactions.

 Visualized fraud distribution by transaction amount.

- **Insight Generation** 

Identified time and amount patterns associated with fraudulent transactions.

Highlighted significant differences between fraud and non-fraud groups.




### Results/Findings

The analysis results are summarized as follows:
- A total of 284,807 transactions were recorded, comprising 284,315 normal transactions amounting to $25,102,462.04, and 492 fraudulent transactions amounting to $60,127.97.
- Hour 11 recorded the highest number of fraudulent transactions (43), followed by Hour 26 with 36 fraudulent transactions. 
- Fraud is rare but costly, though only 0.17% of transactions are fraudulent, the value lost is significant.
- High-value transactions are riskiest, most fraudulent activity occurred in the 500+ amount category, highlighting where monitoring should be strongest.
- Fraud vs Normal, visually, fraud transactions are dwarfed in count, but the impact per transaction is disproportionately higher.
- Temporal Trend, fraud attempts spike periodically, showing that fraudsters may test the system in bursts rather than a steady flow.


### Recommendations

1. The organization needs to focus monitoring efforts on high-value transactions and peak fraud hours, while maintaining strong data validation and customer awareness.
   
2. Educate customers on safe transaction practices and phishing prevention and encourage prompt reporting of suspicious transactions or unauthorized charges.
   
3. Conduct root-cause analyses for detected frauds to improve fraud prevention rules.
4. Establish a fraud monitoring team or schedule periodic reviews focused on high-risk categories to cross-verify frequent transaction accounts and suspicious patterns detected during analysis.
5. Since fraudulent activities are more frequent among high-value transactions, introducing extra authentication steps (e.g., OTP, biometric, or multi-factor verification) for high-value transactions.
6. Since the highest fraud activity occurs around Hour 11, increase real-time transaction monitoring and automated alerts during that period.
