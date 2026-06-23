# 🏠 California Housing Price Prediction ML

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-teal?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 🚀 End-to-End Machine Learning Project for California Housing Price Prediction

Predicting California housing prices using **Machine Learning**, **EDA**, **Feature Engineering**, **Regression Models**, and **Hyperparameter Optimization**.

</div>

---

# 📌 Project Overview

This project focuses on building a complete Machine Learning pipeline for predicting California housing prices based on demographic, geographic, and housing-related features.

The project includes:

✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Data Visualization  
✔ Correlation Analysis  
✔ Feature Engineering  
✔ Regression Model Training  
✔ Hyperparameter Tuning  
✔ Model Evaluation  
✔ House Price Prediction System  
✔ Model Serialization using Joblib  

---

# 🗂️ Project Structure

```bash
CALIFORNIA-HOUSING-PRICE-PREDICTION/
│
├── 📁 Data_set/
│   └── housing.csv
│
├── 📁 models/
│   ├── x_train.pkl
│   ├── x_test.pkl
│   ├── y_train.pkl
│   ├── y_test.pkl
│   └── best_model.pkl
│
├── 📁 src/
│   ├── 1_data_preprocessing.ipynb
│   ├── 2_model_training.ipynb
│   ├── 3_evaluation.ipynb
│   └── 4_prediction.ipynb
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Joblib | Model Saving & Loading |

---

# 📊 Exploratory Data Analysis (EDA)

Extensive Exploratory Data Analysis was performed to understand the dataset and identify patterns affecting house prices.

### 🔍 EDA Includes

- Missing Value Analysis
- Duplicate Detection
- Feature Distribution Analysis
- Outlier Detection
- Correlation Analysis
- Target Variable Distribution
- Categorical Feature Analysis

---

# 📈 Visualizations

The project includes multiple visualizations such as:

✅ Target Variable Distribution  
✅ Histogram Distributions  
✅ Boxplots for Outlier Analysis  
✅ Correlation Heatmaps  
✅ Ocean Proximity Countplots  
✅ Residual Analysis Plots  

---

# 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Missing Value Imputation
- Standard Scaling
- One-Hot Encoding
- Feature Transformation
- Train-Test Splitting
- ColumnTransformer Pipeline

---

# 🤖 Machine Learning Models

The following regression models were implemented and evaluated:

| Model | Status |
|---|---|
| Linear Regression | ✅ Tested |
| Ridge Regression | ✅ Tested |
| Lasso Regression | ✅ Tested |
| Random Forest Regressor | ✅ Tested |
| HistGradientBoosting Regressor | ✅ Best Performance |

---

# 🏆 Best Performing Model

## ✅ HistGradientBoosting Regressor

The HistGradientBoosting model achieved the best overall performance after hyperparameter optimization.

### Techniques Used

- K-Fold Cross Validation
- GridSearchCV
- Hyperparameter Optimization
- RMSE-Based Evaluation

---

# 📌 Evaluation Metrics

The models were evaluated using:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score
- Residual Analysis

---

# 💾 Model Serialization

The trained model was saved using **Joblib** for future predictions.

```python
joblib.dump(best_model, "best_model.pkl")
```

---

# 🔮 House Price Prediction System

A custom prediction function was implemented to estimate California housing prices based on user input features.

```python
predict_house_price()
```

### Example Prediction

```python
prediction = predict_house_price(
    longitude=-122.23,
    latitude=37.88,
    housing_median_age=41.0,
    total_rooms=880.0,
    total_bedrooms=129.0,
    population=322.0,
    households=126.0,
    median_income=8.3252,
    ocean_proximity="NEAR BAY"
)
```

---

# ▶️ Installation & Usage

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/CALIFORNIA-HOUSING-PRICE-PREDICTION.git
```

---

## 2️⃣ Navigate to Project

```bash
cd CALIFORNIA-HOUSING-PRICE-PREDICTION
```

---

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open notebooks from:

```bash
src/
```

---

# 📚 Dataset Information

Dataset used for this project:

🔗 https://www.kaggle.com/datasets/camnugent/california-housing-prices

---

# 📌 Dataset Features

| Feature | Description |
|---|---|
| longitude | Geographical longitude |
| latitude | Geographical latitude |
| housing_median_age | Median age of houses |
| total_rooms | Total rooms in block |
| total_bedrooms | Total bedrooms in block |
| population | Population in block |
| households | Number of households |
| median_income | Median household income |
| ocean_proximity | Distance from ocean |

---

# 🎯 Target Variable

| Target | Description |
|---|---|
| median_house_value | Median house value in California |

---

# 🚀 Future Improvements

Planned future enhancements:

- 🌐 Flask/FastAPI Deployment
- 📊 Streamlit Dashboard
- ☁ Cloud Deployment
- 📱 Interactive Web Application
- 🔍 Advanced Ensemble Models
- ⚡ Real-Time Prediction API

---

# 📷 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
EDA & Visualization
     ↓
Feature Engineering
     ↓
Train/Test Split
     ↓
Preprocessing Pipeline
     ↓
Model Training
     ↓
Hyperparameter Tuning
     ↓
Model Evaluation
     ↓
House Price Prediction
```

---

# 👨‍💻 Author

## Dilshan Nethmin Wijayarathne

💻 Data Science Undergraduate

🤖 AI & Machine Learning Enthusiast

📊 Data Analytics and Intelligent Systems Developer

🌐 Full Stack Developer

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
🛠️ Contribute to improvements  

---

<div align="center">

## 🚀 Thanks for Visiting

### 🏠 California Housing Price Prediction using Machine Learning

</div>
