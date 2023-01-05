# HOD_Hackathon

In this hackathon a Dataset released by Microsoft was used. We won the hackthon by puttin in some effort.

# Notes :

# Data Analysis, Cleaning

The dataset was in Parquet fromat we used simple Pandas technique to load it however. 
Then, we did go through the dataset. It contained many of the Null Values.
We dropped columns with more than 50% of the Null values
The next thing is that we found out that Dataset was having only the categorical columns.
We studied it and decided to go through the KNN imputeation method, but due to computation limit we went through general mode imputation.

We used Chi Square test for Feature Selection. The P values were displayed and accordingly we filtered out some of the features.

For Dimensionality reduction we first thought of PCA but it was not an effective way so we skipped it.

# Model Building 

We went through many models.
At last we found that Boosting models were working better, in boosting too we got two models XGBoost and LGBM, the LGBM was giving better accuracy,
due to it's leaf based model structure

We did use Lazy Predictor to go through approximately 30 models all at once, to decide for the best model available
We also used some Dense Neural Models but the Machine Learning models proved to work better.

# Results

In the Public Test Cases, we got 63.8% accuracy which was the highest amongst all the participants, and we ultimately won.

