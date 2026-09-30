# Basic_Exploratory_Data_Analysis
Exploratory Data Analysis (EDA) on Titanic and Job Market datasets using Python, Pandas, Matplotlib, and Seaborn for data cleaning, outlier detection, and visual insights.
## Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, demographic trends, and socioeconomic factors that influenced passenger survival.

## Dataset Details
* **Source:** Titanic Disaster Dataset (`Titanic-Dataset.csv`)
* **Shape:** 891 rows, 12 columns
* **Target Variable:** `Survived` (0 = No, 1 = Yes)
* **Key Features:** `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

## Workflow & Analysis Steps
1. **Data Exploration:** Inspected dataset dimensions, feature types (`dtypes`), null value distribution, and memory usage.
2. **Data Cleaning & Handling Nulls:** Analyzed missing values across continuous and categorical variables.
3. **Feature Engineering:**
   * Binned `Age` into groups: `child` (0–18), `adult` (18–60), and `old` (60+).
   * Evaluated family size interactions via `SibSp` and `Parch`.
4. **Data Visualization & Insights:**
   * **Overall Survival:** Only ~38% of passengers survived.
   * **Gender Impact:** Female survival rate (~74%) significantly exceeded male survival rate (~19%).
   * **Socioeconomic Class:** First-class passengers survived at ~63%, compared to ~24% for third-class passengers.
   * **Interactions:** First-class status offered strong protective effects across demographics, while third-class passengers faced systemic disadvantages.

## Repository Contents
* `Titanic_EDA.ipynb`: Full Python code with step-by-step EDA and visualizations.
* `Titanic-Dataset.csv`: Raw dataset.
* `README.md`: Project summary and findings.

## How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<repo-name>.git
