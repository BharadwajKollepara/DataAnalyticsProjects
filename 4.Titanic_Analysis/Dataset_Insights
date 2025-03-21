# Dataset Description:

## 1. Data Overview

* Total Entries: 887
* Columns: 8

## 2. Types of Data:
* Numerical: Survived, Pclass, Age, Siblings/Spouses Aboard, Parents/Children Aboard, Fare
* Categorical: Name, Sex

## 3. Column Description

* Survived (0 = No, 1 = Yes) → Indicates whether the passenger survived.
* Pclass (1st, 2nd, 3rd) → Passenger class.
* Name → Passenger's full name.
* Sex → Gender of the passenger.
* Age → Age of the passenger.
* Siblings/Spouses Aboard → Number of siblings or spouses aboard.
* Parents/Children Aboard → Number of parents or children aboard.
* Fare → Ticket price paid by the passenger.
# Dataset Observations:

## Visualisation Insights: 
1. Survival Rate Observations
* Only ~38% of passengers survived, while ~62% perished.
* Women had a much higher survival rate (~74%) compared to men (~18%).
* Children (age < 10) had a better chance of survival than adults.
2. Gender and Survival Insights
* ~74% of females survived, while only ~18% of males survived.
* “Women and children first” policy led to a higher survival rate for women.
* Male survival was much lower, especially in 3rd Class (~13%).
3. Summary:
* Higher class, higher fare, and being female or a child greatly increased survival chances.
* Men in 3rd class had the worst survival rate (~13%).
* Passengers with large families struggled to survive.

## Logistic Regression Model insights:

* Dropping irrelevant columns (Name, PassengerId, Ticket)
* Handling missing values by filling missing Age values with the mean.

Data cleaning and preprocessing steps are performed, such as:

* Filling missing Cabin values based on Survived and Pclass.
* Filling missing Embarked values with "S".
* Printing some of the dataset's categorical features (Sex, Embarked, Pclass).

* One-hot encoding the Cabin column using pd.get_dummies().
* Dropping categorical features (Pclass, Sex, Embarked, and Cabin) and replacing them with the encoded versions.
* Defining the features (X) and the target (y):
    * X → Contains the independent variables (features).
    * y → Contains the target variable (Survived).
