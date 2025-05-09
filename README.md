# House-Pricing-Predication

Overview 
This is a project to predict house sale prices. We use a Linear Regression model 
trained on some features in the Ames Housing dataset. The model relies on 
numerical features, such as ground living area, total material quality, year of 
construction, and size of garage cars, to make predictions on the market value of 
a property.

Dataset 
Source: train. csv function the Ames Housing dataset (popular in Kaggle 
competitions) 

Features Used 
GrLivArea:  Above ground living area (in square feet) 
OverallQual:  Rates the overall material and finish of the house (Ordinal) 
YearBuilt:  Year that the house was built 
GarageCars:  Size of garage in car capacity 

Target 
SalePrice:  Final sale price of the house

Steps 
1. Import Libraries:  Loaded necessary libraries for data processing, 
visualization, modeling and evaluation. 
2. Load The Data:  Loaded the housing data (train. csv) using pandas. 
3. Preliminary Exploration (optional):  prepared for preliminary checks 
such as datatypes and summary statistics (commented out) 
4. Choose Features & Target:  You have been asked to build a regression 
model to predict house prices using 4 features (GrLivArea, OverallQual, 
YearBuilt, GarageCars) and provided the target (SalePrice). Remove 
missing values from the data. 
5. Correlation Heatmap :  It would show the correlation between features 
and target variable and with this, we could decide which features are 
important. 
6. Define X and y:  Defined feature matrix X and target y for modeling. 
7. Train-Test Split:  Partition the data into a training and test set (80% 
training, 20% testing). 
8. Feature Scaling: Performed standardization on the features with 
StandardScaler. 
9. Train Model:  Fit a LinearRegression model on the scaled train data. 
10. Cross-Validation: Model generalization was assessed using 5-fold cross
validated R² scores. 
11. Predict:  Predicted the saleprice on testing dataset using trained model. 
12. Model Evaluation:  Performed Mean Squared Error (MSE) and R² score 
on test data to evaluate performance. 
13. Interpret Coefficients:  Show feature coefficients to interpret how each 
variable affects prediction. 
14. Actual vs Predicted Plot:  Plotted to see how much we were able to 
predict the sale price. 
15. Residual Plot: Considers the plotted residuals to determine if the patterns 
or bias exist in predictions. 
16. Distribution of Residuals: Plotted to check for normality and meet model 
assumptions.

Outputs 
• Correlation Heatmap 
• Actual vs Predicted Prices Plot 
• Residuals Plot 
• Residual Distribution
