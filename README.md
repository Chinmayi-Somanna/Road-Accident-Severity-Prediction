# Road Accident Severity Prediction Using Machine Learning

## Project Overview

Road Accident Severity Prediction is a machine learning mini project that uses historical road accident data to classify accident severity categories.

The project implements Decision Tree and Random Forest classification algorithms and compares their performance using accuracy and macro F1-score.

An interactive interface built with Gradio allows users to enter accident-related information and obtain a predicted severity category.

## Objectives

- Analyse historical road accident data.
- Preprocess numerical and categorical features.
- Build machine learning classification models.
- Compare Decision Tree and Random Forest performance.
- Develop an interactive prediction interface.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Gradio
- Google Colab
- Kaggle dataset

## Machine Learning Algorithms

### 1. Decision Tree Classifier

A supervised machine learning algorithm that learns decision rules from training data to classify accident severity.

### 2. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to produce predictions.

## Project Workflow

1. Dataset collection from Kaggle.
2. Data inspection and preprocessing.
3. Feature selection and target identification.
4. Splitting data into training and testing sets.
5. Encoding categorical features and handling missing values.
6. Training Decision Tree and Random Forest models.
7. Evaluating and comparing model performance.
8. Developing an interactive interface using Gradio.

## Model Evaluation

The initial experimental results were:

| Model | Accuracy | Macro F1-score |
|---|---:|---:|
| Decision Tree | 75.56% | 0.4307 |
| Random Forest | 85.89% | 0.3080 |

These are initial results from the current implementation. Further evaluation is needed to examine performance across individual severity categories and check for possible data leakage.

## How to Run the Project

1. Open the Jupyter notebook in Google Colab.
2. Upload the required dataset.
3. Run the notebook cells in order.
4. Train the machine learning models.
5. Launch the Gradio interface.
6. Enter accident-related details to view a prediction.

## Project Files

- `Road_Accident_Severity_Prediction.ipynb` — Project implementation.
- `Road.csv` — Road accident dataset.
- `road_accident_decision_tree.pkl` — Saved Decision Tree pipeline.
- `model_comparison_results.csv` — Model comparison results.

The Random Forest model is not included in the repository yet because it exceeds GitHub's browser upload size limit.

## Limitations

- Predictions depend on the quality and representativeness of the dataset.
- Model accuracy may vary across severity categories.
- The predicted probabilities may not be calibrated.
- The model is intended for educational purposes and must not be used for real-world emergency or road-safety decisions.

## Author

Chinmayi Somanna

## Disclaimer

This project was developed for academic learning as part of a Machine Learning mini project. It is not a validated real-world accident severity assessment system.
