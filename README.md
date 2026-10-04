# Diabetes Diagnosis

A DATA 555 project that predicts diabetes (`Outcome`: 0 = no diabetes, 1 = diabetes) using `diabetes.csv`. The notebook includes data quality checks, exploratory plots, feature selection, and a comparison of a logistic regression baseline with untuned and tuned random forests.

## Quick start

Use Python 3.13 (tested) and VS Code with the Python and Jupyter extensions.

1. From the project folder, run these commands in PowerShell:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\python.exe -m pip install pandas matplotlib scikit-learn ipykernel
   ```

2. Open [Project_2_Diabetes_Diagnosis.ipynb](Project_2_Diabetes_Diagnosis.ipynb) in VS Code.
3. Select `.venv` as the notebook kernel, then choose **Run All**.

The notebook uses the local `diabetes.csv` or downloads it automatically if the file is missing. All plots, explanations, and model results are included in the notebook.

## Dataset reference

- Source: [Pima Indians Diabetes Dataset](https://github.com/npradaschnor/Pima-Indians-Diabetes-Dataset) by npradaschnor on GitHub.
- Download copy: [diabetes.csv in this repository](https://raw.githubusercontent.com/QihangFeng/data555-project2/refs/heads/main/diabetes.csv).
