

# Medical Charges Prediction Project

This project is a beginner-friendly Machine Learning and Data Analysis project based on a medical insurance charges dataset. The goal of this project is to analyze how factors such as age, BMI, smoking habits, gender, and region affect medical insurance charges.

## What I Did in This Project

### 1. Dataset Collection

* Downloaded the dataset using `urlretrieve` from `urllib.request`.
* Loaded the dataset into a Pandas DataFrame for analysis.

### 2. Data Exploration

* Checked dataset information using:

  * `info()`
  * `describe()`
* Analyzed data types and statistical information of numerical columns.

### 3. Data Visualization

Used:

* Matplotlib
* Seaborn
* Plotly Express

Created multiple visualizations including:

* Distribution of Age
* Distribution of BMI
* Distribution of Medical Charges
* Age vs Charges relationship
* BMI vs Charges relationship
* Smoker vs Non-Smoker charge comparison

### 4. Correlation Analysis

Computed correlations between:

* Age and Charges
* BMI and Charges

This helped understand how strongly different features affect insurance charges.

### 5. Data Preprocessing

Converted categorical columns into numerical format:

* female → 1, male → 0
* smoker yes/no → 1/0

Applied One-Hot Encoding on the `region` column using `pd.get_dummies()`.

### 6. Non-Smoker Data Analysis

Created a separate dataset for non-smokers and analyzed:

* Relationship between age and insurance charges
* Scatter plot visualization for better understanding

### 7. Simple Prediction Model

Implemented a basic linear equation:

charges = w \cdot age + b

Used different values of:

* `w` (weight/slope)
* `b` (bias/intercept)

to estimate insurance charges manually.

### 8. Model Visualization

Compared:

* Estimated charges
* Actual charges

using:

* Line plots
* Scatter plots

to understand how prediction lines fit real-world data.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

## Key Learning Outcomes

Through this project, I learned:

* Data analysis workflow
* Exploratory Data Analysis (EDA)
* Data visualization techniques
* Correlation analysis
* Feature encoding
* Basic prediction concepts
* Linear relationship modeling
* Understanding how machine learning models estimate outputs

This project helped build a strong foundation in data preprocessing, visualization, and beginner-level predictive modeling.

## Dataset Source

The medical insurance charges dataset used in this project was downloaded from the JovianML open datasets repository:

* Source: JovianML Open Datasets
* Dataset Link: https://raw.githubusercontent.com/JovianML/opendatasets/master/data/medical-charges.csv

The dataset contains information related to age, BMI, smoking habits, region, and medical insurance charges.

