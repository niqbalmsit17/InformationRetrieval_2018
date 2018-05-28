# Information Retreival Project

Project has been done by.

  - Naveed Iqbal
  - Abdul Samad
  - Usama Ilyas

# Steps of Project

 - Installing Anaconda navigator with python 3.6.3
 - Insallation of Conda for setting up python environment
 - Installation of python packages 
            - Numpy 
            - OS 
            - CSV
            - NLTK
            - Collections
            - SKlearn 
            - Matplotlib 
            - Seaborn Library
            - Pandas

# Data Sets!

### DBworld Email Dataset
    It contains 64 emails which have been manually collected from DB_World's mailing list. It is binary classification problem. Classes are i) Announcement of Conferences and ii) Everything else. There are 7642 attributes
## Steps for Naive Bayes
        - Reading DB-World CSV file
        - Splitting dataset in 80-20 ratio
        - Applying Naive Bayes Classifier on training data
        - Make predictions on test data
        - Calculating accuracy, which was 84.62%
        - Generating classification report with the following 
             precision    recall  f1-score   support

          0       1.00      0.60      0.75         5
          1       0.80      1.00      0.89         8

avg / total       0.88      0.85      0.84        13
        
## Steps for KNN Classifier

        - Reading DB-World CSV file
        - Splitting dataset in 80-20 ratio
        - Evaluate algorithm for different vlaues of K i.e 1,3,5,7,9,11,13,15
        - Best Accuracy calculated on K=9 i.e 76.92%
        - Generated Classificatin report 
        - Precision = 86
        - Generated confusion matrix
        - only 3 records were misclassified

## Steps for Rocchio Classifier

        - Reading DB-World CSV file
        - Splitting dataset in 80-20 ratio
        - Evaluate algorithm and calculated Precision. i.e 86
        - Calculations were made based on Euclidion Distance
        - Accuracy = 76.92%
        - Generated Classificatin report 
        - Precision = 86
        - Generated confusion matrix
        - only 3 records were misclassified
        

