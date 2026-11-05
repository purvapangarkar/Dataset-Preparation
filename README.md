# Activity 1: Dataset Preparation and Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on preparing a dataset for future Machine Learning applications. The Titanic Passenger Dataset is used to inspect data, identify missing values, handle data-quality issues, perform basic Exploratory Data Analysis (EDA), encode categorical features, and scale numerical features.

The activity is completed using Python in Google Colab.

## 🎯 Objectives
- Load and understand a tabular dataset.
- Identify numerical and categorical columns.
- Check and handle missing values.
- Detect and remove unwanted duplicate records.
- Perform basic Exploratory Data Analysis.
- Create visualizations to understand the data.
- Apply one-hot encoding to categorical features.
- Apply standardization to selected numerical features.
- Save the prepared dataset as a CSV file.

## 📂 Dataset Information

- **Dataset Name:** Titanic Passenger Dataset
- **Domain:** Transport
- **Source:** Kaggle
- **File Format:** CSV
- **Target Column:** Survived

### Dataset Source
https://www.kaggle.com/datasets/yasserh/titanic-dataset

## 🛠️ Technologies and Libraries Used

- Python
- Google Colab
- Pandas – Data loading and manipulation
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Feature scaling

## ⚙️ Steps Performed

### 1. Dataset Loading and Inspection
Loaded the Titanic dataset and examined its first and last records, dimensions, column names, and data types.

### 2. Data Type Identification
Separated numerical and categorical columns and generated summary statistics.

### 3. Missing Value Analysis
Identified missing values and calculated their count and percentage in each column.

### 4. Missing Value Handling
- Numerical columns: Missing values filled using median.
- Categorical columns: Missing values filled using mode.

### 5. Duplicate and Consistency Checking
Checked duplicate records and removed unwanted duplicates. Removed extra spaces from categorical values.

### 6. Exploratory Data Analysis (EDA)
Performed statistical analysis and created visualizations:
- Histogram of passenger age distribution.
- Count plot of passenger survival by class.

### 7. Categorical Encoding
Applied One-Hot Encoding to convert nominal categorical features into numerical representations.

### 8. Numerical Feature Scaling
Applied StandardScaler to selected numerical features such as Age and Fare.

### 9. Saving Prepared Dataset
Saved the cleaned and transformed dataset as a separate CSV file.

## 📊 Results
The dataset was inspected and prepared through missing-value treatment, duplicate checking, exploratory analysis, categorical encoding, and numerical scaling.

The final prepared dataset was saved as:

`titanic_prepared.csv`

## 📁 Project Structure

```text
Activity-1-Dataset-Preparation/
│
├── Activity_1_Dataset_Preparation.ipynb
├── titanic dataset.csv
└── README.md
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open Google Colab or Jupyter Notebook.
3. Upload the dataset file `titanic.csv`.
4. Open `Activity_1_Dataset_Preparation.ipynb`.
5. Run all cells in sequence.
6. View the analysis, visualizations, and prepared dataset.

## 📌 Conclusion
This activity helped in understanding the basic steps of data preparation and exploratory data analysis. The Titanic dataset was inspected, cleaned, and transformed into a prepared dataset suitable for future Machine Learning workflows.

