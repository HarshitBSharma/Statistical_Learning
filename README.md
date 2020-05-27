### Statistical Learning
My notes from Intro to Statistical Learning by Gareth James,  Daniela Witten, trevor Hastie and Robert Tibshirani. 


## Intro notes
When tackling a problem using Machine Learning, always explore the data first. Find out if there are any correlations.

Variables can be either classified as quantitative(numerical) or qualitative(categories). So, a problem with a quantitative response is called a regression problem, and a problem with a qualitative response is called as classification problem.

Usually, in machine learning problems, for given parameters(X), out the prediction(ˆY). Or, in mathematical terms, an estimated function ˆf(X) such that ˆY = ˆf(X) + c, where c is some constant. Now there is a real function f(X) which gives out correct predictions every time, and we wish that our defined function ˆf(X) should be as close to f(X) as possible. We can categorize our prediction functions as flexible or non-flexible. 

Non Flexible function: Function consisting of linear polynomials 

Flexible function: Function consisting of higher order polynomials 

So if we want to give the best fit to our data, we might argue to use a flexible function, right? No! Since flexible functions can try to fit data which might be mislabelled, and perform poor on data which the function has not seen before. This is called overfitting, which is due to high variance. On the other hand, if the best fit to the data is actually non-linear, using a linear fit(Non-flexible) function will
give us poor performance of the function on data which it hasn't seen before.


## Algorithms
# Linear Regression
Linear Regression assumes that there is a linear relation between the input features and the output.

In mathematical terms, we could say that Y ≈ β0 + β1X
In a simple case, where we have a single input feature x and the output y, we can represent the function as y = mx + c

where, m = slope and c = y_intercept
In a machine learning model m and c are called parameters of the model

