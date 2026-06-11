
# 🏠 House Price Prediction using Feature Engineering & Model Optimization

### Artificial Intelligence & Machine Learning Internship – Task 2

This project focuses on improving house price prediction using Feature Engineering, Feature Scaling, and Model Comparison techniques on the California Housing Dataset.

The objective is to evaluate multiple machine learning models and identify the best-performing model based on RMSE and R² Score.

---

# 📖 Project Overview

In this project, a complete machine learning workflow was implemented, including:

✅ Data Loading & Exploration

✅ Feature Engineering

✅ Feature Scaling

✅ Model Training

✅ Model Evaluation

✅ Model Comparison

✅ Data Visualization

---

# 🎯 Objectives

* Load and explore the California Housing Dataset
* Create new engineered features
* Apply feature scaling using StandardScaler
* Train multiple machine learning models
* Compare model performance
* Evaluate models using RMSE and R² Score
* Visualize results using graphs

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

# 📊 Dataset Information

Dataset Used: California Housing Dataset (Scikit-Learn)

### Features

| Feature    | Description       |
| ---------- | ----------------- |
| MedInc     | Median Income     |
| HouseAge   | House Age         |
| AveRooms   | Average Rooms     |
| AveBedrms  | Average Bedrooms  |
| Population | Population        |
| AveOccup   | Average Occupancy |
| Latitude   | Latitude          |
| Longitude  | Longitude         |

### Target Variable

🏠 Median House Price

---

# ⚙️ Feature Engineering

A new feature was created:

### RoomsPerPerson

```python
RoomsPerPerson = AveRooms / Population
```

This engineered feature provides additional information about room availability relative to population density.

---

# 🔧 Feature Scaling

StandardScaler was used to normalize numerical features before training the models.

Benefits:

* Better model performance
* Improved optimization
* Reduced scale-related bias

---

# 🤖 Machine Learning Models

The following regression models were trained and compared:

### 1️⃣ Linear Regression

Baseline model used for comparison.

### 2️⃣ Ridge Regression

Regularized Linear Regression model that helps reduce overfitting.

### 3️⃣ Decision Tree Regressor

Tree-based model capable of learning non-linear relationships.

---

# 📈 Evaluation Metrics

Model performance was evaluated using:

### RMSE (Root Mean Squared Error)

Measures prediction error.

### R² Score

Measures how well the model explains the variance in the target variable.

---

# 📝 Code Workflow

The notebook follows the following structure:

### Step 1 – Import Libraries

Import all required Python libraries.

### Step 2 – Load Dataset

Load California Housing Dataset and create a DataFrame.

### Step 3 – Data Exploration

* Dataset Overview
* Statistical Summary
* Missing Value Check

### Step 4 – Feature Engineering

Create the RoomsPerPerson feature.

### Step 5 – Feature Scaling

Apply StandardScaler.

### Step 6 – Model Training

Train:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

### Step 7 – Model Evaluation

Calculate:

* RMSE
* R² Score

### Step 8 – Model Comparison

Compare all models and identify the best-performing model.

### Step 9 – Visualization

Generate graphs for performance analysis.

---

# 📸 Project Screenshots

## Dataset Preview



<img width="940" height="289" alt="Screenshot 2026-06-04 145521" src="https://github.com/user-attachments/assets/eed81065-162b-447c-9c01-110d913ffcd2" />

---

## Correlation Heatmap


<img width="1026" height="736" alt="Screenshot 2026-06-04 143442" src="https://github.com/user-attachments/assets/8391e8ae-e77c-4db2-9492-1f879e04a1c0" />


## Pairplot Analysis

<img width="669" height="634" alt="image" src="https://github.com/user-attachments/assets/1bf9f416-cc82-48f3-ade5-aea28ec94592" />

## Model Comparison (R² Score)

<img width="882" height="524" alt="image" src="https://github.com/user-attachments/assets/38b95e89-c5db-4088-8d37-5b33bf834a42" />


## RMSE Comparison

<img width="854" height="509" alt="image" src="https://github.com/user-attachments/assets/91371443-c422-475f-a5a7-4c3b9123ddd9" />


## Actual vs Predicted Prices

<img width="767" height="715" alt="image" src="https://github.com/user-attachments/assets/15b4c677-22b5-4783-ab5c-4e5fc12e3602" />


## Feature Importance
<img width="752" height="473" alt="image" src="https://github.com/user-attachments/assets/26f54955-01b0-4155-94fb-9007488ee048" />


## Residual Plot
<img width="949" height="555" alt="image" src="https://github.com/user-attachments/assets/c7772a59-1e1b-4606-b387-0aaf9cb69077" />

# 🏆 Results

| Model                   | RMSE       | R² Score   |
| ----------------------- | ---------- | ---------- |
| Linear Regression       | 0.745      | 0.578      |
| Ridge Regression        | 0.745      | 0.576      |
| Decision Tree Regressor | 0.713      | 0.613      |

### Best Performing Model

🏅 Add Your Best Model Here

 Decision Tree Regressor

# 📂 Project Structure

```text
House-Price-Prediction-Model-Comparison/
│
├── task2_model_comparison.ipynb
├── report.pdf
├── README.md
├── requirements.txt
│
└── screenshots/
    ├── dataset_preview.png
    ├── heatmap.png
    ├── pairplot.png
    ├── model_comparison.png
    ├── rmse_comparison.png
    ├── prediction.png
    ├── feature_importance.png
    └── residual_plot.png
```

---


# 🔮 Future Improvements

* Hyperparameter Tuning
* Random Forest Regressor
* XGBoost
* Cross Validation
* Advanced Feature Engineering

---

# 👨‍💻 Author

**Mohit Rajak**

B.Tech Computer Science & Engineering

Artificial Intelligence & Machine Learning Intern

---

⭐ If you found this project interesting, consider giving it a star.
