# Student Performance – Data Quality and Feature Engineering

## Project Overview

This project demonstrates fundamental Data Quality and Feature Engineering techniques using Python, Pandas, and NumPy.

The analysis uses the Students Performance in Exams dataset to create meaningful numerical features and transform categorical variables for further machine learning applications.

## Dataset

Students Performance in Exams dataset.

Source: Kaggle – Students Performance in Exams.

## Implemented Techniques

### 1. Dataset Acquisition
- Downloads the dataset using the Kaggle API.
- Extracts and loads StudentsPerformance.csv.

### 2. Aggregate Feature Creation
- Calculates total student scores.
- Generates average score features.

### 3. Feature Binning
- Categorizes students into Low, Medium, and High performance levels.
- Uses Pandas pd.cut().

### 4. Categorical Encoding
- Converts test preparation completion into binary values.
- Encodes gender into numerical values.

### 5. Feature Engineering Observations
- Examines newly created aggregate features.
- Analyzes categorical transformations.
- Discusses the importance of feature engineering in machine learning.

## Technologies Used

- Python
- Pandas
- NumPy
- Kaggle API
- Google Colab / Jupyter Notebook

## Project Structure

Student-Performance-Feature-Engineering/
├── Student_Performance_Feature_Engineering.ipynb
├── README.md
└── requirements.txt

## Execution

1. Open the notebook in Google Colab.
2. Configure Kaggle API credentials.
3. Execute the dataset download and extraction cells.
4. Run the feature engineering operations sequentially.
5. Examine the generated features and observations.


## Additional Implementation: Missing Value Handling Strategies

This notebook demonstrates fundamental missing-value imputation techniques using Python, Pandas, NumPy, and Matplotlib.

### Implemented Techniques

1. Mean Imputation
   - Calculates the mean of the Mathematics score.
   - Replaces missing values with the calculated mean.

2. Median Imputation
   - Calculates the median Mathematics score.
   - Uses median-based replacement for missing values.

3. Mode Imputation
   - Calculates the most frequently occurring Mathematics score.
   - Replaces missing values using the mode.

### Additional Features

- Downloads the Students Performance in Exams dataset using Kaggle API.
- Introduces artificial missing values into 10% of Mathematics scores.
- Examines missing-value counts after imputation.
- Compares original and mean-imputed score distributions using histograms.
- Discusses the differences between mean, median, and mode imputation.

Notebook: Missing_Value_Handling_Strategies.ipynb


## Additional Implementation: Data Quality Analysis

This notebook performs exploratory data quality analysis on the Students Performance in Exams dataset using Python.

### Implemented Analysis

1. Dataset Loading
   - Downloads the dataset using Kaggle API.
   - Loads StudentsPerformance.csv using Pandas.

2. Dataset Inspection
   - Examines dataset dimensions.
   - Inspects column names and data structure.
   - Generates descriptive statistical summaries.

3. Missing Value Analysis
   - Identifies missing values.
   - Calculates missing-value percentages for each column.

4. Duplicate Detection
   - Identifies duplicate records.

5. Unique Value Analysis
   - Examines unique values across dataset columns.

6. Data Type Analysis
   - Identifies numerical and categorical features.

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Kaggle API

### Notebook

Data_Quality_Analysis.ipynb

