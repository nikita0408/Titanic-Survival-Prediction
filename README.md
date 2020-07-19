# Titanic-Survival-Prediction
ABSTRACT
The sinking of the RMS Titanic caused the death of thousands of  passengers  and  crew  is  one  of  the  deadliest  maritime disasters in history. One of the reasons that the shipwreck led to such loss  of life was  that there  were not  enough lifeboats for  the  passengers  and  crew.  The  interesting  observation which comes out  from the  sinking is that some  people were more likely to survive than others, like women, children were the one who got the priority to rescue. The objective is to first explore  hidden  or  previously  unknown  information  by applying exploratory  data analytics  on available  dataset and then apply different machine learning models to complete the analysis of what sorts of people were likely to survive. After this  the  results  of  applying  machine  learning  models  are compared and analyzed on the basis of accuracy.

PROBLEM STATEMENT
Analysing data ,applying machine learning and predicting the survival in the tragedy.

SOFTWARE AND LIBRARIES
This project uses the following software and Python libraries:

Python 3.7
NumPy
pandas
seaborn
sklearn
matplotlib
iPython Notebook

MODELS IMPLEMENTED

RandomForest
Support Vector Machine
Naive Bayes
K nearest-Neighbors
DecisionTree
Logistic Regression

WORKFLOW

Classifying(Classify or categorize our samples)
Correlating(Deciding which features within the dataset contribute significantly to our solution goal)
Converting(Preparing the data depending on the choice of algorithm ,features - categorical to be converted to numerical equivalent values)
Dealing missing values(Data preparation required to estimate any missing values within a feature)
Correcting(Analyzed the dataset for errors or possibly innacurate values within features) 
Creating(Creating new features based on an existing feature that the new feature follows the correlation, conversion)
Model making and evaluation by calculating the accuracy.

SOME DATA INSIGHTS

Female passengers had much better survival rate than males.
Pclass=3 had most passengers, however most did not survive
Infant passengers in Pclass=2 and Pclass=3 mostly survived.
Most passengers in Pclass=1 survived.
Pclass varies in terms of Age distribution of passengers.
Infants (Age <=4) had high survival rate.
Oldest passengers (Age = 80) survived.
Large number of 15-25 year olds did not survive.
Most passengers are in 15-35 age range.

ACCURACY SCORES

Random Forest -	85.75
Decision Tree	- 85.75
KNN - 83.73
Support Vector Machines - 78.79
Logistic Regression -	78.56
Naive Bayes -	75.31


