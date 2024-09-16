
# Student_Performance_Using_ML

Student performance analysis and prediction using datasets has become an
essential component of modern education systems. With the increasing
availability of data on student demographics, academic history, and other
relevant factors, schools and universities are using advanced analytics and
machine learning algorithms to gain insights into student performance and
predict future outcomes.


## OBJECTIVE

 - The primary objective of higher education institutions is to impart quality
education to their students.
 - By using all ML Algorithm, tried to find best ML technique which is best
for my data sets and for prediction results for client.



## UNDERSTANDING THE PROBLEM
- This project understands how the student’s performance (test scores) is affected
by other variables such as Gender, Ethnicity, Parental level of education, and
Lunch and Test preparation course.
## METHODOLOGY USED
We worked on these methods to enhance the accuracy of ML methods for the
student performance.

    1) Linear Regression
    2) Ridge Regression
    3) Lasso Regression
    4) Random Forest Regression
    5) Support Vector Regression
    6) K-Neighbors
    7) Decision Tree
## FLOW OF THE PROJECT
    (1) Data gathering and journals references.
    (2) Data pre processing.
    (3) Training and Testing, Model parameters, evaluation, hyper-tuning etc.
    (4) Proper visualisation and assessment on obtained result and then come to
    conclusion.
    (5) Choose the best model which gives highest possibility of result in accuracy
    so that we know which parameters students marks can increase or decrease.
    (6) Final prediction.
## DATASET


### Dataset Source :-
www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977

### Dataset Features :-
    a) gender : sex of students -> (Male/female)
    b) race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
    c) parental level of education : parents' final education ->(bachelor's
    degree,some college,master's degree,associate degree,high school)
    d) lunch : having lunch before test (standard or free/reduced)
    e) test preparation course : complete or not complete before test
    f) math score
    g) reading score
    h) writing score
## DATA PREPROCESSING

### Data Checks to perform

    ➢ Check Missing values
    ➢ Check Duplicates
    ➢ Check data type
    ➢ Check the number of unique values of each column
    ➢ Check statistics of data set
    ➢ Check various categories present in the different categorical column

### Adding columns for "Total Score" and "Average"
### Exploring Data ( Visualization )
    1. Histogram
    2. Kernel Distribution Function (KDE)
    3. Histogram & KDE
    4. Gender Column
    5. Heatmap of initial dataset 
    6. Pair-plot for Numerical Features of Dataset

### Final Feature selection
Mutual information (MI) between two random variables is a non-negative
value, which measures the dependency between the variables. It is equal to zero
if and only if two random variables are independent, and higher values mean
higher dependency.

This method basically utilize the mutual information. It calculates mutual
information value for each of independent variables with respect to dependent
variable, and selects the ones which has most information gain. In other words,
it basically measures the dependency of features with the target value. The
higher score means more dependent variables.

    I(X ; Y) = H(X) – H(X | Y) Where I(X ; Y) is the mutual information for X and
    Y, H(X) is the entropy for X and H(X | Y) is the conditional entropy for X given
    Y. The result has the units of bits.
## MODEL TRAINING AND MODEL SELECTION
### 1. Model Training [ Result 1 ]
Target variable --> Maths score

### 2. Model Training [ Result 2 ]
Target variable --> Average score

### 3. Model Training [ Result 3 ]
Target variable --> Average score [ with Top 10 features ]

### Final Result
- Table

![Table Screenshot](https://github.com/ashishkumarak/Student_Performance_Prediction_Using_ML/blob/fca9e831b0277942a9aeead1fccce13e899a6dab/Table.jpg)

- Line plot

![Line Screenshot](https://github.com/ashishkumarak/Student_Performance_Prediction_Using_ML/blob/fca9e831b0277942a9aeead1fccce13e899a6dab/line_plot.jpg)

- Bar plot

![Bar Screenshot](https://github.com/ashishkumarak/Student_Performance_Prediction_Using_ML/blob/fca9e831b0277942a9aeead1fccce13e899a6dab/bar_plot.jpg)


## CONCLUSION

This brings us to an end to the student’s performance prediction. Let us review our work. First, we started by defining our problem statement, looking into the algorithms we were going to use and the regression implementation pipeline. Then we moved on to practically implementing the identification and regression algorithms like Linear Regression, Ridge, Lasso, K-Neighbors Regressor, Decision Tree, Random Forest Regressor. Moving forward, we compared the performances of these models. Lastly, we built a Linear regression model that proved that it works best for student performance prediction problems.

The key takeaways from this  student performance prediction are:

- Identification of student performance prediction is important for many institutions.
- Linear,Ridge,Lasso gives better accuracy compared to other regression problems.
- Linear regression is the best fit for the problem
- Linear regression provides an accuracy of 94.28243 , giving out the most accurate results.


### Thank you
