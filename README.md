# ai-student-dropout-prediction

# AI-Powered Student Dropout Prediction System

## Overview
This project develops a machine learning-based early warning system to predict student dropout risk using institutional data. The goal is to help educational institutions identify at-risk students early and enable timely intervention.

## Objectives
- Predict student dropout risk using supervised learning
- Identify key drivers of student attrition
- Provide actionable insights for early intervention

## Dataset
- Source: Higher Education Predictors of Student Retention Dataset
- Size: 4,424 student records
- Features: 34 input features
- Target: Binary classification (At-Risk vs Not At-Risk)

## Methodology
1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature engineering
4. Model training and comparison
5. Model evaluation using Accuracy, Recall, F1-score, and ROC-AUC
6. Explainability using SHAP

## Model Results

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|------|----------|-----------|--------|----------|---------|
| Random Forest | 0.884 | 0.872 | 0.746 | 0.805 | 0.934 |
| Logistic Regression | 0.888 | 0.874 | 0.761 | 0.814 | 0.931 |
| SVM | 0.882 | 0.905 | 0.708 | 0.794 | 0.927 |
| XGBoost | 0.898 | 0.865 | 0.810 | 0.836 | 0.926 |
| Decision Tree | 0.818 | 0.711 | 0.729 | 0.720 | 0.795 |

## Key Findings
- Academic performance is the strongest predictor of dropout risk
- Financial indicators such as tuition status and debtor status significantly affect outcomes
- Age has moderate influence compared with academic and financial features

## Ethical Considerations
- Financial variables may reflect structural inequalities
- Model outputs should support, not replace, human academic advising
- Fairness monitoring should be part of future deployment

## Repository Structure
- `data/` raw or reference data files
- `notebooks/` Jupyter notebooks
- `src/` reusable scripts
- `models/` trained model files
- `reports/` presentation decks and report files
- `images/` charts and visual outputs

## How to Run
1. Clone or download this repository
2. Install required packages
3. Open the notebooks and run the cells in order

## Requirements
Install dependencies using:

```bash
pip install -r requirements.txt
