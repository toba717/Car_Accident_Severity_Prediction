# Car_Accident_Severity_Prediction
Generated handful of machine learning models to classify the severity of car accidents nationwide


Models used:
- KNN model
- Logistic Regression
- Decision Tree
- Pruned Decision Tree
- Random Forest


Techniques implemented:
- missForest Imputation
- Text Mining
- Median imputation
- Addition of Prediction
- Construction of confusion matrix and assessing misclassification rate
- test vs train split
- Compuation of Time


According to kaggle.com, "This is a countrywide car accident dataset, which covers 49 states of the USA. The accident data are collected from February 2016 to Dec 2021, using multiple APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 2.8 million accident records in this dataset."

Further, this is the description for the data sets:

" The data is split into two data sets; the training data set which contains 35,000 observations with 44 variables. While the testing data contains 15,000 observations with 43 variables (No target variable).

-   The purpose of this project is to be able to classify accidents as "SEVERE" or "MILD" based on the rest of the data attributes.

-   The target variable is "SEVERITY" which is a categorical variable with two categories: "SEVERE" or "MILD". The "SEVERE" accidents are around 10% of the accidents, while "MILD" is the other 90% of the accidents in the training data.

-   This means, your classifier misclassification rate has to beat 10% to be considered a better than a chance classifier."

Ultimately, our goal is to undergo a systematic process to classify rather an accident is "SEVERE" or "MILD"
