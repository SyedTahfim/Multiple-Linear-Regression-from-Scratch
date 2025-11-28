# <img src="https://cdn-icons-png.flaticon.com/128/11315/11315900.png" width="20" /> Motivation 
Machine learning (ML) library like scikit learn has made it very easy to apply ML models without getting your hands dirty. As a result, it is easy forget what is happening behind the hood. Keeping this in mind, I wanted to develop linear regression model from scratch to have a clearer understanding about the math behind it and how it's done in python.

# <img src ="https://cdn-icons-png.flaticon.com/128/3295/3295476.png" width="20" /> What is linear regression?  
Linear regression is a fundamental statistical method used to model the relationship between a dependent variable and one or more independent variables. It helps us understand the relationship between variables and predict how one variable will change with respect to another one. The following figure shows what do we mean by linear relationship. It shows how a change in X (__Independant variable__) impacts y (__Dependent variable__). 

<p align="center">
    <img src="linear_relation.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
</p>
<br clear="all" />

***This repository demonstrated how to develop a very basic multiple linear regression from scratch.***  

## <img src="https://cdn-icons-png.flaticon.com/128/10152/10152820.png" width="20" /> Mathematical Foundation
- **Regression Equations:** Simple Linear Regression: $y = f(x)$; $y = wx + b$, Multiple Linear Regression: $y = x_1* w_1 + x_2 * w_2 + ...... + x_n*w_n + b$
- **Cost Function (Mean Squared Error):** $J(w,b) = (1/2m) \sum{(f(x) - y)}^2$ 
- **Gradient Descent Update:** Where \
        $w = w - \alpha \times \frac{\partial J}{\partial w}$ \
        $b = b - \alpha \times \frac{\partial J}{\partial b}$

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
*The project uses Salary_Data.csv containing:*
- **YearsExperience:** Independent variable (features)
- **Salary:** Dependent variable (target)


## <img src="https://cdn-icons-png.flaticon.com/128/4185/4185714.png" width="20" /> Key Takeways
*This implementation helps understand:*
- What are the mathematical equations involved in linear regression
- The role of derivatives in optimization and convergence
- How weight and bias works
- How to use object oriented programming
- How vectorization speeds up machine learning
- The Importance of normalization
## <img src="https://cdn-icons-png.flaticon.com/128/2065/2065169.png" width="20" /> Results
<p align="center">
    <img src="scatter_salary_experience.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
    <img src="multiple_linear_regression.png" width="45%" alt="Image 2 Description" style="float: right; margin-left: 2%;">
</p>
<br clear="all" />


