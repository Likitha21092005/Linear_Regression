
# Linear Regression:

## 📌 Introduction

**Linear Regression** is a supervised machine learning algorithm used to predict a **continuous value** based on one or more input variables. It models the relationship between independent variables and a dependent variable using a straight line.



## 📈 Simple Linear Regression

**Simple Linear Regression** involves **one independent variable** and **one dependent variable**.

### 📐 Equation

[
y = mx + b
]

Where:

* `y` = dependent variable (output)
* `x` = independent variable (input)
* `m` = slope (rate of change)
* `b` = intercept (value of y when x = 0)

### 🧠 Idea

It tries to find the best-fit straight line that minimizes the error between predicted values and actual values.

### 🧪 Example

Predicting:

* House price based on **size**
* Salary based on **years of experience**


## 📊 Multiple Linear Regression

**Multiple Linear Regression** uses **more than one independent variable** to predict a dependent variable.

### 📐 Equation

[
y = b_0 + b_1x_1 + b_2x_2 + \dots + b_nx_n
]

Where:

* `y` = dependent variable
* `x₁, x₂, ..., xₙ` = independent variables
* `b₀` = intercept
* `b₁, b₂, ..., bₙ` = coefficients

### 🧠 Idea

Each independent variable contributes to the prediction, and the model learns how important each variable is.

### 🧪 Example

Predicting:

* House price based on **size, location, number of rooms**
* Student performance based on **study time, attendance, sleep hours**



## 📉 Assumptions of Linear Regression

* Linear relationship between variables
* No or little multicollinearity
* Homoscedasticity (constant variance of errors)
* Errors are normally distributed
* Independence of observations



## 🎯 Applications

* Price prediction
* Trend analysis
* Risk assessment
* Forecasting



## ✅ Summary

| Type                       | Independent Variables |
| -------------------------- | --------------------- |
| Simple Linear Regression   | One                   |
| Multiple Linear Regression | More than one         |



## 📚 Conclusion

Linear Regression is one of the simplest and most interpretable machine learning algorithms. Understanding both simple and multiple linear regression forms the foundation for more advanced predictive models.


