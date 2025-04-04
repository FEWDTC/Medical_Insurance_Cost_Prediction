# Medical_Insuracne_Cost_Prediction
Collaborated in a 4-person team to predict insurance costs using structured health and demographic data. Led data preprocessing (StandardScaler, encoding) and implemented CART. Compared performance of Linear Regression, Random Forest, and Gradient Boosting.Gradient Boosting achieved highest accuracy (OSR² = 0.87),but CART with best interpretability

# Medical Insurance Cost Prediction (IEOR 142A Capstone)

## Project Overview
This project focuses on predicting individual medical insurance costs using demographic and health-related features. It was completed as a capstone project for IEOR 142A at UC Berkeley and emphasizes real-world machine learning workflows and model comparison for regression tasks.

> Goal: Predict medical charges for insurance customers using regression models.

The project explores the trade-off between model performance and interpretability, comparing simple decision trees (CART) with more powerful ensemble models.

---

## Methods & Workflow

### Data Preprocessing
- Removed outliers based on medical charges and BMI
- Transformed categorical variables using dummy encoding
- Applied `StandardScaler` to numerical variables
- Split the data into training and test sets

### Models Implemented
- **Linear Regression**
- **CART (Decision Tree)**
- **Random Forest**
- **Gradient Boosting**

> Evaluation Metric: OSR² (Out-of-Sample R-Squared), MSE, MAE

---

## Results & Insights
- **Gradient Boosting** achieved the highest predictive performance (OSR² = 0.87)
- **CART** was the most interpretable model, useful for basic insights
- Feature importance analysis revealed key cost drivers:
  - Smoking status
  - BMI
  - Age
  - Number of children

---

## Files Included
```
Medical_Insurance_Cost_Prediction/
├── insurance.csv                  # Original dataset
├── 142A_Final_Project.ipynb       # Data preprocessing + modeling notebook
├── IEOR_142A_Final_Report.pdf     # Group report (academic write-up)
└── README.md                      # Project documentation
```

---

## Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn (CART, RandomForest, GradientBoosting)
- Matplotlib, Seaborn

---

## Contributor Role
This was a group project (4 students). I was responsible for:
- Full data preprocessing
- Outlier handling
- Feature engineering
- CART model building and tuning

**[View Visualizations in Jupyter Notebook](https://github.com/FEWDTC/Medical_Insurance_Cost_Prediction/blob/main/142A_Final_Project.ipynb)**
---

## Academic Context
- **Course**: IEOR 142A – Machine Learning and Data Analytics for Industrial Engineering
- **Institution**: UC Berkeley

---

## Acknowledgements
Thanks to Professors and course staff of IEOR 142A for feedback and support during model evaluation and report generation.

---

## License & Usage
This dataset was used for educational purposes only.
Please do not redistribute the dataset externally.

---

**Created by Junghyun Cheon | UC Berkeley Data Science | Data Analyst**


