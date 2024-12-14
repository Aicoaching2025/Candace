# Data Wrangling and Cleaning: Titanic Dataset

Welcome to my data science portfolio project! This repository demonstrates essential data wrangling and cleaning techniques applied to the [Titanic dataset](https://www.kaggle.com/c/titanic). The goal of this project is to transform messy, incomplete data into a structured and analysis-ready format.

## Project Overview

### Objective
- To handle missing data, outliers, and inconsistencies in the Titanic dataset.
- To prepare the dataset for exploratory data analysis (EDA) and predictive modeling.

### Techniques Demonstrated
- **Handling Missing Data**: Imputation, removal, and investigation of missing values.
- **Outlier Detection and Treatment**: Identification of extreme values and strategies for handling them.
- **Data Transformation**: Encoding categorical data, scaling numerical features, and deriving new variables.

### Tools and Libraries
- **Python**: The primary programming language used.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.

## Repository Contents

### Files and Folders
- `data/`
  - Contains the raw Titanic dataset (`titanic.csv`).
- `notebooks/`
  - Jupyter Notebook with detailed steps for data cleaning (`data_cleaning_titanic.ipynb`).
- `scripts/`
  - Python scripts for automated data cleaning (`cleaning_pipeline.py`).
- `results/`
  - Cleaned dataset (`titanic_cleaned.csv`).

### Key Files
1. **`data_cleaning_titanic.ipynb`**: A step-by-step notebook showcasing the cleaning process, including code, visualizations, and explanations.
2. **`cleaning_pipeline.py`**: A reusable script to clean the dataset programmatically.

## Methodology

1. **Data Inspection**
   - Loaded the raw dataset to inspect column types, missing values, and anomalies.
   - Summarized key statistics and identified data quality issues.

2. **Handling Missing Data**
   - Imputed missing values for `Age` using the median.
   - Filled missing `Embarked` values with the mode.
   - Dropped irrelevant columns with excessive missing data (e.g., `Cabin`).

3. **Outlier Treatment**
   - Detected outliers in numerical columns (`Fare`, `Age`) using box plots and z-scores.
   - Applied capping and transformation techniques to manage extreme values.

4. **Data Transformation**
   - Encoded categorical variables (`Sex`, `Embarked`) using one-hot encoding.
   - Scaled numerical features for consistency.
   - Derived new features (e.g., `FamilySize` = `SibSp` + `Parch` + 1).

## Results
- Cleaned dataset saved as `results/titanic_cleaned.csv`.
- Improved data quality and structure, making it suitable for further analysis and modeling.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-wrangling-titanic.git
   ```

2. Navigate to the project directory:
   ```bash
   cd data-wrangling-titanic
   ```

3. Run the Jupyter Notebook to explore the data cleaning process:
   ```bash
   jupyter notebook notebooks/data_cleaning_titanic.ipynb
   ```

4. Alternatively, run the cleaning pipeline script:
   ```bash
   python scripts/cleaning_pipeline.py
   ```

## Next Steps
- Perform exploratory data analysis (EDA) on the cleaned dataset.
- Build predictive models to predict survival on the Titanic.
- Explore feature engineering to enhance model performance.

## Acknowledgments
- Dataset: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- Libraries: Pandas, NumPy, Jupyter Notebook

## Contact
For questions or feedback, feel free to reach out:
- **Name**: Candace Grant
- **Email**: aicoaching2025@gmail.com
- **LinkedIn**: [Candace Grant](https://www.linkedin.com/in/candace215)

---

Thank you for exploring my project! If you find this repository helpful, please consider starring it. ⭐

