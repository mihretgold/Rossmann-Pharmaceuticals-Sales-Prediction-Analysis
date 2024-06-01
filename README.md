# Rossmann Store Sales Prediction

## Overview
Rossmann Pharmaceuticals, a leading pharmaceutical company, has approached you as a Machine Learning Engineer to build an end-to-end product that can forecast sales in all their stores across several cities six weeks ahead of time. This project aims to develop a robust sales prediction model using machine learning techniques and serve the predictions through a web interface.

## Objectives
The key objectives of this project are:

1. **Exploration of customer purchasing behavior**: Conduct an extensive exploratory data analysis to understand the factors influencing customer purchasing behavior, such as promotions, competition, holidays, seasonality, and locality.

2. **Prediction of store sales**: Develop and fine-tune both machine learning and deep learning models to accurately predict the store sales six weeks in advance.

3. **Serving predictions on a web interface**: Build a web-based application that can serve the sales predictions to the finance team.

## Data Description
The data for this challenge can be found on [Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales/data). The dataset includes the following features:

- `Id`: an ID that represents a (Store, Date) duple within the test set
- `Store`: a unique ID for each store
- `Sales`: the turnover for any given day (this is what you are predicting)
- `Customers`: the number of customers on a given day
- `Open`: an indicator for whether the store was open: 0 = closed, 1 = open
- `StateHoliday`: indicates a state holiday
- `SchoolHoliday`: indicates if the (Store, Date) was affected by the closure of public schools
- `StoreType`: differentiates between 4 different store models: a, b, c, d
- `Assortment`: describes an assortment level: a = basic, b = extra, c = extended
- `CompetitionDistance`: the distance in meters to the nearest competitor store
- `CompetitionOpenSince[Month/Year]`: gives the approximate year and month of the time the nearest competitor was opened
- `Promo`: indicates whether a store is running a promo on that day
- `Promo2`: a continuing and consecutive promotion for some stores
- `Promo2Since[Year/Week]`: describes the year and calendar week when the store started participating in Promo2
- `PromoInterval`: describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew

## Tasks
The project is divided into the following tasks:

1. **Exploration of customer purchasing behavior**:
   - Clean and preprocess the data
   - Visualize and analyze the distribution of features in both training and test sets
   - Investigate the effects of holidays, seasonality, and promotions on customer purchasing behavior
   - Explore the relationships between various features and sales

2. **Prediction of store sales**:
   - Develop and fine-tune machine learning models (e.g., linear regression, decision trees, random forests) to predict store sales
   - Explore the use of deep learning models (e.g., neural networks, recurrent neural networks) for sales prediction
   - Compare the performance of different models and select the best-performing one

3. **Serving predictions on a web interface**:
   - Build a web-based application using a framework like Flask or Streamlit
   - Integrate the best-performing sales prediction model into the web interface
   - Allow users to input store information and receive sales predictions

## Deliverables
The deliverables for this project include:

1. Exploratory data analysis notebook
2. Machine learning and deep learning model code
3. Web-based application for serving sales predictions
4. Documentation, including a README file and any necessary reports or presentations

## Competencies Developed
By completing this project, you will develop the following competencies:

- Advanced use of scikit-learn and other machine learning libraries
- Feature engineering and selection
- Model building, tuning, and comparison
- CI/CD deployment of ML models
- Python logging and unit testing
- Building interactive dashboards and web applications
- Model management and MLOps with tools like DVC, CML, and MLFlow
