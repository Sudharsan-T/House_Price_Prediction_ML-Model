# 🏡 Housing Price Prediction using Supervised Machine Learning

A complete regression pipeline built using **Scikit-learn** to predict house prices based on housing features. The goal is to apply core machine learning principles such as **data preprocessing**, **exploratory data analysis**, **feature engineering**, and **model evaluation** on structured tabular data.

> 📈 Achieved an R² Score of ~0.64. This project serves as a foundation for deeper exploration into regression models, hyperparameter tuning, and deployment.

---

## 📌 Repository Overview

| File/Folder                   | Description                                      |
|------------------------------|--------------------------------------------------|
| `housing_price_prediction.ipynb` | Main notebook with full pipeline implementation |
| `Housing.csv`                | Dataset containing housing data (features + target) |
| `README.md`                  | Project documentation                            |

---

## 🎯 Objective

To build a predictive model using machine learning that estimates the price of a house based on input features such as area, location, number of bedrooms, and other relevant attributes.

---

## 💡 Problem Statement

House pricing is a regression problem, where the goal is to map a set of independent variables (features) to a continuous target variable (price). Accurate housing price models help both buyers and sellers make data-driven decisions.

---

## 🧪 Technologies Used

| Tool / Library     | Purpose                               |
|--------------------|----------------------------------------|
| Python             | Programming language                   |
| Pandas, NumPy      | Data preprocessing, manipulation       |
| Matplotlib, Seaborn| Data visualization, EDA                |
| Scikit-learn       | Model building, regression, metrics    |
| Jupyter Notebook   | Interactive development & experimentation |

---

## 🔍 Workflow & Pipeline

### 1. Data Loading & Inspection
- Loaded the dataset and checked for missing values, data types, and basic statistics.

### 2. Exploratory Data Analysis (EDA)
- Visualized correlations and distributions of features.
- Identified outliers and feature-target relationships.

### 3. Data Preprocessing
- Handled missing values.
- Encoded categorical variables.
- Normalized numerical features.
- Verified data integrity post-cleaning.

### 4. Model Building
- Applied **Linear Regression** from Scikit-learn.
- Trained model on processed data.
- Evaluated using R² Score, Mean Absolute Error, Mean Squared Error.

### 5. Evaluation
| Metric               | Value     |
|----------------------|-----------|
| R² Score             | ~0.64     |
| Mean Absolute Error  | Moderate  |
| Overfitting Observed | No        |

---

## 📈 Results & Analysis

- The model performs reasonably well for a baseline approach.
- Achieved an R² score of ~0.64, indicating a moderate fit.
- Model generalizes decently to unseen data, though underfitting is possible due to limited features or model complexity.

---

## 🧠 Key Learnings

- Understood the full lifecycle of an ML regression problem.
- Learned the importance of data preprocessing in real-world datasets.
- Interpreted model evaluation metrics to identify strengths and limitations.
- Practiced effective feature encoding and transformation.

---

## 🔮 Possible Enhancements

| Area                    | Proposed Improvement                     |
|-------------------------|-------------------------------------------|
| Feature Engineering     | Add more features (e.g., location score, age of house) |
| Model Complexity        | Try non-linear models: Random Forest, XGBoost, SVR |
| Validation Strategy     | Use K-Fold Cross-Validation               |
| Hyperparameter Tuning   | Implement GridSearchCV or RandomizedSearchCV |
| Deployment              | Build a web interface using Streamlit or Flask |

---

## 📁 Dataset Information

- Format: CSV
- Features: Area, Location, Bedrooms, Bathrooms, etc.
- Target: Housing Price
- Dataset Source: [View Dataset](https://github.com/Sudharsan-T/House_Price_Prediction_ML-Model/blob/main/Housing.csv)

---

## 📌 Quick Access

- 📘 [Notebook - housing_price_prediction.ipynb](https://github.com/Sudharsan-T/House_Price_Prediction_ML-Model/blob/main/housing_price_prediction.ipynb)
- 📂 [Dataset - Housing.csv](https://github.com/Sudharsan-T/House_Price_Prediction_ML-Model/blob/main/Housing.csv)
- 🌐 [GitHub Repository](https://github.com/Sudharsan-T/House_Price_Prediction_ML-Model)

---

## 👨‍💻 About Me

Hi, I’m **Sudharsan**, a computer science student passionate about building real-world applications using data science and machine learning. This project marks a step forward in my journey to master predictive modeling and apply it to practical use cases.

- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/sudharsan-thirumalai-85361b1a4/)
- 💼 Actively exploring data-focused internships and junior ML roles
- 📧 Open to feedback, suggestions, or collaborations!

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

