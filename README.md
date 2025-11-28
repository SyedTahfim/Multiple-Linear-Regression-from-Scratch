# What is linear regression?  
Linear regression is a fundamental __statistical method__ used to model the relationship between a dependent variable (must be a __continuous variable__) and one or more independent variables. It helps us understand the relationship between variables and predict how one variable will change with respect to another one. \
In this repository, we demonstrated how to develop a very basic mulitiple regression model from scratch using only numpy library.  

<p align="center">
    <img src="scatter_salary_experience.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
    <img src="multiple_linear_regression.png" width="45%" alt="Image 2 Description" style="float: right; margin-left: 2%;">
</p>
<br clear="all" />

## <img src="https://cdn-icons-png.flaticon.com/128/10435/10435158.png" width="20" /> Features
- **Cost Function**: Mean Squared Error (MSE) implementation
- **Gradient Descent Optimization:** Manual calculation of gradients for parameter updates
- **Data Visualization:** Scatter plots and regression line visualization
## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
*The project uses Salary_Data.csv containing:*
- **YearsExperience:** Independent variable (features)
- **Salary:** Dependent variable (target)

## <img src="https://cdn-icons-png.flaticon.com/128/10152/10152820.png" width="20" /> Mathematical Foundation
- **Linear Regression Equation:** $f(x) = wx + b$
- **Cost Function:** $J(w,b) = (1/2m) \sum{(f(x) - y)}^2$ 
- **Gradient Descent Update:** Where \
        $w = w - \alpha \times \frac{\partial J}{\partial w}$ \
        $b = b - \alpha \times \frac{\partial J}{\partial b}$

## <img src="https://cdn-icons-png.flaticon.com/128/4185/4185714.png" width="20" /> Key Takeways
*This implementation helps understand:*
- How linear regression works mathematically
- The role of derivatives in optimization
- How to use object oriented programming
- How learning rate affects training
- The relationship between cost and model performance


