# Fraud Detection and Account Risk Assessment Project (Anti-Money Laundering)

## Goal
The primary goal of this project is to develop a machine learning model capable of identifying fraudulent transactions within a dataset. I aim to leverage supervised machine learning techniques to detect patterns associated with fraudulent transactions, with a particular focus on identifying SAR cycles. Additionally, I plan to employ unsupervised machine learning to predict the likelihood of an account being fraudulent based on these detected transactions.

## Tech Stack
- Python Libraries for Data Science Pipeline
- Tableau Dashboards
- GraphQL
- Apache Kafka
- Node.js
- React.js

## Dataset
I'll be using a dataset, I found reference through Kaggle
- **Reference:** https://www.kaggle.com/datasets/anshankul/ibm-amlsim-example-dataset
- **Source:** https://github.com/IBM/AMLSim/wiki
- **Dataset variables descritpion:** https://github.com/IBM/AMLSim/wiki/Data-Schema-for-Input-Parameters-and-Generated-Data-Set
- **Dataset in use: 1K vertices(accounts), 100K edges(transactions):** https://github.com/IBM/AMLSim/wiki/Download-Example-Data-Set

## Project Progress
Here is an overview of the project's current progress:

1. **Data Exploration:** I have completed the initial data exploration phase, which involved understanding the dataset's structure, identifying key features, and gaining insights into the nature of transactions.

2. **Data Pre-processing:** I have performed necessary data pre-processing tasks, including data cleaning, handling missing values, and transforming the data into a suitable format for machine learning.

3. **Data Visualization:** I have created data visualizations to better understand transaction patterns and relationships within the dataset.

4. **Feature Engineering:** I have removing the outliers from txs_df, combined the dataframes with all the required columns,extracted more information using sender_account_id and receiver_account_id such as frequency and recency which is the number of transactions or the time since the last transaction for each sender account as a sender and each receiver account as a receiver, train-test split for time-series data, standardizing the tx_amount column, correlation, sampling for dealing with imbalance in train dataset, multicollinearity using VIF.

5. **Superevised Machine Learning Model Development:** By far I have worked with Logistic Regression and Random Forest to predict fraudulent transactions.


Please stay tuned for further updates as I move forward with model development, evaluation, and the creation of data-driven dashboards.

## Next Steps
The next steps in the project involve:

- Supervised Machine Learning Model Development (continue)
- Unsupervised Machine Learning for Account Risk Assessment
- Integration with GraphQL and Apache Kafka
- Web Application Development using Node.js and React.js


Thank you for your interest in my project!

