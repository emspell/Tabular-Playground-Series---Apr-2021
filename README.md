# Tabular-Playground-Series---Apr-2021
Synthanic - You're going to need a bigger boat

#Goal
The task wass to predict whether or not a passenger survived the sinking of the Synthanic (a synthetic, much larger dataset based on the actual Titanic dataset). For each PasengerId row in the test set, you must predict a 0 or 1 value for the Survived target.bYour score is the percentage of passengers you correctly predict, known as accuracy.

Data Dictionary
Variable	   Definition	                                    Key
survival	   Survival	                                      0 = No, 1 = Yes
pclass	     Ticket class	                                  1 = 1st, 2 = 2nd, 3 = 3rd
sex	         Sex	
Age	         Age in years	
sibsp	       # of siblings / spouses aboard the Titanic	
parch	       # of parents / children aboard the Titanic	
ticket	     Ticket number	
fare	       Passenger fare	
cabin	       Cabin number	
embarked	   Port of Embarkation	                          C = Cherbourg, Q = Queenstown, S = Southampton

Variable Notes
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.
