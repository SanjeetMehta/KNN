# Classification using K Nearest Neighbor
Classification model to predict the investment risk based on certain features.
Features:
- Salary
- Number of dependents(max. 4)
- EMI/RENT of house.
- Savings

Formulas used:
EMI/RENT= 0-50% of Salary [0-50% is randomly generated]
SAVINGS= Salary- EMI/RENT- (Number of dependents * 0.10 * Salary)  [considering that each dependent of family requires 10% of salary, we have considered maximum of 4 dependents]

Classification of different classes i.e Very low risk taker, Low risk taker, High risk taker, Very high risk taker
--> If savings< 15000 - Very low or 10
--> If savings>15000 and savings<25000 - Low or 20
--> If savings>25000 and savings<40000 - High or 30
--> If savings>40000 - Very High or 40
