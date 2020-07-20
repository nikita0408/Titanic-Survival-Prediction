# Titanic-Survival-Prediction
ABSTRACT<br>
The sinking of the RMS Titanic caused the death of thousands of  passengers  and  crew  is  one  of  the  deadliest  maritime disasters in history. One of the reasons that the shipwreck led to such loss  of life was  that there  were not  enough lifeboats for  the  passengers  and  crew.  The  interesting  observation which comes out  from the  sinking is that some  people were more likely to survive than others, like women, children were the one who got the priority to rescue. The objective is to first explore  hidden  or  previously  unknown  information  by applying exploratory  data analytics  on available  dataset and then apply different machine learning models to complete the analysis of what sorts of people were likely to survive. After this  the  results  of  applying  machine  learning  models  are compared and analyzed on the basis of accuracy.<br>

PROBLEM STATEMENT<br>
Analysing data ,applying machine learning and predicting the survival in the tragedy.<br>

DATASET<br>
train.csv contains the details of a subset of the passengers(name, age, price of ticket, etc)on board (891 passengers)<br>
test.csv does not have a "Survived" column (we need to predict this)<br>

SOFTWARE AND LIBRARIES<br>
This project uses the following software and Python libraries:<br>

Python 3.7<br>
NumPy<br>
pandas<br>
seaborn<br>
sklearn<br>
matplotlib<br>
iPython Notebook<br>

MODELS IMPLEMENTED<br>

RandomForest<br>
Support Vector Machine<br>
Naive Bayes<br>
K nearest-Neighbors<br>
DecisionTree<br>
Logistic Regression<br>

WORKFLOW<br>

Classifying(Classify or categorize our samples)<br>
Correlating(Deciding which features within the dataset contribute significantly to our solution goal)<br>
Converting(Preparing the data depending on the choice of algorithm ,features - categorical to be converted to numerical equivalent values)<br>
Dealing missing values(Data preparation required to estimate any missing values within a feature)<br>
Correcting(Analyzed the dataset for errors or possibly innacurate values within features) <br>
Creating(Creating new features based on an existing feature that the new feature follows the correlation, conversion)<br>
Model making and evaluation by calculating the accuracy.

SOME DATA INSIGHTS<br>

Female passengers had much better survival rate than males.<br>
Pclass=3 had most passengers, however most did not survive<br>
Infant passengers in Pclass=2 and Pclass=3 mostly survived.<br>
Most passengers in Pclass=1 survived.<br>
Pclass varies in terms of Age distribution of passengers.<br>
Infants (Age <=4) had high survival rate.<br>
Oldest passengers (Age = 80) survived.<br>
Large number of 15-25 year olds did not survive.<br>
Most passengers are in 15-35 age range.<br>

ACCURACY SCORES<br>

Random Forest -	85.75<br>
Decision Tree	- 85.75<br>
KNN - 83.73<br>
Support Vector Machines - 78.79<br>
Logistic Regression -	78.56<br>
Naive Bayes -	75.31<br>


