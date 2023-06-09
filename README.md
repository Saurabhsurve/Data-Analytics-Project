# Data-Analytics-Project

This is a machine learning project built in python jupiter notebooks as a part of data analytics course at ReDI, Munich for Spring semester 2023. 

**The data is fetched from kaggle**. Path : https://www.kaggle.com/datasets/mohansacharya/graduate-admissions


The question we intent to answer is : **What are the predictors of acceptance to Masters programs in US universities. **

**Data file** : Admission_Predict.csv
It consists of the followwing data set 
GRE Scores ( out of 340 )
TOEFL Scores ( out of 120 )
University Rating ( out of 5 )
Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
Undergraduate GPA ( out of 10 )
Research Experience ( either 0 or 1 )
Chance of Admit ( ranging from 0 to 1 )

**Main project file** : Graduate_Admission_Project.ipynb

**The project outline can be summarized as follows**:
1. Data Collection
2. Data Exploration and Analysis
  A. Check the dataset for missing values and duplicates
  B. Heatmap of correlation coefficients
  C. Probability distribution of Admit to Program
  D. Correlation coefficients of 'Chance of Admit' with other features
  E. Visualize the correlation
  F. Remove outliers
3. Prediction Models
  A. Separate features and target
  B. Scaling
  C. Train different models for the given data and calculate the r2 values
  
**Scope for improvement:**  We could further fine tune the models with different parameters. Due to paucity of time I went ahead with the default parameters of the various models.

**Citation**
Please cite the following if you are interested in using the dataset :
Mohan S Acharya, Asfia Armaan, Aneeta S Antony : A Comparison of Regression Models for Prediction of Graduate Admissions, IEEE International Conference on Computational Intelligence in Data Science 2019


