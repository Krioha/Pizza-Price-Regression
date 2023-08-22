# Pizza-Price-Regression

The dataset used can be viewed in the file named "pizza.csv"
On Pizza Price Reggresion there is an analysis of the data used and the construction of the model employed.<br />
# EDA
**Data Distribusion**<br />
<img src="https://github.com/Krioha/Pizza-Price-Regression/blob/main/Image/DataDistibution.png?raw=true"><br />
From the above image, it can be concluded that the data distribution is normal.<br />
**Outlier**<br />
![image](https://github.com/Krioha/Pizza-Price-Regression/assets/93811161/e18e124b-095c-478b-9100-5379fdba7f93)<br />
![image](https://github.com/Krioha/Pizza-Price-Regression/assets/93811161/ed0f7246-38df-4397-87b5-45947de7c38f)<br />
Because there are not too many outliers, Outlier removal is not necessary, As the total dataset is small. <br />
**Correlation Affter Preprocessing**<br />
![image](https://github.com/Krioha/Pizza-Price-Regression/assets/93811161/2176e2a1-3dc6-4b64-bd8a-21d8fedaaa49)<br />
The price is highly correlated with two variables, namely the diameter variable and the size variable, while the company variable is negatively correlated with the price.<br />

# Result
![image](https://github.com/Krioha/Pizza-Price-Regression/assets/93811161/738e5fa0-48db-4755-a591-c3fe990edc45)<br />
![image](https://github.com/Krioha/Pizza-Price-Regression/assets/93811161/6a5b64ac-c7df-46f8-9e3d-aade78c3438f)<br />
The conclusion obtained is that the Xgboost model has the best results compared to other models, with a score of 91.91%. It also has lower RMSE and MAE values compared to other models.

