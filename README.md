# House-price-Prediction



---

# 🏡 Bengaluru House Price Prediction

A machine learning project to predict housing prices in Bengaluru based on features like location, square footage, number of bedrooms, bathrooms, and more.

---

## 📌 Table of Contents

* [Overview](#overview)
* [Dataset](Bengaluru_House_Data.csv)
* [Features Used](#features-used)
* [Technologies](#technologies)
* [Project Structure](#project-structure)
* [How to Run](#how-to-run)
* [Model Performance](#model-performance)
* [Improvements](#improvements)
* [License](#license)

---

## 📖 Overview

This project uses supervised machine learning techniques to predict house prices in Bengaluru. It involves:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Feature engineering
* Model building (e.g., Linear Regression, Decision Trees, etc.)
* Evaluation and deployment

---

## 🗃️ Dataset

The dataset used is from \[source like Kaggle or your own collection].
It contains features like:

* `location`
* `size` (e.g., 2 BHK, 3 BHK)
* `total_sqft`
* `bath`
* `price` (target variable)

---

## 🧠 Features Used

After cleaning and preprocessing, the following features were used:

* Location (after dimensionality reduction)
* Square Footage
* Number of Bathrooms
* Number of Bedrooms (BHK)

---

## 🛠 Technologies

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* Jupyter Notebook
* Flask (for deployment if applicable)
* HTML/CSS/JS (if a frontend was built)

---

## 📁 Project Structure

```
bengaluru_house_price_prediction/
│
├── data/                # Dataset and cleaned CSVs
├── notebooks/           # Jupyter Notebooks
├── model/               # Saved trained model (pickle)
├── app/                 # Flask app or deployment files
├── static/              # CSS/JS if used
├── templates/           # HTML files
├── README.md            # This file
├── requirements.txt     # Python dependencies
└── app.py               # Flask main file (if deployed)
```

---

## ▶️ How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/MaazBagwan07/House-price-Prediction.git
   cd bengaluru-house-price-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook (for model training/EDA):

   ```bash
   jupyter notebook
   ```

4. To run the Flask app:

   ```bash
   python app.py
   ```

---

## 📊 Model Performance

| Model             | R² Score | RMSE |
| ----------------- | -------- | ---- |
| Linear Regression | 0.82     | 5.20 |
| Decision Tree     | 0.85     | 4.75 |
| Random Forest     | 0.88     | 4.25 |

*Values are examples; replace with your actual metrics.*

---

## 🚀 Improvements

* Use of advanced models (XGBoost, CatBoost)
* More robust location encoding (e.g., clustering)
* Outlier detection with Isolation Forest
* Integration with live APIs (e.g., Google Maps)

---

## 📜 License

This project is open-source and available under the MIT License.

---


