# 🍽️ Messy Food Waste Prediction – Data Analysis & Machine Learning

## 📌 Project Overview
This project solves a real-world data analysis problem using a deliberately messy dataset.  
The goal is to predict food waste (kg) generated in a cafeteria based on operational, environmental, and historical factors.

The dataset simulates common real-world issues such as missing values, inconsistent data types, extreme values, and categorical inconsistencies. The project demonstrates end-to-end data analysis, from raw data cleaning to final prediction.

---

## 🎯 Objectives
- Clean and preprocess messy real-world data
- Perform exploratory data analysis (EDA)
- Engineer meaningful features
- Train and compare multiple regression models
- Select the best-performing model using MAE
- Generate final predictions and export them to CSV

---

## 📂 Dataset Description
**Source:** Kaggle – Messy Food Waste Prediction Dataset

### Key Features
- `date` – Date of measurement  
- `meals_served` – Number of meals served  
- `kitchen_staff` – Number of staff working  
- `temperature_C` – Cafeteria temperature  
- `humidity_percent` – Humidity level  
- `special_event` – Whether a special event occurred  
- `past_waste_kg` – Previous food waste  
- `staff_experience` – Experience level of staff  
- `waste_category` – Type of food waste  
- `food_waste_kg` – Target variable  

---

## ⚠️ Data Challenges Addressed
- Inconsistent data types and text casing
- Missing values (~8%)
- Extreme and unrealistic values
- Duplicate and noisy records
- Feature scaling issues

---

## 🧹 Data Cleaning & Preprocessing
- Converted string-based numerical columns to numeric
- Standardized categorical text values
- Handled missing values using statistical imputation
- Treated outliers using clipping
- Removed duplicates
- Generated data profiling reports (before and after cleaning)

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to:
- Analyze distributions and trends
- Identify correlations between features
- Detect anomalies impacting predictions

Visualizations and summary statistics guided feature engineering and model selection.

---

## 🛠 Feature Engineering
- Extracted time-based features from date
- Encoded categorical variables using One-Hot and Ordinal Encoding
- Scaled numerical features using StandardScaler

---

## 🤖 Model Training & Evaluation
### Models Tested
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

### Evaluation Metric
- Mean Absolute Error (MAE)

### Results
| Model | MAE |
|------|-----|
| Linear Regression | 5.55 |
| Random Forest Regressor | **4.99** |
| XGBoost Regressor | 5.69 |

The Random Forest Regressor achieved the best performance and was selected as the final model.

---

## 📈 Final Output
- Trained Random Forest model
- Final predictions generated on test data
- Predictions saved as a CSV file ready for submission or deployment

---

## 🧰 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- YData Profiling  
- Kaggle Notebook  

---

## 💡 Key Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression modeling
- Model evaluation and selection
- Real-world dataset handling

---

## 📌 Conclusion
This project demonstrates the complete data analysis lifecycle on messy real-world data and highlights the importance of data quality, feature engineering, and proper model evaluation in predictive modeling.

---

## 📬 Contact
For freelance data analysis or machine learning projects, feel free to connect via GitHub or Upwork.
