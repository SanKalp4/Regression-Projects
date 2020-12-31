# BlackFridayRepo - Analytics Vidhya_Datahack
Beginning of my journey in real world of datascience. 

Problem Statement - 

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

The goal is to build a model to predict the purchase amount of customer against various products which will help the company to create personalized offer for customers against different products.


Update 1:
1st published model in supervised learning with Linear Regression implemented on Black_Friday practice problem offered by Datahack(Analytics Vidhya).
Will be subsequently improving score implementing other models in due time.

Update 2:
Tried optimising the model with Decision Tree regressor resulting a better public LB score. The R2 score came to 0.44.

Update 3:
R2 score updated to 0.68 using random forest and 0.67 using XGB. Will subsequently implement PCA and Randomised search with RF( as this is a very large dataset GridSearchCV will probably fry my computer or I will get bored) and introduced those removed dummy variables to see if the model improves.
