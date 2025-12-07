# Credit Score Classification: Data Loading

This script demonstrates the initial step of a machine learning pipeline: loading and inspecting a financial dataset designed for **Credit Score Classification**. It uses the Python **Pandas** library to read a CSV file and display the first few records to verify the data structure.

## 📋 Prerequisites

To run this code, you need Python installed along with the Pandas library.

```bash
pip install pandas
```

## 📂 Dataset Information

**File Name:** `Credit Score Classification Dataset.csv`

The code assumes this file is located in the **same directory** as your script or notebook. This dataset is typically used to predict a person's creditworthiness based on their financial history.

**Likely Columns (Standard for this type of data):**
*   **Demographics:** Age, Occupation, Annual Income.
*   **Financials:** Number of Bank Accounts, Number of Credit Cards, Interest Rate.
*   **Behavior:** Delay from due date, Number of delayed payments, Outstanding Debt.
*   **Target Variable:** `Credit_Score` (e.g., Good, Standard, Poor).

## 🚀 Usage

1.  Ensure your `Credit Score Classification Dataset.csv` file is in the project folder.
2.  Run the following Python code:

```python
import pandas as pd

# Load the dataset into a DataFrame
df = pd.read_csv('Credit Score Classification Dataset.csv')

# Inspect the first 5 rows to understand the structure
df.head()
```

## 🔍 Code Explanation

*   **`pd.read_csv(...)`**: This function reads the comma-separated values file and converts it into a Pandas **DataFrame**—a 2-dimensional labeled data structure (like a robust Excel spreadsheet).
*   **`df.head()`**: This method outputs the first 5 rows of the DataFrame. It is the standard way to quickly check if the data loaded correctly, view column names, and spot immediate formatting issues (like `NaN` values).

## ⏭️ Next Steps

After loading the data, typical next steps in this project would include:
1.  **Data Cleaning:** Handling missing values or outliers.
2.  **EDA (Exploratory Data Analysis):** Visualizing correlations between income, debt, and credit scores.
3.  **Preprocessing:** Encoding categorical variables (like "Occupation") into numbers.
4.  **Modeling:** Training a classifier (e.g., Random Forest, XGBoost) to predict the Credit Score.

## 🏷️ Tags
`python` `pandas` `data-science` `credit-score` `classification` `csv` `machine-learning`-Score-Classification-Prediction
This script demonstrates the initial step of a machine learning pipeline: loading and inspecting a financial dataset designed for Credit Score Classification. It uses the Python Pandas library to read a CSV file and display the first few records to verify the data structure.
