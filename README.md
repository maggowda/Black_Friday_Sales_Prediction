# Black Friday Sales Prediction

# Dataset Information

This dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand your feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem. The dataset has 550,069 rows and 12 columns.

**Problem:** Predict purchase amount

## Attributes:
| Column ID |         Column Name        | Data type |           Description           | Masked |
|:---------:|:--------------------------:|:---------:|:-------------------------------:|--------|
|     0     |           User_ID          |   int64   |      Unique Id of customer      | False  |
|     1     |         Product_ID         |   object  |       Unique Id of product      | False  |
|     2     |           Gender           |   object  |         Sex of customer         | False  |
|     3     |             Age            |   object  |         Age of customer         | False  |
|     4     |         Occupation         |   int64   |   Occupation code of customer   | True   |
|     5     |        City_Category       |   object  |         City of customer        | True   |
|     6     | Stay_In_Current_City_Years |   object  | Number of years of stay in city | False  |
|     7     |       Marital_Status       |   int64   |    Marital status of customer   | False  |
|     8     |     Product_Category_1     |   int64   |       Category of product       | True   |
|     9     |     Product_Category_2     |  float64  |       Category of product       | True   |
|     10    |     Product_Category_3     |  float64  |       Category of product       | True   |
|     11    |          Purchase          |   int64   |         Purchase amount         | False  |

**Download link:** https://www.kaggle.com/kkartik93/black-friday-sales-prediction

# Libraries

<li>pandas
<li>matplotlib
<li>seaborn
<li>scikit-learn
<li>streamlit

# Algorithms

<li>Linear Regression
<li>Decision Tree
<li>Random Forest
<li>Extra Tress

# Deployment 
The deployment of this app is done with streamlit.

![Screenshot 2025-01-09 074331](https://github.com/user-attachments/assets/8bb4b9bb-8391-4064-8733-8e653b67c3a1)

**Live Demo:** https://blackfridaysalesprediction-va2xpfkntgfrwsx5mxb7gp.streamlit.app
