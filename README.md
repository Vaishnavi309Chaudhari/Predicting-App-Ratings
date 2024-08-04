# Google Play Store App Ratings Prediction

This repository contains the code and documentation for a project aimed at predicting Google Play Store app ratings. By leveraging machine learning techniques, this project provides insights to developers on how to improve their apps and increase user satisfaction, downloads, and engagement.

## Aim of the Project

- Create a model to predict Google Play Store app ratings to help developers improve their apps.
- Use data from app ratings, reviews, and other features to predict ratings accurately.
- Provide developers with insights into the factors affecting app ratings.
- Increase user satisfaction, app downloads, and engagement on the Google Play Store.

## Problem Statement

App ratings are crucial for success on the Google Play Store. High ratings lead to more downloads and revenue, while low ratings can harm app performance. Understanding the factors affecting app ratings helps developers enhance user experience.

The project aims to predict app ratings using features such as category, size, number of installs, and price. Additionally, it includes the deployment of a user-friendly interface for non-technical clients.

## Data Cleaning and Transformation

- Converted the Date variable to `datetime` datatype.
- Dropped null values in the Ratings column.
- Converted app size from string to numerical data (e.g., extracted `19` from `19 MB`).
- Used label encoding for categorical variables (Category, Content Rating, and Paid).
- Performed feature selection and visualized data insights using Power BI.

## Model Building

- Performed feature extraction using PCA (Principal Component Analysis).
- Built and evaluated various models: Decision Tree, Random Forest, Bagging Meta Estimator, Gradient Boosting, and XGBoost.
- Selected Random Forest as the final model due to its best performance and resistance to overfitting.

## Deployment

- Deployed the model using Gradio, an open-source Python library.
- Gradio provides a web application interface for inputting unseen data and getting predicted values based on the model.
- The deployment can collaborate with Google Colab files for easy integration.

## Business Insights

- High app ratings lead to more downloads and increased revenue.
- Low ratings can decrease app visibility and harm revenue.
- Understanding the factors affecting app ratings helps developers enhance user satisfaction.
- Better app ratings can boost user engagement and competitiveness in the market.

