# Problem Statement

Heart disease is one of the leading causes of death worldwide, and early detection plays a critical role in preventing severe complications. Manual diagnosis often requires expert analysis of multiple health parameters, which can be time-consuming and inaccessible to everyone. There is a need for a simple, automated system that can quickly assess a patient's risk of heart disease based on basic health parameters, enabling early awareness and prompting timely medical consultation.

# Scope of the Project

This project focuses on building a basic Machine Learning-based prediction system that takes a set of patient health parameters as input and predicts the likelihood of heart disease using Logistic Regression.

The scope includes:
- Taking user-provided health parameters as input (Age, Sex, Blood Pressure, Heart Rate, Cholesterol)
- Training a Logistic Regression model on a sample dataset (`heart_dataset.csv`)
- Predicting whether the patient is likely to have heart disease (Yes/No)
- Displaying the probability/confidence of the prediction
- Visualizing the entered health parameters through a line chart

This project does **not** cover:
- Integration with real hospital databases or medical records
- Advanced models (e.g., Neural Networks, Random Forest, ensemble methods)
- A web or mobile application interface (currently a command-line based system)
- Clinical validation or deployment as a certified medical tool

# Target Users

- **Students and educators** — as a learning project to understand the basics of Machine Learning classification models
- **Beginners in Data Science/ML** — looking to understand a simple end-to-end ML pipeline (data preprocessing, training, prediction, visualization)
- **Healthcare enthusiasts** — interested in exploring how ML can be applied to healthcare-related problems
- **Academic evaluators** — reviewing this as a college/academic project submission

# High-Level Features

- **User Input System** — accepts patient health parameters via command-line prompts
- **Logistic Regression Model** — trained on a dataset to classify heart disease risk
- **Prediction Output** — displays whether heart disease is likely (Yes/No)
- **Probability Score** — shows the model's confidence in its prediction
- **Data Visualization** — generates a line chart of the entered health parameters using Matplotlib
- **Lightweight & Beginner-Friendly** — built using simple, widely-used Python libraries (Pandas, Scikit-learn, Matplotlib)
