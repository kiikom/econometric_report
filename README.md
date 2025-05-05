Loan Default Prediction Using Logistic Regression

This project builds a logistic regression model to predict the likelihood of loan default based on borrower and loan-related attributes. The analysis involves data preprocessing, feature selection, statistical testing, and model evaluation.

Dataset:
The dataset includes features such as:
- Loan information: loan amount, term, interest rate, etc.
- Borrower characteristics: employment length, home ownership, annual income, etc.
- Credit history: number of delinquencies, credit inquiries, and more.

Libraries Used

- Pandas for data manipulation
- NumPy for numerical operations
- Scikit-learn for modeling and evaluation
- Matplotlib and Seaborn for visualization
- Statsmodels for statistical testing

 Steps Performed

1. Data Loading & Exploration 
   Load the dataset and inspect the structure, types, and missing values.

2. Data Cleaning  
   Handle missing values, encode categorical variables, and remove outliers.

3. Feature Engineering 
   Select and transform features to prepare for model training.

4. Statistical Analysis 
   Use hypothesis testing and p-values to evaluate the significance of variables.

5. Model Building  
   Train a logistic regression model to predict loan default.

6. Model Evaluation  
   Assess the model with:
   - Accuracy score
   - Confusion matrix
   - ROC Curve and AUC

How to Run
1. Clone the repository or download the notebook.
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn statsmodels
