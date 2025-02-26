# Cervical Cancer Risk Factors Analysis

## Overview

This project analyzes risk factors associated with cervical cancer using a dataset sourced from Kaggle. The goal is to identify key predictors and develop a model to assess the likelihood of cervical cancer in patients, aiding in early diagnosis and preventive healthcare.

## Features

- **Comprehensive Dataset**: Includes demographic information, lifestyle factors, and medical history.
- **Data Preprocessing**: Handles missing values and encodes categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualizes data distributions and relationships between variables.
- **Predictive Modeling**: Implements machine learning algorithms to predict cervical cancer risk.
- **Model Evaluation**: Assesses models using metrics like accuracy, precision, recall, and F1-score.

## Methodology

1. **Data Collection**
   - Utilizes the "kag_risk_factors_cervical_cancer.csv" dataset from Kaggle.

2. **Data Preprocessing**
   - Handles missing values through imputation.
   - Encodes categorical variables using appropriate techniques.

3. **Exploratory Data Analysis**
   - Visualizes distributions of variables.
   - Analyzes correlations between risk factors and cervical cancer incidence.

4. **Modeling**
   - Splits data into training and testing sets.
   - Trains classifiers such as Logistic Regression, Decision Trees, and Random Forests.

5. **Evaluation**
   - Evaluates models using performance metrics.
   - Selects the best-performing model for potential deployment.

## Dataset

- **Source**: [Kaggle - Risk Factors of Cervical Cancer](https://www.kaggle.com/datasets/vincentchege/kag-risk-factors-cervical-cancer-csv)
- **Description**: Contains features like age, number of sexual partners, smoking habits, contraceptive use, and medical history related to cervical cancer.

## Installation

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/mohamedsalama677/kag_risk_factors_cervical_cancer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd kag_risk_factors_cervical_cancer
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook cancer.ipynb
   ```

## Applications

- **Healthcare Diagnostics**: Assists in identifying high-risk individuals for cervical cancer.
- **Public Health Research**: Provides insights into prevalent risk factors.
- **Preventive Medicine**: Aids in developing strategies to reduce cervical cancer incidence.

## Limitations & Future Work

- **Challenges**: Addressing class imbalance and ensuring model generalizability.
- **Future Enhancements**: Incorporating additional data sources, exploring advanced machine learning models, and validating the model on external datasets.

## Contributors

- Mohamed Salama ([GitHub](https://github.com/mohamedsalama677))


For detailed analysis and code implementation, refer to the [cancer.ipynb](https://github.com/mohamedsalama677/kag_risk_factors_cervical_cancer/blob/main/cancer.ipynb) notebook. 
