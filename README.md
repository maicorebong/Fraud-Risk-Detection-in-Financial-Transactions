# Fraud-Risk-Detection-in-Financial-Transactions

In the rapidly evolving landscape of digital commerce, fraud detection remains a critical challenge.

With the support of IEEE-CIS, this project utilizes real-world transaction data from Vesta Corporation, world’s leading payment service company, to develop predictive models that assess the likelihood of fraudulent transactions. The objective is to predict the probability of fraud by analyzing transaction and identity data to uncover patterns that differentiate legitimate from fraudulent activities.

Dataset Overview
The dataset consists of two primary files (identity and transaction) which are linked by TransactionID; however, not all transactions have corresponding identity information. The data includes a variety of structured features, such as:

Transaction Features:

TransactionDT: Timedelta from a reference point
TransactionAMT: Transaction amount in USD
ProductCD: Product category of the transaction
Card & Address Information:

card1 - card6: Various card details, including type, category, issuing bank, and country
addr, dist: Address and distance-based attributes
Email & Behavioral Features:

P_emaildomain, R_emaildomain: Purchaser and recipient email domains
C1 - C14: Count-based features related to addresses, payment cards, etc.
D1 - D15: Timedelta features capturing time intervals between transactions
Identity & Risk Indicators:

M1 - M9: Matching features (e.g., name on card vs. billing address)
Vxxx: Engineered features created by Vesta, incorporating ranking, counting, and entity relations
Dataset from Kaggle: https://www.kaggle.com/c/ieee-fraud-detection/data
