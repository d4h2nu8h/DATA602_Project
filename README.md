# DATA602_Project

# Financial Transactions and Money Laundering Analysis

## Project Overview
This project explores the detailed analysis of financial transactions and money laundering activities across various currencies. Our aim is to provide insights into the complex dynamics of illicit financial operations and their wider implications.

Through our analysis, we uncover interesting patterns indicative of money laundering practices across different currencies. We observe the significant dominance of the US Dollar and Euro in illicit financial flows and identify recurring bank codes associated with money laundering activities. Our project also includes visualizations and predictive models to enhance the detection of money laundering schemes.

## Group Members
- **Dhanush Sambasivam**
- **Madhumitha Rajagopal**
- **Lakshitha Senthil Kumar**
- **Shrivarshan Periyaswamy**

## Datasets

### 1. Anti-Money Laundering (AML) Public Data
- **Source**:[https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml)]
- **Description**: This dataset consists of 11 columns and 190 million rows, including string, categorical, and numeric data, providing comprehensive transactional data.

### 2. Exchange Rate Data
- **Source**: [Treasury Reporting Rates of Exchange](https://fiscaldata.treasury.gov/datasets/treasury-reporting-rates-exchange/treasury-reporting-rates-of-exchange)
- **Description**: This dataset includes exchange rates of the U.S. government against various currencies over a period of 10 years, with 13 columns and 173 rows.

## Objectives
- Analyze synthetic transaction data and identify patterns indicative of fraud.
- Investigate correlations between transaction features such as amount, currency, and payment format associated with potential money laundering.
- Analyze temporal patterns, including transaction volume spikes, to identify potential money laundering activities over time.

## Why We Are Choosing This Dataset

We have chosen these datasets because:

1. **Robustness of AML Public Data**: The AML Public Data is robust, containing a vast number of transactions (190 million rows), which provides sufficient data to build models that can effectively identify money laundering patterns. It’s a big data project using a tech stack including PySpark and SQL to identify hidden questions.

2. **Complementary Exchange Rate Data**: The Exchange Rate Data complements the financial transactions dataset by providing important context for cross-currency money laundering schemes. Understanding how currency values fluctuate will help us analyze the preference for certain currencies in illicit transactions.

3. **Uncovering Complex Patterns**: These datasets allow us to uncover complex patterns of fraud by analyzing large-scale financial transaction data and exploring correlations between key factors like currency, transaction amounts, and payment formats.


## Future Work
- Predict whether a client is engaged in money laundering using advanced machine learning techniques.
- Address data imbalance challenges by downsampling and selecting key features for improved prediction accuracy.

