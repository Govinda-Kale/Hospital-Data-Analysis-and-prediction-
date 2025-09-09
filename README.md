# Hospital Management System Data Analysis and No-Show Prediction

## Introduction
This project analyzes hospital management data to predict whether a patient will show up for their scheduled appointment using machine learning techniques. The analysis provides insights into patient behavior, doctor performance, and hospital operations.

## Abstract
Missed appointments are costly for healthcare providers. By identifying key predictors such as day of the week, weekend status, and appointment cost, this analysis helps optimize scheduling and resource allocation.

## Tools Used
- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- Machine Learning Algorithms (Random Forest)
- Data Visualization techniques

## Steps Involved in Building the Project
- **Data Collection:** Merged appointment, patient, doctor, billing, and treatment datasets
- **Data Preprocessing:** Cleaned null values, normalized status, encoded categorical features
- **Feature Engineering:** Extracted 'days_of_week', 'is_weekend', and treatment costs
- **Model Training:** Used Random Forest Classifier with train-test split and stratification
- **Evaluation:** Evaluated with accuracy, confusion matrix, and classification report
- **Visualization:** Visualized prediction performance using confusion matrix heatmap

## Data Files
- `appointments.csv`
- `billing.csv`
- `doctors.csv`
- `patients.csv`
- `treatments.csv`

## How to Run
1. Clone the repository.
2. Open the notebook `hospital-management-dataset-eda-insights-visual.ipynb` in Jupyter or VS Code.
3. Ensure all CSV files are in the same directory as the notebook or update the paths accordingly.
4. Run all cells to reproduce the analysis and results.

## Conclusion
The trained Random Forest model achieved high accuracy in predicting patient attendance. This solution aids in reducing missed appointments, improving clinic efficiency, and enhancing patient care.
