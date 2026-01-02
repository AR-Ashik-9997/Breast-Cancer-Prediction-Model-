# Breast Cancer Prediction Model

## Description

This project develops a machine learning model for predicting breast cancer diagnosis using a dataset of breast cancer features. The notebook implements data preprocessing, exploratory data analysis, model training with Logistic Regression and Random Forest algorithms, and evaluation of the model's performance.

The goal is to accurately classify breast tumors as malignant or benign based on various cellular features extracted from biopsy images.

## Dataset

The dataset (`breast cancer.csv`) contains measurements from breast cancer biopsies, including features such as:

- Mean radius, texture, perimeter, area
- Smoothness, compactness, concavity
- Symmetry and fractal dimension measurements
- Diagnosis label (Malignant/Benign)

## Features

- Data loading and exploration
- Handling missing values
- Feature scaling and encoding
- Model training and hyperparameter tuning
- Performance evaluation with accuracy and confusion matrix
- Data visualization

## Installation

1. Ensure Python 3.7+ is installed
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```
3. Activate the virtual environment:
   - Windows: `.venv\Scripts\activate`
   - macOS/Linux: `source .venv/bin/activate`
4. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Activate the virtual environment
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Breast Cancer Prediction Model .ipynb`
4. Run the cells sequentially to execute the analysis

## Dependencies

- pandas: Data manipulation
- numpy: Numerical computations
- matplotlib: Plotting
- seaborn: Statistical visualization
- scikit-learn: Machine learning algorithms
- jupyter: Notebook environment

## Results

The notebook evaluates model performance using accuracy scores and confusion matrices for both Logistic Regression and Random Forest models.
