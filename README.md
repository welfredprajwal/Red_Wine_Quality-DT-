# Red-Wine-Quality-Decision Tree

# Overview

This project predicts the quality of red wine using the Decision Tree algorithm. Decision Trees are intuitive and interpretable models that classify wines based on chemical properties, helping winemakers understand which features most influence wine quality.

By analyzing factors such as acidity, sugar, pH, and alcohol content, the model categorizes wines into different quality levels, assisting in quality control and production optimization.

# Dataset

| Feature              | Description                                                        |
| -------------------- | ------------------------------------------------------------------ |
| fixed acidity        | Concentration of fixed acids (e.g., tartaric, malic acid)          |
| volatile acidity     | Amount of acetic acid present; high levels can cause vinegar taste |
| citric acid          | Amount of citric acid; contributes to freshness and taste          |
| residual sugar       | Sugar remaining after fermentation                                 |
| chlorides            | Salt content in the wine                                           |
| free sulfur dioxide  | Amount of free SO₂ (prevents microbial growth)                     |
| total sulfur dioxide | Total SO₂ content                                                  |
| density              | Density of the wine                                                |
| pH                   | Acidity/alkalinity measure                                         |
| sulphates            | Sulfate content; acts as preservative and flavor enhancer          |
| alcohol              | Alcohol percentage in the wine                                     |
| quality              | Target variable (wine quality score, e.g., 0–10)                   |

# Why Decision Tree?

Provides interpretable rules for wine quality assessment
Handles both numerical and categorical data
Captures non-linear relationships between features and quality
Efficient and fast to train, making it suitable for real-time predictions

# Project Workflow

1.Data Preprocessing

2.Exploratory Data Analysis (EDA)

3.Decision Tree Modeling

4.Model Evaluation

5.Prediction

# Results

Classification (quality as categories): ~95–85%

Regression (quality as continuous score): R² score ~0.90–0.80
