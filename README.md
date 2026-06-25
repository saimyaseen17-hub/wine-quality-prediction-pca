# Wine Quality Prediction with PCA

## Project Overview

This project analyzes the Wine Quality dataset and applies Principal Component Analysis (PCA) to reduce feature dimensions while preserving important information.

The dataset contains physicochemical properties of wine such as acidity, sugar content, chlorides, sulphates, alcohol level, and other chemical measurements. The target variable is wine quality.

## Dataset Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

Target:

- Quality

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- PCA (Principal Component Analysis)

## Project Workflow

1. Load and explore the dataset
2. Separate features and target variable
3. Split data into training and testing sets
4. Standardize features using StandardScaler
5. Apply PCA for dimensionality reduction
6. Analyze explained variance ratio
7. Compare original and transformed feature space

## PCA Implementation

Principal Component Analysis (PCA) was used to reduce dimensionality and identify the most informative feature combinations.

Two approaches were explored:

- PCA with fixed components (`n_components=2`)
- PCA with variance preservation (`n_components=0.95`)

The explained variance ratio was used to evaluate how much information was retained after dimensionality reduction.

## Results

- Original Features: 11
- PCA was applied after feature standardization.
- Variance preservation was analyzed using `explained_variance_ratio_`.
- PCA helped simplify the dataset while retaining most of the important information.

## Learning Outcomes

Through this project I learned:

- Data preprocessing
- Feature scaling
- Principal Component Analysis (PCA)
- Explained Variance Ratio
- Dimensionality Reduction
- Machine Learning data preparation

## Author

Muhammad Saim
