# Predictive Analytics for Insurance claims

## Project overview
This project focuses on building a machine learning model to predict the likelihood of an insurance claim being filed based on customer demographics, policy details and past claims.
The goal is to deliver actionable insights and a predictive model that can help insurance companies make informed decisions about their customer base and policy offerings.

## Objectives
1. **Data Preparation:** Clean and structure the dataset to ensure high-quality input for the model
2. **Feature engineering:** Analyse and create features to improve model perfomance
3. **Model development:** Build and evaluate a classification model to predict the likelihood of an insurance claim
4. **Insights and Visualisation:** Extract and present insights through visualisation and feature importance analysis

## Dataset
- **Source:** [Kaggle - Healthcare insurance](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance)
- **Description:** This dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits), geographic factors, and their impact on medical insurance charges. It can be used to study how these features influence insurance costs and develop predictive models for estimating healthcare expenses.

## Tools
- Python: Scikit-learn, Pandas, Matplotlib, Seaborn
- SQL: For querying and analysing data

## Folder Structure
```
insurance-claims-prediction/
├── data/            # Raw and processed datasets
├── notebooks/       # Jupyter notebooks for exploration
├── scripts/         # Python scripts for data processing
├── models/          # Saved models
├── reports/         # Visualizations and summaries
├── requirements.txt # Dependencies
└── README.md        # Project documentation
```

## How to Run
1. Clone the repository: `git clone <repository_url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Explore data: Open `notebooks/` in Jupyter.
4. Run scripts: Use the Python scripts in the `scripts/` folder for data cleaning and modeling.
5. View insights: Check the `reports/` folder for visualizations.

## Deliverables
- Cleaned dataset.
- Classification model with feature importance analysis.
- Visualizations and insights into insurance claims.

## Results
The results and insights will be documented in the `reports/` folder.

## Future Work
- Test on additional datasets.
- Optimize the model further.
- Deploy the model using Flask or FastAPI.
