# Data-Science
## Must know ML Algorithms for Data Science
<h1>Linear regression</h1>

> Linear regression is a statistical model used to predict the relationship between dependent and independent variable.

> Examine two factors:
  - Which variables in particular are significant predictors of the outcome variables?
  - How significant is the Regression line to make predictions with highest possible accuracy?
  
### The simplest form of a simple linear regression equation with one dependent and one independent variable is represented by:
   **y=mx+c**
  - Where,
    **y** ---> Dependent Variable  
          
    **x** ---> Independent Variable
    
    **m** ---> Slope of the line  
    
    **c** ---> Intercept
  -  **m** = (y2-y1)/(x2-x1)
    
![Linear Regression](/images/regression.png)

### Prediction using the linear regression:

![Plot1](/images/prediction1.png)

> Plotting the amount of Crop Yield based on the amount of Rainfall




![Plot2](/images/prediction2.png)

> The Red point on the Y axis is the amount of Crop Yield you can expect for some amount of Rainfall (X) represented by Green dot 


### Profit estimation of companies with linear regression using 1000_Companies.csv [[Jupyter Notebook Link]](https://github.com/sobit-nep/Data-Science/blob/main/regression.ipynb)
  - r2_score [ coefficient of determination (R-squared) ] value is found to be ***0.9114714505439288***
![Correlation matrix](/images/matrix.png)

<h1>Logistic regression</h1>

> Logistic regression is a machine learning algorithm that is used for classification tasks, where the output variable is categorical. It is a type of supervised learning algorithm that predicts the probability of a certain outcome based on input features.

> The logistic regression algorithm models the relationship between the input features and the output variable using a logistic function. The logistic function is an S-shaped curve that maps any input value to a value between 0 and 1, which can be interpreted as a probability. The logistic regression algorithm calculates the parameters of the logistic function by minimizing the error between the predicted probabilities and the actual outcomes in the training data.
> Logistic regression uses an equation as the representation, very much like linear regression.

> Input values (x) are combined linearly using weights or coefficient values (referred to as the Greek capital letter Beta) to predict an output value (y). A key difference from linear regression is that the output value being modeled is a binary values (0 or 1) rather than a numeric value.

> Below is an example logistic regression equation:

> y = e^(b0 + b1*x) / (1 + e^(b0 + b1*x))

> Where y is the predicted output, b0 is the bias or intercept term and b1 is the coefficient for the single input value (x). Each column in your input data has an associated b coefficient (a constant real value) that must be learned from your training data.

> Logistic regression can be used for binary classification problems, where the output variable has only two possible values, such as 0 or 1. In this case, the algorithm predicts the probability that the output variable is equal to 1.

> Logistic regression can also be used for multi-class classification problems, where the output variable has more than two possible values. In this case, the algorithm uses a one-vs-all approach, where it trains one logistic regression model for each class, and then predicts the class with the highest probability.

> Overall, logistic regression is a simple and effective algorithm for classification tasks, and is widely used in many fields, such as finance, healthcare, and marketing.

<h3>Logistic Function</h3>

> Logistic regression is named for the function used at the core of the method, the logistic function.

> The logistic function, also called the sigmoid function was developed by statisticians to describe properties of population growth in ecology, rising quickly and maxing out at the carrying capacity of the environment. It’s an S-shaped curve that can take any real-valued number and map it into a value between 0 and 1, but never exactly at those limits.

> 1 / (1 + e^-value)

![SIGMOID FUNCTION](https://github.com/sobit-nep/Data-Science/assets/65544518/33445062-6b7d-4774-96dd-8633f3b722db)
### Logistic regression is implemented using iris data loaded from seaborn [[Jupyter Notebook Link]](https://github.com/sobit-nep/Data-Science/blob/main/logistic_regression_implementation.ipynb)

<h1>Decision tree</h1>
<h1>Random forest</h1>
<h1>KNN</h1>
<h1>SVM</h1>
<h1>Naive Bayes</h1>
<h1>Clustering</h1>
