# Team3: Titanic Project

The project aimed to determine the number of passengers that survived the titanic disaster.

## Understanding the Data

### Data Description

`survival` - Survival (Yes = 1, No = 0)

`Pclass` - Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).  A proxy for socio-economic status, 1st = upper, 2nd = middle, 3rd = lower

`Age` - Age in years. Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5

`sex` - Passengers' gender

`sibsp` - Number of siblings / spouses aboard the Titanic. The dataset defines family relations in this way:
    Sibling = brother, sister, stepbrother, stepsister
    Spouse = husband, wife (mistresses and fiancés were ignored)
    
`Parch` - Number of parents / children aboard the Titanic. The dataset defines family relations in this way:
    Parent = mother, father
    Child = daughter, son, stepdaughter, stepson
    Some children travelled only with a nanny, therefore parch=0 for them.
    
`Ticket` - Ticket Number

`Fare` - Passenger Fare

`cabin` - Cabin Number

`embarked` - Port of Embarkation (C = Cherboug, Q = Queenstown, S = Southampton)

## Modeling
Using a `RandomForestClassifier`, we got a model with an accuracy of 87.4%
