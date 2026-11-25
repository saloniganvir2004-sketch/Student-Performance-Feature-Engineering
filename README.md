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

