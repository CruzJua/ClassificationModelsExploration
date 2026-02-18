# Credit Card Fraud Detection Pipeline

This repository contains a machine learning project focused on detecting fraudulent credit card transactions. The primary challenge addressed is the extreme class imbalance, where fraudulent transactions account for only **0.17%** of the total data.

## Project Overview
The `main.ipynb` notebook implements an end-to-end pipeline including:
- **Exploratory Data Analysis (EDA):** Statistical summaries and visualizations of feature correlations and class distributions.
- **Preprocessing:** Cleaning, scaling, and stratifying the data to ensure robust training.
- **Hyperparameter Tuning:** Utilizing `GridSearchCV` to optimize models while tracking multiple metrics.
- **Model Evaluation:** Detailed analysis using Confusion Matrices, ROC Curves, and Precision-Recall Curves to prioritize the detection of rare fraud events.

## Prerequisites
- Python 3.9+
- A configured virtual environment (recommended)

## How to Run the Project

### 1. Prepare the Data
Ensure your project directory is structured as follows:
```text
.
├── main.ipynb
├── requirements.txt
└── data/
    └── creditcard.csv
```

### 2. Set Up the Environment & Install Dependencies
Run the following commands in your terminal to set up the environment and install all necessary libraries via the requirements file:

```bash
# Create the virtual environment
python -m venv .venv

# Activate the environment
# On Windows:
.venv\Scripts\activate

# On Mac/Linux:
source .venv/bin/activate

# Install all dependencies from requirements.txt
pip install -r requirements.txt

### 3. Execute the Notebook
1. Open `main.ipynb` in your IDE.
2. Select your `.venv` as the Python kernel.
3. select run all cells.
```
### 🤖 AI Attribution
*This `README.md` file was generated with the assistance of AI (Gemini).* **Version:** 1.2.1  
**Date:** February 2026