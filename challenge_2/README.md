# Prediction for Used Cars Prices

<b> A Regression problem </b>
<br/>
A challenge from [sds](https://sdsclub.com/challenges/october-challenge/?utm_content=educational&utm_campaign=2020-10-01&utm_source=email-sendgrid&utm_term=27129696&utm_medium=860148)


<div class="span5 alert alert-info">
<h3>Data Preprocessing</h3> <ol>
•Load data, EDA: check missing values, features
<br/>
•Deal with categorical features: drop<b>model_name</b> which has many unique values (1070), include<b>manufacturer_name</b> with 55 unique values as it's correlated with <b>model_name</b>
<br/>
•Deal with numerical features 
<br/>
•Build Pipeline: Normalization for numerical features and OneHotEncoding for categorical features
</div>


<div class="span5 alert alert-info">
<h3>Play with cross-validation to select best n_estimators</h3> <ol>
•Use cross_val_score
<br/>
</div>


<div class="span5 alert alert-info">
<h3>Model selection</h3> <ol>
•RandomForestRegressor: MSE: 3604622
<br/>
•RandomForestRegressor & Hyperparamter tuning: RandomizedSearchCV: MSE: 6102838
<br/>
•XGBRegressor:MSE: 2940997
<br/>
•XGBRegressor with default parameters :MSE: 2940997
<br/>
•XGBRegressor & Hyperparamter tuning: RandomizedSearchCV: MSE: 3132839
<br/>  
</div>

<div class="span5 alert alert-info">
<h3>Make prediction using chosen model & parameters</h3> <ol>
•XGBRegressor with default parameters
<br/>
•Save predicted output csv file
<br/>
</div>




