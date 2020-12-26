# Linear Regression

## 1. Introduction to Linear Regression




**Linear regression**  is a  _basic_  and  _commonly_  used type of  **predictive analysis**. The overall idea of regression is to examine two things:

-   Does a set of  **predictor variables**  do a good job in predicting an  **outcome**  (dependent) variable?
-   Which variables in particular are  **significant predictors**  of the outcome variable, and in what way they do  **impact**  the outcome variable?

These regression estimates are used to explain the  **relationship between one dependent variable and one or more independent variables**. The simplest form of the regression equation with one dependent and one independent variable is defined by the formula :  
                                   𝑦=𝛽0+𝛽1𝑥


What does each term represent?
-   y  is the response
-   x  is the feature
-   β0  is the intercept
-   β1  is the coefficient for x

Three major uses for  **regression analysis**  are:

-   determining the  **strength**  of predictors,
    -   Typical questions are what is the strength of  **relationship**  between  _dose and effect_, _sales and marketing spending_, or _age and income_.
-   **forecasting**  an effect, and
    -   how much  **additional sales income**  do I get for each additional $1000 spent on marketing?
-   **trend**  forecasting.
    -   what will the  **price of house**  be in _6 months_?
    
    


## 2. Linear Regression Equation with Errors in consideration

While taking errors into consideration the equation of linear regression is:
![enter image description here](https://miro.medium.com/max/2872/1*k2bLmeYIG7z7dCyxADedhQ.png)
Generally speaking, coefficients are estimated using the **least squares criterion**, which means we are find the line (mathematically) which minimizes the **sum of squared residuals** (or "sum of squared errors"):

What elements are present in the diagram?

-   The black dots are the  **observed values**  of x and y.
-   The blue line is our  **least squares line**.
-   The red lines are the  **residuals**, which are the distances between the observed values and the least squares line.

![enter image description here](https://cdn.nextjournal.com/data/QmfPuPp4V74FyvTTojMj6ix9T8Skj1ji4GhX5Pr6zK8w4N?filename=linear-regression.png&content-type=image/png)

How do the model coefficients relate to the least squares line?

- β0  is the  **intercept**  (the value of  𝑦y  when  𝑥x  = 0)
- β1  is the  **slope**  (the change in  𝑦y  divided by change in  𝑥x)

Here is a graphical depiction of those calculations:

![enter image description here](https://i.pinimg.com/originals/ea/08/8a/ea088aec8952b49eedd7cf16b58cd283.jpg)






## 3. Assumption of Linear Regression

1.  There should be a linear and additive relationship between dependent (response) variable and independent (predictor) variable(s). A linear relationship suggests that a change in response Y due to one unit change in X¹ is constant, regardless of the value of X¹. An additive relationship suggests that the effect of X¹ on Y is independent of other variables.
2.  There should be no correlation between the residual (error) terms. Absence of this phenomenon is known as Autocorrelation.
3.  The independent variables should not be correlated. Absence of this phenomenon is known as multicollinearity.
4.  The error terms must have constant variance. This phenomenon is known as homoscedasticity. The presence of non-constant variance is referred to heteroskedasticity.
5.  The error terms must be normally distributed.
