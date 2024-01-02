This Project aims to predict the price of the car providing the few details such as Manufacturer, Model and so on.
The data was extracted from the Kijii website using the web crawling techniques such as Selenium and BeautifulSoup library.
Once the data is acquired from the website, Performed below steps to build the car prediction.

---------------------------------------------------------------
Steps Involved in the project:
1. Data Cleaning 
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Development
6. Model Evaluation
7. Model Validation 

------------------------------------------------

1. Data Cleaning: 

i) Once we gathered the data, I found that a columns such as Price, Mileage are supposed to be in numeric format but the values were in a categorical form and contains symbols like "$". 
ii) Hence performed data cleaning on the columns using the Regrex library in python

2. Data Preprocessing:

i) After cleaning the data, Performed the missing value imputation, Checked for any duplication of records in the data and so on.

3. Exploratory Data Analysis:

i) Performed EDA on the data.

4. Feature Engineering:

i) Checked the correlation on the columns and only the relevant features were selected.
ii) Performed the Outlier detection on the data.
iii) Using one hot encoding, Performed the categorical encoding

5. Model Development and Evaluation:

i) Build Regression models, Random Forest Regressor, and Gradient Boosting Regressor model and evaluated the model with the r2_score on the models.

ii) Got an accuracy of 73 and 75 % on train and test respectively.

6. Model Validation:

i) Manually verified the model by passing the certain values.

Future Scope:

i) Will acquire more data to train the model and predict the car price.
ii) Need to integrate this model as a web app for better user experience and deploy on the cloud.

