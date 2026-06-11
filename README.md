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

📷 Add Screenshot Here

![Dataset Preview](screenshots/dataset_preview.png)

---

## Correlation Heatmap

📷 Add Screenshot Here

![Heatmap](screenshots/heatmap.png)

---

## Pairplot Analysis

📷 Add Screenshot Here

![Pairplot](screenshots/pairplot.png)

---

## Model Comparison (R² Score)

📷 Add Screenshot Here

![Model Comparison](screenshots/model_comparison.png)

---

## RMSE Comparison

📷 Add Screenshot Here

![RMSE Comparison](screenshots/rmse_comparison.png)

---

## Actual vs Predicted Prices

📷 Add Screenshot Here

![Prediction Plot](screenshots/prediction.png)

---

## Feature Importance

📷 Add Screenshot Here

![Feature Importance](screenshots/feature_importance.png)

---

## Residual Plot

📷 Add Screenshot Here

![Residual Plot](screenshots/residual_plot.png)

---

# 🏆 Results

| Model                   | RMSE       | R² Score   |
| ----------------------- | ---------- | ---------- |
| Linear Regression       | Add Result | Add Result |
| Ridge Regression        | Add Result | Add Result |
| Decision Tree Regressor | Add Result | Add Result |

### Best Performing Model

🏅 Add Your Best Model Here

---

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
