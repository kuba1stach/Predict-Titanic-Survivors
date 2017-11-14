# Predict-Titanic-Survivors


#Dataset contains information about Titanic's passengers. 
#It contains information about 1309 passengers, each one is described by 12 features.
#The task is to apply the machine learning tools to predict which passengers survived.
#Dataset is divided to train and test set. Train test contains information whether or not passenger survived.
#In test set we can't find that information.
#This dataset can be used for Kaggle competition.
#You can download this dataset from: https://www.kaggle.com/c/titanic
#
#
#Description of the features:
#
#Variable	Definition					Key
#survival	Survival					0 = No, 1 = Yes
#pclass		Ticket class					1 = 1st, 2 = 2nd, 3 = 3rd
#sex		Sex	
#Age		Age in years	
#sibsp		# of siblings / spouses aboard the Titanic	
#parch		# of parents / children aboard the Titanic	
#ticket		Ticket number	
#fare		Passenger fare	
#cabin		Cabin number	
#embarked	Port of Embarkation				C = Cherbourg, Q = Queenstown, S = Southampton
#
#
#Variable Notes
#pclass: A proxy for socio-economic status (SES)
#1st = Upper
#2nd = Middle
#3rd = Lower
#
#age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
#
#sibsp: The dataset defines family relations in this way...
#Sibling = brother, sister, stepbrother, stepsister
#Spouse = husband, wife (mistresses and fiancés were ignored)
#
#parch: The dataset defines family relations in this way...
#Parent = mother, father
#Child = daughter, son, stepdaughter, stepson
#Some children travelled only with a nanny, therefore parch=0 for them.