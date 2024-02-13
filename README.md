# Data-Fraud-Enrichments-and-Predictions
## Overview
A major financial institution is struggling with new account fraud after running a new promotion on certificates of deposits. Fraudsters are opening fake accounts known as “synthetic fraud” in a legitimate customer’s name, they then transfer funds from the legit customer to these new fraudulent accounts, and after a period of time, they then close the account and running off with the money!

## Assignment
- 1. Project Setup and Data Extraction
     Connect to a remote PostgreSQL database and extract the fraud data
     Install necessary libraries and tools
     Connect to Postgres database on the cloud
     Write an SQL query to extract the customer_accounts table from the database
- 2. Data Enrichment
     Enrich the data by adding additional information based on IP addresses.
- 3. Data Loading
     Load the enriched data into a local MySQL or SQLite database
- 4. Train a Classification Model
     Build a classification model to predict fraud or legit
- 5. Visualize Data to answer these questions
     Connect Excel to your database, and create queries and visualizations to answer the question.
      1. Is credit score predictive of fraud or not?
      2. For your op 5 predictors generate a visual and put them into a dashboard for the relationship between fraud and the predictor. Have a short explanation of how to interpret each chart.
      3. A score distribution
      4. At a predicted probability of fraud of 0.5 and above what is the accuracy, precision, and recall
      5. you must answer if the accuracy of the model better than the default accuracy
