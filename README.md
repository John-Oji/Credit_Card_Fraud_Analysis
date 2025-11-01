# Credit Card Fraud Analysis

### Project Overview

This project focuses on analyzing credit card transaction data to uncover patterns and insights related to fraudulent activities. The goal is to understand the distribution and characteristics of fraudulent transactions using data exploration and visualization techniques.

### Data Source

Sales Data: The primary dataset used for analysis is the "creditcard.CSV" file, containing detailed information about each credit card.

### Tools

- Excel - Data Cleaning
- Power BI - creating reports

### Data Description

The dataset contains anonymized credit card transaction records.
Key columns include:

- Time – time (in seconds) between transactions

- Amount – transaction amount

- V1–V28 – anonymized numerical variables derived from PCA transformation

- Class – indicates whether a transaction is fraudulent (1) or legitimate (0)

 ### Analysis Steps

- Data Cleaning – Checked for missing values, duplicates, and anomalies.

- Exploratory Data Analysis (EDA):

 Examined data distribution and transaction frequency.

 Compared fraudulent vs. non-fraudulent transactions.

 Visualized fraud distribution by transaction amount.

- Insight Generation 

Identified time and amount patterns associated with fraudulent transactions.

Highlighted significant differences between fraud and non-fraud groups.


### Data Analysis




### Results/Findings

The analysis results are summarized as follows:
- Fraud is rare but costly, though only 0.17% of transactions are fraudulent, the value lost is significant.
- High-value transactions are riskiest, most fraudulent activity occurred in the 500+ amount category, highlighting where monitoring should be strongest.
- Fraud vs Normal, visually, fraud transactions are dwarfed in count, but the impact per transaction is disproportionately higher.
- Temporal Trend, fraud attempts spike periodically, showing that fraudsters may test the system in bursts rather than a steady flow.


### Recommendations
