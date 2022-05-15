# carzone-django-project

Car Zone - A Used Car Selling Business Website. 

The basic scenario of this project is, its a website for a car business owner who wants to list his cars on his website and 
allow the user to come to his site and browse through all of his latest cars and featured cars, search and filter the cars by model or price, 
and make some inquiries about his cars that are out for the sale.

In this Bootstrap template is implemented and turn it into websites's front-end. Customization of default Django 
admin panel is done and converted it into a feature-rich, good-looking admin area. Login with Google & Login with Facebook is also implemented to 
attract users into created website.

## About the website

- Implemented HTML/Bootstrap template & Customized Django Admin Panel
- Setup Virtual Environment
- Created Django Apps
- Database Schema, Models and Migrations
- Implemented RichText Editor & Multi-Select Fields on Admin Backend
- Fetched Database Objects
- Pagination
- Search Functionality
- User Authentication
- Login with Facebook & Login with Google
- Database Dump Data & Load Data (local & remote)

Installation with pip:

```bash
pip install -r requirements.txt
```

## Getting Started
Open the terminal in you machine and run the following command to access the web application in your localhost.
```bash
streamlit run app.py
```

## Files
- notebook/Prima_Indians_Diabetes_Prediction.ipynb : Jupyter Notebook with all the workings including pre-processing, modelling and inference.
- app.py : Streamlit App script
- requirements.txt : pre-requiste libraries for the project
- models/ : trained model and scaler objects
- data/ : source data
- setup.sh : Setup file for Heroku.
- Procfile : To trigger the app in Heroku.

## Summary
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
All patients here are females at least 21 years old of Pima Indian heritage. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
Business Goal - To build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes?


## Acknowledgements

[Kaggle](https://kaggle.com/), for providing the data for this problem statement.
