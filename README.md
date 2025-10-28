🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

📘 Overview

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle to uncover key insights about passenger demographics, travel classes, and survival trends. The analysis uses Python, Pandas, Matplotlib, and Seaborn to explore and visualize relationships within the data.

🧰 Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

📊 Steps in Analysis

1.Data Loading & Cleaning
* Loaded dataset using Pandas.
* Checked for missing values and handled nulls in Age and Embarked.

2.Descriptive Statistics
* Used .info(), .describe(), and .value_counts() for dataset overview.
  
3.Univariate Analysis
* Histograms and countplots for distributions of Age, Sex, and Survival.
  
4.Bivariate Analysis
* Analyzed survival by gender, class, and age using violin plots and boxplots.
* Correlation heatmap and pairplot to identify numeric relationships.
* Scatter plots to examine Fare, Age, and Survival.

5.Visualizations Used
* Histograms — Age and Fare distributions
* Boxplots — Outlier and fare spread by class
* Violin Plots — Age vs Survival patterns
* Pie Charts — Gender proportion
* Scatter Plots — Fare vs Age (colored by survival)
* Heatmap — Correlation matrix

💡 Key Insights

* Around 38% of passengers survived the Titanic disaster.
* Females and 1st class passengers had the highest survival rates.
* Higher fares were positively associated with survival chances.
* Age distribution showed that younger passengers were more frequent in 3rd class.
* Correlation analysis revealed Fare and Pclass as strong predictors of survival.

🧠 Conclusion 

The EDA on the Titanic dataset revealed clear social and economic patterns influencing survival. Women and 1st class passengers had significantly higher survival chances, showing the impact of gender and class privilege. Fare was strongly linked to both class and survival. These insights highlight how demographic and socio-economic factors shaped the tragic outcome of the disaster.
