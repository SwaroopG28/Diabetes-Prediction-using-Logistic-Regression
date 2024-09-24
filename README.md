# Diabetes Prediction using Logistic Regression

This project aims to predict whether a patient has diabetes based on medical data using a Logistic Regression model. The model is trained on the Pima Indians Diabetes Dataset and stored for later use in making predictions.

## Project Structure

- **diabetes.csv**: The dataset used to train the model. It includes various medical features (e.g., glucose level, BMI).
- **Diabetes.ipynb**: A Jupyter notebook that contains the data analysis, preprocessing, model training, and evaluation steps.
- **Diabetesmodel.pkl**: A trained Logistic Regression model stored in pickle format.
- **Predict.py**: A Python script for loading the trained model and making predictions on new data.

- Usage
Training the Model:
You can use the Diabetes.ipynb notebook to understand the data, preprocess it, and train a Logistic Regression model. The notebook contains detailed steps for:

Data cleaning and preprocessing
Splitting the data into training and testing sets
Training the Logistic Regression model
Evaluating the model's accuracy and performance
Making Predictions:
The Predict.py script is used to load the saved model (Diabetesmodel.pkl) and make predictions on new patient data. Ensure the model file is in the same directory as Predict.py.


Model
The model used in this project is Logistic Regression, a simple yet effective classifier that predicts the probability of a binary outcome (diabetes or not) based on the input features like glucose levels, BMI, age, and insulin levels.


