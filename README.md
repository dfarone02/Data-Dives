# Titanic-DataDive

This DataDive is an attempt to use a lasso regression to see if based on the given varibales and data in the Titanic_Data.csv that a person can predict if a passenger was French rather than just looking at survival.

The Titanic_Data.csv file info:

    PassengerId: a passenger's unique number 
    
    Survived: 0 or 1 representing Surivived or Not Survived 
    
    Pclass: Passenger Class 1, 2, or 3
    
    Name: Passenger's name (very dirty)
    
    Sex: "male" or "female"
    
    Age: integer value of the passenger age
    
    SibSp: integer value for how many siblings or spouses a passenger brought with them
    
    Parch: integer value for how many children or parents a passenger is associated with
    
    Ticket: Passenger ticket number (text value)
    
    Fare: Cost of the tiket (float value)
    
Ultimately, the lasso regression model can only effectively predict a passenger being French at 12%, 
which is greater prediction power than expected, but insignifcicant nonetheless.
