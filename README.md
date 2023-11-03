# credit-risk-classification_reja
Module 20 Challenge


## Challenge Overview & Methodology ##

The objective of this analysis is to utilize a supervised machine learning method, namely logistic regression, for the training and evaluation of a model designed to categorize loans into two groups: those with a healthy risk profile and those considered high-risk loans.

In the first part of the analysis, my goal is to predict the loan status of borrowers. To achieve this, I initially divided the entire dataset into training and testing sets using the **train_test_split** function imported from **sklearn.model_selection**. The training set was employed for building the logistic regression model, and subsequently, I applied this model to the testing set. The model's objective was to determine whether the loans in the testing set could be classified as low or high risk.

In the subsequent phase of our analysis, I utilized the RandomOverSampler function from the **imblearn.over_sampling** library. This step was essential in the data preprocessing stage to prepare it for the development of a fresh model. The purpose behind this resampling technique was to rectify any potential data imbalances within the dataset. By oversampling certain data points, I ensured that the new logistic regression model would have an equitable number of instances representing each class. This approach helped mitigate the impact of any skewed class distribution, thereby enhancing the model's ability to make reliable predictions.


## Files ##

Downloaded the following files to get started:

[Module 20 Challenge files](https://bootcampspot.instructure.com/courses/3819/assignments/56660?module_item_id=1001084)

