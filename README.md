# 🏠 House Price Prediction using Linear Regression

## 📌 Overview

This project predicts California house prices using a **Linear Regression** model built with **Scikit-Learn**.

The objective of this project was not only to build a regression model but also to understand the complete machine learning workflow, including data exploration, preprocessing, model training, and evaluation.

---

## 📂 Dataset

This project uses the **California Housing Dataset** provided by Scikit-Learn.

It contains **20,640** housing records with features such as:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

Target Variable:

- **MedHouseVal** (Median House Value)

---

## 🛠️ Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## 📊 Project Workflow

### 1. Load Dataset

- Loaded the California Housing Dataset using Scikit-Learn.

### 2. Explore the Data

- Checked dataset information
- Viewed summary statistics
- Checked for missing values
- Calculated feature correlations
- Visualized important relationships using scatter plots

### 3. Feature Selection

Features (`X`):

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

Target (`y`):

- MedHouseVal

### 4. Train/Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

using `train_test_split()`.

### 5. Feature Scaling

Applied **StandardScaler** to standardize the feature values before training.

The scaler was fitted only on the training data and then used to transform both the training and testing datasets to prevent data leakage.

### 6. Model Training

A **Linear Regression** model from Scikit-Learn was trained using the training data.

### 7. Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 📈 Results

| Metric | Value |
|---------|-------|
| Mean Absolute Error | **0.533** |
| Mean Squared Error | **0.556** |
| R² Score | **0.576** |

The model explains approximately **57.6%** of the variation in house prices.

---

## 📚 Concepts Practiced

- Regression
- Linear Regression
- Correlation Analysis
- Feature Scaling
- StandardScaler
- Train/Test Split
- Model Evaluation
- MAE
- MSE
- R² Score

---

## 🚀 Future Improvements

Possible improvements include:

- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor
- Hyperparameter Tuning
- Cross Validation
- Feature Engineering

---

## 📷 Sample Workflow

```
Load Dataset
      ↓
Explore Data
      ↓
Visualize Data
      ↓
Feature Scaling
      ↓
Train/Test Split
      ↓
Train Linear Regression
      ↓
Predict House Prices
      ↓
Evaluate Model
```

---

## 👨‍💻 Author

**Abdullah Nawaz**

This project is part of my Machine Learning learning roadmap, where I build practical projects while studying machine learning concepts.
