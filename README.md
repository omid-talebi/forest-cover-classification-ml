# Forest Cover Type Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Project Overview

This project is the **third Machine Learning Mini Project** focused on multiclass classification using the **Forest CoverType** dataset. The objective is to predict forest cover types based on topographic and environmental attributes while comparing the performance of multiple classification algorithms.

## 🎯 Objectives

- Explore and analyze the Forest CoverType dataset
- Perform data preprocessing and feature scaling
- Train and evaluate multiple classification models
- Compare model performance using several evaluation metrics
- Analyze bias-variance tradeoffs

## 🤖 Models Implemented

- K-Nearest Neighbors (KNN)
- Decision Tree
- Linear Discriminant Analysis (LDA)

## 📁 Project Structure

```text
forest-cover-classification/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── main.ipynb
├── data/
│   └── covtype.csv
├── reports/
│   └── report.pdf
```

## 🚀 How to Run

```bash
git clone https://github.com/omid-talebi/forest-cover-classification.git

cd forest-cover-classification

pip install -r requirements.txt

jupyter notebook main.ipynb
```

## 📊 Dataset

**Forest CoverType Dataset**

The dataset contains:

- 581,012 samples
- 54 input features
- 7 target classes
- Numerical and binary attributes describing topographic and environmental characteristics

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🏆 Model Comparison

The project compares the performance of:

| Model | Characteristics |
|-------|-----------------|
| KNN | Distance-based non-parametric classifier |
| Decision Tree | Interpretable tree-based classifier |
| LDA | Linear probabilistic classifier |

The comparison includes discussions of:

- Bias vs Variance
- Underfitting vs Overfitting
- Model capacity
- Validation performance

## 📄 Report

A detailed project report (written in Persian) is available in:

```
reports/report.pdf
```

> **Note:** The report is written in Persian as it was submitted for a university machine learning course. The source code and project documentation are provided in English.

## 🛠 Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for more information.