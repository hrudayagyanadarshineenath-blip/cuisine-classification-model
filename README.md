# 🍽️ Cuisine Classification Model

This project is a **Machine Learning model that predicts the cuisine of a restaurant** based on information available in the Zomato dataset.

I created this project to understand how machine learning can be used to classify restaurants into different cuisine categories. It was also a good practice project for working with real-world restaurant data, preprocessing, feature engineering, and model evaluation.

## 📌 About the Project

The model uses restaurant-related information such as location, restaurant details, and other available features to predict the cuisine category.

The main goal of this project is to build a classification model that can learn patterns from existing restaurant data and use those patterns to predict the cuisine of a restaurant.

## 📊 Dataset

The project uses the **Zomato restaurant dataset**.

The dataset contains information about restaurants, including details such as:

* Restaurant name
* City
* Cuisines
* Average cost for two
* Aggregate rating
* Votes
* Location
* Latitude and longitude
* Price range
* Other restaurant-related information

Before training the model, the data was cleaned and prepared so that it could be used for machine learning.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

## 🔄 Project Workflow

The project follows these main steps:

1. Load the Zomato dataset
2. Explore the dataset
3. Check missing values and duplicate records
4. Clean and preprocess the data
5. Select the required features
6. Convert categorical data into a machine-readable format
7. Split the data into training and testing sets
8. Train the classification model
9. Evaluate the model
10. Save the trained model for future use

## 🤖 Machine Learning

A classification model was trained using the processed restaurant data.

The model learns from the existing examples in the dataset and tries to identify patterns related to different cuisine categories.

Feature preprocessing was handled using a **Scikit-learn Pipeline**, which made it easier to apply the same preprocessing steps consistently during training and prediction.

## 💾 Saved Model

After training, the model was saved using **Joblib**.


cuisine_classification_model.pkl

The .pkl file contains the trained machine learning model, which can be loaded later without having to train the model again.

## 📈 Model Evaluation

The trained model was evaluated using the test data to check how well it performs on data that it had not seen during training.

The evaluation helped me understand the model's classification performance and the challenges involved in predicting cuisine categories from real-world restaurant data.

## 🎯 What I Learned

Working on this project helped me understand:

* How to work with a real-world dataset
* Data cleaning and preprocessing
* Handling categorical features
* Building a machine learning classification model
* Using Scikit-learn pipelines
* Evaluating a classification model
* Saving and loading trained models using Joblib
* Applying machine learning to a practical problem

## 🚀 How to Run the Project

### 1. Clone the repository


