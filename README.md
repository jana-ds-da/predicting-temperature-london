# 🌦️ Predicting Temperature in London

A machine learning project focused on predicting temperature in London using historical weather data.

![London Tower Bridge](tower_bridge.jpeg)

## 📌 Project Overview

This project explores the use of machine learning to predict temperature based on historical weather data.

The project follows an end-to-end machine learning workflow, including data preprocessing, model training, evaluation, experiment tracking, data versioning, and model monitoring.

## 🎯 Project Goals

- Prepare and preprocess historical weather data.
- Build a machine learning model for temperature prediction.
- Evaluate model performance using appropriate metrics.
- Track experiments and model runs using MLflow.
- Version datasets and machine learning pipelines using DVC.
- Apply MLOps practices to make the workflow more reproducible and maintainable.

## 🛠️ Technologies & Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- MLflow
- DVC
- NannyML
- Docker
- Git & GitHub
- GitHub Actions
- CML

## 🔄 Machine Learning Workflow

The project follows these main steps:

1. **Data Preparation**
   - Load the weather dataset.
   - Clean and preprocess the data.
   - Prepare the data for machine learning.

2. **Model Training**
   - Train a machine learning model using the processed dataset.
   - Track experiments and model runs.

3. **Model Evaluation**
   - Evaluate the model using performance metrics.
   - Generate evaluation results and visualizations.

4. **Data & Pipeline Versioning**
   - Use DVC to version datasets and manage the ML pipeline.

5. **Experiment Tracking**
   - Use MLflow to track experiments, parameters, metrics, and models.

6. **Model Monitoring**
   - Use NannyML to monitor model performance and detect potential changes in production data.

7. **CI/CD**
   - Use GitHub Actions and CML to automate parts of the machine learning workflow.

## 📂 Project Structure


predicting-temperature-london/
│
├── raw_dataset/
├── processed_dataset/
├── train.py
├── preprocess_dataset.py
├── model.py
├── metrics_and_plots.py
├── utils_and_constants.py
├── dvc.yaml
├── dvc.lock
├── requirements.txt
├── metrics.json
├── confusion_matrix.png
├── tower_bridge.jpeg
└── README.md
