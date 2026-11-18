# DTS-201-GROUP-G
Group Machine learning project helping farmers with a validated tomato loss-prediction model and practical guidance on which interventions are linked to lower losses.


# Predicting Post-Harvest Tomato Losses Among Nigerian Farmers Using Machine Learning

## Project Overview

This project explores the use of machine learning to predict reported farm-level tomato losses among Nigerian farmers.

The study uses data from the **IITA Irrigated Endline Survey: Plastic Crates RCT Experiment in Nigeria** to investigate how selected farmer, farm, and agricultural practice characteristics relate to reported tomato losses.

## Project Objectives

- Understand and explore the dataset.
- Clean and preprocess relevant data.
- Identify suitable predictor variables.
- Develop and evaluate machine learning models.
- Examine the factors associated with reported farm-level tomato losses.

## Dataset

**Source:** IITA Irrigated Endline Survey: Plastic Crates RCT Experiment in Nigeria.

The project focuses on the irrigated production observations.

The original dataset is not included in this public repository. The processed modelling dataset is provided in `data/processed/`.

**Note:** The selected target represents reported farm-level tomato loss. Its measurement unit has not been independently verified.

## Repository Structure

```text
group1_r_ca1/
│
├── notebooks/
│   ├── data_understanding.ipynb
│   └── data_preprocessing.ipynb
│
├── data/
│   └── processed/
│       └── tomato_farm_loss_model.csv
│
└── README.md
```

## Project Workflow

1. Data understanding and exploration.
2. Data cleaning and preprocessing.
3. Exploratory data analysis.
4. Machine learning model development.
5. Model evaluation and interpretation.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Team Members

- Ugonna Onyeiwu
- Ayooluwa Folorunso
- Folarin Aseru
- Shuaib Shuaib

## Limitations

The dataset represents a specific study population and should not automatically be treated as representative of all Nigerian tomato farmers. Model predictions and conclusions will be interpreted within the limitations of the available data.