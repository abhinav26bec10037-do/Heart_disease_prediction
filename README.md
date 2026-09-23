# Heart_disease_prediction
This Heart Disease Prediction System uses Python and Logistic Regression to predict heart disease based on age, sex, blood pressure, heart rate, and cholesterol. It uses Pandas, Scikit-learn, and Matplotlib for data processing, prediction, and visualization through a line chart.
##  Heart Disease Prediction System

### Overview of the project
This is a beginner-friendly Machine Learning project built in Python that predicts the likelihood of heart disease in a patient. It uses a **Logistic Regression** model trained on health data to classify whether a person is at risk, based on inputs provided by the user.

### Features
The user provides the following patient details:

- Age
- Sex
- Blood Pressure
- Heart Rate
- Cholesterol

The model is trained on `data.csv` and outputs:

- Presence of Heart Disease (YES/NO)
- Probability of Heart Disease

A line chart is also generated using Matplotlib to visualize the entered health parameters at a glance.

### Tools used
| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and preprocessing |
| Scikit-learn | Model building and prediction |
| Matplotlib | Data visualization |

## Files Required
- `code_heart.py`
- `data.csv`


## Installation
Install required libraries using:


pip install pandas scikit-learn matplotlib

###  Run the project

1. Open a terminal in the project folder.
2. Run the main script:
```bash
   python code_heart.py
```
3. Enter the requested patient details when prompted (age, sex, blood pressure, heart rate, cholesterol).
4. View the prediction output and the generated line chart.

###  Instructions for testing

1. **Basic functionality test**
   Run the script with sample values (e.g., Age: 55, Sex: Male, BP: 140, Heart Rate: 80, Cholesterol: 230) and confirm it returns a prediction (Yes/No) along with a probability score.

2. **Edge case testing**
   Try boundary values such as very low/high age, blood pressure, or cholesterol to check the model doesn't crash and still returns a reasonable output.

3. **Visualization check**
   Confirm that after each run, a line chart pops up correctly showing the entered health parameters.
