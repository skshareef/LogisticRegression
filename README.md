# LogisticRegression

#Some of the classification algorithms are:
#Logistic regression
#Naive Bayes
#Support Vector Machines
#Decision Tree
3 / 12
Logistic regression
Logistic Regression
Basic yet important classification algorithm in machine
leaning.
Although it contains Regression in its name it is a
classification algorithm.
Regression algorithms predict continuous values. Linear
regression is one such algorithm and can be used to predict
weight from height.
Logistic regression is another regression algorithm. It
predicts a continuous value. But in this case, the
continuous value is the probability of a particular
classification such as predicting whether the person
survives or not
Mostly used for binary classification algorithm
4 / 12
Logistic regression
Why Logistic Regression?
Consider a scenario we use linear regression to find the best
linear regression aims at minimizing the distance between
predicted values and actual graph for linear regression
5 / 12
Logistic regression
Why Logistic Regression
If there is a outlier present in the data, the line of linear
regression changes.
Hence threshold value also changes
Another problem with linear regression is the predicted
may exceed ’1’ or go below ’0’.
6 / 12
Logistic regression
Logistic regression
To overcome these problems, we use logistic regression
logistic regression converts the best fit linear line into a
sigmoid function, which always gives values between 0 and
1.
7 / 12
Logistic regression
Logistic Function
We all know the equation of the best fit line in linear
regression is:
y = β0 + β1x1
Let say, we will use consider y as P
P = β0 + β1x1
8 / 12
Logistic regression
Logistic Function
We known the probability values lies between in the range
of (0,1)
But the above equation have range of (−∞, +∞)
To overcome this issue we take the odds of P
p
1 − p
= β0 + β1x1
9 / 12
Logistic regression
Logistic Function
The Range of the Odds lies between and (0, ∞)(always
positive)
The range becomes limited and we don’t want a restricted
range(which decreases the number of points)
To overcome this we use log of odds which has range of
(-∞, +∞) :
log(
p
1 − p
) = β0 + β1x1
10 / 12
Logistic regression
Logistic Function
To get the function of p, we will multiply by exponent on
both sides
exp(log( p
1 − p
)) = exp(β0 + β1X)
e
log(
p
1 − p
)
= e
β0+β1X
p
1 − p
= e
β0+β1X
p =
e
(β0 + β1X)
1 + e
(β0 + β1X)
11 / 12
Logistic regression
Logistic regression
After solving we get,
p =
1
1 + e−(β0 + β1X)
this is our Signoid function
