# Fraud-Detection
Scotia Data Science Competition - 3rd prize

### Background
The widespread use of credit cards in Canada, coupled with the increase in online transactions during
the Covid-19 pandemic, has made credit card fraud a significant problem. With over 80 million
credit cards in circulation in 2021 and more than 6 billion purchase transactions made each year in
Canada, fraudsters have been using credit cards to obtain goods and services without paying. This
not only harms the profitability of financial institutions and the security of consumers, but it also
poses a threat to the stability of the financial system as a whole. As the intensity of transaction fraud
continues to increase, it is essential for financial institutions and consumers to take steps to prevent
and mitigate the impact of this crime.

### Methods
Technical: Extra Data, Data imputation by mode, create new column with null/not null, Correlation, Min-max Scaler, Frequency Encoding, XGBoost (setting weighted by label), Fine-tuning to maximize AUC-ROC.
Maximal F-1 Score: Decrease Prediction Thresholds

### Interpret The Result: 
*  Visualization (correlation Map and Bar charts)
*  Fraud-detection Score (label as low, medium and high groups)
*  Identify Fraud Groups - for important columns, split data into 10 groups and compare density of target labels

### Business Suggesstions: 
*  The system reduces the cost of organization/groups, and detect fraud transactions better than human
*  Customer Experience (Explain the model by important attributes, Double Check results when in the medium group by Fraud Detection System)
*  Transactions to Decline (Fraud Scoring System, Decline Transaction in High Risk Groups, may have more detection on dangerous groups (such as 12:00 am and 8:45 each day - fraud rate is more than twice, Less credit limit will cause more fraud))
*  Long term suggesstions (Updating the model (model stacking, bagging, train different models with different groups)), NLP (example: on comments in transactions), Other AI models (Deep learning, Random Forest, Adaboost), Collaborating with other organizations to gain more data and discuss models

### Solutions
The code, report and powerpoint presentation includes our results
