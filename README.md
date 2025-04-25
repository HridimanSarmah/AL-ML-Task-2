Exploratory Data Analysis (EDA) - Titanic Dataset

This project is part of the **AI & ML Internship Task 2**. The objective is to explore the Titanic dataset using summary statistics and visualizations to draw insights.

## Dataset
- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Used File**: `titanic.csv`

## Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly

## Steps Performed
1. **Data Loading & Overview**
   - Checked data structure, data types, and missing values.

2. **Data Cleaning**
   - Filled missing values in `Age` and `Embarked`.
   - Dropped the `Cabin` column due to high missing rate.

3. **Summary Statistics**
   - Mean, median, standard deviation, and other descriptive stats.

4. **Visualizations**
   - Histograms and KDE plots for Age
   - Boxplots for Fare and Age vs Survival
   - Correlation heatmap
   - Pairplot for multivariate relationships
   - Countplot for gender-based survival

5. **Observations & Insights**
   - Higher survival rate among females
   - First-class passengers had better chances of survival
   - Fare and Age showed moderate correlation with survival

## How to Run
1. Clone the repo
2. Open the notebook in Jupyter or VS Code
3. Run all cells to view outputs and plots

## Folder Structure
```
â”œâ”€â”€ titanic_eda_task2.ipynb
â”œâ”€â”€ README.md
â””â”€â”€ dataset/
    â””â”€â”€ titanic.csv
```

## Author
Hridiman Sarmah  

