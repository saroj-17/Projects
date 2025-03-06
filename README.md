# Student Machine Learning Project

## Project Overview

This project is designed to help students build a complete machine learning pipeline using multiple algorithms, including Linear Regression, Logistic Regression, Decision Tree, and Random Forest. The project will cover Exploratory Data Analysis (EDA), preprocessing, model training, testing, evaluation, and deployment using Django.

---

## Steps to Complete the Project

### 1. Data Collection

- Obtain a dataset relevant to a classification or regression problem (e.g., house price prediction, movie genre classification, spam detection, etc.).
- Ensure the dataset is clean and well-structured (CSV format is recommended).

### 2. Exploratory Data Analysis (EDA)

- Load the dataset using Pandas.
- Display basic statistics (mean, median, missing values, etc.).
- Visualize data using Matplotlib and Seaborn (histograms, box plots, scatter plots, heatmaps, etc.).
- Identify correlations and trends.

### 3. Data Preprocessing

- Handle missing values (drop or impute data).
- Convert categorical variables using one-hot encoding or label encoding.
- Normalize or standardize numerical features if necessary.
- Split the dataset into training and testing sets (e.g., 80% train, 20% test).

### 4. Model Training and Testing

Implement the following machine learning models:

- **Linear Regression** (for regression problems)
- **Logistic Regression** (for classification problems)
- **Decision Tree Classifier/Regressor**
- **Random Forest Classifier/Regressor**

For each model:
- Train the model using the training dataset.
- Make predictions on the test dataset.
- Evaluate performance using appropriate metrics.

### 5. Model Evaluation

Use different evaluation metrics based on the problem type:

#### Regression Metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

#### Classification Metrics:
- Accuracy Score
- Precision, Recall, and F1-Score
- Confusion Matrix

### 6. Model Selection

- Compare results from all models.
- Choose the best-performing model based on evaluation metrics.
- Save the final model using joblib or pickle.

### 7. Django Deployment

- Create a Django project and app.
- Load the trained model in Django views.
- Create a form-based HTML page to accept user input.
- Process the input, pass it to the model, and display predictions.
- Run the Django server and test the application.

### 8. Project Folder Structure

![image](https://github.com/user-attachments/assets/31734400-4088-4a8f-8e4f-9648a61b574a)


### 9. Running the Project

- Install dependencies
  ```bash
  pip install -r requirements.txt

### Run Django server

``` python manage.py runserver
Access the web application Go to *http://127.0.0.1:8000/* in your browser.

