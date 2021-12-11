# Breast Cancer Detection using SVM & KNN
![Breast Cancer detection](https://images.unsplash.com/photo-1598884143267-586d90a32141?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1173&q=80)
# Breast cancer prediction Project

 ## Business Problem  
An end to end modelling to help detect breast cancer in patients.
 
 ## The dataset
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

 
 ## Objective
 
To develop a model that will predict if the patien has benign cancer or a malignant one.
 
## Requirements 
Libraries used - To succesfully run this Jupyter notebook the following libraries need to be installed.

    - Python 3     - Pandas     - Scikit-Learn     - Seaborn     - Matplotlib     - Numpy  
    
## Data Preprocessing
Preprocessing work done on the data included:



1. Handling of missing data by median imputation


## Models 
1. Support Vector Machine

2. K Nearest Neighbors


## Results
Performance Evaluation Metric used:

1.F1 score

2.Precision

3.Recall

4.Support

5.Confusion matrix
