Using a dataset of bankrupcies and financial ratios for companies of Taiwan between the years 1999-2009, we work on a classification problem.
Two main topics arise: high number of explanatory features and high class imbalance in the dependent variable. 
We try different methods to reduce the number of explanatory features (variance threshold, VIF, PCA, RFE). 
We upsample the minority class by repeating the samples randomly and downsample the majority class, after clustering in order to preserve the features of the population of companies.
Different models are then fitted and used for prediction (KNN, Random forest and XGB). 
The results are good in terms of accuracy, but performance has to be improved in terms of other metrics. 

The data was obtained from: https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction and UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction.
Additional information: https://www.sciencedirect.com/science/article/pii/S0377221716000412 
