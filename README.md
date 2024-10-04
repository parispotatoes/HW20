# HW20
credit-risk-classification

The analysis aimed to evaluate the performance of various machine learning models in predicting credit risk. It focused on the accuracy, precision, and recall of these models to identify the most effective methods for detecting potential credit defaults, which are essential for informed lending decisions. The process began with reading a CSV file of lending data using Pandas. The data was then normalized with StandardScaler due to significant variation in the features. Subsequently, a train-test split was performed to predict loan status, taking into account the considerable imbalance in the dataset, where 75.9% of loan statuses indicated no risk of default. Stratification was applied to ensure that the ratio of classes was maintained in both the training and testing datasets.
