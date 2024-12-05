# Project Title

**Drug Classification Using SVM and Naive Bayes**

---

## Description

This project implements and evaluates Support Vector Machine (SVM) and Naive Bayes models for drug classification based on patient data. It provides insights into how these algorithms perform in terms of precision, recall, and F1 score. The dataset contains information about patient attributes such as age, sex, blood pressure, cholesterol levels, and drug prescriptions. 

The project includes Python code for preprocessing, training, testing, and evaluating the models, with a focus on enabling easy reproducibility.

---

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes. See the *Deployment* section for notes on how to deploy the project on a live system.

---

## Prerequisites

To get started, you need the following software installed:

- **Python 3.x**: Download and install from [python.org](https://www.python.org/).
- **Jupyter Notebook**: Install via pip or Anaconda.
- **Required Libraries**: Install using pip:
```bash
  pip install numpy pandas matplotlib scikit-learn
```
# Installing

Follow these steps to set up the project on your local machine:

**Step 1: Clone the Repository**
```bash
git clone https://github.com/Manav2304/drug-classification.git
```
**Step 2: Navigate to the Project Directory**
```bash
cd drug-classification
```
**Step 3: Launch Jupyter Notebook**
```bash
jupyter notebook```

***Step 4: Open the Notebook***

In Jupyter Notebook, open Drug_Classification.ipynb to start working with the project.

Running the Tests

The notebook includes end-to-end tests for the SVM and Naive Bayes models, from preprocessing the data to model evaluation.

***Example Test:***
```bash
from sklearn.svm import SVC
from sklearn.metrics import classification_report

model = SVC(kernel='linear', random_state=100)
model.fit(X_train_scaled, y_train)
predictions = model.predict(X_test_scaled)

print(classification_report(y_test, predictions))
```

You can run these tests within the Jupyter Notebook to verify the functionality of the classification models.

## Deployment
To deploy this project on a live system, consider converting the Jupyter Notebook into a standalone Python script or hosting it on a Jupyter Notebook server.

Use the following command to export the notebook as a Python script:

```bash
jupyter nbconvert --to script Drug_Classification.ipynb
```
## Built With

- **Python** - Programming Language
- **Jupyter Notebook** - Development Environment
- **Scikit-learn** - Machine Learning Library
- **Matplotlib** - Visualization Library

---

## Authors

- **Heli Patel** 

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Introduction to Data Analysis Subject** - For providing valuable Python materials and resources that greatly enhanced the understanding and implementation of the project.

