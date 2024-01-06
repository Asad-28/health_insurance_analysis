# Insurance churn Analysis

This repository contains a Jupyter Notebook (`churn_analysis.ipynb`) that performs an analysis on a health insurance dataset using Python and various data analysis libraries. The analysis includes data exploration, descriptive statistics, correlation analysis, and regression analysis.

## Getting Started

To run the code in the Jupyter Notebook, follow these steps:

1. Open the Jupyter Notebook `churn_analysis.ipynb` using a compatible environment like [Google Colab](https://colab.research.google.com/).
2. Make sure you have the necessary dependencies installed (Pandas, Matplotlib, Seaborn, and Scikit-Learn).
3. Upload the dataset (`insurance.csv`) to the Colab environment or modify the file path accordingly.

## Code Overview

The notebook performs the following tasks:

1. **Data Loading:**
   - Loads the health insurance dataset using Pandas.

2. **Data Exploration:**
   - Displays the first few rows of the dataset.
   - Provides descriptive statistics of the dataset.

3. **Correlation Analysis:**
   - Generates a correlation matrix and visualizes it using a heatmap.

4. **Data Visualization:**
   - Visualizes health charges for smokers and non-smokers using a boxplot.
   - Examines the relationship between age and health charges using a scatter plot.
   - Analyzes health charges across different regions using a boxplot.

5. **Feature Engineering:**
   - Creates new features ('bmi_category' and 'age_group') based on BMI and age.

6. **Regression Analysis:**
   - Performs linear regression on the dataset to predict health charges.
   - Evaluates the model using Mean Squared Error.

7. **Cost-Benefit Analysis:**
   - Conducts a hypothetical cost-benefit analysis considering customer acquisition and retention costs.

8. **Visualization of Results:**
   - Plots the actual charges against predicted charges.
   - Visualizes the distribution of residuals.

## Dependencies

- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

## License

This code is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
