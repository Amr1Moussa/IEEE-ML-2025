and the about of data on kaggle
About Dataset
Context
This classic dataset contains the prices and other attributes of almost 54,000 diamonds. It's a great dataset for beginners learning to work with data analysis and visualization.

Content
price price in US dollars (\$326--\$18,823)

carat weight of the diamond (0.2--5.01)

cut quality of the cut (Fair, Good, Very Good, Premium, Ideal)

color diamond colour, from J (worst) to D (best)

clarity a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

x length in mm (0--10.74)

y width in mm (0--58.9)

z depth in mm (0--31.8)

depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

table width of top of diamond relative to widest point (43--95)


and we did those as preprocessing 
# handle skewed 
# prepare to X and y for spliting
# split  
# encode categ
# standradization numeric
and training 
5. Modeling and Evaluation 
▪ Train and evaluate the following models: 
o Linear Regression 
o Ridge Regression  
o Lasso Regression  
o ElasticNet  
▪ Use Mean Squared Error (MSE), RMSE, R² and R²-adjusted scores to compare models.
Linear Regression Evaluation Metrics:
Mean Squared Error (MSE): 681111.8121
Root Mean Squared Error (RMSE): 825.2950
R-squared (R²): 0.9137
Adjusted R-squared: 0.9135

Linear Regression Evaluation Metrics:
Mean Squared Error (MSE): 681111.8121
Root Mean Squared Error (RMSE): 825.2950
R-squared (R²): 0.9137
Adjusted R-squared: 0.9135

Lasso Regression Evaluation Metrics:
Mean Squared Error (MSE): 687377.4210
Root Mean Squared Error (RMSE): 829.0823
R-squared (R²): 0.9129
Adjusted R-squared: 0.9127

ElasticNet Regression Evaluation Metrics:
Mean Squared Error (MSE): 1588394.2384
Root Mean Squared Error (RMSE): 1260.3151
R-squared (R²): 0.7986
Adjusted R-squared: 0.7982
