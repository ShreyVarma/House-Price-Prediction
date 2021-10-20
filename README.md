# House-Price-Prediction
Creating a Machine Learning model to predict the home prices in Bangalore, India.We are going to use the dataset from Kaggle.com. We are also going to create a single page website which will provide the front end to access our model for predictions.

Below data science concepts are used in this project

1.) Data loading and cleaning

2.) Outlier detection and removal

3.) Feature engineering

4.) Dimensionality reduction

5.) Gridsearchcv for hyperparameter tunning

6.) K fold cross validation

Technology and tools used in this project

1.) Python

2.) Numpy and Pandas for data cleaning

3.) Matplotlib for data visualization

4.) Sklearn for model building

5.) Google Colaboratory Notebook

6.) Python flask for http server

7.) HTML/CSS/Javascript for UI

Steps

We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com.
Second step would be to write a python flask server that uses the saved model to serve http requests.
Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price.

Step#1: Import the required libraries

Step#2: Load the data

Step#3: Understand the data
        -drop unnecessary columns

Step#4: Data Cleaning
        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
        - Feature Engineering
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding

Step#5: Build Machine Learning Model

Step#6: Testing The model

Step#7: Export the model

Step#8: Export any other important info

