# credit-risk-classification_reja
Module 20 Challenge


## Challenge Overview ##

The objective of this analysis is to utilize a supervised machine learning method, namely logistic regression, for the training and evaluation of a model designed to categorize loans into two groups: those with a healthy risk profile and those considered high-risk loans.

In the first part of the analysis, my goal is to predict the loan status of borrowers. To achieve this, I initially divided the entire dataset into training and testing sets using the **train_test_split** function imported from **sklearn.model_selection**. The training set was employed for building the logistic regression model, and subsequently, I applied this model to the testing set. The model's objective was to determine whether the loans in the testing set could be classified as low or high risk.

In the subsequent phase of our analysis, I utilized the RandomOverSampler function from the **imblearn.over_sampling** library. This step was essential in the data preprocessing stage to prepare it for the development of a fresh model. The purpose behind this resampling technique was to rectify any potential data imbalances within the dataset. By oversampling certain data points, I ensured that the new logistic regression model would have an equitable number of instances representing each class. This approach helped mitigate the impact of any skewed class distribution, thereby enhancing the model's ability to make reliable predictions.


## Files ##

Downloaded the following files to get started:

[Module 20 Challenge files](https://bootcampspot.instructure.com/courses/3819/assignments/56660?module_item_id=1001084)

## Two Machine Learning (ML) Models ##

## ML Model 01 ##

**Methods**: I conducted training on a logistic regression model using the initial training dataset.  I divided this model into training and test sets and proceeded to build a logistic regression model. Subsequently, I generated a confusion matrix and computed accuracy, precision, and recall for both the training and test sets.

**Results**:
The logistic regression model exhibits exceptional precision when predicting healthy loans ('0'), achieving a perfect 100% precision rate. This means that every time the model identifies a loan as "healthy," it is indeed a correct classification. In simpler terms, there are no false positive predictions for healthy loans.

For high-risk loans ('1'), the model maintains a relatively high precision of 85%. This indicates that when the model categorizes a loan as "high risk," it is accurate 85% of the time, with a relatively small number of false positives within this category.

The overall accuracy score of 95% signifies the model's strong performance in correctly classifying both healthy and high-risk loans throughout the dataset. It indicates that 95% of the model's predictions are accurate. This high level of accuracy suggests that the model is adept at making reliable predictions across the majority of the dataset, despite the precision for high-risk loans being slightly lower than for healthy loans. In general, a 95% accuracy score demonstrates the model's effectiveness in correctly identifying loans in this classification task. See the results below- 

 ![alt text](https://github.com/mdyousufreja/credit-risk-classification_reja/assets/135454460/1f4a88c8-8a05-4d70-8d4e-b2da8af9720a)

