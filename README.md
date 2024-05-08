Payment-Date-Prediction-ML-Model
Machine Learning Model to predict payment date for the invoices using XGBoost Regressor.
It is a Machine Learning Model in which users in the Account Receivable department do the following tasks on a daily basis:

● View data from various purchasers' invoices.

● View the invoice(s) from a certain buyer's various fields/attributes.

● Pre-process the invoice data via data pre-processing.

● With EDA and Feature Engineering, we may get account-level analytics to quickly display and comprehend data.

● Get an estimate for when the invoice will be paid

B2B Transactions
When a buyer company orders products from a seller company, the seller company sends an invoice to the buyer company. This products invoice includes information such as the specifics of the goods purchased and when they should be paid. In accounting, this is referred to as "Accounts Receivable." Money due to the company by entities for the sale of items or services on credit is represented by Accounts Receivable.

On the basis of the algorithm, MSE score, and R2 score, the models I have compared ML Models to determine which best suits the needs:

Linear Regression

Decision Tree Regression

Random Forest Regression

Support Vector Regression

Extreme Gradient Boost Regression

B2B or Business to Business companies work on credits with other companies. When there is a trade between a buyer's business and a seller's business, the seller's business issues an invoice for the transaction. The invoice for the transaction contains various information about the goods purchased and the date by which the credit shall be cleared. Invoice Management is crucial for all businesses as it frequently trades with multiple other businesses. To correctly predict the most probable Payment Date is an important task for the accounts team to generate the invoice. The buyer must clear the credits within the established timeframe termed the credit terms or Payment Terms. Keywords: B2B, Invoice management, Payment date Prediction, Payment Terms.

Machine learning is a sub-domain of AI that works on the principle to train a model to learn from its experience without being explicitly programmed to do so. An ML model learns in ways similar to how the human brain learns things. A model is fed with the training data to learn from experiences. The process starts with the observation of data. The model looks for patterns in the training data.

The machine learning techniques are basically of two types:

Supervised Learning,
Unsupervised Learning.
The supervised learning technique has two types

Classification model,
Regression model.
Similarly, an unsupervised machine learning model has

Clustering Model,
Association Model.

---> Machine Learning Model to predict the payment date of an invoice when it gets created in the system.
Categorize the invoice into different buckets based on predicted payment date.

The invoices dataset contains the past payment information and behaviour of various buyers. Based on the previous payment patterns, the ML model will predict what will be the date a payment is made by the customer for an invoice.
The model will also predict which aging bucket the invoice falls into based on the predicted payment date.
The different buckets will be :
0-15 days
16-30 days
31-45 days
46-60 days
Greater than 60 days
