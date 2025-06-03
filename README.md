🔍 Objective:
The goal of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract insights, identify patterns, trends, and potential anomalies using visual and statistical methods.

🛠 Tools & Libraries Used:
Python

Jupyter Notebook

Pandas – for data manipulation

Seaborn & Matplotlib – for visualization

NumPy – for numerical operations

📂 Dataset:
Source: sns.load_dataset('titanic') (Seaborn’s built-in dataset)

Contains information about passengers such as age, sex, class, fare, survival status, etc.

📊 Analysis Performed:
Dataset Overview

Used .head(), .info(), .describe() to understand the structure.

Checked for missing values.

Categorical Analysis

Used .value_counts() to understand distribution of categories like sex, class, embark_town.

Visual Analysis

Histograms for age distribution

Boxplots to compare age with passenger class

Countplots to analyze survival by gender and class

Heatmaps to visualize correlations

Pairplots to explore relationships between numerical features

✅ Key Insights:
More females survived than males.

Higher-class passengers had higher survival rates.

Younger passengers (children) were more likely to survive.

Fare and class showed a positive correlation.

Several columns contained missing values (e.g., age, deck).

📁 Files Included:
Titanic_EDA.ipynb – Jupyter Notebook containing all analysis and visualizations

Titanic_EDA_Report.pdf – Exported PDF version of the notebook

README.md – This documentation

💡 How to Run:
Open Titanic_EDA.ipynb in Jupyter Notebook

Run all cells using Cell > Run All

Export as PDF using File > Download As > PDF via LaTeX or save as HTML and print to PDF

