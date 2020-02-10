# Finding Donors for Charity

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing) 


## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

CharityML is a fictitious charity organization that provides financial support for people learning machine learning. In an effort to improve donor outreach effectiveness, I will build an algorithm that best identifies potential donors. My goal here is to evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation yield. 

1. Model Application: List three of the supervised learning models above that are appropriate for this problem that you will test on the census data. For each model chosen:
  - Describe one real-world application in industry where the model can be applied.
  - What are the strengths of the model; when does it perform well?
  - What are the weaknesses of the model; when does it perform poorly?
  - What makes this model a good candidate for the problem, given what you know about the data?


2. Choosing the Best Model, Describing the Model in Layman's Terms.
3. Effects of Feature Selection:
  - How does the final model's F-score and accuracy score on the reduced data using only five features compare to those same scores when all features are used?
  - If training time was a factor, would you consider using the reduced data as your training set?


## Results<a name="results"></a>
 
I have used various supervised learning techniques like Logistic regression, Support Vector Machine(SVM) and Gradient Boosting Classifier to predict possible donors. Adaboost Classifier is also used as part of the ranking most important features from training data. The final Model has been tuned using a grid search(GridSearchCV) functionality.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Feel free to use the code here as you would like! 
