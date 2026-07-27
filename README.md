# Medical Insurance Cost Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Regression](https://img.shields.io/badge/Regression-Prediction-red)
![Data Science](https://img.shields.io/badge/Data-Science-purple)

This project explores the use of machine learning to predict individual medical insurance costs from demographic and health-related attributes. The objective was to investigate how different neural network architectures and training configurations influence regression performance on structured healthcare data.


![Correlation analysis](project_overview.png)


## Project Overview

This project investigates the use of supervised machine learning for predicting individual medical insurance costs from demographic and health-related information.

Rather than training a single model, the project explored multiple deep learning regression architectures and training strategies to evaluate how model complexity, optimization algorithms, and hyperparameter selection affect predictive performance.

The complete workflow included:

- Data preprocessing and cleaning
- Exploratory data analysis
- Feature encoding
- Correlation analysis
- Neural network model design
- Hyperparameter tuning
- Cross-validation
- Model comparison
- Regression performance evaluation

## Dataset

The model was trained using a public medical insurance dataset containing demographic and lifestyle information together with corresponding insurance charges.

Example features include:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

Target variable:

- Medical insurance charges

## Technologies

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```text
.
├── README.md
├── medical_insurance_cost_prediction.ipynb
└── insurance_dataset.csv
```
## My Contribution

This project was completed as part of a university Data Science and Artificial Intelligence course.

My primary contributions included:

- Data preprocessing and exploratory analysis
- Feature engineering and data preparation
- Designing and training regression models
- Comparing different neural network architectures
- Hyperparameter tuning
- Model evaluation using regression performance metrics
- Analyzing the effect of model architecture on prediction accuracy

The final model was selected based on its predictive performance and generalization ability.

## Future Improvements

- Compare deep learning models with traditional regression algorithms
- Perform automated hyperparameter optimization
- Investigate feature importance and explainability techniques
- Develop an interactive web interface for insurance cost prediction
- Evaluate additional healthcare datasets for improved generalization
  
## Disclaimer

This project was developed for educational purposes and should not be used for real-world insurance pricing or clinical decision-making.
