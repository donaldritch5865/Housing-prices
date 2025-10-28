# 🏡 Housing Prices Prediction

## 📘 Overview
This project aims to **predict house sale prices** using machine learning techniques. The dataset includes various features describing different aspects of residential homes, such as size, location, quality, and condition.  
Through data preprocessing, visualization, and model training, this notebook provides an end-to-end solution to understanding and predicting housing prices.

---

## 📊 Dataset
The dataset used in this project comes from the **Kaggle House Prices: Advanced Regression Techniques** competition.

**Files included:**
- `train.csv` — Training dataset containing house features and sale prices  
- `test.csv` — Test dataset without target labels  
- `submission.csv` — Final predictions ready for Kaggle submission  

**Target variable:**  
`SalePrice` — The price at which a home was sold.

---

## 🧹 Data Preprocessing
The following preprocessing steps were applied:
- Handled missing values and outliers  
- Encoded categorical variables  
- Scaled numerical features  
- Analyzed correlations between variables and sale price  

---

## 📈 Exploratory Data Analysis (EDA)
Key visualizations include:
- Distribution of `SalePrice`  
- Relationship between `OverallQual` and `SalePrice`  
- Effect of lot area, year built, and living area on price  
- Heatmap of feature correlations  

These insights helped identify important predictors influencing home values.

---

## 🧠 Model Building
The project experimented with multiple regression models:
- **Linear Regression**
- **Ridge and Lasso Regression**
- **Random Forest Regressor**
- **XGBoost**

**Evaluation Metric:**  
- Root Mean Squared Error (RMSE)  

Model performance was compared to select the most accurate and generalized model.

---

## ⚙️ Technologies Used
- **Python 3.10.12**
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost

---

## 📁 Project Structure
Housing/
│
├── House_Price_Prediction_Project.ipynb # Main notebook
├── train.csv # Training data
├── test.csv # Test data
├── submission.csv # Predicted results
└── README.md # Project documentation


---

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/donaldritch5865/Housing-prices.git
   cd Housing-prices


Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook House_Price_Prediction_Project.ipynb

🏁 Results

The best-performing model achieved strong predictive accuracy with minimal overfitting.
The analysis highlights how data cleaning, feature engineering, and model selection impact housing price predictions.

✨ Author

Donald Ritch Babu
Final-Year Software Engineering Student
📍 Parul University
