# 🏠 House Price Prediction

Machine Learning project for predicting house prices using regression models.  
This project includes data exploration, cleaning, preprocessing, model training, evaluation, and visualization.

---

## 📌 Project Overview

The goal of this project is to build and compare machine learning models for predicting house prices based on various property features.

Two regression models are implemented:

- **Linear Regression**
- **Random Forest Regressor**

The project also generates visualizations to better understand the data and model performance.

---

## 📂 Project Structure

```

House-Price-Prediction/
│
├── analysis.ipynb          # Main Jupyter notebook
├── Housing.csv             # Dataset
├── charts/
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   └── model_results.png
├── README.md
└── requirements.txt

````

---

## 📊 Dataset

**Dataset:** Housing Prices Dataset

Features include:

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Preferred Area
- Furnishing Status

**Target Variable**

- `price`

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📋 Workflow

### 1. Data Loading and Exploration

- Load the housing dataset
- Inspect shape and columns
- Check missing values
- Generate descriptive statistics

### 2. Data Cleaning

- Remove duplicate records
- Handle missing values
- Encode categorical variables using Label Encoding

### 3. Model Building

#### Linear Regression

Used as a baseline model for house price prediction.

#### Random Forest Regressor

Used to improve prediction performance and capture non-linear relationships.

---

## 🔀 Train-Test Split

- Training Set: 80%
- Testing Set: 20%
- Random State: 42

---

## 📈 Evaluation Metrics

Models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📊 Visualizations

### 1. House Price Distribution

Shows how prices are distributed across the dataset.

### 2. Correlation Heatmap

Displays relationships among numerical features.

### 3. Actual vs Predicted Prices

Compares model predictions with actual house prices.

### 4. Feature Importance

Highlights the most influential features in the Random Forest model.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
````

Move into the project directory:

```bash
cd House-Price-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open the notebook:

```bash
jupyter notebook analysis.ipynb
```

Run all cells sequentially to:

1. Load the dataset.
2. Preprocess the data.
3. Train both models.
4. Evaluate performance.
5. Generate visualizations.

---

## 📦 Required Libraries

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🎯 Results

The Random Forest Regressor generally performs better than Linear Regression by capturing complex relationships between housing features and prices.

---

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Cross-validation
* XGBoost and Gradient Boosting models
* Model deployment using Flask or Streamlit

---

```
```
