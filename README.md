
# EDA: Medical Insurance Cost Dataset

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the popular Medical Insurance Cost dataset to uncover trends and relationships in health insurance charges, based on attributes such as age, BMI, smoking status, and region. 

## Dataset Details
- Source: [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Rows: ~1,300
- Columns: 7 (age, sex, bmi, children, smoker, region, charges)

## EDA Stages
1. **Dataset Overview**: Structure, column details, types, missing/unique values
2. **Data Quality Checks**: Duplicates & anomalies detection
3. **Data Cleaning**: Handling of missing, duplicate, or erroneous data
4. **Descriptive Statistics**: Summary stats, distribution checks
5. **Transformation/Encoding**: Scaling & categorical encodings
6. **Outlier Detection**: Using IQR, Z-score, visualized via boxplots
7. **Visualization**: Univariate, bivariate, and correlation analyses
8. **Insights**: Key findings, relationships, and recommendations

## Key Insights & Findings
- **Charges** are typically higher for smokers—even after controlling for age and BMI.
- **BMI** and **age** show strong positive correlations with insurance charges.
- **Regional** cost variations are observed.

## Files in This Repo
- `insurance.ipynb` : Jupyter Notebook with all code and visualizations
- `insurance.csv` : Dataset file
- `README.md` : Project summary & instructions

## Usage Instructions
1. Download all files.
2. Open the notebook in Jupyter/Colab.
3. Review and run cells step-by-step for full EDA.

## Credits
Dataset courtesy: [Kaggle - Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)
