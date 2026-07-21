# Titanic Regression Project using Microsoft Azure Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Azure Machine Learning](https://img.shields.io/badge/Azure-Machine%20Learning-0078D4)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)

---

## Project Overview

This repository presents an end-to-end machine learning workflow using the Titanic dataset in **Microsoft Azure Machine Learning**.

The project combines **Exploratory Data Analysis (EDA)** and **Automated Machine Learning (AutoML)** to demonstrate the complete process of understanding a dataset, preparing it for modeling, automatically comparing multiple machine learning algorithms, and evaluating the best-performing model.

---

## Objectives

- Explore the Titanic dataset
- Assess data quality and missing values
- Perform descriptive and visual data analysis
- Configure and run an Azure AutoML experiment
- Compare multiple machine learning models
- Evaluate the best-performing regression model
- Document the complete workflow

---

## Technologies Used

- Microsoft Azure Machine Learning
- Azure AutoML
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The project uses the **Titanic dataset**, which contains passenger information including:

- Passenger Class
- Age
- Sex
- Fare
- Embarkation Port
- Family Relationships
- Survival Status

---

## Repository Structure

```text
Titanic-AzureML-Regression/
│
├── README.md
├── LICENSE
├── train.csv
│
├── 01_Titanic_EDA.ipynb
├── 02_Titanic_AutoML_Report.ipynb
│
└── images/
```

---

## Project Components

### 1. Exploratory Data Analysis (EDA)

The first notebook focuses on understanding the dataset through:

- Dataset exploration
- Missing value analysis
- Descriptive statistics
- Univariate and bivariate analysis
- Data visualization
- Key insights before modeling

---

### 2. Azure Machine Learning AutoML

The second notebook documents the complete Azure AutoML workflow, including:

- AutoML experiment configuration
- Dataset preparation
- Automated model comparison
- Best model selection
- Performance evaluation
- Discussion of results
- Technical conclusions

---

## Best AutoML Model

| Metric | Value |
|---------|------:|
| **Algorithm** | StandardScalerWrapper + ExtremeRandomTrees |
| **Normalized RMSE** | **0.06663** |
| **R² Score** | **0.4835** |
| **Spearman Correlation** | **0.8336** |
| **Mean Absolute Error (MAE)** | **14.37** |

---

## Sample Visualization

![Average Fare by Passenger Class](images/fare_by_passenger_class.PNG)

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Microsoft Azure Machine Learning
- Automated Machine Learning (AutoML)
- Data preprocessing and exploration
- Model comparison and selection
- Performance evaluation
- Technical reporting
- Cloud-based machine learning workflows

---

## Author

**Sara Meziani**

PhD in Mathematics (Probability, Statistics and Applications)

Associate Professor of Mathematics and Statistics

Learning Artificial Intelligence, Machine Learning, and Data Analytics through practical cloud-based projects.

---

## License

This project is released under the **MIT License**.
