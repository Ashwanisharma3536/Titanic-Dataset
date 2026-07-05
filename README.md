
# Titanic Survival Prediction using Machine Learning
A Machine Learning classification project that predicts whether a passenger survived the Titanic disaster based on passenger information. Multiple machine learning models were trained, optimized using GridSearchCV, and compared to identify the best-performing model.

# 📌 Project Overview

The objective of this project is to build a predictive model that determines whether a passenger survived the Titanic disaster.

The project covers the complete Machine Learning workflow including:

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation
- Performance Comparison
- Best Model Selection

# 📂 Dataset

**Dataset:** Titanic Survival Dataset

### Features
- Passenger Class (Pclass)
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

### Target Variable
- **Survived**
  - 0 = Did Not Survive
  - 1 = Survived

# 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

# 📁 Project Structure

Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── train.csv
├── README.md
└── requirements.txt


# 📊 Model Evaluation Summary

We evaluated 8 different classification architectures using Cross-Validation (CV) and verified them on a separate Holdout Test Set.

| Model | Best CV Score | Test Accuracy |
|--------|--------------:|--------------:|
| Logistic Regression | 81.26% | 78.63% |
| K-Nearest Neighbors | 80.02% | 78.24% |
| SVC | **82.31%** | 78.24% |
| Decision Tree | 79.54% | 78.24% |
| Random Forest | 82.02% | 77.48% |
| Gradient Boosting | 81.83% | 78.24% |
| AdaBoost | 79.92% | 75.19% |
| XGBoost | 81.74% | **80.92%** |

# 🏆 Champion Model

The automated pipeline flagged **SVC** as the mathematical winner & final deployment champion based solely on the highest Cross-Validation accuracy.

| Cross Validation Accuracy | **82.31%** |
| Test Accuracy | **78.24%** |
| Best Hyperparameters for SVC : {'C': 1, 'gamma': 0.1, 'kernel': 'rbf'} 

> **Note:** SVC was selected as the champion model because it achieved the highest Cross Validation Accuracy, indicating better generalization during model selection. However, XGBoost achieved the highest Test Accuracy (80.92%) on the unseen test dataset.

# 📈 Project Highlights

✅ Data Cleaning

✅ Missing Value Handling

✅ Label Encoding

✅ Feature Scaling

✅ Exploratory Data Analysis (EDA)

✅ Feature Engineering

✅ GridSearchCV Hyperparameter Tuning

✅ Multiple Machine Learning Algorithms

✅ Model Comparison

✅ Classification Report

✅ Confusion Matrix

✅ Best Model Selection

# 🎯 Future Improvements

- Deploy the model using Streamlit
- Hyperparameter optimization using RandomizedSearchCV
- Model Explainability using SHAP
- Feature Importance Visualization
- Docker Deployment
- CI/CD Pipeline

# 📜 License

This project is created for learning and portfolio purpose.

# 👨‍💻 Author

**Ashwani Sharma**

💻 Python | Machine Learning | Data Science | SQL | Power BI
