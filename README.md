# Predict customer review rating
## Problem Statement:

My main hypothesis of this project is that "the product and how the order was fulfilled influences customer review rating."

Many companies today measure customer satisfaction. Some of the quick ways of collecting the feedback from customers is through their reviews or by surveying them. These are very important customer service metrics, but are not typically being used to improve operations or help reduce customer churn.

Instead of waiting until the customer interaction is over for feedback/ review, companies can predict how likely an operation is to receive a good or bad rating while they are still in contact with the customer.

In this project, machine learning techniques will be applied to the dataset to predict customer review ratings.  

## Approach:

The problem was divided into several steps:

1. **Data Wrangling:** The datasets were uploaded to a dataframe and explored. Null values were filled in wherever appropriate and polluted values were discarded.

2. **EDA:** Extensive data visualisation was used to extract insights and pattern from the dataset.

3. **Inferential Statistics:** Hypothesis tests were built to derive the statistical significance of the features. 

5. **Machine Learning:** Various classifiers were tested and their accuracy recorded. The best classifier was then hyperparamter tuned using Grid Search Cross Validation. This model was then fit on the test data and the best model was obtained.

## Final Results:

The following Insights were given.

The customers usually are satisfied (score 5) or not satisfied(1) so the number of reviews with score 1 and 5 are comparatively more than 2,3 and 4.

It can be said that delivery accuracy is one of the most important factors in keeping customers happy.

Unfortunately, unlike NLP, it is by no means easy to determine the state of the art model for review prediction.To predict review rating on the basis of product and delivery posses a data challenge. 

Purchase decision processes are composed of several variables that influence customer’s choice for certain products and many factors influence review rating such as 

- Incorrect descriptions of the product
- Poor client service
- Poor response to information request
- Lack of communication
- Rude or Uninformed customer care staff
- Needs not accurately defined
- Promises not carried out
- Repeated complaints from the same customer

To conclude, customer satisfaction can not be predicted solely based on objective facts without taking the vast amount of subjective sensor and service process data into account.


