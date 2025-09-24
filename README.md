# Boston Housing Price Predictor 🏡

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Framework-Scikit--learn-orange" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Library-Pandas-lightgrey" alt="Pandas">
</p>

> A machine learning model developed to predict housing prices in Boston using linear regression. This project demonstrates a complete ML workflow from data exploration and preprocessing to model training, evaluation, and deployment.

---

## 📖 Project Overview

This project aims to solve the classic regression problem of predicting housing prices using the Boston Housing dataset. The primary goal is to build a reliable model that can estimate the median value of homes based on various socio-economic and geographical factors.

The `Dragon Real Estate.ipynb` notebook walks through the entire process, including data exploration, preprocessing with a Scikit-learn pipeline, model training, and evaluation. The final trained model is saved as `Dragon.joblib`.

The `Model Testing.ipynb` notebook shows how to load this saved model and use it to make predictions on new, unseen data.

---

## 🛠️ Tech Stack

| Technology | Description |
|---|---|
| **Python** | Core programming language for the project. |
| **Pandas & NumPy** | Used for data loading, manipulation, and analysis. |
| **Scikit-learn** | The primary library for building the regression model and preprocessing pipeline. |
| **Matplotlib** | For creating visualizations to understand data patterns. |
| **Jupyter Notebook** | For interactive development, analysis, and documentation. |
| **Joblib** | For serializing and deserializing the trained Python model. |

---



📂 Project Structure
.
├── Data.csv                # The dataset used for training
├── Dragon Real Estate.ipynb # Main notebook for data exploration and training
├── Dragon.joblib           # The final, saved machine learning model
├── housing.data            # Raw data file
├── housing.names           # Descriptions of the dataset attributes
├── Model Testing.ipynb     # Notebook demonstrating how to use the saved model
└── README.md               # Project summary and guide




## 🚀 Getting Started

To run this project on your local machine, follow these steps.

### Prerequisites

Make sure you have Python (3.7+) installed. You can install the required libraries using `pip`:
```sh
pip install pandas numpy scikit-learn matplotlib jupyterlab

git clone [https://github.com/YOUR_USERNAME/Dragon-Real-Estate-Predictor.git](https://github.com/YOUR_USERNAME/Dragon-Real-Estate-Predictor.git)
cd Dragon-Real-Estate-Predictor

jupyter notebook

