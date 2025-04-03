# CSCA 5622: Introduction to Machine Learning - Supervised Learning Final Project

This repository contains the final project for the course CSCA 5622: Introduction to Machine Learning, focusing on supervised learning. The project predicts early hospital readmissions (<30 days) for diabetic patients using binary classification, aiming to identify high-risk patients to improve care and optimize resource allocation.

## Dataset

**Source:** [UCI Machine Learning Repository (ID 296)](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)

**Description:** The dataset represents ten years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. Each row concerns hospital records of patients diagnosed with diabetes, who underwent laboratory, medications, and stayed up to 14 days. 

## Project Structure

`src/ml-final-project.ipynb`: Main Jupyter Notebook with all project code and analysis.

`data/`: Contains local dataset files (optional, can be downloaded via ucimlrepo).

## How to Run

1. Clone the repository:

```
git clone https://github.com/kuku147/CSCA-5622-Supervised-Learning.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the notebook

```
jupyter notebook src/ml-final-project.ipynb
```

## Methodology

**Problem:** Binary classification (<30 days readmission vs. not).

**Approach:** Data cleaning (handling missing values, outliers), feature engineering (encoding, scaling), SMOTE for class imbalance, and model training (LightGBM optimized for recall).

## Course

CSCA 5622: Introduction to Machine Learning

Final Project Submission: *April 2025*
