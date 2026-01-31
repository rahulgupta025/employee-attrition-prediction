# Employee Attrition Prediction with Python

This project predicts employee attrition using machine learning techniques on real HR data. 
It demonstrates an end-to-end data science workflow: EDA, preprocessing, modeling, evaluation, and insights.

## Dataset
IBM HR Analytics Employee Attrition & Performance Dataset  
Source: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

> Note: Due to Kaggle licensing, the dataset is not included in this repository. Please download it manually and place it in the `data/` folder.

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Project Workflow
1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Encoding categorical variables  
4. Train-test split  
5. Random Forest classification  
6. Model evaluation and feature importance analysis  

## Results
- Achieved ~85% accuracy on test data (baseline model)
- Identified key drivers of attrition such as job role, monthly income, and overtime

## Repository Structure
```
employee-attrition-prediction/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── employee_attrition_analysis.ipynb
├── requirements.txt
└── README.md
```

## How to Run
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook employee_attrition_analysis.ipynb
   ```

## Use Case
This project helps HR and management teams proactively identify employees at risk of leaving and design targeted retention strategies.
