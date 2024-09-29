# Medical Insurance Cost Prediction

## Project Overview

This project aims to predict medical insurance costs using personal and health-related features such as age, BMI, gender, smoking status, and geographic region. The dataset contains 1338 records and is used to build a linear regression model to predict insurance charges.

The project includes a detailed analysis and implementation using a Jupyter Notebook, which is already provided in this repository. All data analysis, visualizations, and model development are done using Python libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn.

## Project Files

- Medical_Insurance_Prediction.ipynb: The Jupyter Notebook containing the entire project, including data loading, preprocessing, exploratory data analysis (EDA), model training, and evaluation.
- insurance.csv: The dataset used for training and testing the model, containing the following features:
  - age: Age of the individual.
  - sex: Gender of the individual (male/female).
  - bmi: Body Mass Index, a measure of body fat.
  - children: Number of children covered by the insurance.
  - smoker: Smoking status (yes/no).
  - region: Residential region in the US (northeast, southeast, etc.).
  - charges: Medical insurance charges (target variable).

## Getting Started

### Prerequisites

Make sure you have Python 3.x installed on your machine along with Jupyter Notebook and the required libraries.

You can install the dependencies using the requirements.txt file (if provided) or manually install the libraries by running:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
