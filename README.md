# breast-cancer-detection-using-SVM-and-KNN
![Breast Cancer detection](https://www.istockphoto.com/photo/cancer-outbreak-gm1277148522-376442007?utm_source=unsplash&utm_medium=affiliate&utm_campaign=srp_photos_top&utm_content=https%3A%2F%2Funsplash.com%2Fs%2Fphotos%2Fcancer&utm_term=cancer%3A%3A%3A)
# Breast cancer prediction Project

 ## Business Problem  
An end to end modelling to help detect breast canncer in Patients.
 
 ## The dataset

The dataset contains the Donor records collected from a Red Cross. 

The "DONOR_IND" column is a target variable which has Categorical entries (Y or N).

ID - the unique identifier for each constituent

ZIPCODE - the ZIP code for the constituent

AGE - the age of the constituent

MARITAL_STATUS - the marital status of the constituent

GENDER-the gender of the constituent

MEMBERSHIP_IND- a binary flag indicating if a constituent is a radio member

ALUMNUS_IND- a binary flag indicating if a constituent is an alumnus

PARENT_IND- a binary flag indicating if a constituent is a parent

HAS_INVOLVEMENT_IND- a binary flag indicating if a constituent has an involvement code

WEALTH_RATING - a descriptive factor with the results of a wealth screen

DEGREE_LEVEL - the degree level of the constituent if they are an alumnus

PREF_ADDRESS_TYPE - the preferred address type for the constituent

EMAIL_PRESENT_IND - a binary flag indicating if an email address is present

CON_YEARS - consecutive giving years

PrevFYGiving - the fiscal year giving for the previous fiscal year

PrevFY1Giving - the fiscal year giving for the year before the previous fiscal year

PrevFY2Giving - the fiscal year giving for two years before the previous fiscal year

PrevFY3Giving - the fiscal year giving for three years before the previous fiscal year

PrevFY4Giving - the fiscal year giving for four years before the previous fiscal year

CurrFYGiving - the fiscal year giving for the current fiscal year

TotalGiving - the total giving for the constituent

DONOR_IND - a binary flag indicating if a constituent is a donor

BIRTH_DATE - the birth date for the constituent

 
 ## Objective
 
To develop a model that will predict Red cross Donors.
 
## Requirements 
Libraries used - To succesfully run this Jupyter notebook the following libraries need to be installed.

    - Python 3     - Pandas     - Scikit-Learn     - Seaborn     - Matplotlib     - Numpy  
    
## Data Preprocessing
Preprocessing work done on the data included:

1. Outlier removal

2. Label and one hot encoding for categorical data

3. Handling of missing data by median imputation

4. Replacing missing values  with a hard coded values like zero (eg 1 for yes, 0 for none)



## Models 
1.Gradient Boosting Classifier

2.Ada Boost Classifier

3.Random Forest Classifier

4.Naive Bayes

5.K Nearest Neighbors

6.Decision Tree Classifier

7.Logistic Regression

## Results
Performance Evaluation Metric used:

1.F1 score

2.AUC score

3.Training and test accuracy

4.Confusion matrix
