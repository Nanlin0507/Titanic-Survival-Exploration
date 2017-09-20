# Titanic-Survival-Exploration
# From a sample of the RMS Titanic data, we can see the various features present for each passenger on the ship:
# Survived: Outcome of survival (0 = No; 1 = Yes)
# Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
# Name: Name of passenger
# Sex: Sex of the passenger
# Age: Age of the passenger (Some entries contain NaN)
# SibSp: Number of siblings and spouses of the passenger aboard
# Parch: Number of parents and children of the passenger aboard
# Ticket: Ticket number of the passenger
# Fare: Fare paid by the passenger
# Cabin Cabin number of the passenger (Some entries contain NaN)
# Embarked: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

# After several iterations of exploring and conditioning on the data, you have built a useful algorithm for predicting the survival of each passenger aboard the RMS Titanic. The technique applied in this project is a manual implementation of a simple machine learning model, the decision tree. A decision tree splits a set of data into smaller and smaller groups (called nodes), by one feature at a time. Each time a subset of the data is split, our predictions become more accurate if each of the resulting subgroups are more homogeneous (contain similar labels) than before. The advantage of having a computer do things for us is that it will be more exhaustive and more precise than our manual exploration above.
