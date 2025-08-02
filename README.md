Linear Regression:
Linear Regression is a supervised learning algorithm used to predict a continuous numeric value based on one or more input features.
It assumes there is a linear relationship between the input variables (X) and the output variable (Y).
-	Easy to Understand
-	Works well when data follows a linear trend

-	Assumes linearity (fails if the relationship is non linear)
-	Performance drops if there is multicollinearity

-	Use this when u have to predict continuous outcomes e.g, prices, scores, sales
-	When data shows a linear relationship

  

Simple Linear Regression:
-	It has one input column and only one output column
-	Models a straight line relationship between X and Y
-	Use Case Example: Predicting marks based on hours studied.



 
Multiple Linear Regression:
-	It has two or more input columns (independent variables) and only one output column (dependent variable)
-	Models a straight line relationship in multi dimensional space 
-	Use Case Example: Predicting house prices based on area, number of bedrooms, location rating, and age of the house




Polynomial Linear Regression:
-	It has one input column, but the model includes higher degree powers of that input (X², X³, …)
-	Models a curved (non linear) relationship between X and Y while still being linear in terms of coefficients
-	Use Case Example: Predicting car price depreciation over years, where the price drops non linearly with time


Linear Regression (GRAPHING):
In linear regression, if we plot a graph of two columns, it must be linear.
But in case of real world data, the graph may or may not be linear due to real world factor.
<img width="678" height="496" alt="image" src="https://github.com/user-attachments/assets/a5ef7388-c158-4abc-af50-2d4b9929513c" />
This is a graph of CGPA vs Salary. As it’s a real world example. The graph isn’t linear. The factors could be anything.
This is called stochastic errors, due to which the data is sort of linear but not entirely linear.
To solve this problem easily, we draw a best fit line. It is a linear line from the origin which aims to minimize the distance between the line and all the data points



<img width="678" height="497" alt="image" src="https://github.com/user-attachments/assets/11e04ff8-e0aa-4be3-929b-1ac7b1b2e9cb" />
This is a best fit line (the red line), it does the minimum mistake in the calculations.
We use the following eq in this calculation:
y = mx+c
where m is slope and c is y-intercept

In 3D, we use:

y = mx1+nx2+b
OR

y = β0+β1x1+ β2x2  

For n-dim:

y = β0+β1x1+ β2x2 +…… βnxn
where β is called weight, tells us the weightage of each column.

In multiple linear regression, we formulate the value of coefficients using the formula:
Β = (XTX)-1 * XTY
where X = x_train, Y = y_train

Regression Metrics:
<img width="940" height="873" alt="image" src="https://github.com/user-attachments/assets/d0eff356-d5ca-4766-9fb5-7711d5ee98c3" />


<img width="940" height="537" alt="image" src="https://github.com/user-attachments/assets/94122b18-ce59-427c-9c34-e5c227e0e5d9" />

<img width="940" height="340" alt="image" src="https://github.com/user-attachments/assets/2ef0c5e7-0cef-4535-a581-f48369a3597a" />





