# Automobile-Price-Prediction
An end-to-end Machine Learning regression project that predicts automobile prices using vehicle specifications. Includes data preprocessing, exploratory data analysis (EDA), feature engineering, multiple regression models, model comparison, and performance evaluation for accurate price prediction.
# 🚗 Automobile Price Prediction using Machine Learning

## 📌 Project Overview

Automobile pricing depends on various factors such as brand, engine size, fuel type, horsepower, vehicle dimensions, and other technical specifications. This project aims to build a Machine Learning regression model that predicts the price of an automobile based on its features.

The project follows a complete data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple regression algorithms to identify the best-performing model.

---

## 🎯 Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle missing values and duplicate records
- Perform feature engineering and encoding
- Train multiple regression models
- Compare model performance using evaluation metrics
- Recommend the best model for production deployment

---

## 📂 Dataset Information

The dataset contains automobile specifications and pricing information.

### Features

- Symboling
- Normalized Losses
- Make
- Fuel Type
- Aspiration
- Number of Doors
- Body Style
- Drive Wheels
- Engine Location
- Wheel Base
- Length
- Width
- Height
- Curb Weight
- Engine Type
- Number of Cylinders
- Engine Size
- Fuel System
- Bore
- Stroke
- Compression Ratio
- Horsepower
- Peak RPM
- City MPG
- Highway MPG
- Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Dataset overview
- Missing value analysis
- Duplicate value detection
- Statistical summary
- Univariate analysis
- Bivariate analysis
- Correlation heatmap
- Feature distribution
- Outlier detection
- Data visualization

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Removing duplicate records
- Feature engineering
- Encoding categorical variables
- Feature scaling (where required)
- Train-Test Split

---

## 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor *(Optional)*
- XGBoost Regressor *(Optional)*

---

## 📈 Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Best Model Selection
12. Conclusion

---

## 📁 Project Structure

```
Automobile-Price-Prediction/
│
├── data/
│   └── auto_imports.csv
│
├── notebook/
│   └── AutoPricePred.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── residual_plot.png
│   └── prediction_plot.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/TanmayPatel143/Automobile-Price-Prediction.git
```

### 2. Navigate to the project folder

```bash
cd Automobile-Price-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```
AutoPricePred.ipynb
```

---

## 📌 Results

- Performed comprehensive Exploratory Data Analysis (EDA).
- Applied data preprocessing and feature engineering techniques.
- Trained and evaluated multiple regression models.
- Compared model performance using R² Score, MAE, MSE, and RMSE.
- Selected the best-performing regression model for automobile price prediction.

---

## ⚠️ Challenges Faced

- Handling missing values in multiple features.
- Encoding categorical variables for machine learning models.
- Managing feature correlations and multicollinearity.
- Preventing model overfitting.
- Selecting the most suitable regression algorithm.

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
- Deploy the model using Flask, FastAPI, or Streamlit.
- Integrate real-time automobile pricing data.
- Improve prediction accuracy using ensemble and boosting techniques.
- Build an interactive web application for price prediction.

---

## 👨‍💻 Author

**Tanmay Patel**

GitHub: https://github.com/TanmayPatel143

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
