# Loan_Case_Prediction

This project was done to fulfill course requirements for *Machine Learning with Python*. The project explores different classification algorithms to predict whether a loan will be paid off or go into collection. The different models are then evaluated for accuracy to find the best model.

## Data
The datasets contain information about past loans. Two datasets are used in this project. One to build and train the models. And the other to evaluate the accuracy of the models.

Training Data = https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/loan_train.csv
Testing Data = https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/loan_test.csv

Description of columns:
* Loan_status: whether a loan is paid off or in collection
* Principal: principal loan amount
* Terms: payoff schedule which can be weekly, biweekly or monthly
* Effective_date: when the loan became effective
* Due_date: loan due date
* Age: age of loan applicant
* Education: education level of applicant
* Gender: applicant's gender

### Python Modules
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Seaborn

## Method
1. Import Data
2. Data visualization and pre processing
3. Feature Selection
4. Model Development
    * K Nearest Neighbor
    * Decision Tree
    * Support Vector Machine
    * Logistic Regression
5. Model Evaluation
    * Jaccard Similarity Score
    * F1 Score
    * Log Loss
