# Task 1: Data Cleaning & Preprocessing - Titanic Dataset

## Objective
Clean and preprocess the Titanic dataset to prepare it for machine learning.

## Dataset Used
**File Name:** Titanic-Dataset.csv  
**Source:** Kaggle - [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)  

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## Steps Performed
1. **Loaded the Dataset** (`Titanic-Dataset.csv`) and inspected first few rows, shape, and data types.
2. **Checked for Missing Values** and visualized them using a heatmap.
3. **Dropped Cabin Column** because it contained more than 77% missing values.
4. **Filled Missing Age** values with the median.
5. **Filled Missing Embarked** values with the mode.
6. **Encoded Categorical Columns**:
   - `Sex`: male → 0, female → 1  
   - `Embarked`: C → 0, Q → 1, S → 2
7. **Converted Columns to Categorical** where required (`Pclass`, `Survived`).
8. **Visualized Survival Data**:
   - Survival count
   - Survival by sex
   - Survival by passenger class
9. **Saved the Cleaned Dataset** as `titanic_cleaned.csv`.

## Files in this Repository
- `Titanic-Dataset.csv` – Original dataset  
- `titanic_cleaned.csv` – Cleaned dataset  
- `Task1_Titanic_Cleaning.ipynb` – Jupyter/Colab notebook with code and outputs  
- `screenshots/` – Before & after heatmaps and survival plots

## Author
*Alka Kushwaha*
