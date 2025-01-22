INTRODUCTION: the purpose of this analysis is to understand customers' behavior and also identify how much transaction is processed via each transaction type (credit, debit and transaction).
Scope: this project used imaginary dataset with total number of 100,000 entries.

OBJECTIVES: Here are the objectives of the project:
Step i: Import the necessary libraries needed for the analysis
Step ii: Load the data
Step iii: Explore the data - understand the structure and contents of the dataset (describe and info)
Step iv: Data cleaning

1. Check for null values and drop if necessary
2. Ensure the date column is in date format
3. Convert "Amount" to numeric
4. Drop any remaining rows with missing "Amount" after conversion
5. Check the cleaned data
   
Step v: Analyze the data to get insights (Research questions)

1. Transaction volume in each month
2. How much was spent using different payment type
3. How much was spent by each customer per transaction type
4. Sum of transactions in each year

Step vi: Visualize the data

1. Distribution of the transaction values in each year
2. Distribution of the transaction types in each year (pie chart)

Step vii: Save the processed data

METHODOLOGY 
Data Overview: Below is the description of the dataset
transaction_id: Unique identifier for each transaction.
date: The date when the transaction occurred.
customer_id: Unique identifier for each customer.
amount: The monetary value of the transaction.
type: The type of transaction (e.g., "current", "debit", "transfer", etc.).
description: notes from the customer who initiated the transction

RESULTS/SUMMARY:
This report shows the analysis of customers' transaction data, examining the transaction volume, distribution of transaction types and patterns over the years. Key findings indicates that:
1. There was a 74.63% loss in transaction value/amount in 2023 against the 2022 value.
2. There was a 0.26% loss in the transaction value in 2022 against the 2021 value.
3. The year 2020 recorded an all time high with a transaction value of 100,936,349.
4. Also there is no significant difference in the usage of the various transaction types (credit, debit and transfer).

DISCUSSION:
The analysis shows a significant 74.63% decline in transaction value from 2022 to 2023, indicating major shifts in customer behavior or market conditions. This drop could be due to economic downturns, changes in purchasing habits, or operational challenges. The decline warrants further investigation into potential drivers such as reduced customer activity, product changes, or a shift to lower-value transactions. In contrast, the slight 0.26% decrease between 2021 and 2022 suggests stable market conditions during that period.

The record-high transaction value in 2020 was likely influenced by the pandemic and lockdowns, driving increased demand for essential goods, changes in consumer behavior, and a shift toward digital transactions. Understanding the factors behind this surge, such as customer engagement or economic impacts, could help replicate similar results in the future. The consistent use of credit, debit, and transfer methods indicates that customers are not heavily reliant on one payment option, which could guide decisions on transaction processing, fees, and promotions for different payment methods, optimizing customer satisfaction across channels.
