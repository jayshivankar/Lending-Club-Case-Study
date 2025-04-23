# Lending-Club-Case-Study

# 📊 Exploratory Data Analysis - Loan Dataset

This repository contains an Exploratory Data Analysis (EDA) project on a loan dataset. The goal of this analysis is to understand the structure, distribution, and relationships within the data, and to extract key insights that could inform future modeling or decision-making processes.

## 📁 Dataset

The dataset used in this project is `loan.csv`, which includes information related to loan applications, such as applicant details, loan status, and financial background.

### Sample Features

- `Loan_ID`: Unique identifier for each loan
- `Gender`: Gender of the applicant
- `Married`: Marital status
- `Dependents`: Number of dependents
- `Education`: Education level
- `Self_Employed`: Employment status
- `ApplicantIncome`: Income of the applicant
- `CoapplicantIncome`: Income of the co-applicant
- `LoanAmount`: Loan amount requested
- `Loan_Amount_Term`: Term of loan in months
- `Credit_History`: Credit history (1 = good, 0 = bad)
- `Property_Area`: Urban/Semiurban/Rural
- `Loan_Status`: Loan approval status (Y/N)

## 🧪 EDA Process

The EDA was performed using Python (Pandas, Matplotlib, Seaborn, etc.). The process includes:

### 1. Data Cleaning
- Checked for null values and handled them appropriately
- Converted data types where necessary
- Standardized categorical variables

### 2. Univariate Analysis
- Distribution of categorical variables (e.g., Gender, Loan_Status)
- Histogram and boxplot visualizations for numeric variables

### 3. Bivariate & Multivariate Analysis
- Correlation heatmap of numeric features
- Boxplots and countplots segmented by `Loan_Status`
- Cross-tabulations for categorical variables

### 4. Key Insights
- Loan approval rates vary significantly by credit history
- Higher applicant income slightly correlates with loan approval, but not strongly
- Self-employed applicants have slightly lower approval rates
- Most loans are from semi-urban areas

### 5. Visualizations
- Count plots for `Loan_Status` vs. key categorical variables
- Histograms for `LoanAmount` and `ApplicantIncome`
- Correlation heatmap of numerical variables

## 📂 Project Structure

```bash
├── data/
│   └── loan.csv
├── eda/
│   └── loan_eda.ipynb
├── images/
│   ├── loan_status_distribution.png
│   ├── income_vs_loanamount.png
│   └── credit_history_vs_loan_status.png
├── README.md
```

## 🛠 Tools Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn

## 🚀 How to Run

1. Clone this repository
2. Navigate to the `eda/` directory
3. Open and run `loan_eda.ipynb` in Jupyter Notebook

```bash
jupyter notebook loan_eda.ipynb
```


