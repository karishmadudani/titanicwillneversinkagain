# titanicwillneversinkagain
Kaggle_Titanic_V1


data webwork.train;
infile datalines dsd missover;
length PassengerId Survived Pclass Name $ 82;
input PassengerId Survived Pclass Name $ Sex $ Age SibSp Parch Ticket $ Fare Cabin $ Embarked $;
datalines;
