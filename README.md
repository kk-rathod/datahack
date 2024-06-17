#  Koushik_Krishna_Rathod_Datahack
## AIM
Our goal is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, we'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine
## In the code
Firstly ,I imported all the neccessary modules.Secondly ,imported all the dataset and filled the NaN values and preprocced with simpleImputer and One Hot Encoding for catagorical data.Preprocessed Numeric data with StandardScaler().

Have performed different alogirthms viz RandomForest , LogisticRegression and Gaussian Naive Bayes

Out of these RandomForest have performed well in ROC_AUC  , and the I tuned the the parametres using GridSearchCV to find the
 best combinations of the parametres.
