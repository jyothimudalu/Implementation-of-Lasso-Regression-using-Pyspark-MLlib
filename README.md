# Implementation of Lasso Regression with PySpark MLlib

## Overview

This project implements **Lasso Regression** using PySpark's MLlib for hyperparameter tuning in a predictive modeling context. Lasso (Least Absolute Shrinkage and Selection Operator) is a regression analysis method that performs both variable selection and regularization, which enhances the prediction accuracy and interpretability of the resulting model.

### Key Features
- **Lasso Regression**: A regularization method that applies L1 penalty to the regression, shrinking some coefficients to zero and selecting the most relevant features.
- **Hyperparameter Tuning**: Utilizes cross-validation to optimize the regularization parameter (`lambda` or `alpha`), balancing model complexity and performance.
- **PySpark Integration**: Uses PySpark's distributed computing capabilities to efficiently handle large-scale data, making the model scalable for big datasets.

### Project Structure
- **Notebook (`Lasso_Regression_PySpark_MLlib.ipynb`)**: This Jupyter notebook contains:
  - Data preprocessing steps (handling missing values, encoding categorical variables)
  - Implementation of Lasso Regression
  - Hyperparameter tuning using cross-validation
  - Model evaluation and analysis of results (Mean Squared Error, R-squared, feature importance)

### Dependencies

To run this project, you need to install the following libraries:

- **PySpark**: A fast and general-purpose distributed data processing engine with a machine learning library (MLlib).
- **MLlib**: Spark's scalable machine learning library.
  
You can install PySpark via pip:

```bash
pip install pyspark

For further steps refer the above files
