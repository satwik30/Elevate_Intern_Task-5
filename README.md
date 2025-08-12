# Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

## 📌 Objective
Conduct Exploratory Data Analysis (EDA) on the Titanic dataset to uncover trends, patterns, correlations, and anomalies using Python data analysis and visualization libraries.

## 📂 Dataset
- *File:* Dataset.csv (Kaggle Titanic competition)
- *Description:* Passenger details including demographics, ticket information, and survival status.

## 🛠 Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Workflow
1. *Data Loading & Inspection*
   - Imported dataset
   - Checked data types, shape, missing values
2. *Data Cleaning*
   - Filled missing values (Age, Embarked)
   - Adjusted categorical variables
3. *Univariate Analysis*
   - Histograms & boxplots for numerical data
   - Countplots for categorical data
4. *Bivariate Analysis*
   - Survival rates by Sex, Pclass, Age, Fare
   - Scatter plots & grouped bar plots
5. *Multivariate Analysis*
   - Correlation heatmap of numerical features
   - Pairplots to explore combined feature effects
6. *Observations & Summary*
   - Noted patterns and potential predictive features

## 📊 Key Insights
- Female passengers had higher survival rates.
- Passengers in 1st class (Pclass=1) were more likely to survive.
- Younger passengers showed better survival chances.
- Fare is weakly positively correlated with survival.

## 📁 Files
- Titanic_EDA.ipynb – Full Jupyter Notebook analysis
- Dataset.csv – Dataset
- Titanic_EDA.pdf – Exported PDF report
- README.md – Documentation

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Titanic_EDA.ipynb