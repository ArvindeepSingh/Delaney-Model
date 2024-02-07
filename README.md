# Delaney ML Project for Molecular Solubility Prediction

## Overview

The Delaney ML Project is designed to predict the solubility of molecules, a crucial piece of information for chemists and biologists. This machine learning model utilizes a unique dataset that includes molecular descriptors necessary for determining whether a molecule is soluble in water or different solvents.

## Project Structure

- **Data Loading:** Initial loading of the solubility dataset.
- **Data Preparation:** Preparation of the dataset for modeling, including feature and target variable separation, followed by training and test set splitting.
- **Model Building:**
  - *Linear Regression:* Baseline model for prediction accuracy.
  - *Random Forest:* Advanced model for capturing complex patterns.
- **Model Evaluation:** Evaluation of models using metrics like RMSE and R-squared.
- **Data Visualization:** Visualization of actual vs. predicted solubility values.

## Setup Instructions

```bash
# Clone the repository
git clone <repository-url>
cd <repository-directory>

# Install required Python packages
pip install -r requirements.txt

# Open the Jupyter notebook
jupyter notebook delaney_project.ipynb
```

## Usage

1. **Prepare Your Dataset:** Ensure it follows the format of the provided Delaney dataset.
2. **Model Training:** Train the provided Linear Regression or Random Forest models with your dataset.
3. **Prediction:** Input molecular descriptors into the trained model for solubility prediction.
4. **Evaluation and Visualization:** Use the provided code to evaluate and visualize your prediction results.
