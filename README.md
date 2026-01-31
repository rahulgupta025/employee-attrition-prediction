# Employee Attrition Prediction with Python
Employee attrition is a critical challenge for organizations due to its impact on cost, productivity, and team morale.  
This project uses real HR data and machine learning techniques to analyze why employees leave and to predict attrition risk, with the objective of supporting data-driven HR and management decision-making.


## Dataset

The project uses the **IBM HR Analytics Employee Attrition & Performance Dataset**, which contains employee-level information such as demographics, job role, compensation, performance, and work conditions.

Source: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

**Note:** The dataset is publicly available on Kaggle and is not included in this repository due to licensing restrictions. Instructions to reproduce the analysis are provided.

## Key Business Questions

- What factors are most strongly associated with employee attrition?
- Can employee attrition be predicted using historical HR data?
- How can predictive insights help HR teams take proactive retention actions?

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Project Workflow
1. Data understanding and exploratory data analysis (EDA)
2. Identification of attrition patterns and trends
3. Encoding of categorical variables and feature preparation
4. Model training using Random Forest classification
5. Model evaluation and interpretation of results
6. Identification of key drivers influencing employee attrition
   
## Key Insights

- Employees working overtime showed a higher likelihood of attrition.
- Job role and monthly income were strong predictors of employee turnover.
- Work-life balance and job satisfaction played a significant role in retention.
- Predictive models can support early identification of high-risk attrition groups.


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
